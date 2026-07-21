---
description: Index of all narrative events in Wuthering Heights, sorted alphabetically.
id: Events
label: Events
tags: ["index", "events", "plot"]
type: list
---

# Events

This page lists the key narrative events that structure the plot of *Wuthering Heights* (1847).
The novel's non-linear structure — spanning from Lockwood's arrival in 1801 back through
Nelly Dean's retrospective narration to the 1770s — creates a complex web of causally linked
episodes. Each event page traces its narrative function and its connections to preceding
and following events.

::: query
type: event
display: table
fields: [label, timeframe, location, quality]
field_labels:
  label: Event
  timeframe: Timeframe
  location: Location
  quality: Quality
sort: label
order: asc
:::

## Notes

- Events are linked chronologically through `preceding_event` and `following_event` frontmatter fields on individual event pages.
- Some events span multiple chapters; see each event page's `chapter_range` field for exact coverage.
