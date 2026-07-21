---
description: A complete index of all organizations, institutions, and formal bodies in The Borough Treasurer, sorted alphabetically.
id: organizations
label: Organizations & Institutions
tags: ["index", "institution"]
type: list
---

# Organizations & Institutions

This page presents a dynamically-rendered index of every organization, institution, and formal body that appears in *The Borough Treasurer* by J.S. Fletcher. From the municipal offices of Highmarket Borough Council to the building societies, courts, and commercial enterprises that drive the plot, these organizations form the institutional skeleton of the novel's world.

## Alphabetical Index

::: query
type: organization
display: table
fields: [label, org_type, total_refs]
field_labels:
  label: Organization
  org_type: Type
  total_refs: References
sort: label
order: asc
:::

## By Reference Count

::: query
type: organization
display: table
fields: [label, total_refs]
field_labels:
  label: Organization
  total_refs: References
sort: total_refs
order: desc
:::
