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

A tank initially has $$ 300 \mathrm{g} $$ salt dissolved in $$ 50 \mathrm{L} $$ water, with water containing $$ 15 \mathrm{g/L} $$ salt flowing into the tank at $$ 2 \mathrm{L/minute} $$ and solution flowing out of the tank at $$ 5 \mathrm{L/minute} $$. Find the equation which relates the mass of salt and time. (2020 Specialist Exam 2 Section A Question 10)

![tank(2, 15, 5, 50, 300)]({{ '/files/tank.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})