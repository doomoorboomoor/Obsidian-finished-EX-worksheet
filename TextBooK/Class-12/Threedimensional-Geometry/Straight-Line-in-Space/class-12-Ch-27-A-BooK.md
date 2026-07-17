## 27. Equation of a Line Passing through a Given Point and Parallel to a Given Vector

### Vector Form

**THEOREM 1** The vector equation of a straight line passing through a given point with position vector $\overrightarrow{r_{1}}$ and parallel to a given vector $\vec{m}$ is $\vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m}$, where $\lambda$ is a scalar.

**PROOF** Let $L$ be the line, passing through a given point $A$ with position vector $\overrightarrow{r_{1}}$ and parallel to a given vector $\vec{m}$.
Let $O$ be the origin. Then, $\overrightarrow{O A}=\overrightarrow{r_{1}}$.
Let $P$ be an arbitrary point on $L$, and let the position vector of $P$ be $\vec{r}$.
Then, $\overrightarrow{O P}=\vec{r}$.
Clearly, $\overrightarrow{A P} \| \vec{m}$

$$
\begin{aligned}
& \Rightarrow \overrightarrow{A P}=\lambda \vec{m}, \text { for some scalar } \lambda \\
& \Rightarrow(\text { p.v. of } P)-(\text { p.v. of } A)=\lambda \vec{m} \\
& \Rightarrow \overrightarrow{O P}-\overrightarrow{O A}=\lambda \vec{m} \\
& \Rightarrow \vec{r}-\overrightarrow{r_{1}}=\lambda \vec{m} \\
& \Rightarrow \vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m}
\end{aligned}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-001.jpg)

Clearly, every point on the line $L$ satisfies (i), and for any value of $\lambda$, (i) gives the position vector of a point $P$ on the line.
Hence, $\vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m}$ is the desired equation.

**COROLLARY** The vector equation of a straight line passing through the origin and parallel to a given vector $\vec{m}$ is $\vec{r}=\lambda \vec{m}$.

**PROOF** Taking $\overrightarrow{r_{1}}=\overrightarrow{0}$ in (i), we get the desired equation, $\vec{r}=\lambda \vec{m}$.

---

### Cartesian Form

**THEOREM 2** The equations of a straight line with direction ratios $a, b, c$, and passing through a point $A\left(x_{1}, y_{1}, z_{1}\right)$ are

$$
\frac{x-x_{1}}{a}=\frac{y-y_{1}}{b}=\frac{z-z_{1}}{c} .
$$

**PROOF** We know that the vector equation of a straight line passing through a fixed point $A\left(x_{1}, y_{1}, z_{1}\right)$ with position vector $\overrightarrow{r_{1}}$ and parallel to a given vector $\vec{m}$ is given by

$$
\vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m} \quad \ldots \text { (i), where } \lambda \text { is a scalar. }
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-002.jpg)

Let $P(x, y, z)$ be the given point on line with position vector $\vec{r}$.
Then, $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}$ and $\vec{r}_{1}=x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}$.
Since the direction ratios of the given line are $a, b, c$, and this line is parallel to $\vec{m}$, the direction ratios of $\vec{m}$ are $a, b, c$.
$\therefore \vec{m}=a \hat{i}+b \hat{j}+c \hat{k}$.
Putting $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}, \overrightarrow{r_{1}}=x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}$ and $\vec{m}=a \hat{i}+b \hat{j}+c \hat{k}$ in (i), we get the equation of the line as

$$
\begin{aligned}
& (x \hat{i}+y \hat{j}+z \hat{k})=\left(x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}\right)+\lambda(a \hat{i}+b \hat{j}+c \hat{k}) \\
\Rightarrow & (x \hat{i}+y \hat{j}+z \hat{k})=\left(x_{1}+\lambda a\right) \hat{i}+\left(y_{1}+\lambda b\right) \hat{j}+\left(z_{1}+\lambda c\right) \hat{k} \\
\Rightarrow & x=x_{1}+\lambda a, y=y_{1}+\lambda b \text { and } z=z_{1}+\lambda c \\
\Rightarrow & \frac{x-x_{1}}{a}=\frac{y-y_{1}}{b}=\frac{z-z_{1}}{c}=\lambda
\end{aligned}
$$

Hence, the equations of a line having direction ratios $a, b, c$ and passing through $A\left(x_{1}, y_{1}, z_{1}\right)$ are

$$
\frac{x-x_{1}}{a}=\frac{y-y_{1}}{b}=\frac{z-z_{1}}{c} .
$$

**COROLLARY** The equations of a line having direction cosines $l, m, n$ and passing through $\left(x_{1}, y_{1}, z_{1}\right)$ are

$$
\frac{x-x_{1}}{l}=\frac{y-y_{1}}{m}=\frac{z-z_{1}}{n} .
$$

**PROOF** Since the direction cosines of a line are proportional to the direction ratios of the line, the result follows.

---

## Equation of a Line Passing through Two Given Points

### Vector Form

**THEOREM 3** The vector equation of a straight line passing through two points with position vectors $\overrightarrow{r_{1}}$ and $\overrightarrow{r_{2}}$ is given by $\vec{r}=\overrightarrow{r_{1}}+\lambda\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right)$.

**PROOF** Let $L$ be the given line, passing through two given points $A$ and $B$ with position vectors $\overrightarrow{r_{1}}$ and $\overrightarrow{r_{2}}$ respectively.
Let $O$ be the origin.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-003.jpg)

