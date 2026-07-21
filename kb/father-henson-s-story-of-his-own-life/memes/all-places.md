---
description: Index of all place entries in the wiki, sorted by reference count
id: all-places
label: All Places
tags: ["index", "place"]
type: list
---

# All Places

This page lists all place entries in the wiki, dynamically generated from the page registry.

## By Reference Count

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
:::
