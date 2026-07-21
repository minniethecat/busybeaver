---
description: >
id: prose-depth
label: Pages by Prose Depth
tags: []
type: list
---

# Pages by Prose Depth

This index ranks all non-chapter pages by prose character count,
from longest to shortest. Longer pages typically indicate deeper
coverage and more thorough treatment of their subject.

::: query
type: entry
sort: prose_chars desc
limit: 50
columns: label, type, quality, prose_chars, wikilink_count
:::

## Reading the Depth Index

Pages with higher prose counts have received more enrichment rounds.
These pages are typically the best starting points for readers seeking
comprehensive coverage. Pages near the bottom may be candidates for
future enrichment.

## See Also

- [[source-density]] — Pages by citation and source reference density
- [[quality-matrix]] — Quality scores across all pages
- [[most-referenced]] — Pages with the most backlinks
