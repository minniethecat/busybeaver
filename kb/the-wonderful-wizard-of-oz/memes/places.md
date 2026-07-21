---
id: places
label: Places
type: list
description: All locations in The Wonderful Wizard of Oz, grouped by region.
tags: ["list", "place", "location-index"]
---

# Places

This page aggregates all place entries in the wiki, dynamically grouped by region and
sorted by reference count. The tables are auto-generated from page metadata.

## All Locations by Region

::: query
type: place
display: table
fields: [label, region, color, total_refs]
field_labels:
  label: Location
  region: Region
  color: Color
  total_refs: References
sort: region
order: asc
limit: 50
:::

## Top Referenced Locations

::: query
type: place
display: table
fields: [label, region, inhabitants, total_refs]
field_labels:
  label: Location
  region: Region
  inhabitants: Inhabitants
  total_refs: References
sort: total_refs
order: desc
limit: 25
:::
