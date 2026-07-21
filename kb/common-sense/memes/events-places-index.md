---
id: events-places-index
label: Events & Places Index
type: list
description: Combined index of event and place pages, ranked by total backlink count — a unified view of the historical occurrences and geographical locations referenced in Holbach's Common Sense.
tags: ["index", "list", "event", "place", "ranking"]
---

# Events & Places Index

This page combines the [[eve]]nt and place entry types into a [[guilt|sin]]gle ranked view. [[event-index|Events]] include historical occurrences, councils, and episodes that Holbach invokes as [[proof|evidence]]; places include cities, regions, and sites of religious or political significance.

Because each type individually has [[mode|modes]]t page counts, combining them produces a more useful overview while preserving the ran[[monarch|king]] by cross-reference density.

::: query
type_any: [event, place]
sort: total_refs
order: desc
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
title: Events & Places by Reference Count
:::
