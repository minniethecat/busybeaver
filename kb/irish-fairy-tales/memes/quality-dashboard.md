---
description: |
id: quality-dashboard
label: Quality Dashboard
tags: ["index", "quality", "dashboard", "editor-reference"]
type: list
---

# Quality Dashboard

This dashboard presents the wiki's entries grouped by quality tier. Use it to track
content maturity across the five entity types of Irish mythology — persons, places,
concepts, events, and organizations. Each section is dynamically rendered from the
page registry and updates automatically as pages are enriched.

## Featured Pages

These entries represent the wiki's highest-quality content, with comprehensive coverage,
rich citations, and polished presentation.

::: query
quality: featured
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: label
title: Featured Entries
:::

## Standard Pages

The core body of the wiki — entries with solid coverage and adequate citations.

::: query
quality: standard
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: label
title: Standard Entries
:::

## Basic Pages

Entries with foundational coverage that would benefit from deeper enrichment —
additional citations, expanded sections, or improved prose.

::: query
quality: basic
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: label
title: Basic Entries
:::
