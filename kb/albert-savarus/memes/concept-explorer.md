---
description: All concept entities in Albert Savarus ranked by quality score, revealing the intellectual architecture of Balzac's novel — from law and politics to love and honor.
id: concept-explorer
label: Concept Explorer
tags: ["concept", "exploration", "index"]
type: list
---

# Concept Explorer

Balzac's _Albert Savarus_ constructs a dense conceptual world: the machinery of
Restoration law and politics, the social codes of provincial marriage, the
tensions between ambition and desire. This page surfaces all concept entities
ranked by their quality score — a composite metric reflecting sourcing depth,
structural completeness, and narrative coverage.

::: query
type: concept
display: table
fields: [label, quality, total_refs, quality_score]
field_labels:
  label: Concept
  quality: Quality Tier
  total_refs: References
  quality_score: Quality Score
sort: quality_score
order: desc
:::

## Understanding Concept Quality

**Quality Score** is a composite metric (0–100) that weights sourcing density,
structural completeness, and cross-referencing. Concepts with high scores have
rich blockquote citations, well-organized H2 sections, and strong wikilink
integration. Lower-scoring concepts are candidates for enrichment in Phase 5
RCH rounds.
