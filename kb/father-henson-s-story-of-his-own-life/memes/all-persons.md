---
description: Index of all person entries in the wiki, sorted alphabetically by label
id: all-persons
label: All Persons
tags: ["index", "person"]
type: list
---

# All Persons

This page lists all person entries in the wiki, dynamically generated from the page registry.

## Alphabetical Index

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Name
  quality: Quality
  total_refs: References
sort: label
order: asc
:::
