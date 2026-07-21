---
description: Pages in the King Lear wiki ranked by number of incoming references
id: top-cited-pages
label: Top Cited Pages
tags: ["index", "ranking", "reference"]
type: list
---

# Top Cited Pages

The most frequently referenced pages in the King Lear wiki, ranked by total incoming links from other pages. High citation counts indicate pages that are central to the wiki's interconnected network of knowledge — key characters, recurring themes, and pivotal events.

::: query
sort: total_refs
order: desc
limit: 40
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Citations
:::

## About This Ranking

Citation counts are drawn from the wiki's automatic backlink system. A page earns a citation whenever another page links to it with `[[wikilink]]` syntax. The count reflects how often editors and the butler system have found the page relevant to other topics, making it a useful proxy for the page's centrality to the wiki's knowledge graph.
