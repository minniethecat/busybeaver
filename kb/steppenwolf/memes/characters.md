---
description: All named characters in Hermann Hesse's Steppenwolf, sorted alphabetically by display name with quality indicators.
id: characters
label: Characters
tags: ["index", "character", "person", "list"]
type: list
---

# Characters

This page lists every named character who appears or is referenced in [[steppenwolf-novel|Steppenwolf]]. The table is dynamically generated from the wiki's `type: person` pages — it updates automatically as new character entries are added or existing ones are revised. Each character's quality grade reflects the depth and completeness of their entry.

## All Characters

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Top Referenced Characters

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
:::
