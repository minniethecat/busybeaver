---
description: Complete listing of all wiki entries grouped by quality tier — featured, standard, basic.
id: by-quality
label: All Entries by Quality
tags: ["quality", "index", "statistics"]
type: list
---

# All Entries by Quality Tier

Complete index of all wiki entries organized by quality assessment tier, from featured (highest) to basic (foundational).

## Featured

::: query
quality: featured
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
:::

## Standard

::: query
quality: standard
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: label
order: asc
:::

## See also

- [[high-quality]] — featured and premium pages
- [[most-referenced]] — top 30 by reference count
