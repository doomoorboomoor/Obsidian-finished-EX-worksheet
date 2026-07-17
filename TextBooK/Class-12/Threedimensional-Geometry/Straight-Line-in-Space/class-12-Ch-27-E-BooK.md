## Shortest Distance Between Two Skew Lines in the Cartesian Form

The **shortest distance** between the skew lines

$$
\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}} \text { and } \frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}}
$$

is given by

$$
\mathrm{SD}=\frac{\left|\begin{array}{ccc}
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|}{\sqrt{D}},
$$

where $D=\left\{\left(a_{1} b_{2}-a_{2} b_{1}\right)^{2}+\left(b_{1} c_{2}-b_{2} c_{1}\right)^{2}+\left(c_{1} a_{2}-c_{2} a_{1}\right)^{2}\right\}$.

---

## Condition for Two Given Lines to Intersect

Let $L_{1}$ and $L_{2}$ be the given lines whose equations are

$$
\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}} \text { and } \frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}} .
$$

1.  $L_{1}$ and $L_{2}$ **intersect** $\Leftrightarrow$ **SD** between them is 0

    $$
    \Leftrightarrow\left|\begin{array}{ccc}
    x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
    a_{1} & b_{1} & c_{1} \\
    a_{2} & b_{2} & c_{2}
    \end{array}\right|=0 .
    $$

2.  $L_{1}$ and $L_{2}$ **do not intersect** $\Leftrightarrow$ they are **skew lines**

    $$
    \Leftrightarrow\left|\begin{array}{ccc}
    x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
    a_{1} & b_{1} & c_{1} \\
    a_{2} & b_{2} & c_{2}
    \end{array}\right| \neq 0 .
    $$

---

## Solved Examples

### Example 1

Find the shortest distance between the lines

$$
\frac{x+3}{-4}=\frac{y-6}{3}=\frac{z}{2} \text { and } \frac{x+2}{-4}=\frac{y}{1}=\frac{z-7}{1} .
$$

#### Solution

Comparing the given equations with

$$
\begin{aligned}
& \quad \begin{array}{l}
\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}} \text { and } \frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}}, \text { we get } \\
& \left(x_{1}=-3, y_{1}=6, z_{1}=0\right),\left(x_{2}=-2, y_{2}=0, z_{2}=7\right), \\
& \left(a_{1}=-4, b_{1}=3, c_{1}=2\right) \text { and }\left(a_{2}=-4, b_{2}=1, c_{2}=1\right) .
\end{array}
\end{aligned}
$$

$$
\begin{aligned}
\text { Now, } D &=\left(a_{1} b_{2}-a_{2} b_{1}\right)^{2}+\left(b_{1} c_{2}-b_{2} c_{1}\right)^{2}+\left(c_{1} a_{2}-c_{2} a_{1}\right)^{2} \\
& \quad=(-4+12)^{2}+(3-2)^{2}+(-8+4)^{2} \\
& \quad=(64+1+16)=81 .
\end{aligned}
$$

$$
\begin{aligned}
\therefore \quad \mathrm{SD} & =\frac{1}{\sqrt{D}} \cdot\left|\begin{array}{ccc}
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right| \\
& \quad=\frac{1}{\sqrt{81}} \cdot\left|\begin{array}{ccc}
-2+3 & 0-6 & 7-0 \\
-4 & 3 & 2 \\
-4 & 1 & 1
\end{array}\right|=\frac{1}{9} \cdot\left|\begin{array}{ccc}
1 & -6 & 7 \\
-4 & 3 & 2 \\
-4 & 1 & 1
\end{array}\right| \\
& \quad=\frac{1}{9} \cdot\{1 \cdot(3-2)+6 \cdot(-4+8)+7 \cdot(-4+12)\} \\
& =\frac{81}{9}=9 \text { units. }
\end{aligned}
$$

**Hence, the shortest distance between the given lines is 9 units.**

---

### Example 2

Find the length and the equations of the line of shortest distance between the lines

