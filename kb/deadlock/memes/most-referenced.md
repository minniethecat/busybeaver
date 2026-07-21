---
description: Ranking of all entry pages in the Deadlock wiki by total reference count, revealing the most central entities in the link network.
id: most-referenced
label: Most Referenced Pages
tags: ["index", "statistics", "ranking"]
type: list
---

# Most Referenced Pages

This page ranks all entry pages in the *Deadlock* wiki by the number of incoming references (backlinks). Pages with more references are more deeply woven into the wiki's link network, indicating their centrality to the novel's world. This ranking is updated automatically as the wiki grows.

## Top 50 by References

::: query
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
limit: 50
title: Most Referenced Pages (Top 50)
:::

## Notes

- The reference count (`total_refs`) is computed from the wiki's backlink index and updates automatically when new pages are added or linked.
- Chapter pages and list/index pages are excluded from this ranking.
- The `quality` column reflects each page's current quality grade: stub, basic, standard, featured, or premium.
