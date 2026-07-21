---
description: All literary, musical, philosophical, and artistic works mentioned or alluded to in Hermann Hesse's Steppenwolf, sorted alphabetically.
id: works-and-references
label: Works & Cultural References
tags: ["index", "work", "cultural-reference", "list"]
type: list
---

# Works & Cultural References

[[harry-haller|Harry Haller]] carries "the complete works of [[bach|Bach]] and [[haydn|Haydn]]" in his head — this page catalogues every work of art, music, literature, and philosophy that appears in [[steppenwolf-novel|Steppenwolf]], forming the cultural universe the novel inhabits. The table is dynamically generated from `type: work` entries.

## All Works

::: query
type: work
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Work
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Most Referenced Works

::: query
type: work
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Work
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 10
:::
