---
latex: true
slug: statpts
commandtype: Program
title: statpts (Program) - ClassPad Commands
description: stationary points on a function
---

### IMPORTANT - requires [printpts]({{ '/docs/commands/printpts' | relative_url }}) stored in the same folder as your current folder or in the "library" folder (see the Variable Manager).

statpts(*f*, *l*, *u*)

- *f* is an expression in terms of **x**
- *l* is the lower boundary of **x** (*l* should be -∞ if *f* contains other unknown variables besides **x**)
- *u* is the upper boundary of **x** (*u* should be ∞ if *f* contains other unknown variables besides **x**)

Returns a list of coordinates of stationary points on *f* in the domain **x**ϵ[*l*, *u*].

### Example

The coordinates of the stationary points of $$ y = (x-2)^2 (x-a) $$ are $$ (2, 0) $$ and $$ (p(a+1), q(a-2)^3) $$. Find $$ p $$ and $$ q $$. (2017 NHT Methods Exam 2 Section B Question 2d)

![statpts((x-2)^2 (x-a), -2, ∞)]({{ '/files/statpts.png' | relative_url }})