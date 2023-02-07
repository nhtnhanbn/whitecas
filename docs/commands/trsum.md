---
latex: true
slug: trsum
commandtype: Function
title: trsum (Function) - ClassPad Commands
description: approximation of definite integrals using the trapezium rule
update: 21/7/2022
---

trsum(*f*, *v*, *a*, *b*, *w*)

- *f* is an expression in terms of *v*
- *v* is a variable name
- *a* is the *v*-value of the starting point
- *b* is the *v*-value of the ending point
- *w* is the trapezium width

Returns the approximation to $$ \int_a^b f dv $$ using trapeziums of width *w* and vertical parallel side lengths equal to the value of *f* at the trapezium's left and right endpoints.

### Example

Find the approximation of

$$ \int_0^{4} \left( \dfrac{1}{27} (x-3)^2 (x+3)^2 + 1 \right) dx $$

using the trapezium rule with trapeziums of width $$ 1 $$. (Sample Methods Exam 2 Section A Question 3)

![trsum((1/27)(x-3)^2(x+3)^2+1, x, 0, 4, 1)]({{ '/files/trsum.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nathanchen.name }}]({{ site.data.contributors.nathanchen.url }})