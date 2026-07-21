---
id: egyptian-pharaohs-index
label: Egyptian Pharaohs Index
type: list
description: 'A dynamic index of Egyptian rulers and pharaohs mentioned by Herodotus, ordered by citation count'
tags: ["index", "pharaoh", "ancient-egypt"]
---

# Egyptian Pharaohs Index

Herodotus recorded the names and deeds of numerous Egyptian rulers, from the pyramid builders to the contemporaries of the Persian conquest. This page dynamically indexes all wiki entries tagged as pharaohs or Egyptian kings.

::: query
tags: [pharaoh]
display: table
fields: [label, affiliation, era, total_refs]
field_labels:
  label: Ruler
  affiliation: Dynasty
  era: Era
  total_refs: Citations
sort: total_refs
order: desc
title: Pharaohs by Citation Count
:::

::: query
tags: [egyptian-king]
display: table
fields: [label, affiliation, era, total_refs]
field_labels:
  label: Ruler
  affiliation: Dynasty
  era: Era
  total_refs: Citations
sort: label
order: asc
title: Other Egyptian Kings
:::
