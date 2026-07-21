---
description: All event pages sorted alphabetically with quality ratings and reference counts
id: event-index
label: Event Index
tags: []
type: list
---

# Event Index

A complete index of all event pages in *The Mystery of [[cabin-island|Cabin Island]]*. Pages are sorted alphabetically with their current quality tier and total reference count.

::: query
type: event
sort: label
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: References
display: table
:::
