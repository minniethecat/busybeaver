---
description: Pages with the most primary-source citations (PN references to the original text) in The Club of Queer Trades wiki, reflecting depth of textual engagement.
id: highest-cited-pages
label: Highest Cited Pages
tags: ["index", "statistics", "citation"]
type: list
---

# Highest Cited Pages

These pages carry the most primary-source citations — direct references
to passages in the original six adventures of *The Club of Queer Trades*.
A high PN count indicates a page deeply grounded in Chesterton's text,
making it a reliable entry point for close reading.

This complements the [Most Referenced Pages](/most-referenced-pages) index,
which ranks by cross-wiki backlinks rather than primary-source citations.

::: query
display: table
fields: [label, type, quality, pn_count, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  pn_count: PN Citations
  total_refs: References
sort: pn_count
order: desc
limit: 30
title: Top 30 by Primary-Source Citations
:::
