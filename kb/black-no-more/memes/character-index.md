---
description: Complete index of all characters in Black No More, dynamically generated from page metadata. Lists every person page in the wiki sorted alphabetically by label.
id: character-index
label: Index of Characters
tags: ["index", "character", "person"]
type: list
---

This page provides a dynamically generated index of every character appearing in George S. Schuyler's *Black No More* (1931). Characters are listed alphabetically with their affiliations, birth/death years, and relevance measured by cross-references from other pages.

## All Characters

::: query
type: person
display: table
fields: [label, affiliation, born, total_refs]
field_labels:
  label: Character
  affiliation: Affiliation
  born: Born
  total_refs: Refs
sort: label
order: asc
:::

## By Affiliation

::: query
type: person
display: table
fields: [label, affiliation, born, total_refs]
field_labels:
  label: Character
  affiliation: Affiliation
  born: Born
  total_refs: Refs
sort: affiliation
order: asc
:::

## Most Referenced Characters

::: query
type: person
display: table
fields: [label, affiliation, total_refs]
field_labels:
  label: Character
  affiliation: Affiliation
  total_refs: Refs
sort: total_refs
order: desc
limit: 20
:::
