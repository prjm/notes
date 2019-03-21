---
title: Language reference - All syntax rules
layout: default
---

# Syntax rules

## General file format

[File](index) = [Program](program) |
                [Library](library) |
                [Package](package) |
                [Unit](unit) ;

[Program](program) = [[ProgramHead](programhead)] 
                     [[UsesFileClause](usesfileclause)] 
                     [Block](block) '.' ;