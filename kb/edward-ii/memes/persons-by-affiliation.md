---
description: Characters in Edward II grouped by political faction — royalists, baronial opposition, church figures, and unaffiliated characters. Dynamically generated from wiki frontmatter.
id: persons-by-affiliation
label: Persons by Affiliation
tags: ["index", "character", "faction", "affiliation"]
type: list
---

# Persons by Affiliation

The political world of *Edward II* is defined by factional conflict. This page groups
characters by their allegiance, revealing the fault lines that drive the play's action.
Each faction is rendered as a separate query block, dynamically updated from wiki frontmatter.

## Royalists

Supporters of King Edward II and his favourites.

::: query
type: person
affiliation: royalist
display: table
fields: [label, born, died, quality]
field_labels:
  label: Character
  born: Born
  died: Died
  quality: Quality
sort: label
order: asc
title: Royalist Characters
:::

## Baronial Opposition

Nobles who opposed Edward II and his favourites, leading to civil war.

::: query
type: person
affiliation: baronial
display: table
fields: [label, born, died, quality]
field_labels:
  label: Character
  born: Born
  died: Died
  quality: Quality
sort: label
order: asc
title: Baronial Characters
:::

## Church

Ecclesiastical figures who intervene in the political struggle.

::: query
type: person
affiliation: church
display: table
fields: [label, born, died, quality]
field_labels:
  label: Character
  born: Born
  died: Died
  quality: Quality
sort: label
order: asc
title: Church Figures
:::

## Other / Unaffiliated

Characters not aligned with the major factions.

::: query
type: person
affiliation: other
display: table
fields: [label, born, died, quality]
field_labels:
  label: Character
  born: Born
  died: Died
  quality: Quality
sort: label
order: asc
title: Unaffiliated Characters
:::
