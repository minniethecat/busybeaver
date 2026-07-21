---
description: A dynamically ranked listing of the 50 most-cited pages in The Quest of the Silver Fleece wiki, ordered by total backlink references.
id: top-referenced
label: Most Referenced Pages
tags: ["index", "reference", "statistics"]
type: list
---

# Most Referenced Pages

This page lists the 50 most interconnected entries in *The Quest of the Silver Fleece* wiki,
ranked by the total number of other pages that reference them. High reference counts often
indicate central characters, recurring themes, or pivotal locations in the novel.

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Citations
sort: total_refs
order: desc
limit: 50
:::

## See Also

- [[complete-index|Complete A-Z Index]]
- [[featured-content|Featured Content]]
- [[concept-index|Concept Index]]
- [[person-index|Person Index]]
