---
description: Pages at basic quality tier awaiting enrichment to standard.
id: upgrade-queue
label: Upgrade Queue
tags: ["index", "quality", "maintenance"]
type: list
---

# Upgrade Queue

Pages currently at **basic** quality in The Club of Queer Trades wiki.
These pages have adequate frontmatter and body text but need additional prose,
citations, or structural expansion to reach the standard tier.

::: query
quality: basic
display: table
fields: [label, type, total_refs]
field_labels:
  label: Page
  type: Type
  total_refs: References
sort: label
order: asc
:::