$$
\frac{x+1}{7}=\frac{y+1}{-6}=\frac{z+1}{1} \text { and } \frac{x-3}{1}=\frac{y-5}{-2}=\frac{z-7}{1} . \tag{CBSE2008,'14}
$$

#### Solution

The equations of the given lines are

$$
\begin{align*}
& \frac{x+1}{7}=\frac{y+1}{-6}=\frac{z+1}{1}=\lambda \text { (say) } \tag{i}\\
& \frac{x-3}{1}=\frac{y-5}{-2}=\frac{z-7}{1}=\mu \text { (say). } \tag{ii}
\end{align*}
$$

Any point on (i) is $P(7 \lambda-1,-6 \lambda-1, \lambda-1)$.
Any point on (ii) is $Q(\mu+3,-2 \mu+5, \mu+7)$.
The direction ratios of $P Q$ are ( $\mu-7 \lambda+4,-2 \mu+6 \lambda+6, \mu-\lambda+8$ ).
Now, $P Q$ will be the shortest distance between (i) and (ii) only when $P Q$ is perpendicular to both (i) and (ii).

$$
\therefore\left\{\begin{array}{c}
7(\mu-7 \lambda+4)-6(-2 \mu+6 \lambda+6)+1 \cdot(\mu-\lambda+8)=0 \\
\text { and } \\
1 \cdot(\mu-7 \lambda+4)-2(-2 \mu+6 \lambda+6)+1 \cdot(\mu-\lambda+8)=0
\end{array}\right.
$$

$$
\Rightarrow\left\{\begin{array}{r}
20 \mu-86 \lambda=0 \\
6 \mu-20 \lambda=0
\end{array} \Rightarrow\left\{\begin{array}{r}
10 \mu-43 \lambda \\
3 \mu-10 \lambda
\end{array} \Rightarrow \lambda=0\right.\right. \text { and } \mu=0 .
$$

$\therefore P Q$ will be the line of shortest distance when $\lambda=0$ and $\mu=0$.
Putting $\lambda=0$ and $\mu=0$, we get the points $P(-1,-1,-1)$ and $Q(3,5,7)$.

$$
\begin{aligned}
\therefore \quad \mathrm{SD}=|P Q| & =\sqrt{(3+1)^{2}+(5+1)^{2}+(7+1)^{2}} \\
& =\sqrt{(4)^{2}+(6)^{2}+(8)^{2}}=\sqrt{16+36+64} \\
& =\sqrt{116}=2 \sqrt{29} \text { units. }
\end{aligned}
$$

Clearly, the equation of the line of shortest distance is the equation of line $P Q$ given by

$$
\begin{aligned}
& \frac{x-3}{3+1}=\frac{y-5}{5+1}=\frac{z-7}{7+1} \\
\Leftrightarrow & \frac{x-3}{4}=\frac{y-5}{6}=\frac{z-7}{8} \\
\Leftrightarrow & \frac{x-3}{2}=\frac{y-5}{3}=\frac{z-7}{4} .
\end{aligned}
$$

**Hence, the equation of the line of shortest distance is**

$$
\frac{x-3}{2}=\frac{y-5}{3}=\frac{z-7}{4} .
$$

---

### Example 3

Find the length and the equations of the line of shortest distance between the lines

$$
\frac{x-8}{3}=\frac{y+9}{-16}=\frac{z-10}{7} \text { and } \frac{x-15}{3}=\frac{y-29}{8}=\frac{z-5}{-5} .
$$

#### Solution

The equations of the given lines are

$$
\begin{align*}
& \frac{x-8}{3}=\frac{y+9}{-16}=\frac{z-10}{7}=\lambda(\text { say }) \tag{i}\\
& \frac{x-15}{3}=\frac{y-29}{8}=\frac{z-5}{-5}=\mu(\text { say }) \tag{iii}
\end{align*}
$$

Any point on the line (i) is $P(3 \lambda+8,-16 \lambda-9,7 \lambda+10)$.
Any point on the line (ii) is $Q(3 \mu+15,8 \mu+29,-5 \mu+5)$.
The direction ratios of $P Q$ are

$$
(3 \mu-3 \lambda+7,8 \mu+16 \lambda+38,-5 \mu-7 \lambda-5) .
$$

Now, $P Q$ will be the shortest distance between (i) and (ii) only when $P Q$ is perpendicular to each one of (i) and (ii).

$$
\therefore\left\{\begin{array}{c}
3(3 \mu-3 \lambda+7)-16(8 \mu+16 \lambda+38)+7(-5 \mu-7 \lambda-5)=0 \\
\text { and } \\
3(3 \mu-3 \lambda+7)+8(8 \mu+16 \lambda+38)-5(-5 \mu-7 \lambda-5)=0
\end{array}\right.
$$

$$
\Rightarrow\left\{\begin{array}{l}
314 \lambda+154 \mu+622=0 \tag{iii}\\
154 \lambda+98 \mu+350=0
\end{array} \Rightarrow\left\{\begin{array}{c}
157 \lambda+77 \mu+311=0 \\
77 \lambda+49 \mu+175=0 .
\end{array}\right.\right.
$$

On multiplying (iii) by 7 and (iv) by 11 and subtracting, we get

$$
(1099 \lambda-847 \lambda)+(2177-1925)=0 \Rightarrow 252 \lambda=-252 \Rightarrow \lambda=-1
$$

Putting $\lambda=-1$ in (iv), we get

$$
49 \mu+(175-77)=0 \Rightarrow 49 \mu+98=0 \Rightarrow 49 \mu=-98 \Rightarrow \mu=-2 .
$$

Now, $\lambda=-1$ gives $P(5,7,3)$ and $\mu=-2$ gives $Q(9,13,15)$.

$$
\begin{aligned}
\therefore \quad \mathrm{SD} & =|P Q|=\sqrt{(9-5)^{2}+(13-7)^{2}+(15-3)^{2}} \\
& =\sqrt{16+36+144}=\sqrt{196}=14 \text { units. }
\end{aligned}
$$

Equation of the line of shortest distance is the equation of $P Q$, given by

$$
\begin{aligned}
\frac{x-5}{9-5} & =\frac{y-7}{13-7}=\frac{z-3}{15-3} \\
\Rightarrow \quad \frac{x-5}{4} & =\frac{y-7}{6}=\frac{z-3}{12} \Rightarrow \frac{x-5}{2}=\frac{y-7}{3}=\frac{z-3}{6} .
\end{aligned}
$$

**Hence, the equation of the line of shortest distance is**

$$
\frac{x-5}{2}=\frac{y-7}{3}=\frac{z-3}{6}
$$

---

### Example 4

Show that the lines

$$
\frac{x-1}{2}=\frac{y-2}{3}=\frac{z-3}{4} \text { and } \frac{x-4}{5}=\frac{y-1}{2}=z
$$

intersect each other. Find their point of intersection.
[CBSE 2004]

#### Solution

The equations of the given lines are

$$
\begin{align*}
& \frac{x-1}{2}=\frac{y-2}{3}=\frac{z-3}{4}=\lambda(\text { say }) \tag{i}\\
& \frac{x-4}{5}=\frac{y-1}{2}=\frac{z-0}{1}=\mu \tag{ii}
\end{align*}
$$

Any point on the line (i) is $P(2 \lambda+1,3 \lambda+2,4 \lambda+3)$.
Any point on the line (ii) is $Q(5 \mu+4,2 \mu+1, \mu)$.
If the lines (i) and (ii) intesect then $P$ and $Q$ must coincide for some particular values of $\lambda$ and $\mu$.
This gives

$$
\Rightarrow\left\{\begin{array}{l}
2 \lambda+1=5 \mu+4,3 \lambda+2=2 \mu+1 \text { and } 4 \lambda+3=\mu \\
2 \lambda-5 \mu=3 \tag{i}\\
3 \lambda-2 \mu=-1 \\
4 \lambda-\mu=-3
\end{array}\right.
$$

On solving (i) and (ii), we get $\lambda=-1$ and $\mu=-1$.
These values of $\lambda$ and $\mu$ also satisfy (iii).
Hence, the given lines intersect.
Putting $\lambda=-1$, we get $P(-1,-1,-1)$.
Note that putting $\mu=-1$, we get $Q(-1,-1,-1)$.
**Hence, the point of intersection of the given lines is $(-1,-1,-1)$.**

---

### Example 5

Show that the lines

$$
\frac{x-1}{2}=\frac{y+1}{3}=z \text { and } \frac{x+1}{5}=\frac{y-2}{2}, z=2 .
$$

[CBSE 2010]

#### Solution

The equations of the given lines are

$$
\begin{align*}
& \frac{x-1}{2}=\frac{y+1}{3}=\frac{z-0}{1}=\lambda \text { (say) } \tag{i}\\
& \frac{x+1}{5}=\frac{y-2}{1}=\frac{z-2}{0}=\mu \text { (say) } \tag{ii}
\end{align*}
$$

Any point on the line (i) is $P(2 \lambda+1,3 \lambda-1, \lambda)$.
Any point on the line (ii) is $Q(5 \mu-1, \mu+2,2)$.
If the lines (i) and (ii) intersect, then $P$ and $Q$ must coincide for some particular values of $\lambda$ and $\mu$.
This gives

$$
\Rightarrow \quad \begin{align*}
& 2 \lambda+1=5 \mu-1,3 \lambda-1=\mu+2 \text { and } \lambda=2 \\
& \left\{\begin{array}{c}
2 \lambda-5 \mu=-2 \\
3 \lambda-\mu=3 \\
\lambda=-3 .
\end{array}\right. \tag{iii}
\end{align*}
$$

Putting $\lambda=2$ in (iv), we get $\mu=3$.
Clearly, $\lambda=2$ and $\mu=3$ do not satisfy (iii).
**Hence, the given lines do not intersect each other.**

---