## Results on Parallelograms

### Theorem 1
**Prove that in a parallelogram:**
1.  each diagonal divides the parallelogram into two congruent triangles;
2.  opposite sides are equal;
3.  opposite angles are equal.

---

**Given:** A parallelogram $ABCD$ in which $AB \parallel DC$ and $AD \parallel BC$.

**To Prove:**
1.  $\triangle ABC \cong \triangle CDA$ and $\triangle ABD \cong \triangle CDB$;
2.  $AB=CD$ and $BC=AD$;
3.  $\angle B=\angle D$ and $\angle A=\angle C$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-001.jpg)

**Construction:** Join $A$ and $C$.

**Proof:**
1.  In $\triangle ABC$ and $\triangle CDA$, we have:
    - $\angle 1 = \angle 2$ (alternate interior angles, as $AB \parallel DC$ and $CA$ is the transversal)
    - $\angle 3 = \angle 4$ (alternate interior angles, as $BC \parallel AD$ and $CA$ is the transversal)
    - $AC = CA$ (common side)
    
    Therefore, $\triangle ABC \cong \triangle CDA$ (AAS congruence criterion).
    
    Similarly, we can prove that $\triangle ABD \cong \triangle CDB$.

2.  Since $\triangle ABC \cong \triangle CDA$ (proved above), it follows that $AB=CD$ and $BC=AD$ (corresponding parts of congruent triangles).

3.  Since $\triangle ABC \cong \triangle CDA$ (proved above), it follows that $\angle B = \angle D$ (corresponding parts of congruent triangles).
    Also, we have $\angle 1 = \angle 2$ and $\angle 3 = \angle 4$.
    Therefore, $\angle 1 + \angle 4 = \angle 2 + \angle 3 \Rightarrow \angle A = \angle C$.
    Hence, $\angle B=\angle D$ and $\angle A=\angle C$.

---

### Theorem 2
**Prove that the diagonals of a parallelogram bisect each other.**

---

**Given:** A parallelogram $ABCD$ in which $AB \parallel DC$ and $BC \parallel AD$. Its diagonals $AC$ and $BD$ intersect each other at point $O$.

**To Prove:** $OA=OC$ and $OB=OD$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-002.jpg)

**Proof:**
In $\triangle AOB$ and $\triangle COD$, we have:
- $AB=CD$ (opposite sides of a parallelogram)
- $\angle OAB = \angle OCD$ (alternate interior angles, as $AB \parallel DC$ and $CA$ is the transversal)
- $\angle OBA = \angle ODC$ (alternate interior angles, as $AB \parallel DC$ and $DB$ is the transversal)

Therefore, $\triangle AOB \cong \triangle COD$ (AAS congruence criterion).
Hence, $OA=OC$ and $OB=OD$ (corresponding parts of congruent triangles).

---

### Summary
**In a parallelogram:**
- The opposite sides are equal.
- The opposite angles are equal.
- Each diagonal bisects the parallelogram.
- The diagonals bisect each other.

---

## Converse of the Above Theorems

### Theorem 3
**If each pair of opposite sides of a quadrilateral are equal, then it is a parallelogram.**

---

**Given:** A quadrilateral $ABCD$ in which $AB=CD$ and $AD=BC$.

**To Prove:** $ABCD$ is a parallelogram.

**Construction:** Join $A$ and $C$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-003.jpg)

**Proof:**
In $\triangle ABC$ and $\triangle CDA$, we have:
- $AB=CD$ (given)
- $BC=AD$ (given)
- $AC=CA$ (common side)

Therefore, $\triangle ABC \cong \triangle CDA$ (SSS congruence criterion).
So, $\angle BAC = \angle DCA$ (corresponding parts of congruent triangles).

But, these are alternate interior angles.
Therefore, $AB \parallel DC$.
Similarly, $AD \parallel BC$.
Hence, $ABCD$ is a parallelogram.

---

