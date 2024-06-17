---
slug: biPDf
commandtype: Function
title: biPDf (Function) - ClassPad Commands
description: binomial distribution
update: 4/7/2022
---

biPDf(*x*, *n*, *p*)
- *x* is the query integer
- *n* is the number of trials
- *p* is the probability of success each trial

Equivalent to the builtin binomialPDf(*x*, *n*, *p*), but returns exact values in Standard mode whereas binomialPDf can return only decimal answers.

Returns the probability of *x* successes from *n* trials with *p* probability of success each trial.

### Example

A box contains $$ n $$ green balls and $$ m $$ red balls. A ball is selected at random, then replaced in the box. Find the probability that in 8 such selections a green ball is selected at least once. (2023 Methods Exam 2 Section A Question 8)

![1 - biPDf(0, 8, n(n+m))]({{ '/files/biPDf.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
