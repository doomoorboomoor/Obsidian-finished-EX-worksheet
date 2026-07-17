## Criteria for Similarity of Two Triangles

Two triangles are similar, if (i) their corresponding angles are equal and (ii) their corresponding sides are proportional.

Thus, $\triangle ABC \sim \triangle DEF$, if:
1. $\angle A=\angle D, \angle B=\angle E, \angle C=\angle F$
2. $\frac{AB}{DE}=\frac{BC}{EF}=\frac{CA}{FD}$.

---

### Theorem 1: (AAA-similarity)
If in two triangles, the corresponding angles are equal, then their corresponding sides are proportional and hence the triangles are similar.

**GIVEN:** $\triangle ABC$ and $\triangle DEF$ such that $\angle A=\angle D, \angle B=\angle E$ and $\angle C=\angle F$.

**TO PROVE:** $\triangle ABC \sim \triangle DEF$.

**CONSTRUCTION:** Cut $DP=AB$ and $DQ=AC$. Join $PQ$.

**PROOF:** In $\triangle ABC$ and $\triangle DPQ$, we have

$$
\begin{array}{lll}
& AB=DP & \text{[by construction]} \\
& AC=DQ & \text{[by construction]} \\
& \angle A=\angle D & \text{[given]} \\
\therefore & \triangle ABC \cong \triangle DPQ & \text{[by SAS-congruence]} \\
\Rightarrow & \angle B=\angle P & \\
\Rightarrow & \angle E=\angle P & {[\because \angle B=\angle E \text{ (given)] }} \\
\Rightarrow & PQ \| EF & {[\because \text{ corresponding } \angle s \text{ are equal] }} \\
\Rightarrow & \frac{DP}{DE}=\frac{DQ}{DF} & \\
\Rightarrow & \frac{AB}{DE}=\frac{CA}{FD} & {[\because DP=AB \text{ and } DQ=AC]}
\end{array}
$$

Similarly, $\frac{AB}{DE}=\frac{BC}{EF}$.

$\therefore \quad \frac{AB}{DE}=\frac{BC}{EF}=\frac{CA}{FD}$.

Thus, $\angle A=\angle D, \angle B=\angle E, \angle C=\angle F$ and $\frac{AB}{DE}=\frac{BC}{EF}=\frac{CA}{FD}$.

Hence, $\triangle ABC \sim \triangle DEF$.

**Important Remark:** Two $\Delta$s are similar $\Leftrightarrow$ they are equiangular.

### Corollary: (AA-similarity)
If two angles of one triangle are respectively equal to two angles of another triangle then the two triangles are similar.

**PROOF:** In $\triangle ABC$ and $\triangle DEF$, let $\angle A=\angle D$ and $\angle B=\angle E$.
Then, $3\text{rd} \angle C=3\text{rd} \angle F$.
Thus, the two triangles are equiangular and hence similar.

**Remark:** AA-similarity is the same as AAA-similarity.

---

### Theorem 2: (SSS-similarity)
If the corresponding sides of two triangles are proportional then their corresponding angles are equal, and hence the two triangles are similar.

**GIVEN:** $\triangle ABC$ and $\triangle DEF$ in which $\frac{AB}{DE}=\frac{BC}{EF}=\frac{AC}{DF}$.

**TO PROVE:** $\triangle ABC \sim \triangle DEF$.

**CONSTRUCTION:** Let us take $\triangle ABC$ and $\triangle DEF$ such that

$$
\frac{AB}{DE}=\frac{BC}{EF}=\frac{AC}{DF}(<1)
$$

Cut $DP=AB$ and $DQ=AC$. Join $PQ$.

**PROOF:** $\quad \frac{AB}{DE}=\frac{AC}{DF} \Rightarrow \frac{DP}{DE}=\frac{DQ}{DF} \quad[\because AB=DP \text{ and } AC=DQ]$.

So, by the converse of Thales' theorem, $PQ \| EF$.

$$
\begin{array}{lll}
\therefore & \angle P=\angle E & {[\text{ corresponding } \angle\text{s}]} \\
& \angle Q=\angle F & {[\text{ corresponding } \angle\text{s}]}
\end{array}
$$

$\therefore \quad \triangle DPQ \sim \triangle DEF$ [by AA-similarity]

$\Rightarrow \frac{DP}{DE}=\frac{PQ}{EF}$

$\Rightarrow \quad \frac{AB}{DE}=\frac{PQ}{EF} \quad \ldots \text{(i)} \quad [\because DP=AB]$

But, $\frac{AB}{DE}=\frac{BC}{EF} \quad \ldots \text{(ii)} \quad$[given]

$\therefore \quad \frac{PQ}{EF}=\frac{BC}{EF} \quad$[ from (i) and (ii) ]

$\Rightarrow \quad BC=PQ$.

Thus, $AB=DP, AC=DQ$ and $BC=PQ$.

$\therefore \quad \triangle ABC \cong \triangle DPQ$ [by SSS-congruence]

$\therefore \quad \angle A=\angle D, \angle B=\angle P=\angle E$ and $\angle C=\angle Q=\angle F$

$\Rightarrow \quad \angle A=\angle D, \angle B=\angle E$ and $\angle C=\angle F$.

Thus, the given triangles are equiangular and hence similar.

---

### Theorem 3: (SAS-similarity)
If one angle of a triangle is equal to one angle of the other triangle and the sides including these angles are proportional then the two triangles are similar.

**GIVEN:** $\triangle ABC$ and $\triangle DEF$ in which $\angle A=\angle D$ and $\frac{AB}{DE}=\frac{AC}{DF}$.

**TO PROVE:** $\triangle ABC \sim \triangle DEF$.

**CONSTRUCTION:** Let us take $\triangle ABC$ and $\triangle DEF$ such that

$$
\frac{AB}{DE}=\frac{AC}{DF}(<1) \text{ and } \angle A=\angle D.
$$

Cut $DP=AB$ and $DQ=AC$. Join $PQ$.

**PROOF:** In $\triangle ABC$ and $\triangle DPQ$, we have

$$
\begin{array}{lll}
& AB=DP & \text{[by construction]} \\
& \angle A=\angle D & \text{(given)} \\
& AC=DQ & \text{[by construction]} \\
\therefore & \triangle ABC \cong \triangle DPQ & \text{[by SAS-congruence]} \\
\therefore & \angle A=\angle D, \angle B=\angle P \text{ and } \angle C=\angle Q.
\end{array}
$$

Now, $\frac{AB}{DE}=\frac{AC}{DF}$ (given)

$\Rightarrow \quad \frac{DP}{DE}=\frac{DQ}{DF} \quad[\because AB=DP \text{ and } AC=DQ]$

