---
latex: true
slug: normalt
commandtype: Function
title: normalt (Function) - ClassPad Commands
description: normal to a parametric curve
sm: true
update: 23/11/2022
---

normalt(*x*, *y*, *t*, *to*)

- *x* is an expression in terms of *t*
- *y* is an expression in terms of *t*
- *t* is a variable name
- *to* is a value of *t*

Returns the expression in terms of **x** for the normal line to the curve at the point *t* = *to*.

### Example

Find the normal to the curve defined by $$ x = 2\sin(2t) $$ and $$ y = 3\cos(t) $$ when $$ t = \dfrac{\pi}{3} $$.

![normalt(2sin(2t), 3cos(t), t, pi)]({{ '/files/normalt.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})