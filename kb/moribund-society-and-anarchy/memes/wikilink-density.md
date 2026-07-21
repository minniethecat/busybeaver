---
description: >
id: wikilink-density
label: Pages by Wikilink Density
tags: []
type: list
---

# Pages by Wikilink Density

This index ranks all non-chapter pages by the number of wikilinks
they contain. High wikilink density indicates pages that serve as
connective hubs, referencing many other concepts, people, places,
and events throughout the wiki.

::: query
type: entry
sort: wikilink_count desc
limit: 50
columns: label, type, quality, wikilink_count, prose_chars
:::

## Understanding Wikilink Density

Pages with high wikilink counts are typically:

- **Concept hubs** — broad concepts that touch many related ideas
- **Biographical entries** — referencing people, events, and movements
- **Historical overviews** — connecting multiple events and figures

Low-density pages may be candidates for wikification (BLK3).

## See Also

- [[wikilink-hubs]] — Pages serving as wikilink hubs
- [[most-referenced]] — Pages with the most incoming backlinks
- [[prose-depth]] — Pages ranked by prose length
