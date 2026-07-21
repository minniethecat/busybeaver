---
description: Complete index of all wiki entries for The Gambler, organised by type — characters, concepts, events, places, and organisations.
id: master-index
label: Master Index
tags: ["index", "overview"]
type: list
---

# Master Index

This is the complete index of all entry pages in *The Gambler* wiki. Entries are grouped into five categories: Persons (characters), Concepts (themes and ideas), Events (plot points), Places (locations), and Organisations (institutions). Each section renders dynamically from the wiki's current contents.

## Characters

::: query
type: person
display: table
fields: [label, nationality, quality]
field_labels:
  label: Character
  nationality: Nationality
  quality: Quality
sort: label
order: asc
:::

## Concepts

::: query
type: concept
display: table
fields: [label, quality]
field_labels:
  label: Concept
  quality: Quality
sort: label
order: asc
:::

## Events

::: query
type: event
display: table
fields: [label, quality]
field_labels:
  label: Event
  quality: Quality
sort: label
order: asc
:::

## Places

::: query
type: place
display: table
fields: [label, quality]
field_labels:
  label: Place
  quality: Quality
sort: label
order: asc
:::

## Organisations

::: query
type: organization
display: table
fields: [label, quality]
field_labels:
  label: Organisation
  quality: Quality
sort: label
order: asc
:::

## About This Index

All sections render via `::: query` blocks and update automatically as entries are added or enriched. Quality tiers: **featured** (comprehensive), **standard** (full coverage), **basic** (essential only).
