---
description: Characters grouped by narrative role — protagonists, family members, benefactors, servants, and more.
id: character-roles
label: Character Roles
tags: ["index", "person"]
type: list
---

# Character Roles

Characters in George MacDonald's *At the Back of [[north-wind|the North Wind]]* organized by their narrative and social roles. Each section shows characters sharing a common function in the story.

## Protagonists and Central Figures

The main characters who drive the narrative.

::: query
type: person
tags_any: [protagonist]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
:::

## Family Members

Characters defined by family relationships — parents, children, and kin.

::: query
type: person
tags_any: [family, father, mother, child]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Benefactors and Mentors

Figures who guide, protect, or provide for others.

::: query
type: person
tags_any: [benefactor, mentor, master, employer]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Servants, Workers, and Tradespeople

Characters defined by their occupation or service role.

::: query
type: person
tags_any: [servant, tradesman, cabman, coachman, housekeeper, crossing-sweeper, merchant]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Minor Characters

Supporting figures who appear briefly but contribute to the world of the story.

::: query
type: person
tags_any: [minor, neighbour, friend, invalid, drunkard]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: label
order: asc
:::
