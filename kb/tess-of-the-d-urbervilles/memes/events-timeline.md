---
description: 'A dynamic chronological index of narrative events in Hardy''s "Tess of the d''Urbervilles", organized by narrative significance.'
id: events-timeline
label: Events Timeline
tags: ["index", "events", "plot", "navigation"]
type: list
---

# Events Timeline

The tragedy of Tess unfolds through a chain of events — some deliberate, some accidental — that tighten around her like a net. This index catalogs every named event, from the death of Prince to the final scene at Stonehenge.

## All Events Alphabetically

::: query
type: event
sort: label
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: Citations
:::

## Featured Events

The most significant, citation-dense narrative moments.

::: query
type: event
quality: featured
sort: total_refs
order: desc
display: table
fields: [label, total_refs, quality_score]
field_labels:
  label: Event
  total_refs: Citations
  quality_score: Quality Score
:::

## Turning Points

Events that decisively alter the course of Tess's life.

::: query
type: event
tags: [turning-point]
sort: label
display: list
:::

## Tragic Climaxes

The novel's most devastating moments.

::: query
type: event
tags: [tragedy]
sort: label
display: list
:::
