---
description: A comprehensive index of locations in Hugo's 1482 Paris — cathedrals, streets, squares, and quarters — dynamically compiled from wiki place pages.
id: places-in-medieval-paris
label: Places in Medieval Paris
tags: []
type: list
---

# Places in Medieval Paris

Hugo's novel is as much about Paris as it is about its characters. The city
itself — its cathedral, its labyrinthine streets, its quarters — forms the
backdrop against which every event unfolds. This page indexes all documented
locations.

## All Locations

::: query
type: place
display: table
fields: [label, era, total_refs, quality]
field_labels:
  label: Location
  era: Era / District
  total_refs: References
  quality: Quality
sort: label
order: asc
title: All Locations
:::

## By District

::: query
type: place
tags: [right-bank]
display: list
sort: label
order: asc
title: Right Bank (Rive Droite)
:::

::: query
type: place
tags: [left-bank]
display: list
sort: label
order: asc
title: Left Bank (Rive Gauche)
:::

::: query
type: place
tags: [ile-de-la-cite]
display: list
sort: label
order: asc
title: Île de la Cité
:::

## Religious and Secular

::: query
type: place
tags: [church]
display: list
sort: label
order: asc
title: Churches and Religious Buildings
:::

::: query
type: place
tags: [fortress]
display: list
sort: label
order: asc
title: Fortresses and Prisons
:::

## Notes

District and tag classifications are sourced from frontmatter `tags` and `era`
fields. Hugo's Paris predates Haussmann's renovations; the geography reflects
the medieval city of 1482.
