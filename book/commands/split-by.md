---
title: split-by
categories: |
  default
version: 0.75.0
default: |
  Create a new table split.
usage: |
  Create a new table split.
---

# <code>{{ $frontmatter.title }}</code> for default

<div class='command-title'>{{ $frontmatter.default }}</div>

## Signature

```> split-by (splitter)```

## Parameters

 -  `splitter`: the splitter value to use

## Examples

split items by column named "lang"
```shell
>
                {
                    '2019': [
                      { name: 'andres', lang: 'rb', year: '2019' },
                      { name: 'jt', lang: 'rs', year: '2019' }
                    ],
                    '2021': [
                      { name: 'storm', lang: 'rs', 'year': '2021' }
                    ]
                } | split-by lang

```
