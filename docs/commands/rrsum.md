---
latex: true
slug: rrsum
commandtype: Function
title: rrsum (Function) - ClassPad Commands
description: approximation of definite integrals by rectangles using the right rule
update: 21/7/2022
---

rrsum(*f*, *v*, *a*, *b*, *w*)

- *f* is an expression in terms of *v*
- *v* is a variable name
- *a* is the *v*-value of the starting point
- *b* is the *v*-value of the ending point
- *w* is the rectangle width

Returns the approximation to $$ \int_a^b f dv $$ using rectangles of width *w* and height equal to the value of *f* at the rectangle's right endpoint.

### Example

Find the approximation of the area under $$ y = 2\cos(2x) + 3 $$ for $$ x \in \left[ 0, \dfrac{\pi}{2} \right] $$, using rectangles of width $$ \dfrac{\pi}{6} $$ and height equal to the value of $$ y $$ at the rectangle's right endpoint, as a fraction of the exact area.

![rrsum(y, x, 0, pi/2, pi/6)/int(y, x, 0, pi/2)]({{ '/files/rrsum.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nathanchen.name }}]({{ site.data.contributors.nathanchen.url }})