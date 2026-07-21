---
description: Complete index of all organization entries in The Village wiki, covering institutions, government bodies, businesses, and religious organizations referenced in the novel.
id: organization-index
label: Organization Index
tags: ["index", "organization", "institution"]
type: list
---

# Organization Index

This page provides a complete index of all **organization** entries for Ivan Bunin's *The Village*. Each entry covers an institution, government body, business, or religious organization referenced by the characters or narrator.

Entries are sorted alphabetically by label.

## All Organizations

::: query
type: organization
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Organization
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Organization Index — Alphabetical
:::

## Featured Organizations

::: query
type: organization
quality: featured
display: table
fields: [label, total_refs]
field_labels:
  label: Organization
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Organizations — Most Cited First
:::

## Notes

This page is generated dynamically from the wiki's organization entries. No manual maintenance is required — new organization pages are automatically included when they are created with `type: organization` in their frontmatter.
