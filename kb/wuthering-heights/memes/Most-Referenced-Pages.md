---
description: Statistical ranking of the most cross-referenced pages in the Wuthering Heights wiki, ordered by total reference count.
id: Most-Referenced-Pages
label: Most Referenced Pages
tags: ["index", "statistics", "ranking"]
type: list
---

# Most Referenced Pages

This page presents the most heavily cross-referenced entries in the Wuthering Heights wiki.
Reference count — the number of other wiki pages that link to a given entry via `[[wikilinks]]` —
serves as a proxy for a topic's centrality to the novel's narrative and thematic structure.

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
limit: 50
:::

## Notes

- `total_refs` is computed automatically from the backlinks index and updated whenever pages are added or edited.
- Chapter pages are excluded from this ranking to focus on entity-level entries (characters, places, concepts, events).
- A high reference count indicates dense narrative interconnection — the character or theme appears across many chapters and intersects with many other entities.
