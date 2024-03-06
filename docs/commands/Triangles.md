---
latex: true
slug: Triangles
commandtype: eActivity
title: Triangles (eActivity) - ClassPad Commands
description: triangle geometry
update: 6/3/2024
---

<style>
  img {
    vertical-align: top;
  }
</style>

Modify the values of the input variables, then click the top line and hit EXE. The outputs are stored in the relevant variables.

Find unknown side lengths, angles and area given some known values.

### SAAA

Find side lengths and area given 1 side length and 3 angles.

Input: *a*, *α*, *β*, *γ*
- *a* is the side length opposite angle *α*
- *α* is the angle opposite side *a*
- *β* is the angle opposite side *b*
- *γ* is the angle opposite side *c*

*α* + *β* + *γ* = 180°

Output: *b*, *c*, *A*
- *b* is the side length opposite angle *β*
- *c* is the side length opposite angle *γ*
- *A* is the area

#### Example

![a = 4; alpha = 90; beta = 60; gamma = 30]({{ '/files/TriangleSAAA0.png' | relative_url }}) 
![b = 2 sqrt(3); c = 2; A = 2 sqrt(3)]({{ '/files/TriangleSAAA1.png' | relative_url }})

### SAS

Find side lengths, angles and area given 2 side lengths and 1 angle between the known sides.

Input: *a*, *b*, *γ*
- *a* is the side length opposite angle *α*
- *b* is the side length opposite angle *β*
- *γ* is the angle opposite side *c*

Output: *c*, *α*, *β*, *A*
- *c* is the side length opposite angle *γ*
- *α* is the angle opposite side *a*
- *β* is the angle opposite side *b*
- *A* is the area

#### Example

![a = 2; b = 2 sqrt(3); gamme = 90]({{ '/files/TriangleSAS0.png' | relative_url }}) 
![c = 4; alpha = 30; beta = 60; A = 2 sqrt(3)]({{ '/files/TriangleSAS1.png' | relative_url }})

### SSA

Find side lengths, angles and area given 2 side lengths and the angle opposite *a*.

Input: *a*, *b*, *α*, *dβ*
- *a* is the side length opposite angle *α*
- *b* is the side length opposite angle *β*
- *α* is the angle opposite side *a*
- *dβ* is the range of the angle opposite *b* (usually either acute or obtuse)

Output: *β*, *γ*, *c*, *A*
- *β* is the angle opposite side *b*
- *γ* is the angle opposite side *c*
- *c* is the side length opposite angle *γ*
- *A* is the area

#### Example

![a = 2; b = 2 sqrt(3); alpha = 30]({{ '/files/TriangleSSA0.png' | relative_url }}) 
![beta = 60; gamma = 90; c = 4; A = 2 sqrt(3)]({{ '/files/TriangleSSA1.png' | relative_url }})

### SSS

Find angles and area given 3 side lengths.

Input: *a*, *b*, *c*
- *a* is the side length opposite angle *α*
- *b* is the side length opposite angle *β*
- *c* is the side length opposite angle *γ*

Output: *α*, *β*, *γ*, *A*
- *α* is the angle opposite side *a*
- *β* is the angle opposite side *b*
- *γ* is the angle opposite side *c*
- *A* is the area

#### Example

![a = 2; b = 2 sqrt(3); c = 4]({{ '/files/TriangleSSS0.png' | relative_url }}) 
![alpha = 30; beta = 60; gamma = 90; A = 2 sqrt(3)]({{ '/files/TriangleSSS1.png' | relative_url }})

#### Contributed by [{{ site.data.contributors.nhan.name }}]({{ site.data.contributors.nhan.url }})
