---
description: A chronological index of all key events in Shakespeare's Macbeth, from the witches' prophecy to the final battle at Dunsinane.
id: events
label: Events
tags: ["index", "events", "plot", "timeline"]
type: list
---

# Events

An index of the pivotal events that shape the arc of *Macbeth* — battles, murders, prophecies, and confrontations — ordered by their occurrence in the play.

## All Events

::: query
type: event
display: table
fields: [label, description, total_refs]
field_labels:
  label: Event
  description: Description
  total_refs: References
sort: label
order: asc
title: Complete Event Index
:::

## Violent Acts

The murders, battles, and executions that punctuate Macbeth's descent into tyranny.

::: query
type: event
tags: [murder, assassination, battle, execution]
display: table
fields: [label, description, total_refs]
field_labels:
  label: Event
  description: Description
  total_refs: References
sort: label
order: asc
title: Violent Acts
:::

## Supernatural Events

Prophecies, visions, and ghostly appearances that drive the play's supernatural dimension.

::: query
type: event
tags: [prophecy, supernatural, apparition]
display: table
fields: [label, description, total_refs]
field_labels:
  label: Event
  description: Description
  total_refs: References
sort: label
order: asc
title: Supernatural Events
:::
