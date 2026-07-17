## Areas of Triangles and Quadrilaterals

## Introduction

**Heron of Alexandria** (c. 10 AD – c. 75 AD) was a Greek mathematician and engineer who was active in his native city of Alexandria, Roman Egypt. He is considered one of the greatest experimenters of antiquity and his work is representative of the Hellenistic scientific tradition. Heron published a well-recognized formula for the area of a triangle, now known as **Heron's formula**. He also wrote three books on mensuration, dealing with the areas of squares, rectangles, triangles, trapezia, regular polygons, circles, and the surfaces of cylinders, cones, and spheres.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-001.jpg)

---

## Formulae for Area of Triangles

- **Standard Formula**: The area of a triangle is given by:
  $$
  \text{Area} = \frac{1}{2} \times \text{base} \times \text{height}
  $$

- **Heron's Formula**: For a triangle with side lengths $a$, $b$, and $c$, first calculate the semiperimeter, $s$:
  $$
  s = \frac{1}{2}(a+b+c)
  $$
  Then, the area is:
  $$
  \text{Area} = \sqrt{s(s-a)(s-b)(s-c)}
  $$

- **Equilateral Triangle**: For an equilateral triangle with side length $a$:
  $$
  \text{Area} = \frac{\sqrt{3}}{4} a^{2}
  $$
  $$
  \text{Height} = \frac{\sqrt{3}}{2} a
  $$

- **Isosceles Triangle**: For an isosceles triangle with equal sides $a$ and base $b$:
  $$
  \text{Area} = \frac{b}{4} \sqrt{4a^2 - b^2}
  $$

---

## Solved Examples

### Example: 1

Find the area of a triangle whose base is 25 cm long and the corresponding height is 10.8 cm.

#### Solution:

Given **base** $= 25 \text{ cm}$ and **height** $= 10.8 \text{ cm}$.

The area of the triangle is calculated as:
$$
\text{Area} = \frac{1}{2} \times \text{base} \times \text{height}
$$
$$
\text{Area} = \left(\frac{1}{2} \times 25 \times 10.8\right) \text{ cm}^2 = 135 \text{ cm}^2
$$
Hence, the area of the given triangle is **135 cm²**.

---

### Example: 2

Find the perimeter and area of a triangle whose sides are of lengths 52 cm, 56 cm and 60 cm respectively.

#### Solution:

Let the sides of the triangle be $a = 52 \text{ cm}$, $b = 56 \text{ cm}$, and $c = 60 \text{ cm}$.

The **perimeter** of the triangle is the sum of its sides:
$$
\text{Perimeter} = a+b+c = (52 + 56 + 60) \text{ cm} = 168 \text{ cm}
$$
The **semiperimeter**, $s$, is:
$$
s = \frac{1}{2}(a+b+c) = \frac{1}{2} \times 168 \text{ cm} = 84 \text{ cm}
$$
Now we find the differences:
- $s-a = (84-52) \text{ cm} = 32 \text{ cm}$
- $s-b = (84-56) \text{ cm} = 28 \text{ cm}$
- $s-c = (84-60) \text{ cm} = 24 \text{ cm}$

Using **Heron's formula** for the area:
$$
\begin{aligned}
\text{Area} (\Delta) & = \sqrt{s(s-a)(s-b)(s-c)} \\
& = \sqrt{84 \times 32 \times 28 \times 24} \text{ cm}^2 \\
& = \sqrt{(14 \times 6) \times (16 \times 2) \times (14 \times 2) \times (6 \times 4)} \text{ cm}^2 \\
& = (14 \times 6 \times 4 \times 2 \times 2) \text{ cm}^2 = 1344 \text{ cm}^2
\end{aligned}
$$
Hence, the area of the given triangle is **1344 cm²**.

---

### Example: 3

The lengths of the sides of a triangle are in the ratio $3:4:5$ and its perimeter is 144 cm. Find (i) the area of the triangle and (ii) the height corresponding to the longest side.

#### Solution:

Given the **perimeter** $= 144 \text{ cm}$ and the **ratio of sides** $= 3:4:5$.
The sum of the ratio terms is $3+4+5=12$.

Let the lengths of the sides be $a$, $b$, and $c$.
- $a = \left(144 \times \frac{3}{12}\right) \text{ cm} = 36 \text{ cm}$
- $b = \left(144 \times \frac{4}{12}\right) \text{ cm} = 48 \text{ cm}$
- $c = \left(144 \times \frac{5}{12}\right) \text{ cm} = 60 \text{ cm}$

The **semiperimeter**, $s$, is:
$$
s = \frac{1}{2}(a+b+c) = \frac{1}{2}(36+48+60) \text{ cm} = 72 \text{ cm}
$$
(i) Using **Heron's formula** to find the area:
$$
\begin{aligned}
\text{Area} (\Delta) & = \sqrt{s(s-a)(s-b)(s-c)} \\
& = \sqrt{72 \times (72-36) \times (72-48) \times (72-60)} \text{ cm}^2 \\
& = \sqrt{72 \times 36 \times 24 \times 12} \text{ cm}^2 \\
& = \sqrt{(36 \times 2) \times 36 \times 24 \times 12} \text{ cm}^2 = \sqrt{36 \times 36 \times 24 \times 24} \text{ cm}^2 \\
& = (36 \times 24) \text{ cm}^2 = 864 \text{ cm}^2
\end{aligned}
$$
The area of the triangle is **864 cm²**.

(ii) To find the height corresponding to the longest side, we use the standard area formula.
Let the **base** be the longest side, which is $60 \text{ cm}$, and the corresponding **height** be $h$.
$$
\text{Area} = \frac{1}{2} \times \text{base} \times \text{height}
$$
$$
864 \text{ cm}^2 = \frac{1}{2} \times 60 \times h
$$
$$
30h = 864 \implies h = \frac{864}{30} = 28.8 \text{ cm}
$$
The required height is **28.8 cm**.

