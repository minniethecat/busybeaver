---
description: Featured and premium-quality pages in the As You Like It wiki.
id: featured-pages
label: Featured Pages
tags: ["index", "featured", "showcase"]
type: list
---

# Featured Pages

The highest-quality pages in this wiki, curated for showcase.

::: query
quality: featured
display: table
fields: [label, type, description]
field_labels:
  label: Page
  type: Type
  description: Description
sort: label
order: asc
title: Featured Content
:::

## Premium Pages

::: query
quality: premium
display: table
fields: [label, type, description]
field_labels:
  label: Page
  type: Type
  description: Description
sort: label
order: asc
title: Premium Content
:::
