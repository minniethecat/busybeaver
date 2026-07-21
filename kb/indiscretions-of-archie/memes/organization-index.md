---
description: A dynamic index of all organization pages — baseball teams, publishers, military units, businesses, and social clubs referenced in the novel.
id: organization-index
label: Organization Index
tags: ["index", "organization", "institution"]
type: list
---

# Organization Index

This page provides a complete, automatically generated index of every [[organization]] page in the wiki. Organizations range from baseball teams and newspaper publishers to military regiments and social institutions. The table is rendered dynamically from the pages database.

::: query
type: organization
display: table
fields: [label, org_type, real_world, quality, total_refs]
field_labels:
  label: Organization
  org_type: Type
  real_world: Real?
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Notes

- **Type** classifies the organization: sports-team, publisher, military, business, or social-club.
- **Real?** indicates whether the organization existed in the real world (true) or is fictional (false).
- Organizations anchor the novel in both historical reality (real newspapers, military units) and comic invention (fictional hotels, clubs).
