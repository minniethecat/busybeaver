---
description: All significant places and locations in Hermann Hesse's Steppenwolf, from the physical to the symbolic, sorted alphabetically.
id: places-and-locations
label: Places & Locations
tags: ["index", "place", "location", "list"]
type: list
---

# Places & Locations

This page maps every significant space in [[steppenwolf-novel|Steppenwolf]] — the rooms, streets, buildings, and symbolic landscapes that form the geography of [[harry-haller|Harry Haller]]'s world. The table is dynamically generated from `type: place` entries.

## All Places

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Most Referenced Places

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
:::
