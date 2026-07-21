---
description: The most interconnected pages in The Adventures of Sally wiki, ranked by total cross-reference count — showing which entities are most central to the novel's world.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "ranking", "reference"]
type: list
---

# Most Referenced Pages

Which people, places, and concepts are most central to the world of *The Adventures of Sally*? This page answers that question by ranking all entries by their **total reference count** — the number of times other wiki pages link to them. Higher counts indicate greater narrative importance and interconnectedness.

::: query
sort: total_refs
order: desc
limit: 25
display: table
fields: [label, type, total_refs, total_chapters]
field_labels:
  label: Entry
  type: Type
  total_refs: Total Refs
  total_chapters: Chapters
:::

## Reading the Rankings

Reference counts are computed automatically from wikilinks between pages. A high count means many other entries reference this one — a reliable signal of narrative centrality. The chapter count shows how widely distributed those references are across the novel's 23 chapters, distinguishing deep-but-narrow entities from those woven throughout the entire story.
