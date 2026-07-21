---
description: Combined index of all event and organization entries in Sticks and Stones — exhibitions, competitions, architectural firms, schools, and institutions.
id: list-events-organizations
label: List of Events & Organizations
tags: ["list", "event", "organization", "index"]
type: list
---

# List of Events & Organizations

This page aggregates event and organization entries across *Sticks and Stones*. Events include architectural competitions, world's fairs, and milestone gatherings; organizations encompass firms, schools, academies, and professional bodies that shaped architectural practice.

## Events

::: query
type: event
display: table
fields: [label, total_refs]
field_labels:
  label: Event
  total_refs: References
sort: label
order: asc
:::

## Organizations

::: query
type: organization
display: table
fields: [label, total_refs]
field_labels:
  label: Organization
  total_refs: References
sort: label
order: asc
:::
