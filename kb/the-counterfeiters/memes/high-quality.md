---
description: Curated selection of the highest-quality pages in The Counterfeiters wiki — featured and premium entries.
id: high-quality
label: Featured & Premium Pages
tags: ["featured", "premium", "curated", "index"]
type: list
---

# Featured & Premium Pages

A curated view of the wiki's highest-quality entries — those rated `featured` or `premium` by the quality assessment system. These pages have comprehensive prose, multiple blockquote citations, structured sections, and cross-references.

::: query
quality: featured
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
:::

## Premium Pages

::: query
quality: premium
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
:::

## See also

- [[most-referenced]] — top 30 pages by reference count
- [[characters]] — full character index
