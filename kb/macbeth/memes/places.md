---
description: A comprehensive index of all locations and settings in Shakespeare's Macbeth, from the Scottish heath to the English court.
id: places
label: Places
tags: ["index", "places", "locations", "setting"]
type: list
---

# Places & Locations

An index of the places that form the geography of *Macbeth*: castles and heaths, battlefields and burial grounds. Each location carries symbolic weight — from the wild heath where the witches prophecy, to the blood-stained halls of Inverness and Dunsinane.

## All Places

::: query
type: place
display: table
fields: [label, description, total_refs]
field_labels:
  label: Place
  description: Description
  total_refs: References
sort: label
order: asc
title: Complete Place Index
:::

## Castles & Strongholds

The seats of power in *Macbeth* — sites of feasting, murder, and siege.

::: query
type: place
tags: [castle, fortress, stronghold, dunsinane, inverness]
display: table
fields: [label, description, total_refs]
field_labels:
  label: Castle
  description: Description
  total_refs: References
sort: label
order: asc
title: Castles & Strongholds
:::

## Natural & Symbolic Landscapes

Heaths, woods, and natural settings that reflect the play's moral and supernatural dimensions.

::: query
type: place
tags: [forest, heath, nature, supernatural]
display: table
fields: [label, description, total_refs]
field_labels:
  label: Location
  description: Description
  total_refs: References
sort: label
order: asc
title: Natural & Symbolic Landscapes
:::
