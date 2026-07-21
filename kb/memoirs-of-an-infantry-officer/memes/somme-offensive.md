---
description: Pages related to the 1916 Battle of the Somme and its aftermath in *Memoirs of an Infantry Officer* — dynamically rendered from page tags. Sassoon's account of the Somme is the emotional and narrative centre of the memoir, covering the trenches, the casualties, and the transformation of his attitude toward the war.
id: somme-offensive
label: The Somme Offensive
tags: ["Somme", "battle", "1916", "Western Front", "index"]
type: list
---

# The Somme Offensive

The Battle of the Somme (1 July – 18 November 1916) is the pivot around which Sassoon's memoir turns.
It is at the Somme that his romantic conception of soldiering collides with industrial warfare, and his
account moves from chivalric enthusiasm to bitter protest. The pages below, grouped by theme, trace the
people, places, concepts, and events that Sassoon's narrative brings together in this theatre of war.

## All Somme Pages

::: query
tags: [Somme]
sort: label
display: table
fields: [label, type, quality]
field_labels:
  label: Page
  type: Type
  quality: Quality
:::

## People of the Somme

::: query
tags: [Somme]
type: person
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Person
  description: Role
  quality: Quality
:::

## Places

::: query
tags: [Somme]
type: place
sort: label
display: table
fields: [label, description, quality]
field_labels:
  label: Place
  description: Significance
  quality: Quality
:::

## Key Concepts

::: query
tags: [Somme]
type: concept
sort: total_refs
order: desc
limit: 15
display: table
fields: [label, total_refs, quality]
field_labels:
  label: Concept
  total_refs: References
  quality: Quality
:::

## Notes

The Somme tag is applied to pages whose content is primarily situated in or directly references
the battle and its specific locations (e.g. Mametz Wood, Quadrangle Trench, Bazentin).
Pages about general trench warfare or broader Western Front themes carry the `Western Front`
and `trench warfare` tags rather than `Somme` unless their content is Somme-specific.
