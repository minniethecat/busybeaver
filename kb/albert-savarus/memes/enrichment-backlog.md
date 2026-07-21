---
description: Maintenance queue of basic-quality pages ranked by narrative importance (total references), showing enrichment priority order.
id: enrichment-backlog
label: Enrichment Backlog
tags: ["maintenance", "quality", "enrichment"]
type: list
---

# Enrichment Backlog

This page lists all wiki entries currently at **basic** quality that still need
enrichment to reach the **standard** tier. Pages are ranked by total corpus
references — a proxy for narrative importance — so that the most consequential
entries are enriched first. Use this page to plan RCH2 enrichment rounds.

::: query
quality: basic
display: table
fields: [label, type, total_refs, quality_score]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality_score: Quality Score
sort: total_refs
order: desc
:::

## Using This Backlog

Pages with higher **References** counts and lower **Quality Score** values
should be prioritized for enrichment. The goal is to bring every entry with
substantial corpus presence up to **standard** quality — with full frontmatter,
blockquote citations, and comprehensive coverage.
