---
id: featured-articles
label: Featured Articles
type: list
description: 'A curated list of featured and premium content across all entity types in "An Account of Egypt"'
tags: ["index", "featured", "overview"]
---

# Featured Articles

This page brings together all featured and premium-quality pages in this wiki, providing a single entry point for the best-curated content derived from Herodotus's "An Account of Egypt."

::: query
type: person
quality: featured
display: table
fields: [label, affiliation, total_refs]
field_labels:
  label: Person
  affiliation: Affiliation
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Persons
:::

::: query
type: place
quality: featured
display: table
fields: [label, era, total_refs]
field_labels:
  label: Place
  era: Era
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Places
:::

::: query
type: concept
quality: featured
display: table
fields: [label, era, total_refs]
field_labels:
  label: Concept
  era: Era
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Concepts
:::
