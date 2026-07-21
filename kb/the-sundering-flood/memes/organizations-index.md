---
description: >
id: organizations-index
label: Organizations & Factions
tags: ["index", "organization", "faction"]
type: list
---

# Organizations & Factions

This page provides a dynamically updated list of all organizations,
factions, guilds, and leagues in *The [[sundering-flood]]*.

## Featured

::: query
type: organization
quality: featured
sort: label
order: asc
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Organization
  quality: Quality
  total_refs: Mentions
:::

## All Organizations

::: query
type: organization
sort: label
order: asc
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Organization
  quality: Quality
  total_refs: Mentions
:::
