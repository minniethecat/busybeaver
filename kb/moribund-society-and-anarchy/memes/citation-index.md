---
description: >
id: citation-index
label: Citation Index
tags: []
type: list
---

# Citation Index

This index ranks non-chapter pages by the number of citations
(total reference markers) they contain. High citation counts
indicate pages that are deeply grounded in Jean Grave's original
text, with extensive blockquote support.

::: query
type: entry
sort: total_refs desc
limit: 50
columns: label, type, quality, total_refs, blockquote_count, prose_chars
:::

## Reading the Citation Index

- **High citation count** — well-sourced pages with extensive textual evidence
- **Low citation count** — may need additional blockquote enrichment (RCH1)
- **Zero citations** — stubs or newly created pages awaiting enrichment

## See Also

- [[source-density]] — Pages by source density and citation metrics
- [[prose-depth]] — Pages by prose length (often correlates with citation count)
- [[quality-matrix]] — Quality scores across dimensions
