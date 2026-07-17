## INEQUALITIES IN A TRIANGLE

### THEOREM 1
*If two sides of a triangle are unequal, prove that the angle opposite to the longer side is greater.*

**GIVEN** A $\triangle ABC$ in which $AC > AB$.

**TO PROVE** $\angle ABC > \angle BCA$.

**CONSTRUCTION** Mark a point $D$ on $AC$ such that $AD = AB$. Join $BD$.

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-26.jpg?height=200&width=332&top_left_y=1645&top_left_x=865)

**PROOF** We know that in a triangle, the angles opposite to equal sides are equal.

So, in $\triangle ABD$, we have

$$
A B=A D \Rightarrow \angle B D A=\angle A B D . \tag{i}
$$

Now, in $\triangle BCD$, side $CD$ has been produced to $A$, forming exterior angle $\angle BDA$.

$\therefore \quad \angle BDA > \angle BCD$ [exterior angle is greater than int. opp. angle]

$\Rightarrow \angle BDA > \angle BCA$ $[\because \angle BCD = \angle BCA]$

$\Rightarrow \quad \angle ABD > \angle BCA$ [using (i)]

Now, $\angle ABC > \angle ABD$.

$\therefore \quad \angle ABC > \angle BCA$.

Hence, $\angle ABC > \angle BCA$.

---

### THEOREM 2
*In any triangle, prove that the side opposite to the greater angle is longer.*

**GIVEN** A $\triangle ABC$ in which $\angle ABC > \angle ACB$.

**TO PROVE** $AC > AB$.

**PROOF** We have the following possibilities only.
- (i) $AC = AB$
- (ii) $AC < AB$
- (iii) $AC > AB$

Out of these possibilities, exactly one must be true.

#### CASE I

If possible, let $AC = AB$.
We know that the angles opposite to equal sides of a triangle are equal.
$\therefore \quad AC = AB \Rightarrow \angle ABC = \angle ACB$.
This contradicts the given hypothesis that $\angle ABC > \angle ACB$.
$\therefore \quad AC \neq AB$.

#### CASE II

If possible, let $AC < AB$. Then, $AB > AC$.
Since the angle opposite to the longer side is larger, so
$$
A B>A C \Rightarrow \angle A C B>\angle A B C .
$$
This contradicts the given hypothesis that $\angle ABC > \angle ACB$.
$\therefore \quad AC$ cannot be less than $AB$.

#### CASE III

Now, we are left with the only possibility that $AC > AB$, which must be true.

Hence, $AC > AB$.

---

### THEOREM 3
*Prove that, of all the line segments that can be drawn to a given line, from a point not lying on it, the perpendicular line segment is the shortest.*

**GIVEN** A line $AB$ and a point $P$ outside it. $PM \perp AB$ and $N$ is a point, other than $M$, on $AB$.

**TO PROVE** $PM < PN$.

**PROOF** In $\triangle PMN$, we have $\angle M=90^{\circ}$.

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-28.jpg?height=188&width=324&top_left_y=169&top_left_x=875)

But, in a right-angled triangle, each one of the angles other than the right angle is an acute angle.
$\therefore \quad \angle PNM < \angle PMN$.
But, the side opposite to the smaller angle in a triangle is shorter.
$\therefore \quad PM < PN$.
Hence, the perpendicular from $P$ to the given line is shortest of all line segments from $P$ to $AB$.

---

## DISTANCE BETWEEN A LINE AND A POINT

The distance between a line and a point, not on it, is the length of perpendicular from the point to the given line.

**NOTE** The distance between a line and a point lying on it, is zero.

---

### THEOREM 4
*Prove that the sum of any two sides of a triangle is greater than the third side.*

**GIVEN** A $\triangle ABC$.

**TO PROVE**
- (i) $AB + AC > BC$
- (ii) $AB + BC > AC$
- (iii) $BC + AC > AB$

