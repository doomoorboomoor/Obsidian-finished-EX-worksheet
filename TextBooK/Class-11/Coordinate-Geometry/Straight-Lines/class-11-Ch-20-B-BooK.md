## Slope of a Line

---

## Inclination of a Line

The **angle of inclination** or simply the **inclination** of a line is the angle $\theta$ which the part of the line above the $x$-axis makes with the positive direction of the $x$-axis, measured in an anticlockwise direction.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-001.jpg)
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-002.jpg)

Clearly, $0^{\circ} \leq \theta < 180^{\circ}$.

**Remarks:**
1. The inclination of a line parallel to the $x$-axis or the $x$-axis itself is $0^{\circ}$.
2. The inclination of a line parallel to the $y$-axis or the $y$-axis itself is $90^{\circ}$.

A **Horizontal Line** is any line parallel to the $x$-axis or the $x$-axis itself.
A **Vertical Line** is any line parallel to the $y$-axis or the $y$-axis itself.
An **Oblique Line** is a line which is neither horizontal nor vertical.

---

## Slope or Gradient of a Line

If $\theta$ is the inclination of a non-vertical line, then $m=\tan \theta$ is called the **slope** of the line.

### Example 1:

Find the slope of a line whose inclination is:
1. $45^{\circ}$
2. $60^{\circ}$
3. $150^{\circ}$

#### Solution:

Let $m$ be the slope of the line. Then,
1. $m=\tan 45^{\circ}=1$.
2. $m=\tan 60^{\circ}=\sqrt{3}$.
3. $m=\tan 150^{\circ}=\tan \left(180^{\circ}-30^{\circ}\right)=-\tan 30^{\circ}=\frac{-1}{\sqrt{3}}$.

---

**Remark 1:** The slope of a horizontal line is 0.
We know that the inclination of a horizontal line is $0^{\circ}$. So, the slope of a horizontal line is $m=\tan 0^{\circ}=0$.

**Remark 2:** The slope of a vertical line is not defined.
We know that the inclination of a vertical line is $90^{\circ}$. So, the slope of a vertical line is $m=\tan 90^{\circ}$, which is not defined.

### Example 2:

What is the inclination of a line whose slope is:
1. zero?
2. positive?
3. negative?
4. not defined?

#### Solution:

Let $\theta$ be the inclination of the given line. Then, $m=\tan \theta$.
1. $m=0 \Rightarrow \tan \theta=0 \Rightarrow \theta=0^{\circ} \quad [\because 0^{\circ} \leq \theta<180^{\circ}]$
2. $m>0 \Rightarrow \tan \theta>0 \Rightarrow \theta$ lies between $0^{\circ}$ and $90^{\circ} \Rightarrow \theta$ is acute.
3. $m<0 \Rightarrow \tan \theta<0 \Rightarrow \theta$ lies between $90^{\circ}$ and $180^{\circ} \Rightarrow \theta$ is obtuse.
4. We know that a vertical line is the only line whose slope is not defined. And, the inclination of a vertical line is $90^{\circ}$. Hence, the inclination of a line whose slope is not defined is $90^{\circ}$.

---

## Slope of a Line Passing Through Two Given Points

**Theorem 1:** *Prove that the slope of a non-vertical line passing through the points $A(x_1, y_1)$ and $B(x_2, y_2)$ is given by $m=\frac{(y_2-y_1)}{(x_2-x_1)}$*.

**Proof:** Let $X'OX$ and $YOY'$ be the coordinate axes. Let us consider a non-vertical line $CAB$, passing through the points $A(x_1, y_1)$ and $B(x_2, y_2)$. Let $\theta$ be its inclination.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-003.jpg)

Draw $AL \perp OX$, $BM \perp OX$ and $AN \perp BM$.
Then, $\angle BAN=\angle ACX=\theta$ (corr. $\angle s$).

