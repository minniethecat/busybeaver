---
description: An index of all event pages in the wiki, sorted by start date. Covers key historical events from Yung Wing's life and 19th-century Chinese history.
id: list-of-events
label: List of Events
tags: ["list", "index", "event"]
type: list
---

# List of Events

This page indexes all event-type pages in the wiki — the pivotal moments in Yung Wing's life and the broader historical events that defined his era, from the Opium Wars to the Chinese Educational Mission.

::: query
type: event
sort: start_date
order: asc
display: table
fields: [label, start_date, end_date, description, quality]
field_labels:
  label: Event
  start_date: Start Date
  end_date: End Date
  description: Summary
  quality: Quality
:::
