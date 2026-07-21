---
description: All bird species observed by W.N.P. Barbellion in the Journal — from common garden birds to migratory visitors — with scientific names, observation dates, and locations.
id: bird-species
label: Bird Species
tags: ["Index", "Species", "Birds", "Ornithology"]
type: list
---

# Bird Species Observed by Barbellion

Birds occupy a special place in Barbellion's natural history observations. From the swallows whose seasonal migrations he tracked across multiple years, to the woodpecker whose drumming he heard in Devon woods, to the moorhen glimpsed on country ponds — birds are among his most frequent and carefully documented subjects. This page lists every bird species for which a dedicated wiki page exists, drawn from the frontmatter fields of each species entry.

::: query
type: species
tags: [Bird]
display: table
fields: [label, scientific_name, habitat, observation_place, observation_date]
field_labels:
  label: Common Name
  scientific_name: Scientific Name
  habitat: Habitat
  observation_place: Location
  observation_date: Observed
sort: label
order: asc
:::

## Bird Species by Habitat

::: query
type: species
tags: [Bird]
display: table
fields: [label, habitat]
field_labels:
  label: Common Name
  habitat: Habitat
sort: habitat
order: asc
:::

## About This Index

Bird species pages share the standard `type: species` frontmatter with `taxonomic_group: Bird`. The table above is dynamically generated — as new bird species pages are added or existing ones are enriched, the index updates automatically without manual maintenance.
