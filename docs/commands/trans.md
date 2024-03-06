---
latex: true
slug: trans
commandtype: Function
title: trans (Function) - ClassPad Commands
description: transform an equation
update: 6/3/2024
---

trans(*e*, *t*, *x*, *y*)

- *e* is an equation in terms of *x* and *y*
- *t* is a matrix transformation of *x* and *y*
- *x* and *y* are variable names

Returns the equation after the transformation is applied.

### Example

$$ f(x) = e^x + e^{-x} $$ and $$ g(x) = \dfrac{1}{2} f(2-x) $$. Find a possible sequence of transformations that map $$ f $$ to $$ g $$. (2023 Methods Exam 2 Section B Question 5a)

![trans(y=f(x), [[-1 0] [0 1/2]][[x] [y]] + [[2] [0]], x, y)]({{ '/files/trans0.png' | relative_url }})

![(1/2) f(2-x)]({{ '/files/trans1.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
