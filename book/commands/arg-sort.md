---
title: arg-sort
categories: |
  dataframe
version: 0.75.0
dataframe: |
  Returns indexes for a sorted series
usage: |
  Returns indexes for a sorted series
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> arg-sort ```

## Examples

Returns indexes for a sorted series
```shell
> [1 2 2 3 3] | into df | arg-sort
```

Returns indexes for a sorted series
```shell
> [1 2 2 3 3] | into df | arg-sort -r
```
