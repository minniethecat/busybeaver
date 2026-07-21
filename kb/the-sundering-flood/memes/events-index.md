---
description: >
id: events-index
label: Events & Battles
tags: ["index", "event", "timeline"]
type: list
---

# Events & Battles

This page provides a dynamically updated list of all significant events,
battles, and conflicts chronicled in *The [[sundering-flood]]*. Each entry
links to a detailed wiki page with participants, context, and outcomes.

## Featured Events

::: query
type: event
quality: featured
sort: label
order: asc
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: Mentions
:::

## All Events

::: query
type: event
sort: label
order: asc
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: Mentions
:::