**CONSTRUCTION** Produce $BA$ to $D$ such that $AD = AC$. Join CD.

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-28.jpg?height=283&width=229&top_left_y=1047&top_left_x=968)

**PROOF** (i) In $\triangle ACD$, we have
$$
\begin{array}{rll}
& AD=AC & [\text { by construction }] \\
\Rightarrow & \angle ACD=\angle ADC & {[\text {angles opposite to equal sides }]} \\
\end{array}
$$
Now, $\angle BCD = \angle BCA + \angle ACD$.
$\therefore \quad \angle BCD > \angle ACD$.
$$
\begin{array}{rll}
\Rightarrow & \angle BCD>\angle ADC & {[\because \angle ACD = \angle ADC]} \\
\Rightarrow & \angle BCD>\angle BDC & {[\because \angle ADC=\angle BDC]} \\
\Rightarrow & BD>BC & {[\text { side opposite to larger angle is larger] }} \\
\Rightarrow & BA+AD>BC & \\
\Rightarrow & BA+AC>BC & {[\because AD=AC]} \\
\therefore & AB+AC>BC . &
\end{array}
$$
Similarly, $AB+BC > AC$ and $BC+AC > AB$.

---

### THEOREM 5
*Prove that the difference between any two sides of a triangle is less than its third side.*

**GIVEN** A $\triangle ABC$.

**TO PROVE**
- (i) $AC - AB < BC$
- (ii) $BC - AC < AB$
- (iii) $BC - AB < AC$

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-29.jpg?height=168&width=318&top_left_y=173&top_left_x=873)

**CONSTRUCTION** Let $AC > AB$. Then, along $AC$, set off $AD = AB$. Join $BD$.

**PROOF** $AB=AD \Rightarrow \angle 1 = \angle 2$.

Side $CD$ of $\triangle BCD$ has been produced to $A$.
$\therefore \quad \angle 2 > \angle 4$ ... (ii) [$\because$ ext. angle $>$ each int. opp. angle].

Side $BD$ of $\triangle ABD$ has been produced to $C$.
$\therefore \quad \angle 3 > \angle 1$ ... (iii) [ext. angle $>$ each int. opp. angle]
$\Rightarrow \quad \angle 3 > \angle 2$ ... (iv) [using (i)].

From (ii) and (iv), we get $\angle 3 > \angle 4 \Rightarrow \angle 4 < \angle 3$.

Now, $\angle 4 < \angle 3$
$\Rightarrow \quad CD < BC$
$\Rightarrow AC - AD < BC$
$\Rightarrow AC - AB < BC \quad [\because AD = AB]$.

Hence, $AC - AB < BC$.
Similarly, $BC - AC < AB$ and $BC - AB < AC$.

---

### THEOREM 6
*Prove that the sum of any two sides of a triangle is greater than twice the median drawn to the third side.*

**GIVEN** A $\triangle ABC$ in which $AD$ is a median.

**TO PROVE** $AB + AC > 2AD$.

**CONSTRUCTION** Produce $AD$ to $E$ such that $AD = DE$. Join $EC$.

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-29.jpg?height=309&width=370&top_left_y=1095&top_left_x=825)

**PROOF** In $\triangle ADB$ and $\triangle EDC$, we have
$AD = DE$ (by construction)
$\angle ADB = \angle EDC$ (vert. opp. angles)
$BD = CD$ ($\because D$ is the midpoint of $BC$)

$\therefore \quad \triangle ADB \cong \triangle EDC$ (by SAS-criteria).
$\therefore \quad AB = EC$ (c.p.c.t.).

We know that the sum of any two sides of a triangle is greater than the third side. So, in $\triangle ACE$, we have
$EC + AC > AE$.
$\Rightarrow \quad AB + AC > AE \quad [\because EC = AB]$
$\Rightarrow \quad AB + AC > 2AD \quad [\because AE = AD + DE = AD + AD = 2AD]$.

Hence, $AB + AC > 2AD$.

---

## SOLVED EXAMPLES

### Example 1:

