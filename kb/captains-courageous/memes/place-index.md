---
description: Complete geographic index of all locations in the Captains Courageous wiki — ports, fishing grounds, landmarks, cities, and other places.
id: place-index
label: Index of Places
tags: ["index", "place", "geography"]
type: list
---

# Index of Places

This page indexes every geographic location referenced in _Captains Courageous_, organized by type. All tables are generated dynamically from page frontmatter.

## Ports and Harbors

::: query
type: port
display: table
fields: [label, quality]
field_labels:
  label: Port
  quality: Quality
sort: label
order: asc
:::

## Fishing Grounds

::: query
type: fishing-ground
display: table
fields: [label, quality]
field_labels:
  label: Fishing Ground
  quality: Quality
sort: label
order: asc
:::

## Landmarks

::: query
type: landmark
display: table
fields: [label, quality]
field_labels:
  label: Landmark
  quality: Quality
sort: label
order: asc
:::

## Cities

::: query
type: city
display: table
fields: [label, quality]
field_labels:
  label: City
  quality: Quality
sort: label
order: asc
:::

## Other Places

::: query
type: place
display: table
fields: [label, quality]
field_labels:
  label: Place
  quality: Quality
sort: label
order: asc
:::
