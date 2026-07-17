## Condition for the Coplanarity of Two Lines

## Vector Form

**THEOREM 1** The condition for two lines $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}$ to be coplanar is that

$$
\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0 \text {, i.e., }\left[\overrightarrow{a_{2}}-\overrightarrow{a_{1}} \quad \overrightarrow{b_{1}} \quad \overrightarrow{b_{2}}\right]=0 \text {. }
$$

Also, the equation of the plane containing both these lines is

$$
\left(\vec{r}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0 \quad \text { or } \quad\left(\vec{r}-\overrightarrow{a_{2}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0 .
$$

**PROOF** The equations of the given lines are

$$
\begin{align*}
& \vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}  \tag{i}\\
& \vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}} . \tag{ii}
\end{align*}
$$

The line (i) passes through a point $A$ with position vector $\overrightarrow{a_{1}}$ and is parallel to $\overrightarrow{b_{1}}$.

The line (ii) passes through a point $B$ with position vector $\overrightarrow{a_{2}}$ and is parallel to $\overrightarrow{b_{2}}$.

Now, $\overrightarrow{A B}=($ p.v. of $B)-($ p.v. of $A)=\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)$.

$\therefore \quad$ the given lines are coplanar
$\Leftrightarrow \quad \overrightarrow{A B}, \overrightarrow{b_{1}}, \overrightarrow{b_{2}}$ are coplanar
$\Leftrightarrow \overrightarrow{A B} \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0$
$\Leftrightarrow \quad\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0$.

### Equation of the Plane Containing Both the Lines

If the lines $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}$ are coplanar then their common plane is perpendicular to the vector $\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)$, and this plane passes through each of the points $\overrightarrow{a_{1}}$ and $\overrightarrow{a_{2}}$.

So, its equation is

$$
\left(\vec{r}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0, \text { or }\left(\vec{r}-\overrightarrow{a_{2}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0 .
$$

---

## Cartesian Form

**THEOREM 2** The lines

$$
\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}, \text { and } \frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}}
$$

are coplanar $\Leftrightarrow\left|\begin{array}{ccc}x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\ a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2}\end{array}\right|=0$.

And, the equation of the plane containing both these lines is

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|=0 \text { or }\left|\begin{array}{ccc}
x-x_{2} & y-y_{2} & z-z_{2} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|=0 .
$$

**PROOF** The given lines are

$$
\begin{align*}
& \frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}  \tag{i}\\
& \frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}} . \tag{ii}
\end{align*}
$$

The line (i) passes through a point $A\left(x_{1}, y_{1}, z_{1}\right)$ and is parallel to the vector $\overrightarrow{u_{1}}=a_{1} \hat{i}+b_{1} \hat{j}+c_{1} \hat{k}$.

Also, the line (ii) passes through a point $B\left(x_{2}, y_{2}, z_{2}\right)$ and is parallel to the vector $\overrightarrow{u_{2}}=a_{2} \hat{i}+b_{2} \hat{j}+c_{2} \hat{k}$.

Now, $\overrightarrow{A B}=($ p.v. of $B)-($ p.v. of $A)$

$$
\begin{aligned}
& =\left(x_{2} \hat{i}+y_{2} \hat{j}+z_{2} \hat{k}\right)-\left(x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}\right) \\
& =\left(x_{2}-x_{1}\right) \hat{i}+\left(y_{2}-y_{1}\right) \hat{j}+\left(z_{2}-z_{1}\right) \hat{k}
\end{aligned}
$$

$\therefore$ lines (i) and (ii) are coplanar
$\Leftrightarrow$ there is a plane which passes through the points $A$ and $B$, and which is parallel to each of $\overrightarrow{u_{1}}$ and $\overrightarrow{u_{2}}$
$\Leftrightarrow \overrightarrow{A B}, \overrightarrow{u_{1}}, \overrightarrow{u_{2}}$ are parallel to the same plane
$\Leftrightarrow \overrightarrow{A B}, \overrightarrow{u_{1}}, \overrightarrow{u_{2}}$ are coplanar
$\Leftrightarrow\left[\overrightarrow{A B}, \overrightarrow{u_{1}}, \overrightarrow{u_{2}}\right]=0$

