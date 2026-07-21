---
description: Wiki entries with the most internal wikilinks — the best starting points for exploring the wiki by following cross-references from highly connected pages.
id: navigation-hubs
label: Navigation Hubs
tags: ["index", "navigation"]
type: list
---

Some pages function as natural hubs: they link out to many other entries, making them excellent starting points for browsing the wiki by following cross-references. This index ranks all entries by their wikilink count, identifying the most richly connected pages in *Moribund Society and Anarchy*.

## Top 100 Navigation Hubs

::: query
display: table
fields: [label, type, quality, wikilink_count, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  wikilink_count: Outgoing Links
  total_refs: Incoming References
sort: wikilink_count
order: desc
limit: 100
:::

## Pages with Few Outgoing Links

These pages may benefit from additional cross-references to better integrate them into the wiki's link network.

::: query
display: table
fields: [label, type, quality, wikilink_count]
field_labels:
  label: Page
  type: Type
  quality: Quality
  wikilink_count: Outgoing Links
sort: wikilink_count
order: asc
limit: 30
:::
