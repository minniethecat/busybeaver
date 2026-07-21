---
description: |
id: most-cited-pages
label: Most Cited Pages
tags: ["index", "ranking", "reference", "popular"]
type: list
---

# Most Cited Pages

The pages listed here are the most frequently cross-referenced entries across the wiki.
A high reference count signals a character, place, or concept central to multiple tales
and chapters — the connective tissue of Irish mythological narrative as Stephens retold it.

::: query
sort: total_refs desc
limit: 30
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
title: Top 30 Most Referenced Pages
:::

## About This Ranking

Reference counts are drawn from the wiki's internal link network. Each reference
represents a wikilink pointing to this page from another entry, chapter, or list page.
Pages with the highest reference counts are typically those central to the Fenian Cycle —
Fionn mac Uail, the Fianna, and the major sites of Irish myth.
