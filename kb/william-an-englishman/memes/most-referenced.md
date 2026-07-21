---
description: Statistical cross-section of the William—An Englishman wiki showing the most-cited pages within each major category. Uses dynamic query blocks sorted by total citations.
id: most-referenced
label: Most Referenced
tags: []
type: list
---

# Most Referenced

This page offers a statistical overview of the wiki, ranking pages by citation count — a proxy for each entry's centrality in the network of people, places, concepts, and events that make up Cicely Hamilton's novel. All tables are generated dynamically from the page registry.

Citation counts (`total_refs`) are computed automatically from wikilinks embedded in other pages. A high count signals that an entry is frequently referenced — as a central character, a recurring location, a key concept, or a pivotal event.

## Top People

::: query
type: person
display: table
fields: [label, total_refs]
field_labels:
  label: Person
  total_refs: Citations
sort: total_refs
order: desc
limit: 10
:::

## Top Places

::: query
type: place
display: table
fields: [label, total_refs]
field_labels:
  label: Place
  total_refs: Citations
sort: total_refs
order: desc
limit: 10
:::

## Top Concepts

::: query
type: concept
display: table
fields: [label, total_refs]
field_labels:
  label: Concept
  total_refs: Citations
sort: total_refs
order: desc
limit: 10
:::

## Top Events

::: query
type: event
display: table
fields: [label, total_refs]
field_labels:
  label: Event
  total_refs: Citations
sort: total_refs
order: desc
limit: 10
:::

## Featured Content

::: query
quality: featured
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: Citations
sort: label
order: asc
:::
