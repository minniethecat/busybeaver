---
description: Complete index of all event pages in The Dead Letter wiki, sorted alphabetically by label.
id: event-index
label: Event Index
tags: ["index", "event"]
type: list
---

# Event Index

This page aggregates all plot event entries in the wiki. The table is dynamically generated from
frontmatter data — no manual list maintenance is required.

::: query
type: event
display: table
fields: [label, event_type, location, quality]
field_labels:
  label: Event
  event_type: Type
  location: Location
  quality: Quality
sort: label
order: asc
title: All Events
:::
