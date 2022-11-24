---
latex: true
slug: difft
commandtype: Function
title: difft (Function) - ClassPad Commands
description: differentiation of a parametric curve
sm: true
update: 23/11/2022
---

difft(*x*, *y*, *t*, *n*)

- *x* is an expression in terms of *t*
- *y* is an expression in terms of *t*
- *t* is a variable name
- *n* is the derivative order

***n* must be 0, 1 or 2.**

Returns $$ \dfrac{ d^{n} y }{ d x^{n} } $$.

### Example

Find $$ \dfrac{dy}{dx} $$ in terms of $$ t $$ given that $$ x = \sin(t) - \cos(t) $$ and $$ y = \dfrac{1}{2}\sin(2t) $$. (2016 Specialist Exam 2 Section A Question 7)

![difft(sin(t)-cos(t), sin(2t)/2, t, 1)]({{ '/files/difft.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})