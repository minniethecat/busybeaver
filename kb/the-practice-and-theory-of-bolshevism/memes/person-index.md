---
description: Query-based index of all person entities in the wiki, sorted alphabetically by label.
id: person-index
label: Person Index
tags: ["index", "person"]
type: list
---

# Person Index

This page dynamically lists all person entities in the wiki.

::: query
type: person
sort: label
order: asc
display: table
fields: [label, nationality, affiliation, born, died]
field_labels:
  label: Name
  nationality: Nationality
  affiliation: Affiliation
  born: Born
  died: Died
:::

## See Also

- [[index-of-concepts|Index of Concepts]]
- [[index-of-organizations|Index of Organizations]]
