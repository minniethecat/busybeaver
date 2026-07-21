---
description: Complete index of all event entries in The Village wiki, covering historical and in-novel events that shape the characters' world.
id: event-index
label: Event Index
tags: ["index", "event", "history"]
type: list
---

# Event Index

This page provides a complete index of all **event** entries for Ivan Bunin's *The Village*. Each entry covers a historical event or in-novel occurrence referenced by the characters or the narrator, from wars and famines to local incidents.

Entries are sorted alphabetically by label.

## All Events

::: query
type: event
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Event Index — Alphabetical
:::

## Featured Events

::: query
type: event
quality: featured
display: table
fields: [label, total_refs]
field_labels:
  label: Event
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Events — Most Cited First
:::

## Notes

This page is generated dynamically from the wiki's event entries. No manual maintenance is required — new event pages are automatically included when they are created with `type: event` in their frontmatter.
