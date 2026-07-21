# Purple Number (PN) Format Specification

> **Version**: 1
> **Status**: Draft

Purple Numbers (PN) are the canonical citation system used across all Memex-wiki sourced books in the BusyBeaver knowledge base. This document defines the PN format, how PNs appear in book content, and how consumers can use them.

---

## 1. What is a Purple Number?

A Purple Number (PN) is a **stable, permanent identifier** assigned to each paragraph (or block element) in a source text. Once assigned, a PN is **never reused** — if a paragraph is deleted, its PN is retired permanently. This guarantees that a citation like `(021-164)` always refers to the same paragraph, regardless of edition, translation, or reformatting.

The name "Purple Number" honors **Douglas Engelbart**, who introduced the concept in his 1960s NLS system as a way to assign uniquely addressable IDs to every paragraph in a document. The visual rendering in Memex wikis uses a light purple color (`#7B1FA2`), hence the name.

### Key Properties

| Property | Description |
|----------|-------------|
| **Stable** | A PN never changes after assignment |
| **Permanent** | Deleted PNs are never reassigned |
| **Precise** | Each PN addresses one specific paragraph |
| **Portable** | Same PN works across editions, languages, and formats |

---

## 2. PN Format

### 2.1 Basic Format: `NNN-PPP`

```
NNN-PPP
```

| Segment | Width | Description | Examples |
|---------|-------|-------------|----------|
| `NNN` | 3–4 digits/letters | Chapter identifier, zero-padded (001–999, then 1000+) | `001`, `021`, `P01` |
| `PPP` | 3–4 digits | Paragraph number within the chapter, starting at 001 | `001`, `043`, `1000` |

- Segments are separated by a **single hyphen** (`-`)
- Chapters using letter prefixes: `P01`, `P02` for prologues/prefaces
- Paragraph count exceeding 999 extends to 4 digits (e.g., `033-1000`)

**Examples from published books**:

| PN | Meaning |
|----|---------|
| `001-001` | Chapter 1, paragraph 1 |
| `021-164` | Chapter 21, paragraph 164 (AIMA: Stochastic Gradient Descent) |
| `009-039` | Chapter 9, paragraph 39 (Dorian Gray: friendship passage) |
| `P01-005` | Prologue 1, paragraph 5 |

### 2.2 Three-Segment Format: `VVV-NNN-PPP`

For multi-volume works, a volume prefix is prepended:

```
VVV-NNN-PPP
```

| Segment | Width | Description | Examples |
|---------|-------|-------------|----------|
| `VVV` | 1–4 chars | Volume identifier | `GEN`, `BH`, `PS`, `PHIL`, `V01` |
| `NNN` | 3–4 digits/letters | Chapter number (may include letter prefix) | `001`, `P03`, `A01` |
| `PPP` | 3–4 digits | Paragraph number (may include letter prefix) | `001`, `A01` |

Example: `GEN-001-005` = Genesis, chapter 1, paragraph 5.

### 2.3 Sub-paragraph Format: `NNN-PPP-SSS`

When a long paragraph is split into multiple semantically related sub-paragraphs:

```
NNN-PPP-SSS
```

Example: `005-042-001`, `005-042-002` — two sub-paragraphs of the same parent paragraph 42 in chapter 5.

---

## 3. PN in Content

### 3.1 Inline Citation Syntax

Purple Numbers appear in book content as inline citations within parentheses. The parenthesis style follows the language convention of the book:

| Language | Style | Example |
|----------|-------|---------|
| **English** | Half-width parentheses | `(021-164)` |
| **Chinese** | Full-width parentheses | `（056-009）` |

These citations appear inline in the Markdown body, typically at the end of a sentence, clause, or passage that references a specific source paragraph.

**Example (English)**:

> "Your friendship is dearer to me than any fame or reputation" (009-039)

**Example (Chinese)**:

> 宝玉听了，喜之不尽，乃说道："我来的不巧了！"（056-009）

### 3.2 Source Paragraph Markers

In the source wikis (not in the dump output), each paragraph is prefixed with its PN in square brackets:

```markdown
[021-164] Stochastic gradient descent (SGD) is an iterative optimization algorithm…
```

These markers are **not** included in the `memes/*.md` dump files or in the `content` field of the index — they are a source-format artifact. The dump only contains inline citations.

### 3.3 Paragraph-Level Citation vs. Page-Level Citation

PNs operate at the **paragraph level**, much finer than conventional page-number citations. A single wiki page (one Meme) may contain dozens of inline PN citations, each pointing to a specific paragraph in the source text.

---

## 4. PN in book.json

The `meme_count` field in `index.json` counts all Memes in the book. The total PN count is typically much larger, since each Meme may contain multiple inline PN citations.

PN-related metadata is not stored as a separate field in the MemeIndex — PNs appear naturally as part of the Markdown content in `memes/*.md`. Consumers who need to index or query by PN should parse them from the content using the format rules in §2.

---

## 5. Regular Expression Reference

For consumers who need to extract or validate PNs from book content:

### English (half-width parentheses)

```
\((\w+-\w+)\)
```

### Chinese (full-width parentheses)

```
（(\w+-\w+)）
```

### PN Validation (all variants)

```
^[A-Za-z0-9]{1,4}-[A-Za-z0-9]{1,4}(-[A-Za-z0-9]{1,4})?$
```

### Known PN Patterns in Published Books

| Pattern | Book | Example |
|---------|------|---------|
| `\d{3}-\d{3}` | Standard two-segment | `021-164` |
| `P\d{2}-\d{3}` | Prologue chapter | `P01-005` |
| `[A-Z]{2,4}-\d{3}-\d{3}` | Multi-volume (Bible) | `GEN-001-005` |
| `\d{3}-\d{3}-\d{3}` | Sub-paragraph reference | `005-042-001` |

---

## 6. Consumer Guidance

### For AI Agents

- PN citations in content are **referential links** — they point to related paragraphs in the source text, not to other Memes in the same book.
- To resolve a PN, look for the corresponding chapter and paragraph in the source text (which may or may not be part of this book's Meme set).
- PNs enable **precise cross-referencing**: when an agent encounters `(021-164)` it knows the cited passage lies in chapter 21, paragraph 164 of the original work.

### For Human Readers

- PNs are visible in the Markdown files as parenthesized codes like `(021-164)`.
- They function like scholarly footnotes or hyperlinks, pointing to the exact source of a claim or reference.
- The stability guarantee means a PN cited today will point to the same text in perpetuity.

---

## 7. Future Extensions

| Feature | Status |
|---------|--------|
| Resolvable PN URLs (e.g., `https://busybeaver.dev/pn/021-164`) | Under consideration |
| Cross-book PN resolution (resolve a PN from any book against its source) | Under consideration |
| PN range syntax (e.g., `(021-164–021-170)`) | Under consideration |
