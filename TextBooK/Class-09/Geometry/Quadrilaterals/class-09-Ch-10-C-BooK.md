## Midpoint Theorem

**Theorem 1 (Midpoint Theorem):** The line segment joining the midpoints of any two sides of a triangle is parallel to the third side and equal to half of it.

**GIVEN:** A $\triangle ABC$ in which $D$ and $E$ are the midpoints of $AB$ and $AC$ respectively. $DE$ is joined.

**TO PROVE:** $DE \| BC$ and $DE = \frac{1}{2} BC$.

**CONSTRUCTION:** Draw $CF \| BA$, meeting $DE$ produced in $F$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-28.jpg?height=227&width=334&top_left_y=686&top_left_x=865)

**PROOF:** In $\triangle AED$ and $CEF$, we have:
- $\angle AED = \angle CEF$ (vertically opposite angles)
- $AE = CE$ ($\because E$ is the midpoint of $AC$)
- $\angle DAE = \angle FCE$ (alternate interior angles)

$\therefore \triangle AED \cong \triangle CEF$ (ASA-criterion).

And so, $AD = CF$ and $DE = EF$ (c.p.c.t.).

But, $AD = BD$ [$\because D$ is the midpoint of $AB$] and $BD \| CF$ (by construction).

$\therefore BD = CF$ and $BD \| CF$.

$\Rightarrow BCFD$ is a parallelogram.

$\Rightarrow DF \| BC$ and $DF = BC$.

$\Rightarrow DE \| BC$ and $DE = \frac{1}{2} DF = \frac{1}{2} BC$ [$\because DE = EF$].

Hence, $DE \| BC$ and $DE = \frac{1}{2} BC$.

---

**Theorem 2 (Converse of Midpoint Theorem):** The line drawn through the midpoint of one side of a triangle, parallel to another side, bisects the third side.

**GIVEN:** A $\triangle ABC$ in which $D$ is the midpoint of $AB$ and $DE \| BC$.

**TO PROVE:** $E$ is the midpoint of $AC$.

**CONSTRUCTION:** Draw $CF \| BA$, meeting $DE$ produced in $F$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-29.jpg?height=237&width=326&top_left_y=422&top_left_x=869)

**PROOF:** We have $DF \| BC$ [$\because DE \| BC$] and $BD \| CF$ [$\because CF \| BA$].

$\therefore DBCF$ is a parallelogram and so, $CF = DB = AD$ [$\because D$ is the midpoint of $AB$].

Now, in $\triangle ADE$ and $CFE$, we have:
- $\angle EAD = \angle ECF$ (alternate interior angles)
- $AD = CF$ (proved)
- $\angle ADE = \angle CFE$ (alternate interior angles)

$\therefore \triangle ADE \cong \triangle CFE$ (ASA-criterion).

And so, $AE = CE$ (c.p.c.t.).

Hence, $E$ is the midpoint of $AC$.

---
## Some Solved Problems on the Midpoint Theorem

### Example 1

If $D, E$ and $F$ are respectively the midpoints of the sides $BC, CA$ and $AB$ of an equilateral triangle $ABC$, prove that $\triangle DEF$ is also an equilateral triangle.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-29.jpg?height=259&width=261&top_left_y=801&top_left_x=938)

Since $D$ and $E$ are the midpoints of sides $BC$ and $CA$ respectively, we have $DE = \frac{1}{2} AB$ (by midpoint theorem).

Similarly, $FE = \frac{1}{2} BC$ and $DF = \frac{1}{2} CA$.

$\therefore AB = BC = CA \Rightarrow \frac{1}{2} AB = \frac{1}{2} BC = \frac{1}{2} CA \Rightarrow DE = FE = DF$.

Thus, all the sides of $\triangle DEF$ are equal.

Hence, $\triangle DEF$ is an equilateral triangle.

---
### Example 2

In $\triangle ABC$, $D, E$ and $F$ are respectively the midpoints of sides $AB, BC$ and $CA$. Show that $\triangle ABC$ is divided into four congruent triangles by joining $D, E$ and $F$ in pairs.

#### Solution:

