---
description: A ranked listing of the fifty most-referenced entity pages in The Mirror of the Sea knowledge base, ordered by total backlink count across all pages.
id: most-referenced-entities
label: Most Referenced Entities
tags: ["index", "statistics", "reference"]
type: list
---

# Most Referenced Entities

This page ranks all entity pages in *The Mirror of the Sea* knowledge base by reference count. High reference counts indicate concepts, persons, and places that recur throughout Conrad's memoir — these are the threads that bind the work together.

## Top 50 by Reference Count

::: query
type: concept
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Entity
  type: Type
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::
