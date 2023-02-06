---
latex: true
slug: infpts
commandtype: Program
title: infpts (Program) - ClassPad Commands
description: possible points of inflection on a function
update: 23/11/2022
---

### IMPORTANT - requires [printpts]({{ '/docs/commands/printpts' | relative_url }}) stored in the same folder as your current folder or in the "library" folder (see the Variable Manager).

infpts(*f*, *l*, *u*)

- *f* is an expression in terms of **x**
- *l* is the lower boundary of **x** (*l* should not be in terms of unknown variables, and should be -∞ if *f* contains other unknown variables besides **x**)
- *u* is the upper boundary of **x** (*u* should not be in terms of unknown variables, and should be ∞ if *f* contains other unknown variables besides **x**)

Returns a list of coordinates of points on *f* in the domain **x**ϵ[*l*, *u*] where the second derivative equals 0.

**Each point must be verified to determine whether it is really a point of inflection.**

### Example

Find the coordinates of any points of inflection of the graph of $$ \dfrac{x}{1+x^{3}} $$. (2017 Specialist Exam 2 Section B Question 1aiii)

![Each point must be verified to determine whether it is really a point of inflection.]({{ '/files/infpts0.png' | relative_url }})

![infpts(x/(1+x^3), -∞, ∞)]({{ '/files/infpts1.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})