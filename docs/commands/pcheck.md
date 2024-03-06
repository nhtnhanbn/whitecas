---
latex: true
slug: pcheck
commandtype: Program
title: pcheck (Program) - ClassPad Commands
description: determine functions satisfying an equation
update: 6/3/2024
---

Note - this program may throw an error if in Decimal mode. Use Standard mode instead.

Define *f(x)* = {*a*, *b*, *c*, *d*, *e*}

pcheck(*f(x)*, *l*, *r*)

- *f(x)* is defined as a list of any length containing expressions {*a*, *b*, ...} in terms of *x*
- *l* is the left hand side of the equation
- *r* is the right hand side of the equation

Returns a matrix with each row corresponding to an option of *f(x)*, with the columns containing for that option, from left to right, *f(x)*, *l*, *r*, judge(*l*=*r*).

### Example

$$ f(x+f(x)) = f(2x) $$. Which option could possibly be $$ f(x) $$? (2018 Methods Exam 2 Section A Question 10)

![Define f(x)={1-x,x-1,x,x/2,(1-x)/2}]({{ '/files/pcheck0.png' | relative_url }})

![pcheck(f(x),f(x+f(x)),f(2x))]({{ '/files/pcheck1.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }}) and [{{ site.data.contributors.kevin.name }}]({{ site.data.contributors.kevin.url }})