---

### Example: 4

The sides of a triangle are 35 cm, 54 cm and 61 cm respectively. Find the length of its longest altitude.

#### Solution:

Let the sides be $a = 35 \text{ cm}$, $b = 54 \text{ cm}$, and $c = 61 \text{ cm}$.

The **semiperimeter**, $s$, is:
$$
s = \frac{1}{2}(35+54+61) \text{ cm} = \frac{150}{2} \text{ cm} = 75 \text{ cm}
$$
Using **Heron's formula**, the area is:
$$
\begin{aligned}
\text{Area} & = \sqrt{s(s-a)(s-b)(s-c)} \\
& = \sqrt{75 \times (75-35) \times (75-54) \times (75-61)} \text{ cm}^2 \\
& = \sqrt{75 \times 40 \times 21 \times 14} \text{ cm}^2 \\
& = \sqrt{(25 \times 3) \times (4 \times 10) \times (3 \times 7) \times (2 \times 7)} \text{ cm}^2 \\
& = \sqrt{25 \times 9 \times 4 \times (10 \times 2 \times 7 \times 7)} \text{ cm}^2 \text{ (re-evaluating)} \\
& = \sqrt{(15 \times 5) \times (5 \times 8) \times (3 \times 7) \times (2 \times 7)} = \sqrt{(3 \times 5 \times 5) \times (5 \times 2^3) \times (3 \times 7) \times (2 \times 7)} \\
& = \sqrt{15 \times 15 \times 14 \times 14 \times 4 \times 5} \text{ cm}^2 = (15 \times 14 \times 2)\sqrt{5} \text{ cm}^2 = 420\sqrt{5} \text{ cm}^2
\end{aligned}
$$
The **longest altitude** corresponds to the **shortest base**. The shortest side is $35 \text{ cm}$. Let the longest altitude be $h$.
$$
\text{Area} = \frac{1}{2} \times \text{base} \times h
$$
$$
420\sqrt{5} = \frac{1}{2} \times 35 \times h
$$
$$
h = \frac{2 \times 420\sqrt{5}}{35} \text{ cm} = 24\sqrt{5} \text{ cm}
$$
Hence, the longest altitude is **$24\sqrt{5}$ cm**.

---

### Example: 5

The perimeter of an equilateral triangle is 60 cm. Find its (i) area and (ii) height. (Given, $\sqrt{3} \approx 1.732$)

#### Solution:

Given the **perimeter** of the equilateral triangle is $60 \text{ cm}$.
The length of each side, $a$, is:
$$
a = \frac{60}{3} \text{ cm} = 20 \text{ cm}
$$
(i) The **area** of an equilateral triangle is:
$$
\begin{aligned}
\text{Area} & = \left(\frac{\sqrt{3}}{4} \times a^2\right) \\
& = \left(\frac{\sqrt{3}}{4} \times 20^2\right) \text{ cm}^2 = \left(\frac{\sqrt{3}}{4} \times 400\right) \text{ cm}^2 \\
& = 100\sqrt{3} \text{ cm}^2 \\
& = (100 \times 1.732) \text{ cm}^2 = 173.2 \text{ cm}^2
\end{aligned}
$$
The area is **173.2 cm²**.

(ii) The **height** ($h$) of an equilateral triangle is:
$$
\begin{aligned}
h & = \left(\frac{\sqrt{3}}{2} \times a\right) \\
& = \left(\frac{\sqrt{3}}{2} \times 20\right) \text{ cm} = 10\sqrt{3} \text{ cm} \\
& = (10 \times 1.732) \text{ cm} = 17.32 \text{ cm}
\end{aligned}
$$
The height is **17.32 cm**.

---

### Example: 6

The height of an equilateral triangle is 6 cm. Find its area.

#### Solution:

Let the side of the equilateral triangle be $a$. The height, $h$, is given by:
$$
h = \frac{\sqrt{3}}{2} a
$$
Given $h=6 \text{ cm}$:
$$
6 = \frac{\sqrt{3}}{2} a \implies a = \frac{12}{\sqrt{3}} = \frac{12\sqrt{3}}{3} = 4\sqrt{3} \text{ cm}
$$
The **area** of the triangle is:
$$
\begin{aligned}
\text{Area} & = \left(\frac{\sqrt{3}}{4} \times a^2\right) \\
& = \left(\frac{\sqrt{3}}{4} \times (4\sqrt{3})^2\right) \text{ cm}^2 \\
& = \left(\frac{\sqrt{3}}{4} \times 16 \times 3\right) \text{ cm}^2 = \left(\frac{\sqrt{3}}{4} \times 48\right) \text{ cm}^2 = 12\sqrt{3} \text{ cm}^2
\end{aligned}
$$
The area of the triangle is **$12\sqrt{3}$ cm²**.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-002.jpg)

---

### Example: 7

From a point in the interior of an equilateral triangle, perpendiculars are drawn on the three sides. The lengths of the perpendiculars are 14 cm, 10 cm, and 6 cm. Find the area of the triangle.

#### Solution:

Let $\triangle ABC$ be the equilateral triangle with side length $a$. Let $P$ be the interior point.
Let the perpendiculars from $P$ to the sides $BC$, $AC$, and $AB$ be $PL=14 \text{ cm}$, $PM=10 \text{ cm}$, and $PN=6 \text{ cm}$ respectively.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-003.jpg)

