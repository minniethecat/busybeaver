---
description: Index of all event entries in the wiki, sorted by reference count
id: all-events
label: All Events
tags: ["index", "event"]
type: list
---

# All Events

This page lists all event entries in the wiki, dynamically generated from the page registry.

## By Reference Count

::: query
type: event
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
:::