$$
\Leftrightarrow\left|\begin{array}{ccc}
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|=0 .
$$

### Equation of the Plane Containing Both the Lines

If the lines (i) and (ii) are coplanar then their common plane is the plane containing the line (i) and parallel to the line (ii) or it is the plane containing the line (ii) and parallel to the line (i).

Hence, its equation is

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|=0 \text { or }\left|\begin{array}{ccc}
x-x_{2} & y-y_{2} & z-z_{2} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|=0 .
$$

---

## SUMMARY

1.  (i) Two lines $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\lambda \overrightarrow{b_{2}}$ are coplanar only when
    $$
    \left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0 .
    $$
    (ii) If two lines $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\lambda \overrightarrow{b_{2}}$ are coplanar, then the equation of the plane containing both of these lines is given by
    $$
    \left\{\left(\vec{r}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0\right\} \text { or }\left\{\left(\vec{r}-\overrightarrow{a_{2}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0\right\} \text {. }
    $$

2.  (i) The lines $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ and $\frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}}$ are
    $$
    \text { coplanar only when }\left|\begin{array}{ccc}
    x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
    a_{1} & b_{1} & c_{1} \\
    a_{2} & b_{2} & c_{2}
    \end{array}\right|=0 .
    $$
    (ii) The equation of the common plane is
    $$
    \left|\begin{array}{ccc}
    x-x_{1} & y-y_{1} & z-z_{1} \\
    a_{1} & b_{1} & c_{1} \\
    a_{2} & b_{2} & c_{2}
    \end{array}\right|=0 \text { or }\left|\begin{array}{ccc}
    x-x_{2} & y-y_{2} & z-z_{2} \\
    a_{1} & b_{1} & c_{1} \\
    a_{2} & b_{2} & c_{2}
    \end{array}\right|=0 .
    $$

---

## SOLVED EXAMPLES

### Example 1

Show that the lines
$\vec{r}=(\hat{i}+\hat{j}-\hat{k})+\lambda(3 \hat{i}-\hat{j})$ and $\vec{r}=(4 \hat{i}-\hat{k})+\mu(2 \hat{i}+3 \hat{k})$
are coplanar. Also, find the equation of the plane containing both these lines.
*[CBSE 2013C]*

#### Solution:

We know that the lines $\vec{r}=\overrightarrow{a_{1}}+\lambda \overrightarrow{b_{1}}$ and $\vec{r}=\overrightarrow{a_{2}}+\mu \overrightarrow{b_{2}}$ are coplanar

$$
\Leftrightarrow\left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0 .
$$

Here, $\overrightarrow{a_{1}}=\hat{i}+\hat{j}-\hat{k}, \overrightarrow{b_{1}}=3 \hat{i}-\hat{j}, \overrightarrow{a_{2}}=4 \hat{i}-\hat{k}$ and $\overrightarrow{b_{2}}=2 \hat{i}+3 \hat{k}$.

$$
\begin{array}{ll}
\therefore & \left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right)=(4 \hat{i}-\hat{k})-(\hat{i}+\hat{j}-\hat{k})=(3 \hat{i}-\hat{j}) . \\
& \left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\left|\begin{array}{rrr}
\hat{i} & \hat{j} & \hat{k} \\
3 & -1 & 0 \\
2 & 0 & 3
\end{array}\right| \\
& =(-3-0) \hat{i}-(9-0) \hat{j}+(0+2) \hat{k}=-3 \hat{i}-9 \hat{j}+2 \hat{k} . \\
\therefore & \left(\overrightarrow{a_{2}}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=(3 \hat{i}-\hat{j}) \cdot(-3 \hat{i}-9 \hat{j}+2 \hat{k}) \\
& =[3 \times(-3)+(-1) \times(-9)+0 \times 2]=0 .
\end{array}
$$

Hence, the given lines are coplanar.

The equation of the plane containing both the given lines is given by

$$
\begin{aligned}
& \left(\vec{r}-\overrightarrow{a_{1}}\right) \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=0 \Leftrightarrow \vec{r} \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right)=\overrightarrow{a_{1}} \cdot\left(\overrightarrow{b_{1}} \times \overrightarrow{b_{2}}\right) \\
\Leftrightarrow & \vec{r} \cdot(-3 \hat{i}-9 \hat{j}+2 \hat{k})=(\hat{i}+\hat{j}-\hat{k}) \cdot(-3 \hat{i}-9 \hat{j}+2 \hat{k}) \\
\Leftrightarrow & \vec{r} \cdot(-3 \hat{i}-9 \hat{j}+2 \hat{k})=(-3-9-2) \Leftrightarrow \vec{r} \cdot(3 \hat{i}+9 \hat{j}-2 \hat{k})=14 .
\end{aligned}
$$

