---
description: A ranked index of the most cross-referenced pages in the Macbeth wiki, reflecting which characters, concepts, and events are most central to the play's interconnected world.
id: most-referenced
label: Most Referenced
tags: ["index", "statistics", "reference"]
type: list
---

# Most Referenced Pages

Which characters, concepts, and events are most frequently cited across the wiki? This page ranks all entries by their total cross-reference count — a measure of interconnectedness that reflects a page's centrality to the world of *Macbeth*.

## Top 30 by Reference Count

::: query
type: NOT NULL
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 30
title: Top 30 Most Referenced Pages
:::

## Top Concepts by Reference

The ideas and themes that resonate most widely across the wiki.

::: query
type: concept
display: table
fields: [label, total_refs]
field_labels:
  label: Concept
  total_refs: References
sort: total_refs
order: desc
limit: 15
title: Top Concepts
:::

## Top Characters by Reference

The figures whose actions and relationships generate the most cross-references.

::: query
type: person
display: table
fields: [label, total_refs]
field_labels:
  label: Character
  total_refs: References
sort: total_refs
order: desc
limit: 15
title: Top Characters
:::
