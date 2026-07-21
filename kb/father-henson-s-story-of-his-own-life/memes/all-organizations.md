---
description: Index of all organization entries in the wiki, sorted by reference count
id: all-organizations
label: All Organizations
tags: ["index", "organization"]
type: list
---

# All Organizations

This page lists all organization entries in the wiki, dynamically generated from the page registry.

## By Reference Count

::: query
type: organization
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Organization
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
:::
