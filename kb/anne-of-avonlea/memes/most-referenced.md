---
description: Statistical ranking of the most cross-referenced pages in the Anne of Avonlea wiki.
id: most-referenced
label: Most Referenced Pages
tags: ["index", "stats"]
type: list
---

# Most Referenced Pages

This page ranks wiki pages by how often they are referenced from other pages — a measure of their centrality in the *[[anne-shirley|Anne]] of [[avonlea|Avonlea]]* knowledge graph. The ranking is computed dynamically from the wiki's backlink index.

::: query
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
limit: 30
:::

## About This Ranking

The reference count (`total_refs`) measures how many other wiki pages link to a given page using `[[wikilink]]` syntax. Highly-referenced pages tend to be:

- Major characters like [[Anne Shirley]] and [[Gilbert Blythe]]
- Key locations like [[Green Gables]] and [[Avonlea]]
- Central concepts like [[love]] and [[imagination]]

This metric reflects the wiki's internal link structure, not external popularity. It serves as a navigation aid for readers exploring the wiki's most connected content.
