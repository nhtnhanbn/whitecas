---
latex: true
slug: nmeth
commandtype: Program
title: nmeth (Program) - ClassPad Commands
description: Newton's root-finding method
update: 7/2/2023
---

nmeth(*f*, *xa*, *n*)

- *f* is an expression in terms of **x** (execution of Program may fail if there are other unknown variables in the expression)
- *xa* is the initial guess for the **x**-value of a root of *f*
- *n* is the number of iterations

Applies Newton's method for *n* iterations. Prints the details of each iteration and returns the coordinates following the *n*-th iteration.

### Example

Find the number of iterations of Newton's method, with an initial guess of $$ x_0 = 1 $$, after which the $$ x $$-value of the non-zero root of $$ f(x) = \dfrac{x^3}{5} - \sqrt{x} $$ is first approximated correct to 3 decimal places. (Sample Methods Exam 2 Section A Question 2)

![nmeth(f(x), 1, 9)]({{ '/files/nmeth0.png' | relative_url }})

![]({{ '/files/nmeth1.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})