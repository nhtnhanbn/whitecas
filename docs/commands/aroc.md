---
latex: true
slug: aroc
commandtype: Function
title: aroc (Function) - ClassPad Commands
description: average rate of change
update: 4/7/2022
---

aroc(*f*, *x*, *a*, *b*)

- *f* is an expression in terms of *x*
- *x* is a variable name
- *a* is the *x*-value of the starting point
- *b* is the *x*-value of the ending point

Returns the average rate of change of *f* between *x*=*a* and *x*=*b*.

### Example

Find the average rate of change of $$ h(t) = -60 \cos \left( \dfrac{\pi t}{15} \right) + 75 $$, between $$ t=0 $$ and $$ t=\dfrac{30}{4} $$. (2023 Methods Exam 2 Section B Question 2c)

![aroc(h(t), t, 0, 30/4)]({{ '/files/aroc.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
