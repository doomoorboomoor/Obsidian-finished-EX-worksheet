## Shortest Distance between Two Lines

**COPLANAR LINES** Two lines lying in the same plane are called coplanar lines.
Coplanar lines are either parallel or intersecting.

**SKEW LINES** Two lines in space which are not coplanar are called skew lines.
Skew lines are neither parallel nor intersecting.

**line of shortest distance between two skew lines** If $L_{1}$ and $L_{2}$ are two skew lines then there is a unique line which is perpendicular to both the lines $L_{1}$ and $L_{2}$. This line is called the line of shortest distance between $L_{1}$ and $L_{2}$.

**shortest distance between two skew lines** The length of the line segment $\overrightarrow{P Q}$, intercepted by two skew lines $L_{1}$ and $L_{2}$ on the common perpendicular to both the lines, is called the shortest distance (SD) between $L_{1}$ and $L_{2}$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4_b06552ea878a34g-049.jpg?height=302&width=368&top_left_y=699&top_left_x=477)

**REMARK** If two lines in space intersect at a point then the shortest distance between them is zero.

---

## To Find the Shortest Distance between Two Skew Lines

### Vector Form

**THEOREM** The shortest distance between two skew lines $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and

$$
\begin{aligned}
& \vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}} \text { is given by } \\
& \qquad d=\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right|
\end{aligned}
$$

**PROOF** Let $L_{1}$ and $L_{2}$ be two skew lines whose vector equations are respectively

$$
\begin{equation*}
\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}} \tag{i}
\end{equation*}
$$

and $\vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}$.
Then, $L_{1}$ is parallel to $\overrightarrow{b_{1}}$ and passes through a point $A$, whose position vector is $\overrightarrow{a_{1}}$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4_b06552ea878a34g-049.jpg?height=250&width=439&top_left_y=1658&top_left_x=774)

And, $L_{2}$ is parallel to $\overrightarrow{b_{2}}$ and passes through a point $B$, whose position vector is $\overrightarrow{a_{2}}$.

Let $\overrightarrow{P Q}$ be the shortest-distance vector between $L_{1}$ and $L_{2}$.
Then, $\overrightarrow{P Q} \perp \overrightarrow{b_{1}}$ and $\overrightarrow{P Q} \perp \overrightarrow{b_{2}}$.

$$
\begin{aligned}
\therefore & \overrightarrow{P Q} \|\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right) . \\
\therefore & P Q=\mid \text { projection of } \overrightarrow{A B} \text { along }\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right) \mid \\
& =\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right| .
\end{aligned}
$$

**CONDITION FOR TWO GIVEN LINES TO INTERSECT** Suppose that the lines $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}$ intersect. Then, the shortest distance between them is zero.

$$
\therefore\left[\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \overrightarrow{b_{1}} \overrightarrow{b_{2}}\right]=0 .
$$

**REMARK** Two lines intersect only when the shortest distance between them is zero.

---

## Solved Examples

### Example 1:

Find the shortest distance between the lines whose vector equations are

$$
\begin{aligned}
\vec{r} & =(6 \hat{i}+2 \hat{j}+2 \hat{k})+\lambda(\hat{i}-2 \hat{j}+2 \hat{k}) \\
\text { and } \vec{r} & =(-4 \hat{i}-\hat{k})+\mu(3 \hat{i}-2 \hat{j}-2 \hat{k}) .
\end{aligned}
$$

[CBSE 2013C]

#### Solution:

Comparing the given equations with the standard equations $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\lambda \overrightarrow{b_{2}}$, we have

