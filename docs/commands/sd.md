---
latex: true
slug: sd
commandtype: Function
title: sd (Function) - ClassPad Commands
description: standard deviation of a continuous probability distribution
update: 4/7/2022
---

sd(*f*, *x*, *a*, *b*)

- *f* is an expression in terms of *x*
- *x* is a variable name
- *a* is the *x*-value of the starting point
- *b* is the *x*-value of the ending point

For fastest calculation time, the domain [*a*, *b*] should be as small as possible.

**The integral of *f* over the domain [*a*, *b*] must equal 1, as this is assumed by the sd function.**

Returns the standard deviation of the continuous probability distribution defined by the probability density function *f* over the domain [*a*, *b*].

### Example

Find the standard devation of $$ x $$ for the probability density function

$$ \left\{ \begin{array}{ll}
\dfrac{x}{500} & 0 \leq x < 20 \\
\dfrac{50-x}{750} & 20 \leq x \leq 50 \\
\ 0 & \text{elsewhere} \end{array}
\right. $$

(2021 Methods Exam 2 Section B Question 4g)

![sd(function, x, 0, 50)]({{ '/files/sd.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})