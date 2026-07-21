---
description: Dynamic index of Stoic philosophers and figures referenced in Marcus Aurelius' Meditations, organized by quality tier and sorted by reference count.
id: stoic-philosophers
label: Stoic Philosophers
tags: ["index", "persons", "stoicism", "philosophers"]
type: list
---

## Stoic Philosophers

The Stoic philosophical tradition runs through the *Meditations* — from the school's founders to Marcus' own teachers and contemporaries. This page provides a dynamically generated index of all Stoic figures in the wiki, sorted by how frequently they are referenced across other pages.

### Featured Figures

The most thoroughly developed Stoic figure pages, with extensive cross-referencing and primary-source citations.

::: query
type: person
tags: stoicism
quality: featured
display: table
fields: [label, total_refs, quality_score, description]
field_labels:
  label: Name
  total_refs: References
  quality_score: Score
  description: Role
sort: total_refs
order: desc
:::

### Standard & Basic

Additional Stoic figures with developing coverage.

::: query
type: person
tags: stoicism
display: table
fields: [label, quality, total_refs, description]
field_labels:
  label: Name
  quality: Quality
  total_refs: References
  description: Role
sort: total_refs
order: desc
:::

## About This Index

This index is dynamically generated from wiki frontmatter metadata. **References** (`total_refs`) counts how many other wiki pages link to each figure. **Score** (`quality_score`) reflects the page's content depth assessment.

The Stoics represented here span five centuries: from Zeno of Citium (founder, c. 300 BCE) through Cleanthes and Chrysippus (early systematizers), to the Roman Stoics of the Imperial period (Seneca, Musonius Rufus, Epictetus), and finally to Marcus' own teachers and contemporaries (Rusticus, Apollonius, Sextus of Chaeronea, Maximus).