$$
\begin{aligned}
& \overrightarrow{a_{1}}=(6 \hat{i}+2 \hat{j}+2 \hat{k}), \overrightarrow{b_{1}}=(\hat{i}-2 \hat{j}+2 \hat{k}), \\
& \overrightarrow{a_{2}}=(-4 \hat{i}-\hat{k}) \text { and } \overrightarrow{b_{2}}=(3 \hat{i}-2 \hat{j}-2 \hat{k}) . \\
& \therefore \quad\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(-4 \hat{i}-\hat{k})-(6 \hat{i}+2 \hat{j}+2 \hat{k})=(-10 \hat{i}-2 \hat{j}-3 \hat{k}) \\
& \text { and, }\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\left|\begin{array}{rrr}
\hat{i} & \hat{j} & \hat{k} \\
1 & -2 & 2 \\
3 & -2 & -2
\end{array}\right|=(4+4) \hat{i}-(-2-6) \hat{j}+(-2+6) \hat{k} \\
&=(8 \hat{i}+8 \hat{j}+4 \hat{k}) .
\end{aligned}
$$

$$
\begin{aligned}
& \therefore \quad\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|=\sqrt{8^{2}+8^{2}+4^{2}}=\sqrt{64+64+16} \\
& \quad=\sqrt{144}=12 .
\end{aligned}
$$

$$
\begin{aligned}
\therefore \quad \mathrm{SD} & =\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right| \\
& =\left|\frac{(-10 \hat{i}-2 \hat{j}-3 \hat{k}) \cdot(8 \hat{i}+8 \hat{j}+4 \hat{k})}{12}\right|=\left|\frac{-80-16-12}{12}\right| \\
& =\left|\frac{-108}{12}\right|=|-9|=9 \text { units. }
\end{aligned}
$$

---

### Example 2:

Find the shortest distance between the lines $L_{1}$ and $L_{2}$ whose vector equations are given below:

$$
\begin{aligned}
L_{1}: \vec{r} & =\hat{i}+\hat{j}+\lambda(2 \hat{i}-\hat{j}+\hat{k}) \\
L_{2}: \vec{r} & =2 \hat{i}+\hat{j}-\hat{k}+\mu(3 \hat{i}-5 \hat{i}+2 \hat{k})
\end{aligned}
$$

[CBSE 2008C, '14]

#### Solution:

Comparing the given equations with the standard equations $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}$, we have

$$
\begin{aligned}
& \qquad \overrightarrow{a_{1}}=(\hat{i}+\hat{j}), \overrightarrow{b_{1}}=(2 \hat{i}-\hat{j}+\hat{k}) \\
& \overrightarrow{a_{2}}=(2 \hat{i}+\hat{j}-\hat{k}) \text { and } \overrightarrow{b_{2}}=(3 \hat{i}-5 \hat{j}+2 \hat{k})
\end{aligned}
$$

$\therefore \quad\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(2 \hat{i}+\hat{j}-\hat{k})-(\hat{i}+\hat{j})=(\hat{i}-\hat{k})$

$$
\begin{aligned}
\text { and, }\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
2 & -1 & 1 \\
3 & -5 & 2
\end{array}\right|=(-2+5) \hat{i}-(4-3) \hat{j}+(-10+3) \hat{k} \\
& =(3 \hat{i}-\hat{j}-7 \hat{k}) .
\end{aligned}
$$

$$
\therefore \quad\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|=\sqrt{3^{2}+(-1)^{2}+(-7)^{2}}=\sqrt{59} .
$$

$$
\begin{aligned}
\therefore \quad \mathrm{SD} & =\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right|=\frac{|(\hat{i}-\hat{k}) \cdot(3 \hat{i}-\hat{j}-7 \hat{k})|}{\sqrt{59}} \\
& =\frac{|3-0+7|}{\sqrt{59}}=\frac{10 \sqrt{59}}{59} \text { units. }
\end{aligned}
$$

---

### Example 3:

Find the shortest distance between the lines whose vector equations are

$$
\begin{aligned}
& \vec{r}=(1-t) \hat{i}+(t-2) \hat{j}+(3-2 t) \hat{k}, \text { and } \\
& \vec{r}=(s+1) \hat{i}+(2 s-1) \hat{j}-(2 s+1) \hat{k} .
\end{aligned}
$$