In a $\triangle ABC$, if $\angle A = 40^{\circ}$ and $\angle B = 60^{\circ}$ then which side of the triangle is longest and which is shortest?

#### Solution:

Here, $\angle A = 40^{\circ}$ and $\angle B = 60^{\circ}$.
$\therefore \angle C = 180^{\circ} - (40^{\circ} + 60^{\circ}) = 80^{\circ}$.

Thus, $\angle C$ is largest and $\angle A$ is smallest.
So, the side opposite to $\angle C$ is longest.
Hence, the **longest side is AB**.

Also, the side opposite to $\angle A$ is shortest.
$\therefore \quad BC$ is the **shortest side**.

---

### Example 2:

In a right-angled triangle, prove that the hypotenuse is the longest side.

#### Solution:

Let $ABC$ be a right triangle in which $\angle B = 90^{\circ}$.
Then, $\angle A + \angle C = 90^{\circ}$.
$\therefore \quad \angle B > \angle A$ and $\angle B > \angle C$.

$\Rightarrow AC > BC$ and $AC > AB$ [side opp. to larger angle is longer].
$\therefore \quad AC$ is the longest side.

Hence, in a right triangle, the hypotenuse is the longest side.

---

### Example 3:

Show that the sum of three altitudes of a triangle is less than the sum of the three sides of the triangle.

#### Solution:

Let $AL, BM, CN$ be the three altitudes of $\triangle ABC$.
We know that, of all line segments drawn from a point outside a line to the line, the perpendicular is the shortest.
![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-30.jpg?height=252&width=257&top_left_y=1329&top_left_x=938)

$\therefore \quad AL < AB$, $BM < BC$ and $CN < AC$.
Adding these inequalities, we get:
$AL + BM + CN < AB + BC + AC$.

---

### Example 4:

Prove that the perimeter of a triangle is greater than the sum of its three medians.

#### Solution:

Let $AD, BE$ and $CF$ be the three medians of a $\triangle ABC$.
![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-30.jpg?height=221&width=370&top_left_y=1695&top_left_x=825)

We know that the sum of any two sides of a triangle is greater than twice the median drawn to the third side.
$$
\begin{align*}
\therefore \quad AB+AC & >2 AD,  \tag{i}\\
A B+B C & >2 B E,  \tag{ii}\\
\text { and } B C+A C & >2 C F . \tag{iii}
\end{align*}
$$
Adding the corresponding sides of (i), (ii) and (iii), we get
$$
\begin{aligned}
& 2(A B+B C+A C)>2(A D+B E+C F) \\
\therefore \quad & (A B+B C+A C)>(A D+B E+C F) .
\end{aligned}
$$
Hence, the perimeter of a triangle is greater than the sum of its three medians.

---

### Example 5:

In the adjoining figure, $ABC$ is a triangle and $D$ is any point in its interior. Show that $(BD + DC) < (AB + AC)$.

#### Solution:

Produce $BD$ to meet $AC$ at $E$.
![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-31.jpg?height=186&width=350&top_left_y=600&top_left_x=845)

We know that in a triangle, the sum of any two sides is always greater than the third side.
In $\triangle ABE$, we have
$$
A B+A E>B E \Rightarrow A B+A E>B D+D E . \tag{i}
$$
In $\triangle CDE$, we have
$$
D E+E C>D C . \tag{ii}
$$
Adding (i) and (ii), we get
$$
\begin{aligned}
& A B+A E+D E+E C>B D+D E+D C \\
\Rightarrow \quad & A B+(A E+E C)>B D+D C \\
\Rightarrow \quad & (A B+A C)>(B D+D C) .
\end{aligned}
$$
Hence, $(BD + DC) < (AB + AC)$.

---

### Example 6:

In the given figure, $AP \perp QR$, $PR > PQ$ and $PQ = PS$. Show that $AR > AQ$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-31.jpg?height=221&width=398&top_left_y=1409&top_left_x=797)

