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

Four fair coins are tossed at the same time. Find the probability that there is an equal number of heads and tails, given that there is at least one head. (2021 Methods Exam 2 Section A Question 15)

![biPDf(2, 4, 1/2)/(1-biPDf(0, 4, 1/2))]({{ '/files/biPDf.png' | relative_url }})