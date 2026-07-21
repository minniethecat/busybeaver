---
description: Cross-tabulation of quality tiers by page type — a structural overview of the wiki's content maturity across concepts, persons, events, organizations, and places.
id: quality-matrix
label: Quality Matrix
tags: ["index", "quality", "navigation"]
type: list
---

How mature is each section of the wiki? This page groups all entries by their type and quality tier, making it easy to see which areas are well-developed and which still need attention. Three quality tiers are displayed: **basic** (functional coverage), **standard** (solid with quotes and structure), and **featured** (flagship pages with comprehensive treatment).

## Concepts by Quality

::: query
type: concept
quality: basic
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

::: query
type: concept
quality: standard
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

::: query
type: concept
quality: featured
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

## Persons by Quality

::: query
type: person
quality: basic
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

::: query
type: person
quality: standard
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

::: query
type: person
quality: featured
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

## Events by Quality

::: query
type: event
quality: basic
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

::: query
type: event
quality: standard
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

## Organizations by Quality

::: query
type: organization
quality: basic
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

::: query
type: organization
quality: standard
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

## Places by Quality

::: query
type: place
quality: basic
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::

::: query
type: place
quality: standard
display: table
fields: [label, quality_score, prose_chars, total_refs]
field_labels:
  label: Page
  quality_score: Score
  prose_chars: Characters
  total_refs: References
sort: label
order: asc
:::
