---
description: Most referenced pages across all types in the End of the World wiki
id: top-references
label: Top References
tags: ["index", "statistics"]
type: list
---

# Top References

The most frequently referenced pages across the entire wiki, reflecting their centrality to eschatological narrative.

## Top 30 by Reference Count

::: query
display: table
fields: [label, type, total_refs, total_chapters, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  total_chapters: Chapters
  quality: Quality
sort: total_refs
order: desc
limit: 30
title: Most Referenced Pages (All Types)
:::

## Top Persons

::: query
type: person
display: table
fields: [label, total_refs, era]
field_labels:
  label: Person
  total_refs: References
  era: Era
sort: total_refs
order: desc
limit: 15
title: Most Referenced Persons
:::

## Top Concepts

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
title: Most Referenced Concepts
:::