$D$ and $F$ are the midpoints of sides $AB$ and $AC$ respectively of $\triangle ABC$.

$\therefore DF \| BC$. Similarly, $DE \| AC$ and $EF \| AB$.

Now, $DF \| BE$ and $EF \| BD$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-29.jpg?height=220&width=273&top_left_y=1643&top_left_x=922)

$\Rightarrow DBEF$ is a parallelogram.

$\Rightarrow \triangle EDB \cong \triangle DEF$ [$\because DE$ is a diagonal of parallelogram $DBEF$].

[**Note:** Any diagonal of a parallelogram divides it into two congruent triangles.]

Similarly, $\triangle CFE \cong \triangle DEF$ and $\triangle FAD \cong \triangle DEF$.

Hence, all the four triangles are congruent.

---
### Example 3

In the adjoining figure, $\triangle ABC$ is an isosceles triangle in which $AB = AC$ and $D, E, F$ are the midpoints of $BC, CA$ and $AB$ respectively. Show that $AD \perp FE$ and $AD$ is bisected by $FE$.

#### Solution:

Let $AD$ intersect $FE$ at $M$. Join $DE$ and $DF$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-30.jpg?height=243&width=181&top_left_y=420&top_left_x=1018)

Now, $D$ and $E$ being the midpoints of the sides $BC$ and $CA$ respectively, we have $DE \| AB$ and $DE = \frac{1}{2} AB$ (by midpoint theorem).

Similarly, $DF \| AC$ and $DF = \frac{1}{2} AC$.

$$
\therefore AB = AC \Rightarrow \frac{1}{2} AB = \frac{1}{2} AC \Rightarrow DE = DF \quad \text{(i)}
$$

Now, $DE \| FA$ and $DE = FA$ [$\because DE \| AB$ and $DE = \frac{1}{2} AB = FA$].

$\Rightarrow DEAF$ is a parallelogram.

$\Rightarrow DEAF$ is a rhombus [$\because DE = DF$ from (i), $DE = FA$ and $DF = EA$].

But, the diagonals of a rhombus bisect each other at right angles.

$\therefore AD \perp FE$ and $AM = MD$.

Hence, $AD \perp FE$ and $AD$ is bisected by $FE$.

---
### Example 4

Let $ABC$ be a triangle, right-angled at $B$ and $D$ be the midpoint of $AC$. Show that $DA = DB = DC$.

#### Solution:

Through $D$, draw $DE \| BC$, meeting $AB$ at $E$.

Now, $\angle AED = \angle ABC = 90^{\circ}$ [corresponding angles].

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-30.jpg?height=257&width=289&top_left_y=1457&top_left_x=906)

$$
\therefore \angle BED = 90^{\circ} \quad [\because \angle AED + \angle BED = 180^{\circ}]
$$

Now, in $\triangle ABC$, it is given that $D$ is the midpoint of $AC$ and $DE \| BC$ (by construction).

$\therefore E$ must be the midpoint of $AB$ (by converse of midpoint theorem).

$\therefore AE = BE$.

Now, in $\triangle AED$ and $BED$, we have:
- $AE = BE$ (proved)
- $ED = ED$ (common)
- $\angle AED = \angle BED$ (each equal to $90^{\circ}$)

$\therefore \triangle AED \cong \triangle BED$.

$\therefore DA = DB$.

But, $DA = DC$ [$\because D$ is the midpoint of $AC$].

Hence, $DA = DB = DC$.

---
### Example 5

$ABCD$ is a parallelogram in which $E$ and $F$ are the midpoints of the sides $AB$ and $CD$ respectively. Prove that the line segments $CE$ and $AF$ trisect the diagonal $BD$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-31.jpg?height=197&width=299&top_left_y=728&top_left_x=896)

Let $BD$ be intersected by $CE$ and $AF$ at $P$ and $Q$ respectively.

$AB \| DC$ and $AB = DC$ (opposite sides of a parallelogram).

$\Rightarrow AE \| FC$ and $\frac{1}{2} AB = \frac{1}{2} DC \Rightarrow AE \| FC$ and $AE = FC$.

$\Rightarrow AECF$ is a parallelogram.