Then, $\overrightarrow{O A}=\overrightarrow{r_{1}}$ and $\overrightarrow{O B}=\overrightarrow{r_{2}}$.
$\therefore \overrightarrow{A B}=($ p.v. of $B)-($ p.v. of $A)=\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right)$.
Let $P$ be an arbitrary point on $L$, having the position vector $\vec{r}$.
Then, $\overrightarrow{O P}=\vec{r}$.

$$
\begin{aligned}
\therefore \overrightarrow{A P} & =(\text { p.v. of } P)-(\text { p.v. of } A) \\
& =(\overrightarrow{O P}-\overrightarrow{O A})=\left(\vec{r}-\overrightarrow{r_{1}}\right)
\end{aligned}
$$

Since $\overrightarrow{A P}$ and $\overrightarrow{A B}$ are collinear vectors, we have

$$
\begin{aligned}
& \overrightarrow{A P}=\lambda(\overrightarrow{A B}), \text { for some scalar } \lambda \\
\Rightarrow & \left(\vec{r}-\overrightarrow{r_{1}}\right)=\lambda\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right) \\
\Rightarrow & \vec{r}=\overrightarrow{r_{1}}+\lambda\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right)
\end{aligned}
$$

Hence, the vector equation of a line $L$, passing through two given points $A$ and $B$ with position vectors $\overrightarrow{r_{1}}$ and $\overrightarrow{r_{2}}$, is given by

$$
\vec{r}=\overrightarrow{r_{1}}+\lambda\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right)
$$

---

### Cartesian Form

**THEOREM 4** The equations of a line passing through two given points $A\left(x_{1}, y_{1}, z_{1}\right)$ and $B\left(x_{2}, y_{2}, z_{2}\right)$ are given by

$$
\frac{x-x_{1}}{x_{2}-x_{1}}=\frac{y-y_{1}}{y_{2}-y_{1}}=\frac{z-z_{1}}{z_{2}-z_{1}}
$$

**PROOF** We know that the vector equation of a line passing through two points $A$ and $B$ with position vectors $\overrightarrow{r_{1}}$ and $\overrightarrow{r_{2}}$ is given by

$$
\begin{equation*}
\vec{r}=\overrightarrow{r_{1}}+\lambda\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right) . \tag{i}
\end{equation*}
$$

Let $A\left(x_{1}, y_{1}, z_{1}\right)$ and $B\left(x_{2}, y_{2}, z_{2}\right)$ be the points on the given line with position vectors $\overrightarrow{r_{1}}$ and $\overrightarrow{r_{2}}$ respectively.
Let $P(x, y, z)$ be an arbitrary point on this line with position vector $\vec{r}$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-004.jpg)

Then, $\overrightarrow{r_{1}}=x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}, \overrightarrow{r_{2}}=x_{2} \hat{i}+y_{2} \hat{j}+z_{2} \hat{k}$ and $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}$.
Substituting these values in (i), we get

$$
\begin{aligned}
& & \hat{i}+y \hat{j}+z \hat{k}=\left(x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}\right)+\lambda\left[\left(x_{2}-x_{1}\right) \hat{i}\right. \\
& & \left.+\left(y_{2}-y_{1}\right) \hat{j}+\left(z_{2}-z_{1}\right) \hat{k}\right] \\
\Rightarrow & & \left(x-x_{1}\right) \hat{i}+\left(y-y_{1}\right) \hat{j}+\left(z-z_{1}\right) \hat{k} \\
& & =\lambda\left[\left(x_{2}-x_{1}\right) \hat{i}+\left(y_{2}-y_{1} \hat{j}+\left(z_{2}-z_{1}\right) \hat{k}\right]\right. \\
\Rightarrow & & \left(x-x_{1}\right)=\lambda\left(x_{2}-x_{1}\right),\left(y-y_{1}\right)=\lambda\left(y_{2}-y_{1}\right) \text { and }\left(z-z_{1}\right)=\lambda\left(z_{2}-z_{1}\right) \\
\Rightarrow & & \frac{\left(x-x_{1}\right)}{\left(x_{2}-x_{1}\right)}=\frac{\left(y-y_{1}\right)}{\left(y_{2}-y_{1}\right)}=\frac{\left(z-z_{1}\right)}{\left(z_{2}-z_{1}\right)}(=\lambda),
\end{aligned}
$$

which are the required equations.

---

## SUMMARY

1.  (i) If a line passes through a point with p.v. $\overrightarrow{r_{1}}$ and it is parallel to $\vec{m}$ then its vector equation is:

    $$
    \vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m}
    $$

    (ii) If a line passes through a point $A\left(x_{1}, y_{1} . z_{1}\right)$ and it has d.r.'s $a, b, c$ then its Cartesian equations are:

    $$
    \frac{x-x_{1}}{a}=\frac{y-y_{1}}{b}=\frac{z-z_{1}}{c} .
    $$

2.  (i) If a line passes through two points having p.v.'s $\overrightarrow{r_{1}}$ and $\overrightarrow{r_{2}}$, then its vector equation is:

    $$
    \vec{r}=\overrightarrow{r_{1}}+\lambda\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right) .
    $$

    (ii) If a line passes through two points $A\left(x_{1}, y_{1}, z_{1}\right)$ and $B\left(x_{2}, y_{2}, z_{2}\right)$ then its Cartesian equations are:

    $$
    \frac{x-x_{1}}{x_{2}-x_{1}}=\frac{y-y_{1}}{y_{2}-y_{1}}=\frac{z-z_{1}}{z_{2}-z_{1}} .
    $$

---

## SOLVED EXAMPLES

### Example 1:

Find the vector equation of a line which is parallel to the vector $(2 \hat{i}-\hat{j}+3 \hat{k})$ and which passes through the point $(5,-2,4)$. Also find its Cartesian equations.
[CBSE 2007]

#### Solution:

