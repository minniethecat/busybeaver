---
description: Top 50 most-cited entry pages across all types in the Culture and Anarchy wiki, ranked by total cross-reference count.
id: most-cited
label: Most Cited Pages
tags: []
type: list
---

# Most Cited Pages

This page ranks the fifty most-referenced entry pages in the wiki,
measured by the total number of wikilinks pointing to each page. High
citation counts signal pages that serve as hubs in the intellectual
network of Arnold's *Culture and Anarchy* — concepts, persons, and
institutions that the text returns to repeatedly.

::: query
type: NOT NULL
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: Citations
sort: total_refs
order: desc
limit: 50
:::

## About This Index

Citation counts are computed automatically by the wiki engine from
wikilink cross-references (`[[...]]`) across all pages. `total_refs`
reflects the number of distinct pages that link to a given page. The
index excludes chapter and overview pages, which have different citation
dynamics from the encyclopedic entries that make up the wiki's core.
