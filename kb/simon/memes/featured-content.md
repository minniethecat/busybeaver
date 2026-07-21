---
description: Statistical ranking of the most-cited pages in the Simon wiki, highlighting key topics and characters.
id: featured-content
label: Featured Content
tags: ["index", "featured"]
type: list
---

# Featured Content

This page showcases the most frequently cited and referenced pages in the Simon wiki. The rankings are based on the total number of cross-references (`total_refs`) each entry has accumulated, reflecting their centrality in the novel's narrative.

## Most Cited Pages

::: query
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Citations
sort: total_refs
order: desc
limit: 25
:::
