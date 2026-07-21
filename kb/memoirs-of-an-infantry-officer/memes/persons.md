---
description: Index of all person pages in Memoirs of an Infantry Officer — dynamically rendered from page metadata. Updates automatically as new entries are added.
id: persons
label: Persons
tags: ["index", "person", "character"]
type: list
---

# Persons

This page provides a complete index of all person pages in the wiki.
The tables below are dynamically generated from each entry's frontmatter
and update automatically as new pages are created or existing pages are enriched.

## All Persons

::: query
type: person
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Name
  description: Role / Description
  quality: Quality Tier
:::

## Most Referenced

::: query
type: person
sort: total_refs
order: desc
limit: 10
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Name
  total_refs: Times Referenced
  quality: Quality Tier
:::

## Notes

The "Times Referenced" counts are computed from the wiki's backlink index
and reflect how many other pages link to each person entry.
Quality tiers follow the wiki's quality scale: `stub` → `basic` → `standard` → `featured` → `premium`.
