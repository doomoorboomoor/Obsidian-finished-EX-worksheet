## Results on Cyclic Quadrilaterals

### Theorem 1

*The sum of either pair of the opposite angles of a cyclic quadrilateral is $180^{\circ}$. Or, the opposite angles of a cyclic quadrilateral are supplementary.*

**GIVEN:** A cyclic quadrilateral $ABCD$.

**TO PROVE:** $\angle A+\angle C=180^{\circ}$ and $\angle B+\angle D=180^{\circ}$.

**CONSTRUCTION:** Join $AC$ and $BD$.

**PROOF:** We have
$$
\begin{align*}
\angle ACB &= \angle ADB \quad [\text{Angles in the same segment}] \\
\text{and } \angle BAC &= \angle BDC \quad [\text{Angles in the same segment}]. \\
\therefore \angle ACB + \angle BAC &= \angle ADB + \angle BDC \\
\Rightarrow \angle ACB + \angle BAC &= \angle ADC \\
\Rightarrow \angle ACB + \angle BAC + \angle ABC &= \angle ADC + \angle ABC \quad [\text{adding } \angle ABC \text{ on both sides}] \\
\Rightarrow \angle ADC + \angle ABC &= 180^{\circ} \quad [\text{the sum of the angles of } \triangle ABC \text{ is } 180^{\circ}] \\
\Rightarrow \angle B + \angle D &= 180^{\circ}. \quad \text{(i)}
\end{align*}
$$

Now, $\angle A+\angle B+\angle C+\angle D=360^{\circ}$.

$\Rightarrow \angle A+\angle C=360^{\circ}-(\angle B+\angle D)=360^{\circ}-180^{\circ}=180^{\circ}$ [using (i)].

Hence, $\angle A+\angle C=180^{\circ}$ and $\angle B+\angle D=180^{\circ}$.

---

### Theorem 2 (Converse of Theorem 1)

*If a pair of opposite angles of a quadrilateral is supplementary then the quadrilateral is cyclic.*

**GIVEN:** A quadrilateral $ABCD$ in which $\angle B+\angle D=180^{\circ}$.

**TO PROVE:** $ABCD$ is a cyclic quadrilateral.

**CONSTRUCTION:** If possible, let $ABCD$ be not a cyclic quadrilateral. Draw a circle, passing through three noncollinear points $A, B, C$. Let this circle meet $CD$ or $CD$ produced in $D^{\prime}$. Join $D^{\prime}A$.

**PROOF:**
$\angle ABC+\angle ADC=180^{\circ}$ [given]
$\angle ABC+\angle AD'C=180^{\circ}$ [opposite angles of a cyclic quad.]

$\therefore \quad \angle ABC+\angle ADC=\angle ABC+\angle AD'C$
$\Rightarrow \quad \angle ADC=\angle AD'C$.

This is not possible, since an exterior angle of a triangle can never be equal to its interior opposite angle.
So, $\angle ADC=\angle AD'C$ is possible only when $D'$ coincides with $D$.
Hence, the circle passing through $A, B, C$ must pass through $D$ also.
Hence, $ABCD$ is a cyclic quadrilateral.

---

### Theorem 3 (Exterior-angle property of a cyclic quadrilateral)

*If one side of a cyclic quadrilateral is produced then the exterior angle so formed is equal to the interior opposite angle.*

**GIVEN:** A cyclic quadrilateral $ABCD$ whose side $AB$ is produced to $E$.

**TO PROVE:** $\angle CBE=\angle ADC$.

**PROOF:** We have
$\angle ABC+\angle CBE=180^{\circ}$ [linear pair]
and $\angle ABC+\angle ADC=180^{\circ}$ [opposite angles of a cyclic quad.].

$\therefore \quad \angle ABC+\angle CBE=\angle ABC+\angle ADC$
$\Rightarrow \quad \angle CBE=\angle ADC$.

Hence, $\angle CBE=\angle ADC$.

---

## Summary of the Results

1.  The opposite angles of a cyclic quadrilateral are supplementary.
2.  If a pair of opposite angles of a quadrilateral is supplementary then the quadrilateral is cyclic.
3.  If one side of a cyclic quadrilateral is produced, then the exterior angle so formed is equal to the interior opposite angle.

---

## Solved Examples

### Example 1

In the given figure, $ABCD$ is a cyclic quadrilateral in which $AB \| DC$. If $\angle BAD=100^{\circ}$, find
(i) $\angle BCD$,
(ii) $\angle ADC$,
(iii) $\angle ABC$.

#### Solution:

(i) We know that the opposite angles of a cyclic quadrilateral are supplementary.
$\therefore \quad \angle BAD+\angle BCD=180^{\circ}$
$\Rightarrow 100^{\circ}+\angle BCD=180^{\circ}$
$\Rightarrow \angle BCD=180^{\circ}-100^{\circ}=80^{\circ}$.

(ii) $AB \| DC$ and $DA$ is the transversal.
$\therefore \quad \angle ADC+\angle BAD=180^{\circ} \quad$ [sum of int. opp. angles]
$\Rightarrow \angle ADC+100^{\circ}=180^{\circ}$
$\Rightarrow \angle ADC=180^{\circ}-100^{\circ}=80^{\circ}$.

(iii) Using the fact that the opposite angles of a cyclic quadrilateral are supplementary, we have
$$
\begin{align*}
& \angle ABC+\angle ADC=180^{\circ} \\
\Rightarrow & \angle ABC+80^{\circ}=180^{\circ} \quad [\because \angle ADC=80^{\circ}] \\
\Rightarrow & \angle ABC=180^{\circ}-80^{\circ}=100^{\circ}.
\end{align*}
$$
$\therefore \angle BCD=80^{\circ}, \angle ADC=80^{\circ}$ and $\angle ABC=100^{\circ}$.

---

### Example 2

In the given figure, $ABCD$ is a cyclic quadrilateral in which $\angle A=(2x+4)^{\circ}$, $\angle B=(x+10)^{\circ}$, $\angle C=(4y-4)^{\circ}$ and $\angle D=(5y+5)^{\circ}$. Find the values of $x$ and $y$. Hence, find the measure of each angle.