$\Rightarrow \quad PQ \| EF \quad$[by the converse of Thales' theorem]

$\Rightarrow \quad \angle P=\angle E$ and $\angle Q=\angle F \quad$[corresponding $\angle$s]

$\therefore \quad \angle A=\angle D, \angle B=\angle P=\angle E$ and $\angle C=\angle Q=\angle F$.

Thus, $\angle A=\angle D, \angle B=\angle E$ and $\angle C=\angle F$.

So, the given triangles are equiangular and hence similar.

---

### Theorem 4:
If a perpendicular is drawn from the vertex of the right angle of a right triangle to the hypotenuse then the triangles on both sides of the perpendicular are similar to the whole triangle and also to each other.

**GIVEN:** A $\triangle ABC$ in which $\angle BAC=90^{\circ}$ and $AD \perp BC$.

**TO PROVE:**
1. $\triangle DBA \sim \triangle ABC$
2. $\triangle DAC \sim \triangle ABC$
3. $\triangle DBA \sim \triangle DAC$.

**PROOF:**
1. In $\triangle DBA$ and $\triangle ABC$, we have
   $$
   \begin{aligned}
   \angle BDA &= \angle BAC=90^{\circ} \\
   \angle DBA &= \angle ABC \quad \text{(common)} \\
   \therefore \quad \triangle DBA &\sim \triangle ABC \quad \text{[by AA-similarity].}
   \end{aligned}
   $$

2. In $\triangle DAC$ and $\triangle ABC$, we have
   $$
   \begin{aligned}
   \angle CDA &= \angle CAB=90^{\circ} \\
   \angle DCA &= \angle ACB \quad \text{(common)} \\
   \therefore \quad \triangle DAC &\sim \triangle ABC \quad \text{[by AA-similarity].}
   \end{aligned}
   $$

3. In $\triangle DBA$ and $\triangle DAC$, we have
   $$
   \left.\begin{array}{l}
   \angle ADB=\angle CDA=90^{\circ} . \\
   \angle B+\angle BAD=90^{\circ} \\
   \angle C+\angle CAD=90^{\circ} \\
   \angle BAD+\angle CAD=90^{\circ}
   \end{array}\right\} \Rightarrow \angle B=\angle CAD \text{ and } \angle C=\angle BAD .
   $$
   Thus, in $\triangle DBA$ and $\triangle DAC$, we have:
   $$
   \begin{aligned}
   & \angle ADB=\angle CDA \quad [\text{each equal to } 90^{\circ}] \\
   & \angle B=\angle CAD \\
   & \angle BAD=\angle C \\
   \therefore \quad & \triangle DBA \sim \triangle DAC \quad [\text{by AAA-similarity}].
   \end{aligned}
   $$

---

## Summary

- (i) If $\angle A=\angle D, \angle B=\angle E, \angle C=\angle F$, then $\triangle ABC \sim \triangle DEF$. (**AAA-similarity**)
- (ii) If $\angle A=\angle D, \angle B=\angle E$, then $\triangle ABC \sim \triangle DEF$. (**AA-similarity**)
- (iii) If $\frac{AB}{DE}=\frac{BC}{EF}=\frac{AC}{DF}$, then $\triangle ABC \sim \triangle DEF$. (**SSS-similarity**)
- (iv) If $\angle A=\angle D$ and $\frac{AB}{DE}=\frac{AC}{DF}$, then $\triangle ABC \sim \triangle DEF$. (**SAS-similarity**)

---

## Some More Results

### Theorem 1:
If two triangles are equiangular, prove that the ratio of their corresponding sides is the same as the ratio of the corresponding altitudes.

**GIVEN:** $\triangle ABC$ and $\triangle DEF$ in which $\angle A=\angle D, \angle B=\angle E$ and $\angle C=\angle F$ and $AL \perp BC$ and $DM \perp EF$.

**TO PROVE:** $\frac{BC}{EF}=\frac{AL}{DM}$.

**PROOF:** Since $\triangle ABC$ and $\triangle DEF$ are equiangular, $\triangle ABC \sim \triangle DEF$.

$$
\therefore \quad \frac{AB}{DE}=\frac{BC}{EF}. \quad \text{(i)}
$$

In $\triangle ALB$ and $\triangle DME$, we have

$$
\begin{array}{ll}
& \angle ALB=\angle DME=90^{\circ} \text{ and } \angle B=\angle E \text{ (given). } \\
\therefore & \triangle ALB \sim \triangle DME \text{ [by AA-similarity] } \\
\therefore & \frac{AB}{DE}=\frac{AL}{DM}. \quad \text{(ii)}
\end{array}
$$

From (i) and (ii), we get $\frac{BC}{EF}=\frac{AL}{DM}$.

---

### Theorem 2:
If two triangles are equiangular, prove that the ratio of their corresponding sides is the same as the ratio of the corresponding medians.

**GIVEN:** $\triangle ABC$ and $\triangle DEF$ in which $\angle A=\angle D, \angle B=\angle E$ and $\angle C=\angle F$ and $AL$ and $DM$ are the medians.

**TO PROVE:** $\frac{BC}{EF}=\frac{AL}{DM}$.

**PROOF:** Since $\triangle ABC$ and $\triangle DEF$ are equiangular, we have $\triangle ABC \sim \triangle DEF$.

$\therefore \quad \frac{AB}{DE}=\frac{BC}{EF}$.

But, $\frac{AB}{DE}=\frac{BC}{EF}=\frac{2BL}{2EM}=\frac{BL}{EM}$.

Now, in $\triangle ABL$ and $\triangle DEM$, we have

$$
\begin{align*}
& \frac{AB}{DE}=\frac{BL}{EM} \text{ and } \angle B=\angle E \text{ (given). } \\
\therefore \quad & \triangle ABL \sim \triangle DEM \text{ [by SAS-similarity] } \\
\Rightarrow \quad & \frac{AB}{DE}=\frac{AL}{DM}. \quad \text{(ii)}
\end{align*}
$$

From (i) and (ii), we get $\frac{BC}{EF}=\frac{AL}{DM}$.

---

### Theorem 3:
If two triangles are equiangular, show that the ratio of the corresponding sides is the same as the ratio of the corresponding angle-bisector segments.

**GIVEN:** $\triangle ABC$ and $\triangle DEF$ in which $\angle A=\angle D, \angle B=\angle E$ and $\angle C=\angle F$, and $AX$ and $DY$ are the bisectors of $\angle A$ and $\angle D$ respectively.

**TO PROVE:** $\frac{BC}{EF}=\frac{AX}{DY}$.

**PROOF:** Since $\triangle ABC$ and $\triangle DEF$ are equiangular, we have $\triangle ABC \sim \triangle DEF$.

$$
\therefore \quad \frac{AB}{DE}=\frac{BC}{EF}. \quad \text{(i)}
$$

Now, $\angle A=\angle D \Rightarrow \frac{1}{2} \angle A=\frac{1}{2} \angle D \Rightarrow \angle BAX=\angle EDY$.

Thus, in $\triangle ABX$ and $\triangle DEY$, we have

$$
\begin{array}{lll}
& \angle BAX=\angle EDY & \text{(proved)} \\
& \angle B=\angle E & \text{(given)} \\
\therefore \quad & \triangle ABX \sim \triangle DEY \quad \text{[by AA-similarity]} \\
\Rightarrow \quad & \frac{AB}{DE}=\frac{AX}{DY}. \quad \text{(ii)}
\end{array}
$$

From (i) and (ii), we get $\frac{BC}{EF}=\frac{AX}{DY}$.

---

