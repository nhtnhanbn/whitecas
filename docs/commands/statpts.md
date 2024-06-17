---
latex: true
slug: statpts
commandtype: Program
title: statpts (Program) - ClassPad Commands
description: stationary points on a function
update: 9/7/2022
---

### IMPORTANT - requires [printpts]({{ '/docs/commands/printpts' | relative_url }}) stored in the same folder as your current folder or in the "library" folder (see the Variable Manager).

statpts(*f*, *l*, *u*)

- *f* is an expression in terms of **x**
- *l* is the lower boundary of **x** (*l* should not be in terms of unknown variables, and should be -∞ if *f* contains other unknown variables besides **x**)
- *u* is the upper boundary of **x** (*u* should not be in terms of unknown variables, and should be ∞ if *f* contains other unknown variables besides **x**)

Returns a list of coordinates of stationary points on *f* in the domain **x**ϵ[*l*, *u*].

### Example

Find the coordinates of the stationary points of $$ f(x) = x(x-2)(x+1) $$. (2023 Methods Exam 2 Section B Question 1b)

![statpts(x(x-2)(x+1), -∞), ∞)]({{ '/files/statpts.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
