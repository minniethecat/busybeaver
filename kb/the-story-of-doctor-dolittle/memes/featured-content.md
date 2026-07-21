---
description: Curated showcase of the finest pages in the Doctor Dolittle wiki — featured and standard-quality entries ranked by cross-reference count, plus the most-connected entries across the entire wiki.
id: featured-content
label: Featured Content
tags: ["index", "featured", "highlights", "quality"]
type: list
---

# Featured Content

The [[john-dolittle|Doctor Dolittle]] wiki's best work — a curated view of featured and high-quality pages, plus the most interconnected entries that form the backbone of the knowledge graph.

## Featured & Premium Pages

The wiki's flag[[voyage-and-sailing|ship]] pages — each has been deepened with rich prose, multiple perspectives, and well-sourced quotations.

::: query
quality: featured
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
title: Featured & Premium Pages
:::

## Standard & Above

Pages at or above the standard quality threshold, ranked by how often they are referenced throughout the wiki.

::: query
quality: standard
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
title: Standard Quality Pages
:::

## Most Referenced Pages

The most interconnected nodes in [[john-dolittle|the Doctor]] Dolittle knowledge graph — these pages are cited most often by other entries.

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Person
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
title: Most Referenced — People
:::

::: query
type: animal
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Animal
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
title: Most Referenced — Animals
:::

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
title: Most Referenced — Places
:::

::: query
type: event
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
title: Most Referenced — Events
:::

::: query
type: concept
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
title: Most Referenced — Concepts
:::
