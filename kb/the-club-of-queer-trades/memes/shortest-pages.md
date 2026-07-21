---
description: The shortest entry pages in the wiki by prose character count — useful for identifying underdeveloped content that could benefit from expansion.
id: shortest-pages
label: Shortest Pages
tags: ["index", "maintenance", "short", "navigation"]
type: list
---

# Shortest Pages

A ranked list of the shortest entry pages in the wiki, ordered by prose character count.
These pages may be candidates for content enrichment (RCH1/RCH2) to reach a more robust
standard of coverage.

::: query
type NOT IN [chapter, overview, list]
display: table
fields: [label, type, quality, prose_chars, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  prose_chars: Characters
  total_refs: Refs
sort: prose_chars
order: asc
limit: 50
:::

## Notes

- Character count reflects prose text only (excludes frontmatter, headings, blockquotes, and tables).
- Pages at the top of this list may benefit from additional prose content, citations, or structural enrichment.
- Short length does not necessarily indicate low quality — some topics are inherently concise.
