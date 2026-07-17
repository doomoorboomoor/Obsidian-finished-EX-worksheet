# Triangles

**Congruent Figures:** Two geometric figures which have the same shape and size are known as **congruent figures**.

Congruent figures are alike in every respect.

**Similar Figures:** Geometric figures which have the same shape but different sizes are known as **similar figures**.

Two congruent figures are always similar but two similar figures need not be congruent.

---

## Examples

1.  Any two line segments are similar.
2.  Any two equilateral triangles are similar.
3.  Any two squares are similar.
4.  Any two circles are similar.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-001.jpg)

---

## Similar Polygons

Two polygons having the same number of sides are said to be similar, if:
1.  their corresponding angles are equal, and
2.  the lengths of their corresponding sides are proportional.

If two polygons $ABCDE$ and $PQRST$ are similar, we write, $ABCDE \sim PQRST$, where the symbol '$\sim$' stands for 'is similar to'.

The constant ratio between the corresponding sides of two similar figures is known as the **scale factor**, or the **representative fraction**. Since triangles are also polygons, so the same set of conditions apply for the similarity of triangles.

---

## Equiangular Triangles

Two triangles are said to be **equiangular** if their corresponding angles are equal.

---

## Similar Triangles

Two triangles are said to be similar to each other if:
1.  their corresponding angles are equal, and
2.  their corresponding sides are proportional.

---

## Results on Similar Triangles

### (Basic-Proportionality Theorem) or (Thales' Theorem)

**THEOREM 1** *If a line is drawn parallel to one side of a triangle to intersect the other two sides in distinct points then the other two sides are divided in the same ratio.*
[CBSE 2002C, '04C, '05, '06C, '07, '09, '10]

**GIVEN** A $\triangle ABC$ in which $DE \| BC$ and $DE$ intersects $AB$ and $AC$ at $D$ and $E$ respectively.

**TO PROVE** $\frac{AD}{DB}=\frac{AE}{EC}$.

**CONSTRUCTION** Join $BE$ and $CD$. Draw $EL \perp AB$ and $DM \perp AC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-002.jpg)

**PROOF** We have

$$
\begin{align*}
& \quad ar(\triangle ADE)=\frac{1}{2} \times AD \times EL \quad\left[\because \Delta=\frac{1}{2} \times \text{ base } \times \text{ height }\right] \\
& \text{ and } \quad ar(\triangle DBE)=\frac{1}{2} \times DB \times EL. \\
& \therefore \quad \frac{ar(\triangle ADE)}{ar(\triangle DBE)}=\frac{\frac{1}{2} \times AD \times EL}{\frac{1}{2} \times DB \times EL}=\frac{AD}{DB}. \tag{i}
\end{align*}
$$

Again, $ar(\triangle ADE)=\operatorname{ar}(\triangle AED)=\frac{1}{2} \times AE \times DM$

$$
\begin{align*}
& \text{ and } ar(\triangle ECD)=\frac{1}{2} \times EC \times DM. \\
& \therefore \quad \frac{ar(\triangle ADE)}{ar(\triangle ECD)}=\frac{\frac{1}{2} \times AE \times DM}{\frac{1}{2} \times EC \times DM}=\frac{AE}{EC}. \tag{ii}
\end{align*}
$$

Now, $\triangle DBE$ and $\triangle ECD$ being on the same base $DE$ and between the same parallels $DE$ and $BC$, we have

$$
ar(\triangle DBE)=\operatorname{ar}(\triangle ECD) \tag{iii}
$$

From (i), (ii) and (iii), we have

$$
\frac{AD}{DB}=\frac{AE}{EC}.
$$

**COROLLARY** In a $\triangle ABC$, a line $DE \| BC$ intersects $AB$ in $D$ and $AC$ in $E$, then prove that:

(i) $\frac{AB}{DB}=\frac{AC}{EC}$
(ii) $\frac{AD}{AB}=\frac{AE}{AC}$

**PROOF** (i) From Basic-Proportionality theorem, we have

$$
\begin{aligned}
\frac{AD}{DB}=\frac{AE}{EC} & \Rightarrow \frac{AD}{DB}+1=\frac{AE}{EC}+1 \\
& \Rightarrow \frac{AD+DB}{DB}=\frac{AE+EC}{EC} \Rightarrow \frac{AB}{DB}=\frac{AC}{EC}
\end{aligned}
$$

(ii) From Basic-Proportionality theorem, we have

$$
\begin{aligned}
\frac{AD}{DB}=\frac{AE}{EC} & \Rightarrow \frac{DB}{AD}=\frac{EC}{AE} \\
& \Rightarrow\left(1+\frac{DB}{AD}\right)=\left(1+\frac{EC}{AE}\right) \\
& \Rightarrow \frac{(AD+DB)}{AD}=\frac{(AE+EC)}{AE} \\
& \Rightarrow \frac{AB}{AD}=\frac{AC}{AE} \Rightarrow \frac{AD}{AB}=\frac{AE}{AC}
\end{aligned}
$$

---

## Summary

