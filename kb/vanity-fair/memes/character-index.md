---
description: A dynamic index of all characters in Vanity Fair, sorted alphabetically by name. Includes quality ratings and reference counts for each character page.
id: character-index
label: Character Index
tags: ["index", "characters", "navigation"]
type: list
---

# Character Index

This page provides a complete, dynamically-generated index of every character in *Vanity Fair*. Each entry links to a dedicated page with biographical details, role analysis, and citations from the novel.

::: query
type: person
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Character
  quality: Quality
  total_refs: References
sort: label
order: asc
title: All Characters in Vanity Fair
:::

## Notes

- Quality ratings follow the wiki's five-tier system: stub, basic, standard, featured, premium.
- Reference counts (`total_refs`) are the number of other wiki pages that link to this character.
- This index is dynamically generated from page frontmatter and updates automatically as new character pages are added.
