---
latex: true
slug: bmeth
commandtype: Program
title: bmeth (Program) - ClassPad Commands
description: bisection root-finding method
update: 7/2/2023
---

bmeth(*f*, *xl*, *xh*, *n*)

- *f* is an expression in terms of **x** (execution of Program may fail if there are other unknown variables in the expression)
- [*xl*, *xh*] is an interval containing a root of *f*
- *n* is the number of iterations

Applies the bisection method for *n* iterations. Prints the details of each iteration and returns the coordinates following the *n*-th iteration.

### Example

Find the $$ x $$-value for a root of $$ \sin(x) $$ estimated by the bisection method, with an initial range of $$ [3, 5] $$, after 2 iterations.

![bmeth(sin(x), 3, 5, 2)]({{ '/files/bmeth.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})