From right triangle $ANB$, we have:
$$
\tan \theta=\frac{B N}{A N}=\frac{(B M-N M)}{L M}=\frac{(B M-A L)}{(O M-O L)}=\frac{\left(y_{2}-y_{1}\right)}{\left(x_{2}-x_{1}\right)}
$$
$$
\Rightarrow m=\frac{\left(y_{2}-y_{1}\right)}{\left(x_{2}-x_{1}\right)} \quad [\because \tan \theta=m]
$$
Hence, the slope of the line joining the points $A(x_1, y_1)$ and $B(x_2, y_2)$ is given by,
$$
m=\frac{\left(y_{2}-y_{1}\right)}{\left(x_{2}-x_{1}\right)}
$$

### Example 3:

Find the slope of the line passing through the points:
1. $(-2, 3)$ and $(8, -5)$
2. $(4, -3)$ and $(6, -3)$
3. $(3, -1)$ and $(3, 2)$

#### Solution:

1. Let $A(-2, 3)$ and $B(8, -5)$ be the given points. Then,
   $$
   \text{slope of } AB=\frac{-5-3}{8-(-2)}=\frac{-8}{10}=\frac{-4}{5}. \quad \left[\because m=\frac{\left(y_{2}-y_{1}\right)}{\left(x_{2}-x_{1}\right)}\right]
   $$
2. Let $C(4, -3)$ and $D(6, -3)$ be the given points. Then,
   $$
   \text{slope of } CD=\frac{-3-(-3)}{6-4}=\frac{-3+3}{2}=\frac{0}{2}=0
   $$
   **ALITER:** The points $C(4, -3)$ and $D(6, -3)$ have the same $y$-coordinate. So, $CD$ is a line parallel to the $x$-axis. Hence, its slope is 0.
3. Let $P(3, -1)$ and $Q(3, 2)$ be the given points. Then,
   $$
   \text{slope of } PQ=\frac{2-(-1)}{3-3}=\frac{3}{0}
   $$
   which is not defined.
   **ALITER:** The points $P(3, -1)$ and $Q(3, 2)$ have the same $x$-coordinate. So, $PQ$ is a vertical line. Hence, its slope is not defined.

---

### Example 4:

If the slope of the line passing through the points $(2, 5)$ and $(x, 3)$ is 2, find the value of $x$.

#### Solution:

Let $A(2, 5)$ and $B(x, 3)$ be the given points. Then,
$$
\text{slope of } AB = \frac{3-5}{x-2}=\frac{-2}{(x-2)}.
$$
$$
\therefore \quad \frac{-2}{(x-2)}=2 \Leftrightarrow 2 x-4=-2 \Leftrightarrow 2 x=2 \Leftrightarrow x=1 .
$$
Hence, $x=1$.

---

### Example 5:

Find the value of $x$ so that the inclination of the line joining the points $(x, -3)$ and $(2, 5)$ is $135^{\circ}$.

#### Solution:

Let $A(x, -3)$ and $B(2, 5)$ be the given points. Then,
$$
\text{slope of } AB=\frac{5-(-3)}{2-x}=\frac{8}{(2-x)}
$$
But, slope of $AB=\tan 135^{\circ}=\tan(180^{\circ}-45^{\circ})=-\tan 45^{\circ}=-1$.
$$
\therefore \quad \frac{8}{(2-x)}=-1 \Leftrightarrow x-2=8 \Leftrightarrow x=10.
$$
Hence, $x=10$.

---

### Example 6:

Find the angle between the $x$-axis and the line joining the points $(3, -1)$ and $(4, -2)$.

#### Solution:

Let $A(3, -1)$ and $B(4, -2)$ be the given points and let $m$ be the slope of the line $AB$. Then,
$$
m=\frac{-2-(-1)}{4-3}=\frac{-2+1}{1}=-1. \quad \left[\because m=\frac{\left(y_{2}-y_{1}\right)}{\left(x_{2}-x_{1}\right)}\right]
$$
Let $\theta$ be the angle between the $x$-axis and the line $AB$. Then,
$$
\tan \theta=m=-1=-\tan 45^{\circ}=\tan \left(180^{\circ}-45^{\circ}\right)=\tan 135^{\circ}.
$$
$$
\therefore \theta=135^{\circ}.
$$
Hence, the required angle is $135^{\circ}$.

