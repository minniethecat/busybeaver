---
description: "All wiki entries grouped by quality tier, with type breakdowns. Tracks the wiki's content maturity from basic stub-replacements through standard pages to the featured showcase."
id: quality-overview
label: "Quality Overview"
tags: ["index", "quality", "meta"]
type: list
---

This meta-page tracks the quality distribution of the 168 entry pages. Each tier represents a distinct level of content maturity: **basic** pages carry at least two PN citations and complete frontmatter; **standard** pages add richer prose and denser citation; **featured** pages are polished showcases ready for the home page.

## Featured (8 entries)

::: query
quality: featured
display: table
fields: [label, type, era, total_refs]
field_labels:
  label: Entry
  type: Type
  era: Era
  total_refs: References
sort: total_refs
order: desc
:::

## Standard (95 entries)

::: query
quality: standard
display: table
fields: [label, type, era, total_refs]
field_labels:
  label: Entry
  type: Type
  era: Era
  total_refs: References
sort: label
order: asc
limit: 50
:::

## Basic (65 entries)

::: query
quality: basic
display: table
fields: [label, type, era, total_refs]
field_labels:
  label: Entry
  type: Type
  era: Era
  total_refs: References
sort: label
order: asc
limit: 50
:::
