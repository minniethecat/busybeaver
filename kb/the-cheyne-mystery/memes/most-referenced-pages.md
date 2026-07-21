---
description: Statistical ranking of the most cross-referenced entries in The Cheyne Mystery wiki, by total backlink count.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "statistics", "rankings"]
type: list
---

# Most Referenced Pages

This page ranks wiki entries by how frequently they are referenced from other pages — a proxy for their narrative importance in *The Cheyne Mystery*. The ranking is dynamically computed from the wiki's backlink index and updates automatically as new pages and wikilinks are added.

## Top 30 by References

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
limit: 30
:::

## Featured Content

::: query
quality: featured
display: list
sort: label
order: asc
title: Featured Pages
:::