**Vector equation of the given line:**
The given line passes through the point $A(5,-2,4)$ and it is parallel to the vector $\vec{m}=(2 \hat{i}-\hat{j}+3 \hat{k})$.

The position vector of $A$ is given by $\overrightarrow{r_{1}}=(5 \hat{i}-2 \hat{j}+4 \hat{k})$.
Hence, the vector equation of the given line is

$$
\begin{equation*}
\vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m} \Rightarrow \vec{r}=(5 \hat{i}-2 \hat{j}+4 \hat{k})+\lambda(2 \hat{i}-\hat{j}+3 \hat{k}) \tag{i}
\end{equation*}
$$

**Cartesisan equation of the given line:**
Taking $\vec{r}=(x \hat{i}+y \hat{j}+z \hat{k})$, equation (i) becomes:

$$
\begin{aligned}
& (x \hat{i}+y \hat{j}+z \hat{k})=(5 \hat{i}-2 \hat{j}+4 \hat{k})+\lambda(2 \hat{i}-\hat{j}+3 \hat{k}) \\
\Rightarrow & (x \hat{i}+y \hat{j}+z \hat{k})=(5+2 \lambda) \hat{i}-(2+\lambda) \hat{j}+(4+3 \lambda) \hat{k} \\
\Rightarrow & x=5+2 \lambda, y=-(2+\lambda) \text { and } z=4+3 \lambda \\
\Rightarrow & \frac{x-5}{2}=\frac{y+2}{-1}=\frac{z-4}{3}=\lambda
\end{aligned}
$$

Hence, $\frac{x-5}{2}=\frac{y+2}{-1}=\frac{z-4}{3}$ are the required equations of the given line in Cartesian form.

---

### Example 2:

The Cartesian equations of a line are $3 x-3=2 y+1=5-6 z$.
(a) Write these equations in standard form and find the direction ratios of the given line.
(b) Write the equation of the given line in vector form.

#### Solution:

(a) The given equations may be written as

$$
\begin{aligned}
& 3(x-1)=2\left(y+\frac{1}{2}\right)=-6\left(z-\frac{5}{6}\right) \\
\Rightarrow & \frac{(x-1)}{\left(\frac{1}{3}\right)}=\frac{\left(y+\frac{1}{2}\right)}{\left(\frac{1}{2}\right)}=\frac{\left(z-\frac{5}{6}\right)}{\left(\frac{-1}{6}\right)} \\
\Rightarrow & \frac{(x-1)}{2}=\frac{\left(y+\frac{1}{2}\right)}{3}=\frac{\left(z+\frac{5}{6}\right)}{-1} \quad \text { [on dividing each by } 6 \text { ]. }
\end{aligned}
$$

This is the standard form of the given equations in Cartesian form. Clearly, its direction ratios are $2,3,-1$.

(b) The given line passes through the point $A\left(1, \frac{-1}{2}, \frac{5}{6}\right)$ and it is parallel to the vector $\vec{m}=(2 \hat{i}+3 \hat{j}-\hat{k})$.
The position vector of the point $A$ is $\overrightarrow{r_{1}}=\left(\hat{i}-\frac{1}{2} \hat{j}+\frac{5}{6} \hat{k}\right)$.

So, the vector equation of the given line is

$$
\vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m} \Rightarrow \vec{r}=\left(\hat{i}-\frac{1}{2} \hat{j}+\frac{5}{6} \hat{k}\right)+\lambda(2 \hat{i}+3 \hat{j}-\hat{k})
$$

---

### Example 3:

The Cartesian equations of a line are $6 x-2=3 y+1=2 z-2$.
(a) Write these equations in standard form and find the direction cosines of the given line.
(b) Write down the Cartesian and vector equations of a line, passing through $(2,-1,1)$ and parallel to the given line.
[CBSE 2013C]

#### Solution:

(a) The given equations may be written as

$$
\begin{aligned}
& 6\left(x-\frac{1}{3}\right)=3\left(y+\frac{1}{3}\right)=2(z-1) \\
\Rightarrow & \frac{\left(x-\frac{1}{3}\right)}{\left(\frac{1}{6}\right)}=\frac{\left(y+\frac{1}{3}\right)}{\left(\frac{1}{3}\right)}=\frac{(z-1)}{\left(\frac{1}{2}\right)} \\
\Rightarrow & \frac{\left(x-\frac{1}{3}\right)}{1}=\frac{\left(y+\frac{1}{3}\right)}{2}=\frac{(z-1)}{3} \quad \text { [on dividing each by } 6 \text { ] }
\end{aligned}
$$

This is the standard form of the given equations in Cartesian form. The direction ratios of the given are $1,2,3$.
Also, $\sqrt{1^{2}+2^{2}+3^{2}}=\sqrt{14}$.
So, the direction cosines of the given line are $\frac{1}{\sqrt{14}}, \frac{2}{\sqrt{14}}, \frac{3}{\sqrt{14}}$.

(b) The required line passes through the point $A(2,-1,1)$ and it is parallel to the line having direction ratios $1,2,3$.
The equations of this line in Cartesian form are given by

$$
\begin{equation*}
\frac{x-2}{1}=\frac{y+1}{2}=\frac{z-1}{3} . \tag{i}
\end{equation*}
$$

The position vector of the point $A$ is $\overrightarrow{r_{1}}=(2 \hat{i}-\hat{j}+\hat{k})$.
The required line is parallel to the vector $\vec{m}=(\hat{i}+2 \hat{j}+3 \hat{k})$.
So, its equation in vector form is

