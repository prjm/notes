---
title: Programs
layout: langref
---
# Programs

## Syntax

```
Program = [ProgramHead] [UsesFileClause] Block "." ;
```

## Description

A program consists of 

* an optional [program header](programhead)
* an optional [uses file list](usesfileclause)
* an [main program block](block)
* and a final dot

## Example

Here is the classic `HelloWorld.dpr` example:

```pascal
program HelloWorld;

{$APPTYPE CONSOLE}

uses SysUtils;

begin   
  WriteLn('Hello World!');
end.
```