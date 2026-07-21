---
description: Index of all organization pages in Memoirs of an Infantry Officer — military units, battalions, and institutions referenced in Sassoon's memoir. Dynamically rendered from page metadata.
id: organizations
label: Organizations
tags: ["index", "organization", "military", "unit", "battalion"]
type: list
---

# Organizations

This page provides a complete index of all organization pages in the wiki,
covering the military units, battalions, regiments, and institutions that appear
in *Memoirs of an Infantry Officer*. The tables below are dynamically generated
from each entry's frontmatter and update automatically as new pages are created
or existing pages are enriched.

## All Organizations

::: query
type: organization
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Organization
  description: Description
  quality: Quality Tier
:::

## Most Referenced

::: query
type: organization
sort: total_refs
order: desc
limit: 10
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Organization
  total_refs: Times Referenced
  quality: Quality Tier
:::

## Notes

The "Times Referenced" counts are computed from the wiki's backlink index
and reflect how many other pages link to each organization entry.
Sassoon served with the Royal Welch Fusiliers, and his memoir references
numerous battalions, companies, and support units of the British Army
on the Western Front.
