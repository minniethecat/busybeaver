---
description: 按被引用数排序的核心词条 Top 50，反映全书叙事中最重要的实体。
id: top-referenced-pages
label: 核心词条（被引排行）
tags: ["index", "排行"]
type: list
---

# 核心词条（被引排行）

本页按被引用数（total_refs）降序排列，展示全书叙事网络中最核心的人物、地点与概念。

::: query
type_any: [person, place, event, concept, organization, work]
display: table
sort: total_refs
order: desc
limit: 50
fields: [label, type, quality, total_refs]
field_labels:
  label: 词条
  type: 类型
  quality: 质量档
  total_refs: 被引用数
:::

## 说明

"被引用数"统计的是其他 wiki 页面中通过 wikilink 引用该词条的次数，是衡量词条在叙事网络中重要性的核心指标。排行靠前的词条通常是小说的主角、关键地点或贯穿全书的核心概念。
