---
description: A dynamically ranked list of the top 50 most-referenced wiki pages, ordered by total backlink count.
id: Most-Referenced
label: Most Referenced Pages
tags: ["index", "statistics", "overview"]
type: list
---

# Most Referenced Pages

This page ranks wiki entries by their total reference count — a proxy for their centrality in the Yeats poetry knowledge graph. Pages with more references are more deeply woven into the wiki's link network.

::: query
sort: total_refs
order: desc
limit: 50
display: table
fields: [label, type, quality, total_refs]
title: Top 50 by Reference Count
:::
