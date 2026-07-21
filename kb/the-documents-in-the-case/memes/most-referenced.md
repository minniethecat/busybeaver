---
description: The most cross-referenced pages in the wiki, ranked by total backlink count.
id: most-referenced
label: Most Referenced Pages
tags: ["index", "statistics", "reference"]
type: list
---

# Most Referenced Pages

Pages most frequently cited across the wiki, ranked by cross-reference count. These represent the central nodes of the case's information network.

::: query
type: person
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 25
title: Top 25 Persons by References
:::

::: query
type: evidence
display: table
fields: [label, type, total_refs]
field_labels:
  label: Document
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 15
title: Top 15 Evidence Documents by References
:::

::: query
type: event
display: table
fields: [label, type, total_refs]
field_labels:
  label: Event
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 15
title: Top 15 Events by References
:::

## About This Page

Reference counts reflect how often a page is linked from other wiki entries — a proxy for its centrality to the case narrative. These rankings are dynamic and update as the wiki grows.