#### Solution:

We know that the opposite angles of a cyclic quadrilateral are supplementary.
$\therefore \angle A+\angle C=180^{\circ}$ and $\angle B+\angle D=180^{\circ}$

$\Rightarrow (2x+4)+(4y-4)=180$ and $(x+10)+(5y+5)=180$
$\Rightarrow 2x+4y=180$ and $x+5y=165$
$\Rightarrow x+2y=90 \quad \ldots \text{(i)}$ and $x+5y=165 \quad \ldots \text{(ii)}$

On solving (i) and (ii), we get $x=40$ and $y=25$.

$\therefore \angle A=(2 \times 40+4)^{\circ}=84^{\circ}$, $\angle B=(40^{\circ}+10^{\circ})=50^{\circ}$
$\angle C=(4 \times 25-4)^{\circ}=96^{\circ}$ and $\angle D=(5 \times 25+5)^{\circ}=130^{\circ}$.

---

### Example 3

In the given figure, $O$ is the centre of a circle and $\angle ADC=130^{\circ}$. If $\angle BAC=x^{\circ}$, then find the value of $x$.

#### Solution:

Since $ABCD$ is a cyclic quadrilateral, we have
$$
\begin{align*}
& \angle ABC+\angle ADC=180^{\circ} \\
\Rightarrow & \angle ABC+130^{\circ}=180^{\circ} \\
\Rightarrow & \angle ABC=180^{\circ}-130^{\circ}=50^{\circ}.
\end{align*}
$$
Also, $\angle ACB=90^{\circ} \quad$ [angle in a semicircle].
We know that the sum of the angles of a triangle is $180^{\circ}$.
$\therefore \quad$ in $\triangle ABC$, we have $\angle BAC+\angle ACB+\angle ABC=180^{\circ}$
$\Rightarrow x+90+50=180 \Rightarrow x=180-140=40$.

Hence, $x=40$.

---

### Example 4

In the given figure, $O$ is the centre of a circle and $\angle AOC=140^{\circ}$. Find $\angle ABC$.

#### Solution:

Take a point $D$ on the remaining part of the circumference. Join $DA$ and $DC$, as shown in the figure.

We know that the angle at the centre of a circle is twice the angle at any point on the remaining part of the circumference.
$\therefore \quad \angle ADC=\frac{1}{2} \angle AOC=\left(\frac{1}{2} \times 140^{\circ}\right)=70^{\circ}$.

We know that the opposite angles of a cyclic quadrilateral are supplementary.
$\therefore$ from cyclic quadrilateral $ABCD$, we have
$$
\angle ABC+\angle ADC=180^{\circ}
$$
$\Rightarrow \quad \angle ABC+70^{\circ}=180^{\circ}$
$\Rightarrow \angle ABC=180^{\circ}-70^{\circ}=110^{\circ}$.

Hence, $\angle ABC=110^{\circ}$.

---

### Example 5

In the given figure, $O$ is the centre of a circle, $\angle AOC=110^{\circ}$ and side $AB$ has been produced to a point $D$. Find $\angle CBD$.

#### Solution:

Take a point $E$ on the remaining part of the circumference. Join $EA$ and $EC$.

We know that the angle subtended by an arc at the centre of a circle is twice the angle subtended at a point on the remaining part of the circumference.
$\therefore \quad \angle AEC=\frac{1}{2} \angle AOC=\left(\frac{1}{2} \times 110^{\circ}\right)=55^{\circ}$.

Now, $ABCE$ is a cyclic quadrilateral whose side $AB$ has been produced to a point $D$.
But, the exterior angle of a cyclic quadrilateral is equal to its interior opposite angle.
$\therefore \angle CBD=\angle AEC=55^{\circ}$.

Hence, $\angle CBD=55^{\circ}$.

---

### Example 6

In the given figure, $ABCD$ is a cyclic quadrilateral whose diagonals intersect at a point $E$. If $\angle DBC=70^{\circ}$ and $\angle BAC=30^{\circ}$, find $\angle BCD$. Further, if $AB=BC$, find $\angle ECD$.

#### Solution:

We have
$$
\angle BDC=\angle BAC=30^{\circ} \quad [\text{angles in the same segment}]
$$
Now, in $\triangle BCD$, we have
$$
\begin{align*}
& \angle DBC+\angle BCD+\angle BDC=180^{\circ} \quad [\because \text{sum of the angles of a } \triangle \text{ is } 180^{\circ}] \\
\Rightarrow \quad & 70^{\circ}+\angle BCD+30^{\circ}=180^{\circ} \\
\Rightarrow \quad & \angle BCD=180^{\circ}-100^{\circ}=80^{\circ}.
\end{align*}
$$
Now, $AB=BC \Rightarrow \angle BCA=\angle BAC=30^{\circ}$.
$\therefore \quad \angle ECD=\angle BCD-\angle BCA=80^{\circ}-30^{\circ}=50^{\circ}$.

---

### Example 7

In an isosceles $\triangle ABC$ with $AB=AC$, a circle passing through $B$ and $C$ intersects the sides $AB$ and $AC$ at $D$ and $E$ respectively. Prove that $DE \| BC$.

#### Solution:

$$
\begin{align*}
AB=AC \Rightarrow \angle ABC=\angle ACB. \quad \text{(i)}
\end{align*}
$$
Side $BD$ of the cyclic quadrilateral $BCED$ is produced to $A$.
$$
\therefore \quad \angle ADE = \angle ACB \quad \ldots \text{(ii)} \quad [\text{ext. } \angle ADE = \text{int. opp. } \angle C].
$$
From (i) and (ii), we get
$$
\angle ABC=\angle ADE.
$$
But, these are corresponding angles.
Hence, $DE \| BC$.

---

### Example 8

In the given figure, $ABCD$ is a parallelogram. The circle through $A, B, C$ intersects $CD$ produced at $E$. Prove that $AD=AE$.

#### Solution:

It is given that $ABCE$ is a cyclic quadrilateral.
$\therefore \quad \angle ABC+\angle AED=180^{\circ}$. (i)

