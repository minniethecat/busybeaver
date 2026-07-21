---
description: A dynamic ranking of the most-referenced pages across the Vanity Fair wiki. Sorted by total backlinks, showing which characters, places, and concepts appear most frequently in other pages.
id: popular-pages
label: Most Referenced Pages
tags: ["index", "ranking", "navigation", "discovery"]
type: list
---

# Most Referenced Pages

This page presents a dynamically-generated ranking of the most cross-referenced entries in the *Vanity Fair* wiki. Backlink count serves as a proxy for each topic's narrative centrality — characters like Rebecca Sharp and Amelia Sedley top the list because they appear in nearly every chapter's analysis.

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Backlinks
sort: total_refs
order: desc
limit: 50
title: Top 50 Most Referenced Pages
:::

## Notes

- Backlink counts are automatically computed from the wiki's link graph and reflect how many other pages contain `[[wikilinks]]` to each entry.
- This ranking is dynamic — it updates automatically as new pages are created and existing pages gain new references.
- The top entries (Rebecca Sharp, Amelia Sedley, George Osborne) consistently dominate because they are the novel's central figures.
