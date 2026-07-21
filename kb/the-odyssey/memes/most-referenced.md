---
description: A statistical ranking of the most-referenced pages across the Odyssey wiki, ordered by total cross-reference count.
id: most-referenced
label: Most Referenced Pages
tags: ["index", "statistics"]
type: list
---

# Most Referenced Pages

This page ranks wiki entries by their total reference count (`total_refs`) — the number of internal wikilinks pointing to each page. High reference counts indicate central figures, locations, and concepts that appear throughout the *Odyssey* and are frequently linked from other entries.

::: query
sort: total_refs
order: desc
limit: 50
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
title: Top 50 Most Referenced Pages
:::

The `total_refs` metric is automatically computed from the wiki's backlinks index and reflects all incoming wikilinks across the entire page corpus.
