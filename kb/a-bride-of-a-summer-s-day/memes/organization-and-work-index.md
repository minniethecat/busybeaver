---
description: Combined index of all organizations and literary works referenced in A Bride of a Summer's Day.
id: organization-and-work-index
label: Organizations & Works Index
tags: ["index", "organization", "work", "institution", "document"]
type: list
---

# Organizations & Works Index

This page provides a combined, dynamically-rendered index of all organizations (institutions, firms, official bodies) and literary or documentary works referenced in *A Bride of a Summer's Day* (Catherine Louisa Pirkis, 1891). These entities, though fewer in number than the characters and places, provide essential context for the novel's social world — from the Prefect of Police in Paris to the legal documents that frame the plot.

## Organizations

::: query
type: organization
display: table
fields: [label, org_type, location, quality, total_refs]
field_labels:
  label: Organization
  org_type: Type
  location: Location
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: All Organizations
:::

## Works

::: query
type: work
display: table
fields: [label, work_type, author, year, quality, total_refs]
field_labels:
  label: Work
  work_type: Type
  author: Author
  year: Year
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: All Works
:::

## Notes

This index is generated dynamically from page frontmatter. Organization and work counts update automatically as pages are added or revised. For full context, see the individual organization and work pages.
