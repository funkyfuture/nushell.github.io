---
title: group
categories: |
  filters
version: 0.75.0
filters: |
  Groups input into groups of `group_size`.
usage: |
  Groups input into groups of `group_size`.
---

# <code>{{ $frontmatter.title }}</code> for filters

<div class='command-title'>{{ $frontmatter.filters }}</div>

## Signature

```> group (group_size)```

## Parameters

 -  `group_size`: the size of each group

## Examples

Group the a list by pairs
```shell
> [1 2 3 4] | group 2
```
