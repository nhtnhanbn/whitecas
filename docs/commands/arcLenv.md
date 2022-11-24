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

Find the arc length of the curve described by $$ x = \sin(2t) $$ and $$ y = 2\cos(t) $$, between $$ t = 0 $$ and $$ t = 2\pi $$. (2018 Specialist Exam 2 Section A Question 7)

![arcLenv([sin(2t),2cos(t)], 0, 2pi)]({{ '/files/arcLenv.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nathanchen.name }}]({{ site.data.contributors.nathanchen.url }})