The area of the large triangle is the sum of the areas of the three smaller triangles formed by joining $P$ to the vertices:
$$
\text{ar}(\triangle ABC) = \text{ar}(\triangle PBC) + \text{ar}(\triangle PAC) + \text{ar}(\triangle PAB)
$$
$$
\frac{\sqrt{3}}{4} a^2 = \left(\frac{1}{2} \times BC \times PL\right) + \left(\frac{1}{2} \times AC \times PM\right) + \left(\frac{1}{2} \times AB \times PN\right)
$$
Since $AB=BC=AC=a$:
$$
\begin{aligned}
\frac{\sqrt{3}}{4} a^2 & = \left(\frac{1}{2} \times a \times 14\right) + \left(\frac{1}{2} \times a \times 10\right) + \left(\frac{1}{2} \times a \times 6\right) \\
\frac{\sqrt{3}}{4} a^2 & = 7a + 5a + 3a = 15a
\end{aligned}
$$
Since $a \neq 0$, we can divide by $a$:
$$
\frac{\sqrt{3}}{4} a = 15 \implies a = \frac{15 \times 4}{\sqrt{3}} = \frac{60}{\sqrt{3}} = 20\sqrt{3} \text{ cm}
$$
Now, we find the **area** of the triangle:
$$
\begin{aligned}
\text{Area} & = \left(\frac{\sqrt{3}}{4} \times a^2\right) = \left(\frac{\sqrt{3}}{4} \times (20\sqrt{3})^2\right) \text{ cm}^2 \\
& = \left(\frac{\sqrt{3}}{4} \times 400 \times 3\right) \text{ cm}^2 = \left(\frac{\sqrt{3}}{4} \times 1200\right) \text{ cm}^2 = 300\sqrt{3} \text{ cm}^2
\end{aligned}
$$
The area of the triangle is **$300\sqrt{3}$ cm²**.

---

### Example: 8

Find the area of an isosceles triangle each of whose equal sides is 13 cm and whose base is 24 cm.

#### Solution:

Here, we can use **Heron's formula** with $a=13 \text{ cm}$, $b=13 \text{ cm}$, and $c=24 \text{ cm}$.
The **semiperimeter**, $s$, is:
$$
s = \frac{1}{2}(13+13+24) \text{ cm} = \frac{50}{2} \text{ cm} = 25 \text{ cm}
$$
The area is:
$$
\begin{aligned}
\text{Area} (\Delta) & = \sqrt{s(s-a)(s-b)(s-c)} \\
& = \sqrt{25 \times (25-13) \times (25-13) \times (25-24)} \text{ cm}^2 \\
& = \sqrt{25 \times 12 \times 12 \times 1} \text{ cm}^2 \\
& = (5 \times 12) \text{ cm}^2 = 60 \text{ cm}^2
\end{aligned}
$$
The area of the triangle is **60 cm²**.

---

### Example: 9

The base of an isosceles triangle measures 24 cm and its area is 192 cm². Find its perimeter.

#### Solution:

Let $\triangle ABC$ be an isosceles triangle with base $BC = 24 \text{ cm}$. Let $AL$ be the altitude to the base.
Given **area** $= 192 \text{ cm}^2$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-004.jpg)

We first find the height ($h = AL$):
$$
\text{Area} = \frac{1}{2} \times \text{base} \times \text{height}
$$
$$
192 = \frac{1}{2} \times 24 \times h \implies 192 = 12h \implies h = \frac{192}{12} = 16 \text{ cm}
$$
In an isosceles triangle, the altitude to the base bisects the base. So, $BL = \frac{1}{2} \times BC = 12 \text{ cm}$.
Now, consider the right-angled triangle $\triangle ALB$. By **Pythagoras' theorem**, we find the length of the equal side $a = AB$:
$$
\begin{aligned}
a^2 = AB^2 &= BL^2 + AL^2 \\
a^2 &= (12)^2 + (16)^2 = 144 + 256 = 400 \\
a &= \sqrt{400} = 20 \text{ cm}
\end{aligned}
$$
The sides of the triangle are 20 cm, 20 cm, and 24 cm.
The **perimeter** is:
$$
\text{Perimeter} = (20+20+24) \text{ cm} = 64 \text{ cm}
$$

---

### Example: 10

The difference between the sides at right angles in a right-angled triangle is 14 cm. The area of the triangle is 120 cm². Calculate the perimeter of the triangle.

#### Solution:

Let the sides containing the right angle be $x \text{ cm}$ and $(x-14) \text{ cm}$.
The **area** of the triangle is given as $120 \text{ cm}^2$.
$$
\text{Area} = \frac{1}{2} \times \text{base} \times \text{height}
$$
$$
120 = \frac{1}{2} \times x \times (x-14)
$$
$$
240 = x^2 - 14x
$$
$$
x^2 - 14x - 240 = 0
$$
We solve this quadratic equation by factoring:
$$
x^2 - 24x + 10x - 240 = 0
$$
$$
x(x-24) + 10(x-24) = 0
$$
$$
(x-24)(x+10) = 0
$$
The possible values for $x$ are $x=24$ or $x=-10$. Since length cannot be negative, we take $x=24$.
The sides are:
- One side $= 24 \text{ cm}$
- Other side $= (24-14) \text{ cm} = 10 \text{ cm}$

The **hypotenuse** is found using Pythagoras' theorem:
$$
\text{Hypotenuse} = \sqrt{(24)^2 + (10)^2} = \sqrt{576+100} = \sqrt{676} = 26 \text{ cm}
$$
The **perimeter** of the triangle is:
$$
\text{Perimeter} = (24 + 10 + 26) \text{ cm} = 60 \text{ cm}
$$

---

### Example: 11

Calculate the area of the shaded region in the given figure.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-005.jpg)

The area of the shaded region is the area of the larger triangle minus the area of the smaller triangle.
$$
\text{Area of shaded region} = \text{ar}(\triangle ABC) - \text{ar}(\triangle DBC)
$$
**For $\triangle ABC$** (sides 122 m, 120 m, 22 m):
Semiperimeter $s_1$:
$$
s_1 = \frac{1}{2}(122+120+22) = \frac{264}{2} = 132 \text{ m}
$$
Area using Heron's formula:
$$
\begin{aligned}
\text{ar}(\triangle ABC) & = \sqrt{132 \times (132-122) \times (132-120) \times (132-22)} \\
& = \sqrt{132 \times 10 \times 12 \times 110} \text{ m}^2 \\
& = \sqrt{(12 \times 11) \times 10 \times 12 \times (11 \times 10)} \text{ m}^2 \\
& = \sqrt{12^2 \times 11^2 \times 10^2} \text{ m}^2 = (12 \times 11 \times 10) \text{ m}^2 = 1320 \text{ m}^2
\end{aligned}
$$

