---
description: A curated showcase of premium and featured-quality pages across all types in the Odyssey wiki.
id: featured-content
label: Featured Content
tags: ["index", "featured"]
type: list
---

# Featured Content

This page showcases the highest-quality entries in the Odyssey wiki — pages rated **featured** or **premium**. These pages represent the best writing, deepest analysis, and most thorough citation coverage in the corpus.

::: query
quality: premium
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
title: Premium Pages
:::

::: query
quality: featured
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
title: Featured Pages
:::

Featured and premium pages together are capped at 10% of total entries, with premium limited to the top 5% by search relevance. These pages serve as quality benchmarks for new content creation.
