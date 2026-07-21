---
description: The most-referenced 50 pages in the wiki, ranked by total backlink count.
id: top-referenced
label: Top Referenced Pages
tags: ["list", "statistics", "reference"]
type: list
---

## Most Referenced Pages

The pages most frequently linked to from other wiki entries — a proxy for narrative centrality and thematic importance in the novel.

::: query

filter: total_refs > 0
sort: total_refs desc
limit: 50
fields: label, type, quality, total_refs, description

:::
