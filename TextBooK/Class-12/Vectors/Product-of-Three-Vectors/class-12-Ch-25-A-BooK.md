## 25. Product of Three Vectors

**SCALAR TRIPLE PRODUCT** The scalar triple product of three vectors $\vec{a}, \vec{b}, \vec{c}$ is defined as $(\vec{a} \times \vec{b}) \cdot \vec{c}$, and it is denoted by $[\vec{a} \vec{b} \vec{c}]$.

Thus $\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]=(\vec{a} \times \vec{b}) \cdot \vec{c}$.

Since $(\vec{a} \times \vec{b})$ is a vector, $(\vec{a} \times \vec{b}) \cdot \vec{c}$ is a scalar.

Consequently, $\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]$ is a scalar quantity.

## Some Theorems on Scalar Triple Product

### THEOREM 1 (Geometrical interpretation)
$(\vec{a} \times \vec{b}) \cdot \vec{c}$ represents the **volume of a parallelepiped** whose **coterminous edges** are represented by $\vec{a}, \vec{b}, \vec{c}$.

#### PROOF

Let us consider a parallelepiped having **coterminous edges** $OA$, $OB$ and $OC$ respectively.
Let $\overrightarrow{O A}=\vec{a}, \overrightarrow{O B}=\vec{b}$ and $\overrightarrow{O C}=\vec{c}$.
Then, $(\vec{a} \times \vec{b})$ is a vector perpendicular to the plane of $\vec{a}$ and $\vec{b}$.
Let $\theta$ be the angle between $(\vec{a} \times \vec{b})$ and $\vec{c}$.

$$
\begin{aligned}
\therefore \quad[\vec{a} \vec{b} \vec{c}] & =(\vec{a} \times \vec{b}) \cdot \vec{c} \\
& =|\vec{a} \times \vec{b}||\vec{c}| \cos \theta \\
& =(\text { area of }| | \operatorname{gm} O A D B)[\text { projection of } \vec{c} \text { along }(\vec{a} \times \vec{b})] \\
& =(\text { area of }| | \operatorname{gm} O A D B) \cdot O L \\
& =(\text { area of the base of the parallelepiped }) \cdot(\text { height }) \\
& =\text { volume of the parallelepiped with coterminous } \\
& \quad \text { edges } \vec{a}, \vec{b}, \vec{c}
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-69.jpg?height=460&width=455&top_left_y=1034&top_left_x=756)

Hence $\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]$ represents the volume of the parallelepiped with coterminous edges $\vec{a}, \vec{b}, \vec{c}$ forming a **right-handed system**.

---

### THEOREM 2
For any three vectors $\vec{a}, \vec{b}, \vec{c}$ prove that $(\vec{a} \times \vec{b}) \cdot \vec{c}=\vec{a} \cdot(\vec{b} \times \vec{c})$.

#### PROOF

Let $\vec{a}, \vec{b}, \vec{c}$ form a **right-handed system**, representing the coterminous edges of a parallelepiped of volume $V$.
Then, $V=(\vec{a} \times \vec{b}) \cdot \vec{c}$.
Again, $\vec{b}, \vec{c}, \vec{a}$ form a **right-handed system**, representing the coterminous edges of the same parallelepiped.
$\therefore \quad V=(\vec{b} \times \vec{c}) \cdot \vec{a}=\vec{a} \cdot(\vec{b} \times \vec{c}) \quad[\because \vec{A} \cdot \vec{B}=\vec{B} \cdot \vec{A}]$.
Hence, $(\vec{a} \times \vec{b}) \cdot \vec{c}=\vec{a} \cdot(\vec{b} \times \vec{c})$.

---

### THEOREM 3
The scalar triple product of three vectors remains unchanged so long as their **cyclic order** remains unchanged,

i.e.,
$$
(\vec{a} \times \vec{b}) \cdot \vec{c}=(\vec{b} \times \vec{c}) \cdot \vec{a}=(\vec{c} \times \vec{a}) \cdot \vec{b}
$$

#### PROOF

Let $\vec{a}, \vec{b}, \vec{c}$ form a **right-handed system**, representing the coterminous edges of a rectangular parallelepiped of volume $V$.
Then, $V=(\vec{a} \times \vec{b}) \cdot \vec{c}$.
Clearly, $\vec{b}, \vec{c}, \vec{a}$ as well as $\vec{c}, \vec{a}, \vec{b}$ form a **right-handed system**, representing the coterminous edges of the same parallelepiped.
$\therefore \quad V=(\vec{b} \times \vec{c}) \cdot \vec{a}$ and $V=(\vec{c} \times \vec{a}) \cdot \vec{b}$.
Thus, $(\vec{a} \times \vec{b}) \cdot \vec{c}=(\vec{b} \times \vec{c}) \cdot \vec{a}=(\vec{c} \times \vec{a}) \cdot \vec{b} \quad$ [each equal to $V$].
Hence, $\left[\begin{array}{ccc}\vec{a} & \vec{b} & \vec{c}\end{array}\right]=\left[\begin{array}{ccc}\vec{b} & \vec{c} & \vec{a}\end{array}\right]=\left[\begin{array}{ccc}\vec{c} & \vec{a} & \vec{b}\end{array}\right]$.

