---
description: "Complete index of all 48 person entries in the Saragossa wiki, sorted alphabetically by label."
id: person-index
label: "Person Index"
tags: ["index", "person"]
type: list
---

# Person Index

This page lists every person entry in the Saragossa wiki.
Each row shows the entry name, its current quality tier, and how many other pages reference it.
Click any entry to view its full page.

## Complete List

::: query
type: person
sort: label
display: table
fields: [label, quality, total_refs]
field_labels:
  label: Name
  quality: Quality
  total_refs: References
title: Person Entries
:::

## Notes

Quality tiers follow the standard wiki scale: `stub` (minimal), `basic` (established), `standard` (well-developed), `featured` (comprehensive), `premium` (exceptional).
The reference count (`total_refs`) reflects how many other wiki pages link to this entry.


## See Also

- [[key-personages]]
- [[notable-civilians]]
- [[french-forces]]
- [[spanish-defenders]]