**For $\triangle DBC$** (sides 26 m, 24 m, 22 m):
Semiperimeter $s_2$:
$$
s_2 = \frac{1}{2}(26+24+22) = \frac{72}{2} = 36 \text{ m}
$$
Area using Heron's formula:
$$
\begin{aligned}
\text{ar}(\triangle DBC) & = \sqrt{36 \times (36-26) \times (36-24) \times (36-22)} \\
& = \sqrt{36 \times 10 \times 12 \times 14} \text{ m}^2 \\
& = \sqrt{36 \times (2 \times 5) \times (3 \times 4) \times (2 \times 7)} = 6 \sqrt{10 \times 12 \times 14} = 6 \sqrt{1680} \\
& = 6 \sqrt{16 \times 105} = 6 \times 4 \sqrt{105} = 24\sqrt{105} \text{ m}^2 \\
& \approx 24 \times 10.25 \text{ m}^2 \approx 246 \text{ m}^2
\end{aligned}
$$
**Area of the shaded region**:
$$
\text{Area} = (1320 - 246) \text{ m}^2 = 1074 \text{ m}^2
$$

---

## Area of Quadrilaterals

### Example: 12

Find the area of the quadrilateral $ABCD$ in which $AB=9 \text{ cm}$, $BC=40 \text{ cm}$, $CD=28 \text{ cm}$, $DA=15 \text{ cm}$ and $\angle ABC=90^{\circ}$.

#### Solution:

The area of the quadrilateral can be found by splitting it into two triangles, $\triangle ABC$ and $\triangle ACD$, along the diagonal $AC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-006.jpg)

First, consider the right-angled $\triangle ABC$:
$$
\text{Area}(\triangle ABC) = \frac{1}{2} \times AB \times BC = \frac{1}{2} \times 9 \times 40 = 180 \text{ cm}^2
$$
By **Pythagoras' theorem**, we find the length of the diagonal $AC$:
$$
AC^2 = AB^2 + BC^2 = 9^2 + 40^2 = 81 + 1600 = 1681
$$
$$
AC = \sqrt{1681} = 41 \text{ cm}
$$
Now, consider $\triangle ACD$ with sides $a=41 \text{ cm}$, $b=28 \text{ cm}$, and $c=15 \text{ cm}$.
Semiperimeter $s$:
$$
s = \frac{1}{2}(41+28+15) = \frac{84}{2} = 42 \text{ cm}
$$
Using **Heron's formula** for the area of $\triangle ACD$:
$$
\begin{aligned}
\text{Area}(\triangle ACD) & = \sqrt{42 \times (42-41) \times (42-28) \times (42-15)} \\
& = \sqrt{42 \times 1 \times 14 \times 27} \text{ cm}^2 \\
& = \sqrt{(3 \times 14) \times 14 \times (3 \times 9)} \text{ cm}^2 = \sqrt{14^2 \times 3^2 \times 9} \text{ cm}^2 \\
& = (14 \times 3 \times 3) \text{ cm}^2 = 126 \text{ cm}^2
\end{aligned}
$$
The **total area** of the quadrilateral $ABCD$ is:
$$
\text{Area(ABCD)} = \text{Area}(\triangle ABC) + \text{Area}(\triangle ACD) = (180 + 126) \text{ cm}^2 = 306 \text{ cm}^2
$$

---

### Example: 13

The adjacent sides of a parallelogram $ABCD$ are $AB=34 \text{ cm}$, $BC=20 \text{ cm}$ and diagonal $AC=42 \text{ cm}$. Find the area of the parallelogram.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-007.jpg)

A diagonal divides a parallelogram into two triangles of equal area. We can find the area of $\triangle ABC$ and multiply it by 2.
For $\triangle ABC$, the sides are $a=20 \text{ cm}$, $b=42 \text{ cm}$ (diagonal), and $c=34 \text{ cm}$.

Semiperimeter $s$:
$$
s = \frac{1}{2}(20+42+34) = \frac{96}{2} = 48 \text{ cm}
$$
Using **Heron's formula**:
$$
\begin{aligned}
\text{Area}(\triangle ABC) & = \sqrt{48 \times (48-20) \times (48-42) \times (48-34)} \\
& = \sqrt{48 \times 28 \times 6 \times 14} \text{ cm}^2 \\
& = \sqrt{(16 \times 3) \times (4 \times 7) \times (2 \times 3) \times (2 \times 7)} \text{ cm}^2 \\
& = \sqrt{16 \times 4 \times 3^2 \times 7^2 \times 2^2} = (4 \times 2 \times 3 \times 7 \times 2) \text{ cm}^2 \\
& = (14 \times 24) \text{ cm}^2 = 336 \text{ cm}^2
\end{aligned}
$$
The **area of the parallelogram** $ABCD$ is:
$$
\text{Area}(\| \text{gm } ABCD) = 2 \times \text{Area}(\triangle ABC) = 2 \times 336 = 672 \text{ cm}^2
$$

---

## Area of a Quadrilateral (Diagonal and Perpendiculars Method)

Let $ABCD$ be a quadrilateral with diagonal $AC$. Let $BL \perp AC$ and $DM \perp AC$. If $BL = h_1$ and $DM = h_2$, the area of the quadrilateral is given by:
$$
\text{Area} = \text{Area}(\triangle ABC) + \text{Area}(\triangle ACD)
$$
$$
\text{Area} = \left(\frac{1}{2} \times AC \times h_1\right) + \left(\frac{1}{2} \times AC \times h_2\right)
$$
$$
\text{Area} = \frac{1}{2} \times AC \times (h_1 + h_2)
$$