---

## Slopes of Parallel Lines

**Theorem 2:** *Prove that two non-vertical lines are parallel, if and only if their slopes are equal.*

**Proof:** Let $L_1$ and $L_2$ be two non-vertical lines with slopes $m_1$ and $m_2$ respectively. Let their inclinations be $\theta_1$ and $\theta_2$ respectively.

First we assume that $L_1$ and $L_2$ are parallel.
Then, $L_1 \text{ and } L_2 \text{ are parallel} \Rightarrow \theta_1 = \theta_2 \Rightarrow \tan \theta_1 = \tan \theta_2 \Rightarrow m_1 = m_2$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-004.jpg)

Thus, non-vertical parallel lines have equal slopes.

Conversely, let $m_1=m_2$. Then,
$$
m_1 = m_2 \Rightarrow \tan \theta_1 = \tan \theta_2 \Rightarrow \theta_1 = \theta_2 \quad [\because 0^{\circ} \leq \theta<180^{\circ}]
$$
$\Rightarrow L_1 \text{ and } L_2$ are parallel.

Thus, non-vertical lines having equal slopes are parallel.
Hence, two non-vertical lines are parallel if and only if their slopes are equal.

---

## Slopes of Perpendicular Lines

**Theorem 3:** *Prove that two non-vertical lines with slopes $m_1$ and $m_2$ are perpendicular if and only if $m_1 m_2 = -1$.*

**Proof:** Let $L_1$ and $L_2$ be two non-vertical lines with slopes $m_1$ and $m_2$ respectively. Let their inclinations be $\theta_1$ and $\theta_2$ respectively. Then, $m_1=\tan \theta_1$ and $m_2=\tan \theta_2$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-005.jpg)

First we assume that $L_1$ and $L_2$ are perpendicular to each other.
Then, $\theta_2 = (90^{\circ}+\theta_1)$
$\Rightarrow \tan \theta_2 = \tan (90^{\circ}+\theta_1) = -\cot \theta_1$
$\Rightarrow \tan \theta_2 = -\frac{1}{\tan \theta_1}$
$\Rightarrow m_2 = -\frac{1}{m_1} \Rightarrow m_1 m_2 = -1$.

Thus, when $L_1 \perp L_2$, then $m_1 m_2 = -1$.

Conversely, let $L_1$ and $L_2$ be two lines with slopes $m_1$ and $m_2$ respectively such that $m_1 m_2 = -1$.
Let $m_1 = \tan \theta_1$ and $m_2 = \tan \theta_2$. Then,
$$
m_1 m_2 = -1 \Rightarrow \tan \theta_1 \cdot \tan \theta_2 = -1
$$
$$
\Rightarrow \tan \theta_2 = \frac{-1}{\tan \theta_1} = -\cot \theta_1 = \tan(90^{\circ}+\theta_1)
$$
$\Rightarrow \theta_2 = 90^{\circ} + \theta_1 \Rightarrow \theta_2$ and $\theta_1$ differ by $90^{\circ}$
$\Rightarrow L_1$ and $L_2$ are perpendicular to each other.

Thus, when $m_1 m_2 = -1$, then $L_1 \perp L_2$.
Hence, $L_1$ and $L_2$ are perpendicular to each other, if and only if $m_1 m_2 = -1$.

---

## Summary

Let $L_1$ and $L_2$ be two lines whose slopes are $m_1$ and $m_2$ respectively. Then,
1. $L_1 \parallel L_2 \Leftrightarrow m_1 = m_2$
2. $L_1 \perp L_2 \Rightarrow m_1 m_2 = -1$

### Example 7:

Show that the line joining the points $(2, -3)$ and $(-5, 1)$ is parallel to the line joining the points $(7, -1)$ and $(0, 3)$.

#### Solution:

