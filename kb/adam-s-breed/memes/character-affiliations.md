---
description: Characters of Adam's Breed grouped by their institutional and social affiliations — the Doric, Soho, the Campagna.
id: character-affiliations
label: Characters by Affiliation
tags: ["list", "person", "affiliation"]
type: list
---

# Characters by Affiliation

In *Adam's Breed*, a character's affiliation — the Doric restaurant, the Soho [[italian-diaspora|Italian community]], the Campagna village — defines their world. This page organizes every character with a known affiliation, making visible the novel's social architecture.

::: query
type: person
affiliation: NOT NULL
sort: label
display: table
fields: [label, affiliation, nationality, quality]
field_labels:
  label: Character
  affiliation: Affiliation
  nationality: Nationality
  quality: Quality
:::

## Characters Without Recorded Affiliation

These characters appear in the novel but their institutional ties are not yet catalogued in the wiki.

::: query
type: person
affiliation: NULL
sort: label
display: table
fields: [label, nationality, quality]
:::

## About This Page

Affiliations are drawn from each character page's frontmatter. [[persons-index|Characters]] without a recorded affiliation may still have institutional ties described in their prose — this page helps identify where the wiki's structured data can be enriched.