---

### THEOREM 4
The scalar triple product changes in sign but not in magnitude when the **cyclic order** of vectors is changed.

#### PROOF

For any three vectors $\vec{a}, \vec{b}, \vec{c}$, we know that

$$
\begin{aligned}
& \quad\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]=\left[\begin{array}{lll}
\vec{c} & \vec{a} & \vec{b}
\end{array}\right] \\
& \therefore \quad\left[\begin{array}{lll}
\vec{c} & \vec{b} & \vec{a}
\end{array}\right]=\left(\begin{array}{ll}
\vec{c} \times \vec{b} & ) \cdot \vec{a}=-(\vec{b} \times \vec{c}) \cdot \vec{a}=-\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]=-\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]
\end{array}\right.
\end{aligned}
$$

And, $\left[\begin{array}{lll} \vec{a} & \vec{c} & \vec{b} \end{array}\right]=(\vec{a} \times \vec{c} ) \cdot \vec{b}=-(\vec{c} \times \vec{a}) \cdot \vec{b}=-\left[\begin{array}{lll}\vec{c} & \vec{a} & \vec{b}\end{array}\right]=-\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]$

$\therefore \quad\left[\begin{array}{lll} \vec{c} & \vec{b} & \vec{a} \end{array}\right]=-\left[\begin{array}{lll} \vec{a} & \vec{b} & \vec{c} \end{array}\right]$ and $\left[\begin{array}{lll} \vec{a} & \vec{c} & \vec{b} \end{array}\right]=-\left[\begin{array}{lll} \vec{a} & \vec{b} & \vec{c} \end{array}\right]$

---

### THEOREM 5
The scalar triple product vanishes if any two of its vectors are equal,

i.e.,
$$
\left[\begin{array}{lll}
\vec{a} & \vec{a} & \vec{b}
\end{array}\right]=0,\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{a}
\end{array}\right]=0 \text { and }\left[\begin{array}{lll}
\vec{b} & \vec{a} & \vec{a}
\end{array}\right]=0
$$

#### PROOF

We have $\left[\begin{array}{lll}\vec{a} & \vec{a} & \vec{b}\end{array}\right]=(\vec{a} \times \vec{a}) \cdot \vec{b}=\overrightarrow{0} \cdot \vec{b}=0$;

$$
\begin{aligned}
{\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{a}
\end{array}\right] } & =\left[\begin{array}{lll}
\vec{a} & \vec{a} & \vec{b}
\end{array}\right] \quad[\text { cyclic-ordered property }] \\
& =(\vec{a} \times \vec{a}) \cdot \vec{b}=\overrightarrow{0} \cdot \vec{b}=0
\end{aligned}
$$

and $\left[\begin{array}{ccc}\vec{b} & \vec{a} & \vec{a}\end{array}\right]=\left[\begin{array}{ccc}\vec{a} & \vec{b} & \vec{a}\end{array}\right]$ [cyclic-ordered property]

$$
=0 .
$$

Hence, $\quad\left[\begin{array}{lll}\vec{a} & \vec{a} & \vec{b}\end{array}\right]=\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{a}\end{array}\right]=\left[\begin{array}{lll}\vec{b} & \vec{a} & \vec{a}\end{array}\right]=0$.

---

### THEOREM 6
The scalar triple product vanishes if any two of its vectors are **parallel or collinear**.

#### PROOF

Let $\vec{a}, \vec{b}, \vec{c}$ be three vectors such that $\vec{a} \| \vec{b}$, or $\vec{a}$ and $\vec{b}$ are collinear.
Then, $\vec{a}=m \vec{b}$ for some scalar $m$.

$$
\therefore \quad\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=\left[\begin{array}{llll}
m & \vec{b} & \vec{b} & \vec{c}
\end{array}\right]=(m \vec{b} \times \vec{b}) \cdot \vec{c}=\overrightarrow{0} \cdot \vec{c}=0 .
$$

---

### THEOREM 7 (Scalar triple product in terms of components)

Let $\vec{a}=a_{1} \hat{i}+a_{2} \hat{j}+a_{3} \hat{k}$, $\vec{b}=b_{1} \hat{i}+b_{2} \hat{j}+b_{3} \hat{k}$
and $\vec{c}=c_{1} \hat{i}+c_{2} \hat{j}+c_{3} \hat{k}$.

Then,
$$
\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]=\left|\begin{array}{lll}a_{1} & a_{2} & a_{3} \\ b_{1} & b_{2} & b_{3} \\ c_{1} & c_{2} & c_{3}\end{array}\right| .
$$

#### PROOF

We have
$$
\vec{a} \times \vec{b}=\left|\begin{array}{ccc}\hat{i} & \hat{j} & \hat{k} \\ a_{1} & a_{2} & a_{3} \\ b_{1} & b_{2} & b_{3}\end{array}\right|
$$

$$
\begin{aligned}
& =\left(a_{2} b_{3}-a_{3} b_{2}\right) \hat{i}+\left(a_{3} b_{1}-a_{1} b_{3}\right) \hat{j}+\left(a_{1} b_{2}-a_{2} b_{1}\right) \hat{k}
\end{aligned}
$$

