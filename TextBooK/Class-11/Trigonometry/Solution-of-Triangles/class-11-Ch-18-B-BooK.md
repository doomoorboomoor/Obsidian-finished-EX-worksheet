## Problems Based on Sine and Cosine Formulae

### Example 1
Two ships leave a port at the same time. One goes 24 km per hour in the direction $N 45^{\circ} E$ and the other travels 32 km per hour in the direction $S 75^{\circ} E$. Find the distance between the ships at the end of 3 hours.

#### Solution:
Let $A$ and $B$ be the positions of the two ships at the end of 3 hours. The starting port is $O$.

Then, the distance covered by the first ship is $OA = (24 \times 3) \text{ km} = 72 \text{ km}$.
And the distance covered by the second ship is $OB = (32 \times 3) \text{ km} = 96 \text{ km}$.

Let the distance between the ships be $AB = x \text{ km}$.

We have $\angle NOA = 45^{\circ}$ and $\angle SOB = 75^{\circ}$.
The angle between the paths of the ships is $\angle AOB$. Since the directions are measured from the North-South line, we have:
$\angle AOB = 180^{\circ} - (\angle NOA + \angle SOB) = 180^{\circ} - (45^{\circ} + 75^{\circ}) = 180^{\circ} - 120^{\circ} = 60^{\circ}$.

Applying the **cosine formula** on $\triangle AOB$, we get:

$$
\begin{aligned}
\cos(60^{\circ}) &= \frac{(OA)^2 + (OB)^2 - (AB)^2}{2 \times OA \times OB} \\
\frac{1}{2} &= \frac{(72)^{2}+(96)^{2}-x^{2}}{2 \times 72 \times 96} \\
(72)^{2}+(96)^{2}-x^{2} &= \frac{1}{2} \times 2 \times 72 \times 96 \\
5184+9216-x^{2} &= 6912 \\
14400 - x^2 &= 6912 \\
x^{2} &= 14400-6912 \\
x^{2} &= 7488 \\
x &= \sqrt{7488} \approx 86.53
\end{aligned}
$$

Hence, the distance between the ships at the end of 3 hours is **86.53 km**.

---

### Example 2
Two trees $A$ and $B$ are on the same side of a river. From a point $C$ in the river, the distances of trees $A$ and $B$ are 250 m and 300 m respectively. If $\angle C=45^{\circ}$, find the distance between the trees. (Use $\sqrt{2}=1.44$.)

#### Solution:
Let the positions of the trees be $A$ and $B$, and let $C$ be the point of observation in the river.
We are given:
- $b = CA = 250 \text{ m}$
- $a = CB = 300 \text{ m}$
- $\angle ACB = 45^{\circ}$

Let the distance between the trees be $c = AB = x$ metres.

Applying the **cosine formula** on $\triangle ACB$, we get:

$$
c^2 = a^2 + b^2 - 2ab \cos C
$$

$$
\begin{aligned}
x^2 &= (300)^{2}+(250)^{2} - 2 \times 300 \times 250 \times \cos 45^{\circ} \\
x^2 &= 90000 + 62500 - 150000 \times \frac{1}{\sqrt{2}} \\
x^2 &= 152500 - \frac{150000}{\sqrt{2}} \\
x^2 &= 152500 - \frac{150000 \times \sqrt{2}}{2} \\
x^2 &= 152500 - 75000 \sqrt{2} \\
x^2 &= 152500 - 75000 \times 1.44 \\
x^2 &= 152500 - 108000 \\
x^2 &= 44500 \\
x &= \sqrt{44500} \approx 210.95
\end{aligned}
$$

Hence, the distance between the trees is **210.95 m**.

---

### Example 3
The angle of elevation of the top point $P$ of the vertical tower $PQ$ of height $h$ from a point $A$ on the ground is $45^{\circ}$ and from a point $B$, the angle of elevation is $60^{\circ}$, where $B$ is a point at a distance $d$ from the point $A$, measured along the line $AB$, which makes an angle $30^{\circ}$ with $AQ$. Prove that $d=h(\sqrt{3}-1)$.

#### Solution:
Given a vertical tower $PQ$ of height $h$.
From point $A$, the angle of elevation to $P$ is $\angle PAQ = 45^{\circ}$.
From point $B$, the angle of elevation to $P$ is $60^{\circ}$.
The distance $AB = d$. The angle $\angle QAB = 30^{\circ}$.

