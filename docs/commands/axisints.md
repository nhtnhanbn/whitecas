---
latex: true
slug: axisints
commandtype: Program
title: axisints (Program) - ClassPad Commands
description: axis intercepts on a function
update: 9/7/2022
---

### IMPORTANT - requires [printpts]({{ '/docs/commands/printpts' | relative_url }}) stored in the same folder as your current folder or in the "library" folder (see the Variable Manager).

axisints(*f*, *l*, *u*)

- *f* is an expression in terms of **x**
- *l* is the lower boundary of **x** (*l* should not be in terms of unknown variables, and should be -∞ if *f* contains other unknown variables besides **x**)
- *u* is the upper boundary of **x** (*u* should not be in terms of unknown variables, and should be ∞ if *f* contains other unknown variables besides **x**)

Returns a list of coordinates of x-axis and y-axis intercepts on *f* in the domain **x**ϵ[*l*, *u*].

### Example

Find the axis intercepts of $$ y = x(x - 2)(x + 1) $$. (2023 Methods Exam 2 Section B Question 1a)

![axisints(x(x-2)(x+1), -∞, ∞)]({{ '/files/axisints.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