$\therefore \quad[\vec{a} \vec{b} \vec{c}] =(\vec{a} \times \vec{b}) \cdot \vec{c}$

$$
\begin{aligned}
& =\left(a_{2} b_{3}-a_{3} b_{2}\right) c_{1}+\left(a_{3} b_{1}-a_{1} b_{3}\right) c_{2}+\left(a_{1} b_{2}-a_{2} b_{1}\right) c_{3} \\
& =a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)+a_{2}\left(b_{3} c_{1}-b_{1} c_{3}\right)+a_{3}\left(b_{1} c_{2}-b_{2} c_{1}\right) \\
& =\left|\begin{array}{lll}
a_{1} & a_{2} & a_{3} \\
b_{1} & b_{2} & b_{3} \\
c_{1} & c_{2} & c_{3}
\end{array}\right| .
\end{aligned}
$$

---

### THEOREM 8
For any three vectors $\vec{a}, \vec{b}$ and $\vec{c}$, prove that

$$
[\vec{a}+\vec{b}, \vec{b}+\vec{c}, \vec{c}+\vec{a}]=2[\vec{a}, \vec{b}, \vec{c}]
$$

[CBSE 2014]

#### PROOF

We have

$$
\begin{aligned}
& {\left[\begin{array}{lll}
\vec{a}+\vec{b} & \vec{b}+\vec{c} & \vec{c}+\vec{a}
\end{array}\right]} \\
& =(\vec{a}+\vec{b}) \cdot[(\vec{b}+\vec{c}) \times(\vec{c}+\vec{a})] \\
& =(\vec{a}+\vec{b}) \cdot[\vec{b} \times \vec{c}+\vec{b} \times \vec{a}+\vec{c} \times \vec{c}+\vec{c} \times \vec{a}] \text { [by the distributive law] } \\
& =(\vec{a}+\vec{b}) \cdot[(\vec{b} \times \vec{c})-(\vec{a} \times \vec{b})+(\vec{c} \times \vec{a})] \\
& {[\because \vec{c} \times \vec{c}=\overrightarrow{0} \text {, and } \vec{b} \times \vec{a}=-\vec{a} \times \vec{b}]} \\
& =\vec{a} \cdot(\vec{b} \times \vec{c})-\vec{a} \cdot(\vec{a} \times \vec{b})+\vec{a} \cdot(\vec{c} \times \vec{a})+\vec{b} \cdot(\vec{b} \times \vec{c}) \\
& -\vec{b} \cdot(\vec{a} \times \vec{b})+\vec{b} \cdot(\vec{c} \times \vec{a}) \text { [by the distributive law] } \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]-\left[\begin{array}{lll}
\vec{a} & \vec{a} & \vec{b}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{a}
\end{array}\right]+\left[\begin{array}{lll}
\vec{b} & \vec{b} & \vec{c}
\end{array}\right]-\left[\begin{array}{lll}
\vec{b} & \vec{a} & \vec{b}
\end{array}\right]+\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right] \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]+\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right] \\
& \text { [ } \because \text { scalar triple product with two equal vectors is } 0 \text { ] } \\
& =2\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]\left\{\because\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]=\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]\right\} \text { . }
\end{aligned}
$$

Hence, $\left[\begin{array}{lll} \vec{a}+\vec{b} & \vec{b}+\vec{c} & \vec{c}+\vec{a} \end{array}\right]=2\left[\begin{array}{lll} \vec{a} & \vec{b} & \vec{c} \end{array}\right]$.

---

### THEOREM 9
The **necessary and sufficient condition** for three nonzero, noncollinear vectors $\vec{a}, \vec{b}, \vec{c}$ to be **coplanar** is that $\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]=0$.

#### PROOF

Let $\vec{a}, \vec{b}, \vec{c}$ be three nonzero, noncollinear and coplanar vectors.
Then, $\vec{b} \times \vec{c}$ is perpendicular to the plane of $\vec{b}$ and $\vec{c}$
$\Rightarrow \quad(\vec{b} \times \vec{c}) \perp \vec{a} \quad[\because \vec{a}, \vec{b}, \vec{c}$ are coplanar $]$
$\Rightarrow \quad \vec{a} \cdot(\vec{b} \times \vec{c})=0 \Rightarrow\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]=0$.
Thus, whenever $\vec{a}, \vec{b}, \vec{c}$ are coplanar, we have $[\vec{a} \vec{b} \vec{c}]=0$.

Conversely, let $\vec{a}, \vec{b}, \vec{c}$ be three nonzero, noncollinear vectors such that $\left[\begin{array}{ccc}\vec{a} & \vec{b} & \vec{c}\end{array}\right]=\overrightarrow{0}$. Then,

