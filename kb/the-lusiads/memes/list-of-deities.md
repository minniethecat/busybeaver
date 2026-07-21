---
description: A query-generated index of all deity entries in the wiki — Greco-Roman gods, personified abstractions, and mythological beings in Os Lusíadas.
id: list-of-deities
label: List of Deities
tags: []
type: list
---

# List of Deities

A dynamically generated index of all **deity** entries currently in the wiki. This page is powered by a `::: query` block that automatically reflects new and updated pages — no manual list maintenance is needed.

## All Deities

::: query
type: deity
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

This page is automatically updated when new deity pages are added or existing ones are reclassified. The reference count (`total_refs`) reflects the number of backlinks from other wiki pages, serving as a rough proxy for the deity's prominence in the epic's divine apparatus.
