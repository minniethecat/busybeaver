---
description: Pages ranked by how many chapters they touch — a measure of narrative breadth, showing which characters, places, and events span the Doctor's full journey.
id: narrative-span
label: Narrative Span
tags: ["index", "chapters", "narrative", "statistics"]
type: list
---

# Narrative Span

Some pages tell of a single moment; others thread through the entire story. The `total_chapters` metric counts how many of the book's twenty-one chapters reference each entry — a window into which characters, places, and events are woven most deeply into [[john-dolittle|the Doctor]]'s [[travel-and-exploration|adventure]].

## Widest Narrative Span

Pages that appear across the most chapters, from [[puddleby-on-the-marsh|Puddleby]] to [[africa-expedition|Africa]] and back.

::: query
display: table
fields: [label, type, total_chapters, total_refs]
field_labels:
  label: Page
  type: Type
  total_chapters: Chapters
  total_refs: References
sort: total_chapters
order: desc
limit: 30
title: Pages by Chapter Span
:::

## Full Chapter Span Index

Every entry ordered by narrative breadth.

::: query
display: table
fields: [label, type, total_chapters, total_refs]
field_labels:
  label: Page
  type: Type
  total_chapters: Chapters
  total_refs: References
sort: total_chapters
order: desc
title: All Entries by Chapter Span
:::
