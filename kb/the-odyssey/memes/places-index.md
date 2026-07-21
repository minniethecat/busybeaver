---
description: A complete index of all locations and places in Homer's Odyssey, dynamically generated from the wiki's place entries.
id: places-index
label: Places Index
tags: ["index", "places", "geography"]
type: list
---

# Places Index

This page catalogs all locations referenced in Homer's *Odyssey*, from islands and cities
to kingdoms and mythological realms. Places are ordered alphabetically by label.

Each entry includes its type (island, city, kingdom, etc.), ruler where known,
and the books in which it appears.

## All Places

::: query
type: place
display: table
fields: [label, place_type, ruler, book_references, quality]
field_labels:
  label: Place
  place_type: Type
  ruler: Ruler
  book_references: Book References
  quality: Quality
sort: label
order: asc
:::

## Islands

::: query
type: place
place_type: island
display: table
fields: [label, ruler, inhabitants, quality]
field_labels:
  label: Island
  ruler: Ruler
  inhabitants: Inhabitants
  quality: Quality
sort: label
order: asc
:::

## Cities & Kingdoms

::: query
type: place
tags: [city, kingdom]
display: table
fields: [label, place_type, ruler, inhabitants, quality]
field_labels:
  label: Location
  place_type: Type
  ruler: Ruler
  inhabitants: Inhabitants
  quality: Quality
sort: label
order: asc
:::