## Solved Examples

### Example: 1
In the adjoining figure, $\triangle AHK$ is similar to $\triangle ABC$. If $AK=10 \text{ cm}, BC=3.5 \text{ cm}$ and $HK=7 \text{ cm}$, find $AC$. [CBSE 2010]

#### Solution:
$\triangle AHK \sim \triangle ABC$

$\Rightarrow \frac{AK}{AC}=\frac{HK}{BC} \Rightarrow \frac{10}{x}=\frac{7}{3.5}$, where $AC=x \text{ cm}$

$\Rightarrow \quad x=\frac{10 \times 3.5}{7}=5$.

$\therefore \quad AC=5 \text{ cm}$.

---

### Example: 2
In the given figure, $DE \| BC, AD=2 \text{ cm}, BD=2.5 \text{ cm}, AE=3.2 \text{ cm}$ and $DE=4 \text{ cm}$. Find $AC$ and $BC$. [CBSE 2001C]

#### Solution:
Since $DE \| BC$, we have

$$
\begin{aligned}
\angle ADE &= \angle ABC \quad (\text{corresponding } \angle\text{s}) \\
\text{ and } \angle AED &= \angle ACB \quad (\text{corresponding } \angle\text{s}). \\
\therefore \quad \triangle ADE &\sim \triangle ABC \quad \text{[by AA-similarity].}
\end{aligned}
$$

So, the corresponding sides of $\triangle ADE$ and $\triangle ABC$ are proportional.

$$
\therefore \quad \frac{AD}{AB}=\frac{DE}{BC}=\frac{AE}{AC}. \quad \text{(i)}
$$

Now, $\frac{AD}{AB}=\frac{DE}{BC} \Rightarrow \frac{2}{4.5}=\frac{4}{BC} \quad [\because AB=AD+BD=4.5 \text{ cm}]$

$$
\Rightarrow BC=\left(\frac{4 \times 4.5}{2}\right) \text{cm}=9 \text{ cm}.
$$

Again, $\frac{DE}{BC}=\frac{AE}{AC}$ [from (i)]

$\Rightarrow \quad \frac{4}{9}=\frac{3.2}{AC} \quad [\because BC=9 \text{ cm}]$

$\Rightarrow AC=\left(\frac{9 \times 3.2}{4}\right) \text{cm}=7.2 \text{ cm}$.

Hence, $AC=7.2 \text{ cm}$ and $BC=9 \text{ cm}$.

---

### Example: 3
In the given figure, $AB \| CD$. Prove that $\triangle AOB \sim \triangle DOC$.

#### Solution:
$AB \| CD$ (given).

$\therefore \quad \angle OAB=\angle ODC$ (alternate angles)

$\angle OBA=\angle OCD$ (alternate angles)

$\angle AOB=\angle DOC \quad ($vertical opposite $\angle$s)

$\therefore \quad \triangle AOB \sim \triangle DOC$ [by AAA-similarity].

---

### Example: 4
In the given figure, $\triangle AOB \sim \triangle DOC$. Prove that $AB \| CD$.

#### Solution:
$\triangle AOB \sim \triangle DOC$.

So, the given triangles are equiangular.

$\therefore \quad \angle OAB=\angle ODC$.

But, these are alternate angles.

$\therefore \quad AB \| CD$.

---

### Example: 5
Find $\angle P$ in the adjoining figure.

#### Solution:
In $\triangle ABC$ and $\triangle QRP$, we have

$$
\frac{AB}{QR}=\frac{3.6}{7.2}=\frac{1}{2}, \frac{BC}{RP}=\frac{6}{12}=\frac{1}{2} \text{ and } \frac{CA}{PQ}=\frac{3 \sqrt{3}}{6 \sqrt{3}}=\frac{1}{2}
$$

Thus, $\frac{AB}{QR}=\frac{BC}{RP}=\frac{CA}{PQ}$ and so

$$
\triangle ABC \sim \triangle QRP \quad \text{[by SSS-similarity].}
$$

$\therefore \quad \angle C=\angle P \quad $[corresponding angles of similar triangles].

But, $\angle C=180^{\circ}-(\angle A+\angle B)=180^{\circ}-\left(70^{\circ}+60^{\circ}\right)=50^{\circ}$.

$\therefore \quad \angle P=50^{\circ}$.

---

### Example: 6
In the given figure, $\triangle OQP \sim \triangle OAB, \angle OPQ=56^{\circ}$ and $\angle BOQ=132^{\circ}$. Find $\angle OAB$.

#### Solution:
In $\triangle OPQ$, we have

$$
\angle BOQ=\angle OPQ+\angle OQP
$$

$[\because$ the exterior angle is equal to the sum of the two interior opposite angles]

$\Rightarrow \angle OQP=\angle BOQ-\angle OPQ=132^{\circ}-56^{\circ}=76^{\circ}$.

Now, $\triangle OQP \sim \triangle OAB$

$\Rightarrow \angle OQP=\angle OAB$ [corresponding angles of similar triangles].

$\therefore \quad \angle OAB=\angle OQP=76^{\circ}$.

---

### Example: 7
In the given figure, $AP \cdot AR=AS \cdot AQ$. Prove that $\angle P=\angle S$ and $\angle Q=\angle R$.

#### Solution:
We have

$$
\angle PAQ=\angle SAR \quad \ldots \text{(i)} \quad \text{[vertically opposite angles]}
$$

Also, $AP \cdot AR=AS \cdot AQ$ (given)

$\Rightarrow \quad \frac{AP}{AS}=\frac{AQ}{AR}$.

From (i) and (ii), we have

$$
\begin{array}{ll}
& \triangle PAQ \sim \triangle SAR \quad \text{[by SAS-similarity]} \\
\therefore \quad & \angle P=\angle S \text{ and } \angle Q=\angle R
\end{array}
$$

[corresponding angles of similar triangles].

---

### Example: 8
A vertical stick which is 15 cm long casts a 12-cm-long shadow on the ground. At the same time, a vertical tower casts a 50-m-long shadow on the ground. Find the height of the tower.

#### Solution:
Let $AB$ be the vertical stick and let $AC$ be its shadow.
Then, $AB=0.15 \text{ m}$ and $AC=0.12 \text{ m}$.
Let $DE$ be the vertical tower and let $DF$ be its shadow.
Then, $DF=50 \text{ m}$. Let $DE=x \text{ m}$.

Now, in $\triangle BAC$ and $\triangle EDF$, we have

$$
\begin{aligned}
& \angle BAC=\angle EDF=90^{\circ} \\
& \angle ACB=\angle DFE
\end{aligned}
$$

[angular elevation of the sun at the same time]

$$
\begin{array}{ll}
\therefore & \triangle BAC \sim \triangle EDF \\
\Rightarrow & \frac{AB}{DE}=\frac{AC}{DF} \Rightarrow \frac{0.15}{x}=\frac{0.12}{50} \\
\Rightarrow & x=\frac{(0.15 \times 50)}{0.12}=62.5
\end{array}
$$

Hence, the height of the tower is $62.5 \text{ m}$.

---

### Example: 9
Prove that the ratio of the perimeters of two similar triangles is the same as the ratio of their corresponding sides.

