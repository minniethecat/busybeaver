---
description: The top 20 most referenced pages in the wiki, ranked by total cross-reference count. Reflects the most interconnected topics in the North Wind universe.
id: most-referenced
label: Most Referenced Pages
tags: ["index", "statistics"]
type: list
---

# Most Referenced Pages

The top 20 most referenced entries in the wiki, sorted by the total number of cross-references (wikilinks pointing to each page). These are the most interconnected topics in George MacDonald's *At the Back of [[north-wind|the North Wind]]*.

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 20
:::
