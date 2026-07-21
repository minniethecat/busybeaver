---
description: The most frequently referenced pages across the Shepherds of the Wild wiki, ranked by total wikilink references.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "statistics", "reference"]
type: list
---

# Most Referenced Pages

This page ranks wiki entries by how often they are referenced from other pages — a proxy for their centrality in the *Shepherds of the Wild* knowledge graph.

::: query
type: NOT chapter
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 50
title: Top 50 Most Referenced Pages
:::
