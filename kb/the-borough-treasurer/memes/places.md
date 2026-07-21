---
description: A complete index of all locations and settings in The Borough Treasurer, sorted alphabetically.
id: places
label: All Places
tags: ["index", "geography"]
type: list
---

# All Places

This page provides a dynamically-rendered index of every location that appears in *The Borough Treasurer* by J.S. Fletcher. The novel's geography ranges from the industrial town of Highmarket and its surrounding boroughs to the assize courts of Norcaster and the remote harbours where fugitives seek escape.

## Alphabetical Index

::: query
type: place
display: table
fields: [label, location_type, region, total_refs]
field_labels:
  label: Place
  location_type: Type
  region: Region
  total_refs: References
sort: label
order: asc
:::

## By Reference Count

::: query
type: place
display: table
fields: [label, total_refs]
field_labels:
  label: Place
  total_refs: References
sort: total_refs
order: desc
limit: 20
:::
