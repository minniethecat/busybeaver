---
description: Quantitative quality ranking of all wiki entries by quality_score — from the richest, most polished pages to those still growing.
id: quality-leaderboard
label: Quality Leaderboard
tags: ["index", "quality", "ranking", "statistics"]
type: list
---

# Quality Leaderboard

Beyond the simple tier labels — featured, standard, basic — every wiki page carries a numeric `quality_score` that reflects prose depth, citation density, structural richness, and cross-referencing. This leaderboard ranks every entry by that score, giving a precise view of which pages are the wiki's strongest work.

## Top 30 by Quality Score

::: query
display: table
fields: [label, type, quality, quality_score]
field_labels:
  label: Page
  type: Type
  quality: Tier
  quality_score: Score
sort: quality_score
order: desc
limit: 30
title: Top 30 Pages by Quality Score
:::

## Full Ranking

All entries ordered by quality score — a complete map of the wiki's content depth.

::: query
display: table
fields: [label, type, quality, quality_score]
field_labels:
  label: Page
  type: Type
  quality: Tier
  quality_score: Score
sort: quality_score
order: desc
title: All Entries by Quality Score
:::