### Theorem 4
**If in a quadrilateral, each pair of opposite angles are equal, then it is a parallelogram.**

---

**Given:** A quadrilateral $ABCD$ in which $\angle A=\angle C$ and $\angle B=\angle D$.

**To Prove:** $ABCD$ is a parallelogram.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-004.jpg)

**Proof:**
We have $\angle A=\angle C$ and $\angle B=\angle D$ (given).
This implies $\angle A+\angle B=\angle C+\angle D$.
Since the sum of angles in a quadrilateral is $360^{\circ}$, we have $\angle A+\angle B+\angle C+\angle D=360^{\circ}$.
Therefore, $\angle A+\angle B = \angle C+\angle D = \frac{360^{\circ}}{2} = 180^{\circ}$.

Now, the line segments $BC$ and $AD$ are intersected by the transversal $AB$ such that the sum of consecutive interior angles is $180^{\circ}$ ($\angle A+\angle B=180^{\circ}$).
Therefore, $AD \parallel BC$.

Again, since $\angle A=\angle C$ and $\angle D=\angle B$, we have $\angle A+\angle D=\angle C+\angle B = 180^{\circ}$.
Now, the line segments $DC$ and $AB$ are intersected by the transversal $DA$ such that the sum of consecutive interior angles is $180^{\circ}$ ($\angle A+\angle D=180^{\circ}$).
Therefore, $AB \parallel DC$.

Thus, since $AB \parallel DC$ and $AD \parallel BC$, $ABCD$ is a parallelogram.

---

### Theorem 5
**If the diagonals of a quadrilateral bisect each other, then the quadrilateral is a parallelogram.**

---

**Given:** A quadrilateral $ABCD$ whose diagonals $AC$ and $BD$ intersect at a point $O$ such that $OA=OC$ and $OB=OD$.

**To Prove:** $ABCD$ is a parallelogram.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-005.jpg)

**Proof:**
In $\triangle OAB$ and $\triangle OCD$, we have:
- $OA=OC$ (given)
- $OB=OD$ (given)
- $\angle AOB=\angle COD$ (vertically opposite angles)

Therefore, $\triangle OAB \cong \triangle OCD$ (SAS congruence criterion).
So, $\angle BAO = \angle DCO$ (corresponding parts of congruent triangles).
But, these are alternate interior angles.
Therefore, $AB \parallel DC$.

Again, in $\triangle OAD$ and $\triangle OCB$, we have:
- $OA=OC$ (given)
- $OD=OB$ (given)
- $\angle DOA=\angle BOC$ (vertically opposite angles)

Therefore, $\triangle OAD \cong \triangle OCB$ (SAS congruence criterion).
So, $\angle ADO = \angle CBO$ (corresponding parts of congruent triangles).
But, these are alternate interior angles.
Therefore, $AD \parallel BC$.

Thus, since $AB \parallel DC$ and $AD \parallel BC$, $ABCD$ is a parallelogram.

---

### Theorem 6
**Prove that a quadrilateral is a parallelogram if one pair of its opposite sides are equal and parallel.**

---

**Given:** A quadrilateral $ABCD$ in which $AB=DC$ and $AB \parallel DC$.

**To Prove:** $ABCD$ is a parallelogram.

**Construction:** Join $A$ and $C$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-006.jpg)

**Proof:**
In $\triangle ABC$ and $\triangle CDA$, we have:
- $AB=DC$ (given)
- $AC=CA$ (common side)
- $\angle BAC=\angle DCA$ (alternate interior angles, as $AB \parallel DC$ and $CA$ is the transversal)

Therefore, $\triangle ABC \cong \triangle CDA$ (SAS congruence criterion).
So, $\angle BCA = \angle DAC$ (corresponding parts of congruent triangles).
But, these are alternate interior angles.
Therefore, $AD \parallel BC$.

Now, since $AB \parallel DC$ (given) and $AD \parallel BC$ (proved), $ABCD$ is a parallelogram.

