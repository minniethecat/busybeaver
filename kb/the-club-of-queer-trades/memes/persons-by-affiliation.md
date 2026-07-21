---
description: All characters in The Club of Queer Trades grouped by their institutional or social affiliation, revealing the professional and social networks of the stories.
id: persons-by-affiliation
label: Persons by Affiliation
tags: ["index", "person", "affiliation"]
type: list
---

# Persons by Affiliation

The characters of Chesterton's detective-fantasy hybrid are defined as much
by their institutional affiliations as by their personalities. This index
groups every character with a recorded affiliation — from the Club of Queer Trades
itself to the police, the aristocracy, and the professions — making visible
the social architecture of Edwardian London as Chesterton saw it.

::: query
type: person
affiliation: NOT NULL
display: table
fields: [label, affiliation, quality, total_refs]
field_labels:
  label: Character
  affiliation: Affiliation
  quality: Quality
  total_refs: References
sort: affiliation
order: asc
:::
