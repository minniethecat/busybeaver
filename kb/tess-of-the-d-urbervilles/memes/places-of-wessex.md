---
description: 'A dynamic gazetteer of every location in Hardy''s "Tess of the d''Urbervilles", from the Blackmoor Vale to Stonehenge.'
id: places-of-wessex
label: Places of Wessex
tags: ["index", "places", "setting", "navigation"]
type: list
---

# Places of Wessex

Hardy's fictional Wessex is as much a character as any person in the novel. This index catalogs every named location — villages, farms, towns, and natural landmarks — that Tess passes through on her journey from innocence to tragedy.

## All Places Alphabetically

::: query
type: place
sort: label
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Location
  quality: Quality
  total_refs: Citations
:::

## Primary Settings

Locations central to the novel's key events, where Tess lives, works, or encounters pivotal moments.

::: query
type: place
quality: featured
sort: label
display: list
:::

## Marlott and the Vale of Blackmoor

Tess's birthplace and the rural world of her childhood.

::: query
type: place
tags: [rural]
sort: label
display: list
:::

## Towns and Cities

Urban centers that contrast with the agricultural landscape — sites of commerce, judgment, and execution.

::: query
type: place
tags: [town]
sort: label
display: list
:::