In $\triangle APQ$ and $\triangle APS$, we have
- $PQ = PS$ (given)
- $\angle APQ = \angle APS$ (each equal to $90^{\circ}$)
- $AP = AP$ (common)

$\therefore \quad \triangle APQ \cong \triangle APS$ (SAS-criteria).
$\therefore \quad \angle AQP = \angle ASP \Rightarrow \angle AQS = \angle ASQ$. (i)

Now, side $RS$ of $\triangle ARS$ has been produced to $Q$.
$\therefore \quad \angle ASQ > \angle ARS$ [ext. angle > int. opp. angle]
$\Rightarrow \angle AQS > \angle ARS$ [using (i)]
$\Rightarrow \angle AQR > \angle ARQ$
$\Rightarrow AR > AQ$ [the side opposite to greater angle is larger].

Hence, $AR > AQ$.

---

### Example 7:

In the given figure, $O$ is the centre of the circle and $XOY$ is a diameter. If $XZ$ is any other chord, show that $XY > XZ$.

**GIVEN** A circle with centre $O$ in which $XOY$ is a diameter and $XZ$ is another chord.
![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-32.jpg?height=215&width=229&top_left_y=523&top_left_x=966)

**TO PROVE** $XY > XZ$.

**CONSTRUCTION** Join $OZ$.

#### Solution:

We know that in a triangle, the sum of any two sides is always greater than the third side.
So, in $\triangle XOZ$, we have
$$
\begin{array}{rlr}
& X O+O Z>X Z & \\
\Rightarrow & X O+O Y>X Z & {[\because O Z=O Y=\text { radius of the circle }]} \\
\Rightarrow & X Y>X Z & {[\because X O+O Y=X Y]}
\end{array}
$$
Hence, $XY > XZ$.

---

### Example 8:

In $\triangle ABC$, if $D$ is any point on the side $BC$, show that $(AB + BC + AC) > 2AD$.

**GIVEN** A $\triangle ABC$ in which $D$ is a point on $BC$ and $AD$ is drawn.

**TO PROVE** $(AB + BC + AC) > 2AD$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-32.jpg?height=224&width=330&top_left_y=1216&top_left_x=869)

We know that in a triangle, the sum of any two sides is always greater than the third side.
So, in $\triangle ABD$, we have $AB + BD > AD$. (i)

And, in $\triangle ACD$, we have $AC + CD > AD$. (ii)

Adding the corresponding sides of (i) and (ii), we get
$$
\begin{aligned}
& (AB + AC) + (BD + CD) > 2 AD \\
\Rightarrow \quad & AB + AC + BC > 2 AD \quad [\because BD + CD = BC] .
\end{aligned}
$$
Hence, $(AB + BC + AC) > 2AD$.

---

### Example 9:

In $\triangle ABC$, if $AD$ is the bisector of $\angle A$, show that $AB > BD$ and $AC > DC$.

**GIVEN** A $\triangle ABC$ in which $AD$ is the bisector of $\angle A$.

**TO PROVE** $AB > BD$ and $AC > DC$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-33.jpg?height=216&width=322&top_left_y=177&top_left_x=873)

In $\triangle ACD$, side $CD$ has been produced to $B$.
$\therefore \quad$ ext. $\angle ADB >$ int. opp. $\angle CAD$
$\Rightarrow \quad \angle ADB > \angle CAD$
$\Rightarrow \quad \angle ADB > \angle BAD \quad [\because \angle CAD = \angle BAD]$
$\Rightarrow \quad AB > BD \quad$ [side opposite to larger angle is larger].

Again, in $\triangle ABD$, the side $BD$ has been produced to $C$.
$\therefore \quad$ ext. $\angle ADC >$ int. opp. $\angle BAD$
$\Rightarrow \quad \angle ADC > \angle BAD$
$\Rightarrow \quad \angle ADC > \angle CAD \quad [\because \angle BAD = \angle CAD]$
$\Rightarrow \quad AC > DC \quad$ [side opposite to larger angle is larger].

