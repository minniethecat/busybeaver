---
id: person-index
label: Person Index
type: list
description: Alphabetical index of all person entries in the wiki — historical figures, philosophers, theologians, and biblical characters discussed in Holbach's Common Sense and its intellectual milieu.
tags: ["index", "list", "person", "people"]
---

# Person Index

This page aggregates all person entries in the wiki through a dynamic query block. Each person below is discussed either directly in Holbach's *Common Sense* or in the surrounding intellectual context of the Enlightenment critique of religion. The table is rendered automatically from page frontmatter — no manual list maintenance is required.

::: query
type: person
display: table
fields: [label, quality, total_refs, pn_count]
field_labels:
  label: Name
  quality: Quality
  total_refs: References
  pn_count: Citations
sort: label
order: asc
title: All Persons
:::
