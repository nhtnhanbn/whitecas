---
latex: true
slug: biCDf
commandtype: Function
title: biCDf (Function) - ClassPad Commands
description: binomial cumulative distribution
update: 4/7/2022
---

biCDf(*l*, *u*, *n*, *p*)
- *l* is the query lower boundary
- *u* is the query upper boundary
- *n* is the number of trials
- *p* is the probability of success each trial

***l* and *u* should evaluate to numbers, not expressions in terms of unknown variables. Prefer to use [discrete]({{ '/docs/commands/discrete' | relative_url }}) if it would be more appropriate.**

Equivalent to the builtin binomialCDf(*l*, *u*, *n*, *p*), but returns exact values in Standard mode whereas binomialCDf can return only decimal answers.

Returns the probability of between and including *l* and *u* successes from *n* trials with *p* probability of success each trial.

### Example

Let $$ X \sim \mathrm{Bi}(7, p) $$. Find $$ \mathrm{Pr}(2 \leq X \leq 3) $$ as a polynomial in terms of $$ p $$. (2017 Methods Exam 2 Section B Question 3f)

![biCDf(2, 3, 7, p)]({{ '/files/biCDf.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})