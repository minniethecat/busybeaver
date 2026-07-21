---
description: Chronological index of literary and historical works referenced in The Cruise of the Nona, sorted by publication year.
id: works-by-year
label: works-by-year
tags: ["index", "work", "chronology"]
type: list
---

# Works by Year

This page lists all **work** entries in the wiki in chronological order —
books, poems, essays, and other writings mentioned or discussed in
Hilaire [[hilaire-belloc|Belloc]]'s *The Cruise of [[nona|the Nona]]*.

## Works with Known Year

::: query
type: work
year: NOT NULL
sort: year
display: table
fields: [label, year, quality, description]
field_labels:
  label: Work
  year: Year
  quality: Quality
  description: Description
:::

## All Works

::: query
type: work
sort: label
display: table
fields: [label, year, quality, description]
field_labels:
  label: Work
  year: Year
  quality: Quality
  description: Description
:::