[CBSE 2011]

#### Solution:

The given equations can be written as

$$
\begin{aligned}
& \vec{r}=(\hat{i}-2 \hat{j}+3 \hat{k})+t(-\hat{i}+\hat{j}-2 \hat{k}), \text { and } \\
& \vec{r}=(\hat{i}-\hat{j}-\hat{k})+s(\hat{i}+2 \hat{j}-2 \hat{k})
\end{aligned}
$$

Comparing the given equations with the standard equations $\vec{r}=\overrightarrow{a_{1}}+t \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+s \overrightarrow{b_{2}}$, we get

$$
\begin{array}{ll} 
& \overrightarrow{a_{1}}=(\hat{i}-2 \hat{j}+3 \hat{k}), \overrightarrow{b_{1}}=(-\hat{i}+\hat{j}-2 \hat{k}) \\
& \overrightarrow{a_{2}}=(\hat{i}-\hat{j}-\hat{k}) \text { and } \overrightarrow{b_{2}}=(\hat{i}+2 \hat{j}-2 \hat{k})
\end{array}
$$

$\therefore \quad \left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(\hat{i}-\hat{j}-\hat{k})-(\hat{i}-2 \hat{j}+3 \hat{k})=(\hat{j}-4 \hat{k})$

and, $\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\left|\begin{array}{rrr}\hat{i} & \hat{j} & \hat{k} \\ -1 & 1 & -2 \\ 1 & 2 & -2\end{array}\right|$

$$
\begin{aligned}
& =(-2+4) \hat{i}-(2+2) \hat{j}+(-2-1) \hat{k} \\
& =(2 \hat{i}-4 \hat{j}-3 \hat{k}) .
\end{aligned}
$$

$$
\therefore \quad\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right| = \sqrt{2^{2}+(-4)^{2}+(-3)^{2}}=\sqrt{29} .
$$

$$
\begin{aligned}
\therefore \quad \mathrm{SD} & =\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right| \\
& =\frac{|(\hat{j}-4 \hat{k}) \cdot(2 \hat{i}-4 \hat{j}-3 \hat{k})|}{\sqrt{29}}=\frac{|0-4+12|}{\sqrt{29}} \\
& =\frac{8 \sqrt{29}}{29} \text { units. }
\end{aligned}
$$

---

### Example 4:

Show that the lines

$$
\vec{r}=(\hat{i}+\hat{j}-\hat{k})+\lambda(3 \hat{i}-\hat{j}) \text { and } \vec{r}=(4 \hat{i}-\hat{k})+\mu(2 \hat{i}+3 \hat{k})
$$

intersect. Find their point of intersection.
[CBSE 2014]

#### Solution:

Comparing the given equations with the standard equations

$$
\begin{aligned}
\vec{r}= & \overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}} \text { and } \vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}, \text { we get } \\
& \overrightarrow{a_{1}}=(\hat{i}+\hat{j}-\hat{k}), \overrightarrow{b_{1}}=(3 \hat{i}-\hat{j}), \\
& \overrightarrow{a_{2}}=(4 \hat{i}-\hat{k}) \text { and } \overrightarrow{b_{2}}=(2 \hat{i}+3 \hat{k}) .
\end{aligned}
$$

$\therefore \quad \left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(4 \hat{i}-\hat{k})-(\hat{i}+\hat{j}-\hat{k})=(3 \hat{i}-\hat{j}) .$

And, $\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\left|\begin{array}{rrr}\hat{i} & \hat{j} & \hat{k} \\ 3 & -1 & 0 \\ 2 & 0 & 3\end{array}\right|=(-3-0) \hat{i}-(9-0) \hat{j}+(0+2) \hat{k}$