Let $A(2, -3)$, $B(-5, 1)$, $C(7, -1)$ and $D(0, 3)$ be the given points.
Then, slope of $AB = \frac{1-(-3)}{-5-2} = \frac{4}{-7} = -\frac{4}{7}$.
And, slope of $CD = \frac{3-(-1)}{0-7} = \frac{4}{-7} = -\frac{4}{7}$.
$\therefore$ slope of $AB$ = slope of $CD$.
Hence, $AB \parallel CD$.

---

### Example 8:

Show that the line joining the points $(2, -5)$ and $(-2, 5)$ is perpendicular to the line joining the points $(6, 3)$ and $(1, 1)$.

#### Solution:

Let $A(2, -5)$, $B(-2, 5)$, $C(6, 3)$ and $D(1, 1)$ be the given points.
Let $m_1$ and $m_2$ be the slopes of $AB$ and $CD$ respectively. Then,
$$
m_1 = \text{slope of } AB = \frac{5-(-5)}{-2-2} = \frac{10}{-4} = -\frac{5}{2}
$$
$$
m_2 = \text{slope of } CD = \frac{1-3}{1-6} = \frac{-2}{-5} = \frac{2}{5}
$$
$$
\therefore m_1 m_2 = \left(\frac{-5}{2}\right) \times \frac{2}{5} = -1
$$
Hence, $AB \perp CD$.

---

### Example 9:

If the line through the points $(-2, 6)$ and $(4, 8)$ is perpendicular to the line through the points $(8, 12)$ and $(x, 24)$, find the value of $x$.

#### Solution:

Let $A(-2, 6)$, $B(4, 8)$, $C(8, 12)$ and $D(x, 24)$ be the given points.
Let $m_1$ and $m_2$ be the slopes of $AB$ and $CD$ respectively. Then,
$$
m_1 = \text{slope of } AB = \frac{(8-6)}{4-(-2)} = \frac{2}{6} = \frac{1}{3}
$$
$$
m_2 = \text{slope of } CD = \frac{(24-12)}{(x-8)} = \frac{12}{(x-8)}
$$
Now, $AB \perp CD \Leftrightarrow m_1 m_2 = -1$
$$
\Leftrightarrow \frac{1}{3} \times \frac{12}{(x-8)} = -1
$$
$$
\Leftrightarrow -x+8=4 \Leftrightarrow x=4
$$
Hence, the required value of $x$ is 4.

---

### Example 10:

Without using Pythagoras's theorem show that the points $(4, 4)$, $(3, 5)$ and $(-1, -1)$ are the vertices of a right-angled triangle.

#### Solution:

Let $A(4, 4)$, $B(3, 5)$ and $C(-1, -1)$ be the vertices of $\triangle ABC$.
Let $m_1$ and $m_2$ be the slopes of $AB$ and $AC$ respectively. Then,
$m_1 = \text{slope of } AB = \frac{(5-4)}{(3-4)}=-1$.
$m_2 = \text{slope of } AC = \frac{(-1-4)}{(-1-4)}=\frac{-5}{-5}=1$.
$\therefore m_1 m_2 = -1$.
So, $AB \perp AC$ and therefore, $\angle CAB=90^{\circ}$.
Hence, the given points are the vertices of a right triangle.

---

### Example 11:

Using slopes, show that the points $(5, 1)$, $(1, -1)$ and $(11, 4)$ are collinear.

#### Solution:

Let $A(5, 1)$, $B(1, -1)$ and $C(11, 4)$ be the given points. Then,
$$
\text{slope of } AB = \frac{(-1-1)}{(1-5)} = \frac{-2}{-4} = \frac{1}{2}
$$
and
$$
\text{slope of } BC = \frac{4-(-1)}{11-1} = \frac{5}{10} = \frac{1}{2}.
$$
$\therefore$ slope of $AB$ = slope of $BC$
$\Rightarrow AB \parallel BC$ and have a point $B$ in common
$\Rightarrow A, B, C$ are collinear.
Hence, the given points are collinear.

---

### Example 12:

Find the value of $x$ for which the points $(x, -1)$, $(2, 1)$ and $(4, 5)$ are collinear.

#### Solution:

