---
description: Statistical ranking of the top 25 most-referenced entry pages in the Lady Rose's Daughter wiki, ordered by total backlink count.
id: most-referenced
label: Most Referenced Pages
tags: ["index", "statistics", "reference"]
type: list
---

# Most Referenced Pages

A statistical overview of the most heavily referenced pages in the *Lady Rose's Daughter* wiki. Backlink count serves as a proxy for narrative prominence — characters and places central to the plot accumulate the most cross-references.

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Name
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 25
:::

## How This Works

Each page's reference count is the number of other wiki pages that link to it via `[[wikilink]]` syntax. This metric reflects how frequently a character, place, event, or concept is mentioned in the context of other entries, making it a useful proxy for narrative centrality within the novel's world.

The ranking is computed automatically from the wiki's backlink graph and updated as the wiki grows.
