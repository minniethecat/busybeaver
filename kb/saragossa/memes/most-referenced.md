---
description: "The fifty most-cited wiki entries in the Saragossa wiki, ranked by the number of other pages that link to them."
id: most-referenced
label: "Most Referenced Pages"
tags: ["index", "statistics", "reference"]
type: list
---

# Most Referenced Pages

Which topics do wiki authors link to most often? This page ranks every entry by its total incoming references — a rough measure of narrative centrality in the siege story.
Entries at the top tend to be major characters, pivotal events, or key locations that appear across many chapters.

## Top 50 by References

::: query
sort: total_refs
order: desc
limit: 50
display: table
fields: [label, type, quality, total_refs]
field_labels:
  label: Entry
  type: Type
  quality: Quality
  total_refs: References
title: Most Cited Entries
:::

## Notes

Reference counts are derived from the `backlinks.json` index and reflect all intra-wiki links excluding chapter and overview pages.
The ranking favors entries that serve as hubs in the narrative — characters who appear in many contexts, locations that host multiple events, and concepts that recur throughout the siege.


## See Also

- [[person-index]]
- [[place-index]]
- [[event-index]]
- [[key-personages]]
