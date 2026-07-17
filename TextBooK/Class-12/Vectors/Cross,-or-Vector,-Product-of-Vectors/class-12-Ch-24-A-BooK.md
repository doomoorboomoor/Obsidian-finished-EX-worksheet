## 24. Cross, or Vector, Product of Vectors

### Vector Product of Two Vectors

Let $\vec{a}$ and $\vec{b}$ be two nonzero, nonparallel vectors, and let $\theta$ be the angle between them such that $0<\theta<\pi$.
Then, the **vector product** of $\vec{a}$ and $\vec{b}$ is defined as

$$
\vec{a} \times \vec{b}=(|\vec{a}||\vec{b}| \sin \theta) \hat{n}
$$

where $\hat{n}$ is a unit vector perpendicular to both $\vec{a}$ and $\vec{b}$, such that $\vec{a}, \vec{b}, \hat{n}$ form a **right-handed system**.

![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-45.jpg?height=351&width=290&top_left_y=430&top_left_x=919)

When a right-handed screw is rotated from $\vec{a}$ to $\vec{b}$ and it advances along $\hat{n}$ then the system is said to be right handed.

**REMARK 1** If $\vec{a}$ and $\vec{b}$ are parallel or collinear, i.e., when $\theta=0$ or $\theta=\pi$ then we define, $\vec{a} \times \vec{b}=\overrightarrow{0}$.
In particular, $\vec{a} \times \vec{a}=\overrightarrow{0}$.

**REMARK 2** If $\vec{a}=\overrightarrow{0}$ or $\vec{b}=\overrightarrow{0}$, we define, $\vec{a} \times \vec{b}=\overrightarrow{0}$.

**REMARK 3** For any vector $\vec{a}$, we have $\vec{a} \times \vec{a}=(|\vec{a}||\vec{a}| \sin 0) \hat{n}=0 \hat{n}=\overrightarrow{0}$.

### Angle Between Two Vectors

Let $\theta$ be the angle between $\vec{a}$ and $\vec{b}$. Then,

$$
\begin{aligned}
& \vec{a} \times \vec{b}=(a b \sin \theta) \hat{n}, \text { where }|\vec{a}|=a \text { and }|\vec{b}|=b \\
\Rightarrow & |\vec{a} \times \vec{b}|=a b \sin \theta \\
\Rightarrow & \sin \theta=\frac{|\vec{a} \times \vec{b}|}{a b}=\frac{|\vec{a} \times \vec{b}|}{|\vec{a}||\vec{b}|} \\
\Rightarrow & \theta=\sin ^{-1}\left\{\frac{|\vec{a} \times \vec{b}|}{|\vec{a}||\vec{b}|}\right\}
\end{aligned}
$$

### Unit Vector Perpendicular to Two Given Vectors

A unit vector $\hat{n}$ perpendicular to each one of $\vec{a}$ and $\vec{b}$ is given by

$$
\hat{n}=\frac{(\vec{a} \times \vec{b})}{|\vec{a} \times \vec{b}|}
$$

---

## Properties of Vector Product

### RESULT 1
Vector product is **not commutative**.
In fact, we have $(\vec{b} \times \vec{a})=-(\vec{a} \times \vec{b})$.

#### PROOF
Let $\vec{a}, \vec{b}, \hat{n}$ form a right-handed system. Then,

$$
\begin{equation*}
(\vec{a} \times \vec{b})=(a b \sin \theta) \hat{n} \tag{i}
\end{equation*}
$$

Then, $\vec{b}, \vec{a},-\hat{n}$ form a right-handed system.

$$
\begin{equation*}
\therefore(\vec{b} \times \vec{a})=(b a \sin \theta)(-\hat{n}) \tag{ii}
\end{equation*}
$$

$\Rightarrow-(\vec{b} \times \vec{a})=(a b \sin \theta) \hat{n}$.

From (i) and (ii), we get $(\vec{a} \times \vec{b})=-(\vec{b} \times \vec{a})$.

---

### RESULT 2
For any two vectors $\vec{a}$ and $\vec{b}$, prove that

$$
(-\vec{b}) \times \vec{a}=(\vec{a} \times \vec{b})=\vec{b} \times(-\vec{a})
$$

#### PROOF
Let $\theta$ be the angle between $\vec{a}$ and $\vec{b}$.
Then, the angle between $(-\vec{b})$ and $\vec{a}$ is $(\pi-\theta)$.

![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-46.jpg?height=245&width=353&top_left_y=740&top_left_x=860)

And, $(-\vec{b}), \vec{a}, \hat{n}$ form a right-handed system.

$$
\begin{aligned}
\therefore \quad(-\vec{b}) \times \vec{a} & =|-\vec{b}||\vec{a}| \sin (\pi-\theta) \hat{n} \\
& =(|\vec{b}||\vec{a}| \sin \theta) \hat{n} \\
& =(a b \sin \theta) \hat{n}=(\vec{a} \times \vec{b}) . \\
\therefore \quad(-\vec{b}) \times \vec{a} & =(\vec{a} \times \vec{b}) .
\end{aligned}
$$

Similarly, $\vec{b} \times(-\vec{a})=(\vec{a} \times \vec{b})$.
Hence, $(-\vec{b}) \times \vec{a}=(\vec{a} \times \vec{b})=\vec{b} \times(-\vec{a})$.

---

### RESULT 3
For any scalar $m$, we have $(m \vec{a} \times \vec{b})=m(\vec{a} \times \vec{b})=\vec{a} \times(m \vec{b})$.

**An Important Note**
At a later stage, we shall prove that for any three vectors $\vec{a}, \vec{b}, \vec{c}$, we have $\vec{a} \times \vec{b} \cdot \vec{c}=\vec{a} \cdot \vec{b} \times \vec{c}$, i.e., the position of dot and cross can be interchanged. However, we shall use this fact in proving the following theorem.

---

### RESULT 4 (Distributive law)
For any vectors $\vec{a}, \vec{b}, \vec{c}$, prove that

$$
\vec{a} \times(\vec{b}+\vec{c})=(\vec{a} \times \vec{b})+(\vec{a} \times \vec{c})
$$

#### PROOF
Let $\vec{p}=[\vec{a} \times(\vec{b}+\vec{c})-(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})]$, and let $\vec{r}$ be any arbitrary vector.

Then,

$$
\begin{aligned}
\vec{r} \cdot \vec{p} & =\vec{r} \cdot[\vec{a} \times(\vec{b}+\vec{c})-(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})] \\
& =\vec{r} \cdot[\vec{a} \times(\vec{b}+\vec{c})]-\vec{r} \cdot(\vec{a} \times \vec{b})-\vec{r} \cdot(\vec{a} \times \vec{c}) \\
& =(\vec{r} \times \vec{a}) \cdot(\vec{b}+\vec{c})-(\vec{r} \times \vec{a}) \cdot \vec{b}-(\vec{r} \times \vec{a}) \cdot \vec{c} \\
& =(\vec{r} \times \vec{a}) \cdot \vec{b}+(\vec{r} \times \vec{a}) \cdot \vec{c}-(\vec{r} \times \vec{a}) \cdot \vec{b}-(\vec{r} \times \vec{a}) \cdot \vec{c} \\
& =0
\end{aligned}
$$

Now, $\vec{r} \cdot \vec{p}=0 \Rightarrow \vec{r}=\overrightarrow{0}$ or $\vec{p}=\overrightarrow{0}$ or $(\vec{r} \perp \vec{p})$.
Since $\vec{r}$ is an arbitrary vector, we may choose it in such a way that $\vec{r} \neq \overrightarrow{0}$ and $\vec{r}$ is not perpendicular to $\vec{p}$.
Then, $\quad \vec{p}=\overrightarrow{0}$

$$
\begin{aligned}
& \Rightarrow \vec{a} \times(\vec{b}+\vec{c})-(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})=\overrightarrow{0} \\
& \Rightarrow \vec{a} \times(\vec{b}+\vec{c})=(\vec{a} \times \vec{b})+(\vec{a} \times \vec{c})
\end{aligned}
$$

Hence, $\vec{a} \times(\vec{b}+\vec{c})=(\vec{a} \times \vec{b})+(\vec{a} \times \vec{c})$.

---

### RESULT 5
For any three vectors $\vec{a}, \vec{b}, \vec{c}$, prove that

