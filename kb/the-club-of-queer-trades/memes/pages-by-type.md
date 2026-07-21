---
description: All entry pages grouped by their content type — persons, concepts, organizations, places, and events.
id: pages-by-type
label: Pages by Type
tags: ["index", "navigation", "type"]
type: list
---

# Pages by Type

Entry pages grouped by their content type. Each section below displays all pages of that type,
sorted by reference count to surface the most significant entries first.

## Persons

::: query
type: person
display: table
fields: [label, quality, affiliation, total_refs]
field_labels:
  label: Person
  quality: Quality
  affiliation: Affiliation
  total_refs: Refs
sort: total_refs
order: desc
:::

## Concepts

::: query
type: concept
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: Refs
sort: total_refs
order: desc
:::

## Organizations

::: query
type: organization
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Organization
  quality: Quality
  total_refs: Refs
sort: total_refs
order: desc
:::

## Places

::: query
type: place
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Place
  quality: Quality
  total_refs: Refs
sort: total_refs
order: desc
:::

## Events

::: query
type: event
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Event
  quality: Quality
  total_refs: Refs
sort: total_refs
order: desc
:::
