---
description: Statistical ranking of the most-referenced entry pages in the Romola wiki, ordered by total cross-references.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "ranking", "statistics"]
type: list
---

# Most Referenced Pages

This page ranks all entry pages in the Romola wiki by their total number of cross-references,
showing which characters, places, and concepts are most interconnected.

::: query
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 50
title: Most Referenced Pages (Top 50)
:::
