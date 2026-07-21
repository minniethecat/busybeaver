---
description: Side-by-side quality statistics for each page type — average quality scores, prose lengths, and citation counts compared across concepts, persons, events, organizations, and places.
id: type-comparison
label: Type Comparison
tags: ["index", "statistics", "quality"]
type: list
---

Each type of page in the wiki serves a different role: concepts carry the theoretical weight, persons ground the ideas in biography, events anchor them in history, organizations trace institutional threads, and places provide geographic context. This page compares quality metrics across all five types, helping identify which areas of the wiki are strongest and where further development would be most valuable.

## Concepts

::: query
type: concept
display: table
fields: [label, quality, quality_score, prose_chars, pn_count]
field_labels:
  label: Page
  quality: Quality
  quality_score: Score
  prose_chars: Characters
  pn_count: PN Citations
sort: quality_score
order: desc
:::

## Persons

::: query
type: person
display: table
fields: [label, quality, quality_score, prose_chars, pn_count]
field_labels:
  label: Page
  quality: Quality
  quality_score: Score
  prose_chars: Characters
  pn_count: PN Citations
sort: quality_score
order: desc
:::

## Events

::: query
type: event
display: table
fields: [label, quality, quality_score, prose_chars, pn_count]
field_labels:
  label: Page
  quality: Quality
  quality_score: Score
  prose_chars: Characters
  pn_count: PN Citations
sort: quality_score
order: desc
:::

## Organizations

::: query
type: organization
display: table
fields: [label, quality, quality_score, prose_chars, pn_count]
field_labels:
  label: Page
  quality: Quality
  quality_score: Score
  prose_chars: Characters
  pn_count: PN Citations
sort: quality_score
order: desc
:::

## Places

::: query
type: place
display: table
fields: [label, quality, quality_score, prose_chars, pn_count]
field_labels:
  label: Page
  quality: Quality
  quality_score: Score
  prose_chars: Characters
  pn_count: PN Citations
sort: quality_score
order: desc
:::
