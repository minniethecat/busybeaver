---
description: A leaderboard of the most-cited pages in the The Mayor of Casterbridge wiki, showing which characters, places, events, and concepts are most central to the novel's critical and editorial apparatus.
id: top-referenced-pages
label: Most Referenced Pages
tags: ["index", "statistics", "reference"]
type: list
---

This page ranks all wiki entries by their total number of cross-references — a proxy for how central each entity is to the novel's critical discourse. Pages with high citation counts are typically major characters, key locations, and dominant themes that appear throughout the narrative. The table updates automatically as new citations are added.

## Top 50 by Citations

::: query
display: table
fields: [label, type, quality, total_refs, wikilink_count]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Citations
  wikilink_count: WikiLinks
sort: total_refs
order: desc
limit: 50
title: Most Referenced Pages
:::