#### Solution:
**GIVEN:** $\triangle ABC$ and $\triangle PQR$ in which $BC=a, CA=b, AB=c$ and $QR=p, RP=q, PQ=r$. Also, $\triangle ABC \sim \triangle PQR$.

**TO PROVE:** $\frac{a}{p}=\frac{b}{q}=\frac{c}{r}=\frac{a+b+c}{p+q+r}$.

**PROOF:** Since $\triangle ABC$ and $\triangle PQR$ are similar, therefore their corresponding sides are proportional.

$$
\therefore \quad \frac{a}{p}=\frac{b}{q}=\frac{c}{r}=k \text{ (say)} \quad \text{(i)}
$$

$\Rightarrow \quad a=kp, b=kq$ and $c=kr$.

$$
\therefore \quad \frac{\text{perimeter of } \triangle ABC}{\text{perimeter of } \triangle PQR}=\frac{a+b+c}{p+q+r}=\frac{kp+kq+kr}{p+q+r} = \frac{k(p+q+r)}{(p+q+r)}=k \quad \text{(ii)}
$$

From (i) and (ii), we get

$\frac{a}{p}=\frac{b}{q}=\frac{c}{r}=\frac{a+b+c}{p+q+r}=\frac{\text{perimeter of } \triangle ABC}{\text{perimeter of } \triangle PQR} \quad [\text{each equal to } k]$.

---

### Example: 10
The perimeters of two similar triangles are 25 cm and 15 cm respectively. If one side of the first triangle is 9 cm, find the corresponding side of the second triangle. [CBSE 2002C]

#### Solution:
Let $\triangle ABC \sim \triangle DEF$ given in such a way that perimeter of $\triangle ABC=25 \text{ cm}$, perimeter of $\triangle DEF=15 \text{ cm}$ and $AB=9 \text{ cm}$. Then, we have to find $DE$. Let $DE=x \text{ cm}$.

We know that the ratio of the perimeters of two similar triangles is the same as the ratio of their corresponding sides.

$\therefore \quad \frac{\text{perimeter of } \triangle ABC}{\text{perimeter of } \triangle DEF}=\frac{AB}{DE}$

$\Rightarrow \quad \frac{25}{15}=\frac{9}{x} \Rightarrow x=\left(\frac{9 \times 15}{25}\right)=5.4$.

$\therefore \quad DE=5.4 \text{ cm}$.

Hence, the corresponding side of the second triangle is $5.4 \text{ cm}$.

---

### Example: 11
In the given figure, $D$ is a point on the side $BC$ of $\triangle ABC$ such that $\angle ADC=\angle BAC$. Prove that $CA^{2}=CB \times CD$. [CBSE 2004]

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $D$ is a point on $BC$ such that $\angle ADC=\angle BAC$.

**TO PROVE:** $CA^{2}=CB \times CD$.

**PROOF:** In $\triangle ABC$ and $\triangle DAC$, we have

$$
\begin{aligned}
\angle BAC &= \angle ADC \quad \text{(given)} \\
\angle ACB &= \angle DCA \quad \text{(common)} \\
\therefore \quad \triangle ABC &\sim \triangle DAC \quad \text{[by AA-similarity].}
\end{aligned}
$$

So, the sides of $\triangle ABC$ and $\triangle DAC$ are proportional.

$\therefore \quad \frac{CA}{CB}=\frac{CD}{CA}$.

Hence, $CA^{2}=CB \times CD$.

---

### Example: 12
In the given figure, $S$ and $T$ are points on sides $PR$ and $QR$ of $\triangle PQR$ such that $\angle P=\angle RTS$. Show that $\triangle RPQ \sim \triangle RTS$.

#### Solution:
**GIVEN:** $\triangle RPQ$ and $\triangle RTS$ in which $\angle P=\angle RTS$.

**TO PROVE:** $\triangle RPQ \sim \triangle RTS$.

**PROOF:** In $\triangle RPQ$ and $\triangle RTS$, we have

$$
\begin{array}{lll}
& \angle P=\angle RTS & \text{(given)} \\
& \angle R=\angle R & \text{(common)} \\
\therefore & \triangle RPQ \sim \triangle RTS & \text{[by AA-similarity].}
\end{array}
$$

---

### Example: 13
In the given figure, if $\triangle ABE \cong \triangle ACD$, show that $\triangle ADE \sim \triangle ABC$.

#### Solution:
$$
\begin{array}{llr}
\triangle ABE \cong \triangle ACD & & \text{(given)} \\
\therefore \quad AE=AD & \ldots \text{(i)} & {[\text{cpct}]} \\
\text{ and } AB=AC. & \ldots \text{(ii)} & {[\text{cpct}]}
\end{array}
$$

In $\triangle ADE$ and $\triangle ABC$, we have

$$
\begin{array}{ll}
& \angle DAE=\angle BAC \quad \text{(common)} \\
\text{and } & \frac{AD}{AB}=\frac{AE}{AC} \quad [\text{using (i) and (ii)}]. \\
\therefore \quad & \triangle ADE \sim \triangle ABC \quad \text{[by SAS-similarity]}.
\end{array}
$$

---

### Example: 14
In the given figure, altitudes $AD$ and $CE$ of $\triangle ABC$ intersect each other at the point $P$. Show that:
(i) $\triangle AEP \sim \triangle CDP$
(ii) $\triangle ABD \sim \triangle CBE$
(iii) $\triangle AEP \sim \triangle ADB$
(iv) $\triangle PDC \sim \triangle BEC$

#### Solution:
(i) In $\triangle AEP$ and $\triangle CDP$, we have
   $$
   \begin{array}{lll}
   & \angle AEP=\angle CDP & [\text{each equal to } 90^{\circ}] \\
   & \angle APE=\angle CPD & [\text{vertically opposite } \angle\text{s}] \\
   \therefore \quad & \triangle AEP \sim \triangle CDP & [\text{by AA-similarity}].
   \end{array}
   $$

(ii) In $\triangle ABD$ and $\triangle CBE$, we have
   $$
   \begin{array}{lll}
   & \angle ADB=\angle CEB=90^{\circ} \\
   & \angle B=\angle B \quad [\text{common}] \\
   \therefore \quad & \triangle ABD \sim \triangle CBE \quad [\text{by AA-similarity}].
   \end{array}
   $$

(iii) In $\triangle AEP$ and $\triangle ADB$, we have
   $$
   \begin{array}{ll}
   \angle AEP=\angle ADB=90^{\circ} & \\
   \angle EAP=\angle DAB & \text{(common)} \\
   \text{Hence, } \triangle AEP \sim \triangle ADB & \text{[by AA-similarity].}
   \end{array}
   $$

(iv) In $\triangle PDC$ and $\triangle BEC$, we have
   $$
   \begin{aligned}
   & \angle PDC=\angle BEC=90^{\circ} \\
   & \angle PCD=\angle BCE \quad \text{(common)} \\
   \therefore \quad & \triangle PDC \sim \triangle BEC \quad \text{[by AA-similarity].}
   \end{aligned}
   $$

---