Also, $EDC$ is a straight line.
$\therefore \quad \angle ADE+\angle ADC=180^{\circ}$.

But, $\angle ADC=\angle ABC \quad$ [opposite angles of a parallelogram].
$\therefore \quad \angle ADE+\angle ABC=180^{\circ}$. (ii)

Thus, $\angle ABC+\angle AED=\angle ADE+\angle ABC \quad$ [from (i) and (ii)]
$\Rightarrow \quad \angle AED=\angle ADE$
$\Rightarrow AD=AE \quad$ [opposite sides of equal angles of $\triangle ADE$]

Hence, $AD=AE$.

---

### Example 9

In the given figure, $\angle A=60^{\circ}$ and $\angle ABC=80^{\circ}$. Find (i) $\angle DPC$ and (ii) $\angle BQC$.

#### Solution:

(i) Side $AD$ of cyclic quad. $ABCD$ has been produced to $P$.
$\therefore \quad \angle PDC=\angle ABC=80^{\circ} \quad [\because \text{ext. } \angle PDC = \text{int. opp } \angle ABC]$.

Again, side $BC$ of quad. $ABCD$ has been produced to $P$.
$\therefore \angle PCD=\angle BAD=60^{\circ} \quad [\because \text{ext. } \angle PCD = \text{int. opp } \angle BAD]$.

In $\triangle PCD$, we have
$\angle PDC+\angle PCD+\angle DPC=180^{\circ} \quad [\because \text{sum of the angles of a } \triangle \text{ is } 180^{\circ}]$.
$\Rightarrow 80^{\circ}+60^{\circ}+\angle DPC=180^{\circ}$
$\Rightarrow \angle DPC=180^{\circ}-140^{\circ}=40^{\circ}$.

Hence, $\angle DPC=40^{\circ}$.

(ii) Since $ABCD$ is a cyclic quadrilateral, we have
$$
\begin{align*}
& \angle ABC+\angle ADC=180^{\circ} \\
\Rightarrow & 80^{\circ}+\angle ADC=180^{\circ} \\
\Rightarrow & \angle ADC=180^{\circ}-80^{\circ}=100^{\circ}.
\end{align*}
$$
Again, side $DC$ of cyclic quad. $ABCD$ is produced to $Q$.
$\therefore \quad \angle QCB=\angle BAD=60^{\circ} \quad [\because \text{ext. } \angle QCB = \text{int. opp. } \angle BAD]$.

Also, side $AB$ of cyclic quad. $ABCD$ has been produced to $Q$.
$\therefore \quad \angle QBC=\angle ADC=100^{\circ} \quad [\because \text{ext. } \angle QBC = \text{int. opp. } \angle ADC]$.

We know that the sum of the angles of a triangle is $180^{\circ}$. In $\triangle QCB$, we have
$$
\begin{align*}
& \angle QCB+\angle QBC+\angle BQC=180^{\circ} \\
\Rightarrow \quad & 60^{\circ}+100^{\circ}+\angle BQC=180^{\circ} \\
\Rightarrow \quad & \angle BQC=180^{\circ}-160^{\circ}=20^{\circ}
\end{align*}
$$
Hence, $\angle BQC=20^{\circ}$.

---

### Example 10

The bisectors of opposite angles $\angle P$ and $\angle R$ of a cyclic quadrilateral $PQRS$ intersect the corresponding circle at $A$ and $B$ respectively. Prove that $AB$ is a diameter of the circle.

#### Solution:

**GIVEN:** A cyclic quad. $PQRS$ in which $PA$ and $RB$ are the bisectors of $\angle P$ and $\angle R$ respectively.

**TO PROVE:** $AB$ is a diameter of the circle which passes through the points $P, Q, R$ and $S$.

**CONSTRUCTION:** Join $PB$ and $BS$.

**PROOF:** Since $PQRS$ is a cyclic quadrilateral, we have
$$
\begin{align*}
& \angle QPS+\angle QRS=180^{\circ} \\
\Rightarrow & \frac{1}{2} \angle QPS+\frac{1}{2} \angle QRS=90^{\circ} \\
\Rightarrow & \angle APS+\angle BRS=90^{\circ} \\
\Rightarrow & \angle APS+\angle BPS=90^{\circ} \quad [\because \angle BRS=\angle BPS, \text{angles in the same segment}] \\
\Rightarrow & \angle APB=90^{\circ} \quad [\because \angle APS+\angle BPS=\angle APB] \\
\Rightarrow & \angle APB \text{ is in a semicircle}
\end{align*}
$$
$\Rightarrow \quad AB$ is a diameter of the circle which passes through the points $P, Q, R$ and $S$.

Hence, $AB$ is a diameter of the circle.

---

### Example 11

In the given figure, $AC$ is a diameter of a circle with centre $O$. If $CD \| BE$, $\angle AOB=80^{\circ}$ and $\angle ACE=10^{\circ}$, find (i) $\angle BEC$, (ii) $\angle BCD$ and (iii) $\angle CED$.

#### Solution:

(i) Since $AOC$ is a straight line, we have
$$
\begin{align*}
& \angle AOB+\angle BOC=180^{\circ} \\
\Rightarrow & 80^{\circ}+\angle BOC=180^{\circ} \\
\Rightarrow & \angle BOC=180^{\circ}-80^{\circ}=100^{\circ}.
\end{align*}
$$
Now, arc $BC$ makes $\angle BOC=100^{\circ}$ at the centre and $\angle BEC$ at a point $E$ on the remaining part of the circle.
$\therefore \angle BEC=\frac{1}{2} \angle BOC=\left(\frac{1}{2} \times 100^{\circ}\right)=50^{\circ}$.

(ii) Arc $AB$ makes $\angle AOB$ at the centre and $\angle ACB$ at a point $C$ on the remaining part of the circle.
$\therefore \quad \angle ACB=\frac{1}{2} \angle AOB=\left(\frac{1}{2} \times 80^{\circ}\right)=40^{\circ}$.

