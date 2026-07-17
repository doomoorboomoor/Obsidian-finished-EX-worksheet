## Distance of a Point From a Line

### Theorem 3
**Statement:** Prove that the length of the perpendicular from a given point $P(x_1, y_1)$ on a line $Ax + By + C = 0$ is given by:
$$
d = \frac{|Ax_1 + By_1 + C|}{\sqrt{A^2 + B^2}}
$$

#### Proof
Let $L$ be the line represented by the equation $Ax + By + C = 0$ and let $P(x_1, y_1)$ be a given point outside it.

Let this line $L$ intersect the x-axis and y-axis at the points $Q$ and $R$ respectively, and let $PM \perp QR$.

Now,
$$
\begin{aligned}
Ax + By + C = 0 & \Rightarrow Ax + By = -C \\
& \Rightarrow \frac{Ax}{-C} + \frac{By}{-C} = 1 \\
& \Rightarrow \frac{x}{\left(\frac{-C}{A}\right)} + \frac{y}{\left(\frac{-C}{B}\right)} = 1
\end{aligned}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-H-BooK-001.jpg)

Thus, the given line intersects the x-axis and the y-axis at the points:
$$
Q\left(\frac{-C}{A}, 0\right) \text{ and } R\left(0, \frac{-C}{B}\right)
$$
Draw $PM \perp QR$.

**Area of** $\triangle PQR$:
$$
\begin{align*}
\text{Area} & = \frac{1}{2} \cdot \left| x_1 \left(\frac{-C}{B} - 0\right) + 0 \cdot (0 - y_1) + \left(\frac{-C}{A}\right) \cdot \left(y_1 + \frac{C}{B}\right) \right| \\
& = \frac{1}{2} \cdot \left| -C \left(\frac{x_1}{B} + \frac{y_1}{A} + \frac{C}{AB}\right) \right| = \frac{1}{2} \cdot \left| \frac{C}{AB} (Ax_1 + By_1 + C) \right| \\
& = \left| \frac{C}{2AB} (Ax_1 + By_1 + C) \right| \tag{i}
\end{align*}
$$
Also, area of $\triangle PQR = \frac{1}{2} \times QR \times PM = \frac{1}{2} \times PM \times \sqrt{(OQ)^2 + (OR)^2}$:
$$
\begin{align*}
\text{Area} & = \frac{1}{2} \times PM \times \sqrt{\left(\frac{-C}{A}\right)^2 + \left(\frac{-C}{B}\right)^2} \quad \left[\because OQ = \frac{-C}{A} \text{ and } OR = \frac{-C}{B}\right] \\
& = \frac{1}{2} \times PM \times \sqrt{\frac{C^2}{A^2} + \frac{C^2}{B^2}} \tag{ii}
\end{align*}
$$
From (i) and (ii), we get:
$$
\begin{aligned}
& \frac{1}{2} \times PM \times \sqrt{\frac{C^2}{A^2} + \frac{C^2}{B^2}} = \left| \frac{C}{2AB} \cdot (Ax_1 + By_1 + C) \right| \\
\Rightarrow & \frac{1}{2} \times \frac{|C|}{|AB|} \times \sqrt{A^2 + B^2} \times PM = \frac{|C|}{2|AB|} \cdot |Ax_1 + By_1 + C| \\
\Rightarrow & PM = \frac{|Ax_1 + By_1 + C|}{\sqrt{A^2 + B^2}}
\end{aligned}
$$
Hence, $d = \frac{|Ax_1 + By_1 + C|}{\sqrt{A^2 + B^2}}$, where $PM = d$.

**Remark:** Clearly, the length of the perpendicular from the **origin** on the line $Ax + By + C = 0$ is $\frac{|C|}{\sqrt{A^2 + B^2}}$.

---

## Distance Between Two Parallel Lines

### Theorem 4
**Statement:** Prove that the distance between two parallel lines $Ax + By + C_1 = 0$ and $Ax + By + C_2 = 0$ is given by:
$$
d = \frac{|C_2 - C_1|}{\sqrt{A^2 + B^2}}
$$

#### Solution
Let $L_1$ and $L_2$ be two given parallel lines represented by:
$$
\begin{align*}
Ax + By + C_1 = 0 \tag{i} \\
\text{and } Ax + By + C_2 = 0 \tag{ii}
\end{align*}
$$
Putting $y=0$ in (i), we get $x = \left(-\frac{C_1}{A}\right)$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-H-BooK-002.jpg)

