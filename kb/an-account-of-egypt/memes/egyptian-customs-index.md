---
id: egyptian-customs-index
label: Egyptian Customs Index
type: list
description: 'A dynamic index of Egyptian customs documented by Herodotus, organized by era and quality'
tags: ["index", "customs", "overview"]
---

# Egyptian Customs Index

Herodotus devoted extensive attention to Egyptian customs, describing practices ranging from daily habits to religious rituals. This page dynamically indexes all wiki entries tagged under "customs," allowing readers to browse by era and quality tier.

::: query
tags: [customs]
display: table
fields: [label, era, quality, total_refs]
field_labels:
  label: Custom
  era: Era
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: All Egyptian Customs
:::

::: query
tags: [customs]
quality: featured
display: table
fields: [label, era, total_refs]
field_labels:
  label: Custom
  era: Era
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Customs Pages
:::