### Example: 15
Diagonals $AC$ and $BD$ of a trapezium $ABCD$ with $AB \| DC$ intersect each other at point $O$. Using a similarity criterion for two triangles, show that $\frac{OA}{OC}=\frac{OB}{OD}$.

#### Solution:
**GIVEN:** A trapezium $ABCD$ in which $AB \| DC$. The diagonals $AC$ and $BD$ intersect at $O$.

**TO PROVE:** $\frac{OA}{OC}=\frac{OB}{OD}$.

**PROOF:** In $\triangle OAB$ and $\triangle OCD$, we have

$\angle OAB=\angle OCD$ [alternate angles, since $AB \| DC$ ]

and $\angle OBA=\angle ODC$ [alternate angles, since $AB \| DC$ ].

$\therefore \quad \triangle OAB \sim \triangle OCD$ [by AA-similarity].

And so, $\frac{OA}{OC}=\frac{OB}{OD}$.

---

### Example: 16
In $\triangle ABC, AD \perp BC$ and $AD^{2}=BD \cdot CD$. Prove that $\angle BAC=90^{\circ}$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AD \perp BC$ and $AD^{2}=BD \cdot CD$.

**TO PROVE:** $\angle BAC=90^{\circ}$.

**PROOF:** $AD^{2}=BD \cdot CD \Rightarrow \frac{BD}{AD}=\frac{AD}{CD}$.

Now, in $\triangle DBA$ and $\triangle DAC$, we have

$$
\begin{array}{ll}
& \angle BDA=\angle ADC=90^{\circ} \text{ and } \frac{BD}{AD}=\frac{AD}{CD}. \\
\therefore \quad & \triangle DBA \sim \triangle DAC \text{ [by SAS-similarity] } \\
\therefore \quad & \angle B=\angle 2 \text{ and } \angle 1=\angle C \\
\therefore \quad \angle 1+\angle 2=\angle B+\angle C & \Rightarrow \angle A=\angle B+\angle C \\
& \Rightarrow 2 \angle A=\angle A+\angle B+\angle C=180^{\circ} \\
& \Rightarrow \angle A=\angle BAC=90^{\circ}
\end{array}
$$

---

### Example: 17
In the given figure $PA, QB$ and $RC$ each is perpendicular to $AC$ such that $PA=x, RC=y, QB=z, AB=a$ and $BC=b$. Prove that $\frac{1}{x}+\frac{1}{y}=\frac{1}{z}$. [CBSE 2000C]

#### Solution:
$PA \perp AC$ and $QB \perp AC \Rightarrow QB \| PA$.

Thus, in $\triangle PAC, QB \| PA$. So, $\triangle QBC \sim \triangle PAC$.

$\therefore \frac{QB}{PA}=\frac{BC}{AC} \Rightarrow \frac{z}{x}=\frac{b}{a+b}. \quad \ldots \text{(i) [by the property of similar} \Delta\text{s]}$

In $\triangle RAC, QB \| RC$. So, $\triangle QBA \sim \triangle RCA$.

$\therefore \frac{QB}{RC}=\frac{AB}{AC} \Rightarrow \frac{z}{y}=\frac{a}{a+b}. \quad \ldots \text{(ii) [by the property of similar} \Delta\text{s]}$

From (i) and (ii), we get

$$
\frac{z}{x}+\frac{z}{y}=\left(\frac{b}{a+b}+\frac{a}{a+b}\right)=1
$$

$\Rightarrow \quad \frac{z}{x}+\frac{z}{y}=1 \Rightarrow \frac{1}{x}+\frac{1}{y}=\frac{1}{z}$.

Hence, $\frac{1}{x}+\frac{1}{y}=\frac{1}{z}$.

---

### Example: 18
The side $AD$ of a parallelogram $ABCD$ is produced to a point $E$. $BE$ intersects $CD$ at $F$. Show that $\triangle ABE \sim \triangle CFB$.

#### Solution:
We have

$$
\begin{array}{lll}
& AD\|BC \Rightarrow AE\|BC & {[ABCD \text{ is a parallelogram }]} \\
\therefore & \angle AEB=\angle CBF & \text{[alternate angles].}
\end{array}
$$

In $\triangle ABE$ and $\triangle CFB$, we have

$$
\begin{array}{lll}
\angle AEB=\angle CBF & {[\text{proved above}]} \\
\angle EAB=\angle BCF & {[\because \angle DAB=\angle BCD, \text{ being opposite}} \\
& & \text{angles of a parallelogram]} \\
\therefore \quad \triangle ABE \sim \triangle CFB & & \text{[by AA-similarity].}
\end{array}
$$

---

### Example: 19
In the given figure, $\angle ACB=90^{\circ}$ and $CD \perp AB$. Prove that $CD^{2}=BD \cdot AD$. [CBSE 2006]

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $\angle ACB=90^{\circ}$ and $CD \perp AB$.

**TO PROVE:** $CD^{2}=BD \cdot AD$.

**PROOF:** In right $\triangle ADC$, we have $\angle 1+\angle 2=90^{\circ}$.

In right $\triangle ACB$, we have

$$
\begin{aligned}
\angle 1+\angle 3 &= 90^{\circ} . \\
\therefore \quad \angle 1+\angle 2 &= \angle 1+\angle 3 \Rightarrow \angle 2=\angle 3.
\end{aligned}
$$

In $\triangle ADC$ and $\triangle CDB$, we have

$\angle 2=\angle 3$ (proved) and $\angle ADC=\angle CDB=90^{\circ}$.

$\therefore \quad \triangle ADC \sim \triangle CDB$ [by AA-similarity]

$$
\therefore \quad \frac{AD}{CD}=\frac{CD}{BD}.
$$

Hence, $CD^{2}=BD \cdot AD$.

---

### Example: 20
In the given figure, $\triangle ABC$ and $\triangle AMP$ are right-angled at $B$ and $M$ respectively. Prove that:
(i) $\triangle ABC \sim \triangle AMP$
(ii) $\frac{CA}{PA}=\frac{BC}{MP}$

#### Solution:
**GIVEN:** $\triangle ABC$ and $\triangle AMP$ such that $\angle B=90^{\circ}$ and $\angle M=90^{\circ}$.

**TO PROVE:** (i) $\triangle ABC \sim \triangle AMP \quad$ (ii) $\frac{CA}{PA}=\frac{BC}{MP}$.

**PROOF:**
(i) In $\triangle ABC$ and $\triangle AMP$, we have
   $$
   \begin{array}{ll}
   & \angle ABC=\angle AMP=90^{\circ} \\
   & \angle A=\angle A \quad \text{(common)} \\
   \therefore \quad & \triangle ABC \sim \triangle AMP \quad \text{[by AA-similarity].}
   \end{array}
   $$

(ii) Since $\triangle ABC \sim \triangle AMP$, their corresponding sides are proportional.
   $$
   \therefore \quad \frac{CA}{PA}=\frac{BC}{MP}.
   $$

---

### Example: 21
In a $\triangle ABC, AB=AC$ and $D$ is a point on $AC$ such that $BC^{2}=AC \times DC$. Prove that $BD=BC$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AB=AC$ and $D$ is a point on $AC$ such that $BC^{2}=AC \times DC$.