Thus, $L_1$ intersects the x-axis at $Q = \left(-\frac{C_1}{A}, 0\right)$.
Let $QR \perp L_2$ and let $d = |QR|$. Then,
$d$ = length of perpendicular from $Q\left(-\frac{C_1}{A}, 0\right)$ on $Ax + By + C_2 = 0$.
$$
\Rightarrow d = \frac{\left|A \times \frac{(-C_1)}{A} + B \times 0 + C_2\right|}{\sqrt{A^2 + B^2}} = \frac{|C_2 - C_1|}{\sqrt{A^2 + B^2}}
$$

**Remark:** Distance between two parallel lines $y = mx + C_1$ and $y = mx + C_2$ is given by $d = \frac{|C_2 - C_1|}{\sqrt{1 + m^2}}$.

---

## Summary

- **Length of perpendicular** from a point $P(x_1, y_1)$ on the line $Ax + By + C = 0$ is given by $d = \frac{|Ax_1 + By_1 + C|}{\sqrt{A^2 + B^2}}$.
- **Distance between two parallel lines** $Ax + By + C_1 = 0$ and $Ax + By + C_2 = 0$ is given by $d = \frac{|C_2 - C_1|}{\sqrt{A^2 + B^2}}$.
- **Distance between** $y = mx + C_1$ and $y = mx + C_2$ is given by $d = \frac{|C_2 - C_1|}{\sqrt{1 + m^2}}$.

---

## Solved Examples

### Example 1
**Find the distance of the point $(4,1)$ from the line $3x - 4y + 12 = 0$.**

#### Solution
Clearly, the required distance is the length of the perpendicular from the point $P(4,1)$ on the line $3x - 4y + 12 = 0$.

Let the required distance be $d$. Then,
$$
d = \frac{|3 \times 4 - 4 \times 1 + 12|}{\sqrt{3^2 + (-4)^2}} = \frac{|12 - 4 + 12|}{5} = \frac{20}{5} \text{ units} = 4 \text{ units.}
$$

---

### Example 2
**Find the distance of the point $(-1,1)$ from the line $12(x+6) = 5(y-2)$.**

#### Solution
The given point is $P(-1,1)$ and the given line is $12x + 72 = 5y - 10$, which simplifies to $12x - 5y + 82 = 0$.

Let the required distance be $d$. Then,
$d$ = length of perpendicular from $P(-1,1)$ on the line $12x - 5y + 82 = 0$.
$$
d = \frac{|12 \times (-1) - 5 \times 1 + 82|}{\sqrt{(12)^2 + (-5)^2}} = \frac{|-12 - 5 + 82|}{\sqrt{144 + 25}} = \frac{65}{\sqrt{169}} = \frac{65}{13} = 5 \text{ units.}
$$

---

### Example 3
**Find the length of the perpendicular from the point $(a, b)$ to the line $\frac{x}{a} + \frac{y}{b} = 1$.**

#### Solution
The given point is $P(a, b)$ and the given line is $bx + ay = ab$, or $bx + ay - ab = 0$.

Let $d$ be the length of the perpendicular from $P(a, b)$ to the line $bx + ay - ab = 0$.
Then,
$$
d = \frac{|b \times a + a \times b - ab|}{\sqrt{b^2 + a^2}} = \frac{|ab + ab - ab|}{\sqrt{a^2 + b^2}} = \frac{|ab|}{\sqrt{a^2 + b^2}} \text{ units.}
$$

---

### Example 4
**Find the length of the perpendicular from the origin to the line $4x + 3y - 2 = 0$.**

#### Solution
The given point is the origin $P(0,0)$ and the given line is $4x + 3y - 2 = 0$.

Let $d$ be the length of the perpendicular from $P(0,0)$ to the line $4x + 3y - 2 = 0$.
Then,
$$
d = \frac{|4 \times 0 + 3 \times 0 - 2|}{\sqrt{4^2 + 3^2}} = \frac{|-2|}{\sqrt{16 + 9}} = \frac{2}{5} \text{ unit.}
$$

---

