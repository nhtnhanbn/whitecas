---
latex: true
slug: tanLinet
commandtype: Function
title: tanLinet (Function) - ClassPad Commands
description: tangent to a parametric curve
sm: true
update: 23/11/2022
---

tanLinet(*x*, *y*, *t*, *to*)

- *x* is an expression in terms of *t*
- *y* is an expression in terms of *t*
- *t* is a variable name
- *to* is a value of *t*

Returns the expression in terms of **x** for the tangent line to the curve at the point *t* = *to*.

### Example

Find the tangent to the curve defined by $$ x = 2\sin(2t) $$ and $$ y = 3\cos(t) $$ when $$ t = \pi $$. (2020 Specialist Exam 2 Section B Question 1bi)

![tanLinet(2sin(2t), 3cos(t), t, pi)]({{ '/files/tanLinet.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})