$$
\begin{equation*}
\vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m} \Rightarrow \vec{r}=(2 \hat{i}-\hat{j}+\hat{k})+\lambda(\hat{i}+2 \hat{j}+3 \hat{k}) \tag{ii}
\end{equation*}
$$

Thus, the Cartesian and vector forms of equations of the desired line are given by (i) and (ii) respectively.

---

### Example 4:

Find the vector and Cartesian equations of the line passing through the point $(1,2,-4)$ and perpendicular to each of the lines

$$
\begin{equation*}
\frac{x-8}{3}=\frac{y+19}{-16}=\frac{z-10}{7} \text { and } \frac{x-15}{3}=\frac{y+29}{8}=\frac{z-5}{-5} \tag{CBSE2012}
\end{equation*}
$$

#### Solution:

The given lines are

$$
\begin{array}{r}
\frac{x-8}{3}=\frac{y+19}{-16}=\frac{z-10}{7} \\
\text { and } \frac{x-15}{3}=\frac{y+29}{8}=\frac{z-5}{-5} \tag{ii}
\end{array}
$$

Let $a, b, c$ be the direction ratios of the required line.
Then, it being perpendicular to each of the lines (i) and (ii), we have $3 a-16 b+7 c=0$ and $3 a+8 b-5 c=0$.
On solving these equations by cross multiplication, we get

$$
\begin{aligned}
\frac{a}{(80-56)} & =\frac{b}{(21+15)}=\frac{c}{(24+48)} \\
\Rightarrow \quad \frac{a}{24}=\frac{b}{36} & =\frac{c}{72} \Rightarrow \frac{a}{2}=\frac{b}{3}=\frac{c}{6}
\end{aligned}
$$

Thus, the desired line has direction ratios 2, 3, 6 .
So, we have to find the equations of a line passing through the point $A(1,2,-4)$ and having $2,3,6$ as its direction ratios.
So, the required equations in Cartesian form are

$$
\frac{(x-1)}{2}=\frac{(y-2)}{3}=\frac{(z+4)}{6} .
$$

The position vector of point $A$ is $\overrightarrow{r_{1}}=(\hat{i}+2 \hat{j}-4 \hat{k})$.
Also, the required line has direction ratios $2,3,6$ and so it is parallel to the vector $\vec{m}=(2 \hat{i}+3 \hat{j}+6 \hat{k})$.
So, its equation in vector form is

$$
\vec{r}=\overrightarrow{r_{1}}+\lambda \vec{m} \Rightarrow \vec{r}=(\hat{i}+2 \hat{j}-4 \hat{k})+\lambda(2 \hat{i}+3 \hat{j}+6 \hat{k})
$$

---

### Example 5:

Find the equation of a line passing through the point $P(2,-1,3)$ and perpendicular to the lines
and

$$
\begin{aligned}
\vec{r} & =(\hat{i}+\hat{j}-\hat{k})+\lambda(2 \hat{i}-2 \hat{j}+\hat{k}) \\
\vec{r} & =(2 \hat{i}-\hat{j}-3 \hat{k})+\mu(\hat{i}+2 \hat{j}+2 \hat{k})
\end{aligned}
$$

[CBSE 2012]

#### Solution:

The given lines are
$\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}} \ldots$ (i), where $\overrightarrow{a_{1}}=(\hat{i}+\hat{j}-\hat{k})$ and $\overrightarrow{b_{1}}=(2 \hat{i}-2 \hat{j}+\hat{k})$ and
$\vec{r}=\overrightarrow{a_{2}}+\lambda \overrightarrow{b_{2}} \ldots$ (ii), where $\overrightarrow{a_{2}}=(2 \hat{i}-\hat{j}-3 \hat{k})$ and $\overrightarrow{b_{2}}=(\hat{i}+2 \hat{j}+2 \hat{k})$.
The required line is perpendicular to (i) as well as (ii).

Also (i) is parallel to $\overrightarrow{b_{1}}$ and (ii) is parallel to $\overrightarrow{b_{2}}$.
So, the required line is perpendicular to both $\overrightarrow{b_{1}}$ and $\overrightarrow{b_{2}}$.
Consequently, this line must be parallel to $\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)$.
Now, $\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\left|\begin{array}{ccc}\hat{i} & \hat{j} & \hat{k} \\ 2 & -2 & 1 \\ 1 & 2 & 2\end{array}\right|=(-6 \hat{i}-3 \hat{j}+6 \hat{k})$.
So, we have to find the equation of a line passing through the point $P(2,-1,3)$ and parallel to $\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)$.

Hence, the required equation is

$$
\vec{r}=(2 \hat{i}-\hat{j}+3 \hat{k})+t(-6 \hat{i}-3 \hat{j}+6 \hat{k}),
$$

where $t$ is an arbitrary constant.

---

### Example 6:

Find the vector equation of the line passing through the point $A(2,-1,1)$, and parallel to the line joining the points $B(-1,4,1)$ and $C(1,2,2)$. Also, find the Cartesian equations of the line.
[CBSE 2003]

---

#### Solution:

**Vector equation of the given line:**

The p.v. of $B=(-\hat{i}+4 \hat{j}+\hat{k})$ and p.v. of $C=(\hat{i}+2 \hat{j}+2 \hat{k})$.
$\therefore \quad \overrightarrow{B C}=($ p.v. of $C)-($ p.v. of $B)$

$$
=(\hat{i}+2 \hat{j}+2 \hat{k})-(-\hat{i}+4 \hat{j}+\hat{k})=(2 \hat{i}-2 \hat{j}+\hat{k})
$$

The p.v. of $A$ is $\overrightarrow{r_{1}}=2 \hat{i}-\hat{j}+\hat{k}$.
$\therefore$ the vector equation of the given line is