$\Rightarrow AF \| CE \Rightarrow EP \| AQ$ and $FQ \| CP$.

In $\triangle BAQ$, $E$ is the midpoint of $AB$ and $EP \| AQ$, so $P$ is the midpoint of $BQ$.

$\therefore BP = PQ$.

Again, in $\triangle DPC$, $F$ is the midpoint of $DC$ and $FQ \| CP$, so $Q$ is the midpoint of $DP$.

$\therefore PQ = QD$.

$\therefore BP = PQ = QD$.

Hence, $CE$ and $AF$ trisect the diagonal $BD$.

---
### Example 6

Show that the figure formed by joining the midpoints of the adjacent sides of a quadrilateral is a parallelogram.

#### Solution:

Let $ABCD$ be a quadrilateral in which $P, Q, R, S$ are the midpoints of $AB, BC, CD$ and $DA$ respectively. Join $AC$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-31.jpg?height=200&width=322&top_left_y=1711&top_left_x=873)

In $\triangle ABC$, the points $P$ and $Q$ are the midpoints of $AB$ and $BC$ respectively.

$\therefore PQ \| AC$ and $PQ = \frac{1}{2} AC$ (by midpoint theorem).

Again, in $\triangle DAC$, the points $S$ and $R$ are the midpoints of $AD$ and $DC$ respectively.

$\therefore SR \| AC$ and $SR = \frac{1}{2} AC$ (by midpoint theorem).

Now, $PQ \| AC$ and $SR \| AC \Rightarrow PQ \| SR$.

Also, $PQ = SR$ (each equal to $\frac{1}{2} AC$).

$\therefore PQ \| SR$ and $PQ = SR$.

Hence, $PQRS$ is a parallelogram.

---
### Example 7

$E$ and $F$ are respectively the midpoints of the nonparallel sides $AD$ and $BC$ of a trapezium $ABCD$. Prove that (i) $EF \| AB$, (ii) $EF = \frac{1}{2}(AB + CD)$.

**GIVEN:** A trapezium $ABCD$ in which $E$ and $F$ are midpoints of sides $AD$ and $BC$ respectively.

**TO PROVE:** (i) $EF \| AB$, (ii) $EF = \frac{1}{2}(AB + CD)$.

**CONSTRUCTION:** Join $DF$ and produce it to meet $AB$ produced in $P$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-32.jpg?height=188&width=314&top_left_y=1083&top_left_x=881)

In $\triangle DCF$ and $PBF$ we have:
- $\angle DFC = \angle PFB$ (vertically opposite angles)
- $CF = BF$ ($\because F$ is the midpoint of $BC$)
- $\angle DCF = \angle PBF$ (alternate interior angles)

$\therefore \triangle DCF \cong \triangle PBF$ (ASA-criterion).

And so, $DF = PF$ and $CD = BP$ (c.p.c.t).

Now, in $\triangle DAP$, we have $E$ is the midpoint of $AD$ and $F$ is the midpoint of $DP$.

$\therefore EF \| AP$ and $EF = \frac{1}{2} AP$ [by midpoint theorem].

$\Rightarrow EF \| AB$ and $EF = \frac{1}{2}(AB + BP)$.

Hence, $EF \| AB$ and $EF = \frac{1}{2}(AB + CD)$.

---
### Example 8

Let $ABCD$ be a trapezium in which $AB \| DC$ and let $E$ be the midpoint of $AD$. Let $F$ be a point on $BC$ such that $EF \| AB$. Prove that (i) $F$ is the midpoint of $BC$, (ii) $EF = \frac{1}{2}(AB + DC)$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-33.jpg?height=192&width=299&top_left_y=169&top_left_x=898)

Join $BD$, cutting $EF$ at $M$.

Now, in $\triangle DAB$, $E$ is the midpoint of $AD$ and $EM \| AB$.

$\therefore M$ is the midpoint of $BD$.

$\therefore EM = \frac{1}{2} AB$. (i)

Again, in $\triangle BDC$, $M$ is the midpoint of $BD$ and $MF \| DC$.

$\therefore F$ is the midpoint of $BC$.

