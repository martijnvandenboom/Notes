+++
title = "Author Widget"
date = 2021-12-03T11:10:19+08:00
featured = false
comment = true
toc = true
reward = true
categories = [
  "Widget"
]
tags = [
]
series = [
  "Docs"
]
images = []
aliases = [
  "/en/posts/widgets/author"
]
authors = ["RazonYang"]
+++

The author widget is located in the sidebar, in order to introduce yourself briefly.

<!--more-->

## Site Parameters

{{% alert warning %}}
`config/_default/author.toml` is deprecated, please use `params.author` instead.
{{% /alert %}}

```toml
// params.toml
[author]
name = "Foobar"
[author.params]
[author.social]
```

| Name | Type | Default | Description
|---|:-:|:-:|---
| `author` | Object | - | Author profile shown in sidebar.
| `author.name` | String | - | Name.
| `author.avatar` | String | `/images/Martijn_001.jpeg` | Avatar.
| `author.bio` | Object | - | Bio.
| `author.company` | String | - | Company.
| `author.location` | String | - | Location.
| `author.about` | String | - | The external about page. The internal about page will be used if not set.
| `author.params` | Object | - |
| `author.params.layout` | String | - | Optional values: `compact`.
| `author.social` | Object | - | [Social Links]({{< ref "/docs/widgets/social-links" >}}).

