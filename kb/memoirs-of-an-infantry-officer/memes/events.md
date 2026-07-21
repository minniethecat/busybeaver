---
description: Index of all event pages in Memoirs of an Infantry Officer — dynamically rendered from page metadata. Covers battles, offensives, and significant episodes from Sassoon's wartime narrative.
id: events
label: Events
tags: ["index", "event", "battle", "timeline"]
type: list
---

# Events

This page provides a complete index of all event pages in the wiki,
covering the battles, offensives, raids, and significant episodes described
in *Memoirs of an Infantry Officer*. The tables below are dynamically generated
from each entry's frontmatter and update automatically as new pages are created
or existing pages are enriched.

## All Events

::: query
type: event
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Event
  description: Description
  quality: Quality Tier
:::

## Most Referenced

::: query
type: event
sort: total_refs
order: desc
limit: 10
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Event
  total_refs: Times Referenced
  quality: Quality Tier
:::

## Notes

The "Times Referenced" counts are computed from the wiki's backlink index
and reflect how many other pages link to each event entry.
Sassoon's account spans from his training in England through the Somme offensive
to his eventual protest against the war — each event page captures a key moment
in that trajectory.