---

### Summary
**A quadrilateral is a parallelogram if:**
- both pairs of opposite sides are equal, or
- both pairs of opposite angles are equal, or
- the diagonals bisect each other, or
- a pair of opposite sides are equal and parallel.

---

## Some Results on Rectangle, Rhombus and Square

### Theorem 7
**Prove that each angle of a rectangle is a right angle.**

---

**Given:** A rectangle $ABCD$ in which $\angle A=90^{\circ}$.

**To Prove:** $\angle A=\angle B=\angle C=\angle D=90^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-007.jpg)

**Proof:**
By definition, a rectangle is a parallelogram, so $ABCD$ is a parallelogram.
This implies $AB \parallel DC$ and $AD \parallel BC$.

Now, since $AD \parallel BC$ and $AB$ is a transversal, the sum of consecutive interior angles is $180^{\circ}$:
$\angle A+\angle B=180^{\circ}$
Given $\angle A = 90^{\circ}$, we have $\angle B = 180^{\circ} - 90^{\circ} = 90^{\circ}$.

Also, in a parallelogram, opposite angles are equal.
Therefore, $\angle C = \angle A = 90^{\circ}$ and $\angle D = \angle B = 90^{\circ}$.
Thus, each angle of a rectangle is a right angle.

---

### Theorem 8
**Prove that the diagonals of a rectangle are equal.**

---

**Given:** A rectangle $ABCD$ with diagonals $AC$ and $BD$.

**To Prove:** $AC=BD$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-008.jpg)

**Proof:**
In $\triangle ABD$ and $\triangle BAC$, we have:
- $AB=BA$ (common side)
- $\angle A=\angle B$ (each equal to $90^{\circ}$)
- $AD=BC$ (opposite sides of a rectangle)

Therefore, $\triangle ABD \cong \triangle BAC$ (SAS congruence criterion).
Hence, $BD=AC$ (corresponding parts of congruent triangles).

---

### Theorem 9 (Converse of Theorem 8)
**If the two diagonals of a parallelogram are equal, prove that the parallelogram is a rectangle.**

---

**Given:** A parallelogram $ABCD$ in which $AC=BD$.

**To Prove:** $ABCD$ is a rectangle.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-009.jpg)

**Proof:**
In $\triangle ABC$ and $\triangle DCB$, we have:

$$
\begin{align*}
& AB=DC \quad (\text{opposite sides of a parallelogram}) \\
& BC=CB \quad (\text{common side}) \\
& AC=DB \quad (\text{given})
\end{align*}
$$

Therefore, $\triangle ABC \cong \triangle DCB$ (SSS congruence criterion).
This implies $\angle ABC = \angle DCB$. (i)

But, since $DC \parallel AB$ and $CB$ is a transversal, we know that consecutive interior angles are supplementary:
$\angle ABC + \angle DCB = 180^{\circ}$.

Using equation (i), we get $2 \angle ABC = 180^{\circ}$, which means $\angle ABC = 90^{\circ}$.
Thus, $ABCD$ is a parallelogram with one right angle.
Hence, $ABCD$ is a rectangle.

---

### Theorem 10
**Prove that the diagonals of a rhombus bisect each other at right angles.**

---

**Given:** A rhombus $ABCD$ whose diagonals $AC$ and $BD$ intersect at point $O$.

**To Prove:**
1.  $OA=OC$ and $OB=OD$.
2.  $\angle BOC=\angle DOC=\angle AOD=\angle AOB=90^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-010.jpg)

**Proof:**
1.  A rhombus is a parallelogram, and we know that the diagonals of a parallelogram bisect each other. Therefore, $OA=OC$ and $OB=OD$.