In $\triangle ABC$, let $DE \| BC$. Then,
(i) $\frac{AD}{DB}=\frac{AE}{EC}$ (B.P.T.)
(ii) $\frac{AB}{DB}=\frac{AC}{EC}$
(iii) $\frac{AD}{AB}=\frac{AE}{AC}$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-003.jpg)

---

### Theorem 2 (Converse of Thales' theorem)

*If a line divides any two sides of a triangle in the same ratio then the line must be parallel to the third side.*

**GIVEN** A $\triangle ABC$ and a line $l$ intersecting $AB$ at $D$ and $AC$ at $E$, such that $\frac{AD}{DB}=\frac{AE}{EC}$.

**TO PROVE** $DE \| BC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-004.jpg)

**PROOF** If possible, let $DE$ not be parallel to $BC$. Then, there must be another line through $D$, which is parallel to $BC$. Let $DF \| BC$.
Then, by Thales' theorem, we have

$$
\begin{align*}
\frac{AD}{DB} & =\frac{AF}{FC} \tag{i}\\
\text{ But, } \frac{AD}{DB} & =\frac{AE}{EC} \text{ (given). } \tag{ii}
\end{align*}
$$

From (i) and (ii), we get

$$
\begin{aligned}
\frac{AF}{FC}=\frac{AE}{EC} & \Rightarrow \frac{AF}{FC}+1=\frac{AE}{EC}+1 \Rightarrow \frac{AF+FC}{FC}=\frac{AE+EC}{EC} \\
& \Rightarrow \frac{AC}{FC}=\frac{AC}{EC} \Rightarrow \frac{1}{FC}=\frac{1}{EC} \Rightarrow FC=EC.
\end{aligned}
$$

This is possible only when $E$ and $F$ coincide.
Hence, $DE \| BC$.

---

## Solved Examples

### Example 1

In the given figure, $MN \| AB$, $BC=7.5 \mathrm{~cm}, AM=4 \mathrm{~cm}$ and $MC=2 \mathrm{~cm}$. Find the length of $BN$.
[CBSE 2010]

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-005.jpg)

#### Solution:

In $\triangle ABC, MN \| AB$.
$$
\therefore \quad \frac{MC}{AC}=\frac{NC}{BC} \quad [\text{by Thales' theorem}]
$$
$$
\Rightarrow \frac{MC}{AM+MC}=\frac{NC}{BC}
$$
$$
\Rightarrow \quad \frac{2}{4+2}=\frac{x}{7.5}, \text{ where } NC=x \mathrm{~cm}
$$
$$
\Rightarrow \quad x=\frac{2 \times 7.5}{6}=\frac{15}{6}=2.5
$$
$$
\Rightarrow NC=2.5 \mathrm{~cm}.
$$
Hence, $BN=BC-NC=(7.5-2.5) \mathrm{~cm}=5 \mathrm{~cm}$.

---

### Example 2

In the given figure, $DE \| BC$ and $\frac{AD}{DB}=\frac{3}{5}$.
If $AC=4.8 \mathrm{~cm}$, find the length of $AE$.
[CBSE 2008C]

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-006.jpg)

#### Solution:

Let $AE=x \mathrm{~cm}$.
Then, $EC=(AC-AE)=(4.8-x) \mathrm{~cm}$.

Now, in $\triangle ABC, DE \| BC$.
$$
\therefore \quad \frac{AD}{DB}=\frac{AE}{EC} \Rightarrow \frac{3}{5}=\frac{x}{(4.8-x)}
$$
$$
\Rightarrow 3(4.8-x)=5 x \Rightarrow 8 x=14.4
$$
$$
\Rightarrow \quad x=1.8.
$$
Hence, $AE=1.8 \mathrm{~cm}$.

---

### Example 3

In the given figure, in $\triangle ABC, DE \| BC$ so that $AD=(4 x-3) \mathrm{~cm}, AE=(8 x-7) \mathrm{~cm}$, $BD=(3 x-1) \mathrm{~cm}$ and $CE=(5 x-3) \mathrm{~cm}$. Find the value of $x$.
[CBSE 2002C]

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-007.jpg)

#### Solution:

