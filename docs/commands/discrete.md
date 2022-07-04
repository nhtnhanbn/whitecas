---
latex: true
slug: discrete
commandtype: Function
title: discrete (Function) - ClassPad Commands
description: discrete points on a function (useful for solving certain binomial distribution questions)
---

Note - this program does not work in all cases, such as biCDf (use the builtin binomialCDf instead). Answers should be tested by the user.

discrete(*f*, *x*, *l*, *u*, *h*)

- *f* is an expression in terms of *x*, **enclosed in ” ”**
- *x* is a variable name
- *l* is the *x*-value of the starting point
- *u* is the *x*-value of the ending point
- *h* is the step size

Returns a matrix with *x*-values in the left column and *f*-values at the corresponding *x*-values in the right column, for discrete values of *x* with step size *h* in the domain [*l*,*u*].

### Example

$$ X \sim \mathrm{Bi}(n, 0.1) $$. Find the least $$ n $$ such that $$ \mathrm{Pr}(X \geq 2) \geq 0.5 $$. (2021 Methods Exam 2 Section A Question 17)

![discrete("binomialCDf(2, n, n, 0.1)", n, 15, 19, 1)]({{ '/files/discrete.png' | relative_url }})