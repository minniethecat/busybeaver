---
description: Statistical ranking of the most-referenced pages in the His Family wiki, sorted by total backlink count.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "navigation", "statistics"]
type: list
---

# Most Referenced Pages

This page ranks all entry pages in the *His Family* wiki by their total reference count — a measure of how extensively each topic is discussed across the wiki. Pages with more references are typically central to the novel's narrative and themes.

::: query
sort: total_refs
order: desc
limit: 50
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
:::

## About This Ranking

The reference count is computed automatically from wikilinks across the wiki. A higher count indicates the topic is referenced from many other pages, reflecting its centrality to the novel's world. This page updates dynamically as new pages are added and linked.