In $\triangle ABC, DE \| BC$.
$$
\therefore \quad \frac{AD}{BD}=\frac{AE}{CE} \quad [\text{by Thales' theorem}]
$$
$$
\Rightarrow \quad \frac{4 x-3}{3 x-1}=\frac{8 x-7}{5 x-3} \Rightarrow(4 x-3)(5 x-3)=(3 x-1)(8 x-7)
$$
$$
\Rightarrow 20 x^{2}-27 x+9=24 x^{2}-29 x+7
$$
$$
\Rightarrow 4 x^{2}-2 x-2=0 \Rightarrow 2 x^{2}-x-1=0
$$
$$
\Rightarrow 2 x^{2}-2 x+x-1=0 \Rightarrow 2 x(x-1)+(x-1)=0
$$
$$
\Rightarrow \quad(x-1)(2 x+1)=0
$$
$$
\Rightarrow \quad(x-1)=0 \quad \text{ or } (2 x+1)=0
$$
$$
\Rightarrow \quad x=1 \text{ or } x=\frac{-1}{2}.
$$
But, $x=\frac{-1}{2} \Rightarrow AD=\left[4 \times\left(\frac{-1}{2}\right)-3\right]=-5$.
And, distance can never be negative. So, $x \neq \frac{-1}{2}$.
Hence, $x=1$.

---

### Example 4

If $D$ and $E$ are points on the sides $AB$ and $AC$ respectively of $\triangle ABC$ such that $AB=5.6 \mathrm{~cm}, AD=1.4 \mathrm{~cm}, AC=7.2 \mathrm{~cm}$ and $AE=1.8 \mathrm{~cm}$, show that $DE \| BC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-008.jpg)

#### Solution:

Given, $AB=5.6 \mathrm{~cm}, AD=1.4 \mathrm{~cm}, AC=7.2 \mathrm{~cm}$ and $AE=1.8 \mathrm{~cm}$.
$$
\therefore \quad \frac{AD}{AB}=\frac{1.4}{5.6}=\frac{1}{4} \text{ and } \frac{AE}{AC}=\frac{1.8}{7.2}=\frac{1}{4}
$$
$$
\Rightarrow \quad \frac{AD}{AB}=\frac{AE}{AC}.
$$
Hence, by the converse of Thales' theorem, $DE \| BC$.

---

### Example 5

In the adjoining figure, $MN \| QR$.
Find (i) PN and (ii) PR.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-009.jpg)

#### Solution:

