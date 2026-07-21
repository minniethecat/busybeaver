---
description: The most referenced pages in A Girl of the Limberlost wiki, ranked by total incoming backlinks.
id: most-referenced-pages
label: Most Referenced Pages
tags: ["index", "statistics"]
type: list
---

# Most Referenced Pages

This page ranks all wiki entries by their total number of incoming references. Highly-referenced pages tend to be central characters, key locations, or recurring themes that connect multiple chapters and events.

## Top 30 by References

::: query
type: person
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 10
:::

::: query
type: place
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 10
:::

::: query
type: event
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 10
:::

::: query
type: concept
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
limit: 10
:::
