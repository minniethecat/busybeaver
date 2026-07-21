---
description: A query-generated index of all place entries in the wiki — cities, ports, regions, oceans, rivers, and mythological locations referenced in Os Lusíadas.
id: list-of-places
label: List of Places
tags: []
type: list
---

# List of Places

A dynamically generated index of all **place** entries currently in the wiki. This page is powered by a `::: query` block that automatically reflects new and updated pages — no manual list maintenance is needed.

## All Places

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Name
  quality: Quality
  total_refs: Refs
sort: label
order: asc
:::

## About This Index

This page is automatically updated when new place pages are added or existing ones are reclassified. The reference count (`total_refs`) reflects the number of backlinks from other wiki pages, serving as a rough proxy for the location's significance in the epic.
