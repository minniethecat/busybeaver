---
description: A ranked index of the 50 most-referenced entities across the wiki — the people, places, deities, events, and concepts most frequently cited in other pages, reflecting their centrality in the world of Os Lusíadas.
id: most-referenced-entities
label: Most Referenced Entities
tags: []
type: list
---

# Most Referenced Entities

The 50 most-referenced entities in this wiki, ranked by backlink count. This page is dynamically generated — as new pages are added and linked, the ranking updates automatically. No manual curation is required.

## Top 50 by Reference Count

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Entity
  type: Type
  quality: Quality
  total_refs: Refs
sort: total_refs
order: desc
limit: 50
:::

## About This Index

The reference count (`total_refs`) tallies every incoming wikilink from other pages. It serves as a rough measure of an entity's prominence in the epic's narrative and in the wiki's knowledge graph. Entities with high reference counts are typically central characters, key locations, or recurring thematic concepts.
