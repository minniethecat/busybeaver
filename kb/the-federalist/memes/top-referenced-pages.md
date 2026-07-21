---
description: A ranked listing of the most referenced (linked-to) pages across this wiki, providing a measure of centrality and importance within The Federalist Papers knowledge graph.
id: top-referenced-pages
label: Top Referenced Pages
tags: ["index", "statistics", "references"]
type: list
---

# Top Referenced Pages

This page ranks all wiki entries by their total reference count — the number of other pages
that link to them via `[[wikilinks]]`. A high reference count indicates a concept, person,
or event that is central to the constitutional arguments in The Federalist Papers.

The ranking serves as a proxy for importance and connectivity within the knowledge graph.

::: query
display: table
fields: [label, type, quality, total_refs, total_chapters]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Total References
  total_chapters: Chapters
sort: total_refs
order: desc
limit: 50
title: Most Referenced Pages (Top 50)
:::
