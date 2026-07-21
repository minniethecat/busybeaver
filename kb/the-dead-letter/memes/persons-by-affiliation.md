---
description: Person pages grouped by their professional or institutional affiliation, as recorded in frontmatter.
id: persons-by-affiliation
label: Persons by Affiliation
tags: ["index", "person", "affiliation"]
type: list
---

# Persons by Affiliation

This page groups [[honor-and-reputation|character]] entries by their professional or institutional affiliation.
The query blocks are dynamically generated — no manual list maintenance is required.

::: query
type: person
affiliation: NOT NULL
display: table
fields: [label, role, affiliation, quality]
field_labels:
  label: Name
  role: Role
  affiliation: Affiliation
  quality: Quality
sort: affiliation
order: asc
title: Characters with Recorded Affiliations
:::
