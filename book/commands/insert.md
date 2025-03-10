---
title: insert
categories: |
  filters
version: 0.75.0
filters: |
  Insert a new column, using an expression or closure to create each row's values.
usage: |
  Insert a new column, using an expression or closure to create each row's values.
---

# <code>{{ $frontmatter.title }}</code> for filters

<div class='command-title'>{{ $frontmatter.filters }}</div>

## Signature

```> insert (field) (new value)```

## Parameters

 -  `field`: the name of the column to insert
 -  `new value`: the new value to give the cell(s)

## Examples

Insert a new entry into a single record
```shell
> {'name': 'nu', 'stars': 5} | insert alias 'Nushell'
```

Insert a column with values equal to their row index, plus the value of 'foo' in each row
```shell
> [[foo]; [7] [8] [9]] | insert bar {|el ind| $el.foo + $ind }
```
