---
description: Complete index of all characters in Charlotte Temple, sorted alphabetically with quality indicators.
id: person-index
label: Person Index
tags: ["index", "person", "character"]
type: list
---

# Person Index

This page provides a complete, dynamically-rendered index of all person entries in the Charlotte Temple wiki. Each entry links to a dedicated character page with biographical details, narrative role, and cited passages.

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: All Characters
:::

## By Citation Count

Characters with the most cross-references tend to be central to the novel's plot and moral framework.

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: Citations
sort: total_refs
order: desc
limit: 20
title: Most Referenced Characters
:::