Hence, $AB > BD$ and $AC > DC$.

---

### Example 10:

In the given figure, $AB > AC$. If $D$ is any point on $BC$, show that $AB > AD$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-33.jpg?height=220&width=269&top_left_y=918&top_left_x=926)

We know that the angle opposite to the larger side is larger.
$$
\begin{aligned}
\therefore \quad AB > AC & \Rightarrow \angle ACB > \angle ABC \\
& \Rightarrow \angle ACD > \angle ABD . \quad \text{(i)}
\end{aligned}
$$
Again, side $CD$ of $\triangle ACD$ has been produced to $B$.
$$
\therefore \quad \text { ext. } \angle ADB > \angle ACD . \tag{ii}
$$
From (i) and (ii), we get
$$
\begin{aligned}
& \angle ADB > \angle ACD > \angle ABD \\
\Rightarrow \quad & \angle ADB > \angle ABD
\end{aligned}
$$
$\Rightarrow \quad AB > AD \quad$ [side opposite to larger angle is larger].

Hence, $AB > AD$.

---

### Example 11:

In the given figure, $AC > AB$ and $AD$ is the bisector of $\angle A$. Show that $\angle ADC > \angle ADB$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-33.jpg?height=227&width=322&top_left_y=1566&top_left_x=873)

Given $AC > AB$.
$\Rightarrow \quad \angle B > \angle C$ (angle opposite to larger side is greater).

Let $\angle BAD = \angle CAD = \angle 1$.
In $\triangle ABD$, the exterior angle at $D$ is $\angle ADC$.
$\therefore \quad \angle ADC = \angle B + \angle 1$.

In $\triangle ACD$, the exterior angle at $D$ is $\angle ADB$.
$\therefore \quad \angle ADB = \angle C + \angle 1$.

Since $\angle B > \angle C$, it follows that $\angle B + \angle 1 > \angle C + \angle 1$.
$\Rightarrow \quad \angle ADC > \angle ADB$.

---

### Example 12:

In the given figure, the sides $AB$ and $AC$ of $\triangle ABC$ have been extended to $D$ and $E$ respectively. If $x > y$, show that $AB > AC$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-34.jpg?height=324&width=277&top_left_y=168&top_left_x=920)

We are given $x > y$.
$\angle ABC = 180^{\circ} - x$
$\angle ACB = 180^{\circ} - y$

Since $x > y$,
$\Rightarrow -x < -y$
$\Rightarrow (180 - x) < (180 - y)$
$\Rightarrow \angle ABC < \angle ACB$
$\Rightarrow \angle ACB > \angle ABC$

$\Rightarrow AB > AC$ [side opposite to larger angle is larger].

Hence, $AB > AC$.

---

### Example 13:

In the given figure, $Q$ is a point on the side $SR$ of $\triangle PSR$ such that $PQ = PR$. Prove that $PS > PQ$.

#### Solution:

![](https://cdn.mathpix.com/cropped/2025_09_25_6efc6062a3fff7670a58g-34.jpg?height=222&width=320&top_left_y=636&top_left_x=879)

We know that the angles opposite to equal sides are equal.
$$
\therefore \quad P Q=P R \Rightarrow \angle P Q R=\angle P R Q . \tag{i}
$$
In $\triangle PSQ$, the side $SQ$ has been produced to $R$.
$\therefore \quad \angle PQR > \angle PSQ$ [exterior angle is greater than int. opp. $\angle$s]
$\Rightarrow \quad \angle PRQ > \angle PSQ \quad$ [using (i)]
$\Rightarrow \quad \angle PRS > \angle PSR \quad [\because \angle PRQ = \angle PRS$ and $\angle PSQ = \angle PSR]$
$\Rightarrow \quad PS > PR$
$\Rightarrow \quad PS > PQ \quad [\because PQ = PR]$.

Hence, $PS > PQ$.

---

 $BD+DE > BE$. Therefore, $(AB+AC) > BE$.