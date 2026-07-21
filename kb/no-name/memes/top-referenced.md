---
description: Pages with the highest cross-reference counts in the No Name wiki, indicating their centrality to the novel's narrative and themes.
id: top-referenced
label: top-referenced
tags: ["index", "statistics"]
type: list
---

# Most Referenced Pages

This page highlights the most heavily cross-referenced articles in the *No Name* wiki. A high reference count typically indicates a character, event, or concept that appears across multiple chapters and intersects with numerous other elements of the novel. These pages serve as natural entry points for exploring the wiki's connective tissue.

::: query
display: table
fields: [label, type, quality, total_refs, prose_chars]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
  prose_chars: Article Length
sort: total_refs
order: desc
limit: 25
title: Top 25 by Reference Count
:::