Let $A(x, -1)$, $B(2, 1)$ and $C(4, 5)$ be the given collinear points.
Then, by collinearity of $A, B, C$ we have: slope of $AB$ = slope of $BC$.
$$
\frac{1-(-1)}{2-x} = \frac{(5-1)}{(4-2)} \Rightarrow \frac{2}{2-x}=2 \Rightarrow 2-x=1 \Rightarrow x=1.
$$
Hence, $x=1$.

---

### Example 13:

If the points $(h, 0)$, $(a, b)$ and $(0, k)$ lie on a line, show that $\frac{a}{h}+\frac{b}{k}=1$.

#### Solution:

Let $A(h, 0)$, $B(a, b)$ and $C(0, k)$ be the given collinear points.
Since the given points $A, B, C$ are collinear, we have slope of $AB$ = slope of $BC$.
$$
\therefore \frac{b-0}{a-h} = \frac{k-b}{0-a} \Leftrightarrow \frac{b}{(a-h)} = \frac{(b-k)}{a}
$$
$$
\Leftrightarrow ab=(a-h)(b-k)
$$
$$
\Leftrightarrow ak+hb=hk
$$
$$
\Leftrightarrow \frac{a}{h}+\frac{b}{k}=1 \quad \text{[on dividing both sides by } hk]
$$
Hence, $\frac{a}{h}+\frac{b}{k}=1$.

---

### Example 14:

Using slopes, show that the vertices $(-2, -1)$, $(4, 0)$, $(3, 3)$ and $(-3, 2)$ are the vertices of a parallelogram.

#### Solution:

Let $A(-2, -1)$, $B(4, 0)$, $C(3, 3)$ and $D(-3, 2)$ be the vertices of the given quadrilateral $ABCD$. Then,
- slope of $AB = \frac{0-(-1)}{4-(-2)} = \frac{1}{6}$
- slope of $DC = \frac{3-2}{3-(-3)} = \frac{1}{6}$
- slope of $BC = \frac{3-0}{3-4} = \frac{3}{-1} = -3$
- slope of $AD = \frac{2-(-1)}{-3-(-2)} = \frac{3}{-1} = -3$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-006.jpg)

$\therefore$ slope of $AB$ = slope of $DC \Rightarrow AB \parallel DC$.
$\therefore$ slope of $BC$ = slope of $AD \Rightarrow BC \parallel AD$.
Hence, $ABCD$ is a parallelogram.

---

### Example 15:

$A(-4, 2)$, $B(2, 6)$, $C(8, 5)$ and $D(9, -7)$ are the vertices of a quadrilateral $ABCD$. If $P, Q, R, S$ are the midpoints of $AB, BC, CD$ and $DA$ respectively, using slopes, show that $PQRS$ is a parallelogram.

#### Solution:

Clearly, the points $P, Q, R, S$ are given by
$P(-1, 4)$, $Q\left(5, \frac{11}{2}\right)$, $R\left(\frac{17}{2}, -1\right)$ and $S\left(\frac{5}{2}, \frac{-5}{2}\right)$.

- slope of $PQ = \frac{\left(\frac{11}{2}-4\right)}{(5+1)} = \frac{3}{12} = \frac{1}{4}$
- slope of $SR = \frac{\left(-1+\frac{5}{2}\right)}{\left(\frac{17}{2}-\frac{5}{2}\right)} = \frac{3}{12} = \frac{1}{4}$
- slope of $QR = \frac{\left(-1-\frac{11}{2}\right)}{\left(\frac{17}{2}-5\right)} = \left(\frac{-13}{2} \times \frac{2}{7}\right) = \frac{-13}{7}$
- slope of $PS = \frac{\left(\frac{-5}{2}-4\right)}{\left(\frac{5}{2}+1\right)} = \left(\frac{-13}{2} \times \frac{2}{7}\right) = \frac{-13}{7}$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-007.jpg)

$\therefore$ slope of $PQ$ = slope of $SR \Rightarrow PQ \parallel SR$.
$\therefore$ slope of $QR$ = slope of $PS \Rightarrow QR \parallel PS$.
Hence, $PQRS$ is a parallelogram.

