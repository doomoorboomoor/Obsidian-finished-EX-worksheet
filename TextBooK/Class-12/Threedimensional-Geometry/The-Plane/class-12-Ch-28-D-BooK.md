## Equation of a Plane Parallel to a Given Plane

---

### Vector Form

Any plane parallel to $\vec{r} \cdot \vec{n}=q_{1}$ is given by **$\vec{r} \cdot \vec{n}=q_{2}$**, where the constant $q_{2}$ is determined by a given condition.

---

### Cartesian Form

Let $a x+b y+c z+d=0$ be a given plane.
Then, any plane parallel to this plane is of the form **$a x+b y+c z+k=0$**, where $k$ is determined by a given condition.

---

### Distance Between Two Parallel Planes

Let $a_{1} x+b_{1} y+c_{1} z+d_{1}=0$ and $a_{1} x+b_{1} y+c_{1} z+d_{2}=0$ be any two parallel planes. Then, we take a point $P\left(x_{1}, y_{1}, z_{1}\right)$ on any of these planes and find the length of perpendicular drawn from $P\left(x_{1}, y_{1}, z_{1}\right)$ to the other plane.

---

## Solved Examples

### Example 1

Find the vector equation of a plane which is parallel to the plane $\vec{r} \cdot(2 \hat{i}-\hat{j}+2 \hat{k})=5$ and passes through the point whose position vector is $(\hat{i}+\hat{j}+\hat{k})$.

#### Solution:

Any plane parallel to the plane $\vec{r} \cdot(2 \hat{i}-\hat{j}+2 \hat{k})=5$ is given by

$$
\begin{equation*}
\vec{r} \cdot(2 \hat{i}-\hat{j}+2 \hat{k})=q \text { for some constant } q . \tag{i}
\end{equation*}
$$

Since it passes through a point having position vector $(\hat{i}+\hat{j}+\hat{k})$, we have

$$
(\hat{i}+\hat{j}+\hat{k}) \cdot(2 \hat{i}-\hat{j}+2 \hat{k})=q \Rightarrow q=(2-1+2)=3 .
$$

Putting $q=3$ in (i), we get the required equation of the plane as

$$
\vec{r} \cdot(2 \hat{i}-\hat{j}+2 \hat{k})=3
$$

---

### Example 2

Find the vector equation of a plane which is parallel to the plane $\vec{r} \cdot(2 \hat{i}-3 \hat{j}+5 \hat{k})+2=0$ and passes through the point $(3,4,-1)$.

#### Solution:

Any plane parallel to the plane $\vec{r} \cdot(2 \hat{i}-3 \hat{j}+5 \hat{k})+2=0$ is given

$$
\begin{equation*}
\text { by } \vec{r} \cdot(2 \hat{i}-3 \hat{j}+5 \hat{k})=q \text { for some constant } q \text {. } \tag{i}
\end{equation*}
$$

Since it passes through a point $A(3,4,-1)$ whose position vector is $(3 \hat{i}+4 \hat{j}-\hat{k})$, we have

$$
(3 \hat{i}+4 \hat{j}-\hat{k}) \cdot(2 \hat{i}-3 \hat{j}+5 \hat{k})=q \Rightarrow q=(6-12-5)=-11 .
$$

Putting $q=-11$ in (i), we get the required equation of the plane as

$$
\vec{r} \cdot(2 \hat{i}-3 \hat{j}+5 \hat{k})=-11 \Rightarrow \vec{r} \cdot(2 \hat{i}-3 \hat{j}+5 \hat{k})+11=0 .
$$

---

### Example 3

Find the equation of the plane which is parallel to the plane $2 x-3 y+z+8=0$ and which passes through the point ( $-1,1,2$ ).

#### Solution:

Any plane parallel to the given plane is

$$
\begin{equation*}
2 x-3 y+z+k=0 \text { for some constant } k . \tag{i}
\end{equation*}
$$

If it passes through the point $A(-1,1,2)$, then

$$
\begin{aligned}
& 2 \times(-1)-3 \times 1+2+k=0 \\
\Rightarrow \quad & (-2-3+2)+k=0 \Rightarrow-3+k=0 \Rightarrow k=3 .
\end{aligned}
$$

Hence, the required equation of the plane is **$2 x-3 y+z+3=0$**.

---

### Example 4

Find the distance between the planes $2 x-y+3 z+4=0$ and $6 x-3 y+9 z-3=0$.

#### Solution:

Clearly, we have $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$.
$\therefore$ the given planes are parallel.
Let $P\left(x_{1}, y_{1}, z_{1}\right)$ be any point on the plane $2 x-y+3 z+4=0$.
Then, $2 x_{1}-y_{1}+3 z_{1}+4=0 \Rightarrow 2 x_{1}-y_{1}+3 z_{1}=-4$.

Let $p$ be the distance of the point $P\left(x_{1}, y_{1}, z_{1}\right)$ from the plane $6 x-3 y+9 z-3=0$. Then,

$$
\begin{aligned}
p & =\frac{\left|6 x_{1}-3 y_{1}+9 z_{1}-3\right|}{\sqrt{6^{2}+(-3)^{2}+9^{2}}}=\frac{\left|3\left(2 x_{1}-y_{1}+3 z_{1}\right)-3\right|}{\sqrt{36+9+81}} \\
& =\frac{|3 \times(-4)-3|}{\sqrt{126}}[\text { using (i) }] \\
& =\frac{|-15|}{3 \sqrt{14}}=\frac{15}{3 \sqrt{14}}=\frac{5}{\sqrt{14}} \text { units. }
\end{aligned}
$$

Hence, the distance between the given planes is **$\frac{5}{\sqrt{14}}$ units**.

---