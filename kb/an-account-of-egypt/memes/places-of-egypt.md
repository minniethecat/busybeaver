---
id: places-of-egypt
label: Places of Egypt
type: list
description: 'A comprehensive index of all cities, temples, regions, and natural features of Egypt documented in this wiki'
tags: ["ancient-egypt", "geography", "places", "index"]
---

# Places of Egypt

This page provides a complete, dynamically generated directory of every place page in the wiki — from the Nile Delta cities to Upper Egyptian temples, from desert oases to Mediterranean ports. Entries are sorted alphabetically by label.

## All Places

::: query
type: place
display: table
fields: [label, era, quality, total_refs]
field_labels:
  label: Place
  era: Era
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Complete Place Index
:::

## Featured Places

The most thoroughly developed place entries, meeting the wiki's highest quality standards.

::: query
type: place
quality: featured
display: table
fields: [label, era, total_refs]
field_labels:
  label: Place
  era: Era
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Places
:::