$$
\begin{align*}
\vec{r} & =\overrightarrow{r_{1}}+\lambda(\overrightarrow{B C}) \\
\Leftrightarrow \quad \vec{r} & =(2 \hat{i}-\hat{j}+\hat{k})+\lambda(2 \hat{i}-2 \hat{j}+\hat{k}) \tag{i}
\end{align*}
$$

**Cartesian equations of the given line:**
Taking $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}$, equation (i) becomes

$$
\begin{aligned}
& (x \hat{i}+y \hat{j}+z \hat{k})=(2 \hat{i}-\hat{j}+\hat{k})+\lambda(2 \hat{i}-2 \hat{j}+\hat{k}) \\
\Leftrightarrow & (x \hat{i}+y \hat{j}+z \hat{k})=(2+2 \lambda) \hat{i}+(-1-2 \lambda) \hat{j}+(1+\lambda) \hat{k} \\
\Leftrightarrow & x=2+2 \lambda, y=-1-2 \lambda \text { and } z=1+\lambda
\end{aligned}
$$

$\Leftrightarrow \quad \frac{x-2}{2}=\frac{y+1}{-2}=\frac{z-1}{1}=\lambda$.
Hence, $\frac{x-2}{2}=\frac{y+1}{-2}=\frac{z-1}{1}$ are the required equations of the given line in the Cartesian form.

---

### Example 7:

Find the vector and Cartesian equations of the line passing through the points $A(2,-1,4)$ and $B(1,1,-2)$.

#### Solution:

**Vector equation of the given line:**
Let the position vectors of $A$ and $B$ be $\overrightarrow{r_{1}}$ and $\overrightarrow{r_{2}}$ respectively. Then,

$$
\begin{aligned}
& \overrightarrow{r_{1}}=2 \hat{i}-\hat{j}+4 \hat{k} \text { and } \overrightarrow{r_{2}}=\hat{i}+\hat{j}-2 \hat{k} \\
\therefore \quad & \left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right)=(\hat{i}+\hat{j}-2 \hat{k})-(2 \hat{i}-\hat{j}+4 \hat{k})=(-\hat{i}+2 \hat{j}-6 \hat{k})
\end{aligned}
$$

$\therefore \quad$ the vector equation of the line $A B$ is

$$
\begin{align*}
\vec{r} & =\overrightarrow{r_{1}}+\lambda\left(\overrightarrow{r_{2}}-\overrightarrow{r_{1}}\right) \text { for some scalar, } \lambda \\
\text { i.e., } \vec{r} & =(2 \vec{i}-\vec{j}+4 \vec{k})+\lambda(-\vec{i}+2 \vec{j}-6 \vec{k}) \tag{i}
\end{align*}
$$

**Cartesian equations of the given line:**
Taking $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}$, equation (i) becomes

$$
\begin{aligned}
& (x \hat{i}+y \hat{j}+z \hat{k})=(2 \hat{i}-\hat{j}+4 \hat{k})+\lambda(-\hat{i}+2 \hat{j}-6 \hat{k}) \\
\Leftrightarrow & (x \hat{i}+y \hat{j}+z \hat{k})=(2-\lambda) \hat{i}+(2 \lambda-1) \hat{j}+(4-6 \lambda) \hat{k} \\
\Leftrightarrow & x=2-\lambda, y=2 \lambda-1 \text { and } z=4-6 \lambda \\
\Leftrightarrow & \frac{x-2}{-1}=\frac{y+1}{2}=\frac{z-4}{-6}=\lambda
\end{aligned}
$$

Hence, $\frac{x-2}{-1}=\frac{y+1}{2}=\frac{z-4}{-6}$ are the Cartesian equations of the given line.

---

### Example 8:

Show that the lines $\frac{x+1}{3}=\frac{y+3}{5}=\frac{z+5}{7}$ and $\frac{x-2}{1}=\frac{y-4}{3}=\frac{z-6}{5}$ intersect. Also find their point of intersection.
[CBSE 2014]

#### Solution:

The given lines are

$$
\begin{array}{r}
\frac{x+1}{3}=\frac{y+3}{5}=\frac{z+5}{7}=\lambda \text { (say) } \\
\text { and } \frac{x-2}{1}=\frac{y-4}{3}=\frac{z-6}{5}=\mu \text { (say). } \tag{2}
\end{array}
$$

The general point on (1) is $P(3 \lambda-1,5 \lambda-3,7 \lambda-5)$.

The general point on (2) is $Q(\mu+2,3 \mu+4,5 \mu+6)$.
The given lines will intersect only when they have a common point. This happens when $P$ and $Q$ coincide for some particular values of $\lambda$ and $\mu$.
So, the given lines will intersect only when

$$
\begin{align*}
& 3 \lambda-1=\mu+2,5 \lambda-3=3 \mu+4 \text { and } 7 \lambda-5=5 \mu+6 \\
\Rightarrow \quad & 3 \lambda-\mu=3 \ldots \text { (i), } 5 \lambda-3 \mu=7 \ldots \text { (ii) and } 7 \lambda-5 \mu=11 . \tag{iii}
\end{align*}
$$

On solving (i) and (ii), we get $\lambda=\frac{1}{2}$ and $\mu=\frac{-3}{2}$.
Clearly, these values of $\lambda$ and $\mu$ also satisfy (iii).
Hence, the given lines intersect.
Putting $\lambda=\frac{1}{2}$ in $P$ or $\mu=\frac{-3}{2}$ in $Q$, we get the point of intersection of the given lines as $\left(\frac{1}{2}, \frac{-1}{2}, \frac{-3}{2}\right)$.

---

### Example 9:

Show that the lines

