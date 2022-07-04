---
latex: true
slug: nPDf
commandtype: Function
title: nPDf (Function) - ClassPad Commands
description: normal distribution
---

nPDf(*x*, *σ*, *μ*)

- *x* is a number or variable name
- *σ* is the standard deviation
- *μ* is the mean

Equivalent to the builtin normPDf(*x*, *σ*, *μ*), but more convenient to obtain the specific probability density function and to graph the function.

Returns the value of the normal distribution function with a standard deviation of *σ* and a mean of *μ* at the value *x*.

### Example

Let $$ M \sim \mathrm{N}(68, 8^2) $$. Find $$ \mathrm{Pr}(60<M<90) $$. (2018 Methods Exam 2 Section B Question 4a)

![graph of nPDf(x, 8, 68)](/files/nPDf.png)