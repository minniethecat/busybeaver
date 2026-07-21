---
description: Pages ranked by number of direct quotations from The Autobiography of an Idea — a guide to the wiki entries richest in Sullivan's own words and primary-source evidence.
id: quoted-pages
label: Most Quoted Pages
tags: ["list", "citations"]
type: list
---

# Most Quoted Pages

Which wiki entries carry the most of Sullivan's own voice? This page ranks entries by their count of direct block quotations from *The Autobiography of an Idea* — a proxy for how deeply each topic is rooted in Sullivan's primary text rather than secondary synthesis.

::: query
display: table
fields: [label, type, blockquote_count, total_refs, quality]
field_labels:
  label: Page
  type: Type
  blockquote_count: Quotations
  total_refs: References
  quality: Quality
sort: blockquote_count
order: desc
limit: 50
:::

## Notes

- `blockquote_count` is the number of block-quote (PN-cited) passages from Sullivan's text on each page.
- Pages with zero quotations are omitted from the ranking automatically (they appear as empty rows only if `blockquote_count` is null).
- This index is dynamically generated — new pages and enrichments are reflected automatically.