$$
\vec{a} \times(\vec{b}-\vec{c})=(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})
$$

#### PROOF
We have

$$
\begin{aligned}
\vec{a} \times(\vec{b}-\vec{c}) & =\vec{a} \times[\vec{b}+(-\vec{c})] \\
& =(\vec{a} \times \vec{b})+\vec{a} \times(-\vec{c}) \quad[\text { by the distributive law }] \\
& =(\vec{a} \times \vec{b})+[-(\vec{a} \times \vec{c})] \quad[\because \quad \vec{a} \times(-\vec{c})=-(\vec{a} \times \vec{c})] \\
& =(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})
\end{aligned}
$$

Hence, $\vec{a} \times(\vec{b}-\vec{c})=(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})$.

---

### RESULT 6
Prove that two nonzero vectors $\vec{a}$ and $\vec{b}$ are **parallel or collinear** if and only if $(\vec{a} \times \vec{b})=\overrightarrow{0}$.

#### PROOF
Let $\vec{a} \neq \overrightarrow{0}$ and $\vec{b} \neq \overrightarrow{0}$ and let $\theta$ be the angle between them.
Let $\vec{a}$ and $\vec{b}$ be parallel or collinear.
Then, $\theta=0$ or $\theta=\pi$

$\Rightarrow \quad \sin \theta=0 \Rightarrow(\vec{a} \times \vec{b})=(a b \sin \theta) \hat{n}=0 \hat{n}=\overrightarrow{0} .$

Thus, when $\vec{a}$ and $\vec{b}$ are parallel or collinear, then $(\vec{a} \times \vec{b})=\overrightarrow{0}$.

Again, let $\vec{a} \neq \overrightarrow{0}, \vec{b} \neq \overrightarrow{0}$ and $(\vec{a} \times \vec{b})=\overrightarrow{0}$. Then,

$$
\begin{aligned}
(\vec{a} \times \vec{b})=\overrightarrow{0} & \Rightarrow|\vec{a} \times \vec{b}|=0 \\
& \Rightarrow a b \sin \theta=0 \\
& \Rightarrow \sin \theta=0 \quad[a \neq 0 \text { and } b \neq 0] \\
& \Rightarrow \theta=0 \text { or } \theta=\pi \\
& \Rightarrow(\vec{a} \| \vec{b}) \text { or }(\vec{a} \text { and } \vec{b} \text { are collinear })
\end{aligned}
$$

---

### RESULT 7
Prove that

$$
(\vec{a} \times \vec{b})=\overrightarrow{0} \Rightarrow \vec{a}=\overrightarrow{0} \text { or } \vec{b}=\overrightarrow{0} \text { or } \vec{a} \| \vec{b} \text { or } \vec{a} \text { and } \vec{b} \text { are collinear. }
$$

#### PROOF
Let $\theta$ be the angle between $\vec{a}$ and $\vec{b}$. Then,

$$
\begin{aligned}
\vec{a} \times \vec{b}=\overrightarrow{0} & \Rightarrow(a b \sin \theta) \hat{n}=\overrightarrow{0} \\
& \Rightarrow a b \sin \theta=0 \\
& \Rightarrow a=0 \text { or } b=0 \text { or } \sin \theta=0 \\
& \Rightarrow \vec{a}=\overrightarrow{0} \text { or } \vec{b}=\overrightarrow{0} \text { or } \theta=0 \text { or } \theta=\pi \\
& \Rightarrow \vec{a}=\overrightarrow{0} \text { or } \vec{b}=\overrightarrow{0} \text { or } \vec{a} \text { and } \vec{b} \text { are parallel or collinear. }
\end{aligned}
$$

**COROLLARY**
Show that $\vec{a} \times \vec{b}=\vec{a} \times \vec{c}$ does not imply that $\vec{b}=\vec{c}$.

#### PROOF
$\vec{a} \times \vec{b}=\vec{a} \times \vec{c} \Rightarrow \vec{a} \times \vec{b}-\vec{a} \times \vec{c}=\overrightarrow{0}$

$$
\begin{aligned}
& \Rightarrow \vec{a} \times(\vec{b}-\vec{c})=\overrightarrow{0} \\
& \Rightarrow \vec{a}=\overrightarrow{0} \text { or }(\vec{b}-\vec{c})=0 \text { or } \vec{a} \|(\vec{b}-\vec{c}) \\
& \Rightarrow \vec{a}=\overrightarrow{0} \text { or } \vec{b}=\vec{c} \text { or } \vec{a} \|(\vec{b}-\vec{c})
\end{aligned}
$$

$\therefore \quad \vec{a} \times \vec{b}=\vec{a} \times \vec{c}$ does not always mean that $\vec{b}=\vec{c}$.

---

## Summary

- (i) $(\vec{a} \times \vec{b})=-(\vec{b} \times \vec{a})$
- (ii) $(-\vec{b}) \times \vec{a}=(\vec{a} \times \vec{b})=\vec{b} \times(-\vec{a})$
- (iii) $m \vec{a} \times \vec{b}=m(\vec{a} \times \vec{b})=\vec{a} \times(m \vec{b})$
- (iv) $\vec{a} \times(\vec{b}+\vec{c})=(\vec{a} \times \vec{b})+(\vec{a} \times \vec{c})$
- (v) $\vec{a} \times(\vec{b}-\vec{c})=(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})$
- (vi) $\vec{a} \times \vec{b}=\overrightarrow{0} \Leftrightarrow(\vec{a} \| \vec{b})$ or ( $\vec{a}$ and $\vec{b}$ are collinear), when $\vec{a} \neq \overrightarrow{0}$ and $\vec{b} \neq \overrightarrow{0}$

---

## Area of a Parallelogram

### THEOREM 1
Two adjacent sides of a $||gm$ are represented by $\vec{a}$ and $\vec{b}$ respectively.
Prove that the area of the $|\operatornamegm=|\vec{a} \times \vec{b}|$.

#### PROOF
Let $A B C D$ be a $\| \mathrm{gm}$. Join $B D$.
Let $\overrightarrow{A B}=\vec{a}, \overrightarrow{A D}=\vec{b}$ and $\angle B A D=\theta$.
Draw $D L \perp A B$. Then,

$$
\begin{aligned}
& A B=a \text { and } D L=A D \sin \theta=b \sin \theta . \\
& \therefore \quad \operatorname{ar}(\triangle A B D)=\frac{1}{2} \times \text { base } \times \text { altitude } \\
&=\left(\frac{1}{2} \times A B \times D L\right)=\frac{1}{2} a b \sin \theta \\
&=\frac{1}{2}|\vec{a} \times \vec{b}| .
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-49.jpg?height=215&width=367&top_left_y=389&top_left_x=842)

$\therefore \quad \operatorname{ar}(\mid \operatornamegm A B C D)=2 \times \operatorname{ar}(\triangle A B D)=|\vec{a} \times \vec{b}|$.

**REMARK** $\quad(\vec{a} \times \vec{b})$ is called the **vector area** of the $\| \mathrm{gm}$.

---

## Area of a Triangle

### THEOREM 2
Prove that the area of $\triangle A B C$, where $\overrightarrow{A B}=\vec{a}$ and $\overrightarrow{A C}=\vec{b}$, is $\frac{1}{2}|\vec{a} \times \vec{b}|$.

#### PROOF
In $\triangle A B C$, let $\overrightarrow{A B}=\vec{a}$ and $\overrightarrow{A C}=\vec{b}$ and $\angle B A C=\theta$.
Draw $C L \perp A B$. Then,

$A B=a$ and $C L=(A C) \sin \theta=b \sin \theta$

and $\quad \operatorname{ar}(\triangle A B C)=\frac{1}{2} \times A B \times C L$

$$
=\frac{1}{2} a b \sin \theta=\frac{1}{2}|\vec{a} \times \vec{b}| .
$$

$\therefore \operatorname{ar}(\triangle A B C)=\frac{1}{2}|\vec{a} \times \vec{b}|$.

![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-49.jpg?height=237&width=259&top_left_y=1188&top_left_x=950)

**REMARK** $\quad \frac{1}{2}(\vec{a} \times \vec{b})$ is called the **vector area** of $\triangle A B C$.

## Area of a Quadrilateral

### THEOREM 3
Prove that the area of a quadrilateral $A B C D$ with diagonals $A C$ and $B D$ is $\frac{1}{2}|\overrightarrow{A C} \times \overrightarrow{B D}|$.

