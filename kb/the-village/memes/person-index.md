---
description: Complete index of all person entries in The Village wiki, sorted alphabetically by name.
id: person-index
label: Person Index
tags: ["index", "person", "character"]
type: list
---

# Person Index

This page provides a complete index of all **person** entries for Ivan Bunin's *The Village*. Each entry covers a character appearing in the novel, from major protagonists to minor figures mentioned in passing.

Entries are sorted alphabetically by label. Use the quality filter to focus on featured or premium content.

## All Persons

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Name
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Person Index — Alphabetical
:::

## Featured Persons

::: query
type: person
quality: featured
display: table
fields: [label, total_refs]
field_labels:
  label: Name
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Persons — Most Cited First
:::

## Notes

This page is generated dynamically from the wiki's person entries. No manual maintenance is required — new person pages are automatically included when they are created with `type: person` in their frontmatter.