Now, $CD \| BE$ and $CE$ is the transversal.
$\therefore \quad \angle ECD = \angle BEC=50^{\circ} \quad$ [alt. int. angles]
$\therefore \quad \angle BCD = \angle ACB+\angle ACE+\angle ECD = 40^{\circ}+10^{\circ}+50^{\circ}=100^{\circ}$.

(iii) $DEBC$ is a cyclic quadrilateral.
$$
\begin{align*}
\therefore & \angle BED+\angle BCD=180^{\circ} \\
\Rightarrow & \angle BEC+\angle CED+\angle BCD=180^{\circ} \\
\Rightarrow & 50^{\circ}+\angle CED+100^{\circ}=180^{\circ} \\
\Rightarrow & \angle CED=180^{\circ}-150^{\circ}=30^{\circ}
\end{align*}
$$
---

### Example 12

In the given figure, $\triangle ABC$ is isosceles with $AB=AC$ and $\angle ABC=50^{\circ}$. Find $\angle BDC$ and $\angle BEC$.

#### Solution:

$AB=AC \Rightarrow \angle ACB=\angle ABC=50^{\circ}$.
But, $\angle ABC+\angle ACB+\angle BAC=180^{\circ}$
$\Rightarrow 50^{\circ}+50^{\circ}+\angle BAC=180^{\circ}$
$\Rightarrow \angle BAC=180^{\circ}-100^{\circ}=80^{\circ}$.

$\therefore \quad \angle BDC=\angle BAC=80^{\circ}$ [angles in the same segment].

Now, $BECD$ being a cyclic quadrilateral, we have
$$
\begin{align*}
& \angle BEC+\angle BDC=180^{\circ} \\
\Rightarrow \quad & \angle BEC+80^{\circ}=180^{\circ} \\
\Rightarrow \quad & \angle BEC=180^{\circ}-80^{\circ}=100^{\circ}.
\end{align*}
$$
Hence, $\angle BDC=80^{\circ}$ and $\angle BEC=100^{\circ}$.

---

### Example 13

In the given figure, $AOB$ is a diameter of a circle with centre $O$. Write down the numerical value of $\angle ACD+\angle DEB$.

#### Solution:

Join $BC$.
Then, $\angle ACB=90^{\circ}$ [angle in a semicircle].

Now, $DCBE$ is a cyclic quadrilateral.
$\therefore \quad \angle BCD+\angle DEB=180^{\circ}$
$\Rightarrow \angle ACB+\angle BCD+\angle DEB=90^{\circ}+180^{\circ} \quad [\because \angle ACB=90^{\circ}]$
$\Rightarrow \quad \angle ACD+\angle DEB=270^{\circ} \quad [\because \angle ACB+\angle BCD=\angle ACD]$.

$\therefore$ the numerical value of $(\angle ACD+\angle DEB)$ is $270^{\circ}$.

---

### Example 14

In the given figure, $AB$ is a diameter of the circle and $CD \| AB$. If $\angle DAB=25^{\circ}$, calculate (i) $\angle ACD$ and (ii) $\angle CAD$.

#### Solution:

Join $AC$ and $BD$.
We know that an angle in a semicircle is $90^{\circ}$.
$\therefore \quad \angle ADB=90^{\circ}$.

Also, the sum of the angles of a triangle is $180^{\circ}$.
$\therefore \quad$ in $\triangle ABD$, we have
$\angle BAD+\angle ADB+\angle ABD=180^{\circ}$
$\Rightarrow 25^{\circ}+90^{\circ}+\angle ABD=180^{\circ}$
$\Rightarrow \angle ABD=180^{\circ}-115^{\circ}=65^{\circ}$.

Since $ABDC$ is a cyclic quadrilateral, we have
$\angle ABD+\angle ACD=180^{\circ} \Rightarrow \angle ACD=180^{\circ}-\angle ABD$
$\Rightarrow \angle ACD=180^{\circ}-65^{\circ}=115^{\circ}$

Also, $AB \| CD$ and $AD$ is a transversal.
$\therefore \quad \angle ADC=\angle BAD=25^{\circ} \quad$ [alt. int. angles].

Now, in $\triangle ACD$, we have
$$
\begin{align*}
& \angle ACD+\angle CAD+\angle ADC=180^{\circ} \\
\Rightarrow \quad & 115^{\circ}+\angle CAD+25^{\circ}=180^{\circ} \\
\Rightarrow \quad & \angle CAD=180^{\circ}-140^{\circ}=40^{\circ}
\end{align*}
$$
Hence, (i) $\angle ACD=115^{\circ}$ (ii) $\angle CAD=40^{\circ}$.

---

### Example 15

In the given figure, $AB$ is a diameter of a circle with centre $O$ and $CD \| BA$. If $\angle BAC=20^{\circ}$, find (i) $\angle BOC$, (ii) $\angle COD$, (iii) $\angle CAD$ and (iv) $\angle ADC$.

#### Solution:

(i) Arc $BC$ subtends $\angle BOC$ at the centre and $\angle BAC$ at a point on the remaining part of the circumference.
$\therefore \quad \angle BOC=2 \times \angle BAC=2 \times 20^{\circ}=40^{\circ}$.

(ii) $CD \| BA$ and $OC$ cuts them.
$\therefore \quad \angle OCD=\angle BOC=40^{\circ} \quad$ [alt. int. angles].
$\therefore \quad \angle ODC=\angle OCD=40^{\circ} \quad [\because OC=OD=\text{radius}]$.

Now, in $\triangle OCD$, we have
$$
\begin{align*}
& \angle COD+\angle OCD+\angle ODC=180^{\circ} \\
\Rightarrow & \angle COD+40^{\circ}+40^{\circ}=180^{\circ} \quad [\because \angle OCD=\angle ODC=40^{\circ}] \\
\Rightarrow & \angle COD=180^{\circ}-80^{\circ}=100^{\circ}.
\end{align*}
$$
(iii) Since the angle at the centre is double the angle at a point on the remaining part of the circumference, we have
$\angle CAD=\frac{1}{2} \angle COD=\left(\frac{1}{2} \times 100^{\circ}\right)=50^{\circ}$.

