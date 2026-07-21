---
id: concept-citations
label: Concept Citations
type: list
description: The 50 most cross-referenced concept pages in the wiki, ranked by total backlink count — revealing which philosophical and theological ideas from Holbach's Common Sense form the densest nodes in the knowledge network.
tags: ["index", "list", "concept", "ranking", "citations"]
---

# Concept Citations

This page ranks the 50 most cross-referenced concept entries by total backlink count. [[concept-index|Concepts]] are the dominant page type in this wiki, covering philosophical ideas, [[doctrine|theological doctrine]]s, and analytical categories from Holbach's materialist critique of religion.

The ran[[monarch|king]] below reveals which concepts other pages most frequently invoke — a measure of their centrality to the Enlightenment argument of *Common Sense*.

::: query
type: concept
sort: total_refs
order: desc
limit: 50
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: References
title: Top 50 Concepts by Reference Count
:::
