---
description: A complete index of all characters appearing in The Borough Treasurer, sorted alphabetically.
id: persons
label: All Characters
tags: ["index", "character"]
type: list
---

# All Characters

This page presents a comprehensive, dynamically-rendered index of every character who appears in *The Borough Treasurer* by J.S. Fletcher. Characters are drawn from all 31 chapters and span the novel's intersecting spheres: municipal politics, legal proceedings, business dealings, and domestic life.

## Alphabetical Index

::: query
type: person
display: table
fields: [label, role, total_refs]
field_labels:
  label: Character
  role: Role
  total_refs: References
sort: label
order: asc
:::

## By Reference Count

::: query
type: person
display: table
fields: [label, total_refs]
field_labels:
  label: Character
  total_refs: References
sort: total_refs
order: desc
limit: 20
:::
