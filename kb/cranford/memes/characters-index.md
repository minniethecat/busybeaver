---
description: Complete index of all characters appearing in Elizabeth Gaskell's Cranford, dynamically generated from the wiki knowledge base.
id: characters-index
label: Characters Index
tags: ["index", "characters"]
type: list
---

# Characters Index

This page aggregates all character entries in the Cranford wiki. Each entry links to a dedicated page with biographical details, narrative role, and key scenes. The table is generated dynamically from frontmatter metadata and reflects the current state of the wiki.

## All Characters

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Name
  quality: Quality
  total_refs: Refs
sort: label
order: asc
:::

## Notes

This index is rendered dynamically from the wiki's knowledge base. Entries are listed as stored in frontmatter; no manual curation is applied. Quality ratings follow the wiki's five-tier system (stub, basic, standard, featured, premium). The Refs column shows the total number of incoming wikilinks.