(iv) Since $BA \| CD$ and $AC$ cuts them, we have
$\angle ACD=\angle CAB=20^{\circ} \quad$ [alt. int angles].

In $\triangle ACD$, we have
$$
\begin{align*}
& \angle CAD+\angle ACD+\angle ADC=180^{\circ} \\
\Rightarrow & 50^{\circ}+20^{\circ}+\angle ADC=180^{\circ} \\
\Rightarrow & \angle ADC=180^{\circ}-70^{\circ}=110^{\circ}
\end{align*}
$$

---

### Example 16

In the given figure, $ABCD$ is a cyclic quadrilateral. A circle passing through $A$ and $B$, meets $AD$ and $BC$ in $E$ and $F$ respectively. Prove that $EF \| DC$.

#### Solution:

Join $EF$.
Now, $ABFE$ being a cyclic quadrilateral, we have
$\angle 1+\angle 2=180^{\circ}$. (i)

Also, $ABCD$ being a cyclic quadrilateral, we have
$\angle 1+\angle 3=180^{\circ}$. (ii)

From (i) and (ii), we get
$\angle 1+\angle 2=\angle 1+\angle 3 \Rightarrow \angle 2=\angle 3$.

But, these are corresponding angles.
$\therefore \quad EF \| DC$.

---

### Example 17

In the given figure $A, B, C$ and $D, E, F$ are two sets of collinear points. Prove that $AD \| CF$.

#### Solution:

Join $BE$.
Now, $ABED$ is a cyclic quadrilateral.
$\therefore \quad \angle 1+\angle 2=180^{\circ}$. (i)

Again, $BCFE$ is a cyclic quadrilateral.
$\therefore \quad$ exterior angle = interior opposite angle.
$\therefore \quad \angle 2=\angle 3$. (ii)

From (i) and (ii), we get $\angle 1+\angle 3=180^{\circ}$.
But these are interior angles on the same side of the transversal.
Hence, $AD \| CF$.

---

### Example 18

In the given figure, two circles intersect at $P$ and $Q$. If $\angle A=80^{\circ}$ and $\angle D=84^{\circ}$, calculate (i) $\angle QBC$ and (ii) $\angle BCP$.

#### Solution:

Join $PQ$.
Now, quad. $AQPD$ is cyclic
$\Rightarrow \angle QAD+\angle QPD=180^{\circ}$
$\Rightarrow 80^{\circ}+\angle QPD=180^{\circ}$
$\Rightarrow \angle QPD=180^{\circ}-80^{\circ}=100^{\circ}$.

(i) The side $CP$ of quad. $QBCP$ is produced to $D$.
$\therefore \quad \angle QBC=\angle QPD=100^{\circ} \quad$ [ext. angle = int. opp. angle].

(ii) Side $AQ$ of cyclic quad. $PDAQ$ is produced to $B$.
$\therefore \quad \angle PQB=\angle ADP=84^{\circ} \quad$ [ext. angle = int. opp. angle].

In the cyclic quad. $QBCP$, we have
$$
\begin{align*}
& \angle PQB+\angle BCP=180^{\circ} \\
\Rightarrow & 84^{\circ}+\angle BCP=180^{\circ} \\
\Rightarrow & \angle BCP=180^{\circ}-84^{\circ}=96^{\circ}.
\end{align*}
$$
---

### Example 19

In the given figure, two circles intersect at $A$ and $B$. The centre of the smaller circle is $O$ and lies on the circumference of the larger circle. If $PAC$ and $PBD$ are straight lines and $\angle APB=70^{\circ}$, find (i) $\angle AOB$, (ii) $\angle ACB$ and (iii) $\angle ADB$.

#### Solution:

(i) Minor arc $AB$ subtends $\angle AOB$ at the centre and $\angle APB$ at a point on the remaining part of the circle.
$\therefore \quad \angle AOB=2 \angle APB=2 \times 70^{\circ}=140^{\circ}$.

(ii) $AOBC$ is a cyclic quadrilateral
$$
\begin{align*}
\therefore & \angle AOB+\angle ACB=180^{\circ} \\
\Rightarrow & 140^{\circ}+\angle ACB=180^{\circ} \\
\Rightarrow & \angle ACB=180^{\circ}-140^{\circ}=40^{\circ}.
\end{align*}
$$
(iii) $\angle ADB=\angle ACB=40^{\circ}$ [angles in the same segment].

---

### Example 20

$\triangle ABC$ is an isosceles triangle in which $AB=AC$. If $D$ and $E$ are midpoints of $AB$ and $AC$ respectively, prove that the points $B, C, E$ and $D$ are concyclic.

#### Solution:

In order to show that the points $B, C, E$ and $D$ are concyclic, we must prove that $\angle ECB+\angle EDB=180^{\circ}$.

Since $D$ and $E$ are the midpoints of $AB$ and $AC$ respectively, we have $DE \| BC$.
Now, $DE \| BC$
$\Rightarrow \quad \angle ABC=\angle ADE$
$\Rightarrow \angle ACB=\angle ADE \quad \ldots \text{(i)} \quad [\because AB=AC \Rightarrow \angle ABC=\angle ACB]$.

$\therefore \quad \angle ECB+\angle EDB=\angle ACB+\angle EDB$
$=\angle ADE+\angle EDB \quad$ [using (i)]
$=180^{\circ} \quad [\because \angle ADE \text{ and } \angle EDB \text{ form a linear pair}]$.

Hence, the points $B, C, E$ and $D$ are concyclic.

---

### Example 21

$D$ and $E$ are points on equal sides $AB$ and $AC$ of an isosceles $\triangle ABC$ such that $AD=AE$. Prove that the points $B, C, E$ and $D$ are concyclic.

#### Solution:

In order to prove that the points $B, C, E$ and $D$ are concyclic, we must show that $\angle ECB+\angle EDB=180^{\circ}$.

Now, $AB=AC \Rightarrow \angle ABC=\angle ACB$. (i)
And, $AD=AE \Rightarrow \angle AED=\angle ADE$. (ii)

