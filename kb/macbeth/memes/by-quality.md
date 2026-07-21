---
description: A quality-tier index of all entry pages in the Macbeth wiki, grouped by quality level — from featured flagship pages through standard entries to basic stubs.
id: by-quality
label: By Quality
tags: ["index", "quality", "meta"]
type: list
---

# By Quality

This page groups all entry pages by their quality tier, making it easy to see at a glance which pages are the wiki's strongest and which still need enrichment.

## Featured Pages

These are the wiki's flagship entries — fully developed pages with substantial analysis, multiple citations, and cross-references.

::: query
quality: featured
display: table
fields: [label, type, total_refs, wikilink_count]
field_labels:
  label: Page
  type: Type
  total_refs: References
  wikilink_count: Wikilinks
sort: total_refs
order: desc
title: Featured Pages
:::

## Standard Pages

The core content of the wiki — well-structured entries with adequate coverage.

::: query
quality: standard
display: table
fields: [label, type, total_refs, wikilink_count]
field_labels:
  label: Page
  type: Type
  total_refs: References
  wikilink_count: Wikilinks
sort: total_refs
order: desc
limit: 50
title: Top 50 Standard Pages
:::

## Basic Pages

Entries that have been created but still need substantial enrichment.

::: query
quality: basic
display: table
fields: [label, type]
field_labels:
  label: Page
  type: Type
sort: label
order: asc
title: Basic Pages (Needs Enrichment)
:::
