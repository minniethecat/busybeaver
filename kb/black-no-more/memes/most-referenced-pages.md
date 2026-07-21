---
description: Statistical ranking of the most cross-referenced pages in the Black No More wiki. Sorted by total backlink count, this page highlights the most connected entities — characters, concepts, places, and organizations central to Schuyler's narrative.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "statistics", "reference"]
type: list
---

This page ranks every wiki page by the number of incoming wikilinks from other pages, serving as a measure of narrative centrality in George S. Schuyler's *Black No More* (1931). Pages with the highest reference counts are the entities most frequently discussed across the wiki — typically major characters, central concepts, and key locations.

## Top 50 Most Referenced Pages

::: query
type: NOT chapter
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: Refs
sort: total_refs
order: desc
limit: 50
:::

## Top Characters

::: query
type: person
display: table
fields: [label, affiliation, total_refs]
field_labels:
  label: Character
  affiliation: Affiliation
  total_refs: Refs
sort: total_refs
order: desc
limit: 20
:::

## Top Concepts

::: query
type: concept
display: table
fields: [label, total_refs]
field_labels:
  label: Concept
  total_refs: Refs
sort: total_refs
order: desc
limit: 20
:::
