---
description: An index of all organizations, factions, armies, and groups in Shakespeare's Macbeth — from the Scottish thanes to the English forces and the Weird Sisters' coven.
id: organizations
label: Organizations
tags: ["index", "organizations", "groups"]
type: list
---

# Organizations

The world of *Macbeth* is shaped by shifting allegiances between organizations and factions. The Scottish thanes form the political order; the English forces represent its overthrow; the Weird Sisters operate as a supernatural collective outside human hierarchies.

## All Organizations

::: query
type: organization
display: table
fields: [label, description, total_refs]
field_labels:
  label: Organization
  description: Description
  total_refs: References
sort: total_refs
order: desc
title: All Organizations
:::

## Military Forces

Armies and military groups that drive the play's conflict.

::: query
tags: [military, battle]
display: table
fields: [label, type, description, total_refs]
field_labels:
  label: Force
  type: Type
  description: Description
  total_refs: References
sort: total_refs
order: desc
title: Military Forces
:::

## Political Factions

Groups defined by political allegiance and power.

::: query
tags: [politics, kingship]
display: table
fields: [label, type, description]
field_labels:
  label: Faction
  type: Type
  description: Description
sort: label
order: asc
title: Political Factions
:::
