<div align="center">

# 📚 BusyBeaver Catalog

*Every book memified so far, with its Memes ready for your agent.*

</div>

---

## Books

| Book | Author | Language | Year | Memes | Wiki |
| --- | --- | --- | --- | --- | --- |
| **红楼梦** (Dream of the Red Chamber) | 曹雪芹 Cao Xueqin | 简体中文 | 1791 | 3,897 | [`kb/honglou/`](./kb/honglou/) |
| **The Picture of Dorian Gray** | Oscar Wilde | English | 1890 | 452 | [`kb/the-picture-of-dorian-gray/`](./kb/the-picture-of-dorian-gray/) |
| **Common Sense** | Baron d'Holbach | English | 1772 | 617 | [`kb/common-sense/`](./kb/common-sense/) |
| **Letters to His Son** | Lord Chesterfield | English | 1774 | 497 | [`kb/letters-to-his-son/`](./kb/letters-to-his-son/) |
| **Aesop's Fables** | Aesop | English | 6th cent. BCE | 479 | [`kb/aesops-fables/`](./kb/aesops-fables/) |
| **Le Morte d'Arthur** | Sir Thomas Malory | English | 1485 | 453 | [`kb/le-morte-darthur/`](./kb/le-morte-darthur/) |
| **Olney Hymns** | William Cowper & John Newton | English | 1779 | 453 | [`kb/olney-hymns/`](./kb/olney-hymns/) |
| **Moby-Dick** | Herman Melville | English | 1851 | 411 | [`kb/moby-dick/`](./kb/moby-dick/) |
| **A Vindication of the Rights of Woman** | Mary Wollstonecraft | English | 1792 | 364 | [`kb/a-vindication-of-the-rights-of-woman/`](./kb/a-vindication-of-the-rights-of-woman/) |
| **Industrial Biography** | Samuel Smiles | English | 1863 | 353 | [`kb/industrial-biography/`](./kb/industrial-biography/) |
| **Metamorphoses** | Ovid | English | 8 CE | 344 | [`kb/metamorphoses/`](./kb/metamorphoses/) |
| **Choice Specimens of American Literature** | Various (anthology) | English | 1871 | 335 | [`kb/choice-specimens-of-american-literature/`](./kb/choice-specimens-of-american-literature/) |
| **Daniel Deronda** | George Eliot | English | 1876 | 331 | [`kb/daniel-deronda/`](./kb/daniel-deronda/) |
| **Dombey and Son** | Charles Dickens | English | 1848 | 331 | [`kb/dombey-and-son/`](./kb/dombey-and-son/) |
| **A Popular History of Ireland** | Thomas D'Arcy McGee | English | 1863 | 324 | [`kb/a-popular-history-of-ireland/`](./kb/a-popular-history-of-ireland/) |
| **Alarms and Discursions** | G. K. Chesterton | English | 1910 | 314 | [`kb/alarms-and-discursions/`](./kb/alarms-and-discursions/) |
| **The Philosophical Works of Descartes** | René Descartes | English | 1637–1649 | 307 | [`kb/philosophical-works/`](./kb/philosophical-works/) |

**Totals:** 17 books · 10,262 Memes

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

Memes are typed so you can slice a book by what you need. Every book uses this core set:

| Type | Meaning |
| --- | --- |
| `quote` | A source-anchored passage worth citing on its own |
| `concept` | An idea, theme, or motif running through the work |
| `person` | A character or real person |
| `chapter` | A chapter, with full text and paragraph numbers (PN) for citation |
| `event` | Something that happens in the narrative |
| `organization` | A group, institution, or collective |
| `overview` | Orientation pages (`About`, `TOC`) |

Books also carry types specific to what they are *about* — *红楼梦*, for instance, adds `poem`, `food`, `clothing`, `plant`, `medicine`, `ritual`, and `game`, because those are the texture of the novel. Read a book's `index.json` for its own type inventory rather than assuming a fixed vocabulary.

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