#### PROOF
Vector area of quad. $A B C D$
$=($ vector area of $\triangle A B C)+($ vector area of $\triangle A C D)$
$=\frac{1}{2}(\overrightarrow{A B} \times \overrightarrow{A C})+\frac{1}{2}(\overrightarrow{A C} \times \overrightarrow{A D})$

![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-49.jpg?height=197&width=310&top_left_y=1719&top_left_x=903)

$$
\begin{aligned}
& =-\frac{1}{2}(\overrightarrow{A C} \times \overrightarrow{A B})+\frac{1}{2}(\overrightarrow{A C} \times \overrightarrow{A D}) \\
& =\frac{1}{2} \cdot\{\overrightarrow{A C} \times(\overrightarrow{A D}-\overrightarrow{A B})\}=\frac{1}{2}(\overrightarrow{A C} \times \overrightarrow{B D}) \\
& \therefore \operatorname{ar}(\text { quad. } A B C D)=\frac{1}{2}|\overrightarrow{A C} \times \overrightarrow{B D}|
\end{aligned}
$$

---

## Summary

- (i) $\operatorname{ar}(\mid \operatorname{gm} A B C D)=|\vec{a} \times \vec{b}|$, where $\overrightarrow{A B}=\vec{a}$ and $\overrightarrow{A D}=\vec{b}$.
- (ii) $\operatorname{ar}(\mid \operatorname{gm} A B C D)=\frac{1}{2}\left|\vec{d}_{1} \times \vec{d}_{2}\right|$, where $\vec{d}_{1}$ and $\vec{d}_{2}$ are the diagonal vectors.
- (iii) $\operatorname{ar}(\triangle A B C)=\frac{1}{2}|\vec{a} \times \vec{b}|$, where $\overrightarrow{A B}=\vec{a}$ and $\overrightarrow{A C}=\vec{b}$.
- (iv) ar (quad. $A B C D$ ) $=\frac{1}{2}|\overrightarrow{A C} \times \overrightarrow{B D}|$, where $A C$ and $B D$ are its diagonals.

---

## Vector Product of an Orthonormal Vector Triad

For mutually perpendicular unit vectors $\hat{i}, \hat{j}, \hat{k}$, we have

