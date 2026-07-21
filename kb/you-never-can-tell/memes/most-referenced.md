---
description: Pages in You Never Can Tell wiki ranked by total backlink count — a proxy for centrality and reader interest.
id: most-referenced
label: Most Referenced
tags: ["index", "statistics"]
type: list
---

# Most Referenced

Pages ranked by how often they are referenced from other pages in this wiki.
Backlink count serves as a rough measure of each entity's narrative centrality and cross-page relevance.

## Top 20 by References

::: query
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 20
:::

## Notes

This page is dynamically generated — the ranking updates automatically whenever backlinks are rebuilt.
Pages of type `chapter`, `overview`, and `list` are excluded from this view.