2.  Now, in $\triangle BOC$ and $\triangle DOC$, we have:
    - $OB=OD$ (diagonals of a parallelogram bisect each other)
    - $BC=DC$ (sides of a rhombus are equal)
    - $OC=OC$ (common side)

    Therefore, $\triangle BOC \cong \triangle DOC$ (SSS congruence criterion).
    This implies $\angle BOC = \angle DOC$ (corresponding parts of congruent triangles).
    
    Since $\angle BOC$ and $\angle DOC$ form a linear pair, their sum is $180^{\circ}$:
    $\angle BOC + \angle DOC = 180^{\circ}$
    $2 \angle BOC = 180^{\circ} \Rightarrow \angle BOC = 90^{\circ}$.
    
    Hence, $\angle BOC = \angle DOC = 90^{\circ}$. Similarly, all angles at the intersection are $90^{\circ}$.

---

### Theorem 11 (Converse of Theorem 10)
**If the diagonals of a quadrilateral bisect each other at right angles, prove that it is a rhombus.**

---

**Given:** A quadrilateral $ABCD$ whose diagonals $AC$ and $BD$ intersect at $O$ such that $OA=OC$, $OB=OD$, and $AC \perp BD$.

**To Prove:** $ABCD$ is a rhombus.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-011.jpg)

**Proof:**
Since the diagonals of quadrilateral $ABCD$ bisect each other, $ABCD$ is a parallelogram.

Now, in $\triangle AOD$ and $\triangle COD$, we have:
- $OA=OC$ (given)
- $\angle AOD=\angle COD=90^{\circ}$ (since $AC \perp BD$)
- $OD=OD$ (common side)

Therefore, $\triangle AOD \cong \triangle COD$ (SAS congruence criterion).
And so, $AD=CD$ (corresponding parts of congruent triangles).

Since $ABCD$ is a parallelogram, opposite sides are equal: $AB=CD$ and $AD=BC$.
As we proved $AD=CD$, it follows that $AB=BC=CD=AD$.
Hence, $ABCD$ is a rhombus.

---

### Theorem 12
**Prove that the diagonals of a square are equal and bisect each other at right angles.**

---

**Given:** A square $ABCD$ whose diagonals $AC$ and $BD$ intersect at $O$.

**To Prove:**
1.  $AC=BD$
2.  $OA=OC$ and $OB=OD$
3.  $AC \perp BD$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-012.jpg)

**Proof:**
1.  **Equality of diagonals:**
    In $\triangle ABC$ and $\triangle BAD$, we have:
    - $AB=BA$ (common side)
    - $BC=AD$ (sides of a square are equal)
    - $\angle ABC=\angle BAD$ (each equal to $90^{\circ}$)
    
    Therefore, $\triangle ABC \cong \triangle BAD$ (SAS congruence criterion).
    And so, $AC=BD$ (corresponding parts of congruent triangles).

2.  **Bisection of diagonals:**
    A square is a parallelogram. Therefore, its diagonals bisect each other.
    And so, $OA=OC$ and $OB=OD$.

3.  **Perpendicularity of diagonals:**
    In $\triangle AOB$ and $\triangle AOD$, we have:
    - $OB=OD$ (diagonals bisect each other)
    - $AB=AD$ (sides of a square are equal)
    - $AO=AO$ (common side)
    
    Therefore, $\triangle AOB \cong \triangle AOD$ (SSS congruence criterion).
    So, $\angle AOB = \angle AOD$.
    But, $\angle AOB + \angle AOD = 180^{\circ}$ (linear pair).
    Therefore, $\angle AOB = \angle AOD = 90^{\circ}$.
    Thus, $AC \perp BD$.

---

### Theorem 13 (Converse of Theorem 12)
**If the diagonals of a quadrilateral are equal and bisect each other at right angles, then prove that the quadrilateral is a square.**

---

**Given:** A quadrilateral $ABCD$ in which diagonals $AC$ and $BD$ intersect at $O$ such that $AC=BD$; $OA=OC$ and $OB=OD$; and $AC \perp BD$.

**To Prove:** $ABCD$ is a square.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-013.jpg)

