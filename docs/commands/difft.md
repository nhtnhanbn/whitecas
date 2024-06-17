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

Find $$ \dfrac{dy}{dx} $$ when $$ t=2 $$ given that $$ x = \dfrac{6t}{t+1} $$ and $$ y = \dfrac{-8}{t^2 + 4} $$. (2023 Specialist Exam 2 Section A Question 9)

![difft(6t/(t+1), -8/(t^2+4), t, 1), t=2]({{ '/files/difft.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
