# PYTHAGORAS' THEOREM

We have proved earlier in this chapter that:
> "If a perpendicular is drawn from the vertex of the right angle of a right triangle to the hypotenuse then the triangles on both sides of the perpendicular are similar to the whole triangle and also to each other."

Now, we shall use this theorem to prove the Pythagoras' theorem.

---

## THEOREM 1: Pythagoras' Theorem
In a **right triangle**, the square of the **hypotenuse** is equal to the sum of the squares of the other two sides.
*[CBSE 2001, '02, '03, '04, '04C, '05, '06, '06C, '07, '07C, '09]*

**GIVEN:** A $\triangle ABC$ in which $\angle ABC = 90^{\circ}$.

**TO PROVE:** $AC^{2} = AB^{2} + BC^{2}$.

**CONSTRUCTION:** Draw $BD \perp AC$.

**PROOF:**
In $\triangle ADB$ and $\triangle ABC$, we have
$$
\begin{array}{lll}
& \angle A=\angle A & \text { (common) } \\
& \angle A D B=\angle A B C \quad \text { [each equal to } 90^{\circ} \text { ] } \\
\therefore \quad & \triangle A D B \sim \triangle A B C \quad[\text { by AA-similarity] }] \\
\Rightarrow \quad & \frac{A D}{A B}=\frac{A B}{A C} \\
\Rightarrow \quad & A D \times A C=A B^{2} . \tag{i}
\end{array}
$$
In $\triangle BDC$ and $\triangle ABC$, we have
$$
\begin{array}{lll}
& \angle C=\angle C & \text { (common) } \\
& \angle B D C=\angle A B C \quad \text { [each equal to } 90^{\circ} \text { ] } \\
\therefore \quad & \triangle B D C \sim \triangle A B C \quad[\text { by AA-similarity] }] \\
\Rightarrow \quad & \frac{D C}{B C}=\frac{B C}{A C} \\
\Rightarrow \quad & D C \times A C=B C^{2} . \tag{ii}
\end{array}
$$
From (i) and (ii), we get
$$
\begin{aligned}
& A D \times A C+D C \times A C=A B^{2}+B C^{2} \\
\Rightarrow \quad & (A D+D C) \times A C=A B^{2}+B C^{2} \\
\Rightarrow \quad & A C \times A C=A B^{2}+B C^{2} \Rightarrow A C^{2}=A B^{2}+B C^{2}
\end{aligned}
$$

---

## THEOREM 2: Converse of Pythagoras' Theorem
In a triangle, if the square of one side is equal to the sum of the squares of the other two sides then the angle opposite to the first side is a right angle.
*[CBSE 2001, '03, '05C, '06, '06C, '07, '09, '09C]*

**GIVEN:** A $\triangle ABC$ in which $AC^{2} = AB^{2} + BC^{2}$.

**TO PROVE:** $\angle B = 90^{\circ}$.

**CONSTRUCTION:** Draw a $\triangle DEF$ such that $DE = AB$, $EF = BC$ and $\angle E = 90^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-001.jpg)

**PROOF:**
In $\triangle DEF$, we have $\angle E = 90^{\circ}$.
So, by Pythagoras' theorem, we have
$$
\begin{aligned}
& D F^{2}=D E^{2}+E F^{2} \\
\Rightarrow \quad & D F^{2}=A B^{2}+B C^{2} .
\end{aligned} \quad \text {... (i) }[\because D E=A B \text { and } E F=B C]
$$

---

# SOME IMPORTANT RESULTS BASED UPON PYTHAGORAS' THEOREM

## THEOREM 1
In a $\triangle ABC$, $AD$ is perpendicular to $BC$. Prove that $(AB^{2} + CD^{2}) = (AC^{2} + BD^{2})$.
*[CBSE 2003, '05C, '09]*

**GIVEN:** A $\triangle ABC$ in which $AD \perp BC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-002.jpg)

**TO PROVE:** $(AB^{2} + CD^{2}) = (AC^{2} + BD^{2})$.