**Proof:**
Since the diagonals of quadrilateral $ABCD$ bisect each other, $ABCD$ is a parallelogram.
Since the diagonals of the parallelogram bisect each other at right angles, it is a rhombus. This means all sides are equal: $AB=BC=CD=AD$.

Now, in $\triangle ABC$ and $\triangle BAD$, we have:
- $AB=BA$ (common side)
- $AC=BD$ (given)
- $BC=AD$ (sides of a rhombus)

Therefore, $\triangle ABC \cong \triangle BAD$ (SSS congruence criterion).
And so, $\angle ABC = \angle BAD$ (corresponding parts of congruent triangles).

Since $ABCD$ is a parallelogram, consecutive interior angles are supplementary:
$\angle ABC + \angle BAD = 180^{\circ}$.
This implies $\angle ABC = \angle BAD = 90^{\circ}$.

Thus, $ABCD$ is a parallelogram with all sides equal and one angle equal to $90^{\circ}$.
Therefore, $ABCD$ is a square.

---

## Solved Examples

### Example: 1
In a parallelogram $ABCD$, if $\angle A=115^{\circ}$, find $\angle B, \angle C$ and $\angle D$.

#### Solution:

Let $ABCD$ be a parallelogram in which $\angle A=115^{\circ}$.
Since $AD \parallel BC$ and $AB$ is a transversal, the consecutive interior angles are supplementary.

$$
\angle A+\angle B=180^{\circ}
$$

$$
115^{\circ}+\angle B=180^{\circ}
$$

$$
\angle B = 180^{\circ}-115^{\circ} = 65^{\circ}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-014.jpg)

Since the opposite angles of a parallelogram are equal, we have:
$\angle C=\angle A=115^{\circ}$ and $\angle D=\angle B=65^{\circ}$.

Hence, **$\angle B=65^{\circ}$**, **$\angle C=115^{\circ}$**, and **$\angle D=65^{\circ}$**.

---

### Example: 2
Diagonals $AC$ and $BD$ of a parallelogram $ABCD$ intersect at $O$. If $OA=3 \text{ cm}$ and $OD=2 \text{ cm}$, determine the lengths of $AC$ and $BD$.

#### Solution:

The diagonals of a parallelogram bisect each other.
Therefore, $OA=OC=3 \text{ cm}$ and $OB=OD=2 \text{ cm}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-015.jpg)

And so,
$AC = OA+OC = (3+3) \text{ cm} = 6 \text{ cm}$
$BD = OB+OD = (2+2) \text{ cm} = 4 \text{ cm}$

---

### Example: 3
In the adjoining figure, $ABCD$ is a rectangle whose diagonals $AC$ and $BD$ intersect at $O$. If $\angle OAB=28^{\circ}$, find $\angle OBC$.

#### Solution:

We know that the diagonals of a rectangle are equal and bisect each other.
Therefore, in $\triangle OAB$, $OA = OB$. This means $\triangle OAB$ is an isosceles triangle.

$$
\angle OBA = \angle OAB = 28^{\circ}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-016.jpg)

Also, each angle of a rectangle measures $90^{\circ}$.
So, $\angle ABC=90^{\circ}$.

$$
\angle ABC = \angle OBA + \angle OBC = 90^{\circ}
$$

$$
28^{\circ}+\angle OBC = 90^{\circ}
$$

$$
\angle OBC = 90^{\circ}-28^{\circ} = 62^{\circ}
$$

---

### Example: 4
The diagonals $AC$ and $BD$ of a parallelogram $ABCD$ intersect each other at the point $O$. If $\angle DAC=32^{\circ}$ and $\angle AOB=70^{\circ}$, find $\angle DBC$.

#### Solution:

Angles $\angle AOB$ and $\angle AOD$ form a linear pair.
$\angle AOB+\angle AOD=180^{\circ}$
$70^{\circ}+\angle AOD=180^{\circ} \Rightarrow \angle AOD=110^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-017.jpg)

