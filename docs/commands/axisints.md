---
latex: true
slug: axisints
commandtype: Program
title: axisints (Program) - ClassPad Commands
description: axis intercepts on a function
---

### IMPORTANT - requires [printpts]({{ '/docs/commands/printpts' | relative_url }}) stored in the same folder as your current folder or in the "library" folder (see the Variable Manager).

axisints(*f*, *l*, *u*)

- *f* is an expression in terms of **x**
- *l* is the lower boundary of **x** (*l* should be -∞ if *f* contains other unknown variables besides **x**)
- *u* is the upper boundary of **x** (*u* should be ∞ if *f* contains other unknown variables besides **x**)

Returns a list of coordinates of x-axis and y-axis intercepts on *f* in the domain **x**ϵ[*l*, *u*].

### Example

Let $$ f(x)=8-2^{x-1} $$. Find the area bound by the graph of $$ f(x) $$ and the line connecting the axis intercepts of $$ f(x) $$. (2019 NHT Methods Exam 2 Section A Question 18)

This solution also uses [lineof]({{ '/docs/commands/lineof' | relative_url }}).

![axisints(8-2^(x-1), -∞, ∞)]({{ '/files/axisints.png' | relative_url }})