Hence, the required equation of the plane is

$$
\vec{r} \cdot(3 \hat{i}+9 \hat{j}-2 \hat{k})=14 .
$$

---

### Example 2

Show that the lines $\frac{x+3}{-3}=\frac{y-1}{1}=\frac{z-5}{5}$ and $\frac{x+1}{-1}=\frac{y-2}{2}=\frac{z-5}{5}$ are coplanar. Also, find the equation of the plane containing these lines.
*[CBSE 2013C]*

#### Solution:

We know that the lines

$$
\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}, \text { and } \frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}}
$$

are coplanar only when $\left|\begin{array}{ccc}x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\ a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2}\end{array}\right|=0$.

Here, $x_{1}=-3, y_{1}=1, z_{1}=5$ and $x_{2}=-1, y_{2}=2, z_{2}=5$.
$a_{1}=-3, b_{1}=1, c_{1}=5$ and $a_{2}=-1, b_{2}=2, c_{2}=5$

$$
\begin{gathered}
\therefore\left|\begin{array}{ccc}
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|=\left|\begin{array}{ccc}
-1+3 & 2-1 & 5-5 \\
-3 & 1 & 5 \\
-1 & 2 & 5
\end{array}\right| \\
\quad=\left|\begin{array}{ccc}
2 & 1 & 0 \\
-3 & 1 & 5 \\
-1 & 2 & 5
\end{array}\right|=\left|\begin{array}{ccc}
2 & 1 & 0 \\
-2 & -1 & 0 \\
-1 & 2 & 5
\end{array}\right|\left[R_{2} \rightarrow\left(R_{2}-R_{3}\right)\right] \\
\quad=5(-2+2)=(5 \times 0)=0\left[\text { expanding by } c_{3}\right] .
\end{gathered}
$$

Hence, the given lines are coplanar.

Equation of the plane containing both these lines is given by

$$
\begin{aligned}
& \left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right|=0 \Leftrightarrow\left|\begin{array}{ccc}
x+3 & y-1 & z-5 \\
-3 & 1 & 5 \\
-1 & 2 & 5
\end{array}\right|=0 \\
\Leftrightarrow & (x+3)(5-10)-(y-1)(-15+5)+(z-5)(-6+1)=0 \\
\Leftrightarrow & (-5)(x+3)+10(y-1)-5(z-5)=0 \\
\Leftrightarrow & -5 x+10 y-5 z=0 \Leftrightarrow x-2 y+z=0 .
\endaligned}
$$

Hence, the required equation plane is $x-2 y+z=0$.

---

### Example 3

Show that the lines

$$
\frac{x-a+d}{\alpha-\delta}=\frac{y-a}{\alpha}=\frac{z-a-d}{\alpha+\delta}, \text { and } \frac{x-b+c}{\beta-\gamma}=\frac{y-b}{\beta}=\frac{z-b-c}{\beta+\gamma}
$$

are coplanar. Also find the equation of the plane containing them.

#### Solution:

The given lines are

$$
\begin{align*}
& \frac{x-(a-d)}{\alpha-\delta}=\frac{y-a}{\alpha}=\frac{z-(a+d)}{\alpha+\delta}  \tag{i}\\
& \frac{x-(b-c)}{\beta-\gamma}=\frac{y-b}{\beta}=\frac{z-(b+c)}{\beta+\gamma} \tag{ii}
\end{align*}
$$

We know that the lines

$$
\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}, \text { and } \frac{x-x_{2}}{a_{2}}=\frac{y-y_{2}}{b_{2}}=\frac{z-z_{2}}{c_{2}}
$$

are coplanar $\Leftrightarrow\left|\begin{array}{ccc}x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\ a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2}\end{array}\right|=0$.

