---
description: "Complete index of characters in George Eliot's The Mill on the Floss, organized by family, role, and prominence"
id: characters
label: "Characters of The Mill on the Floss"
tags: ["index", "character", "person", "reference"]
type: list
---

# Characters of The Mill on the Floss

This page provides a dynamically generated index of all characters in George Eliot's *The Mill on the Floss*. The listing is organized by family affiliation and narrative prominence, drawing from the structured metadata of each character page.

## All Characters (Alphabetical)

::: query
type: person
display: table
fields: [label, family, role, total_refs]
field_labels:
  label: Character
  family: Family
  role: Role
  total_refs: Citations
sort: label
order: asc
:::

## By Family

### The Tullivers

::: query
type: person
tags: [tulliver-family]
display: table
fields: [label, role, total_refs]
field_labels:
  label: Character
  role: Role
  total_refs: Citations
sort: label
order: asc
:::

### The Dodsons

::: query
type: person
tags: [dodson-family]
display: table
fields: [label, role, total_refs]
field_labels:
  label: Character
  role: Role
  total_refs: Citations
sort: label
order: asc
:::

### The Wakems

::: query
type: person
tags: [wakem-family]
display: table
fields: [label, role, total_refs]
field_labels:
  label: Character
  role: Role
  total_refs: Citations
sort: label
order: asc
:::

### The Guests and Deanes

::: query
type: person
tags: [guest-family]
display: table
fields: [label, role, total_refs]
field_labels:
  label: Character
  role: Role
  total_refs: Citations
sort: label
order: asc
:::

## Featured Characters

The most prominent figures in the novel, with featured-quality pages:

::: query
type: person
quality: featured
display: table
fields: [label, family, role]
field_labels:
  label: Character
  family: Family
  role: Role
sort: label
order: asc
:::

## Top Cited Characters

::: query
type: person
display: table
fields: [label, family, total_refs]
field_labels:
  label: Character
  family: Family
  total_refs: Citations
sort: total_refs
order: desc
limit: 20
:::

## Notes

- Character pages are built from corpus evidence across all seven books of the novel.
- Citation counts (`total_refs`) reflect the number of distinct paragraph references to each character across the wiki.
- Some minor characters may appear in the alphabetical index without belonging to a major family group.
