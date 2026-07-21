---
id: most-referenced-pages
label: Most Referenced Pages
type: list
description: Ranking of the 50 most referenced entry pages in the wiki — a statistical view of which concepts, persons, and themes form the densest nodes in Holbach's Common Sense knowledge network.
tags: ["index", "list", "statistics", "ranking", "popular"]
---

# Most Referenced Pages

This page presents the 50 most cross-referenced entry pages in the wiki, ranked by total backlink count. These pages represent the densest conceptual nodes in Holbach's *Common Sense* — the ideas, figures, and [[eve]]nts that other pages most frequently invoke. The ran[[monarch|king]] is computed automatically from wiki backlink data and requires no manual curation.

High backlink counts typically indicate either a foundational concept (e.g., [[god]], [[nature]], [[reason]]) or a frequently mentioned figure or institution that recurs across many chapters and page types. The table below is rendered dynamically.

::: query
sort: total_refs
order: desc
limit: 50
display: table
fields: [label, type, quality, total_refs, pn_count]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
  pn_count: Citations
title: Top 50 Most Referenced Pages
:::
