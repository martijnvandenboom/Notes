+++
title = "作者小部件"
date = 2021-12-03T11:10:19+08:00
featured = false
comment = true
toc = true
reward = true
categories = [
  "小部件"
]
tags = [
]
series = [
  "文档"
]
images = []
aliases = [
  "/zh-cn/posts/widgets/author"
]
authors = ["RazonYang"]
+++

作者小部件位于侧边栏，用于简要地自我介绍。

<!--more-->

## 站点参数

{{% alert warning %}}
`config/_default/author.toml` 已被弃用，请使用 `params.author` 代替。
{{% /alert %}}

```toml
// params.toml
[author]
name = "Foobar"
[author.params]
[author.social]
```

| 名称 | 类型 | 默认值 | 描述
|---|:-:|:-:|---
| `author` | Object | - | 个人档案。
| `author.name` | String | - | 名称。
| `author.avatar` | String | `/images/Martijn_001.jpeg` | 头像。
| `author.bio` | Object | - | 简介。
| `author.company` | String | - | 公司。
| `author.location` | String | - | 地理位置。
| `author.about` | String | - | “关于我”的外部页面，如果未设置，则使用内部的“关于我”的页面。
| `author.params` | Object | - |
| `author.params.layout` | String | - | 可选值：`compact`。
| `author.social` | Object | - | [社交链接]({{< ref "/docs/widgets/social-links" >}})。
