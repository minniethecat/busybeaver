---
description: "A statistical ranking of the most frequently cited pages across the entire wiki — a map of the knowledge graph's central nodes, showing which topics are most interconnected."
id: most-cited
label: "Most Cited Pages"
tags: ["list", "statistics", "citations", "ranking"]
type: list
---

# Most Cited Pages

Citation count measures how often a page is referenced by other pages — a signal of its importance in the wiki's knowledge graph. The pages below are the most interconnected nodes in the chronicle's web of knowledge: the persons, places, events, and concepts that other entries most frequently invoke.

::: query
display: table
sort: total_refs
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: Citations
limit: 50
title: Top 50 Most Cited Pages
:::

## Reading This Ranking

High citation counts often indicate foundational topics — the species, eras, and concepts that form the backbone of the chronicle. Browse the [[featured-showcase|Featured Pages]] for the highest-quality writing, or explore the type-specific indexes for a complete catalogue: [[species-index|Species]], [[era-index|Eras]], [[civilization-index|Civilizations]], [[person-index|Persons]], [[concept-index|Concepts]], [[place-index|Places]], [[event-index|Events]], and [[organization-index|Organizations]].
