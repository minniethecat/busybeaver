---
description: Statistical ranking of all entry pages by total cross-references, highlighting the most interconnected topics in Yarrow's mortuary customs survey.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["statistics", "index"]
type: list
---

This page ranks all non-chapter entry pages by their total number of cross-references within the wiki, surfacing the most interconnected topics in Yarrow's 1880 survey of Native American mortuary customs. High reference counts indicate topics that feature prominently across multiple tribes' burial descriptions.

::: query
type: NOT NULL
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
title: Top 50 Most Referenced Pages
:::
