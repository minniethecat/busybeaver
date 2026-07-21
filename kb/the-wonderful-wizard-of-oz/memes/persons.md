---
id: persons
label: Persons
type: list
description: All characters appearing in The Wonderful Wizard of Oz, sorted by most referenced.
tags: ["list", "person", "character-index"]
---

# Persons

This page aggregates all person entries in the wiki, dynamically ranked by reference count
across the corpus. The table is auto-generated from page metadata and requires no manual
maintenance.

## All Characters

::: query
type: person
display: table
fields: [label, species, affiliation, total_refs]
field_labels:
  label: Character
  species: Species
  affiliation: Affiliation
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::

## By Species

::: query
type: person
display: table
fields: [label, species, residence, total_refs]
field_labels:
  label: Character
  species: Species
  residence: Residence
  total_refs: References
sort: species
order: asc
limit: 50
:::
