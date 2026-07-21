---
description: "An index of all places and locations in Wilkie Collins's Basil, grouped by setting category."
id: places-index
label: "Places Index"
tags: ["list", "index", "place"]
type: list
---

# Places Index

All places and locations in Wilkie Collins's *Basil* (1852).

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: References
sort: label
order: asc
title: All Places
:::

## By Category

::: query
type: place
tags: [London]
display: list
sort: label
order: asc
title: London Locations
:::

::: query
type: place
tags: [Cornwall]
display: list
sort: label
order: asc
title: Cornwall Locations
:::

::: query
type: place
tags: [primary]
display: list
sort: label
order: asc
title: Primary Settings
:::

::: query
type: place
tags: [interior]
display: list
sort: label
order: asc
title: Interior Spaces
:::

::: query
type: place
tags: [landscape]
display: list
sort: label
order: asc
title: Landscapes
:::

::: query
type: place
tags: [domestic]
display: list
sort: label
order: asc
title: Domestic Spaces
:::

## Most Referenced

::: query
type: place
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Place
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
limit: 10
title: Top 10 Most Referenced Places
:::
