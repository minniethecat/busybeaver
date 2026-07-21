---
description: Complete index of all place entries in The Village wiki, covering real and fictional locations from the novel.
id: place-index
label: Place Index
tags: ["index", "place", "location", "geography"]
type: list
---

# Place Index

This page provides a complete index of all **place** entries for Ivan Bunin's *The Village*. Each entry covers a location appearing in or referenced by the novel, from the village of Durnovka itself to cities, regions, and estates.

Entries are sorted alphabetically by label.

## All Places

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Place Index — Alphabetical
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
title: Featured Places — Most Cited First
:::

## Notes

This page is generated dynamically from the wiki's place entries. No manual maintenance is required — new place pages are automatically included when they are created with `type: place` in their frontmatter.