### Example: 14

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-008.jpg)

In a four-sided field, the length of the longer diagonal is 128 m. The lengths of the perpendiculars from the opposite vertices upon this diagonal are 22.7 m and 17.3 m. Find the area of the field.

#### Solution:

Let the diagonal $AC = 128 \text{ m}$.
Let the perpendiculars be $h_1 = 22.7 \text{ m}$ and $h_2 = 17.3 \text{ m}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-009.jpg)

Using the formula:
$$
\begin{aligned}
\text{Area of the field} & = \frac{1}{2} \times AC \times (h_1 + h_2) \\
& = \frac{1}{2} \times 128 \times (22.7 + 17.3) \text{ m}^2 \\
& = 64 \times 40 \text{ m}^2 = 2560 \text{ m}^2
\end{aligned}
$$
The area of the field is **2560 m²**.

---
## Some More Examples

### Example: 15

Find the area of the quadrilateral $ABCD$ in which $AB=9 \text{ m}$, $BC=40 \text{ m}$, $\angle ABC=90^{\circ}$, $CD=15 \text{ m}$ and $AD=28 \text{ m}$.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-010.jpg)

First, calculate the area of the right-angled $\triangle ABC$:
$$
\text{Area}(\triangle ABC) = \frac{1}{2} \times \text{base} \times \text{height} = \frac{1}{2} \times 40 \times 9 = 180 \text{ m}^2
$$
Next, find the length of the diagonal $AC$ using **Pythagoras' theorem** in $\triangle ABC$:
$$
AC^2 = AB^2 + BC^2 = 9^2 + 40^2 = 81 + 1600 = 1681
$$
$$
AC = \sqrt{1681} = 41 \text{ m}
$$
Now, find the area of $\triangle ACD$ with sides $AC=41 \text{ m}$, $CD=15 \text{ m}$, and $AD=28 \text{ m}$.
Semiperimeter $s$:
$$
s = \frac{1}{2}(41+15+28) = \frac{84}{2} = 42 \text{ m}
$$
Using **Heron's formula**:
$$
\begin{aligned}
\text{Area}(\triangle ACD) & = \sqrt{42 \times (42-41) \times (42-15) \times (42-28)} \\
& = \sqrt{42 \times 1 \times 27 \times 14} \text{ m}^2 \\
& = \sqrt{(3 \times 14) \times (3 \times 9) \times 14} = \sqrt{14^2 \times 3^2 \times 9} = 14 \times 3 \times 3 = 126 \text{ m}^2
\end{aligned}
$$
The **total area** of the quadrilateral is:
$$
\text{Area(Quad. } ABCD) = \text{Area}(\triangle ABC) + \text{Area}(\triangle ACD) = (180 + 126) \text{ m}^2 = 306 \text{ m}^2
$$

---

### Example: 16

A piece of land is in the shape of a rhombus whose perimeter is 400 m and one of its diagonals is 160 m. Find the area of the land.

#### Solution:

Let the rhombus be $PQRS$.
Given **perimeter** $= 400 \text{ m}$.
Since all sides of a rhombus are equal, the length of each side is:
$$
\text{Side} = \frac{400}{4} = 100 \text{ m}
$$
Let the diagonal be $PR = 160 \text{ m}$. The diagonal splits the rhombus into two congruent triangles, $\triangle PQR$ and $\triangle PSR$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-011.jpg)

Consider $\triangle PQR$, with sides $PQ=100 \text{ m}$, $QR=100 \text{ m}$, and $PR=160 \text{ m}$.
Semiperimeter $s$:
$$
s = \frac{1}{2}(100+100+160) = \frac{360}{2} = 180 \text{ m}
$$
Using **Heron's formula**:
$$
\begin{aligned}
\text{Area}(\triangle PQR) & = \sqrt{180 \times (180-100) \times (180-100) \times (180-160)} \\
& = \sqrt{180 \times 80 \times 80 \times 20} \text{ m}^2 \\
& = \sqrt{(3600) \times 80 \times 80} = \sqrt{36 \times 100 \times 6400} = 6 \times 10 \times 80 = 4800 \text{ m}^2
\end{aligned}
$$
The **area of the rhombus** is twice the area of one triangle:
$$
\text{Area of land} = 2 \times \text{Area}(\triangle PQR) = 2 \times 4800 = 9600 \text{ m}^2
$$

---

### Example: 17

Find the area of the parallelogram $ABCD$ in which $BC=12 \text{ cm}$, $CD=17 \text{ cm}$ and $BD=25 \text{ cm}$. Also, find the length of the altitude $AE$ from vertex $A$ on the side $BC$.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-012.jpg)

The diagonal $BD$ divides the parallelogram into two congruent triangles, $\triangle BCD$ and $\triangle DAB$.
First, find the area of $\triangle BCD$ with sides $12 \text{ cm}$, $17 \text{ cm}$, and $25 \text{ cm}$.
Semiperimeter $s$:
$$
s = \frac{1}{2}(12+17+25) = \frac{54}{2} = 27 \text{ cm}
$$
Using **Heron's formula**:
$$
\begin{aligned}
\text{Area}(\triangle BCD) & = \sqrt{27 \times (27-12) \times (27-17) \times (27-25)} \\
& = \sqrt{27 \times 15 \times 10 \times 2} \text{ cm}^2 \\
& = \sqrt{(9 \times 3) \times (3 \times 5) \times (5 \times 2) \times 2} = \sqrt{9 \times 9 \times 25 \times 4} \\
& = (3 \times 3 \times 5 \times 2) \text{ cm}^2 = 90 \text{ cm}^2
\end{aligned}
$$
The **area of the parallelogram** $ABCD$ is:
$$
\text{Area}(\| \text{gm } ABCD) = 2 \times \text{Area}(\triangle BCD) = 2 \times 90 = 180 \text{ cm}^2
$$
Now, let $AE = h$ be the altitude from vertex $A$ to the side $BC$. The base is $BC = AD = 12 \text{ cm}$.
$$
\text{Area}(\| \text{gm } ABCD) = \text{base} \times \text{altitude}
$$
$$
180 = BC \times AE = 12 \times h
$$
$$
h = \frac{180}{12} = 15 \text{ cm}
$$
The length of the altitude $AE$ is **15 cm**.

