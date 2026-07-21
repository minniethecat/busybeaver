---
description: Entry pages grouped by quality tier — from featured down to basic.
id: pages-by-quality
label: Pages by Quality
tags: ["index", "quality", "maintenance", "list"]
type: list
---

# Pages by Quality

Entry pages in the [[our-american-cousin-play|Our American Cousin]] wiki, grouped by quality tier. Higher-quality pages have richer prose, denser citations, and more complete frontmatter.

## Featured Pages

::: query
quality: featured
sort: total_refs
order: desc
columns: [label, type, total_refs, description]
:::

## Standard Pages

::: query
quality: standard
sort: label
columns: [label, type, description]
:::

## Basic Pages

::: query
quality: basic
sort: label
columns: [label, type, description]
:::

## See Also

- [[top-referenced|Most Referenced Pages]] — sorted by backlink count
- [[all-pages|Complete Page Index]] — all pages alphabetically
