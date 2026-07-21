---
description: Wiki entries ranked by the number of paragraph-number citations (PN) in each page — a measure of how deeply each topic is anchored in the source text of *Moribund Society and Anarchy*.
id: source-density
label: Source Density Index
tags: ["index", "statistics", "sources"]
type: list
---

The PN count per page measures how many specific passages from Jean Grave's text are cited in support of each entry. Pages with high PN counts draw from many locations in the source, indicating broad textual grounding. Pages with low PN counts may represent concepts mentioned only briefly or still awaiting deeper sourcing. This index helps readers and editors identify the most source-rich articles in the wiki.

## Top 100 by PN Count

::: query
display: table
fields: [label, type, quality, pn_count, prose_chars]
field_labels:
  label: Page
  type: Type
  quality: Quality
  pn_count: PN Citations
  prose_chars: Characters
sort: pn_count
order: desc
limit: 100
:::

## PN Density (Citations per 1000 Characters)

The ratio of PN citations to prose length reveals which pages pack the most source references per word — these are the most intensively cited entries.

::: query
display: table
fields: [label, type, quality, pn_count, prose_chars]
field_labels:
  label: Page
  type: Type
  quality: Quality
  pn_count: PN Citations
  prose_chars: Characters
sort: pn_count
order: desc
limit: 100
:::
