---
description: All entry pages grouped by quality tier — useful for tracking quality progression and identifying pages needing enrichment.
id: pages-by-quality
label: Pages by Quality Tier
tags: ["index", "maintenance", "quality", "navigation"]
type: list
---

# Pages by Quality Tier

Entry pages grouped by their current quality assessment. Quality tiers range from `featured`
(highest, with comprehensive coverage and multiple citations) to `standard` (meets baseline
requirements). Use this page to track quality distribution and identify enrichment priorities.

## Featured Pages

::: query
type NOT IN [chapter, overview, list]
quality: featured
display: table
fields: [label, type, quality_score, total_refs]
field_labels:
  label: Page
  type: Type
  quality_score: Score
  total_refs: Refs
sort: quality_score
order: desc
:::

## Premium Pages

::: query
type NOT IN [chapter, overview, list]
quality: premium
display: table
fields: [label, type, quality_score, total_refs]
field_labels:
  label: Page
  type: Type
  quality_score: Score
  total_refs: Refs
sort: quality_score
order: desc
:::

## Standard Pages

::: query
type NOT IN [chapter, overview, list]
quality: standard
display: table
fields: [label, type, quality_score, total_refs]
field_labels:
  label: Page
  type: Type
  quality_score: Score
  total_refs: Refs
sort: quality_score
order: desc
limit: 100
:::
