---
latex: true
slug: printpts
commandtype: Program
title: printpts (Program) - ClassPad Commands
description: points on a function given a list of x-values
update: 9/7/2022
---

printpts(*f*, {*s*})

- *f* is an expression in terms of **x**
- *s* is a list of **x**-values, **enclosed in { }**

Returns a list of coordinates of points on *f* corresponding to the **x**-values in *s*.

### Example

Find the $$y$$-values of the points where $$ x = - \infty, -1, 0, 1, \infty $$ on $$ y = (x-1)^2 (x+2)^3 $$.

![printpts((x-1)^2 (x+2)^3, {-∞, -1, 0, 1, ∞})]({{ '/files/printpts.png' | relative_url }})