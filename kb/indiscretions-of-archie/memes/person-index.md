---
description: A dynamic index of all person pages in the wiki, sorted alphabetically. Rendered automatically from the pages database — no manual maintenance required.
id: person-index
label: Person Index
tags: ["index", "person", "character"]
type: list
---

# Person Index

This page provides a complete, automatically generated index of every [[person]] page in the wiki. The table below is rendered dynamically from the pages database and reflects the current state of the wiki at all times — new person pages appear here automatically.

::: query
type: person
display: table
fields: [label, role, nationality, quality, total_refs]
field_labels:
  label: Name
  role: Role
  nationality: Nationality
  quality: Quality
  total_refs: References
sort: label
order: asc
:::

## Notes

- The **References** column counts the number of other wiki pages that link to this person.
- The **Quality** column shows the current quality grade (stub → basic → standard → featured → premium).
- A person's **Role** is one of: protagonist, antagonist, supporting, minor, or referenced.
- For detailed information about any person, click the page link in the Name column.
