---
title: math arccos
categories: |
  math
version: 0.75.0
math: |
  Returns the arccosine of the number.
usage: |
  Returns the arccosine of the number.
---

# <code>{{ $frontmatter.title }}</code> for math

<div class='command-title'>{{ $frontmatter.math }}</div>

## Signature

```> math arccos --degrees```

## Parameters

 -  `--degrees`: Return degrees instead of radians

## Examples

Get the arccosine of 1
```shell
> 1 | math arccos
```

Get the arccosine of -1 in degrees
```shell
> -1 | math arccos -d
```
