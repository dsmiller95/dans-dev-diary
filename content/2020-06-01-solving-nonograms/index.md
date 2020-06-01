---
title: Devising a generic solution to any nonogram
tags: []
date: 2020-06-01T05:25:44.226Z
path: blog/nonogram-solving
cover: ./preview.png
excerpt: Finding a process to solve any nonogram, which can be implemented in code.
---

Nonograms are a puzzle similar to sudoku, and solving them results in a small picture. 

# Basic rules

Each row and column has a list of numbers along it - each number represents a run of that length of "set" squares. When there are multiple numbers for one row/column, each run cannot touch each other!

-----nonogram example here
For example if a 6-cell row has [2, 3] associated with it, the result must be [110111]
-----

## Single row
