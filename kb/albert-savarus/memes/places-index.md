---
description: Complete geographical index of locations in Balzac's Albert Savarus, from Besançon to the Italian Lakes
id: places-index
label: Places Index
tags: []
type: list
---

# Places of Albert Savarus

This page catalogues all locations mentioned in Honoré de Balzac's *Albert Savarus*,
from the provincial capital of Besançon to the Italian lakes where Albert seeks refuge.
The novel's geography maps the tension between provincial confinement and cosmopolitan aspiration.

## All Places by Quality

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality Tier
  total_refs: Citations
sort: label
order: asc
:::

## Featured Places

::: query
type: place
quality: featured
display: table
fields: [label, total_refs]
field_labels:
  label: Place
  total_refs: Citations
sort: total_refs
order: desc
:::
