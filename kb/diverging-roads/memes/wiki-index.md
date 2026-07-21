---
description: Master index of all entry-type pages in the Diverging Roads wiki — characters, places, events, concepts, and organizations.
id: wiki-index
label: Wiki Index
tags: ["index", "master-index", "reference"]
type: list
---

## Master Index

The complete register of every entry page in the Diverging Roads wiki. Use this page to browse the full scope of documented content.

## Characters

All named persons in the novel.

::: query
type: person
display: table
fields: [label, role, affiliation, description]
field_labels:
  label: Character
  role: Role
  affiliation: Affiliation
  description: Description
sort: label
order: asc
title: Characters
:::

## Places

Every location — towns, cities, streets, buildings, and natural features.

::: query
type: place
display: table
fields: [label, location_type, region, description]
field_labels:
  label: Place
  location_type: Type
  region: Region
  description: Description
sort: label
order: asc
title: Places
:::

## Events

All documented events in the novel's narrative and historical backdrop.

::: query
type: event
display: table
fields: [label, date, location, description]
field_labels:
  label: Event
  date: Date
  location: Location
  description: Description
sort: label
order: asc
title: Events
:::

## Concepts and Themes

The ideas, motifs, and themes that shape the novel's meaning.

::: query
type: concept
display: table
fields: [label, category, description]
field_labels:
  label: Concept
  category: Category
  description: Description
sort: label
order: asc
title: Concepts
:::

## Organizations

Businesses, clubs, banks, and institutions.

::: query
type: organization
display: table
fields: [label, org_type, location, description]
field_labels:
  label: Organization
  org_type: Type
  location: Location
  description: Description
sort: label
order: asc
title: Organizations
:::

## About This Index

This master index is automatically generated from all entry-type pages in the wiki. It serves as a comprehensive browsing entry point for the full scope of documented content. Chapter pages, overview pages, and other list pages are excluded from this index.
