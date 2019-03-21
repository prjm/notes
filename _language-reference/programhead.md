---
title: Program Header
layout: langref
---
# Program Header

## Syntax

```
ProgramHeader = 'program' NamespaceName [ProgramParams] ';' ;
```

## Description

The program header marks the start of a program. The [name](namespacename) of the program
has to be equal to the file name which contains the program (excluding the file extension).

The [parameters](programparams) of the program are optional and parsed only for historical reasons.