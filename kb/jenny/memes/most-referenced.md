---
description: Statistical ranking of the most frequently referenced pages across all entity types in Jenny
id: most-referenced
label: Most Referenced
tags: ["list", "ranking", "statistics"]
type: list
---

# Most Referenced Pages

This page provides a dynamically-generated ranking of the most frequently cross-referenced pages in the *Jenny* wiki.
Higher reference counts indicate entities central to the novel's narrative and thematic fabric.
This list updates automatically as pages are enriched with new wikilinks.

## Top 50 by Reference Count

::: query
type: NOT chapter
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

Reference counts are derived from the `total_refs` engine-computed field, which tallies every `[[wikilink]]`
targeting a given page. Chapter pages are excluded from this view.