Here, $x_{1}=(a-d), y_{1}=a, z_{1}=(a+d)$;
$x_{2}=(b-c), y_{2}=b, z_{2}=(b+c)$;
$a_{1}=(\alpha-\delta), b_{1}=\alpha, c_{1}=(\alpha+\delta)$; and
$a_{2}=(\beta-\gamma), b_{2}=\beta, c_{2}=(\beta+\gamma)$.

$$
\begin{aligned}
& \therefore\left|\begin{array}{ccc}
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\end{array}\right| \\
& \quad=\left|\begin{array}{ccc}
(b-c)-(a-d) & b-a & (b+c)-(a+d) \\
\alpha-\delta & \alpha & \alpha+\delta \\
\beta-\gamma & \beta & \beta+\gamma
\end{array}\right| \\
& \quad=\left|\begin{array}{ccc}
2(b-a) & b-a & b+c-a+d \\
2 \alpha & \alpha & \alpha+\delta \\
2 \beta & \beta & \beta+\gamma
\end{array}\right|\left\{C_{1} \rightarrow C_{1}+C_{3}\right\} \\
& \quad=0\left[\because C_{1} \text { and } C_{2} \text { are proportional }\right] .
\end{aligned}
$$

Hence, the given lines are coplanar.

Equation of the plane containing the given lines is given by

$$
\left|\begin{array}{ccc}
x-(a-d) & y-a & z-(a+d) \\
\alpha-\delta & \alpha & \alpha+\delta \\
\beta-\gamma & \beta & \beta+\gamma
\end{array}\right|=0 .
$$

Applying $C_{1} \rightarrow C_{1}+C_{3}-2 C_{2}$, we get

$$
\begin{aligned}
& \left|\begin{array}{ccc}
x-z-2 y & y-a & z-(a+d) \\
0 & \alpha & \alpha+\delta \\
0 & \beta & \beta+\gamma
\end{array}\right|=0 \\
\Rightarrow & (x+z-2 y)-[\alpha(\beta+\gamma)-\beta(\alpha+\delta)]=0 \\
\Rightarrow & (x+z-2 y)(\alpha \gamma-\beta \delta)=0 \Rightarrow x+z-2 y=0 .
\end{aligned}
$$

Hence, the required equation of the plane is $x+z-2 y=0$.

---

## PLANE CONTAINING PARALLEL LINES

### Example 4

Find the equation of the plane which contains the two parallel lines $\frac{x-3}{3}=\frac{y+4}{2}=\frac{z-1}{1}$, and $\frac{x+1}{3}=\frac{y-2}{2}=\frac{z}{1}$.

#### Solution:

Clearly, the plane which contains the two given parallel lines must pass through the points $A(3,-4,1)$ and $B(-1,2,0)$, and it must be parallel to the line having direction ratios $3,2,1$.

Any plane passing through the point $A(3,-4,1)$ is given by

$$
a(x-3)+b(y+4)+c(z-1)=0 . \tag{i}
$$

If this plane passes through the point $B(-1,2,0)$, we have

$$
a(-1-3)+b(2+4)+c(0-1)=0 \Rightarrow 4 a-6 b+c=0 \tag{ii}
$$

If the plane (ii) is parallel to the line having direction ratios $3,2,1$ then

$$
3 a+2 b+c=0 \tag{iii}
$$

On solving (ii) and (iii) by cross multiplication, we get

$$
\begin{aligned}
\frac{a}{(-6-2)}=\frac{b}{(3-4)}=\frac{c}{(8+18)} & \Rightarrow \frac{a}{-8}=\frac{b}{-1}=\frac{c}{26}=\lambda \text { (say) } \\
& \Rightarrow a=-8 \lambda, b=-\lambda \text { and } c=26 \lambda
\end{aligned}
$$

Putting these values of $a, b$ and $c$ in (i), we get

$$
\begin{aligned}
& -8 \lambda(x-3)-\lambda(y+4)+26 \lambda(z-1)=0 \\
\Rightarrow \quad & 8(x-3)+(y+4)-26(z-1)=0 \Rightarrow 8 x+y-26 z+6=0 .
\end{aligned}
$$

Hence, the required equation of the plane is $8 x+y-26 z+6=0$.

---