$\therefore MF = \frac{1}{2} DC$. (ii)

$\therefore EF = EM + MF = \frac{1}{2}AB + \frac{1}{2}DC = \frac{1}{2}(AB + DC)$ [from (i) and (ii)].

Hence, $F$ is the midpoint of $BC$ and $EF = \frac{1}{2}(AB + DC)$.

---
### Example 9

Prove that the line segment joining the midpoints of the diagonals of a trapezium is parallel to the parallel sides and equal to half their difference.

#### Solution:

Let $ABCD$ be a trapezium in which $AB \| DC$, and let $M$ and $N$ be the midpoints of the diagonals $AC$ and $BD$ respectively.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-33.jpg?height=165&width=350&top_left_y=1163&top_left_x=849)

Join $CN$ and produce it to meet $AB$ at $E$.

In $\triangle CDN$ and $EBN$, we have:
- $DN = BN$ [$\because N$ is midpoint of $BD$]
- $\angle DCN = \angle BEN$ (alternate interior angles)
- $\angle CDN = \angle EBN$ (alternate interior angles)

$\therefore \triangle CDN \cong \triangle EBN$ [SAA-criteria].

$\therefore DC = EB$ and $CN = NE$ (c.p.c.t.).

Thus, in $\triangle CAE$, the points $M$ and $N$ are the midpoints of $AC$ and $CE$ respectively.

$\therefore MN \| AE$ and $MN = \frac{1}{2} AE \Rightarrow MN \| AB \| DC$.

and $MN = \frac{1}{2} AE = \frac{1}{2}(AB - EB) = \frac{1}{2}(AB - DC)$ [$\because EB = DC$].

---
### Example 10

$ABCD$ is a trapezium in which $AB \| DC$ and $E$ is the midpoint of $AD$. A line is drawn through $E$ parallel to $AB$ intersecting $BC$ at $F$. Show that $F$ is the midpoint of $BC$.

**GIVEN:** A trapezium $ABCD$ in which $AB \| DC$. $E$ is the midpoint of side $AD$. A line $EF$ is drawn parallel to $AB$ intersecting $BC$ at $F$.

**TO PROVE:** $F$ is the midpoint of $BC$.

**CONSTRUCTION:** Join $BD$. Let $BD$ intersect $EF$ at $G$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-34.jpg?height=185&width=293&top_left_y=418&top_left_x=898)

In $\triangle DAB$, we have $E$ is the midpoint of $AD$ and $EG \| AB$.

$\therefore G$ is the midpoint of $BD$ [by converse of midpoint theorem].

Now, in $\triangle BCD$, we have $G$ is the midpoint of $BD$ and $GF \| DC$ [$\because EF \| AB$ and $AB \| DC \Rightarrow EF \| DC$].

Hence, $F$ is the midpoint of $BC$ [by converse of midpoint theorem].

---
### Example 11

$ABC$ is a triangle right angled at $C$. A line through the midpoint $P$ of hypotenuse $AB$ and parallel to $BC$ intersects $AC$ at $M$. Show that
(i) $M$ is the midpoint of $AC$,
(ii) $MP \perp AC$,
(iii) $CP = AP = \frac{1}{2} AB$.

#### Solution:

In $\triangle ACB$, we have $P$ is the midpoint of $AB$ and $PM \| BC$.

$\therefore M$ is the midpoint of $AC$ [by converse of midpoint theorem]. (i)

Now, $PM \| BC$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-34.jpg?height=205&width=231&top_left_y=1151&top_left_x=964)

$\therefore \angle PMC + \angle BCM = 180^{\circ}$ (co-interior angles).

$\Rightarrow \angle PMC + 90^{\circ} = 180^{\circ} \Rightarrow \angle PMC = 90^{\circ}$.

Thus, $MP \perp AC$. (ii)

Join PC. In $\triangle PMA$ and $PMC$, we have:
- $MA = MC$ [$\because M$ is the midpoint of $AC$]
- $\angle PMA = \angle PMC$ (each equal to $90^{\circ}$)
- $PM = PM$ (common)

$\therefore \triangle PMA \cong \triangle PMC$ (SAS-criterion).

