---
description: An index of all named characters in *Simon the Coldheart*, dynamically rendered from the wiki's person pages.
id: characters
label: Characters
tags: ["list", "characters", "index"]
type: list
---

This page provides a dynamic index of all characters appearing in *Simon the Coldheart*. It is automatically generated from the wiki's person pages and updates as new character entries are added.

## All Characters

Character entries are listed alphabetically, with their house affiliation and quality rating.

::: query
type: person
display: table
fields: [label, affiliation, quality]
field_labels:
  label: Character
  affiliation: House / Faction
  quality: Quality
sort: label
order: asc
title: Character Index
:::

## Historical Figures

Several characters in the novel are based on real historical figures from the early 15th century.

::: query
type: person
display: table
fields: [label, affiliation, quality]
field_labels:
  label: Character
  affiliation: House / Faction
  quality: Quality
sort: label
order: asc
title: Historical Figures
:::

## Notes

- The "Quality" column reflects the current assessment of each character page (basic, standard, or featured).
- Characters are grouped by their house or faction allegiance in the "House / Faction" column.
