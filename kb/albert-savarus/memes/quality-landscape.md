---
description: An at-a-glance overview of all entity pages by quality tier, showing the distribution of standard, basic, and featured content across the wiki.
id: quality-landscape
label: Quality Landscape
tags: ["quality", "overview", "maintenance"]
type: list
---

# Quality Landscape

This page provides a comprehensive view of the wiki's quality distribution: all
entity pages (excluding chapter, overview, and list pages) organized by quality
tier and type. Use it to assess overall quality coverage and identify areas
needing systematic attention.

## Featured Pages

::: query
quality: featured
display: table
fields: [label, type, total_refs, quality_score]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality_score: Quality Score
sort: total_refs
order: desc
:::

## Standard Pages

::: query
quality: standard
display: table
fields: [label, type, total_refs, quality_score]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality_score: Quality Score
sort: total_refs
order: desc
:::

## Basic Pages

::: query
quality: basic
display: table
fields: [label, type, total_refs, quality_score]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality_score: Quality Score
sort: total_refs
order: desc
:::
