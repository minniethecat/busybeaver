---
description: Query-based index of all concept entities in the wiki, sorted alphabetically by label.
id: index-of-concepts
label: Index of Concepts
tags: ["index", "concept"]
type: list
---

# Index of Concepts

This page dynamically lists all concept entities in the wiki.

::: query
type: concept
sort: label
order: asc
display: table
fields: [label, tags]
field_labels:
  label: Concept
  tags: Tags
:::

## See Also

- [[person-index|Person Index]]
- [[index-of-organizations|Index of Organizations]]