We know that the sum of the angles of a triangle is $180^{\circ}$.
$\therefore \quad$ in $\triangle ABC$ and $\triangle ADE$, we have
$$
\begin{align*}
& \angle A+\angle ABC+\angle ACB=180^{\circ} \text{ and } \angle A+\angle ADE+\angle AED=180^{\circ} \\
\Rightarrow & \angle A+2\angle ACB=180^{\circ} \text{ and } \angle A+2\angle ADE=180^{\circ} \quad [\text{using (i) and (ii)}] \\
\Rightarrow & \angle A+2\angle ACB=\angle A+2\angle ADE \\
\Rightarrow & 2\angle ACB=2\angle ADE \Rightarrow \angle ACB=\angle ADE \\
\therefore & \angle ECB=\angle ADE \quad \ldots \text{(iii)} \\
\therefore & \angle ECB+\angle EDB=\angle ADE+\angle EDB \quad [\text{using (iii)}] \\
& =180^{\circ} \quad [\because \angle ADE+\angle EDB = \text{a straight angle}].
\end{align*}
$$
Thus, $\angle ECB+\angle EDB=180^{\circ}$.
This shows that the points $B, C, E$ and $D$ are concyclic.

---

### Example 22

Prove that if the bisector of any angle of a triangle and the perpendicular bisector of its opposite side intersect then they will intersect on the circumcircle of the triangle.

#### Solution:

Let $O$ be the circumcentre of the given $\triangle ABC$. Then, the perpendicular bisector of $BC$ passes through the point $O$. Let it cut the circumcircle of $\triangle ABC$ at $D$ and $BC$ at $E$. Join $OB$ and $OC$.

In order to show that the perpendicular bisector of $BC$ and the bisector of $\angle A$ of $\triangle ABC$ intersect at $D$, it is sufficient to show that $AD$ is the bisector of $\angle A$.

Clearly, arc $BC$ makes $\angle BOC$ at the centre and $\angle A$ at a point $A$ on the remaining part of the circle.
$\therefore \quad \angle BOC=2 \angle A$. (i)

In $\triangle OEB$ and $\triangle OEC$, we have $\angle OEB=\angle OEC=90^{\circ}$.
Hyp. $OB=$ hyp. $OC=$ radius of the circle.
$OE=OE \quad$ (common)
$\therefore \quad \triangle OEB \cong \triangle OEC$
$\therefore \quad \angle BOE=\angle COE=\angle A \quad [\because \angle BOC=2 \angle A]$.

Now, arc $DC$ makes $\angle A$ at the centre and therefore it will make $\frac{1}{2} \angle A$ at the point $A$ on remaining part of the circle.
$\therefore \quad \angle CAD=\frac{1}{2} \angle A$.

This shows that $AD$ is the bisector of $\angle A$.
Thus, the bisector of $\angle A$ and the perpendicular bisector of side $BC$, intersect at a point $D$ lying on the circumcircle of $\triangle ABC$. Hence, the result follows.

---

### Example 23

In the given figure, $AB$ is a diameter of a circle with centre $O$. If $ADE$ and $CBE$ are straight lines, meeting at $E$ such that $\angle BAD=35^{\circ}$ and $\angle BED=25^{\circ}$, find (i) $\angle DBC$, (ii) $\angle BCD$ and (iii) $\angle CDB$.

#### Solution:

Join $AC$ and $BD$.
Now, $\angle ADB=90^{\circ}$ (angle in a semicircle).
Since $ADE$ is a straight line, we have
$\angle ADB+\angle EDB=180^{\circ} \Rightarrow 90^{\circ}+\angle EDB=180^{\circ} \Rightarrow \angle EDB=180^{\circ}-90^{\circ}=90^{\circ}$.

In $\triangle DBE$, we have
$$
\begin{align*}
& \angle DBE+\angle BED+\angle EDB=180^{\circ} \\
\Rightarrow \quad & \angle DBE+25^{\circ}+90^{\circ}=180^{\circ} \\
\Rightarrow \quad & \angle DBE=180^{\circ}-115^{\circ}=65^{\circ}.
\end{align*}
$$
(i) Since $CBE$ is a straight line, we have
$\angle DBC+\angle DBE=180^{\circ} \Rightarrow \angle DBC+65^{\circ}=180^{\circ} \Rightarrow \angle DBC=180^{\circ}-65^{\circ}=115^{\circ}$.

(ii) $\angle BCD=\angle BAD=35^{\circ}$ [angles in the same segment].

(iii) In $\triangle DBC$, we have
$$
\begin{align*}
& \angle DBC+\angle BCD+\angle CDB=180^{\circ} \\
\Rightarrow \quad & 115^{\circ}+35^{\circ}+\angle CDB=180^{\circ} \\
\Rightarrow \quad & \angle CDB=(180^{\circ}-150^{\circ})=30^{\circ}.
\end{align*}
$$

---

### Example 24

Let the vertex of an $\angle ABC$ be located outside a circle and let the sides of the angle intersect equal chords $AD$ and $CE$ with the circle. Prove that $\angle ABC$ is equal to half of the difference of the angles subtended by the chords $AC$ and $DE$ at the centre.

#### Solution:

Let $O$ be the centre of the given circle. Let $ADB$ and $CEB$ be the two chords of the circle such that $AD=CE$. Join $OA, OC, OD, OE$ and $DE$.

Then, we have to prove that $\angle ABC=\frac{1}{2}(\angle AOC-\angle DOE)$.

In $\triangle OAD$ and $\triangle OCE$, we have
$OA=OC$ [radii of the same circle]
$OD=OE$ [radii of the same circle]
$AD=CE$ [given]
$\therefore \quad \triangle OAD \cong \triangle OCE$ [by SSS-congruence].
So, $\angle AOD=\angle COE, OA=OC$ and $OD=OE$.
$\therefore \angle OAD = \angle ODA = \angle OCE = \angle OEC = x^{\circ}$ (say).

In $\triangle OAC$, we have
$OA=OC \Rightarrow \angle OAC=\angle OCA=y^{\circ}$ (say).
$\therefore \quad \angle AOC=(180^{\circ}-2y^{\circ})$. (i)