$$
\begin{aligned}
&\left.\therefore \quad\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|=\sqrt{(-3)^{2}+(-9)^{2}+2^{2}}=\sqrt{94}+2 \hat{k}\right) . \\
& \therefore \quad \mathrm{SD}=\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right| \\
&=\frac{|(3 \hat{i}-\hat{j}) \cdot(-3 \hat{i}-9 \hat{j}+2 \hat{k})|}{\sqrt{94}} \\
&=\frac{|-9+9+0|}{\sqrt{94}}=0 .
\end{aligned}
$$

Thus, the shortest distance between the given lines is 0.
Hence, the given lines intersect.
Thus, for some particular values of $\lambda$ and $\mu$, we have

$$
\begin{aligned}
& (\hat{i}+\hat{j}-\hat{k})+\lambda(3 \hat{i}-\hat{j})=(4 \hat{i}-\hat{k})+\mu(2 \hat{i}+3 \hat{k}) \\
\Rightarrow & (1+3 \lambda) \hat{i}+(1-\lambda) \hat{j}-\hat{k}=(4+2 \mu) \hat{i}+(3 \mu-1) \hat{k} \\
\Rightarrow & 1+3 \lambda=4+2 \mu, 1-\lambda=0 \text { and } 3 \mu-1=-1 \\
\Rightarrow & \lambda=1 \text { and } \mu=0 .
\end{aligned}
$$

Thus, the position vector of the point of intersection of the given lines is given by

$\vec{r}=(\hat{i}+\hat{j}-\hat{k})+(3 \hat{i}-\hat{j}) \quad[\text { putting } \lambda=1], \text { i.e., } \vec{r}=(4 \hat{i}-\hat{k}) .$

Hence, the point of intersection of the given lines is $P(4,0,-1)$.

---

### Example 5:

Show that the lines

$$
\vec{r}=(\hat{i}-\hat{j})+\lambda(2 \hat{i}+\hat{k}) \text { and } \vec{r}=(2 \hat{i}-\hat{j})+\mu(\hat{i}+\hat{j}-\hat{k})
$$

do not intersect.
[CBSE 2012C]

#### Solution:

Comparing the given equations with the standard equations $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}$, we get

$$
\begin{array}{ll} 
& \overrightarrow{a_{1}}=(\hat{i}-\hat{j}), \overrightarrow{b_{1}}=(2 \hat{i}+\hat{k}) \\
& \overrightarrow{a_{2}}=(2 \hat{i}-\hat{j}) \text { and } \overrightarrow{b_{2}}=(\hat{i}+\hat{j}-\hat{k})
\end{array}
$$

$\therefore \quad \left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(2 \hat{i}-\hat{j})-(\hat{i}-\hat{j})=\hat{i}$

$$
\begin{aligned}
\text { And, } & \left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\left|\begin{array}{rrr}
\hat{i} & \hat{j} & \hat{k} \\
2 & 0 & 1 \\
1 & 1 & -1
\end{array}\right|=(0-1) \hat{i}-(-2-1) \hat{j}+(2-0) \hat{k} \\
& =(-\hat{i}+3 \hat{j}+2 \hat{k})
\end{aligned}
$$

$\therefore \quad\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|=\sqrt{(-1)^{2}+3^{2}+2^{2}}=\sqrt{14}$

$$
\begin{aligned}
\therefore \quad \mathrm{SD} & =\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right| \\
& =\left|\frac{\hat{i} \cdot(-\hat{i}+3 \hat{j}+2 \hat{k})}{\sqrt{14}}\right|=\frac{|-1|}{\sqrt{14}} \\
& =\frac{1 \times \sqrt{14}}{14}=\frac{\sqrt{14}}{14} \neq 0
\end{aligned}
$$

Since the shortest distance between the given lines is not zero, the given lines do not intersect.

---

### Distance between Parallel Lines

**distance between parallel lines** Let $L_{1}$ and $L_{2}$ be two parallel lines. Then, these lines are clearly coplanar.

Let the equations of these lines be

