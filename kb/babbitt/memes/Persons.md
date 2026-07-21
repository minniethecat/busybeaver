---
description: Complete index of all person entities in the Babbitt wiki, dynamically rendered from page frontmatter.
id: Persons
label: Persons
tags: ["index", "persons", "characters"]
type: list
---

# Persons

This page provides a complete, dynamically-rendered index of all persons documented in the Babbitt wiki. It draws on the characters who populate Sinclair Lewis's satirical portrait of Zenith — from the central figures like George Babbitt and Paul Riesling to the minor figures who fill the city's business clubs, dinner parties, and church committees. The listing updates automatically as pages are created or enriched.

::: query
type: person
display: table
fields: [label, quality, cat]
field_labels:
  label: Name
  quality: Quality
  cat: Role
sort: label
order: asc
:::

## About This Index

The persons documented in this wiki span the full social spectrum of Zenith. Central characters like George F. Babbitt and Paul Riesling anchor the narrative, while supporting figures — business associates, club members, family relations, and chance acquaintances — fill out the city's social fabric. Each person page includes biographical details, key scenes, character traits, and relationships to other figures.

The `cat` field classifies characters as major, supporting, or minor, reflecting their narrative significance in the novel. Quality levels indicate the depth of documentation: **featured** pages serve as exemplars of the person template, **standard** pages provide comprehensive coverage, and **basic** pages offer essential information awaiting further enrichment.