In $\triangle ODE$, we have
$OD=OE \Rightarrow \angle ODE=\angle OED=z^{\circ}$ (say).
$\therefore \quad \angle DOE=(180^{\circ}-2z^{\circ})$. (ii)

Clearly, $ACED$ is a cyclic quadrilateral.
$\therefore \quad \angle C+\angle D=180^{\circ} \Rightarrow (x^{\circ}+y^{\circ})+(x^{\circ}+z^{\circ})=180^{\circ} \Rightarrow 2x^{\circ}+y^{\circ}+z^{\circ}=180^{\circ}$ (iii)

Now, in $\triangle BDE$, we have
$$
\begin{align*}
& \angle BDE+\angle BED+\angle DBE=180^{\circ} \\
\Rightarrow \quad & \{180^{\circ}-(x^{\circ}+z^{\circ})\} + \{180^{\circ}-(x^{\circ}+z^{\circ})\} + \angle DBE = 180^{\circ} \\
\Rightarrow \quad & \angle DBE=2x^{\circ}+2z^{\circ}-180^{\circ} \\
& =180^{\circ}-(y^{\circ}+z^{\circ})+2z^{\circ}-180^{\circ} \quad [\text{using (iii)}] \\
\Rightarrow \quad & \angle DBE=z^{\circ}-y^{\circ} \\
\Rightarrow & \angle ABC=z^{\circ}-y^{\circ} \quad \ldots \text{(iv)} \quad [\because \angle DBE=\angle ABC].
\end{align*}
$$
From (i) and (ii), we get
$(\angle AOC-\angle DOE)=(180^{\circ}-2y^{\circ})-(180^{\circ}-2z^{\circ})=2(z^{\circ}-y^{\circ})$
$\Rightarrow \quad \frac{1}{2}(\angle AOC-\angle DOE)=z^{\circ}-y^{\circ}$. (v)

From (iv) and (v), we have
$\frac{1}{2}(\angle AOC-\angle DOE)=\angle ABC$

---

### Example 25

Prove that any four vertices of a regular pentagon are concyclic.

#### Solution:

**GIVEN:** A regular pentagon $ABCDE$.

**TO PROVE:** Every set of four vertices of $ABCDE$ is a set of points lying on a circle.

**PROOF:** First we show that the points $A, B, C, E$ lie on a circle.
Join $AC$ and $BE$.

In $\triangle ABC$ and $\triangle BAE$, we have
$$
\begin{align*}
& AB=BA \quad [\text{common}] \\
& BC=AE \quad [\text{sides of a regular pentagon}] \\
& \angle ABC=\angle BAE \quad [\text{each equal to } 108^{\circ}] \\
\therefore & \triangle ABC \cong \triangle BAE \quad [\text{by SAS-congruence}] \\
\Rightarrow & \angle BCA=\angle AEB \quad [\text{c.p.c.t.}].
\end{align*}
$$
Thus, $AB$ subtends equal angles at two points $C$ and $E$ on the same side of $AB$.
$\therefore \quad$ the points $A, B, C, E$ are concyclic.
Similarly, every set of four vertices of pentagon $ABCDE$ is a set of concyclic points.

---

## Some Results on Cyclic Quadrilaterals

### Theorem 1

*Prove that every cyclic parallelogram is a rectangle.*

**GIVEN:** A parallelogram $ABCD$ inscribed in a circle.

**TO PROVE:** $ABCD$ is a rectangle.

**PROOF:** We have
$\angle A+\angle C=180^{\circ}$ (i) [opp. angles of a cyclic quad.].

But, $\angle A=\angle C$ (ii) [opposite angles of a parallelogram].
$\therefore \angle A=\angle C=90^{\circ}$ [from (i) and (ii)].

But, a parallelogram one of whose angles is $90^{\circ}$ is a rectangle.
Hence, $ABCD$ is a rectangle.

---

### Theorem 2

*Prove that an isosceles trapezium is always cyclic. Or, If two nonparallel sides of a trapezium are equal, prove that it is cyclic.*

**GIVEN:** A trapezium $ABCD$ in which $AB \| DC$ and $AD=BC$.

**TO PROVE:** $\angle A+\angle C=180^{\circ}$, and $\angle B+\angle D=180^{\circ}$.

**CONSTRUCTION:** Draw $DL \perp AB$ and $CM \perp AB$.

**PROOF:** From the right $\triangle ALD$ and $B M C$, we have
$AD=BC$ [given]
$DL=CM$ [distance between two parallels]

$\therefore \quad \triangle ALD \cong \triangle BMC$. [RHS-congruence]
$\Rightarrow \angle A=\angle B \quad \ldots \text{(i)}$ and $\angle ADL=\angle BCM$

$\Rightarrow \angle C=\angle BCD=\angle BCM+90^{\circ} = \angle ADL+90^{\circ}=\angle ADC=\angle D$ (ii)

$\Rightarrow \quad \angle C=\angle D$.

Now, $\angle A+\angle B+\angle C+\angle D=360^{\circ}$ [sum of the angles of a quad. is $360^{\circ}$]
$\Rightarrow \quad 2(\angle A+\angle C)=360^{\circ}$ and $2(\angle B+\angle D)=360^{\circ}$ [using (i) and (ii)]
$\Rightarrow \angle A+\angle C=180^{\circ}$ and $\angle B+\angle D=180^{\circ}$.

Hence, quad. $ABCD$ is cyclic.

---

### Theorem 3

*Prove that a cyclic trapezium is always isosceles and its diagonals are equal. Or, If two sides of a cyclic quadrilateral are parallel, prove that its remaining two sides are equal and the diagonals are equal.*

**GIVEN:** A cyclic trapezium in which $AB \| DC$.

**TO PROVE:** $AD=BC$ and $AC=BD$.