$$
\begin{aligned}
& {\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=0 } \Rightarrow \vec{a} \cdot(\vec{b} \times \vec{c})=0 \\
& \Rightarrow \vec{a}=\overrightarrow{0}, \text { or }(\vec{b} \times \vec{c})=\overrightarrow{0}, \text { or }(\vec{b} \times \vec{c}) \perp \vec{a} \\
& \Rightarrow(\vec{b} \times \vec{c})=\overrightarrow{0}, \text { or }(\vec{b} \times \vec{c}) \perp \vec{a} \quad[\because \vec{a} \neq \overrightarrow{0}] \\
& \Rightarrow(\vec{b} \times \vec{c}) \perp \vec{a} \\
& {[\because \vec{b} \neq \overrightarrow{0}, \vec{c} \neq \overrightarrow{0}, \text { and } \vec{b}, \vec{c} \text { are noncollinear } \Rightarrow \vec{b} \times \vec{c} \neq \overrightarrow{0}] }
\end{aligned}
$$

Thus, $(\vec{b} \times \vec{c})$ is perpendicular to $\vec{a}$.
But, $(\vec{b} \times \vec{c})$ is perpendicular to the plane of $\vec{b}$ and $\vec{c}$.
$\therefore \quad \vec{a}$ must lie in the plane of $\vec{b}$ and $\vec{c}$.
Hence $\vec{a}, \vec{b}, \vec{c}$ must be coplanar.

**NOTE:** $\vec{a}, \vec{b}, \vec{c}$ are **coplanar** $\Leftrightarrow[\vec{a} \vec{b} \vec{c}]=0$.

---

### THEOREM 10
For any three vectors $\vec{a}, \vec{b}, \vec{c}$ show that the vectors $(\vec{a}-\vec{b}),(\vec{b}-\vec{c}), (\vec{c}-\vec{a})$ are **coplanar**.
[CBSE 2001]

#### PROOF

We know that

$(\vec{a}-\vec{b}),(\vec{b}-\vec{c}),(\vec{c}-\vec{a})$ are **coplanar**
$\Leftrightarrow\left[\begin{array}{ccc} \vec{a}-\vec{b} & \vec{b}-\vec{c} & \vec{c}-\vec{a} \end{array}\right]=0$

Now,
$$
\begin{aligned}
& \left[\begin{array}{lll}
\vec{a}-\vec{b} & \vec{b}-\vec{c} & \vec{c}-\vec{a}
\end{array}\right] \\
& =(\vec{a}-\vec{b}) \cdot[(\vec{b}-\vec{c}) \times(\vec{c}-\vec{a})] \\
& =(\vec{a}-\vec{b}) \cdot[\vec{b} \times \vec{c}-\vec{b} \times \vec{a}-\vec{c} \times \vec{c}+\vec{c} \times \vec{a}] \text { [by the distributive law] } \\
& =(\vec{a}-\vec{b}) \cdot[\vec{b} \times \vec{c}+\vec{a} \times \vec{b}+\vec{c} \times \vec{a}] \quad[\because-\vec{b} \times \vec{a}=\vec{a} \times \vec{b} \text {, and } \vec{c} \times \vec{c}=\overrightarrow{0}] \\
& =\vec{a} \cdot(\vec{b} \times \vec{c})+\vec{a} \cdot(\vec{a} \times \vec{b})+\vec{a} \cdot[\vec{c} \times \vec{a}] \\
& -\vec{b} \cdot(\vec{b} \times \vec{c})-\vec{b} \cdot(\vec{a} \times \vec{b})-\vec{b} \cdot(\vec{c} \times \vec{a}) \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{a} & \vec{b}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{a}
\end{array}\right]-\left[\begin{array}{lll}
\vec{b} & \vec{b} & \vec{c}
\end{array}\right]-\left[\begin{array}{lll}
\vec{b} & \vec{a} & \vec{b}
\end{array}\right]-\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right] \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]-\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right] \quad[\because \text { scalar triple product with two equal } \\
& \text { vectors is } 0 \text { ] } \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]-\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=0 \quad\left\{\because\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]=\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]\right\} \text { . }
\end{aligned}
$$
Hence, $(\vec{a}-\vec{b}),(\vec{b}-\vec{c}),(\vec{c}-\vec{a})$ are **coplanar**.

---

