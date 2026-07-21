---
description: Articles in The Woodlanders wiki ranked by total cross-references — the most interconnected pages in the knowledge graph, rendered dynamically from wiki metadata
id: most-referenced-articles
label: Most Referenced Articles
tags: ["index", "statistics", "reference"]
type: list
---

# Most Referenced Articles

The most-referenced articles in the Woodlanders wiki represent the knowledge graph's central nodes — the characters, places, concepts, and events that other entries most frequently cite. A high reference count indicates a page that serves as a nexus for the wiki's interconnected structure, linking together the novel's people, places, and ideas.

::: query
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Article
  type: Type
  quality: Quality
  total_refs: References
sort: total_refs
order: desc
limit: 30
:::

## Reading the Rankings

Reference counts are generated automatically by the wiki engine from `[[wikilink]]` usage across all non-chapter pages. A page that is referenced in many other entries functions as a hub — it may be a major character around whom the plot revolves, a place that appears across multiple chapters, or a concept that illuminates diverse aspects of the novel. The ranking is dynamic and updates as new pages and links are added.

Chapter pages (type=chapter) and list pages (type=list) are excluded from this ranking to focus on the core entity entries.
