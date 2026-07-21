---
description: A dynamic index of all quote pages — memorable lines, catchphrases, dialogue excerpts, and notable narrative passages from the novel.
id: quote-index
label: Quote Index
tags: ["index", "quote", "dialogue"]
type: list
---

# Quote Index

This page provides a complete, automatically generated index of every [[quote]] page in the wiki. Quotes capture the novel's most memorable language — Archie's catchphrases, Lucille's retorts, Daniel Brewster's explosions of wrath, and Wodehouse's own narrative asides. The table is rendered dynamically from the pages database.

::: query
type: quote
display: table
fields: [label, speaker, quote_type, quality, total_refs]
field_labels:
  label: Quote
  speaker: Speaker
  quote_type: Type
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Notes

- **Speaker** identifies the character who delivers the line (or "narrator" for narrative voice).
- **Type** classifies the quote: catchphrase, dialogue, headline, or narrative.
- Quotes are the smallest unit of the wiki's evidentiary system — each should include a PN citation.
