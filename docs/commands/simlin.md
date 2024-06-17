---
latex: true
slug: simlin
commandtype: Function
title: simlin (Function) - ClassPad Commands
description: when do 2 lines intersect 0, 1 or ∞ times?
update: 4/7/2022
---

simlin(*a*, *b*, *c*, *d*, *e*, *f*, *g*)
- *a*, *b*, *c* are numbers or expressions in terms of *g*, representing a line *a***x**+*b***y**=*c*
- *d*, *e*, *f* are numbers or expressions in terms of *g*, representing a line *d***x**+*e***y**=*f*
- *g* is a variable name

Returns a list.
- 0th item is values of *g* for which the 2 lines intersect 0 times.
- 1st item is values of *g* for which the 2 lines intersect 1 time.
- 2nd item is values of *g* for which the 2 lines intersect ∞ times.

### Example

Find the largest set of values of $$ k $$ for which the simultaneous linear equations $$ kx+5y=k+5 $$ and $$ 4x+(k+1)y=0 $$ have ∞ solutions for $$ (x, y) $$. (2023 Methods Exam 2 Section A Question 4)

![simlin(k, 5, k+5, 4, k+1, 0, k)]({{ '/files/simlin.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
