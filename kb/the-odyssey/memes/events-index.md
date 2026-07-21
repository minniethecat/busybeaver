---
description: A complete index of all events in Homer's Odyssey, dynamically generated from the wiki's event entries.
id: events-index
label: Events Index
tags: ["index", "events", "narrative"]
type: list
---

# Events Index

This page catalogs all significant events in Homer's *Odyssey*, ordered alphabetically by label.
Events include battles, journeys, assemblies, recognition scenes, contests, and councils.

Each entry includes the book in which the event occurs, its type, key participants, and location.

## All Events

::: query
type: event
display: table
fields: [label, book, event_type, location, quality]
field_labels:
  label: Event
  book: Book
  event_type: Type
  location: Location
  quality: Quality
sort: label
order: asc
:::

## By Book

::: query
type: event
display: table
fields: [label, book, event_type, participants, quality]
field_labels:
  label: Event
  book: Book
  event_type: Type
  participants: Participants
  quality: Quality
sort: book
order: asc
:::
