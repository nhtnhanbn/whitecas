---
latex: true
slug: lineof
commandtype: Function
title: lineof (Function) - ClassPad Commands
description: line connecting 2 points
---

lineof(*a*, *b*, *c*, *d*, *x*)

- (*a*, *b*) are the coordinates of a point
- (*c*, *d*) are the coordinates of a point
- *x* is a variable name

Returns an expression for the line connecting points (*a*, *b*) and (*c*, *d*) in terms of *x*.

### Example

Let $$ f(x) = x^3 - 5x $$. Find the equation of the line through $$ (-1, f(-1)) $$ and $$ (1, f(1)) $$. (2017 Methods Exam 2 Section B Question 1bi)

![lineof(-1, f(-1), 1, f(1), x)](/files/lineof.png)