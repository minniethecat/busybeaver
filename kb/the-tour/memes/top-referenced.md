---
description: A ranked index of the most-referenced wiki entries across all types, ordered by total cross-reference count. Serves as a discovery tool for the wiki's most connected pages.
id: top-referenced
label: Top Referenced
tags: ["index", "statistics", "reference"]
type: list
---

## Overview

This page lists the thirty most-referenced entries in the wiki, ordered by the total number of incoming wikilinks from other pages. Highly-referenced pages are typically the narrative and thematic hubs of "The Tour" — central characters, major locations, and key concepts that appear across many chapters.

## Most Referenced Pages

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Entry
  type: Type
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 30
:::

## About the Ranking

Reference counts are computed automatically by the wiki engine from all `[[wikilink]]` mentions across page bodies. A high reference count indicates a page that is woven deeply into the wiki's link network — these are the best starting points for exploring the world of "The Tour."
