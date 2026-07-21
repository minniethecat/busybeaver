---
description: A dynamically-rendered showcase of the best-documented pages in the Babbitt wiki, spanning all entity types from persons to concepts.
id: featured-content
label: Featured Content
tags: ["featured", "index", "showcase"]
type: list
---

# Featured Content

This page presents the wiki's flagship entries — pages that have reached **featured** quality through the GROW enrichment pipeline. These are the most thoroughly documented entities, with multi-perspective analysis, extensive PN citations, and cross-entity context. The listing updates automatically as pages are promoted or newly reach featured status.

::: query
quality: featured
display: table
fields: [label, type, pn_count, total_refs]
field_labels:
  label: Page
  type: Type
  pn_count: PN Citations
  total_refs: References
sort: total_refs
order: desc
:::

## About Featured Pages

Featured status is the second-highest quality tier in the wiki (below premium). To qualify, a page must demonstrate comprehensive coverage across all sections of its type template, include multiple paragraph-number citations grounding each claim in Lewis's text, and where applicable offer multi-perspective analysis. The standard is verified by `compute_quality.py` as part of the GROW quality pipeline.
