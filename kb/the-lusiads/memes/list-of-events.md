---
description: A query-generated index of all event entries in the wiki — major narrative episodes, battles, voyages, and council scenes in Os Lusíadas.
id: list-of-events
label: List of Events
tags: []
type: list
---

# List of Events

A dynamically generated index of all **event** entries currently in the wiki. This page is powered by a `::: query` block that automatically reflects new and updated pages — no manual list maintenance is needed.

## All Events

::: query
type: event
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

This page is automatically updated when new event pages are added or existing ones are reclassified. The reference count (`total_refs`) reflects the number of backlinks from other wiki pages, serving as a rough proxy for the episode's narrative importance.
