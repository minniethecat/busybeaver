---
description: Complete index of all place pages in The Dead Letter wiki, sorted alphabetically by label.
id: place-index
label: Place Index
tags: ["index", "place"]
type: list
---

# Place Index

This page aggregates all location entries in the wiki. The table is dynamically generated from
frontmatter data — no manual list maintenance is required.

::: query
type: place
display: table
fields: [label, place_type, location, quality]
field_labels:
  label: Place
  place_type: Type
  location: Location
  quality: Quality
sort: label
order: asc
title: All Places
:::
