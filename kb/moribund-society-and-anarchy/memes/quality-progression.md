---
description: >
id: quality-progression
label: Quality Progression
tags: []
type: list
---

# Quality Progression

This index groups all non-chapter pages by quality tier and ranks
them by quality score within each tier. The score reflects prose
depth, citation support, wikilink connectivity, and structural
completeness.

::: query
type: entry
group: quality
sort: quality_score desc
limit: 100
columns: label, type, quality, quality_score, prose_chars, wikilink_count
:::

## Quality Tiers

| Tier | Criteria |
|------|----------|
| **featured** | Comprehensive, well-sourced, exemplar of wiki quality |
| **standard** | Solid coverage with citations and wikilinks |
| **basic** | Core content present, awaiting enrichment |
| **stub** | Placeholder or minimal content |

## See Also

- [[quality-matrix]] — Multi-dimensional quality scoring
- [[by-quality]] — Simple quality tier listing
- [[enrichment-backlog]] — Pages needing quality upgrades
