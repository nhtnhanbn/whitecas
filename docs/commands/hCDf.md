---
slug: hCDf
commandtype: Function
title: hCDf (Function) - ClassPad Commands
description: hypergeometric cumulative distribution (not explicitly on the Methods Study Design, but useful for certain examination questions)
update: 4/7/2022
---

hCDf(*l*, *u*, *n*, *M*, *N*)
- *l* is the query lower boundary
- *u* is the query upper boundary
- *n* is the number of draws from the population
- *M* is the number of successes in the population
- *N* is the population size

**Parameters should evaluate to numbers, not expressions in terms of unknown variables.**

Equivalent to the builtin hypergeoCDf(*l*, *u*, *n*, *M*, *N*), but returns exact values in Standard mode whereas hypergeoCDf can return only decimal answers.

Returns the probability of between and including *l* and *u* successes from *n* draws, without replacement between draws, from a population size *N* that contains *M* successes.

*The [hypergeometric distribution](https://en.wikipedia.org/wiki/Hypergeometric_distribution) is not on the VCE Mathematical Methods Study Design, but can be useful for certain examination questions. See the Example. Students are expected to, and should be able to, answer these questions using alternative Mathematical Methods. This function should be used only for checking, and only with an understanding of the circumstances in which the hypergeometric distribution applies.*

### Example

A bag contains 5 blue marbles and 4 red marbles. 4 balls are taken from the bag, without replacement between draws. Find the probability that the proportion of blue marbles in the 4 draws is greater than half. (2017 NHT Methods Exam 2 Section A Question 11)

![hCDf(3, 4, 4, 5, 5+4)]({{ '/files/hCDf.png' | relative_url }})