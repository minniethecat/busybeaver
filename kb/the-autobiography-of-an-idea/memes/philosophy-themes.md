---
description: Cross-type aggregation of pages tagged with core philosophical themes in Sullivan's autobiography — exploring idealism, pragmatism, and the philosophical foundations of organic architecture.
id: philosophy-themes
label: philosophy-themes
tags: ["philosophy", "theme-index"]
type: list
---

# Philosophy Themes

A thematic index of wiki pages exploring the philosophical dimensions of Louis Sullivan's thought.
This page aggregates entities tagged with `philosophy` and related philosophical concepts,
offering a cross-type view of how philosophical ideas permeate Sullivan's architectural vision
and personal philosophy.

## Core Philosophy Pages

::: query
type: NOT NULL
tags: [philosophy]
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Title
  type: Type
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
title: Philosophy-Tagged Pages
:::

## Philosophical Concepts

::: query
type: concept
tags: [philosophical-concept]
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Concept
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
title: Philosophical Concepts
:::

## About This Page

This page uses dynamic query blocks to aggregate content across all entity types.
No manual list maintenance is required — new pages matching these criteria are
automatically included when they are created and tagged.