$$
\begin{align*}
& \vec{r}=\overrightarrow{a_{1}}+\lambda \vec{b}  \tag{i}\\
& \vec{r}=\overrightarrow{a_{2}}+\mu \vec{b} \tag{ii}
\end{align*}
$$

Let $A$ be a point on $L_{1}$ with position vector $\overrightarrow{a_{1}}$ and let $B$ be a point on $L_{2}$ with position vector $\overrightarrow{a_{2}}$.

Draw $B M \perp L_{1}$. Then,
distance between $L_{1}$ and $L_{2}=|\overrightarrow{B M}|$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4_b06552ea878a34g-054.jpg?height=225&width=433&top_left_y=1314&top_left_x=774)

Let $\theta$ be the angle between $\overrightarrow{A B}$ and $\vec{b}$. Then,

$(\vec{b} \times \overrightarrow{A B})=\{|\vec{b}||\overrightarrow{A B}| \cdot \sin \theta\} \hat{n},$

where $\hat{n}$ is a unit vector, perpendicular to the plane of $L_{1}$ and $L_{2}$.

$$
\begin{array}{ll}
\therefore & \vec{b} \times\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=\{|\vec{b}||\overrightarrow{A B}| \cdot \sin \theta\} \hat{n} \\
\Rightarrow & \vec{b} \times\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=|\vec{b}|(B M) \vec{n} \quad\{\because \quad(A B) \sin \theta=B M\} \\
\Rightarrow & \left|\vec{b} \times\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)\right|=|\vec{b}||\overrightarrow{B M}| \cdot 1 \quad[\because|\hat{n}|=1]
\end{array}
$$

$$
\Rightarrow|\overrightarrow{B M}|=\left|\frac{\vec{b} \times\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)}{|\vec{b}|}\right| .
$$

---

### Example 6:

Find the shortest distance between the lines $L_{1}$ and $L_{2}$, given by

$$
\vec{r}=\hat{i}+\hat{j}+\lambda(2 \hat{i}-\hat{j}+\hat{k}) \text { and } \vec{r}=2 \hat{i}+\hat{j}-\hat{k}+\mu(4 \hat{i}-2 \hat{j}+2 \hat{k})
$$

#### Solution:

The given lines are

$$
\begin{align*}
& L_{1}: \vec{r}=(\hat{i}+\hat{j})+\lambda(2 \hat{i}-\hat{j}+\hat{k})  \tag{i}\\
& L_{2}: \vec{r}=(2 \hat{i}+\hat{j}-\hat{k})+2 \mu(2 \hat{i}-\hat{j}+\hat{k}) \tag{ii}
\end{align*}
$$

These equations are of the form:

$$
\begin{aligned}
& \vec{r}=\overrightarrow{a_{1}}+\lambda \vec{b} \text { and } \vec{r}=\overrightarrow{a_{2}}+2 \mu \vec{b}=\overrightarrow{a_{2}}+\mu^{\prime} \vec{b} \text {, where } \\
& \overrightarrow{a_{1}}=(\hat{i}+\hat{j}), \overrightarrow{a_{2}}=(2 \hat{i}+\hat{j}-\hat{k}), \vec{b}=(2 \hat{i}-\hat{j}+\hat{k}) \text { and } \mu^{\prime}=2 \mu
\end{aligned}
$$

Clearly, the given lines are parallel.
Now, $\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(2 \hat{i}+\hat{j}-\hat{k})-(\hat{i}+\hat{j})=(\hat{i}-\hat{k})$

$$
\begin{aligned}
\therefore \quad\left\{\vec{b} \times\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)\right\} & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
2 & -1 & 1 \\
1 & 0 & -1
\end{array}\right| \\
& =(1-0) \hat{i}-(-2-1) \hat{j}+(0+1) \hat{k} \\
& =(\hat{i}+3 \hat{j}+\hat{k})
\end{aligned}
$$

