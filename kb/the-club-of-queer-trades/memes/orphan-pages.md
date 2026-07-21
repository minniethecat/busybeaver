---
description: Pages with no incoming wikilinks — useful for identifying content that needs better integration into the wiki's link network.
id: orphan-pages
label: Orphan Pages
tags: ["index", "maintenance", "orphan", "navigation"]
type: list
---

# Orphan Pages

Pages that currently have zero incoming wikilinks. These pages may need additional cross-linking
from related articles to improve navigation and discoverability within the wiki.

::: query
type NOT IN [chapter, overview, list]
display: table
fields: [label, type, quality, prose_chars, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  prose_chars: Length
  total_refs: Refs
sort: label
order: asc
:::

## Notes

- Pages listed here have `total_refs = 0`, meaning no other wiki page links to them.
- Consider adding wikilinks from related pages (characters, places, concepts) to reduce the orphan count.
- Some orphans may be naturally low-connectivity (e.g., very specific minor characters).