And so, $AP = CP$ (c.p.c.t.).

Now, $P$ is the midpoint of $AB$.

$\therefore CP = AP = \frac{1}{2} AB$. (iii)

---
### Example 12

In the adjoining figure, $ABCD$ is a parallelogram in which $P$ is the midpoint of $DC$ and $Q$ is a point on $AC$ such that $CQ = \frac{1}{4} AC$. Also, $PQ$ when produced meets $BC$ at $R$. Prove that $R$ is the midpoint of $BC$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-35.jpg?height=196&width=299&top_left_y=378&top_left_x=896)

Join $BD$, intersecting $AC$ at $O$.

Then, $AO = OC$ [$\because$ diagonals of a parallelogram bisect each other].

$\therefore CQ = \frac{1}{4} AC = \frac{1}{4} \times (2OC) = \frac{1}{2} OC$.

Thus, $Q$ is the midpoint of $OC$.

Now, in $\triangle CDO$, $P$ and $Q$ are the midpoints of $CD$ and $CO$ respectively.

$\therefore PQ \| DO$ and therefore, $QR \| OB$ [$\because PQ \| DO \Rightarrow PQR \| DOB$].

Now, in $\triangle COB$, $Q$ is the midpoint of $CO$ and $QR \| OB$.

$\therefore R$ must be the midpoint of $BC$.

---
### Example 13

In the adjoining figure, $AD$ is a median of $\triangle ABC$ and $E$ is the midpoint of $AD$. Also, $BE$ produced meets $AC$ in $F$. Prove that $AF = \frac{1}{3} AC$.

#### Solution:

Draw $DP \| EF$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-35.jpg?height=253&width=378&top_left_y=1252&top_left_x=821)

In $\triangle ADP$, $E$ is the midpoint of $AD$ and $EF \| DP$.

$\therefore F$ is the midpoint of $AP$, i.e., $AF = FP$.

In $\triangle FBC$, $D$ is the midpoint of $BC$ and $DP \| BF$.

$\therefore P$ is the midpoint of $FC$, i.e., $FP = PC$.

Thus, $AF = FP = PC$.

Hence, $AF = \frac{1}{3} AC$.

---
### Example 14

In the adjoining figure, $ABCD$ is a trapezium in which $AB \| DC$ and $AD = BC$. If $P, Q, R, S$ be respectively the midpoints of $BA, BD, CD, CA$ then show that $PQRS$ is a rhombus.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-36.jpg?height=196&width=334&top_left_y=169&top_left_x=861)

In $\triangle BDC$, $Q$ and $R$ are the midpoints of $BD$ and $CD$ respectively.

$\therefore QR \| BC$ and $QR = \frac{1}{2} BC$.

Similarly, $PS \| BC$ and $PS = \frac{1}{2} BC$.

$\therefore PS \| QR$ and $PS = QR$ (each equal to $\frac{1}{2} BC$).

$\therefore PQRS$ is a parallelogram.

In $\triangle ACD$, $S$ and $R$ are the midpoints of $AC$ and $CD$ respectively.

$\therefore SR \| AD$ and $SR = \frac{1}{2} AD = \frac{1}{2} BC$ [$\because AD = BC$].

$\therefore PS = QR = SR = PQ$.

Hence, $PQRS$ is a rhombus.

---
### Example 15

In the adjoining figure, $ABCD$ and $PQRC$ are rectangles, where $Q$ is the midpoint of $AC$. Prove that (i) $DP = PC$, (ii) $PR = \frac{1}{2} AC$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-36.jpg?height=200&width=291&top_left_y=1031&top_left_x=906)

$\angle CRQ = \angle CBA = 90^{\circ} \Rightarrow QR \| AB$.

In $\triangle ABC$, $Q$ is the midpoint of $AC$ and $QR \| AB$.

$\therefore R$ is the midpoint of $BC$, i.e., $BR = RC$.

Similarly, $P$ is the midpoint of $DC$.

$\therefore DP = PC$.

In $\triangle CDB$, $P$ is the midpoint of $DC$ and $R$ is the midpoint of $BC$.