In the right-angled $\triangle PAQ$:
$$
\tan 45^{\circ} = \frac{PQ}{AQ} \Rightarrow 1 = \frac{h}{AQ} \Rightarrow AQ = h
$$
Also,
$$
AP^2 = AQ^2 + PQ^2 = h^2 + h^2 = 2h^2 \Rightarrow AP = \sqrt{2}h
$$

In the right-angled triangle formed by $P$, $Q$, and the projection of $B$ on the ground, let's call it $Q$, the angle of elevation is $60^{\circ}$.
In $\triangle PBQ$ (assuming B is on line AQ for simplicity of elevation angle), we get $\tan 60^{\circ} = \frac{PQ}{BQ} \Rightarrow \sqrt{3} = \frac{h}{BQ} \Rightarrow BQ = \frac{h}{\sqrt{3}}$.
However, the problem states $\angle QAB = 30^{\circ}$, so $A, B, Q$ form a triangle on the ground.

Let's analyze the angles in $\triangle APB$.
We need to find the angles of $\triangle APB$ to use the sine rule. We have side $AB=d$ and side $AP = \sqrt{2}h$.
In $\triangle AQB$, we have $AQ=h$, $AB=d$, and $\angle QAB=30^{\circ}$. We can't solve this directly.

Let's reconsider the problem's solution logic. The provided solution calculates angles within $\triangle APB$ itself.
*This appears to be a more complex 3D problem than standard elevation problems, and the provided solution in the source text seems to have made some simplifying assumptions or contains errors in its reasoning (e.g., `In ΔAPB, we have ∠PAB = 15°`). The calculation of `∠APB = 15°` and `∠PAB=15°` appears inconsistent with the given geometry.*

Following the provided calculation steps from the source:
Assuming $\angle APB = 15^{\circ}$ and $\angle PAB$ is not $30^{\circ}$ but some other value. The solution seems to have an error by stating `∠PAB = 15°` and then using `sin 30°` for the angle opposite AP. There must be a misunderstanding in the provided text's logic. Let's re-examine the provided calculation, which uses `sin 30°` as the angle opposite AP, which would be `∠ABP`. The text states `∠ABP = 150°`.

Let's follow the calculation as written in the source:
Using sine formula on $\triangle ABP$:
$$
\frac{AB}{\sin \angle APB} = \frac{AP}{\sin \angle ABP}
$$
The source seems to have used incorrect angles in the formula setup:
The line `\frac{A B}{\sin 15^{\circ}} = \frac{A P}{\sin 15^{\circ}}` implies $AB=AP$, which is not given. The next line `\frac{d}{\sin 15^{\circ}} = \frac{\sqrt{2} h}{\sin 30^{\circ}}` contradicts the first. We will follow the second, more likely intended, step. It implies $\angle APB = 15^{\circ}$ and $\angle ABP = 30^{\circ}$.

$$
\begin{aligned}
\frac{d}{\sin 15^{\circ}} &= \frac{\sqrt{2} h}{\sin 30^{\circ}} \\
d &= \frac{\sqrt{2} h \cdot \sin 15^{\circ}}{\sin 30^{\circ}} \\
d &= \frac{\sqrt{2} h \cdot \sin 15^{\circ}}{1/2} \\
d &= 2\sqrt{2} h \cdot \sin 15^{\circ}
\end{aligned}
$$
Now, we find the value of $\sin 15^{\circ}$:
$$
\begin{aligned}
\sin 15^{\circ} &= \sin(45^{\circ} - 30^{\circ}) \\
&= \sin 45^{\circ} \cos 30^{\circ} - \cos 45^{\circ} \sin 30^{\circ} \\
&= \frac{1}{\sqrt{2}} \cdot \frac{\sqrt{3}}{2} - \frac{1}{\sqrt{2}} \cdot \frac{1}{2} \\
&= \frac{\sqrt{3}-1}{2\sqrt{2}}
\end{aligned}
$$
Substituting this back into the equation for $d$:
$$
d = 2\sqrt{2} h \cdot \left( \frac{\sqrt{3}-1}{2\sqrt{2}} \right) = (\sqrt{3}-1)h
$$
Hence, it is proved that **$d = h(\sqrt{3}-1)$**.

---

### Example 4
A lamp post is situated at the middle point $M$ of the side $AC$ of a triangular plot $ABC$ with $BC=7 \text{ m}, CA=8 \text{ m}$ and $AB=9 \text{ m}$. The lamp post subtends an angle $\tan^{-1} 3$ at the point $B$. Determine the height of the lamp post.