### Example 5
**If $p$ is the length of the perpendicular from the origin to the line whose intercepts on the axes are $a$ and $b$, then show that $\frac{1}{p^2} = \frac{1}{a^2} + \frac{1}{b^2}$.**

#### Solution
The equation of the line making intercepts $a$ and $b$ on the axes is given by:
$$
\frac{x}{a} + \frac{y}{b} = 1, \text{ i.e., } \frac{x}{a} + \frac{y}{b} - 1 = 0 \tag{i}
$$
Since $p$ is the length of the perpendicular from $O(0,0)$ to line (i), we have:
$$
p = \frac{\left|\frac{1}{a} \times 0 + \frac{1}{b} \times 0 - 1\right|}{\sqrt{\frac{1}{a^2} + \frac{1}{b^2}}} = \frac{|-1|}{\sqrt{\frac{1}{a^2} + \frac{1}{b^2}}} = \frac{1}{\sqrt{\frac{1}{a^2} + \frac{1}{b^2}}}
$$
$$
\Rightarrow p^2 = \frac{1}{\left(\frac{1}{a^2} + \frac{1}{b^2}\right)} = \frac{a^2b^2}{b^2 + a^2}
$$
$$
\Rightarrow \frac{1}{p^2} = \frac{b^2 + a^2}{a^2b^2} = \left(\frac{b^2}{a^2b^2} + \frac{a^2}{a^2b^2}\right) = \left(\frac{1}{a^2} + \frac{1}{b^2}\right)
$$
Hence, $\frac{1}{p^2} = \frac{1}{a^2} + \frac{1}{b^2}$.

---

### Example 6
**Find the perpendicular distance of the line joining the points $A(\cos\theta, \sin\theta)$ and $B(\cos\phi, \sin\phi)$ from the origin.**

#### Solution
We know that the equation of the line AB is given by:
$$
\begin{align*}
& \frac{y - \sin\theta}{x - \cos\theta} = \frac{\sin\phi - \sin\theta}{\cos\phi - \cos\theta} \\
\Rightarrow & \frac{y - \sin\theta}{x - \cos\theta} = \frac{2 \cos\left(\frac{\phi+\theta}{2}\right) \sin\left(\frac{\phi-\theta}{2}\right)}{-2 \sin\left(\frac{\phi+\theta}{2}\right) \sin\left(\frac{\phi-\theta}{2}\right)} \\
\Rightarrow & \frac{y - \sin\theta}{x - \cos\theta} = \frac{\cos\left(\frac{\phi+\theta}{2}\right)}{-\sin\left(\frac{\phi+\theta}{2}\right)} \\
\Rightarrow & x \cos\left(\frac{\phi+\theta}{2}\right) + y \sin\left(\frac{\phi+\theta}{2}\right) = \cos\theta \cos\left(\frac{\phi+\theta}{2}\right) + \sin\theta \sin\left(\frac{\phi+\theta}{2}\right) \\
\Rightarrow & x \cos\left(\frac{\phi+\theta}{2}\right) + y \sin\left(\frac{\phi+\theta}{2}\right) - \cos\left(\frac{\phi+\theta}{2} - \theta\right) = 0 \\
\Rightarrow & x \cos\left(\frac{\phi+\theta}{2}\right) + y \sin\left(\frac{\phi+\theta}{2}\right) - \cos\left(\frac{\phi-\theta}{2}\right) = 0 \tag{i}
\end{align*}
$$
Let $d$ be the perpendicular distance from the origin to line (i). Then,
$$
d = \frac{\left|0 \times \cos\left(\frac{\phi+\theta}{2}\right) + 0 \times \sin\left(\frac{\phi+\theta}{2}\right) - \cos\left(\frac{\phi-\theta}{2}\right)\right|}{\sqrt{\cos^2\left(\frac{\phi+\theta}{2}\right) + \sin^2\left(\frac{\phi+\theta}{2}\right)}} = \left|\cos\left(\frac{\phi-\theta}{2}\right)\right|
$$
Hence, the required distance is $\left|\cos\left(\frac{\phi-\theta}{2}\right)\right|$.

---

### Example 7
**If $p_1$ and $p_2$ are the lengths of perpendiculars from the origin to the lines $x \sec\theta + y \operatorname{cosec}\theta = a$ and $x \cos\theta - y \sin\theta = a \cos2\theta$ respectively, then prove that $4p_1^2 + p_2^2 = a^2$.**

