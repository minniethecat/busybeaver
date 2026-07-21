---
description: Complete index of all persons in the End of the World wiki, sorted alphabetically
id: person-index
label: Person Index
tags: ["index", "person"]
type: list
---

# Person Index

A comprehensive listing of all persons documented in this wiki, drawn from biblical and eschatological sources.

::: query
type: person
display: table
fields: [label, era, affiliation, quality]
field_labels:
  label: Name
  era: Era
  affiliation: Affiliation
  quality: Quality
sort: label
order: asc
title: All Persons
:::

## By Era

::: query
type: person
display: table
fields: [label, era, born, died]
field_labels:
  label: Name
  era: Era
  born: Born
  died: Died
sort: era
order: asc
title: Persons by Era
:::
