---
description: The most cross-referenced entries in the Our American Cousin wiki, ranked by citation count.
id: top-referenced
label: Most Referenced Pages
tags: ["index", "statistics", "popular"]
type: list
---

# Most Referenced Pages

This page ranks wiki entries by their total number of cross-references,
highlighting the most interconnected topics in the *Our American Cousin* knowledge base.
Pages with high reference counts typically represent central characters, key locations,
and major thematic concerns that permeate the play.

::: query
type: NOT NULL
display: table
fields: [label, type, total_refs, quality]
field_labels:
  label: Page
  type: Type
  total_refs: References
  quality: Quality Tier
sort: total_refs
order: desc
limit: 50
:::

## Reading the Rankings

High reference counts indicate pages that serve as hubs in the wiki's knowledge graph.
Characters like Lord Dundreary and Asa Trenchard, locations like Trenchard Manor,
and concepts like class-and-manners naturally accumulate citations because they
intersect with many other topics across the play's three acts.
