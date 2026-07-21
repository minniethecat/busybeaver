---
description: A query-generated index of all concept entries in the wiki — thematic concepts, literary traditions, and cultural ideas explored in Os Lusíadas.
id: list-of-concepts
label: List of Concepts
tags: []
type: list
---

# List of Concepts

A dynamically generated index of all **concept** entries currently in the wiki. This page is powered by a `::: query` block that automatically reflects new and updated pages — no manual list maintenance is needed.

## All Concepts

::: query
type: concept
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

This page is automatically updated when new concept pages are added or existing ones are reclassified. The reference count (`total_refs`) reflects the number of backlinks from other wiki pages, serving as a rough proxy for the concept's thematic significance.
