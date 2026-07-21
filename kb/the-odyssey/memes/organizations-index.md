---
description: A complete index of all groups, tribes, and collectives in Homer's Odyssey, dynamically generated from the wiki's organization entries.
id: organizations-index
label: Organizations Index
tags: ["index", "organizations", "groups"]
type: list
---

# Organizations Index

This page catalogs all groups, tribes, peoples, and collectives referenced in Homer's *Odyssey*.
Organizations range from the Greek army and individual tribal groups to the divine assembly on Olympus.

Each entry includes the group type, location, leader, and known members.

## All Organizations

::: query
type: organization
display: table
fields: [label, group_type, location, leader, quality]
field_labels:
  label: Organization
  group_type: Type
  location: Location
  leader: Leader
  quality: Quality
sort: label
order: asc
:::

## Tribes & Peoples

::: query
type: organization
group_type: tribe
display: table
fields: [label, location, leader, members, quality]
field_labels:
  label: Tribe
  location: Location
  leader: Leader
  members: Members
  quality: Quality
sort: label
order: asc
:::
