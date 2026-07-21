---
description: A dynamic index of all event pages — subplots, backstories, climaxes, and historical references that structure the novel's narrative.
id: event-index
label: Event Index
tags: ["index", "event", "plot"]
type: list
---

# Event Index

This page provides a complete, automatically generated index of every [[event]] page in the wiki. Events are the plot-level building blocks of the novel's narrative: subplots, climactic moments, backstories, and historical references. The table is rendered dynamically from the pages database.

::: query
type: event
display: table
fields: [label, event_type, quality, total_refs]
field_labels:
  label: Event
  event_type: Type
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Notes

- **Type** classifies the event: subplot, backstory, climax, episode, or historical.
- Events are the narrative spine of the wiki — they connect characters to actions and consequences across chapters.
- Each event page should include chapter references and key character participants.
