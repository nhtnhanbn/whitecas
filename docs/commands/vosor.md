---
latex: true
slug: vosor
commandtype: Function
title: vosor (Function) - ClassPad Commands
description: volume of solid of revolution
sm: true
update: 23/11/2022
---

vosor(*f*, *x*, *a*, *b*)

- *f* is an expression in terms of *x*
- *x* is a variable name
- *a* is the *x*-value of the starting point
- *b* is the *x*-value of the ending point

Returns the volume of the solid obtained by rotating the graph of *f* between *x* = *a* and *x* = *b* around the *x*-axis.

### Example

$$ f(x) = \dfrac{x}{1+x^3} $$. Find the value of $$ a $$ such that the volume of the solid obtained by rotating the graph of $$ f(x) $$ between $$ x=0 $$ and $$ x=a $$ around the $$ x $$-axis equals the volume of the solid obtained by rotating the graph of $$ f(x) $$ between $$ x=a $$ and $$ x=3 $$ around the $$ x $$-axis. (2017 Specialist Exam 2 Section B Question 1cii)

![solve(vosor(f(x), x, 0, a)=vosor(f(x), x, a, 3), a)]({{ '/files/vosor.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})