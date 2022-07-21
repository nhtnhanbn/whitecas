---
latex: true
slug: lrsum
commandtype: Function
title: lrsum (Function) - ClassPad Commands
description: approximation of definite integrals by rectangles using the left rule
update: 21/7/2022
---

lrsum(*f*, *v*, *a*, *b*, *w*)

- *f* is an expression in terms of *v*
- *v* is a variable name
- *a* is the *v*-value of the starting point
- *b* is the *v*-value of the ending point
- *w* is the rectangle width

Returns the approximation to $$ \int_a^b f dv $$ using rectangles of width *w* and height equal to the value of *f* at the rectangle's left endpoint.

### Example

The approximation of the area under $$ y = 2^x + c $$ for $$ x \in [1,5] $$, using rectangles of width $$ 1 $$ and height equal to the value of $$ y $$ at the rectangle's left endpoint, equals $$ 44 $$. Find $$ c $$. (2013 Methods Exam 2 Section A Question 14)

![solve(lrsum(2^x+c, x, 1, 5, 1)=44, c)]({{ '/files/lrsum.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nathanchen.name }}]({{ site.data.contributors.nathanchen.url }})