---

## Angle Between Two Non-Vertical and Non-Perpendicular Lines

**Theorem 4:** *If $\alpha$ is the acute angle between two non-vertical and non-perpendicular lines $L_1$ and $L_2$ with slopes $m_1$ and $m_2$ then prove that*
$$
\tan \alpha=\left|\frac{m_{2}-m_{1}}{1+m_{1} m_{2}}\right|, \text{ where } 1+m_{1} m_{2} \neq 0.
$$

**Proof:** Let $L_1$ and $L_2$ be the two given non-vertical and non-perpendicular lines with slopes $m_1$ and $m_2$ respectively. Let $\alpha_1$ and $\alpha_2$ be their respective inclinations. Then,
$$
m_1=\tan \alpha_1 \text{ and } m_2=\tan \alpha_2.
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Straight-Lines/class-11-Ch-20-B-BooK-008.jpg)

Let $\theta$ and $(180^{\circ}-\theta)$ be the angles between $L_1$ and $L_2$.
From the given figure, we have
$$
\theta=\alpha_{2}-\alpha_{1}, \text{ where } \alpha_{1}, \alpha_{2} \neq 90^{\circ}
$$
$$
\Rightarrow \tan \theta=\tan \left(\alpha_{2}-\alpha_{1}\right)=\frac{\tan \alpha_{2}-\tan \alpha_{1}}{1+\tan \alpha_{1} \tan \alpha_{2}}
$$
$$
\Rightarrow \tan \theta=\frac{\left(m_{2}-m_{1}\right)}{\left(1+m_{1} m_{2}\right)} \quad \dots \text{(i), where } 1+m_1m_2 \neq 0.
$$
Also,
$$
\tan \left(180^{\circ}-\theta\right)=-\tan \theta=-\frac{\left(m_{2}-m_{1}\right)}{\left(1+m_{1} m_{2}\right)} \quad \dots \text{(ii)}
$$
Thus, tangent of the angle between given lines $= \pm \frac{\left(m_{2}-m_{1}\right)}{\left(1+m_{1} m_{2}\right)}$ [from (i) and (ii)].
Let $\alpha=\min.\{\theta, (180^{\circ}-\theta)\}$, then $\alpha$ is acute and so $\tan \alpha > 0$.
$$
\therefore \tan \alpha=\left|\frac{m_{2}-m_{1}}{1+m_{1} m_{2}}\right|.
$$

### Example 16:

Find the angle between the lines whose slopes are $\frac{1}{2}$ and 3.

#### Solution:

Let $\theta$ be the angle between the given lines. Let $m_1 = \frac{1}{2}$ and $m_2 = 3$. Then,
$$
\tan \theta=\left|\frac{m_{2}-m_{1}}{1+m_{1} m_{2}}\right|=\left|\frac{\left(3-\frac{1}{2}\right)}{\left(1+3 \cdot \frac{1}{2}\right)}\right|=\left|\frac{(5 / 2)}{(5 / 2)}\right|=|1|=1
$$
$$
\Rightarrow \theta=45^{\circ}.
$$
Hence, the angle between the given lines is $45^{\circ}$.

---

### Example 17:

If $A(-2, 1)$, $B(2, 3)$ and $C(-2, -4)$ be the vertices of a $\triangle ABC$, show that $\tan B=\frac{2}{3}$.

#### Solution:

Clearly, $B$ is the angle between $BA$ and $BC$.
Now, $m_1 = \text{slope of } BA = \frac{3-1}{2+2} = \frac{1}{2}$
and $m_2 = \text{slope of } BC = \frac{-4-3}{-2-2} = \frac{7}{4}$.
$$
\therefore \tan B=\left|\frac{m_{2}-m_{1}}{1+m_{1} m_{2}}\right|=\left|\frac{\frac{7}{4}-\frac{1}{2}}{1+\frac{7}{4} \cdot \frac{1}{2}}\right|=\frac{2}{3}.
$$
Hence, $\tan B=\frac{2}{3}$.

---

