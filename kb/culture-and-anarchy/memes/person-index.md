---
description: Complete index of all person pages in the Culture and Anarchy wiki, sorted alphabetically with quality tier and nationality.
id: person-index
label: Person Index
tags: []
type: list
---

# Person Index

This page provides a complete, dynamically-rendered index of all person
pages in the wiki. Each entry links to its full page. The table is
generated automatically from frontmatter fields and updates as new
person pages are added.

::: query
type: person
display: table
fields: [label, nationality, quality, total_refs]
field_labels:
  label: Name
  nationality: Nationality
  quality: Quality
  total_refs: Citations
sort: label
order: asc
:::

## About This Index

The index draws on the `type: person` filter and renders three
frontmatter fields — nationality, quality tier, and total citation count —
alongside each person's display label. All data comes from the
frontmatter of individual person pages, maintained through the wiki's
standard add/edit workflow. No manual list curation is required.
