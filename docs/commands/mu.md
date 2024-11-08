---
latex: true
slug: mu
commandtype: Function
title: mu (Function) - ClassPad Commands
description: expected value of a continuous probability distribution
update: 4/7/2022
---

mu(*f*, *x*, *a*, *b*)

- *f* is an expression in terms of *x*
- *x* is a variable name
- *a* is the *x*-value of the starting point
- *b* is the *x*-value of the ending point

For fastest calculation time, the domain [*a*, *b*] should be as small as possible.

**If *f* is a piecewise function it should be entered raw not as a user-defined function.**

**The integral of *f* over the domain [*a*, *b*] must equal 1, as this is assumed by the mu function.**

Returns the mean of the continuous probability distribution defined by the probability density function *f* over the domain [*a*, *b*].

### Example

Find the expected value of $$ v $$ for the probability density function

$$ f(v) =
\left\{ \begin{array}{ll}
\dfrac{1}{6 \pi} \sin \left( \sqrt{ \dfrac{v-30}{3} } \right) & 30 \leq v \leq 3 \pi^2 + 30 \\
\ 0 & \mathrm{elsewhere} \end{array}
\right. $$

(2023 Methods Exam 2 Section B Question 4i)

![mu(3/50 (t/50)^2 e^(-(t/50)^3), t, 0, ∞)]({{ '/files/mu.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