In $\triangle AOD$, the sum of angles is $180^{\circ}$.
$\angle DAO+\angle AOD+\angle ADO=180^{\circ}$
$32^{\circ}+110^{\circ}+\angle ADO=180^{\circ}$
$\angle ADO = 180^{\circ}-32^{\circ}-110^{\circ} = 38^{\circ}$.

Since $AD \parallel BC$ and $BD$ is the transversal, the alternate interior angles are equal.
$\angle DBC = \angle ADO = 38^{\circ}$.

Therefore, $\angle DBC=38^{\circ}$.

---

### Example: 5
In the adjoining figure, $ABCD$ is a rhombus. If $\angle A=70^{\circ}$, find $\angle CDB$.

#### Solution:

In a rhombus (which is a parallelogram), opposite angles are equal.
$\angle C = \angle A = 70^{\circ}$.

In $\triangle CDB$, the sides $CD$ and $CB$ are equal (sides of a rhombus).
Therefore, $\triangle CDB$ is an isosceles triangle, and the angles opposite the equal sides are equal.
$\angle CBD = \angle CDB = x^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-018.jpg)

The sum of angles in $\triangle CDB$ is $180^{\circ}$.
$\angle CDB+\angle CBD+\angle DCB=180^{\circ}$
$x^{\circ}+x^{\circ}+70^{\circ}=180^{\circ}$
$2x = 110 \Rightarrow x=55$.

Hence, $\angle CDB=55^{\circ}$.

---

### Example: 6
$ABCD$ is a rhombus such that $\angle ACB=40^{\circ}$. Find $\angle ADB$.

#### Solution:

Let the diagonals $AC$ and $BD$ intersect at $O$.
The diagonals of a rhombus intersect at right angles, so $\angle BOC=90^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-019.jpg)

In $\triangle BOC$, the sum of angles is $180^{\circ}$.
$\angle OCB+\angle BOC+\angle CBO=180^{\circ}$
$40^{\circ}+90^{\circ}+\angle CBO=180^{\circ}$
$\angle CBO = 180^{\circ} - 130^{\circ} = 50^{\circ}$.

Since $AD \parallel BC$ and $BD$ is the transversal, the alternate interior angles are equal.
$\angle ADB = \angle CBO = 50^{\circ}$.

---

### Example: 7
In the adjoining figure, $ABCD$ is a square. A line segment $DX$ cuts the side $BC$ at $X$ and the diagonal $AC$ at $O$ such that $\angle COD=105^{\circ}$ and $\angle OXC=x^{\circ}$. Find the value of $x$.

#### Solution:

The diagonals of a square bisect its angles.
Since $\angle DCB=90^{\circ}$ and $CA$ is a diagonal, it bisects $\angle DCB$.
Therefore, $\angle OCD = \angle OCX = \frac{90^{\circ}}{2} = 45^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-020.jpg)

Angles $\angle COD$ and $\angle COX$ form a linear pair.
$\angle COD+\angle COX=180^{\circ}$
$105^{\circ}+\angle COX=180^{\circ} \Rightarrow \angle COX = 75^{\circ}$.

Now, in $\triangle COX$, the sum of angles is $180^{\circ}$.
$\angle OCX+\angle COX+\angle OXC=180^{\circ}$
$45^{\circ}+75^{\circ}+x^{\circ}=180^{\circ}$
$120^{\circ} + x^{\circ} = 180^{\circ}$
$x = 60$.

---

### Example: 8
In the adjoining figure, $ABCD$ is a parallelogram and $X, Y$ are points on the diagonal $BD$ such that $DX=BY$. Prove that:
1.  $CXAY$ is a parallelogram.
2.  $\triangle ADX \cong \triangle CBY$ and $\triangle ABY \cong \triangle CDX$.
3.  $AX=CY$ and $CX=AY$.

#### Solution:

