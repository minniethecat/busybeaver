---
id: persons-index
label: Persons Index
type: list
description: Complete index of all person pages in the Timon of Athens wiki, sorted alphabetically by label
tags: ["persons", "index", "characters"]
---

# Persons Index

This page lists all characters from *Timon of Athens*, dynamically rendered from the wiki's person pages. Each entry links to a character's dedicated page with biographical details, affiliations, and key scenes.

## All Characters

::: query
type: person
display: table
fields: [label, affiliation, quality]
field_labels:
  label: Character
  affiliation: Affiliation
  quality: Quality
sort: label
order: asc
:::

## By Quality Tier

### Featured

::: query
type: person
quality: featured
display: table
fields: [label, affiliation]
field_labels:
  label: Character
  affiliation: Affiliation
sort: label
order: asc
:::

### Standard

::: query
type: person
quality: standard
display: table
fields: [label, affiliation]
field_labels:
  label: Character
  affiliation: Affiliation
sort: label
order: asc
:::
