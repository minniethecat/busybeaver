---
description: Pages ranked by number of primary-source citations (PN annotations), revealing which entries have the strongest textual grounding.
id: citation-index
label: Citation Index
tags: ["quality", "citations", "sourcing"]
type: list
---

# Citation Index

This page ranks all wiki entries by their primary-source citation count — the
number of `[chapter-paragraph]` (PN) annotations linking claims to specific
passages in Balzac's _Albert Savarus_. Pages with higher citation counts have
the most thorough textual grounding; those with lower counts may need additional
source-work in future enrichment rounds.

::: query
display: table
fields: [label, type, pn_count, blockquote_count, total_refs]
field_labels:
  label: Page
  type: Type
  pn_count: PN Citations
  blockquote_count: Blockquotes
  total_refs: Total References
sort: pn_count
order: desc
limit: 50
:::

## Reading Citation Counts

**PN Citations** count individual `[NNN-PPP]` annotations in the page body.
**Blockquotes** count `>` -formatted block quotations, each of which should bear
a PN annotation. A high PN-to-blockquote ratio indicates dense, well-sourced
prose. Pages with zero PN citations rely entirely on chapter-level attribution
and may benefit from targeted source-work.