1.  **Proof that $CXAY$ is a parallelogram:**
    Join $AC$, meeting $BD$ at $O$.
    Since the diagonals of a parallelogram bisect each other, we have $OA=OC$ and $OD=OB$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-021.jpg)
    
    Now, we are given $DX=BY$.
    Since $OD=OB$, we can write $OD-DX = OB-BY$, which simplifies to $OX=OY$.
    
    The quadrilateral $CXAY$ has diagonals $AC$ and $XY$. We have shown that $OA=OC$ and $OX=OY$. Since the diagonals bisect each other, **$CXAY$ is a parallelogram**.

2.  **Proof of triangle congruency:**
    In $\triangle ADX$ and $\triangle CBY$, we have:
    - $AD=BC$ (opposite sides of a parallelogram)
    - $\angle ADX=\angle CBY$ (alternate interior angles, since $AD \parallel BC$)
    - $DX=BY$ (given)
    
    Therefore, **$\triangle ADX \cong \triangle CBY$** (SAS congruence criterion).
    
    Similarly, in $\triangle ABY$ and $\triangle CDX$:
    - $AB=CD$ (opposite sides of a parallelogram)
    - $\angle ABY=\angle CDX$ (alternate interior angles, since $AB \parallel DC$)
    - $BY=DX$ (given)
    
    Therefore, **$\triangle ABY \cong \triangle CDX$** (SAS congruence criterion).

3.  **Proof of side equality:**
    From the congruency $\triangle ADX \cong \triangle CBY$, we conclude that **$AX=CY$** (corresponding parts of congruent triangles).
    From the congruency $\triangle ABY \cong \triangle CDX$, we conclude that **$AY=CX$** (corresponding parts of congruent triangles).

---

### Example: 9
Prove that in a parallelogram, the bisectors of any two consecutive angles intersect at right angles.

#### Solution:

**Given:** A parallelogram $ABCD$ in which the bisectors of two consecutive angles $\angle A$ and $\angle B$ intersect at a point $P$.

**To Prove:** $\angle APB=90^{\circ}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-022.jpg)

**Proof:**
In parallelogram $ABCD$, $AD \parallel BC$ and $AB$ is a transversal.
The sum of consecutive interior angles is $180^{\circ}$.
$\angle A + \angle B = 180^{\circ}$.

Multiplying by $\frac{1}{2}$:
$\frac{1}{2} \angle A + \frac{1}{2} \angle B = 90^{\circ}$.

Since $AP$ and $BP$ are angle bisectors, $\angle PAB = \frac{1}{2} \angle A$ and $\angle PBA = \frac{1}{2} \angle B$.
Letting $\angle PAB = \angle 1$ and $\angle PBA = \angle 2$, we have $\angle 1 + \angle 2 = 90^{\circ}$.

In $\triangle APB$, the sum of angles is $180^{\circ}$:
$\angle 1 + \angle 2 + \angle APB = 180^{\circ}$
$90^{\circ} + \angle APB = 180^{\circ}$
$\angle APB = 90^{\circ}$.

---

### Example: 10
$ABCD$ is a parallelogram and $AL$ and $CM$ are perpendiculars from vertices $A$ and $C$ on diagonal $BD$, as shown in the adjoining figure. Show that (i) $\triangle ALB \cong \triangle CMD$ and (ii) $AL=CM$.

#### Solution:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Geometry/Quadrilaterals/class-09-Ch-10-B-BooK-023.jpg)

In $\triangle ALB$ and $\triangle CMD$, we have:
- $\angle ALB=\angle CMD=90^{\circ}$ (given that $AL \perp BD$ and $CM \perp BD$)
- $\angle ABL=\angle CDM$ (alternate interior angles, since $AB \parallel DC$)
- $AB=CD$ (opposite sides of a parallelogram)

Therefore, **$\triangle ALB \cong \triangle CMD$** (AAS congruence criterion).
And so, **$AL=CM$** (corresponding parts of congruent triangles).

---