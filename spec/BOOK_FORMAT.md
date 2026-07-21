# BusyBeaver Book Format Specification

> **Version**: 1
> **Status**: Draft

This document describes the canonical format of a **book** in the BusyBeaver knowledge base. Every book published in this repository conforms to this specification.

---

## 1. Directory Layout

Each book lives in its own directory named after its `book` identifier:

```
busybeaver/
├── <book-id>/                  # e.g. "plato", "aristotle", "bible"
│   ├── memes/                  # One .md file per Meme, browsable on GitHub
│   │   ├── socrates.md
│   │   ├── allegory-of-the-cave.md
│   │   └── ...
│   └── index.json               # Book metadata + lightweight Meme index
├── <another-book>/
│   ├── memes/
│   └── index.json
└── README.md
```

### Example

```
busybeaver/
├── plato/
│   ├── memes/
│   │   ├── socrates.md
│   │   ├── allegory-of-the-cave.md
│   │   ├── theory-of-forms.md
│   │   └── ... (N files)
│   └── index.json
├── aristotle/
│   ├── memes/
│   │   ├── aristotle.md
│   │   ├── nicomachean-ethics.md
│   │   ├── four-causes.md
│   │   └── ...
│   └── index.json
└── README.md
```

---

## 2. Glossary

| Term | Definition |
|------|------------|
| **Book** | A collection of Memes sharing a common source or theme. Each book maps to one directory. |
| **Meme** | The fundamental unit of knowledge — one semantic fragment, roughly equivalent to one wiki page. |
| **index.json** | Metadata file containing book-level info and a lightweight index of all Memes (without full content). |

---

## 3. `memes/*.md` — Browsable Meme Files

Each `.md` file is one Meme, directly readable on GitHub.

### Format (simplified frontmatter)

```markdown
---
id: socrates
label: Socrates
type: person
description: Classical Greek philosopher who founded Western philosophy, mentor of Plato
tags: [Greek philosophy, Athens, classical]
---

Full body content in Markdown.
```

### Rules

| Rule | Description |
|------|-------------|
| **Fields** | Only `id`, `label`, `type`, `description`, `tags` appear in the frontmatter. |
| **Full content** | The body is the complete Markdown content, identical to the source. No truncation. |
| **Filename** | `<id>.md`, where `id` matches the `id` field in `index.json` |
| **Encoding** | UTF-8 |

---

## 4. `index.json` — Book Metadata

### 4.1 Top-level Structure

```json
{
  "book": "plato",
  "title": "Plato's Republic & Dialogues",
  "description": "A knowledge base of Plato's works — the foundational texts of Western philosophy, built for AI agents",
  "language": "en",
  "generated": "2026-07-21",
  "version": 1,
  "meme_count": 1200,
  "memes": [
    …
  ]
}
```

### 4.2 Top-level Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `book` | string | ✓ | Book identifier, used as directory name and namespace for `source_ref` |
| `title` | string | ✓ | Human-readable book title |
| `description` | string | | One-sentence description of the book |
| `language` | string | ✓ | Primary language of the content (BCP 47 code, e.g. `en`, `zh-CN`, `ja`) |
| `generated` | string | ✓ | ISO 8601 date when this dump was generated (`YYYY-MM-DD`) |
| `version` | int | ✓ | Monotonically increasing dump version number |
| `meme_count` | int | ✓ | Number of Memes in this book |
| `memes` | array | ✓ | Lightweight Meme index (see §4.3) |

### 4.3 MemeIndex Entry

The `memes` array contains a **lightweight index** of all Memes. Each entry includes metadata and relations but **not** the full `content` body. Agents use this index for search and filtering, and read the full content from `memes/<id>.md` when needed.

```json
{
  "id": "socrates",
  "type": "person",
  "label": "Socrates",
  "description": "Classical Greek philosopher who founded Western philosophy, mentor of Plato",
  "aliases": ["Socrates of Athens", "Σωκράτης"],
  "tags": ["Greek philosophy", "Athens", "classical"],
  "quality": "premium",
  "source_ref": "plato:socrates",
  "relations": [
    {"type": "related", "target": "plato", "label": "Plato"},
    {"type": "related", "target": "allegory-of-the-cave", "label": "Allegory of the Cave"},
    {"type": "related", "target": "socratic-method", "label": "Socratic method"}
  ]
}
```

### 4.4 MemeIndex Fields

| Field | Type | Required | Source | Description |
|-------|------|----------|--------|-------------|
| `id` | string | ✓ | Page slug / filename | Globally unique within this book |
| `type` | string | ✓ | Page frontmatter | Page category (`person`, `concept`, `event`, `organization`, …) |
| `label` | string | ✓ | Page frontmatter | Display name |
| `description` | string | | Page frontmatter | One-sentence summary |
| `aliases` | string[] | | Page frontmatter | Alternative names / aliases |
| `tags` | string[] | | Page frontmatter | Tags |
| `quality` | string | | Page frontmatter | Quality level (`stub`, `standard`, `featured`, `premium`, …) |
| `source_ref` | string | ✓ | Computed | `"<book-id>:<slug>"` — traces back to the source page |
| `relations` | Relation[] | | Extracted from wikilinks | Semantic links to other Memes |

### 4.5 Relation Structure

```json
{
  "type": "related",
  "target": "plato",
  "label": "Plato"
}
```

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | ✓ | Relationship type. Currently only `related`; may be extended to `supports`, `contradicts`, `elaborates`, etc. |
| `target` | string | ✓ | Target Meme `id` (within the same book) |
| `label` | string | | Human-readable link text |

### 4.6 Relation Extraction Rules

1. Parse `[[target]]` and `[[target|display]]` wikilinks from the page body
2. Validate that the target exists in the book's page registry
3. Invalid / dead wikilinks are **silently skipped**
4. For prefixed wikilinks (e.g. `[[ref:spec/something]]`), strip the prefix and use only the slug
5. Deduplicate: only one relation per `(source, target)` pair

---

## 5. Packaging

Books in the BusyBeaver repository are stored as plain files in a Git repository — no special packaging is required.

For distribution, the entire repository can be cloned, or individual book directories can be downloaded separately.

### ZIP Bundles (Optional)

Bundles may be distributed as ZIP archives in object storage (GitHub Releases, S3, R2, etc.) with the naming convention:

```
<book-id>-<version>-<generated>.zip
```

Example: `plato-1-2026-07-21.zip`

The ZIP contains the same structure as the Git checkout:

```
plato-1-2026-07-21.zip
└── plato/
    ├── memes/
    └── index.json
```

---

## 6. Conventions

### Language Codes

All `language` fields use [BCP 47](https://tools.ietf.org/rfc/bcp/bcp47.txt) tags:

| Code | Language |
|------|----------|
| `en` | English |
| `zh-CN` | Chinese (Simplified, mainland China) |
| `ja` | Japanese |
| `fr` | French |
| `de` | German |
| `es` | Spanish |

### Quality Levels

The following quality levels are used (from lowest to highest):

| Level | Meaning |
|-------|---------|
| `stub` | Minimal content, needs expansion |
| `standard` | Adequate coverage |
| `featured` | Well-developed, substantial |
| `premium` | Thoroughly researched and polished |

---

## 7. Future Extensions

| Feature | Status |
|---------|--------|
| Cross-book relations (`target: "another-book:slug"`) | Under consideration |
| Extended relation types (`supports`, `contradicts`, `elaborates`) | Under consideration |
| Incremental dumps | Future |
