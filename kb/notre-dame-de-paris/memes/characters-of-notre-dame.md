---
description: A complete index of all named characters in Victor Hugo's Notre-Dame de Paris (1831), dynamically rendered from the wiki's person pages.
id: characters-of-notre-dame
label: Characters of Notre-Dame de Paris
tags: []
type: list
---

# Characters of Notre-Dame de Paris

Victor Hugo populated his 1482 Paris with a rich cast of characters — from the
cathedral's bell-ringer to the king of France. This page lists every named
character documented in the wiki, drawn directly from the novel's text.

## All Characters

::: query
type: person
display: table
fields: [label, affiliation, total_refs, quality]
field_labels:
  label: Character
  affiliation: Affiliation
  total_refs: References
  quality: Quality
sort: label
order: asc
title: All Characters
:::

## By Affiliation

Characters are grouped by their primary social or institutional affiliation.

::: query
type: person
tags: [clergy]
display: list
sort: label
order: asc
title: Clergy
:::

::: query
type: person
tags: [nobility]
display: list
sort: label
order: asc
title: Nobility
:::

::: query
type: person
tags: [bourgeoisie]
display: list
sort: label
order: asc
title: Bourgeoisie
:::

::: query
type: person
tags: [truand]
display: list
sort: label
order: asc
title: Truands and Outcasts
:::

## Notes

Affiliation data is sourced from frontmatter fields and may not cover every
character. Tags are derived from the novel's social categories as described by
Hugo in Book I and Book III.