$\Rightarrow\left|\vec{b} \times\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)\right| =\sqrt{1^{2}+3^{2}+1^{2}}=\sqrt{11}$
and $|\vec{b}| =\sqrt{2^{2}+(-1)^{2}+1^{2}}=\sqrt{6}$

$\Rightarrow$ shortest distance between $L_{1}$ and $L_{2}$
= distance between $L_{1}$ and $L_{2}$

$$
\begin{aligned}
& =\frac{\left|\vec{b} \times\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)\right|}{|\vec{b}|}=\frac{\sqrt{11}}{\sqrt{6}} \\
& =\left(\frac{\sqrt{11}}{\sqrt{6}} \times \frac{\sqrt{6}}{\sqrt{6}}\right)=\frac{\sqrt{66}}{6} \text { units. }
\end{aligned}
$$

---

### Example 7:

Write the vector equations of the following lines and hence find the shortest distance between them:

$$
\frac{x+1}{2}=\frac{y+1}{-6}=\frac{z+1}{1} \text { and } \frac{x-3}{1}=\frac{y-5}{-2}=\frac{z-7}{1}
$$

[CBSE 2008, '14]

#### Solution:

The given lines are

$$
\begin{equation*}
\frac{x+1}{2}=\frac{y+1}{-6}=\frac{z+1}{1} \tag{i}
\end{equation*}
$$

and $\frac{x-3}{1}=\frac{y-5}{-2}=\frac{z-7}{1}$. (ii)

The line (i) passes through the point $(-1,-1,-1)$ and has d.r.'s. $7,-6,1$.
So, its vector equation is

$$
\begin{equation*}
\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}, \tag{iii}
\end{equation*}
$$

where $\overrightarrow{a_{1}}=(-\hat{i}-\hat{j}-\hat{k})$ and $\overrightarrow{b_{1}}=7 \hat{i}-6 \hat{j}+\hat{k}$.
The line (ii) passes through the point $(3,5,7)$ and has d.r.'s. $1,-2,1$. So, its vector equation is

$$
\begin{equation*}
\vec{r}=\overrightarrow{a_{2}}+\lambda \overrightarrow{b_{2}}, \tag{iv}
\end{equation*}
$$

where $\overrightarrow{a_{2}}=(3 \hat{i}+5 \hat{j}+7 \hat{k})$ and $\overrightarrow{b_{2}}=\hat{i}-2 \hat{j}+\hat{k}$.
$\therefore \quad\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(3 \hat{i}+5 \hat{j}+7 \hat{k})-(-\hat{i}-\hat{j}-\hat{k})=(4 \hat{i}+6 \hat{j}+8 \hat{k})$

$$
\begin{aligned}
& \text { and }\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\left|\begin{array}{crr}
\hat{i} & \hat{j} & \hat{k} \\
7 & -6 & 1 \\
1 & -2 & 1
\end{array}\right|=(-6+2) \hat{i}-(7-1) \hat{j}+(-14+6) \hat{k} \\
& \quad=(-4 \hat{i}-6 \hat{j}-8 \hat{k}) .
\end{aligned}
$$

$\therefore \quad\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|=\sqrt{(-4)^{2}+(-6)^{2}+(-8)^{2}}=\sqrt{16+36+64}=\sqrt{116} .$

$$
\begin{aligned}
\therefore \quad \mathrm{SD} & =\left|\frac{\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)}{\left|\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right|}\right|=\left|\frac{(4 \hat{i}+6 \hat{j}+8 \hat{k}) \cdot(-4 \hat{i}-6 \hat{j}-8 \hat{k})}{\sqrt{116}}\right| \\
& =\frac{|(-16-36-64)|}{\sqrt{116}}=\frac{|-116|}{\sqrt{116}}=\frac{116}{\sqrt{116}} \times \frac{\sqrt{116}}{\sqrt{116}} \\
& =\sqrt{116}=\sqrt{4 \times 29}=2 \sqrt{29} \text { units. }
\end{aligned}
$$

---