**TO PROVE:** $BD=BC$.

**PROOF:** $BC^{2}=AC \times DC$ (given)

$\Rightarrow \quad \frac{BC}{DC}=\frac{AC}{BC}$.

Thus, in $\triangle ABC$ and $\triangle BDC$, we have

$$
\begin{aligned}
& \frac{BC}{DC}=\frac{AC}{BC} \text{ and } \angle C=\angle C \quad \text{(common).} \\
\therefore \quad & \triangle ABC \sim \triangle BDC \quad \text{[by SAS-similarity]} \\
\Rightarrow \quad & \frac{AC}{BC}=\frac{AB}{BD} \\
\Rightarrow \quad & \frac{AC}{BC}=\frac{AC}{BD} \quad [\because AB=AC \text{(given)}] \\
\Rightarrow \quad & BD=BC.
\end{aligned}
$$

Hence, $BD=BC$.

---

### Example: 22
In the given figure, $CD$ and $GH$ are respectively the bisectors of $\angle ACB$ and $\angle FGE$ of $\triangle ABC$ and $\triangle FEG$ respectively. If $\triangle ABC \sim \triangle FEG$, prove that:
(a) $\triangle ADC \sim \triangle FHG$
(b) $\triangle BCD \sim \triangle EGH$
(c) $\frac{CD}{GH}=\frac{AC}{FG}$

#### Solution:
$\triangle ABC \sim \triangle FEG$ (given)

$\therefore \quad \angle ACB=\angle FGE$ [corresponding angles of similar triangles are equal]

$\Rightarrow \quad \frac{1}{2} \angle ACB=\frac{1}{2} \angle FGE$

$\therefore \quad \angle ACD=\angle FGH$ and $\angle DCB=\angle HGE$.

(a) In $\triangle ADC$ and $\triangle FHG$, we have
   $$
   \begin{aligned}
   \quad \angle DAC &= \angle HFG \quad [\because \angle A=\angle F \text{ since } \triangle ABC \sim \triangle FEG] \\
   \text{ and } \angle ACD &= \angle FGH \quad [\text{proved above}] \\
   \therefore \quad \triangle ADC &\sim \triangle FHG \quad [\text{by AA-similarity}].
   \end{aligned}
   $$

(b) In $\triangle BCD$ and $\triangle EGH$, we have
   $$
   \begin{aligned}
   \quad \angle DBC &= \angle HEG \quad [\because \angle B=\angle E \text{ since } \triangle ABC \sim \triangle FEG] \\
   \text{ and } \angle DCB &= \angle HGE \quad [\text{proved above}] \\
   \therefore \quad \triangle BCD &\sim \triangle EGH.
   \end{aligned}
   $$

(c) We have $\triangle ADC \sim \triangle FHG \quad $[proved above].
   And so, $\frac{CD}{GH}=\frac{AC}{FG}$ [corresponding sides of similar triangles are proportional].

---

### Example: 23
In the given figure, BM and $EN$ are respectively the medians of $\triangle ABC$ and $\triangle DEF$. If $\triangle ABC \sim \triangle DEF$, prove that:
(a) $\triangle AMB \sim \triangle DNE$
(b) $\triangle CMB \sim \triangle FNE$
(c) $\frac{BM}{EN}=\frac{AC}{DF}$

#### Solution:
$\triangle ABC \sim \triangle DEF$ (given)

$\therefore \quad \angle A=\angle D, \angle B=\angle E$ and $\angle C=\angle F \quad \ldots \text{(i)}$

and $\frac{AB}{DE}=\frac{BC}{EF}=\frac{CA}{FD}. \quad \ldots \text{(ii)}$

Since $BM$ and $EN$ are medians, we have

$$
CA=2AM=2CM \text{ and } FD=2DN=2FN.
$$

$\therefore$ from (ii), we have

$$
\begin{align*}
& \frac{AB}{DE}=\frac{BC}{EF}=\frac{CA}{FD}=\frac{2AM}{2DN}=\frac{2CM}{2FN} \\
\Rightarrow \quad & \frac{AB}{DE}=\frac{BC}{EF}=\frac{CA}{FD}=\frac{AM}{DN}=\frac{CM}{FN} \quad \text{(iii)}
\end{align*}
$$

(a) In $\triangle AMB$ and $\triangle DNE$, we have
   $$
   \begin{array}{ll}
   & \angle BAM=\angle EDN \quad [\because \angle A=\angle D \text{ from (i)}] \\
   \text{ and } & \frac{AB}{DE}=\frac{AM}{DN} \quad [\text{from (iii)}]. \\
   \therefore \quad & \triangle AMB \sim \triangle DNE \quad [\text{by SAS-similarity}].
   \end{array}
   $$

(b) In $\triangle CMB$ and $\triangle FNE$, we have
   $$
   \begin{array}{ll}
   \angle BCM=\angle EFN & {[\because \angle C=\angle F \text{ from (i)}]} \\
   \text{ and } \frac{BC}{EF}=\frac{CM}{FN} & {[\text{from (iii)}].} \\
   \therefore \quad \triangle CMB \sim \triangle FNE & {[\text{by SAS-similarity}].}
   \end{array}
   $$

(c) As proved above, $\triangle AMB \sim \triangle DNE$ and so
   $$
   \frac{AB}{DE}=\frac{BM}{EN}. \quad \text{(iv)}
   $$
   From (ii) and (iv), we get
   $$
   \frac{BM}{EN}=\frac{AC}{FD}
   $$

---

### Example: 24
In a $\triangle ABC, P$ and $Q$ are points on $AB$ and $AC$ respectively such that $PQ \| BC$. Prove that the median $AD$, drawn from $A$ to $BC$, bisects $PQ$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $P$ and $Q$ are points on $AB$ and $AC$ respectively such that $PQ \| BC$ and $AD$ is the median, cutting $PQ$ at $E$.

**TO PROVE:** $PE=EQ$.

**PROOF:** In $\triangle APE$ and $\triangle ABD$, we have

$$
\begin{aligned}
& \angle PAE=\angle BAD \quad [\text{common}] \\
& \angle APE=\angle ABD \quad [\text{corresponding } \angle\text{s}] \\
\therefore \quad & \triangle APE \sim \triangle ABD \quad [\text{by AA-similarity}].
\end{aligned}
$$

But, in similar triangles, the corresponding sides are proportional.

$$
\therefore \quad \frac{AE}{AD}=\frac{PE}{BD}. \quad \text{(i)}
$$

In $\triangle AEQ$ and $\triangle ADC$, we have

$$
\begin{array}{ll}
& \angle QAE=\angle CAD \quad \text{[common]} \\
& \angle AQE=\angle ACD \quad \text{[corresponding angles]} \\
\therefore \quad & \triangle AEQ \sim \triangle ADC \quad \text{[by AA-similarity]}
\end{array}
$$

But, in similar triangles, the corresponding sides are proportional.

$$
\therefore \quad \frac{AE}{AD}=\frac{EQ}{DC}. \quad \text{(ii)}
$$

