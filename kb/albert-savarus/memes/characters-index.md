---
description: Complete index of characters in Balzac's Albert Savarus, grouped by role and quality tier
id: characters-index
label: Characters Index
tags: []
type: list
---

# Characters of Albert Savarus

This page provides a complete index of all characters appearing in Honoré de Balzac's *Albert Savarus*,
grouped by their narrative role and quality tier. Each entry links to a dedicated page with biographical details,
relationships, and chapter appearances.

## All Characters by Quality

::: query
type: person
display: table
fields: [label, quality, total_refs, tags]
field_labels:
  label: Character
  quality: Quality Tier
  total_refs: Citations
  tags: Tags
sort: label
order: asc
:::

## Featured Characters

::: query
type: person
quality: featured
display: table
fields: [label, total_refs]
field_labels:
  label: Character
  total_refs: Citations
sort: total_refs
order: desc
:::

## Standard Characters

::: query
type: person
quality: standard
display: table
fields: [label, total_refs]
field_labels:
  label: Character
  total_refs: Citations
sort: total_refs
order: desc
:::