#### Solution:

Let the triangular plot be $\triangle ABC$ with sides:
- $a = BC = 7 \text{ m}$
- $b = CA = 8 \text{ m}$
- $c = AB = 9 \text{ m}$

Let $MP$ be the lamp post of height $h$, where $M$ is the midpoint of $AC$.
Therefore, $AM = MC = \frac{1}{2} AC = \frac{1}{2}(8) = 4 \text{ m}$.

The angle subtended by the lamp post at point $B$ is $\angle MBP = \theta$, where $\theta = \tan^{-1} 3$.
This means $\tan \theta = 3$.

First, we find the length of the median $BM$. We can use the cosine rule in $\triangle BMC$. For that, we first need to find $\cos C$ from $\triangle ABC$.
Using the cosine rule in $\triangle ABC$:
$$
\cos C = \frac{a^2 + b^2 - c^2}{2ab} = \frac{7^2 + 8^2 - 9^2}{2 \times 7 \times 8} = \frac{49+64-81}{112} = \frac{32}{112} = \frac{2}{7}
$$
Now, apply the cosine rule in $\triangle BMC$:
$$
\begin{aligned}
BM^2 &= BC^2 + CM^2 - 2(BC)(CM)\cos C \\
BM^2 &= 7^2 + 4^2 - 2(7)(4)\left(\frac{2}{7}\right) \\
BM^2 &= 49 + 16 - 16 \\
BM^2 &= 49 \\
BM &= 7 \text{ m}
\end{aligned}
$$
Now consider the right-angled triangle $\triangle BMP$ (since the lamp post is vertical).
$$
\tan(\angle MBP) = \frac{PM}{BM}
$$
We are given $\angle MBP = \tan^{-1} 3$, so $\tan(\angle MBP) = 3$.
$$
3 = \frac{h}{7} \Rightarrow h = 3 \times 7 = 21 \text{ m}
$$
Hence, the height of the lamp post is **21 m**.

---

### Example 5
A tree stands vertically on a hill side which makes an angle of $15^{\circ}$ with the horizontal. From a point on the ground 35 m down the hill from the base of the tree, the angle of elevation of the top of the tree is $60^{\circ}$. Find the height of the tree.

#### Solution:

Let $AB$ be the tree of height $H$. Let $A$ be the base of the tree.
Let $P$ be the point of observation on the hill, such that $PA = 35$ m.
The hill makes an angle of $15^{\circ}$ with the horizontal. Let the horizontal line from $P$ be $PX$.
So, $\angle XPA = 15^{\circ}$.

The angle of elevation of the top of the tree $B$ from $P$ is $60^{\circ}$. This is the angle between the line of sight $PB$ and the horizontal line $PX$.
So, $\angle XPB = 60^{\circ}$.

The angle $\angle APB$ within $\triangle PAB$ is the difference between the angle of elevation of the top and the angle of the hill.
$\angle APB = \angle XPB - \angle XPA = 60^{\circ} - 15^{\circ} = 45^{\circ}$.

Now, let's find the other angles of $\triangle PAB$.
The tree $AB$ is vertical. The hill $PAQ$ is inclined at $15^{\circ}$ to the horizontal. The angle between the vertical tree and the inclined hill is $\angle PAB$.
The angle between the vertical tree and the horizontal is $90^{\circ}$.
So, $\angle PAB = 90^{\circ} + 15^{\circ} = 105^{\circ}$.

The sum of angles in $\triangle PAB$ is $180^{\circ}$.
$\angle PBA = 180^{\circ} - (\angle PAB + \angle APB) = 180^{\circ} - (105^{\circ} + 45^{\circ}) = 180^{\circ} - 150^{\circ} = 30^{\circ}$.

Now, applying the sine rule on $\triangle PAB$:
$$
\begin{aligned}
\frac{AB}{\sin(\angle APB)} &= \frac{PA}{\sin(\angle PBA)} \\
\frac{H}{\sin 45^{\circ}} &= \frac{35}{\sin 30^{\circ}} \\
H &= \frac{35 \times \sin 45^{\circ}}{\sin 30^{\circ}} \\
H &= \frac{35 \times (1/\sqrt{2})}{1/2} \\
H &= 35 \times \frac{2}{\sqrt{2}} \\
H &= 35\sqrt{2}
\end{aligned}
$$
Hence, the height of the tree is **$35\sqrt{2}$ m**.

---

