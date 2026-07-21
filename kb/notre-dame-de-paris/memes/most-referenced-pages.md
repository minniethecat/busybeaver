---
description: A ranked list of the most-referenced wiki pages, ordered by total cross-reference count across the entire knowledge base.
id: most-referenced-pages
label: Most Referenced Pages
tags: []
type: list
---

# Most Referenced Pages

This page ranks every wiki entry by how often it is cited across the knowledge
base. High reference counts indicate central topics — characters, locations,
and concepts that appear frequently across multiple pages.

## Top 50 by Total References

::: query
type: NOT chapter
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
limit: 50
title: Top 50 Most Referenced Pages
:::

## By Type

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
title: Most Referenced Characters
:::

::: query
type: place
display: table
fields: [label, total_refs]
field_labels:
  label: Location
  total_refs: References
sort: total_refs
order: desc
limit: 10
title: Most Referenced Locations
:::

::: query
type: concept
display: table
fields: [label, total_refs]
field_labels:
  label: Concept
  total_refs: References
sort: total_refs
order: desc
limit: 10
title: Most Referenced Concepts
:::

## Notes

Reference counts (`total_refs`) are computed by the wiki engine from
cross-page wikilink and backlink data. Rankings may shift as new pages are
added and existing pages are enriched.
