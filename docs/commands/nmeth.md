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

Applies Newton's method for *n* iterations. Prints the details of each iteration and returns the coordinates following the *n*-th iteration. Column *i* is the iteration number, *x* is $$ x_i $$, *y* is $$ f(x_i) $$, *dy/dx* is $$ f'(x_i) $$ and *δx* is $$ x_{i+1} - x_i =  - \dfrac{f(x_i)}{f'(x_i)} $$.

### Example

Find $$ x_1 $$, $$ x_2 $$ and $$ x_3 $$ using Newton's method with $$ x_0 = 0 $$ to approximate an x-intercept of $$ h(x) = 2^x - x^2 $$. (2023 Methods Exam 2 Section B Question 3f)

![nmeth(2^x-x^2, 0, 3)]({{ '/files/nmeth.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
