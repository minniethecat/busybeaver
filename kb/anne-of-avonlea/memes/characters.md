---
description: Complete index of all characters appearing in Anne of Avonlea, sorted alphabetically.
id: characters
label: All Characters
tags: ["index", "person"]
type: list
---

# All Characters

This page lists all characters appearing in *[[anne-shirley|Anne]] of [[avonlea|Avonlea]]*, drawn from the wiki's [[person]] pages. The table is dynamically generated from frontmatter metadata — new character pages are automatically included.

::: query
type: person
display: table
fields: [label, residence, occupation, quality]
field_labels:
  label: Character
  residence: Residence
  occupation: Role
  quality: Quality
sort: label
order: asc
:::

## About This Index

The character list is rendered by the `::: query` engine, which scans all wiki pages of `type: person`. Each entry links to the character's full page, which includes their role in the story, relationships, key scenes, and character analysis.

For characters [[humor|wit]]h limited corpus presence, the quality field indicates the depth of coverage:
- **featured** — flagship character pages [[humor|wit]]h comprehensive analysis
- **standard** — full character pages [[humor|wit]]h adequate citations and context
- **basic** — pages [[humor|wit]]h essential information only
