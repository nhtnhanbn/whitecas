---
latex: true
slug: scalares
commandtype: Function
title: scalares (Function) - ClassPad Commands
description: scalar resolute
sm: true
update: 23/11/2022
---

scalares(*a*, *b*)

- *a*, *b* are vectors

Returns the scalar resolute of *a* in the direction of *b*.

### Example

Find $$ \alpha $$ for which the scalar resolute of $$ 3\boldsymbol{\hat{\imath}} + 2\boldsymbol{\hat{\jmath}} + \alpha\boldsymbol{\hat{k}} $$ in the direction of
$$ 4\boldsymbol{\hat{\imath}} - \boldsymbol{\hat{\jmath}} + \alpha^2 \boldsymbol{\hat{k}} $$ equals $$ \dfrac{74}{\sqrt{273}} $$. (2016 Specialist Exam 2 Section A Question 11)

![solve(scalares([3,2,alpha], [4,-1,alpha&2])=74/sqrt(273), alpha)]({{ '/files/scalares.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})