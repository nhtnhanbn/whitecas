---
latex: true
slug: aosort
commandtype: Function
title: aosort (Function) - ClassPad Commands
description: area of surface of revolution of parametric curve
sm: true
update: 6/3/2024
---

aosort(*x*, *y*, *t*, *a*, *b*)

- *x* is an expression in terms of *t*
- *y* is an expression in terms of *t*
- *t* is a variable name
- *a* is the *t*-value of the starting point
- *b* is the *t*-value of the ending point

Returns the area of the surface obtained by rotating the curve between *t* = *a* and *t* = *b* around the *x*-axis.

### Example

Find the area of the surface of revolution obtained by rotating the curve defined by $$ x = t + 1 $$ and $$ y = t^2 $$ between $$ t=0 $$ and $$ t=2 $$ around the $$ x $$-axis.

![aosort(t+1, t^2, t, 0, 2)]({{ '/files/aosort.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