### THEOREM 11
Show that the vectors $\vec{a}, \vec{b}, \vec{c}$ are **coplanar** if and only if $(\vec{a}+\vec{b})$, $(\vec{b}+\vec{c}),(\vec{c}+\vec{a})$ are **coplanar**.
[CBSE 2013C, '14]

#### PROOF

$(\vec{a}+\vec{b}),(\vec{b}+\vec{c}),(\vec{c}+\vec{a})$ are **coplanar**

$$
\begin{aligned}
& \Leftrightarrow[\vec{a}+\vec{b} \vec{b}+\vec{c} \vec{c}+\vec{a}]=0 \\
& \Leftrightarrow(\vec{a}+\vec{b}) \cdot\{(\vec{b}+\vec{c}) \times(\vec{c}+\vec{a})\}=0 \\
& \Leftrightarrow(\vec{a}+\vec{b}) \cdot\{\vec{b} \times \vec{c}+\vec{b} \times \vec{a}+\vec{c} \times \vec{c}+\vec{c} \times \vec{a}\}=0 \\
& \left.\begin{array}{rl}
\Leftrightarrow & (\vec{a}+\vec{b}) \cdot\{\vec{b} \times \vec{c}+\vec{b} \times \vec{a}+\vec{c} \times \vec{a}\}=0 \\
\Leftrightarrow & \vec{a} \cdot(\vec{b} \times \vec{c})+\vec{a} \cdot(\vec{b} \times \vec{a})+\vec{a} \cdot(\vec{c} \times \vec{a}) \\
& \quad+\vec{b} \cdot(\vec{b} \times \vec{c})+\vec{b} \cdot(\vec{b} \times \vec{a})+\vec{b} \cdot(\vec{c} \times \vec{a})=0
\end{array}\right] \\
& \begin{aligned}
\Leftrightarrow & {\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{a}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{a}
\end{array}\right]+\left[\begin{array}{lll}
\vec{b} & \vec{b} & \vec{c}
\end{array}\right] } \\
& \quad+\left[\begin{array}{lll}
\vec{b} & \vec{b} & \vec{a}
\end{array}\right]+\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]=0
\end{aligned} \\
& \Leftrightarrow\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]+\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]=0
\end{aligned}
$$
[ $\because$ scalar triple product with two equal vectors is 0 ]
$$
\begin{aligned}
& \Leftrightarrow 2\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=0 \quad\left\{\because\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]=\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]\right\} \\
& \Leftrightarrow\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=0 \\
& \Leftrightarrow \vec{a}, \vec{b}, \vec{c} \text { are coplanar. }
\end{aligned}
$$
Hence, $\vec{a}, \vec{b}$ and $\vec{c}$ are **coplanar** if and only if $(\vec{a}+\vec{b}),(\vec{b}+\vec{c})$ and $(\vec{c}+\vec{a})$ are **coplanar**.

---

### THEOREM 12
For any three vectors $\vec{a}, \vec{b}, \vec{c}$, prove that $[\vec{a} \vec{b}+\vec{c} \vec{a}+\vec{b}+\vec{c}]=0$.

#### PROOF

We have
$$
\begin{aligned}
& {\left[\begin{array}{lll}
\vec{a} & \vec{b}+\vec{c} & \vec{a}+\vec{b}+\vec{c}
\end{array}\right]} \\
& =\{\vec{a} \times(\vec{b}+\vec{c})\} \cdot(\vec{a}+\vec{b}+\vec{c}) \\
& =\{(\vec{a} \times \vec{b})+(\vec{a} \times \vec{c})\} \cdot(\vec{a}+\vec{b}+\vec{c}) \text { [by the distributive law] } \\
& =(\vec{a} \times \vec{b}) \cdot \vec{a}+(\vec{a} \times \vec{b}) \cdot \vec{b}+(\vec{a} \times \vec{b}) \cdot \vec{c}+(\vec{a} \times \vec{c}) \cdot \vec{a} \\
& +(\vec{a} \times \vec{c}) \cdot \vec{b}+(\vec{a} \times \vec{c}) \cdot \vec{c} \text { [by the distributive law] } \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{a}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{b}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{a}
\end{array}\right] \\
& +\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{b}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{c}
\end{array}\right] \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]+\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{b}
\end{array}\right] \\
& {[\because \text { scalar triple product with two equal vectors is } 0]} \\
& =\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]-\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=0 \quad\left\{\because\left[\begin{array}{lll}
\vec{a} & \vec{c} & \vec{b}
\end{array}\right]=-\left[\begin{arraylll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]\right\} \text { . }
\end{aligned}
$$
Hence, $\left[\begin{array}{lll} \vec{a} & \vec{b}+\vec{c} & \vec{a}+\vec{b}+\vec{c} \end{array}\right]=0$.

---

### THEOREM 13
If $\vec{a}, \vec{b}, \vec{c}$ are the position vectors of points $A, B, C$, prove that $(\vec{a} \times \vec{b}+\vec{b} \times \vec{c}+\vec{c} \times \vec{a})$ is a vector **perpendicular to the plane of triangle $ABC$**.
[CBSE 2001C]

#### PROOF

In order to prove the required result, we have to show that $(\vec{a} \times \vec{b}+\vec{b} \times \vec{c}+\vec{c} \times \vec{a})$ is perpendicular to each of the vectors $\overrightarrow{A B}, \overrightarrow{B C}$ and $\overrightarrow{C A}$.

We have, $\overrightarrow{A B}=(\vec{b}-\vec{a}), \overrightarrow{B C}=(\vec{c}-\vec{b})$ and $\overrightarrow{C A}=(\vec{a}-\vec{c})$.

Now, $(\vec{a} \times \vec{b}+\vec{b} \times \vec{c}+\vec{c} \times \vec{a}) \cdot(\vec{b}-\vec{a})$
$$
\begin{aligned}
&=(\vec{a} \times \vec{b}) \cdot(\vec{b}-\vec{a})+(\vec{b} \times \vec{c}) \cdot(\vec{b}-\vec{a})+(\vec{c} \times \vec{a}) \cdot(\vec{b}-\vec{a}) \\
&=(\vec{a} \times \vec{b}) \cdot \vec{b}-(\vec{a} \times \vec{b}) \cdot \vec{a}+(\vec{b} \times \vec{c}) \cdot \vec{b}-(\vec{b} \times \vec{c}) \cdot \vec{a} \\
& \quad+(\vec{c} \times \vec{a}) \cdot \vec{b}-(\vec{c} \times \vec{a}) \cdot \vec{a} \\
&= {[\vec{a} \vec{b} \vec{b}]-\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{a}
\end{array}\right]+\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{b}
\end{array}\right]-\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]+\left[\begin{array}{lll}
\vec{c} & \vec{a} & \vec{b}
\end{array}\right]-\left[\begin{array}{lll}
\vec{c} & \vec{a} & \vec{a}
\end{array}\right] } \\
&=\left[\begin{array}{lll}
\vec{c} & \vec{a} & \vec{b}
\end{array}\right]-\left[\begin{array}{lll}
\vec{b} & \vec{c} & \vec{a}
\end{array}\right]
\end{aligned}
$$
[ $\because$ scalar triple product with two equal vectors is 0 ]
$=0 \quad\left(\because\left[\begin{array}{lll}\vec{c} & \vec{a} & \vec{b}\end{array}\right]=\left[\begin{array}{lll}\vec{b} & \vec{c} & \vec{a}\end{array}\right]\right)$.

