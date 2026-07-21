<div align="center">

# 📚 BusyBeaver Catalog

*Every book memified so far, with its Memes ready for your agent.*

</div>

---

## Books

| Book | Author | Language | Memes | Wiki |
| --- | --- | --- | --- | --- |
| **The Picture of Dorian Gray** | Oscar Wilde | English | 452 | [`kb/the-picture-of-dorian-gray/`](./kb/the-picture-of-dorian-gray/) |

**Totals:** 1 book · 452 Memes

---

## How the catalog is organized

Each book lives under `kb/<book-slug>/`:

```
kb/<book-slug>/
├── index.json      # machine-readable manifest: every Meme's id, type, label,
│                   # description, aliases, tags, quality grade, source_ref, relations
└── memes/          # one Markdown file per Meme
    ├── About.md    # what this book's wiki covers
    ├── TOC.md      # table of contents
    └── <slug>.md   # the Memes themselves
```

**Start with `index.json`.** It is the fastest way for an agent to see everything a book contains without reading 450 files — each entry carries the Meme's type, quality grade, and its `relations` to other Memes.

### Meme types

Memes are typed so you can slice a book by what you need:

| Type | Meaning |
| --- | --- |
| `quote` | A source-anchored passage worth citing on its own |
| `concept` | An idea, theme, or motif running through the work |
| `person` | A character or real person |
| `chapter` | A chapter, with full text and paragraph numbers (PN) for citation |
| `location` | A place |
| `event` | Something that happens in the narrative |
| `organization` | A group, institution, or collective |
| `overview` | Orientation pages (`About`, `TOC`) |

### Quality grades

Every Meme carries a grade — `stub` → `basic` → `standard` → `featured` → `premium` — so you can filter for depth before you spend tokens on it.

---

## Scope

This public catalog contains **only books free of copyright** (public domain). See [Copyright & scope](./README.md#copyright--scope) in the README.

Want a classic prioritized? Open an issue, or see [Request a book](./README.md#-request-a-book).

---

<div align="center">

*Give every piece of knowledge an address.*

</div>
