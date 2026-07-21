---
description: All entity pages grouped by quality tier — featured, standard, and basic — sorted alphabetically within each group.
id: list-by-quality
label: Pages by Quality Tier
tags: ["index", "list", "quality", "overview"]
type: list
---

# Pages by Quality Tier

This page organizes all entity pages by their quality tier. Featured pages
represent the most polished entries with comprehensive coverage. Standard pages
provide solid coverage, while basic pages offer essential information and are
candidates for future enrichment.

## Featured Pages

::: query
quality: featured
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: Citations
sort: label
order: asc
title: Featured Pages
:::

## Standard Pages

::: query
quality: standard
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: Citations
sort: label
order: asc
title: Standard Pages
:::

## Basic Pages

::: query
quality: basic
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: Citations
sort: label
order: asc
title: Basic Pages
:::