---

### Example: 18

The adjacent sides of a parallelogram are 36 cm and 27 cm in length. If the distance between the shorter sides is 12 cm, find the distance between the longer sides.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-013.jpg)

Let the sides be $a = 36 \text{ cm}$ (longer side) and $b = 27 \text{ cm}$ (shorter side).
The distance between the shorter sides is the altitude corresponding to base $b$, so $h_b = 12 \text{ cm}$.
Let the distance between the longer sides be $h_a = x \text{ cm}$.

The area of a parallelogram can be calculated in two ways:
$$
\text{Area} = \text{longer side} \times \text{distance between longer sides} = a \times h_a
$$
$$
\text{Area} = \text{shorter side} \times \text{distance between shorter sides} = b \times h_b
$$
Therefore,
$$
a \times h_a = b \times h_b
$$
$$
36 \times x = 27 \times 12
$$
$$
x = \frac{27 \times 12}{36} = \frac{27}{3} = 9
$$
The distance between the longer sides is **9 cm**.

---

### Example: 19

The diagonals of a rhombus are 48 cm and 20 cm long. Find (i) the area of the rhombus and (ii) the perimeter of the rhombus.

#### Solution:

(i) The **area** of a rhombus is given by half the product of its diagonals ($d_1$ and $d_2$):
$$
\text{Area} = \frac{1}{2} \times d_1 \times d_2 = \frac{1}{2} \times 48 \times 20 = 480 \text{ cm}^2
$$

(ii) The diagonals of a rhombus bisect each other at right angles.
Let the point of intersection be $O$. Then,
$OA = \frac{1}{2} \times 48 = 24 \text{ cm}$ and $OB = \frac{1}{2} \times 20 = 10 \text{ cm}$.
Also, $\angle AOB = 90^\circ$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-014.jpg)

Using **Pythagoras' theorem** in the right-angled $\triangle AOB$ to find the side length $AB$:
$$
AB^2 = OA^2 + OB^2 = (24)^2 + (10)^2 = 576 + 100 = 676
$$
$$
AB = \sqrt{676} = 26 \text{ cm}
$$
The **perimeter** of the rhombus is $4 \times \text{side}$:
$$
\text{Perimeter} = 4 \times 26 = 104 \text{ cm}
$$

---

### Example: 20

Find the area of the given trapezium $PQRS$ in which $RQ \| SP$ and $PQ \perp SP$ such that $RQ=7 \text{ m}$, $RS=13 \text{ m}$ and $SP=12 \text{ m}$.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-015.jpg)

Draw a line $RT$ perpendicular to $SP$. This forms a rectangle $PQRT$.
So, $TP = RQ = 7 \text{ m}$.
The length of $ST$ is $SP - TP = 12 - 7 = 5 \text{ m}$.
The height of the trapezium is $RT$, which is equal to $PQ$.
In the right-angled triangle $\triangle RTS$, by **Pythagoras' theorem**:
$$
RT^2 = RS^2 - ST^2 = 13^2 - 5^2 = 169 - 25 = 144
$$
$$
RT = \sqrt{144} = 12 \text{ m}
$$
The distance between the parallel sides (height) is $12 \text{ m}$.
The **area** of the trapezium $PQRS$ is:
$$
\begin{aligned}
\text{Area} & = \frac{1}{2} \times (\text{sum of parallel sides}) \times \text{height} \\
& = \frac{1}{2} \times (RQ + SP) \times RT \\
& = \frac{1}{2} \times (7 + 12) \times 12 \text{ m}^2 = (19 \times 6) \text{ m}^2 = 114 \text{ m}^2
\end{aligned}
$$
The area is **114 m²**.

---

### Example: 21

In the given figure, $ABCD$ is a rectangle of length 51 cm and breadth 25 cm. A trapezium PQCD with its parallel sides $QC$ and $PD$ in the ratio $9:8$ is cut off from the rectangle. If the area of the trapezium PQCD is $\frac{5}{6}$th part of the area of the rectangle, find the lengths QC and PD.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-016.jpg)

**Area of rectangle** $ABCD = \text{length} \times \text{breadth} = 51 \times 25 = 1275 \text{ cm}^2$.

**Area of trapezium** $PQCD$ is given as $\frac{5}{6}$ of the area of the rectangle:
$$
\text{Area(trap. } PQCD) = \frac{5}{6} \times 1275 = \frac{6375}{6} = 1062.5 \text{ cm}^2
$$
Let the parallel sides of the trapezium be $QC=9k$ and $PD=8k$.
The height of the trapezium is the breadth of the rectangle, which is $CD = 25 \text{ cm}$.
The area of a trapezium is given by:
$$
\text{Area} = \frac{1}{2} \times (\text{sum of parallel sides}) \times \text{height}
$$
$$
1062.5 = \frac{1}{2} \times (9k + 8k) \times 25
$$
$$
1062.5 = \frac{1}{2} \times 17k \times 25
$$
$$
1062.5 = \frac{425}{2} k \implies 1062.5 = 212.5k
$$
$$
k = \frac{1062.5}{212.5} = 5
$$
Now, we find the lengths of the sides:
- $QC = 9k = 9 \times 5 = 45 \text{ cm}$
- $PD = 8k = 8 \times 5 = 40 \text{ cm}$

