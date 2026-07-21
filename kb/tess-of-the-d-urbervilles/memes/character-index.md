---
description: 'A dynamic index of all characters in Hardy''s "Tess of the d''Urbervilles", grouped by role and sorted alphabetically.'
id: character-index
label: Character Index
tags: ["index", "characters", "navigation"]
type: list
---

# Character Index

This page provides a complete, dynamically-generated index of all characters in Hardy's *Tess of the d'Urbervilles*. Characters are grouped by their narrative role — protagonists, antagonists, major characters, and minor figures — and displayed with their quality ratings.

## All Characters by Label

::: query
type: person
sort: label
display: table
fields: [label, quality, affiliation, total_refs]
field_labels:
  label: Character
  quality: Quality
  affiliation: Affiliation
  total_refs: Citations
:::

## Protagonists and Major Characters

The central figures whose actions and decisions drive the novel's tragic arc.

::: query
type: person
tags: [protagonist]
sort: label
display: list
:::

::: query
type: person
tags: [major]
sort: label
display: list
:::

## Antagonists

Forces of opposition — social, moral, and personal — that shape Tess's fate.

::: query
type: person
tags: [antagonist]
sort: label
display: list
:::

## Minor Characters

The supporting cast of farm workers, family members, and villagers who populate Hardy's Wessex.

::: query
type: person
tags: [minor-character]
sort: label
display: list
:::

## Featured Characters

Characters with the most developed, citation-rich entries.

::: query
type: person
quality: featured
sort: total_refs
order: desc
display: table
fields: [label, total_refs, quality_score]
field_labels:
  label: Character
  total_refs: Citations
  quality_score: Quality Score
:::
