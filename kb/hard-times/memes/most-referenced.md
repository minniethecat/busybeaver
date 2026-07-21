---
description: >-
id: most-referenced
label: Most Referenced Pages
tags: ["index", "statistics", "backlinks"]
type: list
---

# Most Referenced Pages

A ranked listing of the most interconnected entries in the *Hard Times* knowledge base. Higher backlink counts indicate concepts, characters, and places that figure prominently across multiple entries, reflecting their centrality to Dickens' novel.

::: query
{
  "sort": "total_refs",
  "sort_direction": "desc",
  "limit": 50,
  "fields": ["label", "type", "quality", "description"]
}
:::

## About This Index

The backlink count for each entry is the number of other wiki pages that link to it. Pages with many backlinks tend to be central characters and recurring themes that appear throughout the novel. This ranking is automatically updated as new pages are added and wikified.
