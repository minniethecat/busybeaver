---
description: "A thematic index of all concepts and themes in Wilkie Collins's Basil, grouped by category."
id: concepts-index
label: "Concepts & Themes Index"
tags: ["list", "index", "concept"]
type: list
---

# Concepts & Themes Index

All concepts and themes identified in Wilkie Collins's *Basil* (1852).

::: query
type: concept
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: References
sort: label
order: asc
title: All Concepts & Themes
:::

## By Category

::: query
type: concept
tags: [moral]
display: list
sort: label
order: asc
title: Moral Concepts
:::

::: query
type: concept
tags: [psychological]
display: list
sort: label
order: asc
title: Psychological Concepts
:::

::: query
type: concept
tags: [social]
display: list
sort: label
order: asc
title: Social Concepts
:::

::: query
type: concept
tags: [narrative]
display: list
sort: label
order: asc
title: Narrative Concepts
:::

::: query
type: concept
tags: [theme]
display: list
sort: label
order: asc
title: Major Themes
:::

::: query
type: concept
tags: [emotion]
display: list
sort: label
order: asc
title: Emotions
:::

## Most Referenced

::: query
type: concept
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Concept
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
limit: 15
title: Top 15 Most Referenced Concepts
:::