In $\triangle PQR, MN \| QR$.
$$
\therefore \quad \frac{PM}{MQ}=\frac{PN}{NR} \quad [\text{by Thales' theorem}]
$$
$$
\Rightarrow \quad \frac{1.9}{5.7}=\frac{x}{6.9}, \text{ where } PN=x \mathrm{~cm}
$$
$$
\Rightarrow \quad x=\frac{1.9 \times 6.9}{5.7}=2.3.
$$
Hence, (i) $PN=x \mathrm{~cm}=2.3 \mathrm{~cm}$ and (ii) $PR=PN+NR=(2.3+6.9) \mathrm{~cm}=9.2 \mathrm{~cm}$.

---

### Example 6

In the given figure, $\frac{AD}{DB}=\frac{AE}{EC}$ and $\angle ADE=\angle ACB$. Prove that $\triangle ABC$ is an isosceles triangle.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-010.jpg)

#### Solution:

We have
$$
\frac{AD}{DB}=\frac{AE}{EC} \Rightarrow DE \| BC \quad [\text{by the converse of Thales' theorem}]
$$
$$
\therefore \quad \angle ADE=\angle ABC \text{ (corresponding } \angle\text{s)}.
$$
But, $\angle ADE=\angle ACB$ (given).
$$
\therefore \quad \angle ABC=\angle ACB.
$$
So, $AB=AC$ [sides opposite to equal angles].
Hence, $\triangle ABC$ is an isosceles triangle.

---

### Example 7

$M$ and $N$ are points on the sides $AC$ and $BC$ respectively of a $\triangle ABC$. In each of the following cases, state whether $MN \| AB$.

(i) $CM=4.2 \mathrm{~cm}, MA=2.8 \mathrm{~cm}, NB=3.6 \mathrm{~cm}, CN=5.7 \mathrm{~cm}$
(ii) $CB=6.92 \mathrm{~cm}, CN=1.04 \mathrm{~cm}, CA=1.73 \mathrm{~cm}, CM=0.26 \mathrm{~cm}$
(iii) $CM=5.1 \mathrm{~cm}, CA=6.8 \mathrm{~cm}, CB=5.6 \mathrm{~cm}, NB=1.4 \mathrm{~cm}$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-011.jpg)

#### Solution:

(i) We have
$$
\frac{CM}{MA}=\frac{4.2}{2.8}=\frac{3}{2} \text{ and } \frac{CN}{NB}=\frac{5.7}{3.6}=\frac{19}{12}.
$$
Since $\frac{CM}{MA} \neq \frac{CN}{NB}$.
So, $MN$ is not parallel to $AB$.

(ii) We have
$$
\begin{aligned}
MA & =CA-CM=(1.73-0.26) \mathrm{~cm}=1.47 \mathrm{~cm} \\
\text{ and } NB & =CB-CN=(6.92-1.04) \mathrm{~cm}=5.88 \mathrm{~cm}
\end{aligned}
$$
$$
\therefore \quad \frac{CM}{MA}=\frac{0.26}{1.47}=\frac{26}{147} \text{ and } \frac{CN}{NB}=\frac{1.04}{5.88}=\frac{26}{147}.
$$
Clearly, $\frac{CM}{MA}=\frac{CN}{NB}$ and so $MN \| AB$ [by the converse of Thales' theorem].

(iii) We have
$$
\begin{aligned}
& \qquad MA=CA-CM=(6.8-5.1) \mathrm{~cm}=1.7 \mathrm{~cm} \\
& \text{ and } CN=CB-NB=(5.6-1.4) \mathrm{~cm}=4.2 \mathrm{~cm}
\end{aligned}
$$
$$
\therefore \quad \frac{CM}{MA}=\frac{5.1}{1.7}=\frac{3}{1} \text{ and } \frac{CN}{NB}=\frac{4.2}{1.4}=\frac{3}{1}
$$
Clearly, $\frac{CM}{MA}=\frac{CN}{NB}$ and so $MN \| AB$ [by the converse of Thales' theorem].

---

### Example 8

In the given figure, $DE \| AC$ and $DF \| AE$. Prove that $\frac{BF}{FE}=\frac{BE}{EC}$.
[CBSE 2005, '07]

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-012.jpg)

#### Solution:

In $\triangle BAE, DF \| AE$.
$$
\therefore \quad \frac{BD}{DA}=\frac{BF}{FE}. \quad ... \text{(i) [by Thales' theorem]}
$$
In $\triangle BAC, DE \| AC$.
$$
\therefore \quad \frac{BD}{DA}=\frac{BE}{EC}. \quad ... \text{(ii) [by Thales' theorem]}
$$
From (i) and (ii), we get
$$
\frac{BF}{FE}=\frac{BE}{EC} \quad \left[\text{ each equal to } \frac{BD}{DA}\right].
$$

---

### Example 9

In the figure given along side, $DE \| OQ$ and $DF \| OR$. Show that $EF \| QR$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-013.jpg)

#### Solution:

In $\triangle POQ, DE \| OQ$.
$$
\therefore \quad \frac{PD}{DO}=\frac{PE}{EQ}. \quad ... \text{(i) [by Thales' theorem]}
$$
In $\triangle POR, DF \| OR$.
$$
\therefore \quad \frac{PD}{DO}=\frac{PF}{FR}. \tag{ii}
$$
From (i) and (ii), we get
$$
\frac{PE}{EQ}=\frac{PF}{FR} \quad \left[\text{ each equal to } \frac{PD}{DO}\right].
$$
Thus, in $\triangle PQR, E$ and $F$ are points on $PQ$ and $PR$ respectively such that $\frac{PE}{EQ}=\frac{PF}{FR}$.

Hence, $EF \| QR$ [by the converse of Thales' theorem].

---

### Example 10

In the given figure, $LM \| CB$ and $LN \| CD$. Prove that $\frac{AM}{AB}=\frac{AN}{AD}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-014.jpg)

#### Solution:

In $\triangle ALM, LM \| CB$.
$$
\therefore \quad \frac{AB}{AM}=\frac{AC}{AL} \Rightarrow \frac{AM}{AB}=\frac{AL}{AC}. \quad ... \text{(i) [by Thales' theorem]}
$$
In $\triangle ALN, LN \| CD$.
$$
\therefore \quad \frac{AC}{AL}=\frac{AD}{AN} \Rightarrow \frac{AL}{AC}=\frac{AN}{AD}. \tag{ii}
$$
From (i) and (ii), we get
$$
\frac{AM}{AB}=\frac{AN}{AD}.
$$

---

### Example 11

In the given figure, $AB \| DE$ and $BD \| EF$. Prove that $DC^{2}=CF \times AC$.
[CBSE 2004C, '10]

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-015.jpg)

#### Solution:

In $\triangle ABC, AB \| DE$.
$$
\therefore \quad \frac{CD}{DA}=\frac{CE}{EB}. \quad ... \text{(i) [by Thales' theorem]}
$$
In $\triangle CDB, BD \| EF$.
$$
\therefore \quad \frac{CF}{FD}=\frac{CE}{EB}. \quad ... \text{(ii) [by Thales' theorem]}
$$
From (i) and (ii), we get
$$
\frac{CD}{DA}=\frac{CF}{FD}
$$
$$
\Rightarrow \frac{DA}{DC}=\frac{FD}{CF} \quad [\text{taking reciprocals}]
$$
$$
\Rightarrow \frac{DA}{DC}+1=\frac{FD}{CF}+1
$$
$$
\Rightarrow \quad \frac{DA+DC}{DC}=\frac{FD+CF}{CF}
$$
$$
\Rightarrow \quad \frac{AC}{DC}=\frac{DC}{CF}
$$
$$
\Rightarrow DC^{2}=CF \times AC.
$$

---

### Example 12

In the given figure, $PQ \| AB$ and $PR \| AC$. Prove that $QR \| BC$. [CBSE 2002, '05C]

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-016.jpg)

#### Solution:

In $\triangle OAB, PQ \| AB$.
$$
\therefore \quad \frac{OP}{PA}=\frac{OQ}{QB}. \quad ... \text{(i) [by Thales' theorem]}
$$
In $\triangle AOC, PR \| AC$.
$$
\therefore \quad \frac{OP}{PA}=\frac{OR}{RC}. \quad ... \text{(ii) [by Thales' theorem]}
$$
From (i) and (ii), we get
$$
\frac{OQ}{QB}=\frac{OR}{RC} \text{ in } \triangle OBC.
$$
Thus, in $\triangle OBC, Q$ and $R$ are points on $OB$ and $OC$ respectively such that $\frac{OQ}{QB}=\frac{OR}{RC}$.
Hence, by the converse of Thales' theorem, $QR \| BC$.

---

### Example 13

In the given figure, in $\triangle ABC, \angle B=\angle C$ and $BD=CE$. Prove that $DE \| BC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-017.jpg)

**GIVEN** A $\triangle ABC$ in which $\angle B=\angle C$ and $BD=CE$.

**TO PROVE** $DE \| BC$.

**PROOF** In $\triangle ABC, \angle B=\angle C \Rightarrow AB=AC$ [sides opposite equal $\angle$s are equal].
Now, $AB=AC \Rightarrow(AD+BD)=(AE+CE)$
$$
\begin{array}{ll}
\Rightarrow AD=AE & {[\because BD=CE(\text{given})]} \\
\Rightarrow \frac{AD}{BD}=\frac{AE}{CE} & {[\because BD=CE].}
\end{array}
$$
Thus, $\frac{AD}{BD}=\frac{AE}{CE}$.
Hence, $DE \| BC$ [by the converse of Thales' theorem].

---

### Example 14

In $\triangle ABC, D$ and $E$ are two points on $AB$ such that $AD=BE$. If $DP \| BC$ and $EQ \| AC$, prove that $PQ \| AB$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-018.jpg)

**GIVEN** A $\triangle ABC$ and $D, E$ are two points on $AB$ such that $AD=BE$. Also, $DP \| BC$, and $EQ \| AC$.

**TO PROVE** $PQ \| AB$.

**PROOF** In $\triangle ABC, DP \| BC$.
$$
\therefore \quad \frac{AD}{DB}=\frac{AP}{PC}. \quad \text{[by Thales' theorem]}
$$
In $\triangle CBA, EQ \| AC$.
$$
\therefore \quad \frac{BE}{EA}=\frac{BQ}{QC} \quad \text{[by Thales' theorem]}
$$
$$
\Rightarrow \quad \frac{AD}{DB}=\frac{BQ}{QC}. \quad [\because \quad BE=AD, EA=(ED+DA)=(DE+EB)=DB] \tag{ii}
$$
From (i) and (ii), we get
$$
\frac{AP}{PC}=\frac{BQ}{QC}
$$
$$
\therefore \quad PQ \| AB \quad \text{[by the converse of Thales' theorem].}
$$

---

### Example 15

If three or more parallel lines are intersected by two transversals, prove that the intercepts made by them on the transversals are proportional.

**GIVEN** Three lines $l, m, n$ such that $l\|m\| n$. These lines are cut by the transversals $AB$ and $CD$ in $P, Q, R$ and $E, F, G$ respectively.

**TO PROVE** $\frac{PQ}{QR}=\frac{EF}{FG}$.

**CONSTRUCTION** Draw $PM \| CD$, meeting the lines $m$ and $n$ at $L$ and $M$ respectively.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-019.jpg)

**PROOF**
$$
\begin{align*}
PL \| EF \text{ and } PE \| LF & \Rightarrow PLFE \text{ is a } \|gm \\
& \Rightarrow PL=EF. \tag{i}
\end{align*}
$$
(opp. sides of a $\|gm$)

$$
\begin{align*}
\text{Also, } LM \| FG \text{ and } LF \| MG & \Rightarrow LMG F \text{ is a } \|gm \\
& \Rightarrow LM=FG. \tag{ii}
\end{align*}
$$
(opp. sides of a $\|gm$)

In $\triangle PRM, QL \| RM$ and therefore, by Thales' theorem, we have
$$
\begin{aligned}
\frac{PQ}{QR} & =\frac{PL}{LM}=\frac{EF}{FG} \quad [\text{ using (i) and (ii) }]. \\
\therefore \quad \frac{PQ}{QR} & =\frac{EF}{FG}.
\end{aligned}
$$

---

### Example 16

$ABCD$ is a quadrilateral and $P, Q, R, S$ are the points of trisection of the sides $AB, BC, CD$ and $DA$ respectively and are adjacent to $A$ and $C$. Prove that $PQRS$ is a parallelogram.

**GIVEN** A quadrilateral $ABCD$ in which $P, Q, R, S$ are the points of trisection of $AB, BC, CD$ and $DA$ respectively (as shown).

**TO PROVE** $PQRS$ is a parallelogram.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-020.jpg)

**CONSTRUCTION** Join AC.

**PROOF** In $\triangle BAC$, we have $\frac{BP}{PA}=\frac{BQ}{QC}=\frac{2}{1}$.
$$
\therefore PQ \| AC. \quad ... \text{(i) [by the converse of Thales' theorem]}
$$
Also, in $\triangle DAC$, we have
$$
\frac{DS}{SA}=\frac{DR}{RC}=\frac{2}{1}.
$$
$$
\therefore \quad SR \| AC. \quad ... \text{(ii) [by the converse of Thales' theorem]}
$$
Thus, $PQ \| SR$ [from (i) and (ii)].
Similarly, by joining $BD$ we can prove that $SP \| RQ$.
Hence, $PQRS$ is a parallelogram.

---

### Example 17

$ABCD$ is a trapezium with $AB \| DC$. $E$ and $F$ are points on nonparallel sides $AD$ and $BC$ respectively such that $EF \| AB$. Show that $\frac{AE}{ED}=\frac{BF}{FC}$.

**GIVEN** A trap. $ABCD$ in which $AB \| DC$. $E$ and $F$ are points on $AD$ and $BC$ respectively such that $EF \| AB$.

**TO PROVE** $\frac{AE}{ED}=\frac{BF}{FC}$.

**CONSTRUCTION** Join $AC$, intersecting $EF$ at $G$.

**PROOF** $EF \| AB$ and $AB\|DC \Rightarrow EF\| DC$.
Now, in $\triangle ADC, EG \| DC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-021.jpg)

$$
\therefore \quad \frac{AE}{ED}=\frac{AG}{GC}. \quad ... \text{(i) [by Thales' theorem]}
$$
Similarly, in $\triangle CAB, GF \| AB$.
$$
\therefore \quad \frac{CG}{GA}=\frac{CF}{FB} \tag{ii}
$$
[by Thales' theorem]
$$
\Rightarrow \quad \frac{AG}{GC}=\frac{BF}{FC}.
$$
From (i) and (ii), we get
$$
\frac{AE}{ED}=\frac{BF}{FC}.
$$

---

### Example 18

$ABCD$ is a trapezium in which $AB \| DC$ and its diagonals intersect each other at the point $O$.
Prove that $\frac{AO}{OC}=\frac{BO}{OD}$.
[CBSE 2004]

#### Solution:

**GIVEN** A trapezium $ABCD$ in which $AB \| DC$ and its diagonals $AC$ and $BD$ intersect at $O$.

**TO PROVE** $\frac{AO}{OC}=\frac{BO}{OD}$.

**CONSTRUCTION** Through $O$, draw $EO \| AB$, meeting $AD$ at $E$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-022.jpg)

**PROOF** In $\triangle ADC, EO \| DC \quad [\because EO\|AB\| DC]$.
$$
\therefore \quad \frac{AE}{ED}=\frac{AO}{OC} \quad ... \text{(i) [by Thales' theorem]}
$$
In $\triangle DAB, EO \| AB$.
$$
\therefore \quad \frac{DE}{EA}=\frac{DO}{OB} \tag{ii}
$$
[by Thales' theorem]
$$
\Rightarrow \frac{AE}{ED}=\frac{BO}{OD}.
$$
From (i) and (ii), we get
$$
\frac{AO}{OC}=\frac{BO}{OD}
$$

---

### Example 19

The diagonals of a quadrilateral $ABCD$ intersect each other at the point $O$ such that $\frac{AO}{OC}=\frac{BO}{OD}$. Show that $ABCD$ is a trapezium.
[CBSE 2005, '08]

**GIVEN** A quadrilateral $ABCD$ whose diagonals $AC$ and $BD$ intersect at a point $O$ such that $\frac{AO}{OC}=\frac{BO}{OD}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-023.jpg)

**TO PROVE** $ABCD$ is a trapezium, i.e., $AB \| DC$.

**CONSTRUCTION** Draw $EO \| DC$, meeting $AD$ at $E$.

**PROOF** In $\triangle ACD, EO \| DC$.
$$
\therefore \quad \frac{AO}{OC}=\frac{AE}{ED} \quad \text{[by Thales' theorem].}
$$
But, $\frac{AO}{OC}=\frac{BO}{OD}$ (given)
$$
\therefore \quad \frac{BO}{OD}=\frac{AE}{ED} \Rightarrow \frac{DO}{OB}=\frac{DE}{EA} \text{ in } \triangle DAB.
$$
So, $EO \| AB$ [by the converse of Thales' theorem].
But, $EO \| DC$.
Hence, $AB \| DC$, i.e., $ABCD$ is a trapezium.

---

### Example 20

In the given figure, $ABCD$ is a trapezium in which $AB \| DC$ and its diagonals intersect at $O$. If $AO=(3 x-1) \mathrm{~cm}, O C=(5 x-3) \mathrm{~cm}$, $BO=(2 x+1) \mathrm{~cm}$ and $OD=(6 x-5) \mathrm{~cm}$, find the value of $x$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-024.jpg)

We know that $AB \| DC$ in trapezium $ABCD$ and its diagonals intersect at $O$. Then, we have
$$
\begin{aligned}
\frac{AO}{OC}=\frac{BO}{OD} & \Rightarrow \frac{3 x-1}{5 x-3}=\frac{2 x+1}{6 x-5} \\
& \Rightarrow(3 x-1)(6 x-5)=(2 x+1)(5 x-3) \\
& \Rightarrow 18 x^{2}-21 x+5=10 x^{2}-x-3 \\
& \Rightarrow 8 x^{2}-20 x+8=0 \Rightarrow 2 x^{2}-5 x+2=0 \\
& \Rightarrow(x-2)(2 x-1)=0 \\
& \Rightarrow x=2 \text{ or } x=\frac{1}{2}
\end{aligned}
$$
But, $x=\frac{1}{2}$ will make $OC=(5 x-3) \mathrm{~cm}=\left(5 \times \frac{1}{2}-3\right) \mathrm{~cm}=-\frac{1}{2} \mathrm{~cm}$.

And, the distance cannot be negative.
$$
\therefore \quad x \neq \frac{1}{2}.
$$
Hence, $x=2$.

---

## Midpoint Theorem

### Example 21

Prove that the line segment joining the midpoints of any two sides of a triangle is parallel to the third side.

#### Solution:

**GIVEN** A $\triangle ABC$ in which $D$ and $E$ are the midpoints of $AB$ and $AC$ respectively.

**TO PROVE** $DE \| BC$.

**PROOF** Since $D$ and $E$ are the midpoints of $AB$ and $AC$ respectively, we have

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-025.jpg)

$AD=DB$ and $AE=EC$.
$$
\therefore \quad \frac{AD}{DB}=\frac{AE}{EC} \quad [\text{each equal to 1}].
$$
Hence, by the converse of Thales' theorem, $DE \| BC$.

---

### Example 22

Prove that a line drawn through the midpoint of one side of a triangle parallel to another side bisects the third side.

#### Solution:

**GIVEN** A $\triangle ABC$ in which $D$ is the midpoint of $AB$ and $DE \| BC$, meeting $AC$ at $E$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-026.jpg)

**TO PROVE** $AE=EC$.

**PROOF** Since $DE \| BC$, by Thales' theorem, we have
$$
\begin{aligned}
& \frac{AE}{EC}=\frac{AD}{DB}=1 \quad [\because AD=DB(\text{given})] \\
\Rightarrow & \frac{AE}{EC}=1 \Rightarrow AE=EC.
\end{aligned}
$$

---

### Example 23

In $\triangle ABC, AD$ is a median and $E$ is the midpoint of $AD$. If $BE$ is produced, it meets $AC$ in $F$. Show that $AF=\frac{1}{3} AC$. [CBSE 2006C]

#### Solution:

**GIVEN** A $\triangle ABC$ in which $AD$ is a median and $E$ is the midpoint of $AD$. Also, $BE$ is produced to meet $AC$ at $F$.

**TO PROVE** $AF=\frac{1}{3} AC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-027.jpg)

**CONSTRUCTION** From $D$, draw $DG \| EF$, meeting $AC$ at $G$.

**PROOF** In $\triangle BCF, D$ is the midpoint of $BC$ and $DG \| BF$.
$\therefore \quad G$ is the midpoint of $CF$.
So, $FG=GC$.

In $\triangle ADG, E$ is the midpoint of $AD$ and $EF \| DG$.
$\therefore \quad F$ is the midpoint of $AG$.
So, $AF=FG$.
Thus, $AF=FG=GC$.
$$
\therefore \quad AC=(AF+FG+GC)=3 AF.
$$
Hence, $AF=\frac{1}{3} AC$.

---

### Example 24

Prove that the line segments joining the midpoints of the adjacent sides of a quadrilateral form a parallelogram.

#### Solution:

**GIVEN** A quadrilateral $ABCD$ in which $P, Q, R, S$ are the midpoints of $AB, BC, CD$ and $DA$ respectively.

**TO PROVE** $PQRS$ is a parallelogram.

**CONSTRUCTION** Join AC.

**PROOF** In $\triangle ABC, P$ and $Q$ are the midpoints of $AB$ and $BC$ respectively.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-028.jpg)

$$
\therefore \quad PQ \| AC. \quad ... \text{(i) [by midpoint theorem]}
$$
In $\triangle DAC, S$ and $R$ are the midpoints of $AD$ and $CD$ respectively.
$$
\therefore \quad SR \| AC. \quad ... \text{(ii) [by midpoint theorem]}
$$
From (i) and (ii), we get $PQ \| SR$.
Similarly, by joining $BD$, we can prove that $PS \| QR$.
Hence, $PQRS$ is a parallelogram.

---

## Angle-Bisector Theorem

### Example 25

Prove that the internal bisector of an angle of a triangle divides the opposite side internally in the ratio of the sides containing the angle.

#### Solution:

**GIVEN** A $\triangle ABC$ in which $AD$, the bisector of $\angle A$, meets $BC$ in $D$.

**TO PROVE** $\frac{BD}{DC}=\frac{AB}{AC}$.

**CONSTRUCTION** Draw $CE \| DA$, meeting $BA$ produced at $E$.

**PROOF** Since $DA \| CE$, we have
$$
\begin{aligned}
\angle 2 & =\angle 3 \quad [\text{alternate int. } \angle\text{s}] \\
\text{ and } \angle 1 & =\angle 4 \quad [\text{corresponding } \angle\text{s}]. \\
\text{ But, } \angle 1 & =\angle 2 \quad [\because AD \text{ is the bisector of } \angle A] \\
\therefore \quad \angle 3 & =\angle 4.
\end{aligned}
$$
Now, in $\triangle BCE, DA \| CE$.
$$
\therefore \quad \frac{BD}{DC}=\frac{AB}{AE}
$$
$$
\Rightarrow \quad \frac{BD}{DC}=\frac{AB}{AC} \quad [\because \quad AE=AC].
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-029.jpg)

Hence, $\frac{BD}{DC}=\frac{AB}{AC}$.

---

### Example 26

In a $\triangle ABC$, let $D$ be a point on $BC$ such that $\frac{BD}{DC}=\frac{AB}{AC}$. Prove that $AD$ is the bisector of $\angle A$.

#### Solution:

**GIVEN** A $\triangle ABC$ in which $D$ is a point on $BC$ such that $\frac{BD}{DC}=\frac{AB}{AC}$.

**TO PROVE** $AD$ is the bisector of $\angle A$.

**CONSTRUCTION** Produce $BA$ to $E$ such that $AE=AC$. Join $EC$.

**PROOF** $\frac{BD}{DC}=\frac{AB}{AC}$ (given)

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-030.jpg)

$$
\Rightarrow \quad \frac{BD}{DC}=\frac{AB}{AE} \quad [\because \quad AC=AE]
$$
$$
\Rightarrow DA \| CE \quad \text{[by the converse of Thales' theorem].}
$$
$$
\therefore \quad \angle 2=\angle 3 \quad ... \text{(i) [alternate int. } \Delta]
$$
$$
\text{and } \angle 1=\angle 4 \quad ... \text{(ii) [corresponding } \measuredangle]
$$
Also, $AE=AC \Rightarrow \angle 3=\angle 4$.
$$
\therefore \quad \angle 1=\angle 2 \quad \text{[from (i), (ii) and (iii)].}
$$
Hence, $AD$ is the bisector of $\angle A$.

---

### Example 27

In the given figure, $AD$ is the bisector of $\angle BAC$. If $AB=10 \mathrm{~cm}, AC=6 \mathrm{~cm}$ and $BC=12 \mathrm{~cm}$, find $BD$ and $DC$.
[CBSE 2001]

#### Solution:

Let $BD=x \mathrm{~cm}$. Then,
$$
DC=(BC-BD)=(12-x) \mathrm{~cm}.
$$
In $\triangle ABC, AD$ is the bisector of $\angle BAC$.
So, by the angle-bisector theorem, we have
$$
\begin{aligned}
\frac{BD}{DC}=\frac{AB}{AC} & \Rightarrow \frac{x}{12-x}=\frac{10}{6} \\
& \Rightarrow 6 x=10(12-x) \\
& \Rightarrow 16 x=120 \Rightarrow x=7.5
\end{aligned}
$$
Hence, $BD=7.5 \mathrm{~cm}$, and $DC=(12-7.5) \mathrm{~cm}=4.5 \mathrm{~cm}$.

---

### Example 28

If the bisector of an angle of a triangle bisects the opposite side, prove that the triangle is isosceles.
[CBSE 2000, '01, '02]

#### Solution:

**GIVEN** A $\triangle ABC$ in which $AD$ is the bisector of $\angle BAC$ such that $BD=DC$.

**TO PROVE** $AB=AC$.

**PROOF** Since $AD$ is the bisector of $\angle A$, by the angle-bisector theorem, we have
$$
\begin{aligned}
\frac{AB}{AC} & =\frac{BD}{DC}=1 \quad [\because BD=DC] \\
\Rightarrow \quad \frac{AB}{AC} & =1 \Rightarrow AB=AC.
\end{aligned}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-031.jpg)

Hence, $\triangle ABC$ is an isosceles triangle.

---

### Example 29

If the diagonal $BD$ of a quadrilateral $ABCD$ bisects both $\angle B$ and $\angle D$, prove that $\frac{AB}{BC}=\frac{AD}{CD}$.

#### Solution:

**GIVEN** A quad. $ABCD$ in which diagonal $BD$ bisects both $\angle B$ and $\angle D$.

**TO PROVE** $\frac{AB}{BC}=\frac{AD}{CD}$.

**CONSTRUCTION** Join $AC$, intersecting $BD$ at $E$.

**PROOF** In $\triangle CBA, BE$ is the bisector of $\angle ABC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Geometry/Triangles/class-10-Ch-07-A-BooK-032.jpg)

$$
\therefore \quad \frac{AE}{EC}=\frac{AB}{BC}. \quad ... \text{(i) [by the angle-bisector theorem]}
$$
In $\triangle ADC, DE$ is the bisector of $\angle ADC$.
$$
\therefore \quad \frac{AE}{EC}=\frac{AD}{CD}. \quad ... \text{(ii) [by the angle-bisector theorem]}
$$
From (i) and (ii), we get $\frac{AB}{BC}=\frac{AD}{CD}$.

---

