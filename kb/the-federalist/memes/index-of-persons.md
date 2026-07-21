---
description: A complete index of all persons appearing in this wiki, including the authors of The Federalist Papers, political figures of the founding era, and other historical figures referenced in the essays.
id: index-of-persons
label: Index of Persons
tags: ["index", "persons", "authors", "founders"]
type: list
---

# Index of Persons

This page indexes all persons referenced in this wiki — from the authors of The Federalist Papers
(Alexander Hamilton, James Madison, John Jay) to political opponents (the Anti-Federalists) and
historical figures whose ideas shaped the constitutional debates.

Each entry links to a detailed biography page with citations from the original essays and related
historical context.

::: query
type: person
sort: quality_score
order: desc
display: table
fields: [label, quality, total_refs, affiliation]
field_labels:
  label: Person
  quality: Quality
  total_refs: References
  affiliation: Affiliation
title: Persons by Quality
:::
