---
description: Pages ranked by total backlink count — a measure of narrative prominence and interconnectedness within the Blind Mice wiki.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "reference", "navigation", "statistics"]
type: list
---

# Most Referenced Pages

This page ranks wiki entries by how frequently they are cited from other pages — a rough proxy for each entity's importance to the novel's narrative web. [[lucy-winter]], [[nannie-merwent]], and [[john-winter]] anchor the network as the most-referenced figures, reflecting their centrality to the plot. Concepts such as [[money-and-class]] and [[gender-roles]] also appear high in the rankings, reflecting how pervasively Scott weaves social commentary into character-driven storytelling.

The backlink count is automatically computed by the wiki engine from `[[wikilink]]` references across all non-chapter pages and is refreshed whenever the backlink index is rebuilt.

::: query
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: Backlinks
sort: total_refs
order: desc
limit: 30
title: Top 30 by Backlink Count
:::

## By Type

::: query
type: person
display: list
sort: total_refs
order: desc
limit: 10
title: Most Referenced Characters
:::

::: query
type: concept
display: list
sort: total_refs
order: desc
limit: 10
title: Most Referenced Concepts
:::
