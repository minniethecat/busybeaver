---
description: Index of all work pages — literary works, books, and texts referenced in or relevant to Memoirs of an Infantry Officer. Dynamically rendered from page metadata.
id: works
label: Works
tags: ["index", "work", "literature", "book", "reference"]
type: list
---

# Works

This page provides a complete index of all work pages in the wiki,
covering literary works, books, poems, and texts referenced in *Memoirs of an
Infantry Officer* or relevant to its context. The tables below are dynamically
generated from each entry's frontmatter and update automatically as new pages
are created or existing pages are enriched.

## All Works

::: query
type: work
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Work
  description: Description
  quality: Quality Tier
:::

## Most Referenced

::: query
type: work
sort: total_refs
order: desc
limit: 10
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Work
  total_refs: Times Referenced
  quality: Quality Tier
:::

## Notes

The "Times Referenced" counts are computed from the wiki's backlink index
and reflect how many other pages link to each work entry.
Sassoon was himself a poet and his memoir engages with the literary culture
of the Edwardian and Great War period — these work pages map that intertextual
landscape.
