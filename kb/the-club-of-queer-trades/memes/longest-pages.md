---
description: Pages with the most extensive prose content in The Club of Queer Trades wiki, ranked by character count — useful for identifying candidates for structural reorganization or in-depth study.
id: longest-pages
label: Longest Pages
tags: ["index", "statistics", "maintenance"]
type: list
---

# Longest Pages

The most textually substantial entries in the wiki. These pages have accumulated
the deepest prose coverage across multiple rounds of enrichment and may benefit
from structural review — logical section reordering, narrative flow improvements,
or splitting if a single page has grown unwieldy.

This list also serves as a reading guide: the longest pages are typically the
most comprehensively covered topics.

::: query
display: table
fields: [label, type, quality, prose_len, h2_count]
field_labels:
  label: Page
  type: Type
  quality: Quality
  prose_len: Prose (chars)
  h2_count: Sections
sort: prose_len
order: desc
limit: 30
title: Top 30 Longest Pages
:::
