---
latex: true
slug: tank
commandtype: Function
title: tank (Function) - ClassPad Commands
description: differential equation for tank scenario
sm: true
update: 23/11/2022
---

tank(*Vin*, *QVin*, *Vout*, *Vo*, *Qo*)

- *Vin* is the rate of solution volume flowing into the tank
- *QVin* is the concentration of solute in incoming solution
- *Vout* is the rate of solution volume flowing out of the tank
- *Vo* is the initial solution volume in the tank
- *Qo* is the initial quantity of solute in the tank

Returns a differential equation relating **Q** the quantity of solute in the tank, **t** time, and **Q'** the derivative of **Q** with respect to **t**.

### Example

A tank initially has some quantity of chemical dissolved in $$ 8000 \mathrm{L} $$ water, with fresh water flowing into the tank at $$ 15 \mathrm{L/minute} $$ and solution flowing out of the tank at $$ 20 \mathrm{L/minute} $$. Find the equation which relates the mass of chemical and time. (2023 Specialist Exam 2 Section A Question 8)

![tank(15, 0, 20, 8000, Qo)]({{ '/files/tank.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