#### Solution
We have the first line:
$$
x \sec\theta + y \operatorname{cosec}\theta = a \Rightarrow \frac{x}{\cos\theta} + \frac{y}{\sin\theta} - a = 0 \tag{i}
$$
Now, $p_1$ is the length of the perpendicular from the origin to line (i), so we have:
$$
\begin{align*}
& p_1 = \frac{\left|\frac{1}{\cos\theta} \times 0 + \frac{1}{\sin\theta} \times 0 - a\right|}{\sqrt{\frac{1}{\cos^2\theta} + \frac{1}{\sin^2\theta}}} = \frac{|-a|}{\sqrt{\frac{\sin^2\theta + \cos^2\theta}{\sin^2\theta\cos^2\theta}}} = |a| \sin\theta \cos\theta = \frac{|a|}{2} \sin2\theta \\
\Rightarrow & 2p_1 = |a| \sin2\theta \\
\Rightarrow & 4p_1^2 = a^2 \sin^2 2\theta \tag{ii}
\end{align*}
$$
The other line is $x \cos\theta - y \sin\theta - a \cos2\theta = 0$.
Now, $p_2$ is the length of the perpendicular from the origin to this line, so we have:
$$
\begin{align*}
p_2 & = \frac{|0 \times \cos\theta - 0 \times \sin\theta - a \cos2\theta|}{\sqrt{\cos^2\theta + \sin^2\theta}} = |a \cos2\theta| \\
\Rightarrow & p_2^2 = a^2 \cos^2 2\theta \tag{iv}
\end{align*}
$$
Adding (ii) and (iv), we get:
$$
\begin{aligned}
4p_1^2 + p_2^2 & = a^2(\sin^2 2\theta + \cos^2 2\theta) \\
\Rightarrow 4p_1^2 + p_2^2 & = a^2
\end{aligned}
$$

---

### Example 8
**What are the points on the y-axis whose perpendicular distance from the line $\frac{x}{3} - \frac{y}{4} = 1$ is 3 units?**

#### Solution
The equation of the line is $\frac{x}{3} - \frac{y}{4} = 1 \Rightarrow 4x - 3y = 12 \Rightarrow 4x - 3y - 12 = 0$.

Let $P(0, y)$ be a point on the y-axis. Its perpendicular distance from the line $4x - 3y - 12 = 0$ is 3 units.
$$
\begin{aligned}
& \frac{|4 \times 0 - 3y - 12|}{\sqrt{4^2 + (-3)^2}} = 3 \\
\Rightarrow & |-3y - 12| = 3 \times 5 = 15 \\
\Rightarrow & |-3(y+4)| = 15 \\
\Rightarrow & 3|y+4| = 15 \\
\Rightarrow & |y+4| = 5 \\
\Rightarrow & (y+4 = 5) \text{ or } (y+4 = -5) \\
\Rightarrow & y = 1 \text{ or } y = -9
\end{aligned}
$$
Hence, the required points are $(0, 1)$ and $(0, -9)$.

---

### Example 9
**Find the distance between the parallel lines $15x + 8y - 34 = 0$ and $15x + 8y + 31 = 0$.**

#### Solution
The lines are of the form $Ax + By + C_1 = 0$ and $Ax + By + C_2 = 0$.
Here, $A=15$, $B=8$, $C_1 = -34$, and $C_2 = 31$.
The distance $d$ between the parallel lines is:
$$
d = \frac{|C_2 - C_1|}{\sqrt{A^2 + B^2}} = \frac{|31 - (-34)|}{\sqrt{15^2 + 8^2}} = \frac{|65|}{\sqrt{225 + 64}} = \frac{65}{\sqrt{289}} = \frac{65}{17} \text{ units.}
$$

---

### Example 10
**Find the distance between the lines $3x - 4y + 9 = 0$ and $6x - 8y - 17 = 0$.**

#### Solution
The first line is $3x - 4y + 9 = 0$.
The second line is $6x - 8y - 17 = 0$. To make the coefficients of $x$ and $y$ the same, we can divide the second equation by 2:
$3x - 4y - \frac{17}{2} = 0$.

