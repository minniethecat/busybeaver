---
description: Pages situated on or directly concerned with the Western Front theatre of the First World War in *Memoirs of an Infantry Officer*. Sassoon served in the Royal Welch Fusiliers on the Western Front from late 1915 through mid-1917, and this page gathers the people, places, battles, and concepts that define his frontline experience.
id: western-front-theatre
label: The Western Front
tags: ["Western Front", "index", "France", "Flanders"]
type: list
---

# The Western Front

The Western Front was the principal theatre of British military operations in the Great War,
and it is the landscape against which nearly all of *Memoirs of an Infantry Officer* unfolds.
From the billets behind the lines to the forward trenches and the casualty clearing stations,
Sassoon's narrative maps a world bounded by mud, wire, and the ever-present sound of artillery.
The pages below are dynamically drawn from entries tagged with `Western Front`.

## All Western Front Pages

::: query
tags: [Western Front]
sort: label
display: table
fields: [label, type, quality]
field_labels:
  label: Page
  type: Type
  quality: Quality
:::

## Places on the Front

::: query
tags: [Western Front]
type: place
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Place
  description: Description
  quality: Quality
:::

## Frontline Events

::: query
tags: [Western Front]
type: event
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Event
  description: Description
  quality: Quality
:::

## Frontline Concepts

::: query
tags: [Western Front]
type: concept
sort: total_refs
order: desc
limit: 20
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Concept
  total_refs: References
  quality: Quality
:::

## Notes

The `Western Front` tag is applied to pages whose content is primarily situated at or
directly concerned with the trench line and its immediate rear areas. Pages about
England or the home front carry the `home front` tag instead.
