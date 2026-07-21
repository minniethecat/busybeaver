---
description: A dynamic ranking of the most frequently cited pages across all entity types, sorted by total reference count.
id: list-most-referenced
label: Most Referenced Pages
tags: ["index", "list", "statistics", "ranking"]
type: list
---

# Most Referenced Pages

This page provides a dynamically ranked list of the pages most frequently
referenced by other wiki pages. Higher citation counts identify narrative hubs
and key concepts that connect multiple tales and characters in *The Windfairies*.

The ranking helps readers discover central figures, pivotal events, and recurring
themes that form the backbone of the collection.

## Top 50 by Citations

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Citations
sort: total_refs
order: desc
limit: 50
title: Most Referenced Pages (Top 50)
:::