**PROOF:** $AB \| DC$ and $BC$ is a transversal.
$\therefore \quad \angle ABC+\angle BCD=180^{\circ}$ [sum of int. angles].
But, $\angle ABC+\angle ADC=180^{\circ}$ [opposite angles of a cyclic quad.].
$$
\begin{align*}
\therefore & \angle ABC+\angle ADC=\angle ABC+\angle BCD \\
\Rightarrow & \angle ADC=\angle BCD. \quad \text{(i)}
\end{align*}
$$
Now, in $\triangle ADC$ and $\triangle BCD$, we have
$$
\begin{align*}
\angle ADC &= \angle BCD \quad [\text{proved in (i)}] \\
\angle DAC &= \angle CBD \quad [\text{angles in the same segment}] \\
DC &= CD \quad [\text{common}] \\
\therefore \quad \triangle ADC & \cong \triangle BCD. \\
\text{Hence, } AD &= BC \text{ and } AC=BD.
\end{align*}
$$
---

### Theorem 4

*Prove that the quadrilateral formed by angle bisectors of a cyclic quadrilateral is also cyclic.*

**GIVEN:** A cyclic quad. $ABCD$ in which $AP, BP, CR$ and $DR$ are the bisectors of $\angle A, \angle B, \angle C$ and $\angle D$ respectively, forming quad. $PQRS$.

**TO PROVE:** $PQRS$ is a cyclic quadrilateral.

**PROOF:** Since the sum of the angles of a triangle is $180^{\circ}$, from $\triangle ABP$ and $\triangle CDR$, we have
$$
\left.
\begin{array}{l}
\angle APB+\angle PAB+\angle PBA=180^{\circ} \\
\angle CRD+\angle RCD+\angle RDC=180^{\circ}
\end{array}
\right\}
\Rightarrow
\left\{
\begin{array}{l}
\angle APB+\frac{1}{2} \angle A+\frac{1}{2} \angle B=180^{\circ} \quad \text{(i)} \\
\angle CRD+\frac{1}{2} \angle C+\frac{1}{2} \angle D=180^{\circ} \quad \text{(ii)}
\end{array}
\right.
$$
Adding (i) and (ii), we get
$$
\begin{align*}
& \angle APB+\angle CRD+\frac{1}{2}(\angle A+\angle B+\angle C+\angle D)=360^{\circ} \\
\Rightarrow & \angle APB+\angle CRD=180^{\circ} \quad [\because \angle A+\angle B+\angle C+\angle D=360^{\circ}] \\
\Rightarrow & \angle QPS+\angle QRS=180^{\circ}.
\end{align*}
$$
Thus, two opposite angles of quad. $PQRS$ are supplementary.
Hence, $PQRS$ is cyclic.

---

### Theorem 5

*Prove that the sum of the angles in the four segments exterior to a cyclic quadrilateral is equal to six right angles.*

**GIVEN:** A cyclic quadrilateral $ABCD$, and $\angle P, \angle Q, \angle R$ and $\angle S$ are in the four segments exterior to it.

**TO PROVE:** $\angle P+\angle Q+\angle R+\angle S=6$ rt. angles.

**CONSTRUCTION:** Join $BS$ and $CS$.

**PROOF:** $APBS$ is a cyclic quadrilateral.
$\therefore \quad \angle 1+\angle P=180^{\circ}$. (i)

Again, $SBQC$ is a cyclic quadrilateral.
$\therefore \quad \angle 2+\angle Q=180^{\circ}$. (ii)

Also, $SCRD$ is a cyclic quadrilateral.
$\therefore \quad \angle 3+\angle R=180^{\circ}$. (iii)

From (i), (ii) and (iii), we get
$(\angle 1+\angle 2+\angle 3)+(\angle P+\angle Q+\angle R)=540^{\circ}$
$\Rightarrow \quad \angle P+\angle Q+\angle R+\angle S=540^{\circ}=6$ rt. angles $[\because \angle 1+\angle 2+\angle 3=\angle S]$.

Hence, $\angle P+\angle Q+\angle R+\angle S=6$ rt. angles.

---

### Theorem 6

*Prove that the altitudes of a triangle are concurrent. Or, Prove that the perpendiculars from the vertices of a triangle on the opposite sides are concurrent.*

**GIVEN:** A $\triangle ABC$ in which $BE \perp AC$ and $CF \perp AB$ such that $BE$ and $CF$ intersect at a point $O$. $AO$ is joined and produced to meet $BC$ at $D$.

**TO PROVE:** $AD \perp BC$.

**CONSTRUCTION:** Join $FE$.

**PROOF:** $BE \perp AC$ and $CF \perp AB$
$\Rightarrow \angle BEC=\angle BFC=90^{\circ}$
$\Rightarrow \quad BC$ makes equal angles at $E$ and $F$
$\Rightarrow \quad BCEF$ is a cyclic quadrilateral
$\Rightarrow \quad \angle ECB+\angle BFE=180^{\circ}$
$\Rightarrow \angle ACD+\angle BFE=180^{\circ} \quad [\because \angle ECB=\angle ACD]$
$\Rightarrow \quad \angle ACD+(\angle BFO+\angle OFE)=180^{\circ}$
$\Rightarrow \angle ACD+90^{\circ}+\angle OFE=180^{\circ} \quad [\because \angle BFO=90^{\circ}]$
$\Rightarrow \quad \angle ACD+\angle OFE=90^{\circ}$. (i)

Again, $\angle OFA+\angle OEA=90^{\circ}+90^{\circ}=180^{\circ}$
$\Rightarrow EOFA$ is a cyclic quadrilateral
$\Rightarrow \quad \angle OFE=\angle OAE \quad$ [angles in the same segment]. (ii)

From (i) and (ii), we have
$\angle ACD+\angle OAE = 90^{\circ}$
$\Rightarrow \quad \angle ACD+\angle DAC = 90^{\circ} \quad \ldots \text{(iii)} \quad [\because \angle OAE=\angle DAC]$.

We know that the sum of the angles of a triangle is $180^{\circ}$.
$\therefore \quad$ in $\triangle ADC$, we have
$\angle ACD+\angle DAC+\angle ADC=180^{\circ}$
$\Rightarrow 90^{\circ}+\angle ADC=180^{\circ} \quad$ [using (iii)]
$\Rightarrow \angle ADC=90^{\circ}$
$\Rightarrow \quad AD \perp BC$.

Hence, the altitudes $AD, BE$ and $CF$ are concurrent.

---