From (i) and (ii), we get $\frac{PE}{BD}=\frac{EQ}{DC} \quad [\text{each equal to } \frac{AE}{AD}]$.

But, $BD=DC \quad [\because AD$ is the median]

$\therefore \quad PE=EQ$.

---

### Example: 25
In the given figure, $E$ is a point on side $CB$ produced of an isosceles $\triangle ABC$ with $AB=AC$. If $AD \perp BC$ and $EF \perp AC$, prove that $\triangle ABD \sim \triangle ECF$.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $AB=AC$ and $AD \perp BC$. Side $CB$ is produced to $E$ and $EF \perp AC$.

**TO PROVE:** $\triangle ABD \sim \triangle ECF$.

**PROOF:** We know that the angles opposite to equal sides of a triangle are equal.

$\therefore \quad \angle B=\angle C \quad [\because AB=AC]$.

Now, in $\triangle ABD$ and $\triangle ECF$, we have

$\angle B=\angle C \quad $[proved above]

$$
\angle ADB=\angle EFC=90^{\circ}.
$$

$\therefore \quad \triangle ABD \sim \triangle ECF \quad $[by AA-similarity].

---

### Example: 26
Prove that the line segments joining the midpoints of the sides of a triangle form four triangles, each of which is similar to the original triangle.

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $D, E, F$ are the midpoints of $BC, CA$ and $AB$ respectively.

**TO PROVE:**
$$
\begin{aligned}
\triangle AFE &\sim \triangle ABC, \\
\triangle FBD &\sim \triangle ABC, \\
\triangle EDC &\sim \triangle ABC, \\
\text{and } \triangle DEF &\sim \triangle ABC.
\end{aligned}
$$

**PROOF:** We shall first show that $\triangle AFE \sim \triangle ABC$.

Since $F$ and $E$ are the midpoints of $AB$ and $AC$ respectively, so by the midpoint theorem, we have $FE \| BC$.

$\therefore \quad \angle AFE=\angle B \quad $[corresponding $\angle$s]

Now, in $\triangle AFE$ and $\triangle ABC$, we have

$\angle AFE=\angle B \quad $[corresponding $\angle$s]

and $\angle A=\angle A \quad $(common).

$\therefore \quad \triangle AFE \sim \triangle ABC$ [by AA-similarity].

Similarly, $\triangle FBD \sim \triangle ABC$ and $\triangle EDC \sim \triangle ABC$.

Now, we shall show that $\triangle DEF \sim \triangle ABC$.

In the same manner as above, we can prove that $ED \| AF$ and $DF \| EA$.

$\therefore \quad AFDE$ is a parallelogram.

$\therefore \quad \angle EDF=\angle A \quad $[opposite angles of a parallelogram].

Similarly, $BDEF$ is a parallelogram.

$\therefore \quad \angle DEF=\angle B \quad $[opposite angles of a parallelogram].

Thus, in $\triangle DEF$ and $\triangle ABC$, we have

$\angle EDF=\angle A$ and $\angle DEF=\angle B$.

$\therefore \quad \triangle DEF \sim \triangle ABC$ [by AA-similarity].

Hence, the result follows.

---

### Example: 27
In the given figure, $DEFG$ is a square and $\angle BAC=90^{\circ}$. Prove that
(i) $\triangle AGF \sim \triangle DBG$
(ii) $\triangle AGF \sim \triangle EFC$
(iii) $\triangle DBG \sim \triangle EFC$
(iv) $DE^{2}=BD \times EC$
[CBSE 2009]

#### Solution:
**GIVEN:** A $\triangle ABC$ in which $\angle BAC=90^{\circ}$ and $DEFG$ is a square.

**TO PROVE:**
(i) $\triangle AGF \sim \triangle DBG$
(ii) $\triangle AGF \sim \triangle EFC$
(iii) $\triangle DBG \sim \triangle EFC$
(iv) $DE^{2}=BD \times EC$

**PROOF:**
(i) In $\triangle AGF$ and $\triangle DBG$, we have
   $$
   \begin{aligned}
   & \angle GAF=\angle BDG=90^{\circ} \\
   & \angle AGF=\angle DBG \quad [\text{corresponding } \angle\text{s}] \\
   & \quad [\because GF \| BC \text{ and } AB \text{ is the transversal}] \\
   & \therefore \quad \triangle AGF \sim \triangle DBG.
   \end{aligned}
   $$

(ii) In $\triangle AGF$ and $\triangle EFC$, we have
   $$
   \begin{aligned}
   \angle FAG &= \angle CEF=90^{\circ} \\
   \angle GFA &= \angle FCE \quad [\text{corresponding } \angle\text{s}] \\
   & {[\because GF \| BC \text{ and } AC \text{ is the transversal}]} \\
   \therefore \quad \triangle AGF &\sim \triangle EFC.
   \end{aligned}
   $$

(iii) $\triangle DBG \sim \triangle AGF$ and $\triangle AGF \sim \triangle EFC$
   $$
   \Rightarrow \triangle DBG \sim \triangle EFC.
   $$

(iv)
   $$
   \begin{aligned}
   \triangle DBG \sim \triangle EFC &\Rightarrow \frac{BD}{FE}=\frac{DG}{EC} \\
   &\Rightarrow \frac{BD}{DE}=\frac{DE}{EC} \quad [\because DG=DE \text{ and } FE=DE]
   \end{aligned}
   $$
   Hence, $DE^{2}=BD \times EC$.

---

### Example: 28
Two right triangles $ABC$ and $DBC$ are drawn on the same hypotenuse $BC$ and on the same side of $BC$. If $AC$ and $BD$ intersect at $P$, prove that $AP \times PC=BP \times PD$. [CBSE 2000C]

#### Solution:
**GIVEN:** Right triangles $\triangle ABC$ and $\triangle DBC$ are drawn on the same hypotenuse $BC$ and on the same side of $BC$. Also, $AC$ and $BD$ intersect at $P$.

**TO PROVE:** $AP \times PC=BP \times PD$.

**PROOF:** In $\triangle BAP$ and $\triangle CDP$, we have

$$
\begin{aligned}
& \angle BAP=\angle CDP=90^{\circ} \\
& \angle BPA=\angle CPD \quad (\text{vert. opp. } \angle\text{s}) \\
\therefore \quad & \triangle BAP \sim \triangle CDP \quad \text{[by AA-similarity]} \\
\therefore \quad & \frac{AP}{DP}=\frac{BP}{CP}
\end{aligned}
$$

$\Rightarrow AP \times CP=BP \times DP \Rightarrow AP \times PC=BP \times PD$.

Hence, $AP \times PC=BP \times PD$.

---

### Example: 29
Through the midpoint $M$ of the side $CD$ of a parallelogram $ABCD$, the line $BM$ is drawn, intersecting $AC$ in $L$ and $AD$ produced in $E$. Prove that $EL=2 BL$. [CBSE 2006C, '08, '09]

#### Solution:
**GIVEN:** A parallelogram $ABCD$ and $M$ is the midpoint of $CD$. Line $BM$ is drawn, intersecting $AC$ in $L$ and $AD$ produced in $E$.

**TO PROVE:** $EL=2 BL$.

