---
description: "Top 50 most-referenced wiki entries in The Wolf-Leader, ranked by total wikilink citations across all pages."
id: most-referenced
label: "Most Referenced Pages"
tags: ["index", "statistics", "ranking"]
type: list
---

This page surfaces the fifty most-cited entries in the wiki — the concepts, characters, places, and events that form the dense connective tissue of *The Wolf-Leader*'s knowledge graph. High citation counts reveal which ideas the novel returns to most insistently.

## Top 50 by Total References

::: query
type_any: [person, place, concept, event]
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality
sort: total_refs
order: desc
limit: 50
:::
