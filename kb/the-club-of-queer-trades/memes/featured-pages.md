---
description: Featured and premium-quality pages representing the best content in the wiki.
id: featured-pages
label: Featured Pages
tags: ["index", "featured", "quality"]
type: list
---

# Featured Pages

The highest-quality pages in the wiki — pages rated **featured** or **premium** that serve
as exemplars of content depth, citation rigour, and editorial polish for
G.K. Chesterton's *The Club of Queer Trades*.

::: query
quality: featured|premium
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Page
  type: Type
  quality: Quality
  total_refs: References
sort: label
order: asc
:::