$\therefore PR \| DB$ and $PR = \frac{1}{2} DB = \frac{1}{2} AC$ [$\because AC = BD$].

---
### Example 16

In the adjoining figure, $D, E, F$ are the midpoints of the sides $BC, CA$ and $AB$ of $\triangle ABC$. If $BE$ and $DF$ intersect at $X$ while $CF$ and $DE$ intersect at $Y$, prove that $XY = \frac{1}{4} BC$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-36.jpg?height=224&width=350&top_left_y=1683&top_left_x=845)

In $\triangle ABC$, $F$ and $E$ are the midpoints of $AB$ and $AC$ respectively.

$\therefore FE \| BC$ and $FE = \frac{1}{2} BC = BD$.

$\therefore FE \| BD$ and $FE = BD$.

So, $BDEF$ is a parallelogram whose diagonals $BE$ and $DF$ intersect each other at $X$.

$\therefore X$ is the midpoint of $DF$.

Similarly, $Y$ is the midpoint of $DE$.

Thus, in $\triangle DEF$, $X$ and $Y$ are the midpoints of $DF$ and $DE$ respectively.

So, $XY \| FE$ and $XY = \frac{1}{2} FE = \frac{1}{2} \times \frac{1}{2} BC = \frac{1}{4} BC$.

---
## Intercept Theorem

**Theorem 3 (Intercept Theorem):** If there are three parallel lines and the intercepts made by them on one transversal are equal then the intercepts on any other transversal are also equal.

**GIVEN:** Three parallel lines $l, m$ and $n$ are cut by a transversal $p$ at $A, B, C$ respectively such that $AB = BC$. Also, $q$ is another transversal, cutting $l, m, n$ at $P, Q, R$ respectively.

**TO PROVE:** $PQ = QR$.

**CONSTRUCTION:** Join $AR$. Let $AR$ intersect $m$ at $K$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-37.jpg?height=269&width=374&top_left_y=930&top_left_x=825)

**PROOF:** In $\triangle ACR$, we have $B$ is the midpoint of $AC$ and $BK \| CR$ [$\because m \| n$].

$\therefore K$ is the midpoint of $AR$ (by converse of midpoint theorem).

Now, in $\triangle RPA$, we have $K$ is the midpoint of $RA$ and $KQ \| AP$ [$\because m \| l$].

$\therefore Q$ is the midpoint of $PR$ (by converse of midpoint theorem).

Hence, $PQ = QR$.

---
## Some Solved Problems on the Intercept Theorem

### Example 1

In the adjoining figure, two points $A$ and $B$ lie on the same side of a line $XY$. If $AD \perp XY$, $BE \perp XY$ and $C$ is the midpoint of $AB$, prove that $CD = CE$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-37.jpg?height=228&width=338&top_left_y=1655&top_left_x=857)

Draw $CM \perp XY$.

Now, $AD \perp XY$, $CM \perp XY$ and $BE \perp XY \Rightarrow AD \| CM \| BE$.

Thus, $AD, CM, BE$ are three parallel lines, cut by the transversal $ACB$ at $A, C$ and $B$ respectively such that $AC = CB$.

These lines $AD, CM, BE$ are also cut by the transversal $XY$ at $D, M$ and $E$ respectively.

$\therefore DM = ME$ (by intercept theorem).

Now, in $\triangle CDM$ and $CEM$, we have:
- $DM = ME$ (proved)
- $CM = CM$ (common)
- $\angle CMD = \angle CME = 90^{\circ}$

$\therefore \triangle CDM \cong \triangle CEM$.

Hence, $CD = CE$ (c.p.c.t.).

---
### Example 2

In the adjoining figure, points $M$ and $N$ divide the side $AB$ of $\triangle ABC$ into three equal parts. Line segments $MP$ and $NQ$ are both parallel to $BC$ and meet $AC$ in $P$ and $Q$ respectively. Prove that $P$ and $Q$ divide $AC$ into three equal parts.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-38.jpg?height=184&width=305&top_left_y=817&top_left_x=886)

Through $A$, draw $XAY \| BC$.

Now, $XY \| MP \| NQ$ are cut by the transversal $AB$ at $A, M, N$ respectively such that $AM = MN$.

