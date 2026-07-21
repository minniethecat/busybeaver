---
description: Statistical ranking of the most-cited pages across all entry types in the Albert Savarus wiki, ordered by total reference count
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "statistics", "ranking"]
type: list
---

# Most Referenced Pages

This page ranks every entry in the wiki by its total cross-reference count — a proxy for narrative centrality in Balzac's _Albert Savarus_. Pages with high reference counts are the connective tissue of the novel: characters, places, and concepts that recur across chapters and are cited by other entries.

## Top 50 Most Referenced

::: query
sort: total_refs
order: desc
limit: 50
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
:::

## By Type — Top 20

### Characters

::: query
type: person
sort: total_refs
order: desc
limit: 20
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
title: Most Cited Characters
:::

### Places

::: query
type: place
sort: total_refs
order: desc
limit: 20
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: References
title: Most Cited Places
:::

### Concepts

::: query
type: concept
sort: total_refs
order: desc
limit: 20
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: References
title: Most Cited Concepts
:::

## Notes

Reference counts (`total_refs`) are derived from the wiki's backlink index and include both inline wikilinks and structured cross-references from other entry pages. The count is automatically maintained by the wiki engine and does not include chapter-page citations.
