---
latex: true
slug: var
commandtype: Function
title: var (Function) - ClassPad Commands
description: variance of a continuous probability distribution
update: 4/7/2022
---

var(*f*, *x*, *a*, *b*)

- *f* is an expression in terms of *x*
- *x* is a variable name
- *a* is the *x*-value of the starting point
- *b* is the *x*-value of the ending point

For fastest calculation time, the domain [*a*, *b*] should be as small as possible.

**If *f* is a piecewise function it should be entered raw not as a user-defined function.**

**The integral of *f* over the domain [*a*, *b*] must equal 1, as this is assumed by the var function.**

Returns the variance of the continuous probability distribution defined by the probability density function *f* over the domain [*a*, *b*].

### Example

Find the expected value of $$ x $$ for the probability density function

$$ \left\{ \begin{array}{ll}
0.2e^{-0.2x} & x \geq 0 \\
\ 0 & x < 0 \end{array}
\right. $$

(2021 NHT Methods Exam 2 Section A Question 14)

![var(0.2e^(-0.2x), x, 0, ∞)]({{ '/files/var.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})