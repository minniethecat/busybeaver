---
description: Index of organizations, institutions, and criminal networks in The Lone Wolf (1914).
id: organizations
label: Organizations
tags: ["organization-index"]
type: list
---

# Organizations in The Lone Wolf

A directory of every organization that shapes the world of *The Lone Wolf*: the criminal Pack, Scotland Yard, the French government, and the institutions caught between them.

::: query
type: organization
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Organization
  quality: Quality
  total_refs: References
sort: label
order: asc
title: All Organizations
:::

## Featured Organizations

The most significant institutions:

::: query
type: organization
quality: featured
display: table
fields: [label, total_refs, total_chapters]
field_labels:
  label: Organization
  total_refs: References
  total_chapters: Chapters
sort: total_refs
order: desc
title: Featured Organizations
:::
