---
description: Basic-quality pages sorted by quality score (ascending), helping editors identify the highest-priority enrichment targets.
id: list-enrichment-candidates
label: Enrichment Candidates
tags: ["index", "list", "quality", "enrichment", "editor"]
type: list
---

# Enrichment Candidates

This page surfaces all entity pages currently at the basic quality tier,
sorted by their quality score from lowest to highest. Pages with lower scores
have the greatest room for improvement and should be prioritized for enrichment.

The quality score is computed automatically based on prose length, citation
density, section structure, and wikilink coverage.

## Priority Enrichment Queue

::: query
quality: basic
display: table
fields: [label, type, quality_score, total_refs]
field_labels:
  label: Page
  type: Type
  quality_score: Quality Score
  total_refs: Citations
sort: quality_score
order: asc
limit: 50
title: Basic Pages — Lowest Quality First
:::
