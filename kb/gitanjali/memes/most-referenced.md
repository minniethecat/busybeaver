---
description: A dynamic ranking of the most-referenced pages in 1366-Gitanjali — a statistical view of which concepts, persons, places, and works form the connective tissue of the wiki's link network.
id: most-referenced
label: Most Referenced Pages
tags: []
type: list
---

# Most Referenced Pages

This page shows the 50 most-referenced pages across the entire wiki, ranked by how many other pages link to them. This statistical view reveals the conceptual backbone of Tagore's Gitanjali — the ideas, figures, and places that recur most frequently across the poem cycle.

## Top 50 by Reference Count

::: query
type_any: [concept, person, place, work]
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::

## Notes

- The table is dynamically generated from the wiki's link network
- `References` is the total number of inbound wikilinks from other pages
- This ranking reflects the wiki's internal link structure, not external search popularity
- Pages with high reference counts serve as natural hub nodes in the wiki's knowledge graph
