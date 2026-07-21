---
description: "Complete index of places and locations in George Eliot's The Mill on the Floss, organized by type and significance"
id: places
label: "Places of The Mill on the Floss"
tags: ["index", "place", "location", "geography", "reference"]
type: list
---

# Places of The Mill on the Floss

This page provides a dynamically generated index of all places and locations in George Eliot's *The Mill on the Floss*. The listing draws from the structured metadata of each place page and is organized by location type and narrative significance.

## All Places (Alphabetical)

::: query
type: place
display: table
fields: [label, location_type, significance, quality]
field_labels:
  label: Place
  location_type: Type
  significance: Significance
  quality: Quality
sort: label
order: asc
:::

## By Type

### Towns and Settlements

::: query
type: place
tags: [town, settlement]
display: table
fields: [label, significance, quality]
field_labels:
  label: Place
  significance: Significance
  quality: Quality
sort: label
order: asc
:::

### Rivers and Natural Features

::: query
type: place
tags: [river, natural-area]
display: table
fields: [label, significance, quality]
field_labels:
  label: Place
  significance: Significance
  quality: Quality
sort: label
order: asc
:::

### Houses and Buildings

::: query
type: place
tags: [house, mill]
display: table
fields: [label, significance, quality]
field_labels:
  label: Place
  significance: Significance
  quality: Quality
sort: label
order: asc
:::

## Central and Symbolic Places

::: query
type: place
significance: central
display: table
fields: [label, location_type, quality]
field_labels:
  label: Place
  location_type: Type
  quality: Quality
sort: label
order: asc
:::

## Notes

- Place pages are built from close reading of the novel's geographical references.
- The River Floss and Dorlcote Mill serve as central symbolic landscapes throughout the narrative.
- St. Ogg's is the primary social setting for most of the novel's action.
