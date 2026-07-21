---
id: quality-showcase
label: Quality Showcase
type: list
description: The 100 highest-quality entry pages in the wiki, ranked by computed quality score — a showcase of the most polished, well-structured, and thoroughly cited content across all types.
tags: ["index", "list", "quality", "ranking", "showcase"]
---

# Quality Showcase

This page ranks the 100 highest-quality entry pages by their computed quality score. The score incorporates depth of prose coverage, citation density from Holbach's *Common Sense*, wikilink interconnectivity, and structural completeness. Pages at the top represent the most mature content in the wiki. The ran[[monarch|king]] is rendered dynamically from page frontmatter and requires no manual maintenance.

::: query
sort: quality_score
order: desc
limit: 100
display: table
fields: [label, type, quality, quality_score, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  quality_score: Score
  total_refs: References
title: Top 100 Pages by Quality Score
:::