**PROOF:**
From right $\triangle ADB$, we have
$$
\begin{align*}
& A B^{2}=A D^{2}+B D^{2} \quad[\text { by Pythagoras' theorem }] \\
\Rightarrow \quad & \left(A B^{2}-B D^{2}\right)=A D^{2} . \tag{i}
\end{align*}
$$
From right $\triangle ADC$, we have
$$
\begin{align*}
& A C^{2}=A D^{2}+C D^{2} \\
\Rightarrow \quad & \left(A C^{2}-C D^{2}\right)=A D^{2} \tag{ii}
\end{align*}
$$
From (i) and (ii), we get $(AB^{2} - BD^{2}) = (AC^{2} - CD^{2})$.
Hence, $(AB^{2} + CD^{2}) = (AC^{2} + BD^{2})$.

---

## THEOREM 2
Given a $\triangle ABC$ in which $\angle A=90^{\circ}$ and $AD \perp BC$. Prove that $AD^{2} = BD \cdot CD$.
*[CBSE 2004C, '06, '09]*

**GIVEN:** A $\triangle ABC$ in which $\angle A=90^{\circ}$ and $AD \perp BC$.

**TO PROVE:** $AD^{2} = BD \cdot CD$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-003.jpg)

**PROOF:**
In $\triangle BAC, \angle A = 90^{\circ}$.
$$
\therefore \quad B C^{2}=A B^{2}+A C^{2} \tag{i} \quad \text{[by Pythagoras' theorem].}
$$
In $\triangle ADB, \angle ADB = 90^{\circ}$.
$$
\therefore \quad A B^{2}=A D^{2}+B D^{2} . \tag{ii} \quad \text{[by Pythagoras' theorem]}
$$
In $\triangle ADC, \angle ADC = 90^{\circ}$.
$$
\therefore \quad A C^{2}=A D^{2}+C D^{2} . \tag{iii} \quad \text{[by Pythagoras' theorem]}
$$
From (ii) and (iii), we get
$$
\begin{aligned}
& \left(A B^{2}+A C^{2}\right)=2 A D^{2}+B D^{2}+C D^{2} \\
\Rightarrow \quad & B C^{2}=2 A D^{2}+B D^{2}+C D^{2} \quad[\text { using (i) }] \\
\Rightarrow \quad & (B D+C D)^{2}=2 A D^{2}+B D^{2}+C D^{2} \\
\Rightarrow \quad & B D^{2}+C D^{2}+2 B D \cdot C D=2 A D^{2}+B D^{2}+C D^{2} \\
\Rightarrow \quad & 2 A D^{2}=2 B D \cdot C D \Rightarrow A D^{2}=B D \cdot C D
\end{aligned}
$$
Hence, $AD^{2} = BD \cdot CD$.

---

## THEOREM 3
In $\triangle ABC$, $AD \perp BC$ such that $AD^{2} = BD \cdot CD$. Prove that $\triangle ABC$ is right-angled at $A$.
*[CBSE 2006]*

**GIVEN:** A $\triangle ABC$ in which $AD \perp BC$ and $AD^{2} = BD \cdot CD$.

**TO PROVE:** $\angle A = 90^{\circ}$.

**PROOF:**
In right $\triangle ADB$, $\angle ADB = 90^{\circ}$.
$$
\therefore \quad A B^{2}=A D^{2}+B D^{2} \tag{i} \quad \text{[by Pythagoras' theorem]}
$$
In right $\triangle ADC$, $\angle ADC = 90^{\circ}$.
$$
\therefore \quad A C^{2}=A D^{2}+C D^{2} . \tag{ii} \quad \text{[by Pythagoras' theorem]}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-004.jpg)

Adding (i) and (ii), we get
$$
\begin{aligned}
\left(A B^{2}+A C^{2}\right) & =B D^{2}+C D^{2}+2 A D^{2} \\
& =B D^{2}+C D^{2}+2 B D \cdot C D \quad\left[\because A D^{2}=B D \cdot C D\right] \\
& =(B D+C D)^{2}=B C^{2}
\end{aligned}
$$
Thus, $(AB^{2} + AC^{2}) = BC^{2}$.
Hence, $\triangle ABC$ is right-angled at $A$.

---

## THEOREM 4
In a $\triangle ABC$, $\angle ABC < 90^{\circ}$ (i.e., $\angle B$ is acute) and $AD \perp BC$. Prove that $AC^{2} = AB^{2} + BC^{2} - 2BC \cdot BD$.

**GIVEN:** A $\triangle ABC$ in which $\angle ABC < 90^{\circ}$ and $AD \perp BC$.

**TO PROVE:** $AC^{2} = AB^{2} + BC^{2} - 2BC \cdot BD$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-005.jpg)

**PROOF:**
In $\triangle ADB, \angle ADB = 90^{\circ}$.
$$
\therefore \quad A B^{2}=A D^{2}+B D^{2} . \quad \ldots \text { (i) } \quad \text { [by Pythagoras' theorem] }
$$
In $\triangle ADC, \angle ADC = 90^{\circ}$.
$$
\begin{aligned}
\therefore \quad A C^{2} & =A D^{2}+C D^{2} \\
& =A D^{2}+(B C-B D)^{2} \\
& =A D^{2}+B C^{2}+B D^{2}-2 B C \cdot B D \\
& =\left(A D^{2}+B D^{2}\right)+B C^{2}-2 B C \cdot B D \\
& =A B^{2}+B C^{2}-2 B C \cdot B D \quad[\text { using (i) }] .
\end{aligned}
$$
Hence, $AC^{2} = AB^{2} + BC^{2} - 2BC \cdot BD$.

> **Note:** $BD$ is known as the projection of $AB$ on $BC$. So, this theorem is stated as:
> "In an acute-angled triangle, the square of the side opposite to an acute angle is equal to the sum of the squares of the other two sides minus twice the product of one side and the projection of the other on the first."

---

## THEOREM 5
In a $\triangle ABC$, $\angle ABC > 90^{\circ}$ (i.e., $\angle B$ is obtuse) and $AD \perp (CB$ produced). Prove that $AC^{2} = AB^{2} + BC^{2} + 2BC \cdot BD$.

**GIVEN:** A $\triangle ABC$ in which $\angle ABC > 90^{\circ}$ and $AD \perp (CB$ produced).

**TO PROVE:** $AC^{2} = AB^{2} + BC^{2} + 2BC \cdot BD$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-006.jpg)

**PROOF:**
In $\triangle ADB, \angle ADB = 90^{\circ}$.
$$
\therefore \quad A B^{2}=A D^{2}+B D^{2} . \quad \ldots \text { (i) } \quad \text { [by Pythagoras' theorem] }
$$
In $\triangle ADC, \angle ADC = 90^{\circ}$.
$$
\begin{aligned}
\therefore \quad A C^{2} & =A D^{2}+C D^{2} \\
& =A D^{2}+(B C+B D)^{2} \\
& =A D^{2}+B C^{2}+B D^{2}+2 B C \cdot B D \\
& =\left(A D^{2}+B D^{2}\right)+B C^{2}+2 B C \cdot B D \\
& =A B^{2}+B C^{2}+2 B C \cdot B D \quad[\text { using (i) }] .
\end{aligned}
$$
> **Note:** $BD$ is the projection of $AB$ on $BC$. So, this theorem is stated as:
> "In an obtuse-angled triangle, the square of the side opposite to the obtuse angle is equal to the sum of the squares of the other two sides plus twice the product of one side and the projection of the other on the first."

---

## THEOREM 6
In $\triangle ABC$, if $AD$ is the median, then prove that $(AB^{2} + AC^{2}) = 2(AD^{2} + BD^{2})$.

**GIVEN:** A $\triangle ABC$ in which $AD$ is the median.

**TO PROVE:** $(AB^{2} + AC^{2}) = 2(AD^{2} + BD^{2})$.

**CONSTRUCTION:** Draw $AL \perp BC$.

**PROOF:**
In $\triangle ALD, \angle ALD = 90^{\circ}$.
$\therefore \angle ADL < 90^{\circ}$ and therefore, $\angle ADB > 90^{\circ}$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-007.jpg)

Thus, in $\triangle ADB$, $\angle ADB > 90^{\circ}$ and $AL \perp (BD$ produced).
$$
\therefore \quad A B^{2}=A D^{2}+B D^{2}+2 B D \cdot D L . \quad \ldots \text { (i) }
$$
In $\triangle ADC$, $\angle ADC < 90^{\circ}$ and $AL \perp DC$.
$$
\begin{aligned}
\therefore \quad A C^{2}&=A D^{2}+C D^{2}-2 C D \cdot D L \\
\Rightarrow \quad A C^{2}&=A D^{2}+B D^{2}-2 B D \cdot D L . \quad \ldots \text { (ii) }[\because C D=B D]
\end{aligned}
$$
Adding (i) and (ii), we get $(AB^{2} + AC^{2}) = 2(AD^{2} + BD^{2})$.

> **Note:** This theorem can be stated as:
> "In any triangle, the sum of the squares of any two sides is equal to twice the square of half of the third side together with twice the square of the median which bisects the third side."

---

# SOLVED EXAMPLES

### Example 1
Sides of some triangles are given below. Determine which of them are right triangles.
(i) 8 cm, 15 cm, 17 cm
(ii) 9 cm, 11 cm, 6 cm
(iii) $(2a-1)$ cm, $2\sqrt{2a}$ cm and $(2a+1)$ cm

#### Solution:
For the given triangle to be right-angled, the sum of the squares of the two smaller sides must be equal to the square of the largest side.

(i) Let $a=8$ cm, $b=15$ cm and $c=17$ cm. Then,
$$
(a^{2} + b^{2}) = (8^{2} + 15^{2}) \text{ cm}^{2} = (64+225) \text{ cm}^{2} = 289 \text{ cm}^{2}
$$
and $c^{2} = (17)^{2} \text{ cm}^{2} = 289 \text{ cm}^{2}$.
$\therefore (a^{2} + b^{2}) = c^{2}$.
Hence, the given triangle is **right-angled**.

(ii) Let $a=9$ cm, $b=6$ cm and $c=11$ cm. Then,
$$
(a^{2} + b^{2}) = (9^{2} + 6^{2}) \text{ cm}^{2} = (81+36) \text{ cm}^{2} = 117 \text{ cm}^{2}
$$
and $c^{2}=(11)^{2} \text{ cm}^{2} = 121 \text{ cm}^{2}$.
$\therefore (a^{2} + b^{2}) \neq c^{2}$.
Hence, the given triangle is **not right-angled**.

(iii) Let $p=(2a-1)$ cm, $q=2\sqrt{2a}$ cm and $r=(2a+1)$ cm. Then,
$$
\begin{aligned}
(p^{2} + q^{2}) & = (2a-1)^{2} \text{ cm}^{2} + (2\sqrt{2a})^{2} \text{ cm}^{2} \\
& = \{(4a^{2} + 1 - 4a) + 8a\} \text{ cm}^{2} = (4a^{2} + 4a + 1) \text{ cm}^{2} \\
& = (2a+1)^{2} \text{ cm}^{2} = r^{2} .
\end{aligned}
$$
$\therefore (p^{2} + q^{2}) = r^{2}$.
Hence, the given triangle is **right-angled**.

---

### Example 2
A man goes 15 m due west and then 8 m due north. How far is he from the starting point?

#### Solution:
Starting from $A$, let the man go from $A$ to $B$ and then from $B$ to $C$, as shown in the figure. Then, $AB = 15$ m, $BC = 8$ m and $\angle ABC = 90^{\circ}$.
From right $\triangle ABC$, we have
$$
\begin{aligned}
A C^{2} &= A B^{2}+B C^{2} \\
&= \{(15)^{2}+(8)^{2}\} \mathrm{m}^{2} \\
&= (225+64) \mathrm{m}^{2} \\
&= 289 \mathrm{m}^{2} \\
\therefore \quad A C &= \sqrt{289} \mathrm{~m}=17 \mathrm{~m} .
\end{aligned}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-008.jpg)

Hence, the man is **17 m** away from the starting position.

---

### Example 3
A ladder 25 m long just reaches the top of a building 24 m high from the ground. Find the distance of the foot of the ladder from the building.

#### Solution:
Let $AB$ be the building and $CB$ be the ladder. Then, $AB = 24$ m, $CB = 25$ m and $\angle CAB = 90^{\circ}$.
By Pythagoras' theorem, we have
$$
\begin{aligned}
C B^{2} &= A B^{2}+A C^{2} \\
\Rightarrow \quad A C^{2} &= C B^{2}-A B^{2}=\left[(25)^{2}-(24)^{2}\right] \mathrm{m}^{2} \\
&= (625-576) \mathrm{m}^{2}=49 \mathrm{m}^{2} \\
\Rightarrow \quad A C &= \sqrt{49} \mathrm{~m}=7 \mathrm{~m}
\end{aligned}
$$
Hence, the distance of the foot of the ladder from the building is **7 m**.

---

### Example 4
A ladder 15 m long reaches a window which is 9 m above the ground on one side of a street. Keeping its foot at the same point, the ladder is turned to the other side of the street to reach a window 12 m high. Find the width of the street.

#### Solution:
Let $AB$ be the street and let $C$ be the foot of the ladder. Let $D$ and $E$ be the given windows such that $AD = 9$ m and $BE = 12$ m. Then, $CD$ and $CE$ are the two positions of the ladder.
Clearly, $\angle CAD = 90^{\circ}$, $\angle CBE = 90^{\circ}$ and $CD = CE = 15$ m.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-009.jpg)

From right $\triangle CAD$, we have
$$
C D^{2}=A C^{2}+A D^{2} \quad \text{[by Pythagoras' theorem]}
$$
$$
\begin{aligned}
\Rightarrow A C^{2} & =C D^{2}-A D^{2} \\
& =\left[(15)^{2}-(9)^{2}\right] \mathrm{m}^{2}=(225-81) \mathrm{m}^{2}=144 \mathrm{m}^{2} \\
\Rightarrow A C & =\sqrt{144} \mathrm{~m}=12 \mathrm{~m}
\end{aligned}
$$
From right $\triangle CBE$, we have
$$
C E^{2} =C B^{2}+B E^{2} \quad \text{[by Pythagoras' theorem]}
$$
$$
\begin{aligned}
\Rightarrow C B^{2} & =C E^{2}-B E^{2} \\
& \left.=\left[(15)^{2}-12\right)^{2}\right] \mathrm{m}^{2}=(225-144) \mathrm{m}^{2}=81 \mathrm{m}^{2} \\
\Rightarrow C B & =\sqrt{81} \mathrm{~m}=9 \mathrm{~m}
\end{aligned}
$$
Width of the street $= AC + CB = 12 \text{ m} + 9 \text{ m} = 21 \text{ m}$.

---

### Example 5
Two poles of heights 6 metres and 11 metres stand vertically on a plane ground. If the distance between their feet is 12 metres, find the distance between their tops.
*[CBSE 2002]*

#### Solution:
Let $AB$ and $CD$ be the given vertical poles. Then, $AB = 6$ m, $CD = 11$ m and $AC = 12$ m.
Draw $BE \parallel AC$. Then, $CE = AB = 6$ m, $BE = AC = 12$ m.
$\therefore DE = CD - CE = 11 \text{ m} - 6 \text{ m} = 5 \text{ m}$.
In right $\triangle BED$, we have:
$$
\begin{aligned}
B D^{2} &= B E^{2}+D E^{2} \\
&= \left\{(12)^{2}+(5)^{2}\right\} \mathrm{m}^{2} \\
&= (144+25) \mathrm{m}^{2}=169 \mathrm{m}^{2}
\end{aligned}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-010.jpg)
$$
\Rightarrow B D=\sqrt{169} \mathrm{~m}=13 \mathrm{~m} .
$$
Hence, the distance between the tops of the poles = **13 m**.

---

### Example 6
In a rhombus of side 10 cm, one of the diagonals is 12 cm long. Find the length of the second diagonal.
*[CBSE 2001]*

#### Solution:
Let $ABCD$ be the given rhombus whose diagonals intersect at $O$. Then, $AB = 10$ cm.
Let $AC = 12$ cm and $BD = 2x$ cm.
We know that the diagonals of a rhombus bisect each other at right angles.
$\therefore OA = \frac{1}{2} AC = 6$ cm, $OB = \frac{1}{2} BD = x$ cm, and $\angle AOB = 90^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-011.jpg)

From right $\triangle AOB$, we have
$$
\begin{aligned}
A B^{2} &= O A^{2}+O B^{2} \\
\Rightarrow O B^{2} &= A B^{2}-O A^{2} \\
&= \left\{(10)^{2}-(6)^{2}\right\} \mathrm{cm}^{2}=(100-36) \mathrm{cm}^{2}=64 \mathrm{cm}^{2} \\
\Rightarrow x^{2} &= 64 \Rightarrow x=\sqrt{64}=8 .
\end{aligned}
$$
$\therefore OB = 8$ cm.
$\therefore BD = 2 \times OB = 2 \times 8 \text{ cm} = 16 \text{ cm}$.
Hence, the length of the second diagonal is **16 cm**.

---

### Example 7
$\triangle ABD$ is a right triangle in which $\angle A = 90^{\circ}$ and $AC \perp BD$.
Prove that:
(i) $AB^{2} = BC \cdot BD$
(ii) $AC^{2} = BC \cdot DC$
(iii) $AD^{2} = BD \cdot CD$

#### Solution:
We know that:
> If a perpendicular is drawn from the vertex of the right angle of a right triangle to the hypotenuse then the triangles on both sides of the perpendicular are similar to the whole triangle and also to each other.
$$
\begin{aligned}
\therefore \quad & \triangle A B C \sim \triangle D B A \\
& \triangle A B C \sim \triangle D A C \\
& \triangle D B A \sim \triangle D A C .
\end{aligned}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-012.jpg)

(i) $\triangle ABC \sim \triangle DBA$
$$
\Rightarrow \frac{A B}{D B}=\frac{B C}{B A} \Rightarrow \frac{A B}{B D}=\frac{B C}{A B} \Rightarrow A B^{2}=B C \cdot B D .
$$
(ii) $\triangle ABC \sim \triangle DAC$
$$
\Rightarrow \frac{A C}{D C}=\frac{B C}{A C} \Rightarrow A C^{2}=B C \cdot D C
$$
(iii) $\triangle DBA \sim \triangle DAC$
$$
\Rightarrow \frac{A D}{C D}=\frac{B D}{A D} \Rightarrow A D^{2}=B D \cdot C D .
$$

---

### Example 8
$BL$ and $CM$ are medians of a $\triangle ABC$, right-angled at $A$. Prove that $4(BL^{2} + CM^{2}) = 5BC^{2}$.
*[CBSE 2006C, '10]*

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $BL$ and $CM$ are medians and $\angle A = 90^{\circ}$.

**TO PROVE:** $4(BL^{2} + CM^{2}) = 5BC^{2}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-013.jpg)

**PROOF:**
In $\triangle BAC, \angle A = 90^{\circ}$.
$$
\therefore B C^{2}=A B^{2}+A C^{2} . \quad \text{(i) [by Pythagoras' theorem]}
$$
In $\triangle BAL, \angle A = 90^{\circ}$.
$$
\therefore B L^{2}=A L^{2}+A B^{2} \quad \text{[by Pythagoras' theorem]}
$$
$$
\Rightarrow B L^{2}=\left(\frac{1}{2} A C\right)^{2}+A B^{2} \Rightarrow B L^{2}=\frac{1}{4} A C^{2}+A B^{2}
$$
$$
\Rightarrow 4 B L^{2}=A C^{2}+4 A B^{2} . \quad \text{(ii)}
$$
In $\triangle CAM, \angle A = 90^{\circ}$.
$$
\therefore C M^{2}=A M^{2}+A C^{2} \quad \text{[by Pythagoras' theorem]}
$$
$$
\Rightarrow C M^{2}=\left(\frac{1}{2} A B\right)^{2}+A C^{2} \Rightarrow C M^{2}=\frac{1}{4} A B^{2}+A C^{2}
$$
$$
\Rightarrow 4 C M^{2}=A B^{2}+4 A C^{2} . \quad \text{(iii)}
$$
On adding (ii) and (iii), we get $4(BL^{2} + CM^{2}) = 5(AB^{2} + AC^{2})$.
Hence, $4(BL^{2} + CM^{2}) = 5BC^{2}$ [using (i)].

---

### Example 9
In the given figure, the perpendicular from $A$ on side $BC$ of a $\triangle ABC$, intersects $BC$ at $D$ such that $DB = 3CD$. Prove that $2AB^{2} = 2AC^{2} + BC^{2}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-014.jpg)

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AD \perp BC$ and $BD = 3CD$.

**TO PROVE:** $2AB^{2} = 2AC^{2} + BC^{2}$.

**PROOF:**
We have $BD = 3CD$.
$$
\therefore B C=B D+C D=3 C D+C D=4 C D \tag{i}
$$
$$
\Rightarrow C D=\frac{1}{4} B C .
$$
In $\triangle ADB, \angle ADB = 90^{\circ}$.
$$
\therefore A B^{2}=A D^{2}+B D^{2} . \quad \text{(ii) [by Pythagoras' theorem]}
$$
In $\triangle ADC, \angle ADC = 90^{\circ}$.
$$
\therefore A C^{2}=A D^{2}+C D^{2} . \quad \text{(iii) [by Pythagoras' theorem]}
$$
On subtracting (iii) from (ii), we get
$$
\begin{aligned}
A B^{2}-A C^{2} & =B D^{2}-C D^{2} \\
& =\left[(3 C D)^{2}-\left(C D^{2}\right)\right]=8 C D^{2} \quad[\because B D=3 C D] \\
& =8 \times \frac{1}{16} B C^{2}=\frac{1}{2} B C^{2} \quad[\text { using (i) }] .
\end{aligned}
$$
$\therefore 2AB^{2} - 2AC^{2} = BC^{2}$.
Hence, $2AB^{2} = 2AC^{2} + BC^{2}$.

---

### Example 10
In $\triangle ABC, \angle B = 90^{\circ}$ and $D$ is the midpoint of $BC$. Prove that $AC^{2} = AD^{2} + 3CD^{2}$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $\angle B = 90^{\circ}$ and $D$ is the midpoint of $BC$.

**TO PROVE:** $AC^{2} = AD^{2} + 3CD^{2}$.

**CONSTRUCTION:** Join $AD$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-015.jpg)

**PROOF:**
In $\triangle ABC, \angle B = 90^{\circ}$.
$$
\therefore A C^{2}=A B^{2}+B C^{2} . \quad \text{(i) [by Pythagoras' theorem]}
$$
In $\triangle ABD, \angle B = 90^{\circ}$.
$$
\therefore A D^{2}=A B^{2}+B D^{2} \quad \text{(ii) [by Pythagoras' theorem]}
$$
$$
\Rightarrow A B^{2}=A D^{2}-B D^{2} .
$$
$$
\begin{aligned}
\therefore \quad A C^{2}&=\left(A D^{2}-B D^{2}\right)+B C^{2} \quad \text{[using (i)]} \\
\Rightarrow A C^{2}&=A D^{2}-C D^{2}+(2 C D)^{2} \quad[\because B D=C D \text { and } B C=2 C D] \\
\Rightarrow A C^{2}&=A D^{2}+3 C D^{2} .
\end{aligned}
$$
Hence, $AC^{2} = AD^{2} + 3CD^{2}$.

---

### Example 11
$\triangle ABC$ is right-angled at $B$ and $D$ is the midpoint of $BC$. Prove that $AC^{2} = (4AD^{2} - 3AB^{2})$.
*[CBSE 2008C, '10]*

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $\angle B = 90^{\circ}$ and $D$ is the midpoint of $BC$.

**TO PROVE:** $AC^{2} = (4AD^{2} - 3AB^{2})$.

**PROOF:**
In $\triangle ABC, \angle B = 90^{\circ}$.
$$
\begin{aligned}
\therefore \quad A C^{2} &= A B^{2}+B C^{2} \quad \text{[by Pythagoras' theorem]} \\
&= A B^{2}+(2 B D)^{2} \quad[\because B C=2 B D] \\
&= A B^{2}+4 B D^{2} \\
&= A B^{2}+4\left(A D^{2}-A B^{2}\right) \quad\left[\because A B^{2}+B D^{2}=A D^{2}\right] \\
&= \left(4 A D^{2}-3 A B^{2}\right) .
\end{aligned}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-016.jpg)
Hence, $AC^{2} = (4AD^{2} - 3AB^{2})$.

---

### Example 12
In an isosceles $\triangle ABC, AB = AC$ and $BD \perp AC$. Prove that $(BD^{2} - CD^{2}) = 2CD \cdot AD$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AB = AC$ and $BD \perp AC$.

**TO PROVE:** $(BD^{2} - CD^{2}) = 2CD \cdot AD$.

**PROOF:**
From right $\triangle ADB$, we have
$$
A B^{2}=A D^{2}+B D^{2} \quad \text{[by Pythagoras' theorem]}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-017.jpg)
$$
\begin{aligned}
\Rightarrow A C^{2} &= A D^{2}+B D^{2} \quad[\because A B=A C] \\
\Rightarrow (C D+A D)^{2} &= A D^{2}+B D^{2} \quad[\because A C=C D+A D] \\
\Rightarrow C D^{2}+A D^{2}+2 C D \cdot A D &= A D^{2}+B D^{2} \\
\Rightarrow \left(B D^{2}-C D^{2}\right) &= 2 C D \cdot A D .
\end{aligned}
$$
Hence, $(BD^{2} - CD^{2}) = 2CD \cdot AD$.

---

### Example 13
$\triangle ABC$ is an isosceles triangle, right-angled at $C$. Prove that $AB^{2} = 2AC^{2}$.

#### Solution:
$\triangle ABC$ is an isosceles triangle, right-angled at $C$.
$$
\Rightarrow B C=A C \tag{i}
$$
Now, by Pythagoras' theorem,
$$
A B^{2}=B C^{2}+A C^{2}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-018.jpg)
$$
\begin{aligned}
\Rightarrow A B^{2} &= A C^{2}+A C^{2} \quad \text{[using (i)]} \\
\Rightarrow A B^{2} &= 2 A C^{2} .
\end{aligned}
$$

---

### Example 14
$\triangle ABC$ is an isosceles triangle with $AC = BC$. If $AB^{2} = 2AC^{2}$, prove that $\triangle ABC$ is a right triangle.
*[CBSE 2000C]*

#### Solution:
In $\triangle ABC$, we have $AC = BC$ (given).
Now, $AB^{2} = 2AC^{2}$ (given).
$$
\begin{aligned}
\Rightarrow A B^{2} &= A C^{2}+A C^{2} \\
\Rightarrow A B^{2} &= A C^{2}+B C^{2} \quad \text{[using (i)]} \\
\Rightarrow \angle C &= 90^{\circ} \quad \text{[by converse of Pythagoras' theorem]}
\end{aligned}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-019.jpg)
Hence, $\triangle ABC$ is a right triangle.

---

### Example 15
$\triangle ABC$ is a right triangle in which $\angle C = 90^{\circ}$ and $CD \perp AB$. If $BC = a, CA = b, AB = c$ and $CD = p$ then prove that:
(i) $cp = ab$
(ii) $\frac{1}{p^{2}} = \frac{1}{a^{2}} + \frac{1}{b^{2}}$.
*[CBSE 1997C, '98, '99, '02]*

#### Solution:
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-020.jpg)
(i) We have
$$
\text{ar}(\triangle ABC) = \frac{1}{2} \times AB \times CD = \frac{1}{2} cp \quad \text{[taking AB as base]}
$$
and
$$
\text{ar}(\triangle ABC) = \frac{1}{2} \times BC \times AC = \frac{1}{2} ab \quad \text{[taking BC as base].}
$$
$$
\therefore \frac{1}{2} c p=\frac{1}{2} a b \Rightarrow c p=a b .
$$
Hence, $cp = ab$.

(ii) $cp = ab \Rightarrow \frac{1}{p} = \frac{c}{ab}$.
$$
\begin{aligned}
\therefore \quad \frac{1}{p^{2}} &= \frac{c^{2}}{a^{2} b^{2}}=\frac{b^{2}+a^{2}}{a^{2} b^{2}} \quad\left[\because A B^{2}=A C^{2}+B C^{2}\right] \\
&= \left(\frac{b^{2}}{a^{2} b^{2}}+\frac{a^{2}}{a^{2} b^{2}}\right)=\left(\frac{1}{a^{2}}+\frac{1}{b^{2}}\right) .
\end{aligned}
$$
Hence, $\frac{1}{p^{2}}=\frac{1}{a^{2}}+\frac{1}{b^{2}}$.

---

### Example 16
In an equilateral triangle, prove that three times the square of one side is equal to four times the square of one of its altitudes.
*[CBSE 2002, '07C]*

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AB = BC = CA$ and $AD \perp BC$.

**TO PROVE:** $3AB^{2} = 4AD^{2}$.

**PROOF:**
In $\triangle ADB$ and $\triangle ADC$, we have
$AB = AC$ (given), $\angle B = \angle C = 60^{\circ}$ and $\angle ADB = \angle ADC = 90^{\circ}$.
$\therefore \triangle ADB \cong \triangle ADC$ [AAS-congruence]
$\therefore BD = DC = \frac{1}{2} BC$.

From right $\triangle ADB$, we have
$$
\begin{aligned}
A B^{2} &= A D^{2}+B D^{2} \quad[\text { by Pythagoras' theorem }] \\
&= A D^{2}+\left(\frac{1}{2} B C\right)^{2}=A D^{2}+\frac{1}{4} B C^{2}
\end{aligned}
$$
$$
\begin{aligned}
\Rightarrow 4 A B^{2} &= 4 A D^{2}+B C^{2} \\
\Rightarrow 3 A B^{2} &= 4 A D^{2} \quad[\because B C=A B] .
\end{aligned}
$$
Hence, $3AB^{2} = 4AD^{2}$.

---

### Example 17
In an equilateral triangle with side $a$, prove that
(i) altitude $= \frac{\sqrt{3}}{2}a$
(ii) area $= \frac{\sqrt{3}}{4}a^{2}$.
*[CBSE 1997, '99, '01C, '02C]*

#### Solution:
Let $\triangle ABC$ be an equilateral triangle with side $a$.
Then, $AB = AC = BC = a$.
Draw $AD \perp BC$.

In $\triangle ADB$ and $\triangle ADC$, we have
$AB = AC$ (given), $\angle B = \angle C = 60^{\circ}$ and $\angle ADB = \angle ADC = 90^{\circ}$.
$\therefore \triangle ADB \cong \triangle ADC$.
$\therefore BD = DC = \frac{a}{2}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-021.jpg)

(i) From right $\triangle ADB$, we have
$$
\begin{aligned}
A B^{2} &= A D^{2}+B D^{2} \quad \text{[by Pythagoras' theorem]} \\
\Rightarrow A D &= \sqrt{A B^{2}-B D^{2}} \\
&= \sqrt{a^{2}-\left(\frac{a}{2}\right)^{2}}=\sqrt{a^{2}-\frac{a^{2}}{4}}=\sqrt{\frac{3 a^{2}}{4}}=\frac{\sqrt{3}}{2} a
\end{aligned}
$$
Hence, altitude $= \frac{\sqrt{3}}{2}a$.

(ii) Area of $\triangle ABC = \frac{1}{2} \times \text{base} \times \text{altitude} = (\frac{1}{2} \times BC \times AD)$
$$
\begin{aligned}
&= \left(\frac{1}{2} \times a \times \frac{\sqrt{3}}{2} a\right) \quad \text{[using (i)]} \\
&= \left(\frac{\sqrt{3}}{4} a^{2}\right) \text{ sq units.}
\end{aligned}
$$
Hence, area$(\triangle ABC) = (\frac{\sqrt{3}}{4} a^{2})$ sq units.

---

### Example 18
$O$ is a point in the interior of $\triangle ABC, OD \perp BC, OE \perp AC$ and $OF \perp AB$, as shown in the figure.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-022.jpg)

Prove that:
(i) $OA^{2} + OB^{2} + OC^{2} - OD^{2} - OE^{2} - OF^{2} = AF^{2} + BD^{2} + CE^{2}$
(ii) $AF^{2} + BD^{2} + CE^{2} = AE^{2} + BF^{2} + CD^{2}$

#### Solution:
(i) Using Pythagoras' theorem for each of the right triangles namely $\triangle OFA, \triangle ODB$ and $\triangle OEC$, we get
$$
\begin{align*}
& O A^{2}=O F^{2}+A F^{2}  \tag{i}\\
& O B^{2}=O D^{2}+B D^{2}  \tag{ii}\\
& O C^{2}=O E^{2}+C E^{2} \tag{iii}
\end{align*}
$$
Adding (i), (ii) and (iii), we get
$$
\begin{gathered}
O A^{2}+O B^{2}+O C^{2} = O D^{2}+O E^{2}+O F^{2}+A F^{2}+B D^{2}+C E^{2} . \\
\text{Hence, } O A^{2}+O B^{2}+O C^{2}-O D^{2}-O E^{2}-O F^{2} =A F^{2}+B D^{2}+C E^{2} .
\end{gathered}
$$
(ii) Using Pythagoras' theorem for each of the right triangles, namely $\triangle ODB$ and $\triangle ODC$, we get
$$
O B^{2}=O D^{2}+B D^{2} \text{ and } O C^{2}=O D^{2}+C D^{2} .
$$
$$
\therefore O B^{2}-O C^{2}=B D^{2}-C D^{2} \tag{iv}
$$
Similarly, we have
$$
\begin{align*}
O C^{2}-O A^{2} &= C E^{2}-A E^{2}  \tag{v}\\
\text { and } O A^{2}-O B^{2} &= A F^{2}-B F^{2} . \tag{vi}
\end{align*}
$$
Adding the corresponding sides of (iv), (v) and (vi), we get
$$
A F^{2}+B D^{2}+C E^{2}-A E^{2}-B F^{2}-C D^{2}=0 .
$$
Hence, $AF^{2} + BD^{2} + CE^{2} = AE^{2} + BF^{2} + CD^{2}$.

---

### Example 19
$O$ is any point inside a rectangle $ABCD$. Prove that $OB^{2} + OD^{2} = OA^{2} + OC^{2}$.
*[CBSE 2006C]*
**Deduction:** In the given figure, $O$ is a point inside a rectangle $ABCD$ such that $OB = 6$ cm, $OD = 8$ cm and $OA = 5$ cm, find the length of $OC$.
*[CBSE 2009C]*

#### Solution:
**GIVEN:** $O$ is a point inside a rectangle $ABCD$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-023.jpg)

**TO PROVE:** $OB^{2} + OD^{2} = OA^{2} + OC^{2}$.

**CONSTRUCTION:** Through $O$, draw $POQ \parallel BC$ so that $P$ lies on $AB$ and $Q$ lies on $DC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-024.jpg)

**PROOF:**
We have $POQ \parallel BC \Rightarrow PQ \perp AB$ and $QP \perp DC$.
$\Rightarrow \angle BPQ = 90^{\circ}$ and $\angle CQP = 90^{\circ}$.
$\therefore BPQC$ and $APQD$ are both rectangles.
$\therefore BP = CQ$ [opposite sides of a rectangle]
$DQ = AP$ [opposite sides of a rectangle]

From right $\triangle OPB$, we have $OB^{2} = OP^{2} + BP^{2}$.
From right $\triangle OQD$, we have $OD^{2} = OQ^{2} + DQ^{2}$.
From right $\triangle OPA$, we have $OA^{2} = OP^{2} + AP^{2}$.
From right $\triangle OQC$, we have $OC^{2} = OQ^{2} + CQ^{2}$.
$$
\begin{aligned}
\therefore \quad O B^{2}+O D^{2} &= O P^{2}+O Q^{2}+B P^{2}+D Q^{2} \\
&= O P^{2}+O Q^{2}+C Q^{2}+A P^{2} \quad [\because B P=C Q \text { and } D Q=A P] \\
&= \left(O P^{2}+A P^{2}\right)+\left(O Q^{2}+C Q^{2}\right) \\
&= O A^{2}+O C^{2} .
\end{aligned}
$$
Hence, $OB^{2} + OD^{2} = OA^{2} + OC^{2}$.

**Deduction:** Let $OC = x$ cm. Then,
$$
\begin{aligned}
& O B^{2}+O D^{2}=O A^{2}+O C^{2} \\
\Rightarrow & 6^{2}+8^{2}=5^{2}+x^{2} \\
\Rightarrow & x^{2}=36+64-25=75 \\
\Rightarrow & x=\sqrt{75}=5 \sqrt{3}=(5 \times 1.732)=8.66 \Rightarrow O C=8.66 \mathrm{~cm}
\end{aligned}
$$

---

### Example 20
Prove that the sum of the squares on the sides of a rhombus is equal to the sum of the squares on its diagonals.
*[CBSE 2005, '06, '08C]*

#### Solution:
**GIVEN:** A rhombus $ABCD$ whose diagonals $AC$ and $BD$ intersect at $O$.

**TO PROVE:** $(AB^{2} + BC^{2} + CD^{2} + DA^{2}) = (AC^{2} + BD^{2})$.

**PROOF:**
We know that the diagonals of a rhombus bisect each other at right angles.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-025.jpg)
$$
\begin{aligned}
\therefore \quad & \angle A O B=\angle B O C=\angle C O D=\angle D O A=90^{\circ}, \\
& O A=\frac{1}{2} A C \text { and } O B=\frac{1}{2} B D .
\end{aligned}
$$
From right $\triangle AOB$, we have
$$
\begin{align*}
A B^{2} & =O A^{2}+O B^{2} \text { [by Pythagoras' theorem] } \\
& =\left(\frac{1}{2} A C\right)^{2}+\left(\frac{1}{2} B D\right)^{2}=\frac{1}{4}\left(A C^{2}+B D^{2}\right) \\
\Rightarrow 4 A B^{2} & =\left(A C^{2}+B D^{2}\right) \tag{i}
\end{align*}
$$
Similarly, we have:
$$
\begin{align*}
& 4 B C^{2}=\left(A C^{2}+B D^{2}\right)  \tag{ii}\\
& 4 C D^{2}=\left(A C^{2}+B D^{2}\right)  \tag{iii}\\
& 4 D A^{2}=\left(A C^{2}+B D^{2}\right) \tag{iv}
\end{align*}
$$
On adding (i), (ii), (iii) and (iv), we get
$$
\left(A B^{2}+B C^{2}+C D^{2}+D A^{2}\right)=\left(A C^{2}+B D^{2}\right) .
$$
> **Remark:** In a rhombus $ABCD$, we have $AB = BC = CD = DA$, so the above result may be given as $4AB^{2} = (AC^{2} + BD^{2})$.

---
### Example 21
$P$ and $Q$ are points on the sides $CA$ and $CB$ of a $\triangle ABC$, right-angled at $C$. Prove that $(AQ^{2} + BP^{2}) = (AB^{2} + PQ^{2})$.
*[CBSE 2007, '08]*

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $\angle C = 90^{\circ}$. $P$ and $Q$ are points on $CA$ and $CB$ respectively.

**TO PROVE:** $(AQ^{2} + BP^{2}) = (AB^{2} + PQ^{2})$.

**PROOF:**
From right $\triangle ACQ$, we have
$$
A Q^{2}=\left(A C^{2}+C Q^{2}\right) . \quad \text{(i) [by Pythagoras' theorem]}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-026.jpg)
From right $\triangle BCP$, we have
$$
B P^{2}=\left(B C^{2}+C P^{2}\right) . \quad \text{(ii) [by Pythagoras' theorem]}
$$
From right $\triangle ACB$, we have
$$
A B^{2}=A C^{2}+B C^{2} . \quad \text{(iii) [by Pythagoras' theorem]}
$$
From right $\triangle PCQ$, we have
$$
P Q^{2}=\left(C Q^{2}+C P^{2}\right) . \quad \text{(iv) [by Pythagoras' theorem]}
$$
From (i) and (ii), we get
$$
\begin{aligned}
\left(A Q^{2}+B P^{2}\right) & =\left(A C^{2}+B C^{2}\right)+\left(C Q^{2}+C P^{2}\right) \\
& =\left(A B^{2}+P Q^{2}\right) \text { [using (iii) and (iv)]. }
\end{aligned}
$$
Hence, $(AQ^{2} + BP^{2}) = (AB^{2} + PQ^{2})$.

---

### Example 22
In the figure given below, $\triangle PQR$ is right-angled at $Q$ and the points $S$ and $T$ trisect the side $QR$. Prove that $8PT^{2} = 3PR^{2} + 5PS^{2}$.
*[CBSE 2006C]*

#### Solution:
**GIVEN:** A $\triangle PQR$ in which $\angle PQR = 90^{\circ}$, $S$ and $T$ are the points of trisection of $QR$.

**TO PROVE:** $8PT^{2} = 3PR^{2} + 5PS^{2}$.

**PROOF:**
Let $QS = ST = TR = x$. Then, $QS = x$, $QT = 2x$ and $QR = 3x$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-027.jpg)
From right triangles $PQS, PQT$ and $PQR$, by Pythagoras' theorem, we have
$$
P S^{2}=P Q^{2}+Q S^{2}, P T^{2}=P Q^{2}+Q T^{2} \text{ and } P R^{2}=P Q^{2}+Q R^{2}
$$
$$
\begin{aligned}
\therefore \quad & 3 P R^{2}+5 P S^{2}-8 P T^{2} \\
& =3\left(P Q^{2}+Q R^{2}\right)+5\left(P Q^{2}+Q S^{2}\right)-8\left(P Q^{2}+Q T^{2}\right) \\
& =3 Q R^{2}+5 Q S^{2}-8 Q T^{2} \\
& =3 \times(3 x)^{2}+5(x)^{2}-8 \times(2 x)^{2} \quad [\because Q R=3 x, Q S=x \text { and } Q T=2 x] \\
& =\left(27 x^{2}+5 x^{2}-32 x^{2}\right)=0
\end{aligned}
$$
Thus, $3PR^{2} + 5PS^{2} - 8PT^{2} = 0$.
Hence, $8PT^{2} = 3PR^{2} + 5PS^{2}$.

---

### Example 23
In an isosceles $\triangle ABC, AB = AC$ and $D$ is a point on $BC$. Prove that $AB^{2} - AD^{2} = BD \cdot CD$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AB = AC$ and $D$ is a point on $BC$.

**TO PROVE:** $(AB^{2} - AD^{2}) = BD \cdot CD$.

**CONSTRUCTION:** Draw $AL \perp BC$.

**PROOF:**
In right $\triangle ALB$ and $ALC$, we have:
hyp. $AB =$ hyp. $AC$ (given)
$AL = AL$ (common)
$\therefore \triangle ALB \cong \triangle ALC$ [by RHS-congruence]
$\therefore BL = CL$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-028.jpg)

From right $\triangle ALB$ and $ALD$, by Pythagoras' theorem, we have:
$$
\begin{align*}
A B^{2}&=A L^{2} +B L^{2}  \tag{i}\\
A D^{2}&=A L^{2} +D L^{2}  \tag{ii}
\end{align*}
$$
$$
\begin{aligned}
\therefore \quad A B^{2}-A D^{2} & =B L^{2}-D L^{2} \\
& =(B L-D L)(B L+D L) \\
& =B D \cdot(C L+D L) \quad[\because B L=C L] \\
& =B D \cdot C D .
\end{aligned}
$$
Hence, $AB^{2} - AD^{2} = BD \cdot CD$.

---

### Example 24
In an equilateral $\triangle ABC, D$ is a point on side $BC$ such that $BD = \frac{1}{3}BC$. Prove that $9AD^{2} = 7AB^{2}$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AB = BC = CA$ and $D$ is a point on $BC$ such that $BD = \frac{1}{3}BC$.

**TO PROVE:** $9AD^{2} = 7AB^{2}$.

**CONSTRUCTION:** Draw $AL \perp BC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-029.jpg)

**PROOF:**
In right triangles $ALB$ and $ALC$, we have
$AB = AC$ (given) and $AL = AL$ (common).
$\therefore \triangle ALB \cong \triangle ALC$ [by RHS axiom]
So, $BL = CL$.
Thus, $BD = \frac{1}{3}BC$ and $BL = \frac{1}{2}BC$.
In $\triangle ALB, \angle ALB = 90^{\circ}$.
$$
\therefore A B^{2}=A L^{2}+B L^{2} . \quad \text{(i) [by Pythagoras' theorem]}
$$
In $\triangle ALD, \angle ALD = 90^{\circ}$.
$$
\begin{aligned}
\therefore A D^{2} &= A L^{2}+D L^{2} \quad \text{[by Pythagoras' theorem]} \\
&= A L^{2}+(B L-B D)^{2} \\
&= A L^{2}+B L^{2}+B D^{2}-2 B L \cdot B D \\
&= \left(A L^{2}+B L^{2}\right)+B D^{2}-2 B L \cdot B D \\
&= A B^{2}+B D^{2}-2 B L \cdot B D \quad \text{[using (i)]} \\
&= B C^{2}+\left(\frac{1}{3} B C\right)^{2}-2\left(\frac{1}{2} B C\right) \cdot \frac{1}{3} B C \quad \left[\because A B=B C, B D=\frac{1}{3} B C \text{ and } B L=\frac{1}{2} B C\right] \\
&= B C^{2}+\frac{1}{9} B C^{2}-\frac{1}{3} B C^{2} \\
&= \frac{7}{9} B C^{2}=\frac{7}{9} A B^{2} \quad[\because B C=A B] .
\end{aligned}
$$
Hence, $9AD^{2} = 7AB^{2}$.

---

### Example 25
In a quadrilateral $ABCD, \angle B = 90^{\circ}$. If $AD^{2} = AB^{2} + BC^{2} + CD^{2}$, prove that $\angle ACD = 90^{\circ}$.

#### Solution:
**GIVEN:** A quadrilateral $ABCD$ in which $\angle B = 90^{\circ}$ and $AD^{2} = AB^{2} + BC^{2} + CD^{2}$.

**TO PROVE:** $\angle ACD = 90^{\circ}$.

**CONSTRUCTION:** Join $AC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-030.jpg)

**PROOF:**
In $\triangle ABC, \angle B = 90^{\circ}$.
$$
\therefore A C^{2}=A B^{2}+B C^{2} . \quad \text{(i) [by Pythagoras' theorem]}
$$
Now, $AD^{2} = AB^{2} + BC^{2} + CD^{2}$ (given)
$$
\Rightarrow A D^{2}=A C^{2}+C D^{2} \quad \text{[using (i)]}.
$$
Thus, in $\triangle ACD$, we have $AD^{2} = AC^{2} + CD^{2}$.
Hence, $\angle ACD = 90^{\circ}$ [by converse of Pythagoras' theorem].

---
### Example 26
Equilateral triangles are drawn on the sides of a right triangle. Prove that the area of the triangle on the hypotenuse is equal to the sum of the areas of the triangles on the other two sides.
*[CBSE 2002]*

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $\angle B=90^{\circ}$. Equilateral triangles $\triangle BCD, \triangle CAE$ and $\triangle ABF$ are drawn on the sides $BC, CA$ and $AB$ respectively.

**TO PROVE:** $\text{ar}(\triangle CAE) = \text{ar}(\triangle BCD) + \text{ar}(\triangle ABF)$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-031.jpg)

**PROOF:**
$\triangle BCD, \triangle CAE$ and $\triangle ABF$ are equiangular and hence similar.
We have
$$
\begin{aligned}
& \frac{\operatorname{ar}(\triangle B C D)}{\operatorname{ar}(\triangle C A E)}+\frac{\operatorname{ar}(\triangle A B F)}{\operatorname{ar}(\triangle C A E)}=\frac{B C^{2}}{C A^{2}}+\frac{A B^{2}}{C A^{2}} \\
\Rightarrow & \frac{\operatorname{ar}(\triangle B C D)+\operatorname{ar}(\triangle A B F)}{\operatorname{ar}(\triangle C A E)}=\frac{B C^{2}+A B^{2}}{C A^{2}}=\frac{C A^{2}}{C A^{2}}=1 \quad \text{[by Pythagoras' theorem]}
\end{aligned}
$$
$$
\Rightarrow \operatorname{ar}(\triangle B C D)+\operatorname{ar}(\triangle A B F)=\operatorname{ar}(\triangle C A E).
$$

---

### Example 27
Given a right-angled $\triangle ABC$. The lengths of the sides containing the right angle are 6 cm and 8 cm. A circle is inscribed in $\triangle ABC$. Find the radius of the circle.

#### Solution:
In $\triangle ABC$, we have $\angle B = 90^{\circ}$, $AB = 6$ cm and $BC = 8$ cm.
A circle is inscribed in $\triangle ABC$. Let $O$ be its centre and $M, N$ and $P$ be the points where it touches the sides $AB, BC$ and $CA$ respectively. Then, $OM \perp AB, ON \perp BC, OP \perp CA$.

Let $r$ cm be the radius of the circle.
Then, $OM = ON = OP = r$ cm.
Now, $AB^{2} + BC^{2} = CA^{2}$ [by Pythagoras' theorem]
$\Rightarrow 6^{2} \text{ cm}^{2} + 8^{2} \text{ cm}^{2} = CA^{2} \Rightarrow CA = 10$ cm.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-032.jpg)
Now, $\text{ar}(\triangle ABC) = \text{ar}(\triangle AOB) + \text{ar}(\triangle BOC) + \text{ar}(\triangle COA)$
$$
\begin{aligned}
\Rightarrow \quad & \frac{1}{2} \times A B \times B C=\left(\frac{1}{2} \times A B \times O M\right)+\left(\frac{1}{2} \times B C \times O N\right) +\left(\frac{1}{2} \times C A \times O P\right) \\
\Rightarrow \quad & \frac{1}{2} \times 6 \times 8=\left(\frac{1}{2} \times 6 \times r\right)+\left(\frac{1}{2} \times 8 \times r\right)+\left(\frac{1}{2} \times 10 \times r\right) \\
\Rightarrow \quad & 24 = 3r + 4r + 5r \\
\Rightarrow \quad & 24 = 12r \\
\Rightarrow \quad & r=2 \Rightarrow \text{radius} = 2 \text{ cm} .
\end{aligned}
$$

---

### Example 28
Prove that the sum of the squares of the diagonals of a parallelogram is equal to the sum of the squares of its sides.

#### Solution:
**GIVEN:** A parallelogram $PQRS$.

**TO PROVE:** $PR^{2} + QS^{2} = PQ^{2} + QR^{2} + RS^{2} + SP^{2}$

**PROOF:**
We have proved earlier that if $AD$ is a median of a $\triangle ABC$, then
$$
A B^{2}+A C^{2}=2\left(A D^{2}+B D^{2}\right) \quad \text{i.e., } A B^{2}+A C^{2}=2 A D^{2}+\frac{1}{2} B C^{2} \tag{i}
$$
Now, let $O$ be the point of intersection of the diagonal $PR$ and $QS$.
The diagonals of a parallelogram bisect each other.
$\therefore O$ is the midpoint of $PR$ as well as $QS$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-033.jpg)
Applying result (i) to $\triangle PQR$ and $\triangle RSP$, we get
$$
P Q^{2}+Q R^{2}=2 O Q^{2}+\frac{1}{2} P R^{2} \tag{ii}
$$
$$
\text{ and } R S^{2}+S P^{2}=2 O S^{2}+\frac{1}{2} P R^{2} \tag{iii}
$$
Adding (ii) and (iii), we get
$$
\begin{aligned}
& P Q^{2}+Q R^{2}+R S^{2}+S P^{2}=2\left(\frac{1}{2} Q S\right)^{2}+2\left(\frac{1}{2} Q S\right)^{2}+P R^{2} \\
\Rightarrow \quad & P Q^{2}+Q R^{2}+R S^{2}+S P^{2}= 2(\frac{1}{4} QS^2) + 2(\frac{1}{4} QS^2) + PR^2 \\
\Rightarrow \quad & P Q^{2}+Q R^{2}+R S^{2}+S P^{2}= \frac{1}{2} QS^2 + \frac{1}{2} QS^2 + PR^2 \\
\Rightarrow \quad & P Q^{2}+Q R^{2}+R S^{2}+S P^{2}=P R^{2}+Q S^{2}
\end{aligned}
$$

---

### Example 29
Given a $\triangle ABC$ in which $\angle B = 90^{\circ}$ and $AB = \sqrt{3} BC$. Prove that $\angle C = 60^{\circ}$.

#### Solution:
Let $D$ be the midpoint of the hypotenuse $AC$. Join $BD$.
We have
$$
\begin{aligned}
A C^{2} &= A B^{2}+B C^{2} \quad \text{[by Pythagoras' theorem]} \\
\Rightarrow A C^{2} &= (\sqrt{3} B C)^{2}+B C^{2} \quad [\because A B=\sqrt{3} B C \text{ (given)]} \\
\Rightarrow A C^{2} &= 3BC^2 + BC^2 = 4 B C^{2} \Rightarrow A C=2 B C \\
\Rightarrow 2 C D &= 2 B C \quad [\because D \text{ is the midpoint of } A C]
\end{aligned}
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-D-BooK-034.jpg)
$$
\Rightarrow C D=B C . \quad \text{(i)}
$$
Also, we know that the midpoint of the hypotenuse of a right triangle is equidistant from the vertices.
$$
\therefore B D=C D \tag{ii}
$$
From (i) and (ii), we get
$$
B C=B D=C D
$$
$\therefore \triangle BCD$ is equilateral and hence $\angle C = 60^{\circ}$.