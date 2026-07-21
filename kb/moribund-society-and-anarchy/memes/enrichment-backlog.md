---
description: >
id: enrichment-backlog
label: Enrichment Backlog
tags: []
type: list
---

# Enrichment Backlog

This index identifies pages currently at **basic** quality tier
that are candidates for enrichment. Pages with shorter prose
may need RCH1 (content expansion), while those with longer prose
but low citation counts may benefit from RCH2 (blockquote addition).

::: query
type: entry
filter: quality = basic
sort: prose_chars asc
limit: 50
columns: label, type, quality, prose_chars, total_refs, wikilink_count
:::

## Enrichment Priorities

| Gene | What It Does | Best For |
|------|-------------|----------|
| **RCH1** | Content expansion with blockquotes | Low-prose pages |
| **RCH2** | Quality upgrade to standard | Pages near threshold |
| **RCH3** | Add explanation section | Abstract concepts |
| **RCH4** | Add multi-perspective section | Biographical entries |
| **RFT2** | Section reordering | Disorganized pages |

## See Also

- [[quality-progression]] — Pages ranked by quality score
- [[by-quality]] — Simple quality tier listing
- [[source-density]] — Citation density metrics
