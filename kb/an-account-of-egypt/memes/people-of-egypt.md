---
id: people-of-egypt
label: People of Egypt
type: list
description: 'A comprehensive index of all historical and mythological figures of ancient Egypt documented in this wiki'
tags: ["ancient-egypt", "people", "index", "biography"]
---

# People of Egypt

This page provides a complete, dynamically generated directory of every person page in the wiki — from pharaohs and priests to foreign rulers and mythological figures connected to Egypt. Entries are sorted alphabetically by label for easy browsing.

## All Figures

::: query
type: person
display: table
fields: [label, era, quality, total_refs]
field_labels:
  label: Name
  era: Era
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: Complete Person Index
:::

## Featured Biographies

The most thoroughly developed biographical entries, meeting the wiki's highest quality standards.

::: query
type: person
quality: featured
display: table
fields: [label, era, total_refs]
field_labels:
  label: Name
  era: Era
  total_refs: Citations
sort: total_refs
order: desc
title: Featured Biographies
:::