Now the lines are in the form $Ax + By + C_1 = 0$ and $Ax + By + C_2 = 0$.
Here, $A=3$, $B=-4$, $C_1 = 9$, and $C_2 = -\frac{17}{2}$.
The distance $d$ is:
$$
d = \frac{|C_2 - C_1|}{\sqrt{A^2 + B^2}} = \frac{\left|-\frac{17}{2} - 9\right|}{\sqrt{3^2 + (-4)^2}} = \frac{\left|-\frac{35}{2}\right|}{\sqrt{9+16}} = \frac{\frac{35}{2}}{5} = \frac{35}{10} = \frac{7}{2} \text{ units.}
$$

---

### Example 11
**Prove that the line $5x - 2y - 1 = 0$ is mid-parallel to the lines $5x - 2y - 9 = 0$ and $5x - 2y + 7 = 0$.**

#### Solution
Let the three lines be:
- $L: 5x - 2y - 1 = 0$
- $L_1: 5x - 2y - 9 = 0$
- $L_2: 5x - 2y + 7 = 0$

All three lines have the same slope $m = \frac{5}{2}$, so they are parallel.

Distance between $L$ and $L_1$:
$$
d_1 = \frac{|-1 - (-9)|}{\sqrt{5^2 + (-2)^2}} = \frac{|8|}{\sqrt{25+4}} = \frac{8}{\sqrt{29}} \text{ units.}
$$
Distance between $L$ and $L_2$:
$$
d_2 = \frac{|7 - (-1)|}{\sqrt{5^2 + (-2)^2}} = \frac{|8|}{\sqrt{29}} = \frac{8}{\sqrt{29}} \text{ units.}
$$
Since $d_1 = d_2$, the line $L$ is equidistant from $L_1$ and $L_2$.
Hence, $5x - 2y - 1 = 0$ is mid-parallel to the lines $5x - 2y - 9 = 0$ and $5x - 2y + 7 = 0$.

---

### Example 12
**Find the equation of the line midway between the parallel lines $9x + 6y - 7 = 0$ and $3x + 2y + 6 = 0$.**

#### Solution
The first line is $9x + 6y - 7 = 0$.
The second line is $3x + 2y + 6 = 0$. To make the coefficients match, we multiply the second equation by 3: $9x + 6y + 18 = 0$.

Let the equation of the midway line be $9x + 6y + C = 0$. The constant term $C$ must be the average of the constant terms of the two given lines.
$$
C = \frac{-7 + 18}{2} = \frac{11}{2}
$$
So the equation is $9x + 6y + \frac{11}{2} = 0$.
Multiplying by 2 to clear the fraction, we get:
$$
18x + 12y + 11 = 0
$$

---

### Example 13
**Find the coordinates of a point on the line $x + y + 3 = 0$, whose distance from the line $x + 2y + 2 = 0$ is $\sqrt{5}$.**

#### Solution
Let the required point be $P(a, b)$. Since it lies on the line $x + y + 3 = 0$, we have:
$$
a + b + 3 = 0 \Rightarrow b = -a - 3 \tag{i}
$$
The distance from $P(a, b)$ to the line $x + 2y + 2 = 0$ is $\sqrt{5}$.
$$
\begin{align*}
& \frac{|a + 2b + 2|}{\sqrt{1^2 + 2^2}} = \sqrt{5} \\
\Rightarrow & |a + 2b + 2| = \sqrt{5} \times \sqrt{5} = 5 \\
\Rightarrow & (a + 2b + 2 = 5) \text{ or } (a + 2b + 2 = -5) \\
\Rightarrow & a + 2b = 3 \quad \text{ or } \quad a + 2b = -7 \tag{ii}
\end{align*}
$$
**Case 1:** $a + 2b = 3$.
Substitute $b = -a - 3$ from (i):
$a + 2(-a - 3) = 3 \Rightarrow a - 2a - 6 = 3 \Rightarrow -a = 9 \Rightarrow a = -9$.
Then $b = -(-9) - 3 = 9 - 3 = 6$.
So one point is $(-9, 6)$.

**Case 2:** $a + 2b = -7$.
Substitute $b = -a - 3$ from (i):
$a + 2(-a - 3) = -7 \Rightarrow a - 2a - 6 = -7 \Rightarrow -a = -1 \Rightarrow a = 1$.
Then $b = -(1) - 3 = -4$.
So the other point is $(1, -4)$.

Hence, the required points are $A(-9, 6)$ and $B(1, -4)$.

---

