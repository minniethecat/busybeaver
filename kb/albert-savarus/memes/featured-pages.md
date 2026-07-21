---
description: Curated showcase of featured and premium-quality pages in the Albert Savarus wiki — the most complete, well-cited entries across all types
id: featured-pages
label: Featured Pages
tags: ["index", "featured", "quality"]
type: list
---

# Featured Pages

The wiki's featured and premium-quality pages represent the deepest, most thoroughly researched entries on Balzac's _Albert Savarus_. These pages meet rigorous quality thresholds: substantial prose, dense citation of the primary text, and complete structural coverage of their subject. They serve as models for the wiki's quality standards and as the best entry points for readers.

## Premium Pages

::: query
quality: premium
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
:::

## Featured Pages

::: query
quality: featured
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: label
order: asc
:::

## Notes

Quality tiers are assigned by `compute_quality.py`, which evaluates each entry on prose length, citation density (PN references per paragraph), structural organization (H2 section count), and link density. Featured and premium pages are the top two tiers and receive priority in search results and homepage curation.