Hence, **QC = 45 cm** and **PD = 40 cm**.

---

### Example: 22

A farmer has a triangular field with sides 360 m, 200 m and 240 m, where he grows wheat. Adjacent to this field, he has another triangular field with sides 240 m, 320 m and 400 m, divided into two parts by joining the midpoint of the longest side to the opposite vertex. He grows potatoes in one part and onions in the other part. How much area (in hectares) has been used for wheat, potatoes and onions? (1 hectare = 10000 m²)

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-017.jpg)

**Area for Wheat (Triangle ABC):**
Sides are $a=200 \text{ m}$, $b=240 \text{ m}$, $c=360 \text{ m}$.
Semiperimeter $s_1$:
$$
s_1 = \frac{1}{2}(200+240+360) = \frac{800}{2} = 400 \text{ m}
$$
Area using Heron's formula:
$$
\begin{aligned}
\text{Area}(\triangle ABC) & = \sqrt{400(400-200)(400-240)(400-360)} \\
& = \sqrt{400 \times 200 \times 160 \times 40} \text{ m}^2 \\
& = \sqrt{4 \times 10^2 \times 2 \times 10^2 \times 1.6 \times 10^2 \times 0.4 \times 10^2} \text{ (re-evaluating)} \\
& = \sqrt{400 \times 200 \times 160 \times 40} = \sqrt{512000000} = \sqrt{256 \times 2 \times 10^6} \\
& = 16 \times 1000 \sqrt{2} = 16000\sqrt{2} \text{ m}^2 \approx 16000 \times 1.414 = 22624 \text{ m}^2
\end{aligned}
$$
Area in hectares: $\frac{22624}{10000} \approx 2.26$ hectares.

**Area for Potatoes and Onions (Triangle ACD):**
Sides are $a=240 \text{ m}$, $b=320 \text{ m}$, $c=400 \text{ m}$.
Semiperimeter $s_2$:
$$
s_2 = \frac{1}{2}(240+320+400) = \frac{960}{2} = 480 \text{ m}
$$
Area using Heron's formula:
$$
\begin{aligned}
\text{Area}(\triangle ACD) & = \sqrt{480(480-240)(480-320)(480-400)} \\
& = \sqrt{480 \times 240 \times 160 \times 80} \text{ m}^2 \\
& = \sqrt{(240 \times 2) \times 240 \times (160) \times (160/2)} \text{ (re-evaluating)} \\
& = \sqrt{48 \times 24 \times 16 \times 8 \times 10000} = \sqrt{147456 \times 10000} = 384 \times 100 = 38400 \text{ m}^2
\end{aligned}
$$
Area in hectares: $\frac{38400}{10000} = 3.84$ hectares.

This area is divided into two equal parts by a median (line from vertex C to midpoint E of the longest side AD). A median divides a triangle into two triangles of equal area.
$$
\text{Area for potatoes} = \text{Area for onions} = \frac{3.84}{2} = 1.92 \text{ hectares}
$$
**Summary:**
- **Wheat**: 2.26 hectares
- **Potatoes**: 1.92 hectares
- **Onions**: 1.92 hectares

---
### Example: 23

Reenu made a picture of an aeroplane with coloured paper as shown in the figure given below. Find the total area of the paper used.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-018.jpg)

**Area of Region I (Isosceles Triangle):**
Sides are $a=5 \text{ cm}$, $b=5 \text{ cm}$, $c=1 \text{ cm}$.
$s = \frac{1}{2}(5+5+1) = 5.5 \text{ cm}$.
$\text{Area} = \sqrt{5.5(5.5-5)(5.5-5)(5.5-1)} = \sqrt{5.5 \times 0.5 \times 0.5 \times 4.5} = \sqrt{6.1875} \approx 2.49 \text{ cm}^2$.

**Area of Region II (Rectangle):**
Length = 6.5 cm, Breadth = 1 cm.
$\text{Area} = 6.5 \times 1 = 6.5 \text{ cm}^2$.

**Area of Region III (Isosceles Trapezium):**
Parallel sides are 1 cm and 2 cm. Equal non-parallel sides are 1 cm.
Height $h = \sqrt{1^2 - 0.5^2} = \sqrt{0.75} = \frac{\sqrt{3}}{2} \text{ cm}$.
$\text{Area} = \frac{1}{2}(1+2) \times \frac{\sqrt{3}}{2} = \frac{3\sqrt{3}}{4} \approx \frac{3 \times 1.732}{4} \approx 1.3 \text{ cm}^2$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-019.jpg)

**Area of Region IV (Right Triangle):**
Base = 1.5 cm, Height = 6 cm.
$\text{Area} = \frac{1}{2} \times 1.5 \times 6 = 4.5 \text{ cm}^2$.

**Area of Region V (Right Triangle):**
Identical to Region IV.
$\text{Area} = 4.5 \text{ cm}^2$.

**Total Area:**
$$
\text{Total Area} = (2.49 + 6.5 + 1.3 + 4.5 + 4.5) \text{ cm}^2 = 19.29 \text{ cm}^2
$$

---
### Example: 24

A kite in the shape of a square with a diagonal 32 cm and an isosceles triangle of base 8 cm and sides 6 cm each is to be made of three different shades as shown in the figure. How much paper of each shade has been used in it?

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-020.jpg)

The kite consists of a square $ABCD$ and an isosceles triangle $DEF$. The diagonal of the square $AC = 32 \text{ cm}$.

The diagonals of a square are equal and bisect each other at right angles. So, $BD = 32 \text{ cm}$ and $OB=OD=16 \text{ cm}$.

**Area of Shade I ($\triangle ABC$):**
This is a triangle with base $AC = 32 \text{ cm}$ and height $OB = 16 \text{ cm}$.
$$
\text{Area}(\text{Shade I}) = \frac{1}{2} \times \text{base} \times \text{height} = \frac{1}{2} \times 32 \times 16 = 256 \text{ cm}^2
$$

