---
description: A comprehensive index of all characters appearing in Shakespeare's Macbeth, grouped by significance and allegiance.
id: characters
label: Characters
tags: ["index", "characters", "people"]
type: list
---

# Characters

An index of all characters in *Macbeth*, from central tragic figures to minor attendants. Each character page explores their role, key speeches, relationships, and critical interpretations.

## All Characters

::: query
type: person
display: table
fields: [label, affiliation, tags, total_refs]
field_labels:
  label: Character
  affiliation: Affiliation
  tags: Tags
  total_refs: References
sort: label
order: asc
title: Complete Character Index
:::

## Major Characters

The central figures whose ambitions, fears, and moral struggles drive the tragedy.

::: query
type: person
tags: [macbeth, lady-macbeth, banquo, macduff, malcolm, duncan]
display: table
fields: [label, description, total_refs]
field_labels:
  label: Character
  description: Description
  total_refs: References
sort: total_refs
order: desc
title: Major Characters
:::

## Minor Characters

Nobles, attendants, messengers, and other figures who populate the world of the play and witness Macbeth's reign.

::: query
type: person
tags: [minor-character]
display: table
fields: [label, affiliation, tags]
field_labels:
  label: Character
  affiliation: Affiliation
  tags: Role/Tags
sort: label
order: asc
title: Minor Characters
:::
