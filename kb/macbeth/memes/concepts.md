---
description: A comprehensive index of all concepts, themes, motifs, and abstract ideas in the Macbeth wiki — from ambition and guilt to the supernatural and the natural order, organized by category and cross-referenced by significance.
id: concepts
label: Concepts
tags: ["index", "concept", "theme", "motif"]
type: list
---

# Concepts

This page indexes all 115 concept entries in the Macbeth wiki — the thematic vocabulary through which the play's ideas are tracked, named, and connected. Concepts are the wiki's largest category; they range from major themes like [[ambition]] and [[guilt]] to specific motifs like [[blood]] and [[sleep]], from supernatural forces like [[prophecy]] to political abstractions like [[kingship]].

Each query block below presents a different cross-section: by thematic category, by quality tier, and by citation density — the number of times the concept is referenced from chapter pages.

## By Thematic Category

::: query
type: concept
tags: [theme]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Themes (44 concepts)
:::

::: query
type: concept
tags: [motif]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Motifs (28 concepts)
:::

::: query
type: concept
tags: [supernatural]
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Supernatural Concepts (19 concepts)
:::

## By Quality Tier

::: query
type: concept
quality: featured
display: table
fields: [label, total_refs]
field_labels:
  label: Featured Concept
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Concepts
:::

::: query
type: concept
quality: standard
display: table
fields: [label, total_refs]
field_labels:
  label: Standard Concept
  total_refs: Citations
sort: total_refs
order: desc
limit: 50
title: Standard Concepts — Most Cited (Top 50)
:::

## Most Referenced Concepts

::: query
type: concept
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Concept
  total_refs: Citations
  quality: Quality
sort: total_refs
order: desc
limit: 20
title: Top 20 Most Cited Concepts
:::

## All Concepts (A–Z)

::: query
type: concept
display: list
sort: label
order: asc
:::