Similarly, $(\vec{a} \times \vec{b}+\vec{b} \times \vec{c}+\vec{c} \times \vec{a}) \cdot(\vec{c}-\vec{b})=0$.
And, $(\vec{a} \times \vec{b}+\vec{b} \times \vec{c}+\vec{c} \times \vec{a}) \cdot(\vec{a}-\vec{c})=0$.

Thus, $(\vec{a} \times \vec{b}+\vec{b} \times \vec{c}+\vec{c} \times \vec{a})$ is perpendicular to each one of the vectors $\overrightarrow{A B}, \overrightarrow{B C}$ and $\overrightarrow{C A}$, and therefore, it is perpendicular to the plane of $\triangle A B C$.

---

## Solved Examples

### Example 1:

Prove that $\left[\begin{array}{lll}\hat{i} & \hat{j} & \hat{k}\end{array}\right]=1$, and $\left[\begin{array}{lll}\hat{i} & \hat{k} & \hat{j}\end{array}\right]=-1$.

#### Solution:

We have

$$
\begin{aligned}
& {\left[\begin{array}{lll}
\hat{i} & \hat{j} & \hat{k}
\end{array}\right]=(\hat{i} \times \hat{j}) \cdot \hat{k}=\hat{k} \cdot \hat{k}=1 \text { and }} \\
& {[\hat{i} \hat{k} \quad \hat{j}]=(\hat{i} \times \hat{k}) \cdot \hat{j}=-\hat{j} \cdot \hat{j}=-1 .}
\end{aligned}
$$

---

### Example 2:

If $\vec{a}=2 \hat{i}+\hat{j}+3 \hat{k}, \vec{b}=-\hat{i}+2 \hat{j}+\hat{k}$, and $\vec{c}=-3 \hat{i}+\hat{j}+2 \hat{k}$, find $\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]$.

#### Solution:

We have

$$
\begin{aligned}
{\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=} & \left|\begin{array}{rrr}
2 & 1 & 3 \\
-1 & 2 & 1 \\
-3 & 1 & 2
\end{array}\right|=\left|\begin{array}{rrr}
0 & 5 & 5 \\
-1 & 2 & 1 \\
0 & -5 & -1
\end{array}\right| \\
& {\left[R_{1} \rightarrow R_{1}+2 R_{2}, R_{3} \rightarrow R_{3}-3 R_{2}\right] } \\
= & -(-1) \cdot[-5+25]=20 .
\end{aligned}
$$

---

### Example 3:

Find the **volume of the parallelepiped** whose coterminous edges are represented by the vectors

$$
\vec{a}=2 \hat{i}-3 \hat{j}+\hat{k}, \vec{b}=\hat{i}-\hat{j}+2 \hat{k} \text { and } \vec{c}=2 \hat{i}+\hat{j}-\hat{k}
$$

[CBSE 2000C]

#### Solution:

We have

$$
\begin{aligned}
{\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right] } & =\left|\begin{array}{rrr}
2 & -3 & 1 \\
1 & -1 & 2 \\
2 & 1 & -1
\end{array}\right|=\left|\begin{array}{rrr}
0 & -1 & -3 \\
1 & -1 & 2 \\
0 & 3 & -5
\end{array}\right| \\
& {\left[R_{1} \rightarrow R_{1}-2 R_{2}, \text { and } R_{3} \rightarrow R_{3}-2 R_{2}\right] } \\
& =(-1) \cdot(5+9)=-14 .
\end{aligned}
$$

$\therefore \quad$ **volume of the parallelepiped**

$$
=\left|\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]\right|=|-14|=14 \text { cubic units. }
$$

---

### Example 4:

Show that the vectors
$\hat{i}-3 \hat{j}+4 \hat{k}, 2 \hat{i}-\hat{j}+2 \hat{k}$ and $4 \hat{i}-7 \hat{j}+10 \hat{k}$ are **coplanar**.

