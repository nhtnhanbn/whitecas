---
latex: true
slug: intpts
commandtype: Program
title: intpts (Program) - ClassPad Commands
description: points of intersection of 2 functions
update: 9/7/2022
---

### IMPORTANT - requires [printpts]({{ '/docs/commands/printpts' | relative_url }}) stored in the same folder as your current folder or in the "library" folder (see the Variable Manager).

intpts(*f*, *g*, *l*, *u*)

- *f* is an expression in terms of **x**
- *g* is an expression in terms of **x**
- *l* is the lower boundary of **x** (*l* should not be in terms of unknown variables, and should be -∞ if either *f* or *g* contains other unknown variables besides **x**)
- *u* is the upper boundary of **x** (*u* should not be in terms of unknown variables, and should be ∞ if either *f* or *g* contains other unknown variables besides **x**)

Returns a list of coordinates of points of intersection of *f* and *g*.

### Example

Find the coordinates of the points of intersection of the graphs of $$ (x-1)^3 (x+2)^3 $$ and $$ (x-1)^2 (x+2)^3 $$. (2019 NHT Methods Exam 2 Section B Question 1a)

![intpts((x-1)^3 (x+2)^3, (x-1)^2 (x+2)^3, -∞, ∞)]({{ '/files/intpts.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})