$$
\begin{aligned}
& \hat{i} \times \hat{i}=\hat{j} \times \hat{j}=\hat{k} \times \hat{k}=\hat{0} \\
& \hat{i} \times \hat{j}=\hat{k}=-\hat{j} \times \hat{i}, \hat{j} \times \hat{k}=\hat{i}=-\hat{k} \times \hat{j} \text { and } \hat{k} \times \hat{i}=\hat{j}=-\hat{i} \times \hat{k}
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-50.jpg?height=243&width=239&top_left_y=1123&top_left_x=412)
![](https://cdn.mathpix.com/cropped/2025_09_25_f27128bac635c359d335g-50.jpg?height=223&width=193&top_left_y=1139&top_left_x=715)

---

## Vector Product in Terms of Components

Let $\vec{a}=a_{1} \hat{i}+a_{2} \hat{j}+a_{3} \hat{k}$ and $\vec{b}=b_{1} \hat{i}+b_{2} \hat{j}+b_{3} \hat{k}$. Then,

$$
\vec{a} \times \vec{b}=\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
a_{1} & a_{2} & a_{3} \\
b_{1} & b_{2} & b_{3}
\end{array}\right|
$$

#### PROOF
We have

$$
\begin{aligned}
\vec{a} \times \vec{b} & =\left(a_{1} \hat{i}+a_{2} \hat{j}+a_{3} \hat{k}\right) \times\left(b_{1} \hat{i}+b_{2} \hat{j}+b_{3} \hat{k}\right) \\
& =a_{1} b_{1}(\hat{i} \times \hat{i})+a_{1} b_{2}(\hat{i} \times \hat{j})+a_{1} b_{3}(\hat{i} \times \hat{k})
\end{aligned}
$$

$$
\begin{aligned}
& \quad+a_{2} b_{1}(\hat{j} \times \hat{i})+a_{2} b_{2}(\hat{j} \times \hat{j})+a_{2} b_{3}(\hat{j} \times \hat{k}) \\
& \quad+a_{3} b_{1}(\hat{k} \times \hat{i})+a_{3} b_{2}(\hat{k} \times \hat{j})+a_{3} b_{3}(\hat{k} \times \hat{k}) \\
& =\left(a_{2} b_{3}-a_{3} b_{2}\right) \hat{i}+\left(a_{3} b_{1}-a_{1} b_{3}\right) \hat{j}+\left(a_{1} b_{2}-a_{2} b_{1}\right) \hat{k} \\
& {\left[\begin{array}{lll}
\because & \hat{i} \times \hat{i}=\hat{j} \times \hat{j}=\hat{k} \times \hat{k}=\hat{0}, \hat{i} \times \hat{j}=\hat{k}, \hat{j} \times \hat{k}=\hat{i}, \hat{k} \times \hat{i}=\hat{j}, & \\
& \text { and } \hat{j} \times \hat{i}=-\hat{k}, \hat{k} \times \hat{j}=-\hat{i} \text { and } \hat{i} \times \hat{k}=-\hat{j}
\end{array}\right]} \\
& =\left|\begin{array}{lll}
\hat{i} & \hat{j} & \hat{k} \\
a_{1} & a_{2} & a_{3} \\
b_{1} & b_{2} & b_{3}
\end{array}\right| .
\end{aligned}
$$

---

## Solved Examples

### Example 1:

If $\vec{a}=(3 \hat{i}+\hat{j}-4 \hat{k})$ and $\vec{b}=(6 \hat{i}+5 \hat{j}-2 \hat{k})$, find $(\vec{a} \times \vec{b})$ and $|\vec{a} \times \vec{b}|$.

#### Solution:

We have

$$
\begin{aligned}
(\vec{a} \times \vec{b}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
3 & 1 & -4 \\
6 & 5 & -2
\end{array}\right| \\
& =(-2+20) \hat{i}-(-6+24) \hat{j}+(15-6) \hat{k} \\
& =(18 \hat{i}-18 \hat{j}+9 \hat{k}) \\
|\vec{a} \times \vec{b}|^{2} & =\left\{(18)^{2}+(-18)^{2}+9^{2}\right\}=729 \\
\Rightarrow \quad|\vec{a} \times \vec{b}| & =\sqrt{729}=27
\end{aligned}
$$

---

### Example 2:

If $\vec{a}=(\hat{i}-2 \hat{j}+3 \hat{k})$ and $\vec{b}=(2 \hat{i}+3 \hat{j}-5 \hat{k})$ then find $(\vec{a} \times \vec{b})$ and verify that $(\vec{a} \times \vec{b})$ is perpendicular to each one of $\vec{a}$ and $\vec{b}$.

#### Solution:

We have

$$
\begin{aligned}
(\vec{a} \times \vec{b}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
1 & -2 & 3 \\
2 & 3 & -5
\end{array}\right| \\
& =(10-9) \hat{i}-(-5-6) \hat{j}+(3+4) \hat{k}=(\hat{i}+11 \hat{j}+7 \hat{k})
\end{aligned}
$$

Now, $(\vec{a} \times \vec{b}) \cdot \vec{a}=(\hat{i}+11 \hat{j}+7 \hat{k}) \cdot(\hat{i}-2 \hat{j}+3 \hat{k})$.
$\therefore \quad(\vec{a} \times \vec{b}) \cdot \vec{a}=(1-22+21)=0$.
$\therefore \quad(\vec{a} \times \vec{b}) \perp \vec{a}$.
And, $(\vec{a} \times \vec{b}) \cdot \vec{b}=(\hat{i}+11 \vec{j}+7 \vec{k}) \cdot(2 \hat{i}+3 \hat{j}-5 \hat{k})$

$$
=(2+33-35)=0 .
$$

$\therefore \quad(\vec{a} \times \vec{b}) \perp \vec{b}$.

---

### Example 3:

If $\vec{a}=\hat{i}+\hat{j}+\hat{k}$ and $\vec{b}=\hat{j}-\hat{k}$, find a vector $\vec{c}$ such that $\vec{a} \times \vec{c}=\vec{b}$ and $\vec{a} \cdot \vec{c}=3$.
[CBSE 2013]

#### Solution:

Here $\vec{a}=\hat{i}+\hat{j}+\hat{k}$ and $\vec{b}=\hat{j}-\hat{k}$.
Let $\vec{c}=c_{1} \hat{i}+c_{2} \hat{j}+c_{3} \hat{k}$. Then,

$$
\vec{a} \cdot \vec{c}=3 \text { and } \vec{a} \times \vec{c}=\vec{b}
$$

$\Rightarrow(\hat{i}+\hat{j}+\hat{k}) \cdot\left(c_{1} \hat{i}+c_{2} \hat{j}+c_{3} \hat{k}\right)=3$
and $(\hat{i}+\hat{j}+\hat{k}) \times\left(c_{1} \hat{i}+c_{2} \hat{j}+c_{3} \hat{k}\right)=(\hat{j}-\hat{k})$
$\Rightarrow c_{1}+c_{2}+c_{3}=3 \quad \ldots$ (i) and $\left|\begin{array}{ccc}\hat{i} & \hat{j} & \hat{k} \\ 1 & 1 & 1 \\ c_{1} & c_{2} & c_{3}\end{array}\right|=(\hat{j}-\hat{k})$

Now, (ii) gives: $\left(c_{3}-c_{2}\right) \hat{i}-\left(c_{3}-c_{1}\right) \hat{j}+\left(c_{2}-c_{1}\right) \hat{k}=(\hat{j}-\hat{k})$
$\Rightarrow c_{3}-c_{2}=0, c_{1}-c_{3}=1$ and $c_{2}-c_{1}=-1$
$\Rightarrow \quad c_{3}=c_{2}$ and $c_{1}-c_{2}=1$.
Putting $c_{3}=c_{2}$ in (i), we get $c_{1}+2 c_{2}=3$.
On solving $c_{1}+2 c_{2}=3$ and $c_{1}-c_{2}=1$, we get $c_{2}=\frac{2}{3}$ and $c_{1}=\frac{5}{3}$.
$\therefore \quad c_{1}=\frac{5}{3}, c_{2}=\frac{2}{3}$ and $c_{3}=\frac{2}{3}$.
Hence, $\vec{c}=\frac{5}{3} \hat{i}+\frac{2}{3} \hat{j}+\frac{2}{3} \hat{k} \Rightarrow \vec{c}=\frac{1}{3}(5 \hat{i}+2 \hat{j}+2 \hat{k})$.

---

### Example 4:

Find a unit vector perpendicular to each one of the vectors $\vec{a}=(4 \hat{i}-\hat{j}+3 \hat{k})$ and $\vec{b}=(2 \hat{i}+2 \hat{j}-\hat{k})$.

#### Solution:

We know that $(\vec{a} \times \vec{b})$ is a vector perpendicular to each one of $\vec{a}$ and $\vec{b}$. So, the required vector is $\frac{(\vec{a} \times \vec{b})}{|\vec{a} \times \vec{b}|}$.

$$
\begin{aligned}
& \text { Now, }(\vec{a} \times \vec{b})=\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
4 & -1 & 3 \\
2 & 2 & -1
\end{array}\right| \\
& \qquad \begin{aligned}
= & (1-6) \hat{i}-(-4-6) \hat{j}+(8+2) \hat{k} \\
= & (-5 \hat{i}+10 \hat{j}+10 \hat{k})
\end{aligned} \\
& \text { Hence, the required unit vector }=\frac{(-5 \hat{i}+10 \hat{j}+10 \hat{k})}{1 \vec{a} \times \vec{b} \mid=\sqrt{(-5)^{2}+(10)^{2}+(10)^{2}}}=\sqrt{225}=15 . \\
& =\frac{1}{3}(-\hat{i}+2 \hat{j}+2 \hat{k})
\end{aligned}
$$

---

### Example 5:

Find a vector of magnitude 15 , which is perpendicular to both the vectors $(4 \hat{i}-\hat{j}+8 \hat{k})$ and $(-\hat{j}+\hat{k})$.

#### Solution:

Let $\vec{a}=(4 \hat{i}-\hat{j}+8 \hat{k})$ and $\vec{b}=(-\hat{j}+\hat{k})$.
A unit vector perpendicular to both $\vec{a}$ and $\vec{b}=\frac{(\vec{a} \times \vec{b})}{|\vec{a} \times \vec{b}|}$.
Now, $\vec{a} \times \vec{b}=\left|\begin{array}{ccc}\hat{i} & \hat{j} & \hat{k} \\ 4 & -1 & 8 \\ 0 & -1 & 1\end{array}\right|$

$$
\begin{aligned}
& =(-1+8) \hat{i}-(4-0) \hat{j}+(-4-0) \hat{k} \\
& =(7 \hat{i}-4 \hat{j}-4 \hat{k}) .
\end{aligned}
$$

$\therefore|\vec{a} \times \vec{b}|=\sqrt{7^{2}+(-4)^{2}+(-4)^{2}}=\sqrt{81}=9$.
So, a unit vector perpendicular to both $\vec{a}$ and $\vec{b}$

$$
=\frac{(\vec{a} \times \vec{b})}{|\vec{a} \times \vec{b}|}=\frac{7 \hat{i}-4 \hat{j}-4 \hat{k}}{9} .
$$

The required vector $=\frac{15(7 \hat{i}-4 \hat{j}-4 \hat{k})}{9}=\frac{5}{3}(7 \hat{i}-4 \hat{j}-4 \hat{k})$.

---

### Example 6:

Let $\vec{a}=(\hat{i}+4 \hat{j}+2 \hat{k}), \vec{b}=(3 \hat{i}-2 \hat{j}+7 \hat{k})$ and $\vec{c}=(2 \hat{i}-\hat{j}+4 \hat{k})$. Find a vector $\vec{d}$ which is perpendicular to both $\vec{a}$ and $\vec{b}$ such that $\vec{c} \cdot \vec{d}=18$.
[CBSE 2010]

#### Solution:

Since $\vec{d}$ is perpendicular to both $\vec{a}$ and $\vec{b}$, it follows that $\vec{d}$ is parallel to $(\vec{a} \times \vec{b})$.
Now, $(\vec{a} \times \vec{b})=\left|\begin{array}{ccc}\hat{i} & \hat{j} & \hat{k} \\ 1 & 4 & 2 \\ 3 & -2 & 7\end{array}\right|$

$$
=(28+4) \hat{i}-(7-6) \hat{j}+(-2-12) \hat{k}=(32 \hat{i}-\hat{j}-14 \hat{k}) .
$$

Since $\vec{d}$ is parallel to $(\vec{a} \times \vec{b})$, we have $\vec{d}=\lambda(\vec{a} \times \vec{b})$ for some scalar $\lambda$.

$$
\begin{equation*}
\therefore \quad \vec{d}=\lambda(32 \hat{i}-\hat{j}-14 \hat{k})=(32 \lambda \hat{i}-\lambda \hat{j}-14 \lambda \hat{k}) \tag{i}
\end{equation*}
$$

Since $\vec{c} \cdot \vec{d}=18$, we have

$$
\begin{aligned}
& \quad(2 \hat{i}-\hat{j}+4 \hat{k}) \cdot(32 \lambda \hat{i}-\lambda \hat{j}-14 \lambda \hat{k})=18 \\
& \Rightarrow \quad(64 \lambda+\lambda-56 \lambda)=18 \Rightarrow 9 \lambda=18 \Rightarrow \lambda=2 \\
& \text { Hence, } \vec{d}=(64 \hat{i}-2 \hat{j}-28 \hat{k})[\text { putting } \lambda=2 \text { in (i)]. }
\end{aligned}
$$

---

### Example 7:

Find a vector of magnitude 5 units, perpendicular to each of the vectors
$(\vec{a}+\vec{b})$ and $(\vec{a}-\vec{b})$, where $\vec{a}=(\hat{i}+\hat{j}+\hat{k})$ and $\vec{b}=(\hat{i}+2 \hat{j}+3 \hat{k})$.
[CBSE 2008C]

#### Solution:

We have

$$
\begin{aligned}
& \qquad \begin{aligned}
(\vec{a}+\vec{b}) & =(\hat{i}+\hat{j}+\hat{k})+(\hat{i}+2 \hat{j}+3 \hat{k})=(2 \hat{i}+3 \hat{j}+4 \hat{k}) \text { and } \\
(\vec{a}-\vec{b}) & =(\hat{i}+\hat{j}+\hat{k})-(\hat{i}+2 \hat{j}+3 \hat{k})=(-\hat{j}-2 \hat{k}) . \\
\therefore \quad(\vec{a}+\vec{b}) \times(\vec{a}-\vec{b}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
2 & 3 & 4 \\
0 & -1 & -2
\end{array}\right| \\
& =(-6+4) \hat{i}-(-4-0) \hat{j}+(-2-0) \hat{k} \\
& =(-2 \hat{i}+4 \hat{j}-2 \hat{k}) . \\
\therefore \quad|(\vec{a}+\vec{b}) \times(\vec{a}-\vec{b})| & =\sqrt{(-2)^{2}+4^{2}+(-2)^{2}}=\sqrt{24}=2 \sqrt{6} .
\end{aligned}
\end{aligned}
$$

So, the vectors of magnitude 5 units and perpendicular to each of the vectors $(\vec{a}+\vec{b})$ and $(\vec{a}-\vec{b})$ are:

$$
\pm \frac{5\{(\vec{a}+\vec{b}) \times(\vec{a}-\vec{b})\}}{|(\vec{a}+\vec{b}) \times(\vec{a}-\vec{b})|}= \pm \frac{5(-2 \hat{i}+4 \hat{j}-2 \hat{k})}{2 \sqrt{6}}= \pm \frac{5(-\hat{i}+2 \hat{j}-\hat{k})}{\sqrt{6}} .
$$

---

### Example 8:

If $\vec{a}=4 \hat{i}+3 \hat{j}+2 \hat{k}$ and $\vec{b}=3 \hat{i}+2 \hat{k}$, find $|\vec{b} \times 2 \vec{a}|$.

#### Solution:

We have

$$
\begin{aligned}
\vec{b}=(3 \hat{i}+2 \hat{k}) \text { and } 2 \vec{a}=(8 \hat{i}+6 \hat{j}+4 \hat{k}) . & \\
\therefore \quad(\vec{b} \times 2 \vec{a}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
3 & 0 & 2 \\
8 & 6 & 4
\end{array}\right| \\
& =(0-12) \hat{i}+(16-12) \hat{j}+(18-0) \hat{k} \\
& =(-12 \hat{i}+4 \hat{j}+18 \hat{k}) . \\
\therefore \quad|\vec{b} \times 2 \vec{a}| & =|-12 \hat{i}+4 \hat{j}+18 \hat{k}| \\
& =\sqrt{(-12)^{2}+4^{2}+(18)^{2}}=\sqrt{484}=22 .
\end{aligned}
$$

Hence, $|\vec{b} \times 2 \vec{a}|=22$.

---

### Example 9:

If $|\vec{a}|=\sqrt{26},|\vec{b}|=7$ and $|\vec{a} \times \vec{b}|=35$, find $\vec{a} \cdot \vec{b}$.

#### Solution:

Given that $|\vec{a}|=\sqrt{26}$ and $|\vec{b}|=7$, and $|\vec{a} \times \vec{b}|=35$.

$$
\begin{aligned}
\therefore \quad|\vec{a} \times \vec{b}|=35 & \Rightarrow|\vec{a}||\vec{b}| \sin \theta=35 \\
& \Rightarrow \sin \theta=\frac{35}{|\vec{a}||\vec{b}|}=\frac{35}{(\sqrt{26}) \times 7}=\frac{5}{\sqrt{26}} .
\end{aligned}
$$

Now, $\cos \theta=\sqrt{1-\sin ^{2} \theta}=\sqrt{1-\frac{25}{26}}=\frac{1}{\sqrt{26}}$.
$\therefore \quad \vec{a} \cdot \vec{b}=|\vec{a}||\vec{b}| \cos \theta=\left(\sqrt{26} \times 7 \times \frac{1}{\sqrt{26}}\right)=7$.
Hence, $\vec{a} \cdot \vec{b}=7$.

---

### Example 10:

If $|\vec{a}|=2,|\vec{b}|=7$ and $(\vec{a} \times \vec{b})=(3 \hat{i}+2 \hat{j}+6 \hat{k})$, find the angle between $\vec{a}$ and $\vec{b}$.

#### Solution:

Let $\theta$ be the angle between $\vec{a}$ and $\vec{b}$. Then,

$$
\begin{aligned}
& \vec{a} \times \vec{b}=3 \hat{i}+2 \hat{j}+6 \hat{k} \\
\Rightarrow & |\vec{a} \times \vec{b}|=\sqrt{3^{2}+2^{2}+6^{2}}=\sqrt{49}=7 \\
\Rightarrow & |\vec{a}||\vec{b}| \sin \theta=7 \\
\Rightarrow & \sin \theta=\frac{7}{|\vec{a}||\vec{b}|}=\frac{7}{(2 \times 7)}=\frac{1}{2} \Rightarrow \theta=\frac{\pi}{6} .
\end{aligned}
$$

Hence, the required angle between $\vec{a}$ and $\vec{b}$ is $\frac{\pi}{6}$.

---

### Example 11:

Find the sine of the angle between the vectors $\vec{a}=(2 \hat{i}-\hat{j}+3 \hat{k})$ and $\vec{b}=(\hat{i}+3 \hat{j}+2 \hat{k})$.

#### Solution:

We have

$$
\begin{aligned}
& \begin{aligned}
(\vec{a} \times \vec{b}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
2 & -1 & 3 \\
1 & 3 & 2
\end{array}\right| \\
& =(-2-9) \hat{i}-(4-3) \hat{j}+(6+1) \hat{k} \\
& =(-11 \hat{i}-\hat{j}+7 \hat{k}) \\
|\vec{a} \times \vec{b}| & =\sqrt{(-11)^{2}+(-1)^{2}+7^{2}}=\sqrt{171}=3 \sqrt{19} \\
|\vec{a}| & =\sqrt{2^{2}+(-1)^{2}+3^{2}}=\sqrt{14} \\
|\vec{b}| & =\sqrt{1^{2}+3^{2}+2^{2}}=\sqrt{14}
\end{aligned}
\end{aligned}
$$

Let $\theta$ be the angle between $\vec{a}$ and $\vec{b}$. Then,

$$
\sin \theta=\frac{|\vec{a} \times \vec{b}|}{|\vec{a}||\vec{b}|}=\frac{3 \sqrt{19}}{(\sqrt{14})(\sqrt{14})}=\frac{3}{14} \sqrt{19}
$$

---

### Example 12:

If the vectors $\vec{a}$ and $\vec{b}$ are such that $|\vec{a}|=3,|\vec{b}|=\frac{2}{3}$ and $\vec{a} \times \vec{b}$ is a unit vector then write the angle between $\vec{a}$ and $\vec{b}$.
[CBSE 2014]

#### Solution:

Let $\theta$ be the angle between $\vec{a}$ and $\vec{b}$. Then,

$$
\begin{aligned}
|\vec{a} \times \vec{b}|=1 & \Rightarrow|\vec{a}||\vec{b}| \sin \theta=1 \Rightarrow\left(3 \times \frac{2}{3}\right) \sin \theta=1 \\
& \Rightarrow \sin \theta=\frac{1}{2} \Rightarrow \theta=30^{\circ}
\end{aligned}
$$

Hence, the angle between $\vec{a}$ and $\vec{b}$ is $30^{\circ}$.

---

### Example 13:

Find the area of the parallelogram whose adjacent sides are represented by the vectors $(3 \hat{i}+\hat{j}-2 \hat{k})$ and $(\hat{i}-3 \hat{j}+4 \hat{k})$.

#### Solution:

Let $\vec{a}=(3 \hat{i}+\hat{j}-2 \hat{k})$ and $\vec{b}=(\hat{i}-3 \hat{j}+4 \hat{k})$.
Then, vector area of the $\| \mathrm{gm}$ is $(\vec{a} \times \vec{b})$.

$$
\begin{aligned}
\text { Now, }(\vec{a} \times \vec{b}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
3 & 1 & -2 \\
1 & -3 & 4
\end{array}\right| \\
& =(4-6) \hat{i}-(12+2) \hat{j}+(-9-1) \hat{k} \\
& =(-2 \hat{i}-14 \hat{j}-10 \hat{k}) . \\
\text { Required area } & =|\vec{a} \times \vec{b}| \\
& =\sqrt{(-2)^{2}+(-14)^{2}+(-10)^{2}} \text { sq units } \\
& =\sqrt{300} \text { sq units }=10 \sqrt{3} \text { sq units. }
\end{aligned}
$$

---

### Example 14:

Find the area of the parallelogram whose diagonals are represented by the vectors $\vec{d}_{1}=(2 \hat{i}-\hat{j}+\hat{k})$ and $\vec{d}_{2}=(3 \hat{i}+4 \hat{j}-\hat{k})$.

#### Solution:

Given that $\vec{d}_{1}=(2 \hat{i}-\hat{j}+\hat{k})$ and $\vec{d}_{2}=(3 \hat{i}+4 \hat{j}-\hat{k})$.
Vector area of the ||gm is $\frac{1}{2}\left(\vec{d}_{1} \times \vec{d}_{2}\right)$.

$$
\begin{aligned}
\text { Now, }\left(\overrightarrow{d_{1}} \times \overrightarrow{d_{2}}\right) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
2 & -1 & 1 \\
3 & 4 & -1
\end{array}\right| \\
& =(1-4) \hat{i}-(-2-3) \hat{j}+(8+3) \hat{k} \\
& =(-3 \hat{i}+5 \hat{j}+11 \hat{k}) . \\
\text { Required area } & =\frac{1}{2}\left|\vec{d}_{1} \times \vec{d}_{2}\right| \\
& =\frac{1}{2} \sqrt{(-3)^{2}+5^{2}+(11)^{2}} \text { sq units } \\
& =\frac{1}{2} \sqrt{155} \text { sq units. }
\end{aligned}
$$

---

### Example 15:

Find the area of the triangle whose adjacent sides are determined by the vectors $\vec{a}=(-2 \hat{i}-5 \hat{k})$ and $\vec{b}=(\hat{i}-2 \hat{j}-\hat{k})$.

#### Solution:

Two adjacent sides of the given triangle are represented by the vectors $\vec{a}=(-2 \hat{i}-5 \hat{k})$ and $\vec{b}=(\hat{i}-2 \hat{j}-\hat{k})$.

So, the area of the triangle is $\frac{1}{2}|\vec{a} \times \vec{b}|$.

$$
\begin{aligned}
& \text { Now, }(\vec{a} \times \vec{b}) \\
& =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
-2 & 0 & -5 \\
1 & -2 & -1
\end{array}\right| \\
& =(0-10) \hat{i}-(2+5) \hat{j}+(4-0) \hat{k} \\
& =(-10 \hat{i}-7 \hat{j}+4 \hat{k}) . \\
& \therefore \text { required area }=\frac{1}{2}|\vec{a} \times \vec{b}| \\
& =\frac{1}{2} \cdot\left\{\sqrt{(-10)^{2}+(-7)^{2}+4^{2}}\right\} \text { sq units } \\
& =\frac{1}{2} \sqrt{165} \text { sq units. }
\end{aligned}
$$

---

### Example 16:

Using vectors find the area of $\triangle A B C$ whose vertices are $A(1,2,3)$, $B(2,-1,4)$ and $C(4,5,-1)$.
[CBSE 2013]

#### Solution:

We have
Position vector of $A=(\hat{i}+2 \hat{j}+3 \hat{k})$,
position vector of $B=(2 \hat{i}-\hat{j}+4 \hat{k})$ and
position vector of $C=(4 \hat{i}+5 \hat{j}-\hat{k})$.
$\therefore \quad \overrightarrow{A B}=($ position vector of $B)-($ position vector of $A)$
$$
=(2 \hat{i}-\hat{j}+4 \hat{k})-(\hat{i}+2 \hat{j}+3 \hat{k})=(\hat{i}-3 \hat{j}+\hat{k}) .
$$

$$
\begin{aligned}
\overrightarrow{A C} & =(\text { position vector of } C)-(\text { position vector of } A) \\
& =(4 \hat{i}+5 \hat{j}-\hat{k})-(\hat{i}+2 \hat{j}+3 \hat{k})=(3 \hat{i}+3 \hat{j}-4 \hat{k}) .
\end{aligned}
$$

$\therefore \quad$ area of $\triangle A B C=\left|\frac{1}{2}(\overrightarrow{A B} \times \overrightarrow{A C})\right|$.
Now,
$$
\overrightarrow{A B} \times \overrightarrow{A C}=\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
1 & -3 & 1 \\
3 & 3 & -4
\end{array}\right|
$$

$$
\begin{aligned}
& =(12-3) \hat{i}-(-4-3) \hat{j}+(3+9) \hat{k} \\
& =(9 \hat{i}+7 \hat{j}+12 \hat{k}) . \\
\therefore \quad \text { area of } \triangle A B C & =\frac{1}{2}|\overrightarrow{A B} \times \overrightarrow{A C}| \\
& =\frac{1}{2}|(9 \hat{i}+7 \hat{j}+12 \hat{k})|=\frac{1}{2} \cdot \sqrt{(9)^{2}+7^{2}+(12)^{2}} \\
& =\frac{1}{2} \cdot \sqrt{(81+49+144)}=\frac{1}{2} \sqrt{274} \text { sq units. }
\end{aligned}
$$

Hence, the area of $\triangle A B C$ is $\frac{1}{2} \sqrt{274}$ sq units.

---

### Example 17:

Show that the points whose position vectors are $(5 \hat{i}+6 \hat{j}+7 \hat{k})$, $(7 \hat{i}-8 \hat{j}+9 \hat{k})$ and $(3 \hat{i}+20 \hat{j}+5 \hat{k})$ are collinear.

#### Solution:

Let the given points be $A, B$, and $C$ respectively. Then,

$$
\begin{aligned}
\overrightarrow{A B} & =(\text { position vector of } B)-(\text { position vector of } A) \\
& =(7 \hat{i}-8 \hat{j}+9 \hat{k})-(5 \hat{i}+6 \hat{j}+7 \hat{k})=(2 \hat{i}-14 \hat{j}+2 \hat{k})
\end{aligned}
$$

And, $\overrightarrow{A C}=($ position vector of $C)-($ position vector of $A)$

$$
\begin{aligned}
& =(3 \hat{i}+20 \hat{j}+5 \hat{k})-(5 \hat{i}+6 \hat{j}+7 \hat{k}) \\
& =(-2 \hat{i}+14 \hat{j}-2 \hat{k})
\end{aligned}
$$

$$
\begin{aligned}
\therefore \quad(\overrightarrow{A B} \times \overrightarrow{A C}) & =\left|\begin{array}{rrr}
\hat{i} & \hat{j} & \hat{k} \\
2 & -14 & 2 \\
-2 & 14 & -2
\end{array}\right| \\
& =2 \times(-2) \cdot\left|\begin{array{rrr}
\hat{i} & \hat{j} & \hat{k} \\
1 & -7 & 1 \\
1 & -7 & 1
\end{array}\right|=(-4) \times \overrightarrow{0}=\overrightarrow{0}
\end{aligned}
$$

$\left[\because \quad R_{2}\right.$ and $R_{3}$ are identical $]$.
So, $\overrightarrow{A B}$ and $\overrightarrow{A C}$ are parallel vectors, having a common end point, $A$.
Hence, the given points $A, B$ and $C$ are collinear.

---

### Example 18:

Using vector method, show that the points $A(2,-1,3), B(4,3,1)$ and $C(3,1,2)$ are collinear.

#### Solution:

Clearly, we have
position vector of $A=(2 \hat{i}-\hat{j}+3 \hat{k})$,
position vector of $B=(4 \hat{i}+3 \hat{j}+\hat{k})$, and
position vector of $C=(3 \hat{i}+\hat{j}+2 \hat{k})$.

$$
\begin{aligned}
\therefore \quad \overrightarrow{A B} & =(\text { position vector of } B)-(\text { position vector of } A) \\
& =(4 \hat{i}+3 \hat{j}+\hat{k})-(2 \hat{i}-\hat{j}+3 \hat{k})=(2 \hat{i}+4 \hat{j}-2 \hat{k}) \\
\overrightarrow{A C} & =(\text { position vector of } C)-(\text { position vector of } A) \\
& =(3 \hat{i}+\hat{j}+2 \hat{k})-(2 \hat{i}-\hat{j}+3 \hat{k})=(\hat{i}+2 \hat{j}-\hat{k}) \\
\therefore \quad(\overrightarrow{A B} \times \overrightarrow{A C}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
2 & 4 & -2 \\
1 & 2 & -1
\end{array}\right| \\
& =2\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
1 & 2 & -1 \\
1 & 2 & -1
\end{array}\right|=\overrightarrow{0}\left[\because R_{2} \text { and } R_{3} \text { are identical }\right] .
\end{aligned}
$$

Thus, $\overrightarrow{A B}$ and $\overrightarrow{A C}$ are parallel vectors, having a common end point, $A$.
Hence, the given points $A, B$, and $C$ are collinear.

---

### Example 19:

Show that the points having position vectors
$(\vec{a}-2 \vec{b}+3 \vec{c}),(-2 \vec{a}+3 \vec{b}+2 \vec{c}),(-8 \vec{a}+13 \vec{b})$
are collinear, whatever be $\vec{a}, \vec{b}, \vec{c}$.

#### Solution:

Let $A, B, C$ be the given points whose position vectors are $(\vec{a}-2 \vec{b}+3 \vec{c}),(-2 \vec{a}+3 \vec{b}+2 \vec{c})$ and $(-8 \vec{a}+13 \vec{b})$ respectively. Then,

$$
\begin{aligned}
\overrightarrow{A B} & =(\text { position vector of } B)-(\text { position vector of } A) \\
& =(-2 \vec{a}+3 \vec{b}+2 \vec{c})-(\vec{a}-2 \vec{b}+3 \vec{c})=(-3 \vec{a}+5 \vec{b}-\vec{c}), \text { and } \\
\overrightarrow{A C} & =(\text { position vector of } C)-(\text { position vector of } A) \\
& =(-8 \vec{a}+13 \vec{b})-(\vec{a}-2 \vec{b}+3 \vec{c})=(-9 \vec{a}+15 \vec{b}-3 \vec{c}) \\
\therefore \quad(\overrightarrow{A B} \times \overrightarrow{A C}) & =(-3 \vec{a}+5 \vec{b}-\vec{c}) \times(-9 \vec{a}+15 \vec{b}-3 \vec{c}) \\
& =\vec{p} \times 3 \vec{p}, \text { where }(-3 \vec{a}+5 \vec{b}-\vec{c})=\vec{p} \\
& =\overrightarrow{0}[\because \vec{p} \times \vec{p}=\overrightarrow{0}]
\end{aligned}
$$

$\therefore \overrightarrow{A B}$ and $\overrightarrow{A C}$ are parallel vectors, having a common end point, $A$.
Hence, the points $A, B$ and $C$ are collinear.

---

### Example 20:

Prove that $(\vec{a}-\vec{b}) \times(\vec{a}+\vec{b})=2(\vec{a} \times \vec{b})$.

#### PROOF

We have

$$
\begin{aligned}
& (\vec{a}-\vec{b}) \times(\vec{a}+\vec{b}) \\
& \quad=\vec{a} \times \vec{a}+\vec{a} \times \vec{b}-\vec{b} \times \vec{a}-\vec{b} \times \vec{b} \quad \text { [by the distributive law] } \\
& \quad=\vec{a} \times \vec{b}-\vec{b} \times \vec{a} \quad[\because \vec{a} \times \vec{a}=\overrightarrow{0} \text { and } \vec{b} \times \vec{b}=\overrightarrow{0}] \\
& \quad=(\vec{a} \times \vec{b})+(\vec{a} \times \vec{b}) \quad[\because-\vec{b} \times \vec{a}=(\vec{a} \times \vec{b})] \\
& \quad=2(\vec{a} \times \vec{b})
\end{aligned}
$$

Hence, $(\vec{a}-\vec{b}) \times(\vec{a}+\vec{b})=2(\vec{a} \times \vec{b})$.

---

### Example 21:

If $\vec{a} \times \vec{b}=\vec{c} \times \vec{d}$ and $\vec{a} \times \vec{c}=\vec{b} \times \vec{d}$, show that $(\vec{a}-\vec{d})$ is parallel to $(\vec{b}-\vec{c})$, it being given that $a \neq d$ and $b \neq c$.
[CBSE 2009]

#### Solution:

$\vec{a} \times \vec{b}=\vec{c} \times \vec{d}$, and $\vec{a} \times \vec{c}=\vec{b} \times \vec{d}$

$$
\begin{aligned}
& \Rightarrow \vec{a} \times \vec{b}-\vec{a} \times \vec{c}=\vec{c} \times \vec{d}-\vec{b} \times \vec{d} \\
& \Rightarrow \vec{a} \times \vec{b}-\vec{a} \times \vec{c}+\vec{b} \times \vec{d}-\vec{c} \times \vec{d}=\overrightarrow{0} \\
& \Rightarrow \vec{a} \times(\vec{b}-\vec{c})+(\vec{b}-\vec{c}) \times \vec{d}=\overrightarrow{0} \\
& \Rightarrow \vec{a} \times(\vec{b}-\vec{c})-\vec{d} \times(\vec{b}-\vec{c})=\overrightarrow{0} \\
& \Rightarrow(\vec{a}-\vec{d}) \times(\vec{b}-\vec{c})=\overrightarrow{0} \\
& \Rightarrow(\vec{a}-\vec{d}) \|(\vec{b}-\vec{c})
\end{aligned}
$$

Hence, $(\vec{a}-\vec{d})$ is parallel to $(\vec{b}-\vec{c})$.

---

### Example 22:

Prove that $\vec{a} \times(\vec{b}+\vec{c})+\vec{b} \times(\vec{c}+\vec{a})+\vec{c} \times(\vec{a}+\vec{b})=\overrightarrow{0}$.

#### Solution:

We have

$$
\begin{aligned}
\vec{a} & \times(\vec{b}+\vec{c})+\vec{b} \times(\vec{c}+\vec{a})+\vec{c} \times(\vec{a}+\vec{b}) \\
& =(\vec{a} \times \vec{b})+(\vec{a} \times \vec{c})+(\vec{b} \times \vec{c})+(\vec{b} \times \vec{a})+(\vec{c} \times \vec{a})+(\vec{c} \times \vec{b})
\end{aligned}
$$

[by the distributive law]

$$
\begin{aligned}
& =(\vec{a} \times \vec{b})+(\vec{b} \times \vec{c})+(\vec{c} \times \vec{a})-(\vec{a} \times \vec{b})-(\vec{b} \times \vec{c})-(\vec{c} \times \vec{a}) \\
& =\overrightarrow{0}[\because(\vec{b} \times \vec{a})=-(\vec{a} \times \vec{b}),(\vec{c} \times \vec{b})=-(\vec{b} \times \vec{c})
\end{aligned}
$$

and $(\vec{a} \times \vec{c})=-(\vec{c} \times \vec{a})]$.

Hence, $\vec{a} \times(\vec{b}+\vec{c})+\vec{b} \times(\vec{c}+\vec{a})+\vec{c} \times(\vec{a}+\vec{b})=\overrightarrow{0}$.

---

### Example 23:

If $\vec{a}+\vec{b}+\vec{c}=\overrightarrow{0}$, prove that $(\vec{a} \times \vec{b})=(\vec{b} \times \vec{c})=(\vec{c} \times \vec{a})$.
[CBSE 2001, '04C]

#### Solution:

$\vec{a}+\vec{b}+\vec{c}=\overrightarrow{0} \Rightarrow \vec{a}+\vec{b}=-\vec{c}$

$$
\begin{aligned}
& \Rightarrow(\vec{a}+\vec{b}) \times \vec{b}=(-\vec{c}) \times \vec{b} \\
& \Rightarrow(\vec{a} \times \vec{b})+(\vec{b} \times \vec{b})=(-\vec{c}) \times \vec{b}
\end{aligned}
$$

[by the distributive law]

$$
\begin{align*}
& \Rightarrow(\vec{a} \times \vec{b})+\overrightarrow{0}=(\vec{b} \times \vec{c}) \\
& \Rightarrow \vec{a} \times \vec{b}=\vec{b} \times \vec{c} \tag{i}
\end{align*}
$$

Also, $\vec{a}+\vec{b}+\vec{c}=\overrightarrow{0} \Rightarrow \vec{b}+\vec{c}=-\vec{a}$

$$
\begin{aligned}
& \Rightarrow(\vec{b}+\vec{c}) \times \vec{c}=(-\vec{a}) \times \vec{c} \\
& \Rightarrow(\vec{b} \times \vec{c})+(\vec{c} \times \vec{c})=(-\vec{a}) \times \vec{c}
\end{aligned}
$$

[by the distributive law]

$$
\begin{align*}
& \Rightarrow(\vec{b} \times \vec{c})+\overrightarrow{0}=\vec{c} \times \vec{a} \\
& \quad[\because \vec{c} \times \vec{c}=\overrightarrow{0} \text { and }(-\vec{a}) \times \vec{c}=\vec{c} \times \vec{a}] \\
& \Rightarrow \vec{b} \times \vec{c}=\vec{c} \times \vec{a} \tag{ii}
\end{align*}
$$

From (i) and (ii), we get $\vec{a} \times \vec{b}=\vec{b} \times \vec{c}=\vec{c} \times \vec{a}$.

---

### Example 24:

Prove that the points $A, B, C$ with position vectors $\vec{a}, \vec{b}, \vec{c}$ are collinear if and only if $(\vec{b} \times \vec{c})+(\vec{c} \times \vec{a})+(\vec{a} \times \vec{b})=\overrightarrow{0}$.

#### PROOF

We have

$$
\qquad \overrightarrow{A B}=(\text { position vector of } B)-(\text { position vector of } A)=(\vec{b}-\vec{a})
$$
and $\overrightarrow{B C}=(\text { position vector of } C)-(\text { position vector of } B)=(\vec{c}-\vec{b})$

$$
\begin{aligned}
& \text { Now, } A, B, C \text { are collinear } \\
& \Leftrightarrow \overrightarrow{A B} \text { and } \overrightarrow{B C} \text { are parallel } \Leftrightarrow(\vec{b}-\vec{a}) \times(\vec{c}-\vec{b})=\overrightarrow{0} \\
& \Leftrightarrow(\vec{b}-\vec{a}) \times \vec{c}-(\vec{b}-\vec{a}) \times \vec{b}=\overrightarrow{0} \\
& \Leftrightarrow \vec{b} \times \vec{c}-\vec{a} \times \vec{c}-\vec{b} \times \vec{b}+\vec{a} \times \vec{b}=\overrightarrow{0} \quad \text { [by the distributive law] } \\
& \Leftrightarrow(\vec{b} \times \vec{c})+(\vec{c} \times \vec{a})+(\vec{a} \times \vec{b})=\overrightarrow{0}[\because \vec{b} \times \vec{b}=\overrightarrow{0} \text { and }-\vec{a} \times \vec{c}=\vec{c} \times \vec{a}]
\end{aligned}
$$

Thus, $A, B, C$ are collinear $\Leftrightarrow(\vec{b} \times \vec{c})+(\vec{c} \times \vec{a})+(\vec{a} \times \vec{b})=\overrightarrow{0}$

---

### Example 25:

If $\vec{a} \cdot \vec{b}=0$ and $\vec{a} \times \vec{b}=\overrightarrow{0}$, prove that $\vec{a}=\overrightarrow{0}$ or $\vec{b}=\overrightarrow{0}$.

#### PROOF

Let $\vec{a} \cdot \vec{b}=0$ and $\vec{a} \times \vec{b}=\overrightarrow{0}$. Then,

$$
\begin{aligned}
& \vec{a} \cdot \vec{b}=0 \text { and } \vec{a} \times \vec{b}=\overrightarrow{0} \\
& \Rightarrow \quad(\vec{a}=\overrightarrow{0} \text { or } \vec{b}=\overrightarrow{0} \text { or } \vec{a} \perp \vec{b}) \text { and }(\vec{a}=\overrightarrow{0} \text { or } \vec{b}=\overrightarrow{0} \text { or } \vec{a} \| \vec{b}) \\
& \Rightarrow \quad \vec{a}=\overrightarrow{0} \text { or } \vec{b}=\overrightarrow{0} \\
& \quad[\because \vec{a} \perp \vec{b} \text { and } \vec{a} \| \vec{b} \text { can never hold simultaneously }]
\end{aligned}
$$

Hence, $(\vec{a} \cdot \vec{b}=0$ and $\vec{a} \times \vec{b}=\overrightarrow{0}) \Rightarrow(\vec{a}=\overrightarrow{0}$ or $\vec{b}=\overrightarrow{0})$.

---

### Example 26:

If $\vec{a} \cdot \vec{b}=\vec{a} \cdot \vec{c}, \vec{a} \times \vec{b}=\vec{a} \times \vec{c}$ and $\vec{a} \neq \overrightarrow{0}$ then prove that $\vec{b}=\vec{c}$.

#### PROOF

$\quad \vec{a} \cdot \vec{b}=\vec{a} \cdot \vec{c}$ and $\vec{a} \neq \overrightarrow{0}$

$$
\begin{align*}
& \Rightarrow \vec{a} \cdot \vec{b}-\vec{a} \cdot \vec{c}=0 \text { and } \vec{a} \neq \overrightarrow{0} \Rightarrow \vec{a} \cdot(\vec{b}-\vec{c})=0 \text { and } \vec{a} \neq \overrightarrow{0} \\
& \Rightarrow \vec{b}-\vec{c}=\overrightarrow{0} \text { or } \vec{a} \perp(\vec{b}-\vec{c}) \Rightarrow \vec{b}=\vec{c} \text { or } \vec{a} \perp(\vec{b}-\vec{c}) . \tag{i}
\end{align*}
$$

Again, $\vec{a} \times \vec{b}=\vec{a} \times \vec{c}$ and $\vec{a} \neq \overrightarrow{0}$
$$
\begin{align*}
& \Rightarrow(\vec{a} \times \vec{b})-(\vec{a} \times \vec{c})=\overrightarrow{0} \text { and } \vec{a} \neq \overrightarrow{0} \Rightarrow \vec{a} \times(\vec{b}-\vec{c})=\overrightarrow{0} \text { and } \vec{a} \neq \overrightarrow{0} \\
& \Rightarrow(\vec{b}-\vec{c})=\overrightarrow{0} \text { or } \vec{a} \|(\vec{b}-\vec{c}) \Rightarrow \vec{b}=\vec{c} \text { or } \vec{a} \|(\vec{b}-\vec{c}) . \tag{ii}
\end{align*}
$$

From (i) and (ii), we get $\vec{b}=\vec{c}$
$$
[\because \vec{a} \perp(\vec{b}-\vec{c}) \text { and } \vec{a} \|(\vec{b}-\vec{c}) \text { both cannot hold simultaneously }]
$$

---

## Lagrange's Identity

### Example 27:

Prove that $|\vec{a} \times \vec{b}|^{2}=\left|\begin{array}{ll}\vec{a} \cdot \vec{a} & \vec{a} \cdot \vec{b} \\ \vec{a} \cdot \vec{b} & \vec{b} \cdot \vec{b}\end{array}\right|$.
[CBSE 2002C, '04]

#### Solution:

Let $\theta$ be the angle betwen $\vec{a}$ and $\vec{b}$. Then,

$$
\begin{aligned}
|\vec{a} \times \vec{b}|^{2} & =(\vec{a} \times \vec{b}) \cdot(\vec{a} \times \vec{b})=(a b \sin \theta) \hat{n} \cdot(a b \sin \theta) \hat{n} \\
& =\left(a^{2} b^{2} \sin ^{2} \theta\right)(\hat{n} \cdot \hat{n})=a^{2} b^{2} \sin ^{2} \theta \\
& =a^{2} b^{2}\left(1-\cos ^{2} \theta\right)=a^{2} b^{2}-(a b \cos \theta)^{2} \\
& =(\vec{a} \cdot \vec{a})(\vec{b} \cdot \vec{b})-(\vec{a} \cdot \vec{b})^{2}=\left|\begin{array}{ll}
\vec{a} \cdot \vec{a} & \vec{a} \cdot \vec{b} \\
\vec{a} \cdot \vec{b} & \vec{b} \cdot \vec{b}
\end{array}\right|
\end{aligned}
$$

Hence, $|\vec{a} \times \vec{b}|^{2}=\left|\begin{array}{ll}\vec{a} \cdot \vec{a} & \vec{a} \cdot \vec{b} \\ \vec{a} \cdot \vec{b} & \vec{b} \cdot \vec{b}\end{array}\right|$.

---
