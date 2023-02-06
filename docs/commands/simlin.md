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

Find the largest set of values of $$ m $$ for which the simultaneous linear equations $$ mx+7y=12 $$ and $$ 7x+my=m $$ have 1 solution for $$ (x, y) $$. (2017 NHT Methods Exam 2 Section A Question 3)

![simlin(m, 7, 12, 7, m, m, m)]({{ '/files/simlin.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})