$$
\frac{x-1}{3}=\frac{y+1}{2}=\frac{z-1}{5} \text { and } \frac{x+2}{4}=\frac{y-1}{3}=\frac{z+1}{-2}
$$

do not intersect.
[CBSE 2002]

#### Solution:

The given lines are

$$
\begin{align*}
& \frac{x-1}{3}=\frac{y+1}{2}=\frac{z-1}{5}=\lambda \text { (say) }  \tag{1}\\
& \frac{x+2}{4}=\frac{y-1}{3}=\frac{z+1}{-2}=\mu \text { (say). } \tag{2}
\end{align*}
$$

The general point on (1) is $P(3 \lambda+1,2 \lambda-1,5 \lambda+1)$.
The general point on (2) is $Q(4 \mu-2,3 \mu+1,-2 \mu-1)$.
If possible, let the given lines intersect.
Then, $P$ and $Q$ coincide for some particular values of $\lambda$ and $\mu$.
In that case, we have

$$
\begin{align*}
& 3 \lambda+1=4 \mu-2,2 \lambda-1=3 \mu+1 \text { and } 5 \lambda+1=-2 \mu-1 \\
\Leftrightarrow & 3 \lambda-4 \mu=-3 \ldots \text { (i), } 2 \lambda-3 \mu=2 \ldots \text { (ii), } 5 \lambda+2 \mu=-2 \tag{iii}
\end{align*}
$$

Solving (i) and (ii), we get $\lambda=-17$ and $\mu=-12$.
However, these values of $\lambda$ and $\mu$ do not satisfy (iii).
Hence, the given lines do not intersect.

---

### Example 10:

Show that the lines

$$
\vec{r}=(\hat{i}+\hat{j}-\hat{k})+\lambda(3 \hat{i}-\hat{j}) \text { and } \vec{r}=(4 \hat{i}-\hat{k})+\mu(2 \hat{i}+3 \hat{k})
$$

intersect each other. Find their point of intersection.
[CBSE 2013, '14]

#### Solution:

The given lines are

$$
\begin{align*}
& \vec{r}=(\hat{i}+\hat{j}-\hat{k})+\lambda(3 \hat{i}-\hat{j})  \tag{1}\\
& \vec{r}=(4 \hat{i}-\hat{k})+\mu(2 \hat{i}+3 \hat{k}) \tag{2}
\end{align*}
$$

These lines will intersect if for some particular values of $\lambda$ and $\mu$, the values of $\vec{r}$ given by (1) and (2) are the same.
So, we must have

$$
\begin{aligned}
& (\hat{i}+\hat{j}-\hat{k})+\lambda(3 \hat{i}-\hat{j})=(4 \hat{i}-\hat{k})+\mu(2 \hat{i}+3 \hat{k}) \\
\Rightarrow & (1+3 \lambda) \hat{i}+(1-\lambda) \hat{j}-\hat{k}=(4+2 \mu) \hat{i}+(3 \mu-1) \hat{k} \\
\Rightarrow & 1+3 \lambda=4+2 \mu, 1-\lambda=0 \text { and } 3 \mu-1=-1 \\
\Rightarrow & 3 \lambda-2 \mu=3 \ldots \text { (i), } \lambda=1 \ldots \text { (ii) and } \mu=0 \ldots \text (iii). }
\end{aligned}
$$

Clearly, $\lambda=1$ and $\mu=0$ also satisfy (i).
Hence, the given lines intersect.
Putting $\lambda=1$ in (1), we get $\vec{r}=(4 \hat{i}+0 \hat{j}-\hat{k})$.
Hence, the point of intersection of the given lines is $(4,0,-1)$.

---

### Example 11:

Show that the lines
$\vec{r}=(\hat{i}+2 \hat{j}+\hat{k})+\lambda(\hat{i}-\hat{j}+\hat{k})$ and $\vec{r}=(\hat{i}+\hat{j}+\hat{k})+\mu(\hat{i}-\hat{j}+2 \hat{k})$ do not intersect.

#### Solution:

The given lines are

$$
\begin{align*}
\vec{r} & =(\hat{i}+2 \hat{j}+\hat{k})+\lambda(\hat{i}-\hat{j}+\hat{k})  \tag{1}\\
\vec{r} & =(\hat{i}+\hat{j}+\hat{k})+\mu(\hat{i}-\hat{j}+2 \hat{k}) \tag{2}
\end{align*}
$$

These lines will intersect if for some particular values of $\lambda$ and $\mu$, the values of $\vec{r}$ given by (1) and (2) are the same.
This happens, when

$$
\begin{aligned}
& (\hat{i}+2 \hat{j}+\hat{k})+\lambda(\hat{i}-\hat{j}+\hat{k})=(\hat{i}+\hat{j}+\hat{k})+\mu(\hat{i}-\hat{j}+2 \hat{k}) \\
\Rightarrow & (1+\lambda) \hat{i}+(2-\lambda) \hat{j}+(1+\lambda) \hat{k}=(1+\mu) \hat{i}+(1-\mu) \hat{j}+(1+2 \mu) \hat{k} \\
\Rightarrow & 1+\lambda=1+\mu, 2-\lambda=1-\mu \text { and } 1+\lambda=1+2 \mu \\
\Rightarrow & \lambda-\mu=0 \quad \ldots \text { (i), } \quad \lambda-\mu=1 \quad \ldots \text { (ii), } \quad \lambda-2 \mu=0 \quad \ldots \text (iii). }
\end{aligned}
$$

From (ii) and (iii), we get $\lambda=2$ and $\mu=1$.
And, these values of $\lambda$ and $\mu$ do not satisfy (i).
Hence, the given lines do not intersect.