#### Solution:

Let $\vec{a}=\hat{i}-3 \hat{j}+4 \hat{k}, \vec{b}=2 \hat{i}-\hat{j}+2 \hat{k}$ and $\vec{c}=4 \hat{i}-7 \hat{j}+10 \hat{k}$.

$$
\begin{aligned}
\therefore \quad\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right] & =\left|\begin{array}{rrr}
1 & -3 & 4 \\
2 & -1 & 2 \\
4 & -7 & 10
\end{array}\right|=\left|\begin{array}{rrr}
1 & -3 & 4 \\
0 & 5 & -6 \\
0 & 5 & -6
\end{array}\right|\left|\begin{array}{l}
R_{2} \rightarrow R_{2}-2 R_{1} \\
R_{3} \rightarrow R_{3}-4 R_{1}
\end{array}\right| \\
& =(-30+30)=0 .
\end{aligned}
$$

Hence, the given vectors are **coplanar**.

---

### Example 5:

Find the value of $\lambda$ so that the vectors

$$
\vec{a}=2 \hat{i}-3 \hat{j}+\hat{k}, \vec{b}=\hat{i}+2 \hat{j}-3 \hat{k} \text { and } \vec{c}=\hat{j}+\lambda \hat{k} \text { are coplanar. }
$$

#### Solution:

The given vectors will be **coplanar** if $\left[\begin{array}{lll}\vec{a} & \vec{b} & \vec{c}\end{array}\right]=0$.

$$
\text { Now, } \begin{aligned}
{\left[\begin{array}{lll}
\vec{a} & \vec{b} & \vec{c}
\end{array}\right]=0 } & \Leftrightarrow\left|\begin{array}{rrr}
2 & -3 & 1 \\
1 & 2 & -3 \\
0 & 1 & \lambda
\end{array}\right|=0 \Leftrightarrow\left|\begin{array}{rrr}
0 & -7 & 7 \\
1 & 2 & -3 \\
0 & 1 & \lambda
\end{array}\right|=0 \\
& \Leftrightarrow(-1)(-7 \lambda-7)=0 \Leftrightarrow 7 \lambda+7=0 \Leftrightarrow \lambda=-1 .
\end{aligned}
$$

Hence, the given vectors are **coplanar** when $\lambda=-1$.

---

### Example 6:

Show that the four points with position vectors $(4 \hat{i}+5 \hat{j}+\hat{k}),(-\hat{j}-\hat{k})$,

$$
(3 \hat{i}+9 \hat{j}+4 \hat{k}) \text { and } 4(-\hat{i}+\hat{j}+\hat{k}) \text { are coplanar. }
$$

[CBSE 2014]

#### Solution:

Let the given points be $A, B, C, D$ respectively.
Points $A, B, C, D$ are **coplanar** $\Leftrightarrow \overrightarrow{A B}, \overrightarrow{A C}$ and $\overrightarrow{A D}$ are **coplanar**

$$
\Leftrightarrow\left[\begin{array}{lll}
\overrightarrow{A B} & \overrightarrow{A C} & \overrightarrow{A D}
\end{array}\right]=0 .
$$

Now, $\quad \overrightarrow{A B}=($ p.v. of $B)-($ p.v. of $A)$

$$
=(-\hat{j}-\hat{k})-(4 \hat{i}+5 \hat{j}+\hat{k})=(-4 \hat{i}-6 \hat{j}-2 \hat{k})
$$

$\overrightarrow{A C}=(\text { p.v. of } C)-(\text { p.v. of } A)$

$$
=(3 \hat{i}+9 \hat{j}+4 \hat{k})-(4 \hat{i}+5 \hat{j}+\hat{k})=(-\hat{i}+4 \hat{j}+3 \hat{k})
$$

$\overrightarrow{A D}=(\text { p.v. of } D)-(\text { p.v. of } A)$

$$
=(-4 \hat{i}+4 \hat{j}+4 \hat{k})-(4 \hat{i}+5 \hat{j}+\hat{k})=(-8 \hat{i}-\hat{j}+3 \hat{k})
$$

$$
\therefore \quad[\overrightarrow{A B} \overrightarrow{A C} \overrightarrow{A D}] =\left|\begin{array}{rrr}
-4 & -6 & -2 \\
-1 & 4 & 3 \\
-8 & -1 & 3
\end{array}\right|
$$

$$
\begin{aligned}
& =\left|\begin{array}{rrr}
0 & -22 & -14 \\
-1 & 4 & 3 \\
0 & -21 & -33
\end{array}\right|\left\{\begin{array}{l}
R_{1} \rightarrow R_{1}-4 R_{2} \\
R_{3} \rightarrow R_{3}-8 R_{2}
\end{array}\right\} \\
& =-(-1)[462-462]=0
\end{aligned}
$$

$\therefore \quad \overrightarrow{A B}, \overrightarrow{A C}$ and $\overrightarrow{A D}$ are **coplanar**.
Hence, the points $A, B, C, D$ are **coplanar**.

---

### Example 7:

Find the value of $\lambda$ so that the four points with position vectors

