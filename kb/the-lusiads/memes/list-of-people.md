---
description: A query-generated index of all person entries in the wiki — historical figures, explorers, kings, classical and biblical characters referenced in Os Lusíadas.
id: list-of-people
label: List of People
tags: []
type: list
---

# List of People

A dynamically generated index of all **person** entries currently in the wiki. This page is powered by a `::: query` block that automatically reflects new and updated pages — no manual list maintenance is needed.

## All People

::: query
type: person
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

This page is automatically updated when new person pages are added or existing ones are reclassified. The reference count (`total_refs`) reflects the number of backlinks from other wiki pages, serving as a rough proxy for the figure's prominence in the epic.