---

### Example 12:

Find the points on the line $\frac{x+2}{3}=\frac{y+1}{2}=\frac{z-3}{2}$ at a distance of 5 units from the point (1, 3, 3).
[CBSE 2010]

#### Solution:

The given line is

$$
\begin{equation*}
\frac{x+2}{3}=\frac{y+1}{2}=\frac{z-3}{2}=r \text { (say). } \tag{i}
\end{equation*}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-005.jpg)

The general point on this line is

$$
P(3 r-2,2 r-1,2 r+3) .
$$

The given point is $A(1,3,3)$.
Now, $P A=5 \Rightarrow(P A)^{2}=25$

$$
\begin{aligned}
& \Rightarrow(3 r-2-1)^{2}+(2 r-1-3)^{2}+(2 r+3-3)^{2}=25 \\
& \Rightarrow(3 r-3)^{2}+(2 r-4)^{2}+(2 r)^{2}=25 \\
& \Rightarrow 17 r^{2}-34 r=0 \Rightarrow 17 r(r-2)=0 \\
& \Rightarrow r=0 \text { or } r=2
\end{aligned}
$$

$r=0 \Rightarrow$ the required point is $P(-2,-1,3)$.
$r=2 \Rightarrow$ the required point is $P(4,3,7)$.
Hence, the rquired points are ( $-2,-1,3$ ) and ( $4,3,7$ ).

---

### Example 13:

Find the equations of the perpendicular from the point $(3,-1,11)$ to the line $\frac{x}{2}=\frac{y-2}{3}=\frac{z-3}{4}$. Also find the coordinates of the foot of the perpendicular and the length of the perpendicular.
[CBSE 2011C]

#### Solution:

The given line is

$$
\begin{equation*}
\frac{x}{2}=\frac{y-2}{3}=\frac{z-3}{4}=r(\text { say }) . \tag{i}
\end{equation*}
$$

The general point on this line is

$$
(2 r, 3 r+2,4 r+3)
$$

Let $N$ be the foot of the perpendicular drawn from the point $P(3,-1,11)$ on

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-006.jpg)

the given line.
Then, this point is $N(2 r, 3 r+2,4 r+3)$ for some fixed value of $r$.
D.r.'s of $P N$ are $(2 r-3),(3 r+3),(4 r-8)$.
D.r.'s of the given line (i) are $2,3,4$.

Since $P N$ is perpendicular to the given line (i), we have

$$
2(2 r-3)+3(3 r+3)+4(4 r-8)=0 \Rightarrow 29 r=29 \Rightarrow r=1 .
$$

$\therefore$ D.r.'s of $P N$ are $-1,6,-4$ [putting $r=1$ in (ii)].
So, the required equations of perpendicular $P N$ are

$$
\frac{x-3}{-1}=\frac{y+1}{6}=\frac{z-11}{-4} .
$$

Now, the coordinates of $N$ are $N(2,5,7)$ [Putting $r=1$ ]
Length of perpendicular $P N$

$$
\begin{aligned}
& =\sqrt{(2-3)^{2}+(5+1)^{2}+(7-11)^{2}}=\sqrt{(-1)^{2}+6^{2}+(-4)^{2}} \\
& =\sqrt{1+36+16}=\sqrt{53} .
\end{aligned}
$$

---

### Example 14:

Find the coordinates of the foot of perpendicular and the length of the perpendicular drawn from the point $P(5,4,2)$ to the line $\vec{r}=(-\hat{i}+3 \hat{j}+\hat{k})+\lambda(2 \hat{i}+3 \hat{j}-\hat{k})$. Also find the image of $P$ in this line.
[CBSE 2012]

#### Solution:

The vector equation of the given line is $\vec{r}=(-\hat{i}+3 \hat{j}+\hat{k})+\lambda(2 \hat{i}+3 \hat{j}-\hat{k})$. Clearly, it passes through the point $(-1,3,1)$ and it has direction ratios $2,3,-1$.
So, its Cartesian equations are

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-007.jpg)

$$
\begin{equation*}
\frac{x+1}{2}=\frac{y-3}{3}=\frac{z-1}{-1}=r \text { (say). } \tag{i}
\end{equation*}
$$

The general point on this line is $(2 r-1,3 r+3,-r+1)$.
Let $N$ be the foot of the perpendicular drawn from the point $P(5,4,2)$ on the given line.
Then, this point is $N(2 r-1,3 r+3,-r+1)$ for some fixed value of $r$.
D.r.'s of $P N$ are $(2 r-6,3 r-1,-r-1)$.
D.r.'s of the given line are $2,3,-1$.

Since $P N$ is perpendicular to the given line (i), we have

$$
2(2 r-6)+3(3 r-1)-1 \cdot(-r-1)=0 \Rightarrow 14 r=14 \Rightarrow r=1 .
$$

So, the point $N$ is given by $N(1,6,0)$.
Hence, the foot of the perpendicular from the given point $P(5,4,2)$ on the given line is $N(1,6,0)$.
Let $Q(\alpha, \beta, \gamma)$ be the image of $P(5,4,2)$ in the given line.
Then, $N(1,6,0)$ is the midpoint of $P Q$.

$$
\therefore \quad \frac{5+\alpha}{2}=1, \frac{4+\beta}{2}=6 \text { and } \frac{2+\gamma}{2}=0 \Rightarrow \alpha=-3, \beta=8 \text { and } \gamma=-2 \text { . }
$$

Hence, the image of $P(5,4,2)$ in the given line is $Q(-3,8,-2)$.

---

### Example 15:

Find the image of the point $P(1,6,3)$ in the line $\frac{x}{1}=\frac{y-1}{2}=\frac{z-2}{3}$.
[CBSE 2003C, '08C, '10C]

