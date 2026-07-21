---
description: Index of all places featured in The Lone Wolf (1914), from Parisian streets to European capitals.
id: locations
label: Locations
tags: ["location-index", "place"]
type: list
---

# Locations in The Lone Wolf

A gazetteer of every named location that appears in *The Lone Wolf*, spanning the novel's geography from Paris to New York. Each entry links to the full location page with narrative context and cited passages.

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Location
  quality: Quality
  total_refs: References
sort: label
order: asc
title: All Locations
:::

## Featured Locations

The most significant settings in the novel:

::: query
type: place
quality: featured
display: table
fields: [label, total_refs, total_chapters]
field_labels:
  label: Location
  total_refs: References
  total_chapters: Chapters
sort: total_refs
order: desc
title: Featured Locations
:::
