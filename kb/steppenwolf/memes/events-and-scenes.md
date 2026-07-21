---
description: All significant events, gatherings, and narrative episodes in Hermann Hesse's Steppenwolf, sorted alphabetically.
id: events-and-scenes
label: Events & Scenes
tags: ["index", "event", "scene", "list"]
type: list
---

# Events & Scenes

This page collects every significant event in [[steppenwolf-novel|Steppenwolf]] — from the [[masked-ball|Masked Ball]] to the [[magic-theater|Magic Theater]]'s hallucinatory episodes, and from [[harry-haller|Harry Haller]]'s encounters to the novel's dream sequences. The table is dynamically generated from `type: event` entries.

## All Events

::: query
type: event
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Most Referenced Events

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
limit: 10
:::