Also, $XY \| MP \| NQ$ are cut by the transversal $AC$ at $A, P, Q$ respectively.

$\therefore AP = PQ$ ... (i) (by intercept theorem).

Again, $MP \| NQ \| BC$ are cut by the transversal $AB$ at $M, N, B$ respectively such that $MN = NB$.

Also, $MP \| NQ \| BC$ are cut by the transversal $AC$ at $P, Q, C$ respectively.

$\therefore PQ = QC$ ... (ii) (by intercept theorem).

Thus, from (i) and (ii), we get $AP = PQ = QC$.

Hence, $P$ and $Q$ divide $AC$ into three equal parts.

---
### Example 3

$E$ and $F$ are respectively the midpoints of nonparallel sides $AD$ and $BC$ of a trapezium $ABCD$. Prove that $EF \| AB$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-38.jpg?height=180&width=326&top_left_y=1733&top_left_x=869)

Let $ABCD$ be a trapezium in which $AB \| DC$. Let $E$ and $F$ be the midpoints of $AD$ and $BC$ respectively. $E$ and $F$ are joined.

We have to show that $EF \| AB$.

If possible, let $EF$ be not parallel to $AB$ then draw $EG \| AB$, meeting $BC$ at $G$.

Now, $AB \| EG \| DC$ and the transversal $AD$ cuts them at $A, E, D$ respectively such that $AE = ED$.

Also, $BGC$ is the other transversal cutting $AB, EG$ and $DC$ at $B, G$ and $C$ respectively.

$\therefore BG = GC$ (by intercept theorem).

This shows that $G$ is the midpoint of $BC$.

Hence, $G$ must coincide with $F$ [$\because F$ is the midpoint of $BC$].

Thus, our supposition is wrong.

Hence, $EF \| AB$.

---
### Example 4

Prove that any line segment drawn from the vertex of a triangle to the base is bisected by the line segment joining the midpoints of the other sides of the triangle.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-39.jpg?height=188&width=307&top_left_y=950&top_left_x=890)

Let $\triangle ABC$ be a given triangle in which $E$ and $F$ are the midpoints of $AB$ and $AC$ respectively. Let $AL$ be a line segment drawn from vertex $A$ to the base $BC$, meeting $BC$ at $L$ and $EF$ at $M$.

We have to show that $AM = ML$.

Through $A$, draw $PAQ \| BC$.

In $\triangle ABC$; $E$ and $F$ being the midpoints of $AB$ and $AC$ respectively, we have $EF \| BC$.

Now, $PAQ, EF$ and $BC$ are three parallel lines such that the intercepts $AE$ and $EB$ made by them on transversal $AEB$ are equal.

$\therefore$ the intercepts $AM$ and $ML$ made by them on transversal $AML$ must be equal.

Hence, $AM = ML$.

---
### Example 5

In the adjoining figure, the side $AC$ of $\triangle ABC$ is produced to $E$ such that $CE = \frac{1}{2} AC$. If $D$ is the midpoint of $BC$ and $ED$ produced meets $AB$ at $F$, and $CP, DQ$ are drawn parallel to $BA$, prove that $FD = \frac{1}{3} FE$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_2884ef595d718654ac8bg-40.jpg?height=272&width=350&top_left_y=167&top_left_x=849)

In $\triangle ABC$, $D$ is the midpoint of $BC$ and $DQ \| BA$.

$\therefore Q$ is the midpoint of $AC$.

$\therefore AQ = QC$.

Now, $FA \| DQ \| PC$, and $AQC$ is the transversal such that $AQ = QC$ and $FDP$ is the other transversal on them.

$\therefore FD = DP$ ... (i) (by intercept theorem).

Now, $EC = \frac{1}{2} AC = QC$.

$\therefore$ in $\triangle EQD$, $C$ is the midpoint of $EQ$ and $CP \| DQ$.

$\therefore P$ must be the midpoint of $DE$.

$\therefore DP = PE$ ... (ii)

Thus, $FD = DP = PE$ [from (i) and (ii)].

Hence, $FD = \frac{1}{3} FE$.

---
