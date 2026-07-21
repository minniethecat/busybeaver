---
description: Curated list of the highest-quality articles in The Consolation of Philosophy wiki.
id: featured-entries
label: Featured Entries
tags: ["index", "navigation", "curation"]
type: list
---

# Featured Entries

A curated selection of the wiki's finest articles — those that have reached **featured** or **premium** quality through rigorous enrichment, citation, and review. These pages represent the best of what this knowledge base offers on Boethius's *The Consolation of Philosophy*.

::: query
type: NOT NULL
quality: featured
display: table
fields: [label, type, total_refs]
field_labels:
  label: Title
  type: Type
  total_refs: References
sort: label
order: asc
title: Featured Articles
:::

::: query
type: NOT NULL
quality: premium
display: table
fields: [label, type, total_refs]
field_labels:
  label: Title
  type: Type
  total_refs: References
sort: label
order: asc
title: Premium Articles
:::

## Quality Standards

Articles earn **featured** status through comprehensive prose coverage, adequate inline citations (PN references), and well-structured sections. **Premium** articles meet additional criteria including multi-perspective analysis and exceptional scholarly depth.
