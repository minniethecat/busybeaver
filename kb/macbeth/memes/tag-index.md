---
description: A comprehensive index of all content tags in the Macbeth wiki, showing how concepts, characters, events, and places are categorized across thematic and structural dimensions.
id: tag-index
label: Tag Index
tags: ["index", "tags", "meta"]
type: list
---

# Tag Index

Every page in this wiki carries one or more tags — labels that connect it to thematic threads, character groups, and structural categories. This index surfaces those connections, with query blocks that let you browse by tag and discover relationships across the wiki.

## Thematic Tags

Tags that identify the major themes and motifs running through *Macbeth*.

::: query
type: concept
tags: [theme]
display: table
fields: [label, tags, total_refs]
field_labels:
  label: Theme
  tags: Related Tags
  total_refs: References
sort: total_refs
order: desc
title: Thematic Tags
:::

## Character Tags

Tags that group characters by role, allegiance, and significance.

::: query
type: person
display: table
fields: [label, tags, total_refs]
field_labels:
  label: Character
  tags: Tags
  total_refs: References
sort: total_refs
order: desc
title: Character Tags
:::

## Motif Tags

Recurring images, symbols, and patterns.

::: query
type: concept
tags: [motif]
display: table
fields: [label, tags, total_refs]
field_labels:
  label: Motif
  tags: Related Tags
  total_refs: References
sort: label
order: asc
title: Motif Tags
:::

## Supernatural Tags

Pages exploring the witches, prophecies, apparitions, and other supernatural elements.

::: query
tags: [supernatural]
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: total_refs
order: desc
title: Supernatural Pages
:::
