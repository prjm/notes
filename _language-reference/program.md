---
title: Program
layout: langref
---
# Programs

## File Format

A program consists of 

* an optional [program header](programhead)
* an optional [uses file list](usesfileclause)
* an [main program block](block)
* and a final dot

## Syntax

```
Program ::= [ProgramHead] [UsesFileClause] Block "." ;
```

## Example

Here is the classic `HelloWorld.dpr` example:

```pascal
program HelloWorld;

uses SysUtils;

begin
  WriteLn('Hello World!');
end.
```