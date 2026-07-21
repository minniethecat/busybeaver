---
description: A complete index of all key events in The Borough Treasurer, sorted chronologically by chapter occurrence.
id: events
label: Events
tags: ["index", "timeline"]
type: list
---

# Events

This page provides a dynamically-rendered index of every significant event in *The Borough Treasurer* by J.S. Fletcher. From the initial Wilchester Affair that sets the plot in motion to the final courtroom revelations, these events trace the novel's intricate structure of municipal corruption, murder, and judicial reckoning.

## Alphabetical Index

::: query
type: event
display: table
fields: [label, event_type, chapters, total_refs]
field_labels:
  label: Event
  event_type: Type
  chapters: Chapters
  total_refs: References
sort: label
order: asc
:::

## By Reference Count

::: query
type: event
display: table
fields: [label, total_refs]
field_labels:
  label: Event
  total_refs: References
sort: total_refs
order: desc
limit: 20
:::
