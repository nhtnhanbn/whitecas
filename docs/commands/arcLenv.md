---
latex: true
slug: arcLenv
commandtype: Function
title: arcLenv (Function) - ClassPad Commands
description: arc length of a parametric curve
sm: true
update: 23/11/2022
---

aroc(*r*, *t*, *a*, *b*)

- *r* is a vector in terms of *t*
- *t* is a variable name
- *a* is the *t*-value of the starting point
- *b* is the *t*-value of the ending point

Returns the arc length of *r* between *t* = *a* and *t* = *b*.

### Example

Find the arc length of the curve described by $$ x = 2 \cos(t) + 2 $$ and $$ y = (e-2) \sin(t) $$, between $$ t = \dfrac{\pi}{2} $$ and $$ t = \pi $$. (2023 Specialist Exam 2 Section B Question 1f)

![arcLenv([2cos(t)+2, (e-2)sin(t)], t, pi/2, pi)]({{ '/files/arcLenv.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nathanchen.name }}]({{ site.data.contributors.nathanchen.url }})
