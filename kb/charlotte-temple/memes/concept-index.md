---
description: Complete index of all concepts and themes in Charlotte Temple, from virtue and vice to social institutions and emotions.
id: concept-index
label: Concept Index
tags: ["index", "concept", "theme"]
type: list
---

# Concept Index

This page provides a dynamically-rendered index of all concept entries in the Charlotte Temple wiki. Concepts span the novel's moral universe—virtues, vices, emotions, and social institutions—each with dedicated pages tracing their appearance and significance throughout the narrative.

::: query
type: concept
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: Citations
sort: label
order: asc
title: All Concepts
:::

## Most Referenced Concepts

The most frequently cited concepts reveal the novel's central thematic preoccupations.

::: query
type: concept
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Concept
  quality: Quality
  total_refs: Citations
sort: total_refs
order: desc
limit: 20
title: Most Referenced Concepts
:::
