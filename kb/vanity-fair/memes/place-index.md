---
description: A dynamic index of all places in Vanity Fair, from London drawing-rooms to Continental battlefields. Sorted alphabetically with quality ratings and reference counts.
id: place-index
label: Place Index
tags: ["index", "places", "navigation", "geography"]
type: list
---

# Place Index

This page provides a complete, dynamically-generated index of every location that appears in *Vanity Fair*. Thackeray's novel spans England, Belgium, India, and Germany, weaving fictional and real-world locations into its satirical tapestry.

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: References
sort: label
order: asc
title: All Places in Vanity Fair
:::

## Notes

- Places marked `fictional: true` in their frontmatter are Thackeray's inventions (e.g., Queen's Crawley, Pumpernickel).
- Places with `historical: true` are real-world locations referenced in the novel.
- This index is dynamically generated and updates automatically as new place pages are added.