**PROOF:** In $\triangle BMC$ and $\triangle EMD$, we have

$$
\begin{array}{ll}
& \angle 1=\angle 2 \quad (\text{vert. opp. } \angle\text{s}) \\
& MC=MD \quad [M \text{ is the midpoint of } CD] \\
& \angle BCM=\angle EDM \quad [\text{alternate interior } \angle] \\
\therefore \quad & \triangle BMC \cong \triangle EMD \\
\therefore \quad & BC=DE. \\
\text{ But, } & BC=AD \quad [\text{opposite sides of a parallelogram}] \\
\therefore \quad & BC=AD=DE \Rightarrow AE=(AD+DE)=2BC. \quad \text{(i)}
\end{array}
$$

Now, in $\triangle AEL$ and $\triangle CBL$, we have

$$
\begin{array}{lll}
& \angle 6=\angle 5 & \text{(vert. opp. } \angle\text{s}) \\
& \angle 3=\angle 4 & \text{[alternate interior } \angle\text{]} \\
\therefore & \triangle AEL \sim \triangle CBL & {[\text{AA-similarity]}} \\
\Rightarrow & \frac{EL}{BL}=\frac{AE}{BC}=\frac{2BC}{BC}=2 \quad [\text{using (i)}] \\
\Rightarrow & EL=2BL. &
\end{array}
$$

Hence, $EL=2BL$.

---

### Example: 30
A lamp is 3.3 m above the ground. A boy 110 cm tall walks away from the base of this lamp post at a speed of $0.8 \text{ m/s}$. Find the length of the shadow of the boy after 4 seconds.

#### Solution:
Let $AB$ be the lamp post and $PQ$ be the boy, where $P$ is the position of the boy after 4 seconds.

$AP =$ distance moved in 4 s at $0.8 \text{ m/s} = (4 \times 0.8) \text{ m} = 3.2 \text{ m}$.

$PM$ is the length of shadow of the boy. Let $PM=x \text{ m}$.

In $\triangle AMB$ and $\triangle PMQ$, we have

$$
\angle MAB=\angle MPQ=90^{\circ}
$$

$[\because$ both the lamp post and the boy stand vertically erect]

$\angle AMB=\angle PMQ$ (common)

$\therefore \quad \triangle AMB \sim \triangle PMQ$ [by AA-similarity].

And so, $\frac{AM}{PM}=\frac{AB}{PQ}$ [corresponding sides of similar triangles are proportional]

$\Rightarrow \quad \frac{AP+PM}{PM}=\frac{AB}{PQ} \Rightarrow \frac{3.2+x}{x}=\frac{3.3}{1.1}$

$[\because AB=3.3 \text{ m}, PQ=110 \text{ cm} = 1.1 \text{ m}]$

$\Rightarrow 3.2+x=3x \Rightarrow 2x=3.2 \Rightarrow x=1.6$.

$\therefore \quad$ the length of the shadow of the boy after 4 seconds is $1.6 \text{ m}$.

---

### Example: 31
Sides $AB$ and $BC$ and median $AD$ of a triangle $ABC$ are respectively proportional to sides $PQ$ and $QR$ and median $PM$ of another triangle $PQR$, as shown in the figure. Prove that $\triangle ABC \sim \triangle PQR$.

#### Solution:
We have

$$
\begin{align*}
& \frac{AB}{PQ}=\frac{BC}{QR}=\frac{AD}{PM} \\
\Rightarrow \quad & \frac{AB}{PQ}=\frac{AD}{PM}=\frac{BC}{QR}=\frac{\frac{1}{2}BC}{\frac{1}{2}QR}=\frac{BD}{QM}. \quad \text{(i)}
\end{align*}
$$

In $\triangle ABD$ and $\triangle PQM$, we have

$$
\begin{array}{ll}
& \frac{AB}{PQ}=\frac{AD}{PM}=\frac{BD}{QM} \quad [\text{from (i)}] \\
\therefore \quad & \triangle ABD \sim \triangle PQM \quad [\text{by SSS-similarity}].
\end{array}
$$

And so, $\angle B=\angle Q$ [corresponding angles of similar triangles are equal].

Now, in $\triangle ABC$ and $\triangle PQR$, we have

$\angle B=\angle Q \quad $[proved above]

and $\frac{AB}{PQ}=\frac{BD}{QM} \quad $[ from (i) ].

$\therefore \quad \triangle ABC \sim \triangle PQR$ [by SAS-similarity].

---

### Example: 32
Sides $AB$ and $AC$ and median $AD$ of a triangle $ABC$ are respectively proportional to sides $PQ$ and $PR$ and median $PM$ of another triangle $PQR$. Prove that $\triangle ABC \sim \triangle PQR$.

#### Solution:
**GIVEN:** $AD$ and $PM$ are medians of $\triangle ABC$ and $\triangle PQR$ respectively such that

$$
\frac{AB}{PQ}=\frac{AC}{PR}=\frac{AD}{PM}.
$$

**TO PROVE:** $\triangle ABC \sim \triangle PQR$.

**CONSTRUCTION:** Produce $AD$ to $E$ such that $AD=DE$ and produce $PM$ to $N$ such that $PM=MN$. Join EC and NR.

**PROOF:** In $\triangle ABD$ and $\triangle ECD$, we have

$BD=CD \quad [\because D$ is the midpoint of $BC]$

$AD=ED \quad $[by construction]

$\angle BDA=\angle CDE \quad $[vertically opposite angles]

$\therefore \quad \triangle ABD \cong \triangle ECD$ [by SAS-congruency].

And so, $AB=EC \quad \ldots \text{(i) [cpct]}$

Similarly, $\triangle PQM \cong \triangle NRM$

and so, $PQ=NR \quad \ldots \text{(ii) [cpct]}$

Now, $\frac{AB}{PQ}=\frac{AC}{PR}=\frac{AD}{PM}$ (given)

$\Rightarrow \quad \frac{EC}{NR}=\frac{AC}{PR}=\frac{AD}{PM} \quad $[using (i) and (ii)]

$\Rightarrow \quad \frac{EC}{NR}=\frac{AC}{PR}=\frac{2AD}{2PM}=\frac{AE}{PN} \quad [\because 2AD=AE, 2PM=PN]$

$\Rightarrow \triangle ACE \sim \triangle PNR$ [SSS-similarity].

$\therefore \quad \angle 2=\angle 4$ [corresponding angles of similar triangles are equal].

Similarly, $\angle 1=\angle 3 \quad $[it can be proved by joining $BE$ and $QN$ and showing $\triangle ABE \sim \triangle PQN]$.

$\therefore \quad \angle 1+\angle 2=\angle 3+\angle 4$, i.e., $\angle BAC=\angle QPR$.

Now, in $\triangle ABC$ and $\triangle PQR$, we have

$$
\begin{array}{lll}
& \frac{AB}{PQ}=\frac{AC}{PR} & {[\text{given}]} \\
& \angle BAC=\angle QPR & {[\text{from (iii)}]} \\
\therefore & \triangle ABC \sim \triangle PQR \quad [\text{by SAS-similarity}].
\end{array}
$$

---
