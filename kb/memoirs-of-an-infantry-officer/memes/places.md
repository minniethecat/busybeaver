---
description: Index of all place pages in Memoirs of an Infantry Officer — dynamically rendered from page metadata. Updates automatically as new entries are added or enriched.
id: places
label: Places
tags: ["index", "place", "location", "geography"]
type: list
---

# Places

This page provides a complete index of all place pages in the wiki,
covering the locations that appear in *Memoirs of an Infantry Officer* —
from the trenches of the Western Front to the hospitals and towns of the home front.
The tables below are dynamically generated from each entry's frontmatter
and update automatically as new pages are created or existing pages are enriched.

## All Places

::: query
type: place
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Place
  description: Description
  quality: Quality Tier
:::

## Most Referenced

::: query
type: place
sort: total_refs
order: desc
limit: 10
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Place
  total_refs: Times Referenced
  quality: Quality Tier
:::

## Notes

The "Times Referenced" counts are computed from the wiki's backlink index
and reflect how many other pages link to each place entry.
Sassoon's memoir moves between the Western Front trenches, rear-area billets,
base hospitals, and locations in England — this index captures the full geography
of his wartime experience.
