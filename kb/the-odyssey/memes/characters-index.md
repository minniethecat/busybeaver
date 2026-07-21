---
description: A complete index of all characters in Homer's Odyssey, dynamically generated from the wiki's person entries.
id: characters-index
label: Characters Index
tags: ["index", "characters", "person"]
type: list
---

# Characters Index

This page provides a complete listing of all characters appearing in Homer's *Odyssey*,
drawn from the wiki's structured entries. Characters are ordered alphabetically by label.

The index includes mortals, gods, goddesses, nymphs, monsters, and shades—each with their
role, affiliations, and first appearance noted where available.

## All Characters

::: query
type: person
display: table
fields: [label, role, affiliation, first_appearance, quality]
field_labels:
  label: Character
  role: Role
  affiliation: Affiliation
  first_appearance: First Appearance
  quality: Quality
sort: label
order: asc
:::

## Deities

::: query
type: person
tags: [deity]
display: table
fields: [label, domain, first_appearance, quality]
field_labels:
  label: Deity
  domain: Domain
  first_appearance: First Appearance
  quality: Quality
sort: label
order: asc
:::

## Mortals

::: query
type: person
tags: [mortal]
display: table
fields: [label, role, affiliation, first_appearance, quality]
field_labels:
  label: Character
  role: Role
  affiliation: Affiliation
  first_appearance: First Appearance
  quality: Quality
sort: label
order: asc
:::