#### Solution:

The equations of the given line are

$$
\begin{equation*}
\frac{x}{1}=\frac{y-1}{2}=\frac{z-2}{3}=r \text { (say). } \tag{i}
\end{equation*}
$$

The general point on this line is

$$
(r, 2 r+1,3 r+2)
$$

Let $N$ be the foot of the perpendicular drawn from the point $P(1,6,3)$ on the given line.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-008.jpg)

Then, this point is $N(r, 2 r+1,3 r+2)$ for some fixed value of $r$.
D.r.'s of $P N$ are ( $r-1,2 r-5,3 r-1$ ).
D.r.'s of the given line are $1,2,3$.

Since, $P N$ is perpendicular to the given line (i), we have

$$
1 \cdot(r-1)+2(2 r-5)+3(3 r-1)=0 \Rightarrow 14 r=14 \Rightarrow r=1 .
$$

So, the point $N$ is given by $N(1,3,5)$.
Let $Q(\alpha, \beta, \gamma)$ be the image of $P(1,6,3)$ in the given line.
Then, $N$ is the midpoint of $P Q$.
$\therefore \quad \frac{\alpha+1}{2}=1, \frac{\beta+6}{2}=3, \frac{\gamma+3}{2}=5 \Rightarrow \alpha=1, \beta=0$ and $\gamma=7$.
Hence, the image of the point $P(1,6,3)$ in the given line is $Q(1,0,7)$.

---

### Example 16:

Find the equations of the line passing through the points $A(0,6,-9)$ and $B(-3,-6,3)$. If $D$ is the foot of the perpendicular drawn from a point $C(7,4,-1)$ on the line $A B$ then find the coordinates of $D$ and the equations of the line $C D$.
[CBSE 2010C]

#### Solution:

The equations of line $A B$ are

$$
\begin{align*}
& \frac{x-0}{-3-0}=\frac{y-6}{-6-6}=\frac{z+9}{3+9}\left[\frac{x-x_{1}}{x_{2}-x_{1}}=\frac{y-y_{1}}{y_{2}-y_{1}}=\frac{z-z_{1}}{z_{2}-z_{1}}\right] \\
\Rightarrow & \frac{x}{-3}=\frac{y-6}{-12}=\frac{z+9}{12} \\
\Rightarrow & \frac{x}{1}=\frac{y-6}{4}=\frac{z+9}{-4}=a \text { (say). } \tag{i}
\end{align*}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-009.jpg)

Thus, the required equations of line $A B$ are given by (i).
From (i), we get $x=a, y=4 a+6$ and $z=-4 a-9$.
So, the coordinates of $D$ are $D(a, 4 a+6,-4 a-9)$ for some particular value of $a$.
D.r.'s of $A B$ are $1,4,-4$.
D.r.'s of CD are ( $a-7$ ), ( $4 a+2$ ), ( $-4 a-8$ ).

Since $A B \perp C D$, we have

$$
1 \cdot(a-7)+4(4 a+2)-4(-4 a-8)=0 \Rightarrow 33 a=-33 \Rightarrow a=-1 .
$$

Putting $a=-1$, we get the coordinates of $D$ as $D(-1,2,-5)$.

The equations of the line $C D$ are

$$
\begin{aligned}
\frac{x-7}{-1-7}=\frac{y-4}{2-4}=\frac{z+1}{-5+1} & \Rightarrow \frac{x-7}{-8}=\frac{y-4}{-2}=\frac{z+1}{-4} \\
& \Rightarrow \frac{x-7}{4}=\frac{y-4}{1}=\frac{z+1}{2} .
\end{aligned}
$$

---

### Example 17:

The points $A(4,5,10), B(2,3,4)$ and $C(1,2,-1)$ are three vertices of a parallelogram $A B C D$. Find the vector equations of the sides $A B$ and $B C$ and also find the coordinates of point $D$.
[CBSE 2010]

#### Solution:

D.r.'s of side $A B$ are ( $2-4$ ), ( $3-5$ ), ( $4-10$ ), i.e., $-2,-2,-6$.
Thus, side $A B$ passes through the point $A(4,5,10)$ and it has D.r.'s $-2,-2,-6$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/Straight-Line-in-Space/class-12-Ch-27-A-BooK-010.jpg)

So, the vector equation of side $A B$ is

$$
\vec{r}=(4 \hat{i}+5 \hat{j}+10 \hat{k})+\lambda(-2 \hat{i}-2 \hat{j}-6 \hat{k}) .
$$

D.r.'s. of side $B C$ are ( $1-2$ ), ( $2-3$ ), ( $-1-4$ ), i.e., $-1,-1,-5$.

Thus, side $B C$ passes through the point $B(2,3,4)$ and it has d.r.'s $-1,-1,-5$.
So, the vector equation of side $B C$ is

$$
\vec{r}=(2 \hat{i}+3 \hat{j}+4 \hat{k})+\mu(-\hat{i}-3 \hat{j}-5 \hat{k}) .
$$

Let the coordinates of $D$ be $D(x, y, z)$.
We know that midpoint of $B D$ coincides with the midpoint of $A C$.
$\therefore \quad \frac{2+x}{2}=\frac{4+1}{2}, \frac{3+y}{2}=\frac{5+2}{2}$ and $\frac{4+z}{2}=\frac{10+(-1)}{2}$
$\Rightarrow \quad 2+x=5,3+y=7$ and $4+z=9$
$\Rightarrow \quad x=3, y=4$ and $z=5$.
$\therefore \quad$ coordinates of $D$ are $D(3,4,5)$.

---