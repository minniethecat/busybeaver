---
description: Complete index of all person pages in The Dead Letter wiki, sorted alphabetically by label.
id: person-index
label: Person Index
tags: ["index", "person"]
type: list
---

# Person Index

This page aggregates all [[honor-and-reputation|character]] entries in the wiki. The table is dynamically generated from
frontmatter data — no manual list maintenance is required.

::: query
type: person
display: table
fields: [label, role, affiliation, quality]
field_labels:
  label: Name
  role: Role
  affiliation: Affiliation
  quality: Quality
sort: label
order: asc
title: All Characters
:::