**Area of Shade II ($\triangle ADC$):**
This triangle is congruent to $\triangle ABC$.
$$
\text{Area}(\text{Shade II}) = \frac{1}{2} \times 32 \times 16 = 256 \text{ cm}^2
$$

**Area of Shade III ($\triangle DEF$):**
This is an isosceles triangle with sides $a=8 \text{ cm}$, $b=6 \text{ cm}$, $c=6 \text{ cm}$.
Semiperimeter $s = \frac{1}{2}(8+6+6) = 10 \text{ cm}$.
Using Heron's formula:
$$
\begin{aligned}
\text{Area}(\text{Shade III}) & = \sqrt{10(10-8)(10-6)(10-6)} \\
& = \sqrt{10 \times 2 \times 4 \times 4} = \sqrt{320} = \sqrt{64 \times 5} = 8\sqrt{5} \text{ cm}^2 \\
& \approx 8 \times 2.24 = 17.92 \text{ cm}^2
\end{aligned}
$$
The areas are: **Shade I = 256 cm²**, **Shade II = 256 cm²**, and **Shade III = 17.92 cm²**.

---

### Example: 25

A field is in the shape of a trapezium whose parallel sides are 25 m and 10 m and the nonparallel sides are 14 m and 13 m. Find the area of the field.

#### Solution:

Let the trapezium be $ABCD$ with $AB=25 \text{ m}$ parallel to $CD=10 \text{ m}$. Non-parallel sides are $DA=14 \text{ m}$ and $BC=13 \text{ m}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Mensuration/Areas-of-Triangles-and-Quadrilaterals/class-09-Ch-14-A-BooK-021.jpg)

Draw $CE \| DA$. This makes $ADCE$ a parallelogram.
So, $AE = CD = 10 \text{ m}$ and $CE = DA = 14 \text{ m}$.
The remaining length on the base is $EB = AB - AE = 25 - 10 = 15 \text{ m}$.

Now consider $\triangle EBC$ with sides $15 \text{ m}$, $13 \text{ m}$, and $14 \text{ m}$.
Semiperimeter $s = \frac{1}{2}(15+13+14) = \frac{42}{2} = 21 \text{ m}$.
Area of $\triangle EBC$ using Heron's formula:
$$
\text{Area}(\triangle EBC) = \sqrt{21(21-15)(21-13)(21-14)} = \sqrt{21 \times 6 \times 8 \times 7} = \sqrt{7056} = 84 \text{ m}^2
$$
Let $CF$ be the altitude of $\triangle EBC$ from $C$ to $EB$. This is also the height of the trapezium.
$$
\text{Area}(\triangle EBC) = \frac{1}{2} \times \text{base} \times \text{height} = \frac{1}{2} \times EB \times CF
$$
$$
84 = \frac{1}{2} \times 15 \times CF \implies CF = \frac{84 \times 2}{15} = \frac{168}{15} = 11.2 \text{ m}
$$
The height of the trapezium is $11.2 \text{ m}$.
**Area of trapezium ABCD**:
$$
\text{Area} = \frac{1}{2} \times (AB+CD) \times CF = \frac{1}{2} \times (25+10) \times 11.2 = \frac{1}{2} \times 35 \times 11.2 = 196 \text{ m}^2
$$

---
### Example: 26

If each side of a triangle is doubled, then find the ratio of the area of the new triangle thus formed and the given triangle.

#### Solution:

Let the sides of the original triangle be $a, b, c$.
Its semiperimeter is $s = \frac{1}{2}(a+b+c)$.
Its area is $\Delta = \sqrt{s(s-a)(s-b)(s-c)}$.

The new triangle has sides $2a, 2b, 2c$.
Its semiperimeter is $S = \frac{1}{2}(2a+2b+2c) = a+b+c = 2s$.
The area of the new triangle, $\Delta_{new}$, is:
$$
\begin{aligned}
\Delta_{new} & = \sqrt{S(S-2a)(S-2b)(S-2c)} \\
& = \sqrt{2s(2s-2a)(2s-2b)(2s-2c)} \\
& = \sqrt{2s \cdot 2(s-a) \cdot 2(s-b) \cdot 2(s-c)} \\
& = \sqrt{16s(s-a)(s-b)(s-c)} \\
& = 4\sqrt{s(s-a)(s-b)(s-c)} = 4\Delta
\end{aligned}
$$
The ratio of the area of the new triangle to the area of the given triangle is:
$$
\frac{\Delta_{new}}{\Delta} = \frac{4\Delta}{\Delta} = \frac{4}{1}
$$
The ratio is **4:1**.

---
### Example: 27

The length and breadth of a rectangular park are in the ratio $8:5$. A path, 1.5 m wide, running all around the outside of the park has an area of $594 \text{ m}^2$. Find the dimensions of the park.

#### Solution:

Let the length of the park be $8x$ metres and the breadth be $5x$ metres.
Area of the park = $(8x)(5x) = 40x^2 \text{ m}^2$.

The path is 1.5 m wide on all sides.
Length of the park including the path = $8x + 1.5 + 1.5 = (8x+3) \text{ m}$.
Breadth of the park including the path = $5x + 1.5 + 1.5 = (5x+3) \text{ m}$.

Area of the park including the path = $(8x+3)(5x+3) = 40x^2 + 24x + 15x + 9 = (40x^2 + 39x + 9) \text{ m}^2$.

Area of the path = (Area including path) - (Area of park)
$$
594 = (40x^2 + 39x + 9) - 40x^2
$$
$$
594 = 39x + 9
$$
$$
585 = 39x
$$
$$
x = \frac{585}{39} = 15
$$
The dimensions of the park are:
- **Length** $= 8x = 8 \times 15 = 120 \text{ m}$
- **Breadth** $= 5x = 5 \times 15 = 75 \text{ m}$