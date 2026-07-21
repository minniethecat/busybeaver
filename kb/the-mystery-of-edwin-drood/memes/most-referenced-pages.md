---
description: Cross-type ranking of the most-cited wiki pages across The Mystery of Edwin Drood, ordered by total paragraph references.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "ranking", "statistics"]
type: list
---

# Most Referenced Pages

A cross-type ranking of the most-referenced wiki pages in *The Mystery of Edwin Drood*.
Citation counts reflect the number of paragraph-level references (`PN` blocks) linking to each page across all 23 chapters.

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Citations
sort: total_refs
order: desc
limit: 50
:::

## About This Ranking

This ranking is automatically generated and updated as new pages are added or existing pages gain new citations. It provides a quick view of which entities, places, events, and concepts are most frequently referenced across Dickens' unfinished novel — a proxy measure of narrative significance.
