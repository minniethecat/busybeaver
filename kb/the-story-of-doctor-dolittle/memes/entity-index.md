---
description: Complete index of all entities in the wiki — people, animals, places, events, and concepts — ranked by cross-reference count for quick navigation.
id: entity-index
label: Entity Index
tags: ["index", "overview", "reference"]
type: list
---

# Entity Index

This master index provides a single entry point to every entity in [[john-dolittle|the Doctor]] Dolittle wiki. Pages are ranked by how often they are referenced across the wiki, helping readers find the most connected and significant topics first.

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: People
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::

::: query
type: animal
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Animals
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Places
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::

::: query
type: event
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Events
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::

::: query
type: concept
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concepts
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 50
:::
