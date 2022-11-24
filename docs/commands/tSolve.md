---
latex: true
slug: tSolve
commandtype: Function
title: tSolve (Function) - ClassPad Commands
description: solution of tank scenario
sm: true
update: 23/11/2022
---

tSolve(*Vin*, *QVin*, *Vout*, *Vo*, *Qo*)

- *Vin* is the rate of solution volume flowing into the tank
- *QVin* is the concentration of solute in incoming solution
- *Vout* is the rate of solution volume flowing out of the tank
- *Vo* is the initial solution volume in the tank
- *Qo* is the initial quantity of solute in the tank

Returns an equation relating **Q** the quantity of solute in the tank and **t** time.

### Example

A tank initially has $$ 20 \mathrm{kg} $$ salt dissolved in $$ 100 \mathrm{L} $$ water, with pure water flowing into the tank at $$ 10 \mathrm{L/minute} $$ and solution flowing out of the tank at $$ 5 \mathrm{L/minute} $$. Find the equation which relates the mass of salt and time. (2016 Specialist Exam 2 Section B Question 3a)

![tSolve(10, 0, 5, 100, 20)]({{ '/files/tSolve.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})