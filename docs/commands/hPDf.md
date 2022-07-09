---
slug: hPDf
commandtype: Function
title: hPDf (Function) - ClassPad Commands
description: hypergeometric distribution (not explicitly on the Methods Study Design, but useful for certain examination questions)
update: 4/7/2022
---

hPDf(*x*, *n*, *M*, *N*)
- *x* is the query integer
- *n* is the number of draws from the population
- *M* is the number of successes in the population
- *N* is the population size

Equivalent to the builtin hypergeoPDf(*x*, *n*, *M*, *N*), but returns exact values in Standard mode whereas hypergeoPDf can return only decimal answers.

Returns the probability of *x* successes from *n* draws, without replacement between draws, from a population size *N* that contains *M* successes.

*The [hypergeometric distribution](https://en.wikipedia.org/wiki/Hypergeometric_distribution) is not on the VCE Mathematical Methods Study Design, but can be useful for certain examination questions. See the Example. Students are expected to, and should be able to, answer these questions using alternative Mathematical Methods. This function should be used only for checking, and only with an understanding of the circumstances in which the hypergeometric distribution applies.*

### Example

A box contains **n** marbles, of which **k** marbles are coloured red and the remainder **n-k** marbles are coloured green. 2 marbles are drawn from the box, without replacement between draws. Find the probability that the 2 marbles drawn are the same colour. (2019 Methods Exam 2 Section A Question 17)

![hPDf(0, 2, k, n)+hPDf(2, 2, k, n)]({{ '/files/hPDf.png' | relative_url }})