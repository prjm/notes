---
title: Syntax rule overview
layout: langref
---

# Syntax rules

## General file format

|                                |                                                                                      |
|--------------------------------|--------------------------------------------------------------------------------------|
| [File](index)                  | [Program](program) \| [Library](library) \| [Package](package) \| [Unit](unit)       | 
| [Program](program)             | [[ProgramHead](programhead)] [[UsesFileClause](usesfileclause)] [Block](block) '.'   |
| [ProgramHead](programhead)     | 'program' [NamespaceName](namespacename) [[ProgramParams](programparams)] ';'        |
| [ProgramParams](programparams) | '(' [ [Identifier](identifier) { ',' [Identifier](identifier) } ] ')'                |
|--------------------------------|--------------------------------------------------------------------------------------|