$$
\begin{aligned}
& \quad(-6 \hat{i}+3 \hat{j}+2 \hat{k}),(3 \hat{i}+\lambda \hat{j}+4 \hat{k}),(5 \hat{i}+7 \hat{j}+3 \hat{k}) \\
& \text { and }(-13 \hat{i}+17 \hat{j}-2 \hat{k}) \text { are coplanar. }
\end{aligned}
$$

[CBSE 2000]

#### Solution:

Let the given points be $A, B, C, D$ respectively. Then,

$\overrightarrow{A B}=(\text { p.v. of } B)-(\text { p.v. of } A)$

$$
\begin{aligned}
& =(3 \hat{i}+\lambda \hat{j}+4 \hat{k})-(-6 \hat{i}+3 \hat{j}+2 \hat{k}) \\
& =9 \hat{i}+(\lambda-3) \hat{j}+2 \hat{k}
\end{aligned}
$$

$\overrightarrow{A C}=(\text { p.v. of } C)-(\text { p.v. of } A)$

$$
=(5 \hat{i}+7 \hat{j}+3 \hat{k})-(-6 \hat{i}+3 \hat{j}+2 \hat{k})=(11 \hat{i}+4 \hat{j}+\hat{k})
$$

$\overrightarrow{A D}=(\text { p.v. of } D)-(\text { p.v. of } A)$

$$
\begin{aligned}
& =(-13 \hat{i}+17 \hat{j}-\hat{k})-(-6 \hat{i}+3 \hat{j}+2 \hat{k}) \\
& =(-7 \hat{i}+14 \hat{j}-3 \hat{k})
\end{aligned}
$$

Now, $A, B, C, D$ are **coplanar**

$\Leftrightarrow\left[\begin{array}{lll}
\overrightarrow{A B} & \overrightarrow{A C} & \overrightarrow{A D}
\end{array}\right]=0 \Leftrightarrow\left|\begin{array}{rcr}
9 & \lambda-3 & 2 \\
11 & 4 & 1 \\
-7 & 14 & -3
\end{array}\right|=0$

$$
\begin{aligned}
& \Leftrightarrow 9(-12-14)-(\lambda-3)(-33+7)+2(154+28)=0 \\
& \Leftrightarrow-234+26 \lambda-78+364=0 \Leftrightarrow 26 \lambda=-52 \Leftrightarrow \lambda=-2 .
\end{aligned}
$$

Hence, the required value of $\lambda$ is -2 .

---

### Example 8:

Show that the points $A(-1,4,-3), B(3,2,-5), C(-3,8,-5)$ and $D(-3,2,1)$ are **coplanar**.

#### Solution:

Clearly, the position vectors of $A, B, C, D$ are $(-\hat{i}+4 \hat{j}-3 \hat{k})$,
$(3 \hat{i}+2 \hat{j}-5 \hat{k}),(-3 \hat{i}+8 \hat{j}-5 \hat{k})$ and $(-3 \hat{i}+2 \hat{j}+\hat{k})$ respectively.

$\therefore \quad \overrightarrow{A B}=(\text { p.v. of } B)-(\text { p.v. of } A)$

$$
=(3 \hat{i}+2 \hat{j}-5 \hat{k})-(-\hat{i}+4 \hat{j}-3 \hat{k})=(4 \hat{i}-2 \hat{j}-2 \hat{k})
$$

$\overrightarrow{A C}=(\text { p.v. of } C)-(\text { p.v. of } A)$

$$
=(-3 \hat{i}+8 \hat{j}-5 \hat{k})-(-\hat{i}+4 \hat{j}-3 \hat{k})=(-2 \hat{i}+4 \hat{j}-2 \hat{k})
$$

$\overrightarrow{A D}=(\text { p.v. of } D)-(\text { p.v. of } A)$

$$
=(-3 \hat{i}+2 \hat{j}+\hat{k})-(-\hat{i}+4 \hat{j}-3 \hat{k})=(-2 \hat{i}-2 \hat{j}+4 \hat{k})
$$

$\therefore \quad\left[\overrightarrow{A B} \xrightarrow{\rightarrow} \overrightarrow{A C} \xrightarrow{\rightarrow}\left|\begin{array}{rrr}
4 & -2 & -2 \\
-2 & 4 & -2 \\
-2 & -2 & 4
\end{array}\right|=2 \times(-2) \times(-2) \cdot\left|\begin{array}{rrr}
2 & -1 & -1 \\
1 & -2 & 1 \\
1 & 1 & -2
\end{array}\right|\right.$

$$
\begin{aligned}
&=8 \cdot\left|\begin{array}{lll}
0 & -3 & 3 \\
0 & -3 & 3 \\
1 & 1 & -2
\end{array}\right| \\
&=(8 \times 0)=0 \quad\left[\because R_{1} \text { and } R_{2} \text { are identical }\right]
\end{aligned}
$$

$\Rightarrow \quad \overrightarrow{A B}, \overrightarrow{A C}, \overrightarrow{A D}$ are **coplanar**
$\Rightarrow$ the points $A, B, C, D$ are **coplanar**.

---