---
description: 'A dynamic ranking of the most-cited entries across all types in the "Tess of the d''Urbervilles" wiki, updated automatically as new citations are added.'
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "statistics", "navigation"]
type: list
---

# Most Referenced Pages

This page ranks wiki entries by their citation count — a proxy for their centrality to the novel's narrative and critical discourse. The ranking is dynamic: as pages are enriched with new citations, their position updates automatically.

## Top 50 Most Cited Entries

The pages most frequently referenced across the wiki. These are the core nodes in the knowledge graph of Hardy's novel.

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
  total_refs: Citations
:::

## Most Cited Characters

::: query
type: person
sort: total_refs
order: desc
limit: 15
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Character
  total_refs: Citations
  quality: Quality
:::

## Most Cited Places

::: query
type: place
sort: total_refs
order: desc
limit: 10
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Location
  total_refs: Citations
  quality: Quality
:::

## Most Cited Events

::: query
type: event
sort: total_refs
order: desc
limit: 10
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Event
  total_refs: Citations
  quality: Quality
:::
