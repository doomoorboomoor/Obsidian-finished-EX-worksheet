## 6. Determinants

### Determinant of a Square Matrix

Corresponding to each square matrix

$$
A=\left[\begin{array}{lllll}
a_{11} & a_{12} & a_{13} & \ldots & a_{1 n} \\
a_{21} & a_{22} & a_{23} & \ldots & a_{2 n} \\
\ldots & \ldots & \ldots & \ldots & \ldots \\
a_{n 1} & a_{n 2} & a_{n 3} & \ldots & a_{n n}
\end{array}\right],
$$

there is associated an expression, called the **determinant of $A$**, denoted by $\operatorname{det} A$, or $|A|$, written as

$$
\operatorname{det} A=|A|=\left|\begin{array}{lllll}
a_{11} & a_{12} & a_{13} & \ldots & a_{1 n} \\
a_{21} & a_{22} & a_{23} & \ldots & a_{2 n} \\
\ldots & \ldots & \ldots & \ldots & \ldots \\
a_{n 1} & a_{n 2} & a_{n 3} & \ldots & a_{n n}
\end{array}\right|
$$

A matrix is an arrangement of numbers and so it has no fixed value, while each determinant has a fixed value.

A determinant having $n$ rows and $n$ columns is known as a **determinant of order $n$**.

The determinants of nonsquare matrices are not defined.

---

#### Value of a Determinant of Order 1

The value of a determinant of a ($1 \times 1$) matrix [$a$] is defined as **$|a|=a$**.

---

#### Value of a Determinant of Order 2

We define

$$
\left|\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right|=\left(a_{11} a_{22}-a_{21} a_{12}\right)
$$

### Example 1

Evaluate:
(i) $\left|\begin{array}{ll}6 & -3 \\ 7 & -2\end{array}\right|$
(ii) $\left|\begin{array}{cc}x^{2}-x+1 & x-1 \\ x+1 & x+1\end{array}\right|$

#### Solution:

(i) $\left|\begin{array}{ll}6 & -3 \\ 7 & -2\end{array}\right|=6(-2)-7(-3)=-12+21=9$.

(ii) $\left|\begin{array}{cc}x^{2}-x+1 & x-1 \\ x+1 & x+1\end{array}\right|=\left(x^{2}-x+1\right)(x+1)-(x+1)(x-1)$
$$
=\left(x^{3}+1\right)-\left(x^{2}-1\right)=\left(x^{3}-x^{2}+2\right) .
$$

---

### Example 2

If $\left|\begin{array}{ll}3 x & 7 \\ -2 & 4\end{array}\right|=\left|\begin{array}{ll}8 & 7 \\ 6 & 4\end{array}\right|$, find the value of $x$.
[CBSE 2014]

#### Solution:

We have $\left|\begin{array}{cc}3 x & 7 \\ -2 & 4\end{array}\right|=\left|\begin{array}{cc}8 & 7 \\ 6 & 4\end{array}\right|$

$$
\begin{aligned}
& \Leftrightarrow \quad(3 x \times 4)-(-2) \times 7=(8 \times 4)-(6 \times 7) \\
& \Leftrightarrow \quad 12 x+14=32-42 \\
& \Leftrightarrow \quad 12 x+14=-10 \\
& \Leftrightarrow \quad 12 x=-24 \quad \Leftrightarrow \quad x=-2 .
\end{aligned}
$$

Hence, $x=-2$.

---

### Example 3

If $\left|\begin{array}{ll}x+1 & x-1 \\ x-3 & x+2\end{array}\right|=\left|\begin{array}{rr}4 & -1 \\ 1 & 3\end{array}\right|$, find the value of $x$.
[CBSE 2013]

#### Solution:

We have $\left|\begin{array}{ll}x+1 & x-1 \\ x-3 & x+2\end{array}\right|=\left|\begin{array}{rr}4 & -1 \\ 1 & 3\end{array}\right|$

$$
\begin{aligned}
& \Leftrightarrow \quad(x+1)(x+2)-(x-3)(x-1)=(4 \times 3)-1 \times(-1) \\
& \Leftrightarrow \quad\left(x^{2}+3 x+2\right)-\left(x^{2}-4 x+3\right)=12+1 \\
& \Leftrightarrow \quad 7 x-1=13 \Leftrightarrow \quad 7 x=14 \Leftrightarrow x=2 .
\end{aligned}
$$

Hence, $x=2$.

---

### Example 4

Show that $\left|\begin{array}{rr}\sin 10^{\circ} & -\cos 10^{\circ} \\ \sin 80^{\circ} & \cos 80^{\circ}\end{array}\right|=1$.

#### Solution:

We have $\left|\begin{array}{rr}\sin 10^{\circ} & -\cos 10^{\circ} \\ \sin 80^{\circ} & \cos 80^{\circ}\end{array}\right|$

$$
\begin{aligned}
& =\left(\sin 10^{\circ}\right)\left(\cos 80^{\circ}\right)-\left(\sin 80^{\circ}\right)\left(-\cos 10^{\circ}\right) \\
& =\left(\sin 10^{\circ} \cos 80^{\circ}+\cos 10^{\circ} \sin 80^{\circ}\right) \\
& =\sin \left(10^{\circ}+80^{\circ}\right) \quad[\because \sin A \cos B+\cos A \sin B=\sin (A+B)] \\
& =\sin 90^{\circ}=1 .
\end{aligned}
$$

---

#### Value of a Determinant of Order 3 or More

For finding the value of a determinant of order 3 or more, we need the following definitions.

##### Minor of $a_{ij}$ in $|A|$

The **minor** of an element $a_{i j}$ in $|A|$ is defined as the value of the determinant obtained by deleting the $i$th row and $j$th column of $|A|$, and it is denoted by $M_{i j}$.

##### Cofactor of $a_{ij}$ in $|A|$

The **cofactor** $C_{i j}$ of an element $a_{i j}$ in $|A|$ is defined as $C_{i j}=(-1)^{i+j} \cdot M_{i j}$.

### Example 1

Find the minors and cofactors of the elements of the determinant

$$
\Delta=\left|\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right| .
$$

Let $M_{i j}$ denote the minor of $a_{i j}$ in $\Delta$.

Now, $a_{11}$ occurs in the 1st row and 1st column. So, in order to find the minor of $a_{11}$, we delete the 1st row and 1st column of $\Delta$. The minor $M_{11}$ of $a_{11}$ is given by $M_{11}=\left|\begin{array}{ll}a_{22} & a_{23} \\ a_{32} & a_{33}\end{array}\right|=\left(a_{22} a_{33}-a_{32} a_{23}\right)$.

Similarly, we have

$$
M_{12}=\left|\begin{array}{ll}
a_{21} & a_{23} \\
a_{31} & a_{33}
\end{array}\right|=\left(a_{21} a_{33}-a_{31} a_{23}\right) ;
$$

$$
M_{13}=\left|\begin{array}{ll}
a_{21} & a_{22} \\
a_{31} & a_{32}
\end{array}\right|=\left(a_{21} a_{32}-a_{31} a_{22}\right) ;
$$

$$
M_{21}=\left|\begin{array}{ll}
a_{12} & a_{13} \\
a_{32} & a_{32}
\end{array}\right|=\left(a_{12} a_{33}-a_{32} a_{13}\right) .
$$

Similarly, we may obtain the minor of each of the remaining elements.

Now, if we denote the cofactor of $a_{i j}$ by $C_{i j}$ then

$$
\left.\begin{array}{l}
C_{11}=(-1)^{1+1} \cdot M_{11}=M_{11}=\left(\begin{array}{lll}
a_{22} & a_{33} & -a_{32}
\end{array} a_{23}\right.
\end{array}\right) ;
$$

$$
\left.\begin{array}{l}
C_{12}=(-1)^{1+2} \cdot M_{12}=-M_{12}=-\left(a_{21} a_{33}-a_{31} a_{23}\right) \\
C_{13}=(-1)^{1+3} \cdot M_{13}=M_{13}=\left(a_{21} a_{32}-a_{31} a_{22}\right.
\end{array}\right) ;
$$

Similarly, the cofactor of each of the remaining elements of $\Delta$ can be determined.

---

### Example 2

Find the minor and cofactor of each element of $\Delta=\left|\begin{array}{rrr}1 & -3 & 2 \\ 4 & -1 & 2 \\ 3 & 5 & 2\end{array}\right|$.

#### Solution:

The minors of the elements of $\Delta$ are given by

$$
\begin{aligned}
& M_{11}=\left|\begin{array}{rr}
-1 & 2 \\
5 & 2
\end{array}\right|=-12 ; M_{12}=\left|\begin{array}{ll}
4 & 2 \\
3 & 2
\end{array}\right|=2 ; M_{13}=\left|\begin{array}{rr}
4 & -1 \\
3 & 5
\end{array}\right|=23 ; \\
& M_{21}=\left|\begin{array}{rr}
-3 & 2 \\
5 & 2
\end{array}\right|=-16 ; M_{22}=\left|\begin{array}{ll}
1 & 2 \\
3 & 2
\end{array}\right|=-4 ; M_{23}=\left|\begin{array}{rr}
1 & -3 \\
3 & 5
\end{array}\right|=14 ; \\
& M_{31}=\left|\begin{array}{rr}
-3 & 2 \\
-1 & 2
\end{array}\right|=-4 ; M_{32}=\left|\begin{array}{ll}
1 & 2 \\
4 & 2
\end{array}\right|=-6 ; M_{33}=\left|\begin{array}{rr}
1 & -3 \\
4 & -1
\end{array}\right|=11 .
\end{aligned}
$$

So, the cofactors of the corresponding elements of $\Delta$ are

$$
C_{11}=(-1)^{1+1} \cdot M_{11}=M_{11}=-12 ; C_{12}=(-1)^{1+2} \cdot M_{12}=-M_{12}=-2 ;
$$

$$
\begin{aligned}
& C_{13}=(-1)^{1+3} \cdot M_{13}=M_{13}=23 ; C_{21}=(-1)^{2+1} \cdot M_{21}=-M_{21}=16 ; \\
& C_{22}=(-1)^{2+2} \cdot M_{22}=M_{22}=-4 ; C_{23}=(-1)^{2+3} \cdot M_{23}=-M_{23}=-14 ; \\
& C_{31}=(-1)^{3+1} \cdot M_{31}=M_{31}=-4 ; C_{32}=(-1)^{3+2} \cdot M_{32}=-M_{32}=6 ; \\
& C_{33}=(-1)^{3+3} \cdot M_{33}=M_{33}=11 .
\end{aligned}
$$

---

### Value of a Determinant

The value of a determinant is the **sum of the products of elements of a row (or a column) with their corresponding cofactors**.

We may expand a determinant by any arbitrarily chosen row or column.

#### Expansion of a Determinant

Expanding the given determinant by 1st row, we have

$$
\begin{aligned}
\left|\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right| & =a_{11} \cdot \text { (its cofactor) }+a_{12} \cdot \text { (its cofactor) }+a_{13} \cdot \text { (its cofactor) } \\
& =a_{11} C_{11}+a_{12} C_{12}+a_{13} C_{13} \\
& =a_{11} M_{11}-a_{12} M_{12}+a_{13} M_{13} \\
& \left.\left.=a_{11} \cdot\left|\begin{array}{ll}
a_{22} & a_{23} \\
a_{32} & a_{33}
\end{array}\right|-a_{12} \cdot\left|\begin{array}{ll}
a_{21} & a_{23} \\
a_{31} & a_{33}
\end{array}\right|+a_{13} \cdot\left|\begin{array}{ll}
a_{21} & a_{22} \\
a_{31} & a_{32}
\end{array}\right| \quad \begin{array}{r}
\because C_{12}=-M_{12}
\end{array}\right] C_{13}=M_{13}\right] \\
& =a_{11} \cdot\left(a_{22} a_{33}-a_{32} a_{23}\right)-a_{12} \cdot\left(a_{21} a_{33}-a_{31} a_{23}\right) \\
& +a_{13} \cdot\left(a_{21} a_{32}-a_{31} a_{22}\right)
\end{aligned}
$$

We may expand it by any row or column.

**Remark 1:** If we expand a determinant by any row or column using minors, we keep in view the following symbols for a determinant of order three:

$$
\left|\begin{array}{ccc}
+ & - & + \\
- & + & - \\
+ & - & +
\end{array}\right|
$$

**Remark 2:** If a row or a column of a determinant consists of all zeros, the value of the determinant is zero.

---

### Example 1

Evaluate

$$
\Delta=\left|\begin{array}{rrr}
3 & 4 & 5 \\
-6 & 2 & -3 \\
8 & 1 & 7
\end{array}\right|
$$

#### Solution:

Expanding the given determinant by 1st row, we get

$$
\begin{aligned}
\Delta & =3 \cdot\left|\begin{array}{rr}
2 & -3 \\
1 & 7
\end{array}\right|-4 \cdot\left|\begin{array}{rr}
-6 & -3 \\
8 & 7
\end{array}\right|+5 \cdot\left|\begin{array}{rr}
-6 & 2 \\
8 & 1
\end{array}\right| \\
& =3 \cdot(14+3)-4 \cdot(-42+24)+5 \cdot(-6-16)=13 .
\end{aligned}
$$

---

### Example 2

Expand the determinant $\Delta=\left|\begin{array}{lll}a & h & g \\ h & b & f \\ g & f & c\end{array}\right|$.

#### Solution:

Expanding by 1st column, we get

$$
\begin{aligned}
\Delta & =a \cdot\left|\begin{array}{ll}
b & f \\
f & c
\end{array}\right|-h \cdot\left|\begin{array}{ll}
h & g \\
f & c
\end{array}\right|+g \cdot\left|\begin{array}{ll}
h & g \\
b & f
\end{array}\right| \\
& =a\left(b c-f^{2}\right)-h \cdot(c h-f g)+g \cdot(f h-b g) \\
& =a b c-a f^{2}-c h^{2}+f g h+f g h-b g^{2} \\
& =\left(a b c+2 f g h-a f^{2}-b g^{2}-c h^{2}\right) .
\end{aligned}
$$

---

### Properties of Determinants

The properties of a determinant serve the purpose of a useful tool for finding its value. We will mention these properties and verify them for a third-order determinant.

#### Theorem 1

**The value of a determinant remains unchanged if its rows and columns are interchanged.**

##### Proof

Let $\Delta=\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|$ and let $\Delta^{\prime}$ be the determinant obtained by interchanging the rows and columns of $\Delta$.
Then, $\Delta^{\prime}=\left|\begin{array}{lll}a_{1} & a_{2} & a_{3} \\ b_{1} & b_{2} & b_{3} \\ c_{1} & c_{2} & c_{3}\end{array}\right|$

$$
=a_{1} \cdot\left|\begin{array}{ll}
b_{2} & b_{3} \\
c_{2} & c_{3}
\end{array}\right|-b_{1} \cdot\left|\begin{array}{ll}
a_{2} & a_{3} \\
c_{2} & c_{3}
\end{array}\right|+c_{1} \cdot\left|\begin{array}{ll}
a_{2} & a_{3} \\
b_{2} & b_{3}
\end{array}\right|
$$

[expanded by 1st column]

$$
\begin{aligned}
& =a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)-b_{1}\left(a_{2} c_{3}-c_{2} a_{3}\right)+c_{1}\left(a_{2} b_{3}-a_{3} b_{2}\right) \\
& =\Delta \quad[\text { expanded by } 1 \text { st row }] .
\end{aligned}
$$

##### Corollary

If $A$ is a square matrix then $\left|A^{\prime}\right|=|A|$.

---

#### Theorem 2

**If two rows or columns of a determinant are interchanged then the determinant retains its absolute value but its sign is changed.**

##### Proof

Let $\Delta=\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|$ and let $\Delta^{\prime}$ be the determinant obtained by interchanging any two rows, say 1st and 3rd rows, of $\Delta$. Then,

$$
\begin{aligned}
\Delta^{\prime} & =\left|\begin{array}{lll}
a_{3} & b_{3} & c_{3} \\
a_{2} & b_{2} & c_{2} \\
a_{1} & b_{1} & c_{1}
\end{array}\right| \\
& =a_{3} \cdot\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{1} & c_{1}
\end{array}\right|-a_{2} \cdot\left|\begin{array}{ll}
b_{3} & c_{3} \\
b_{1} & c_{1}
\end{array}\right|+a_{1} \cdot\left|\begin{array}{ll}
b_{3} & c_{3} \\
b_{2} & c_{2}
\end{array}\right|
\end{aligned}
$$

[expanded by 1st column]

$$
\begin{aligned}
& =a_{3}\left(b_{2} c_{1}-b_{1} c_{2}\right)-a_{2}\left(b_{3} c_{1}-b_{1} c_{3}\right)+a_{1}\left(b_{3} c_{2}-b_{2} c_{3}\right) \\
& =-a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)+a_{2}\left(b_{1} c_{3}-b_{3} c_{1}\right)-a_{3}\left(b_{1} c_{2}-b_{2} c_{1}\right) \\
& =-\left[a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)-a_{2}\left(b_{1} c_{3}-b_{3} c_{1}\right)+a_{3}\left(b_{1} c_{2}-b_{2} c_{1}\right)\right] \\
& =-\Delta \quad[\text { expanded by } 1 \text { st column }] .
\end{aligned}
$$

---

#### Theorem 3

**If any two rows or columns of a determinant are identical then its value is zero.**

##### Proof

If we interchange the identical rows of the given determinant $\Delta$ then clearly there is no change in $\Delta$. But, interchanging any two rows of a determinant changes its sign.

$$
\therefore \quad \Delta=-\Delta \quad \Leftrightarrow \quad 2 \Delta=0, \text { i.e., } \Delta=0 .
$$

---

#### Theorem 4

**If each element of a row or a column of a determinant is multiplied by a constant $k$ then the value of the new determinant is $k$ times the value of the original determinant.**

##### Proof

Let $\Delta=\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|$ and let $\Delta^{\prime}$ be the determinant obtained by multiplying each element of a row, say the second row of $\Delta$, by $k$. Then,

$$
\begin{aligned}
\Delta^{\prime} & =\left|\begin{array}{ccc}
a_{1} & b_{1} & c_{1} \\
k a_{2} & k b_{2} & k c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| \\
& =a_{1} \cdot\left|\begin{array}{cc}
k b_{2} & k c_{2} \\
b_{3} & c_{3}
\end{array}\right|-k a_{2} \cdot\left|\begin{array}{cc}
b_{1} & c_{1} \\
b_{3} & c_{3}
\end{array}\right|+a_{3} \cdot\left|\begin{array}{cc}
b_{1} & c_{1} \\
k b_{2} & k c_{2}
\end{array}\right| \\
& =a_{1}\left(k b_{2} c_{3}-k b_{3} c_{2}\right)-k a_{2}\left(b_{1} c_{3}-b_{3} c_{1}\right)+a_{3}\left(k b_{1} c_{2}-k b_{2} c_{1}\right) \\
& =k\left[a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)-a_{2}\left(b_{1} c_{3}-b_{3} c_{1}\right)+a_{3}\left(b_{1} c_{2}-b_{2} c_{1}\right)\right]=k \Delta .
\end{aligned}
$$

##### Corollary

For a square matrix $A$ of order $n$, $|k A|=k^{n} \cdot|A|$.

---

#### Theorem 5

**If any two rows or columns of a determinant are proportional then its value is zero.**

##### Proof

Let $\Delta=\left|\begin{array}{ccc}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ k a_{1} & k b_{1} & k c_{1}\end{array}\right|$

$$
\begin{aligned}
& =k\left|\begin{array}{ccc}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{1} & b_{1} & c_{1}
\end{array}\right| \\
& =k \times 0=0 \quad[\because 1 \text { st and 3rd rows are identical }]
\end{aligned}
$$

---

#### Theorem 6

**If each element of a row (or column) of a determinant is expressed as a sum of two or more terms then the determinant can be expressed as the sum of two or more determinants.**

##### Proof

Let $\Delta=\left|\begin{array}{ccc}a_{1}+\alpha_{1} & b_{1}+\beta_{1} & c_{1}+\gamma_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|$.
Then, on expanding $\Delta$ by first row, we get

$$
\begin{aligned}
\Delta= & \left(a_{1}+\alpha_{1}\right)\left(b_{2} c_{3}-b_{3} c_{2}\right)-\left(b_{1}+\beta_{1}\right)\left(a_{2} c_{3}-a_{3} c_{2}\right)+\left(c_{1}+\gamma_{1}\right)\left(a_{2} b_{3}-a_{3} b_{2}\right) \\
= & {\left[a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)-b_{1}\left(a_{2} c_{3}-a_{3} c_{2}\right)+c_{1}\left(a_{2} b_{3}-a_{3} b_{2}\right)\right] } \\
& \quad+\left[\alpha_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)-\beta_{1}\left(a_{2} c_{3}-a_{3} c_{2}\right)+\gamma_{1}\left(a_{2} b_{3}-a_{3} b_{2}\right)\right] \\
= & \left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|+\left|\begin{array}{lll}
\alpha_{1} & \beta_{1} & \gamma_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| .
\end{aligned}
$$

---

#### Theorem 7

**If to any row or column of a determinant, a multiple of another row or column is added, the value of the determinant remains the same.**

##### Proof

Let $\Delta=\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|$.
Let $\quad \Delta^{\prime}=\left|\begin{array}{ccc}a_{1}+k a_{3} & b_{1}+k b_{3} & c_{1}+k c_{3} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|$.
Then, $\quad \Delta^{\prime}=\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|+\left|\begin{array}{ccc}k a_{3} & k b_{3} & k c_{3} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|$
$$
\begin{aligned}
& =\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|+k\left|\begin{array}{lll}
a_{3} & b_{3} & c_{3} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| \\
& =\Delta+k \times 0 \quad[\because 2 \text { 2nd det. is 0, its 1st and 3rd rows are proportional }] \\
& =\Delta .
\end{aligned}
$$

---

#### Theorem 8

**The sum of the products of the elements of any row (or column) of a determinant with cofactors of the corresponding elements of any other row (or column) is zero.**

##### Proof

Let $\Delta=\left|\begin{array}{lll}a_{11} & a_{12} & a_{13} \\ a_{21} & a_{22} & a_{23} \\ a_{31} & a_{32} & a_{33}\end{array}\right|$.
Let us take the sum of the products of elements of first row with the cofactors of the corresponding elements of second row.

$$
\begin{aligned}
& a_{11} A_{21}+a_{12} A_{22}+a_{13} A_{23} \\
& \quad \begin{aligned}
= & a_{11} \cdot(-1)^{2+1} \cdot\left|\begin{array}{ll}
a_{12} & a_{13} \\
a_{32} & a_{33}
\end{array}\right|+a_{12} \cdot(-1)^{2+2} \cdot\left|\begin{array}{ll}
a_{11} & a_{13} \\
a_{31} & a_{33}
\end{array}\right| \\
& \quad+a_{13} \cdot(-1)^{2+3} \cdot\left|\begin{array}{ll}
a_{11} & a_{12} \\
a_{31} & a_{32}
\end{array}\right| \\
& \quad=-a_{11}\left(a_{12} a_{33}-a_{32} a_{13}\right)+a_{12}\left(a_{11} a_{33}-a_{31} a_{13}\right)-a_{13}\left(a_{11} a_{32}-a_{31} a_{12}\right) \\
& \quad=0
\end{aligned}
\end{aligned}
$$

---

### To Find the Value of a Determinant

The main theme behind the simplification of a determinant lies in obtaining the maximum possible number of zeros in a row (or a column) by using the above properties and then to expand the determinant by that row (or column). We denote the 1st, 2nd, 3rd rows of a determinant by $R_{1}, R_{2}, R_{3}$ respectively and the 1st, 2nd, 3rd columns by $C_{1}, C_{2}, C_{3}$ respectively. We shall also express the
(i) interchange of the $i$th and $j$th rows by $R_{i} \leftrightarrow R_{j}$;
(ii) addition of $k$ times the elements of the $j$th row with the corresponding elements of the $i$th row by $R_{i} \rightarrow R_{i}+k R_{j}$.
We use similar notations for operations on columns, replacing $R$ by $C$.

### Examples

| Operation | Notation |
| :--- | :--- |
| (i) Interchange of 2nd and 3rd rows. | (i) $R_{2} \leftrightarrow R_{3}$ |
| (ii) Interchange of 1st and 3rd columns | (ii) $C_{1} \leftrightarrow C_{3}$ |
| (iii) Multiplying each element of 2nd row by (-5). | (iii) $R_{2} \rightarrow(-5) R_{2}$ |
| (iv) Multiplying each element of 1st column by $\frac{1}{3}$. | (iv) $C_{1} \rightarrow \frac{1}{3} C_{1}$ |
| (v) Multiplying each element of 3rd row by 6 and adding it to the corresponding element of 2nd row. | (v) $R_{2} \rightarrow R_{2}+6 R_{3}$ |
| (vi) Multiplying each element of 2nd column by (-3) and adding it to the corresponding element of 1st column. | (vi) $\mathrm{C}_{1} \rightarrow \mathrm{C}_{1}+(-3) \mathrm{C}_{2}$ |

## SOLVED EXAMPLES (Short-Answer Questions)

### Example 1

Evaluate $\left|\begin{array}{ccc}2 & 7 & 65 \\ 3 & 8 & 75 \\ 5 & 9 & 86\end{array}\right|$. [CBSE 2014C]

#### Solution:

Given determinant

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
2 & 7 & 65 \\
3 & 8 & 75 \\
5 & 9 & 86
\end{array}\right| \\
& =\left|\begin{array}{ccc}
2 & 7 & 2 \\
3 & 8 & 3 \\
5 & 9 & 5
\end{array}\right| \\
& =0
\end{aligned} \quad\left[\text { applying } C_{3} \rightarrow C_{3}-9 C_{2}\right]
$$

---

### Example 2

Prove that $\left|\begin{array}{lll}a-b & b-c & c-a \\ b-c & c-a & a-b \\ c-a & a-b & b-c\end{array}\right|=0$. [CBSE 2009]

#### Solution:

Given determinant

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
a-b & b-c & c-a \\
b-c & c-a & a-b \\
c-a & a-b & b-c
\end{array}\right| \\
& =\left|\begin{array}{ccc}
0 & b-c & c-a \\
0 & c-a & a-b \\
0 & a-b & b-c
\end{array}\right| \quad\left[\text { applying } C_{1} \rightarrow C_{1}+C_{2}+C_{3}\right] \\
& =0 \quad\left[\because C_{1} \text { consists of all zeros }\right] .
\end{aligned}
$$

---

### Example 3

Prove that $\left|\begin{array}{lll}1 & a & b+c \\ 1 & b & c+a \\ 1 & c & a+b\end{array}\right|=0$.

#### Solution:

The given determinant

$$
\begin{aligned}
& =\left|\begin{array}{lll}
1 & a & b+c \\
1 & b & c+a \\
1 & c & a+b
\end{array}\right| \\
& =\left|\begin{array}{lll}
1 & a & a+b+c \\
1 & b & a+b+c \\
1 & c & a+b+c
\end{array}\right| \quad\left[\text { applying } C_{3} \rightarrow C_{3}+C_{2}\right]
\end{aligned}
$$

$$
\begin{aligned}
& \left.=(a+b+c) \cdot\left|\begin{array}{ccc}
1 & a & 1 \\
1 & b & 1 \\
1 & c & 1
\end{array}\right| \text { [taking }(a+b+c) \text { common from } C_{3}\right] \\
& =(a+b+c) \times 0=0 \quad\left[\because \quad C_{1} \text { and } C_{3} \text { are identical }\right]
\end{aligned}
$$

---

### Example 4

Prove that $\left|\begin{array}{lll}1 & b c & a(b+c) \\ 1 & c a & b(c+a) \\ 1 & a b & c(a+b)\end{array}\right|=0$.

#### Solution:

The given determinant

$$
\begin{aligned}
& =\left|\begin{array}{lll}
1 & b c & a(b+c) \\
1 & c a & b(c+a) \\
1 & a b & c(a+b)
\end{array}\right| \\
& =\left|\begin{array}{lll}
1 & b c & a b+b c+c a \\
1 & c a & a b+b c+c a \\
1 & a b & a b+b c+c a
\end{array}\right| \quad\left[\text { applying } C_{3} \rightarrow C_{3}+C_{2}\right] \\
& =(a b+b c+c a) \cdot\left|\begin{array}{lll}
1 & b c & 1 \\
1 & c a & 1 \\
1 & a b & 1
\end{array}\right| \quad\left[\text { taking }(a b+b c+c a) \text { common from } C_{3}\right] \\
& =(a b+b c+c a) \times 0=0 \quad\left[\because \quad C_{1} \text { and } C_{3} \text { are identical }\right]
\end{aligned}
$$

---

### Example 5

Without expanding prove that $\left|\begin{array}{ccc}x+y & y+z & z+x \\ z & x & y \\ 1 & 1 & 1\end{array}\right|=0$.

#### Solution:

The given determinant

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
x+y & y+z & z+x \\
z & x & y \\
1 & 1 & 1
\end{array}\right| \\
& =\left|\begin{array}{ccc}
x+y+z & x+y+z & x+y+z \\
z & x & y \\
1 & 1 & 1
\end{array}\right| \quad\left[R_{1} \rightarrow R_{1}+R_{2}\right] \\
& =(x+y+z) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
z & x & y \\
1 & 1 & 1
\end{array}\right| \quad\left[\text { taking }(x+y+z) \text { common from } R_{1}\right] \\
& =(x+y+z) \times 0=0 \quad\left[\because \quad R_{1} \text { and } R_{3} \text { are identical }\right] .
\end{aligned}
$$

---

### Example 6

If $\omega$ is a complex cube root of unity, prove that

$$
\left|\begin{array}{ccc}
1 & \omega & \omega^{2} \\
\omega & \omega^{2} & 1 \\
\omega^{2} & 1 & \omega
\end{array}\right|=0 .
$$

#### Solution:

The given determinant

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
1 & \omega & \omega^{2} \\
\omega & \omega^{2} & 1 \\
\omega^{2} & 1 & w
\end{array}\right| \\
& =\left|\begin{array}{ccc}
1+\omega+\omega^{2} & 1+\omega+\omega^{2} & 1+\omega+\omega^{2} \\
\omega & \omega^{2} & 1 \\
\omega^{2} & 1 & \omega
\end{array}\right|\left[R_{1} \rightarrow R_{1}+R_{2}+R_{3}\right] \\
& =\left|\begin{array}{ccc}
0 & 0 & 0 \\
\omega & \omega^{2} & 1 \\
\omega^{2} & 1 & \omega
\end{array}\right|\left[\because \quad 1+\omega+\omega^{2}=0\right] \\
& =0
\end{aligned}
$$

---

### Example 7

Show that $\left|\begin{array}{ccc}2 & 3 & 4 \\ 5 & 6 & 8 \\ 6 x & 9 x & 12 x\end{array}\right|=0$. [CBSE 2009]

#### Solution:

The given determinant

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
2 & 3 & 4 \\
5 & 6 & 8 \\
6 x & 9 x & 12 x
\end{array}\right| \\
& =(3 x)\left|\begin{array}{ccc}
2 & 3 & 4 \\
5 & 6 & 8 \\
2 & 3 & 4
\end{array}\right| \\
& =(3 x) \times 0=0 \quad\left[\because R_{1} \text { and } R_{3} \text { are identical }\right] .
\end{aligned}
$$

---

### Example 8

Prove that $\left|\begin{array}{ccc}1 & 1 & 1 \\ 1 & 1+x & 1 \\ 1 & 1 & 1+y\end{array}\right|=x y$.

#### Solution:

The given determinant

$$
=\left|\begin{array}{ccc}
1 & 1 & 1 \\
1 & 1+x & 1 \\
1 & 1 & 1+y
\end{array}\right|
$$

$$
\begin{aligned}
& =\left|\begin{array}{lll}
1 & 0 & 0 \\
1 & x & 0 \\
1 & 0 & y
\end{array}\right| \quad\left[\text { applying } C_{2} \rightarrow C_{2}-C_{1} \text { and } C_{3} \rightarrow C_{3}-C_{1}\right] \\
& =1 \cdot\left|\begin{array}{ll}
x & 0 \\
0 & y
\end{array}\right|=x y \quad\left[\text { expanding by } R_{1}\right] .
\end{aligned}
$$

---

### Example 9

Prove that $\left|\begin{array}{ccc}x & \sin \theta & \cos \theta \\ -\sin \theta & -x & 1 \\ \cos \theta & 1 & x\end{array}\right|$ is independent of $\theta$.

#### Solution:

Let the given determinant be $\Delta$. Then, expanding by first row, we get:

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
x & \sin \theta & \cos \theta \\
-\sin \theta & -x & 1 \\
\cos \theta & 1 & x
\end{array}\right| \\
& =x\left(-x^{2}-1\right)-\sin \theta(-x \sin \theta-\cos \theta)+\cos \theta(-\sin \theta+x \cos \theta) \\
& =-x^{3}-x+x\left(\sin ^{2} \theta+\cos ^{2} \theta\right)=-x^{3}-x+x=-x^{3},
\end{aligned}
$$

which is independent of $\theta$.

---

### Example 10

Prove that $\left|\begin{array}{ccc}0 & \sin \alpha & -\cos \alpha \\ -\sin \alpha & 0 & \sin \beta \\ \cos \alpha & -\sin \beta & 0\end{array}\right|=0$.

#### Solution:

Let the given determinant be $\Delta$. Then, expanding by first row, we get:

$$
\begin{aligned}
\Delta & =(-\sin \alpha) \cdot\left|\begin{array}{cc}
-\sin \alpha & \sin \beta \\
\cos \alpha & 0
\end{array}\right|+(-\cos \alpha) \cdot\left|\begin{array}{cc}
-\sin \alpha & 0 \\
\cos \alpha & -\sin \beta
\end{array}\right| \\
& =(-\sin \alpha) \cdot\{0-\cos \alpha \sin \beta\}+(-\cos \alpha) \cdot(\sin \alpha \sin \beta-0) \\
& =(-\sin \alpha)(-\cos \alpha \sin \beta)+(-\cos \alpha)(\sin \alpha \sin \beta) \\
& =(\sin \alpha \cos \alpha \sin \beta-\sin \alpha(\cos \alpha \sin \beta)=0 .
\end{aligned}
$$

Hence, $\Delta=0$.

---

### Example 11

Prove that $\left|\begin{array}{ccc}a & b & c \\ a+2 x & b+2 y & c+2 z \\ x & y & z\end{array}\right|=0$.

#### Solution:

Let the given determinant be $\Delta$. Then, applying $R_{2} \rightarrow R_{2}-R_{1}$, we get:

$$
\Delta=\left|\begin{array}{ccc}
a & b & c \\
2 x & 2 y & 2 z \\
x & y & z
\end{array}\right|=2\left|\begin{array}{lll}
a & b & c \\
x & y & z \\
x & y & z
\end{array}\right|=0 \quad\left[\because \quad R_{2} \text { and } R_{3} \text { are identical }\right] .
$$

---

### Example 12

Without expanding the determinant, prove that

$$
\left|\begin{array}{ccc}
a+b & 2 a+b & 3 a+b \\
2 a+b & 3 a+b & 4 a+b \\
4 a+b & 5 a+b & 6 a+b
\end{array}\right|=0 .
$$

#### Solution:

Let the given determinant be $\Delta$. Then, applying $C_{3} \rightarrow C_{3}-C_{2}$, we get:

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a+b & 2 a+b & a \\
2 a+b & 3 a+b & a \\
4 a+b & 5 a+b & a
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+b & a & a \\
2 a+b & a & a \\
4 a+b & a & a
\end{array}\right| \\
& =0
\end{aligned} \quad\left[\text { applying } C_{2} \rightarrow C_{2}-C_{1}\right]
$$

Hence, $\Delta=0$.

---

## ILLUSTRATIVE EXAMPLES [Long-Answer Questions]

### Example 1

Evaluate $\left|\begin{array}{lll}265 & 240 & 219 \\ 240 & 225 & 198 \\ 219 & 198 & 181\end{array}\right|$.

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
265 & 240 & 219 \\
240 & 225 & 198 \\
219 & 198 & 181
\end{array}\right| \\
& =\left|\begin{array}{rrr}
46 & 21 & 219 \\
42 & 27 & 198 \\
38 & 17 & 181
\end{array}\right| \quad\left[C_{1} \rightarrow (C_{1}-C_{3}) \text { and } C_{2} \rightarrow (C_{2}-C_{3})\right] \\
& =\left|\begin{array}{rrr}
4 & 21 & 9 \\
-12 & 27 & -72 \\
4 & 17 & 11
\end{array}\right| \quad\left[C_{1} \rightarrow (C_{1}-2 C_{2}) \text { and } C_{3} \rightarrow (C_{3}-10 C_{2})\right] \\
& =\left|\begin{array}{rrr}
0 & 4 & -2 \\
0 & 78 & -39 \\
4 & 17 & 11
\end{array}\right| \\
& =2(39)\left|\begin{array}{rrr}
0 & 2 & -1 \\
0 & 2 & -1 \\
4 & 17 & 11
\end{array}\right|
\end{aligned}
$$

[taking 2 common from $R_{1}$ and 39 common from $R_{2}$ ] $=(78 \times 0)=0 \quad\left[\because \quad R_{1}\right.$ and $R_{2}$ are identical $]$.

---

### Example 2

Without expanding, prove that

$$
\left|\begin{array}{lll}
\sin \alpha & \cos \alpha & \cos (\alpha+\delta) \\
\sin \beta & \cos \beta & \cos (\beta+\delta) \\
\sin \gamma & \cos \gamma & \cos (\gamma+\delta)
\end{array}\right|=0 .
$$
[CBSE 2007]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
\sin \alpha & \cos \alpha & \cos \alpha \cos \delta-\sin \alpha \sin \delta \\
\sin \beta & \cos \beta & \cos \beta \cos \delta-\sin \beta \sin \delta \\
\sin \gamma & \cos \gamma & \cos \gamma \cos \delta-\sin \gamma \sin \delta
\end{array}\right| \\
& =\left|\begin{array}{ccc}
\sin \alpha & \cos \alpha & 0 \\
\sin \beta & \cos \beta & 0 \\
\sin \gamma & \cos \gamma & 0
\end{array}\right| \quad\left[C_{3} \rightarrow C_{3}+(\sin \delta) C_{1}-(\cos \delta) C_{2}\right] \\
& =0 \quad\left[\text { expanded by } C_{3}\right] .
\end{aligned}
$$

Hence, $\Delta=0$.

---

### Example 3

Prove that $\left|\begin{array}{ccc}a & a+b & a+b+c \\ 2 a & 3 a+2 b & 4 a+3 b+2 c \\ 3 a & 6 a+3 b & 10 a+6 b+3 c\end{array}\right|=a^{3}$. [CBSE 2012]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a & a+b & a+b+c \\
2 a & 3 a+2 b & 4 a+3 b+2 c \\
3 a & 6 a+3 b & 10 a+6 b+3 c
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a & a+b & a+b+c \\
0 & a & 2 a+b \\
0 & 3 a & 7 a+3 b
\end{array}\right| \quad\left[R_{2} \rightarrow R_{2}-2 R_{1} \text { and } R_{3} \rightarrow R_{3}-3 R_{1}\right] \\
& =\left|\begin{array}{ccc}
a & a+b & a+b+c \\
0 & a & 2 a+b \\
0 & 0 & a
\end{array}\right| \quad\left[R_{3} \rightarrow R_{3}-3 R_{2}\right] \\
& =a \cdot\left|\begin{array}{cc}
a & 2 a+b \\
0 & a
\end{array}\right| \quad\left[\text { expanding along } C_{1}\right] \\
& =a \cdot\left(a^{2}-0\right)=a^{3} .
\end{aligned}
$$

Hence, $\Delta=a^{3}$.

---

### Example 4

Prove that $\left|\begin{array}{rrr}-a^{2} & a b & a c \\ a b & -b^{2} & b c \\ a c & b c & -c^{2}\end{array}\right|=4 a^{2} b^{2} c^{2}$. [CBSE 2011, '11C]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{rrr}
-a^{2} & a b & a c \\
a b & -b^{2} & b c \\
a c & b c & -c^{2}
\end{array}\right| \\
& =(a b c) \cdot\left|\begin{array}{rrr}
-a & a & a \\
b & -b & b \\
c & c & -c
\end{array}\right| \quad\left[\begin{array}{l}
\text { taking out } a, b, c \text { common from } \\
C_{1}, C_{2}, C_{3} \text { respectively }
\end{array}\right] \\
& =\left|\begin{array}{rrr}
-a & 0 & 0 \\
b & 0 & 2 b \\
c & 2 c & 0
\end{array}\right| \quad\left[C_{2} \rightarrow (C_{2}+C_{1}) \text { and } C_{3} \rightarrow (C_{3}+C_{1})\right] \\
& =(a b c) \cdot(-a)\left|\begin{array}{rr}
0 & 2 b \\
2 c & 0
\end{array}\right|=(a b c)(-a)(-4 b c) \\
& =4 a^{2} b^{2} c^{2}
\end{aligned}
$$

---

### Example 5

Using properties of determinants, prove that

$$
\left|\begin{array}{ccc}
0 & a b^{2} & a c^{2} \\
a^{2} b & 0 & b c^{2} \\
a^{2} c & c b^{2} & 0
\end{array}\right|=2 a^{3} b^{3} c^{3} .
$$

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
0 & a b^{2} & a c^{2} \\
a^{2} b & 0 & b c^{2} \\
a^{2} c & c b^{2} & 0
\end{array}\right| \\
& =\left(a^{2} b^{2} c^{2}\right) \cdot\left|\begin{array}{ccc}
0 & a & a \\
b & 0 & b \\
c & c & 0
\end{array}\right| \quad\left[\begin{array}{l}
\text { taking } a^{2}, b^{2}, c^{2} \text { common from } \\
C_{1}, C_{2} \text { and } C_{3} \text { respectively }
\end{array}\right] \\
& =\left(a^{3} b^{3} c^{3}\right) \cdot\left|\begin{array}{ccc}
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0
\end{array}\right| \quad\left[\begin{array}{l}
\text { taking } a, b, c \text { common from } \\
R_{1}, R_{2} \text { and } R_{3} \text { respectively }
\end{array}\right] \\
& =\left(a^{3} b^{3} c^{3}\right) \cdot\left|\begin{array}{ccc}
0 & 1 & 1 \\
1 & 0 & 1 \\
0 & 1 & -1
\end{array}\right| \quad\left[R_{3} \rightarrow R_{3}-R_{2}\right] \\
& =\left(a^{3} b^{3} c^{3}\right) \cdot(-1) \cdot\left|\begin{array}{rr}
1 & 1 \\
1 & -1
\end{array}\right| \quad\left[\text { expanded by } C_{1}\right] \\
& =-\left(a^{3} b^{3} c^{3}\right)(-1-1)=2 a^{3} b^{3} c^{3} .
\end{aligned}
$$

Hence, $\Delta=2 a^{3} b^{3} c^{3}$.

---

### Example 6

Using properties of determinants, prove that

$$
\left|\begin{array}{ccc}
x+y & x & x \\
5 x+4 y & 4 x & 2 x \\
10 x+8 y & 8 x & 3 x
\end{array}\right|=x^{3} .
$$
[CBSE 2009, '14]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
x+y & x & x \\
5 x+4 y & 4 x & 2 x \\
10 x+8 y & 8 x & 3 x
\end{array}\right| \\
& =\left|\begin{array}{ccc}
x+y & x & x \\
3 x+2 y & 2 x & 0 \\
7 x+5 y & 5 x & 0
\end{array}\right| \quad\left[R_{2} \rightarrow (R_{2}-2 R_{1}) \text { and } R_{3} \rightarrow (R_{3}-3 R_{1})\right] \\
& =x \cdot\left|\begin{array}{ll}
3 x+2 y & 2 x \\
7 x+5 y & 5 x
\end{array}\right| \quad\left[\text { expanded by } C_{3}\right] \\
& =x^{2} \cdot\left|\begin{array}{ll}
3 x+2 y & 2 \\
7 x+5 y & 5
\end{array}\right| \quad\left[\text { taking } x \text { common from } C_{2}\right] \\
& =x^{2} \cdot[5(3 x+2 y)-2(7 x+5 y)]=\left(x^{2} \cdot x\right)=x^{3} .
\end{aligned}
$$

Hence, $\Delta=x^{3}$.

---

### Example 7

Prove that $\left|\begin{array}{lll}1 & a & a^{2} \\ 1 & b & b^{2} \\ 1 & c & c^{2}\end{array}\right|=(a-b)(b-c)(c-a)$.

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
1 & a & a^{2} \\
1 & b & b^{2} \\
1 & c & c^{2}
\end{array}\right| \\
& =\left|\begin{array}{ccc}
1 & a & a^{2} \\
0 & b-a & b^{2}-a^{2} \\
0 & c-a & c^{2}-a^{2}
\end{array}\right|\left[\text { applying } R_{2} \rightarrow (R_{2}-R_{1}) \text { and } R_{3} \rightarrow (R_{3}-R_{1})\right] \\
& =(b-a)(c-a) \cdot\left|\begin{array}{ccc}
1 & a & a^{2} \\
0 & 1 & b+a \\
0 & 1 & c+a
\end{array}\right|
\end{aligned}
$$

[taking ($b-a$) common from $R_{2}$ and ($c-a$) common from $R_{3}$ ]

$$
\begin{aligned}
& =(b-a)(c-a) \times 1 \cdot\left|\begin{array}{ll}
1 & b+a \\
1 & c+a
\end{array}\right| \quad\left[\text { expanded by } C_{1}\right] \\
& =(b-a)(c-a)\{(c+a)-(b+a)\} \\
& =(b-a)(c-a)(c-b)=(a-b)(b-c)(c-a)
\end{aligned}
$$

Hence, $\Delta=(a-b)(b-c)(c-a)$.

---

### Example 8

Prove that $\left|\begin{array}{ccc}1 & 1 & 1 \\ a & b & c \\ a^{3} & b^{3} & c^{3}\end{array}\right|=(a-b)(b-c)(c-a)(a+b+c)$. [CBSE 2009C, '11, '12, '13C]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
1 & 1 & 1 \\
a & b & c \\
a^{3} & b^{3} & c^{3}
\end{array}\right| \\
& =\left|\begin{array}{ccc}
0 & 0 & 1 \\
a-c & b-c & c \\
a^{3}-c^{3} & b^{3}-c^{3} & c^{3}
\end{array}\right| \\
& {\left[\operatorname{applying} \quad C_{1} \rightarrow (C_{1}-C_{3}) \text { and } C_{2} \rightarrow (C_{2}-C_{3})\right] } \\
& =(a-c)(b-c) \cdot\left|\begin{array}{ccc}
0 & 0 & 1 \\
1 & 1 & c \\
a^{2}+a c+c^{2} & b^{2}+b c+c^{2} & c^{3}
\end{array}\right|\,
\end{aligned}
$$

[taking out ($a-c$) and ($b-c$) common from $C_{1}$ and $C_{2}$ ]

$$
\begin{aligned}
& =(a-c)(b-c) \cdot 1 \cdot\left|\begin{array}{cc}
1 & 1 \\
a^{2}+a c+c^{2} & b^{2}+b c+c^{2}
\end{array}\right| \quad\left[\text { expanded by } R_{1}\right] \\
& =(a-c)(b-c) \cdot\left[\left(b^{2}+b c+c^{2}\right)-\left(a^{2}+a c+c^{2}\right)\right] \\
& =(a-c)(b-c)\left[\left(b^{2}-a^{2}\right)+(b c-a c)\right] \\
& =(a-c)(b-c)\left[\left(b^{2}-a^{2}\right)+(b-a) c\right] \\
& =(a-c)(b-c)(b-a)(b+a+c) \\
& =(a-b)(b-c)(c-a)(a+b+c)
\end{aligned}
$$

Hence, $\Delta=(a-b)(b-c)(c-a)(a+b+c)$.

---

### Example 9

Prove that

$$
\left|\begin{array}{ccc}
\alpha & \beta & \gamma \\
\alpha^{2} & \beta^{2} & \gamma^{2} \\
\beta+\gamma & \gamma+\alpha & \alpha+\beta
\end{array}\right|=(\alpha-\beta)(\beta-\gamma)(\gamma-\alpha)(\alpha+\beta+\gamma) .
$$

[CBSE 2007C, '08, '10C, '11C, '12C]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
\alpha & \beta & \gamma \\
\alpha^{2} & \beta^{2} & \gamma^{2} \\
\beta+\gamma & \gamma+\alpha & \alpha+\beta
\end{array}\right| \\
& =\left|\begin{array}{ccc}
\alpha & \beta & \gamma \\
\alpha^{2} & \beta^{2} & \gamma^{2} \\
\alpha+\beta+\gamma & \alpha+\beta+\gamma & \alpha+\beta+\gamma
\end{array}\right|\left[\text { applying } R_{3} \rightarrow\left(R_{3}+R_{1}\right)\right]
\end{aligned}
$$

$$
\begin{aligned}
& =(\alpha+\beta+\gamma) \cdot\left|\begin{array}{ccc}
\alpha & \beta & \gamma \\
\alpha^{2} & \beta^{2} & \gamma^{2} \\
1 & 1 & 1
\end{array}\right| \text { [taking $(\alpha+\beta+\gamma) \text { common from } R_{3} \text { ] } \\
& =(\alpha+\beta+\gamma) \cdot\left|\begin{array}{ccc}
\alpha-\gamma & \beta-\gamma & \gamma \\
\alpha^{2}-\gamma^{2} & \beta^{2}-\gamma^{2} & \gamma^{2} \\
0 & 0 & 1
\end{array}\right| \\
& \left.\quad \text { [applying } C_{1} \rightarrow\left(C_{1}-C_{3}\right) \text { and } C_{2} \rightarrow\left(C_{2}-C_{3}\right)\right] \\
& =(\alpha+\beta+\gamma)(\alpha-\gamma)(\beta-\gamma) \cdot\left|\begin{array}{ccc}
1 & 1 & \gamma \\
\alpha+\gamma & \beta+\gamma & \gamma^{2} \\
0 & 0 & 1
\end{array}\right| \\
& \quad\left[\text { taking $(\alpha-\gamma) \text { common from } C_{1} \text { and }(\beta-\gamma) \text { common from } C_{2}\right] \\
& \left.=(\alpha+\beta+\gamma)(\alpha-\gamma)(\beta-\gamma) \cdot 1 \cdot\left|\begin{array}{cc}
1 & 1 \\
\alpha+\gamma & \beta+\gamma
\end{array}\right| \quad \text { [expanded by } R_{3}\right] \\
& =(\alpha+\beta+\gamma)(\alpha-\gamma)(\beta-\gamma)[(\beta+\gamma)-(\alpha+\gamma)] \\
& =(\alpha+\beta+\gamma)(\alpha-\gamma)(\beta-\gamma)(\beta-\alpha) \\
& =(\alpha-\beta)(\beta-\gamma)(\gamma-\alpha)(\alpha+\beta+\gamma) .
\end{aligned}
$$

Hence, $\Delta=(\alpha-\beta)(\beta-\gamma)(\gamma-\alpha)(\alpha+\beta+\gamma)$.

---

### Example 10

Using properties of determinants, show that

$$
\left|\begin{array}{ccc}
a+x & y & z \\
x & a+y & z \\
x & y & a+z
\end{array}\right|=a^{2}(a+x+y+z)
$$

[CBSE 2003, '14]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a+x & y & z \\
x & a+y & z \\
x & y & a+z
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+x+y+z & y & z \\
a+x+y+z & a+y & z \\
a+x+y+z & y & a+z
\end{array}\right| \quad\left[C_{1} \rightarrow C_{1}+C_{2}+C_{3}\right]
\end{aligned}
$$

$$
\begin{aligned}
& =(a+x+y+z) \cdot\left|\begin{array}{ccc}
1 & y & z \\
1 & a+y & z \\
1 & y & a+z
\end{array}\right| \\
& =(a+x+y+z) \cdot\left|\begin{array}{ccc}
1 & y & z \\
0 & a & 0 \\
0 & 0 & a
\end{array}\right| \quad\left[R_{2} \rightarrow R_{2}-R_{1} \text { and } R_{3} \rightarrow R_{3}-R_{1}\right] \\
& =(a+x+y+z) \cdot 1 \cdot\left|\begin{array}{ll}
a & 0 \\
0 & a
\end{array}\right| \quad\left[\text { expanded by } C_{1}\right] \\
& =a^{2}(a+x+y+z) .
\end{aligned}
$$

Hence, $\Delta=a^{2}(a+x+y+z)$.

---

### Example 11

Using properties of determinants, prove that

$$
\left|\begin{array}{lll}
1 & x & x^{2} \\
x^{2} & 1 & x \\
x & x^{2} & 1
\end{array}\right|=\left(1-x^{3}\right)^{2} .
$$

[CBSE 2008C, '13]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
& \Delta=\left|\begin{array}{lll}
1 & x & x^{2} \\
x^{2} & 1 & x \\
x & x^{2} & 1
\end{array}\right| \\
&=\left|\begin{array}{lll}
1+x+x^{2} & x & x^{2} \\
1+x+x^{2} & 1 & x \\
1+x+x^{2} & x^{2} & 1
\end{array}\right| \quad\left[\text { applying } C_{1} \rightarrow\left(C_{1}+C_{2}+C_{3}\right)\right] \\
&=\left(1+x+x^{2}\right)\left|\begin{array}{ccc}
1 & x & x^{2} \\
1 & 1 & x \\
1 & x^{2} & 1
\end{array}\right| \quad\left[\text { taking }\left(1+x+x^{2}\right) \text { common from } C_{1}\right] \\
&=\left(1+x+x^{2}\right)\left|\begin{array}{ccc}
1 & x & x^{2} \\
0 & 1-x & x(1-x) \\
0 & x(x-1) & (1-x)(1+x)
\end{array}\right| \\
& {\left[\operatorname{applying} R_{2} \rightarrow\left(R_{2}-R_{1}\right) \text { and } R_{3} \rightarrow\left(R_{3}-R_{1}\right)\right] } \\
&=\left(1+x+x^{2}\right)(1-x)^{2} \cdot\left|\begin{array}{ccc}
1 & x & x^{2} \\
0 & 1 & x \\
0 & -x & (1+x)
\end{array}\right|
\end{aligned}
$$

[taking $(1-x)$ common from each of $R_{2}$ and $R_{3}$]

$$
\begin{aligned}
& \left.=\left(1+x+x^{2}\right)(1-x)^{2} \cdot 1 \cdot\left|\begin{array}{cc}
1 & x \\
-x & (1+x)
\end{array}\right| \quad \text { [expanded by } C_{1}\right] \\
& =\left(1+x+x^{2}\right)(1-x)^{2} \cdot\left(1+x+x^{2}\right) \\
& =\left\{(1-x)\left(1+x+x^{2}\right)\right\}^{2}=\left(1-x^{3}\right)^{2}
\end{aligned}
$$

Hence, $\Delta=\left(1-x^{3}\right)^{2}$.

---

### Example 12

Using the properties of determinants, prove that

$$
\left|\begin{array}{ccc}
2 y & y-z-x & 2 y \\
2 z & 2 z & z-x-y \\
x-y-z & 2 x & 2 x
\end{array}\right|=(x+y+z)^{3}
$$

[CBSE 2014]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\Delta=\left|\begin{array}{ccc}
2 y & y-z-x & 2 y \\
2 z & 2 z & z-x-y \\
x-y-z & 2 x & 2 x
\end{array}\right|
$$

$$
\begin{aligned}
& \left.=\left|\begin{array}{ccc}
2 y & y-z-x & 2 y \\
2 z & 2 z & z-x-y \\
x+y+z & x+y+z & x+y+z
\end{array}\right| \text { [applying } R_{3} \rightarrow\left(R_{1}+R_{2}+R_{3}\right)\right] \\
& =(x+y+z) \cdot\left|\begin{array}{ccc}
2 y & y-z-x & 2 y \\
2 z & 2 z & z-x-y \\
1 & 1 & 1
\end{array}\right| \\
& =(x+y+z) \cdot\left|\begin{array}{ccc}
0 & -(x+y+z) & 2 y \\
(x+y+z) & (x+y+z) & z-x-y \\
0 & 0 & 1
\end{array}\right| \\
& \left.\quad \text { [applying } C_{1} \rightarrow\left(C_{1}-C_{3}\right) \text { and } C_{2} \rightarrow\left(C_{2}-C_{3}\right)\right] \\
& =(x+y+z) \cdot 1 \cdot\left|\begin{array}{cc}
0 & -(x+y+z) \\
(x+y+z) & (x+y+z)
\end{array}\right| \text { [expanded by } R_{3} \text { ] } \\
& =(x+y+z)\left\{0+(x+y+z)^{2}\right\}=(x+y+z)(x+y+z)^{2}=(x+y+z)^{3} .
\end{aligned}
$$

Hence, $\Delta=(x+y+z)^{3}$.

---

### Example 13

Using properties of determinants, prove that

$$
\left|\begin{array}{ccc}
3 a & -a+b & -a+c \\
a-b & 3 b & c-b \\
a-c & b-c & 3 c
\end{array}\right|=3(a+b+c)(a b+b c+c a) .
$$

[CBSE 2006,'13]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
3 a & -a+b & -a+c \\
a-b & 3 b & c-b \\
a-c & b-c & 3 c
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+b+c & -a+b & -a+c \\
a+b+c & 3 b & c-b \\
a+b+c & b-c & 3 c
\end{array}\right| \quad\left[C_{1} \rightarrow\left(C_{1}+C_{2}+C_{3}\right)\right] \\
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & -a+b & -a+c \\
1 & 3 b & c-b \\
1 & b-c & 3 c
\end{array}\right| \\
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & -a+b & -a+c \\
0 & 2 b+a & a-b \\
0 & a-c & 2 c+a
\end{array}\right| \\
& =(a+b+c) \cdot 1 \cdot\left|\begin{array}{cc}
2 b+a & a-b \\
a-c & 2 c+a
\end{array}\right| \quad\left[\operatorname{expanded~by~} C_{1}\right] \\
& =(a+b+c)[(2 b+a)(2 c+a)-(a-c)(a-b)]
\end{aligned}
$$

$$
\begin{aligned}
& =(a+b+c)\left[\left(4 b c+2 a b+2 a c+a^{2}\right)-\left(a^{2}-a b-a c+b c\right)\right] \\
& =3(a+b+c)(a b+b c+c a)
\end{aligned}
$$

Hence, $\Delta=3(a+b+c)(a b+b c+c a)$.

---

### Example 14

Prove that

$$
\left|\begin{array}{lll}
b+c & c+a & a+b \\
c+a & a+b & b+c \\
a+b & b+c & c+a
\end{array}\right|=2(a+b+c)\left(a b+b c+c a-a^{2}-b^{2}-c^{2}\right)
$$

[CBSE 2004, '09C]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
b+c & c+a & a+b \\
c+a & a+b & b+c \\
a+b & b+c & c+a
\end{array}\right| \\
& =\left|\begin{array}{ccc}
2(a+b+c) & 2(a+b+c) & 2(a+b+c) \\
c+a & a+b & b+c \\
a+b & b+c & c+a
\end{array}\right|\left[R_{1} \rightarrow\left(R_{1}+R_{2}+R_{3}\right)\right] \\
& =2(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
c+a & a+b & b+c \\
a+b & b+c & c+a
\end{array}\right|
\end{aligned}
$$

[taking $(a+b+c)$ common from $R_{1}$]

$$
\begin{aligned}
& =2(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 0 & 0 \\
c+a & b-c & b-a \\
a+b & c-a & c-b
\end{array}\right| \quad\left[\begin{array}{l}
C_{2} \rightarrow\left(C_{2}-C_{1}\right) \text { and } \\
C_{3} \rightarrow\left(C_{3}-C_{1}\right)
\end{array}\right] \\
& \left.=2(a+b+c) \cdot 1 \cdot\left|\begin{array}{ll}
b-c & b-a \\
c-a & c-b
\end{array}\right| \quad \text { [expanded by } R_{1}\right] \\
& =2(a+b+c) \cdot[(b-c)(c-b)-(c-a)(b-a)] \\
& =2(a+b+c)\left(a b+b c+c a-a^{2}-b^{2}-c^{2}\right)
\end{aligned}
$$

Hence, $\Delta=2(a+b+c)\left(a b+b c+c a-a^{2}-b^{2}-c^{2}\right)$.

---

### Example 15

Using properties of determinants, prove that

$$
\left|\begin{array}{ccc}
a-b-c & 2 a & 2 a \\
2 b & b-c-a & 2 b \\
2 c & 2 c & c-a-b
\end{array}\right|=(a+b+c)^{3} .
$$

[CBSE 2001,'04,'06C,'07]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a-b-c & 2 a & 2 a \\
2 b & b-c-a & 2 b \\
2 c & 2 c & c-a-b
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+b+c & a+b+c & a+b+c \\
2 b & b-c-a & 2 b \\
2 c & 2 c & c-a-b
\end{array}\right| \quad\left[R_{1} \rightarrow\left(R_{1}+R_{2}+R_{3}\right)\right]
\end{aligned}
$$

$$
\begin{aligned}
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
2 b & b-c-a & 2 b \\
2 c & 2 c & c-a-b
\end{array}\right| \\
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 0 & 0 \\
2 b & -(a+b+c) & 0 \\
2 c & 0 & -(a+b+c)
\end{array}\right| \\
& =(a+b+c) \cdot 1 \cdot\left|\begin{array}{cc}
-(a+b+c) & 0 \\
0 & -(a+b+c)
\end{array}\right| \quad\left[\text { expanded by } R_{1}\right] \\
& =(a+b+c)(a+b+c)^{2}=(a+b+c)^{3} .
\end{aligned}
$$

Hence, $\Delta=(a+b+c)^{3}$.

---

### Example 16

Prove that

$$
\left|\begin{array}{ccc}
a+b+2 c & a & b \\
c & b+c+2 a & b \\
c & a & c+a+2 b
\end{array}\right|=2(a+b+c)^{3} .
$$

[CBSE 2008, '12C, '14C]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a+b+2 c & a & b \\
c & b+c+2 a & b \\
c & a & c+a+2 b
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+b+c & -(a+b+c) & 0 \\
c & b+c+2 a & b \\
0 & -(a+b+c) & (a+b+c)
\end{array}\right|\left\{\begin{array}{l}
\text { by } R_{1} \rightarrow\left(R_{1}-R_{2}\right) \\
\text { and } R_{3} \rightarrow\left(R_{3}-R_{2}\right)
\end{array}\right\} \\
& =(a+b+c)^{2} \cdot\left|\begin{array}{ccc}
1 & -1 & 0 \\
c & b+c+2 a & b \\
0 & -1 & 1
\end{array}\right|
\end{aligned}
$$

[taking $(a+b+c)$ common from each one of $R_{1}$ and $R_{3}$]

$$
\begin{aligned}
& =(a+b+c)^{2} \cdot\left|\begin{array}{ccc}
1 & -1 & 0 \\
0 & b+2 c+2 a & b \\
0 & -1 & 1
\end{array}\right| \quad\left[R_{2} \rightarrow R_{2}-c R_{1}\right] \\
& =(a+b+c)^{2} \cdot 1 \cdot\left|\begin{array}{cc}
b+2 c+2 a & b \\
-1 & 1
\end{array}\right| \quad\left[\text { expanded by } C_{1}\right] \\
& =(a+b+c)^{2} \cdot(b+2 c+2 a+b)=2(a+b+c)^{3}
\end{aligned}
$$

Hence, $\Delta=2(a+b+c)^{3}$.

---

### Example 17

Using properties of determinants, prove that

$$
\left|\begin{array}{ccc}
a & b & c \\
a^{2} & b^{2} & c^{2} \\
b c & c a & a b
\end{array}\right|=(a-b)(b-c)(c-a)(a b+b c+c a) .
$$

[CBSE 2011C,'13C]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a & b & c \\
a^{2} & b^{2} & c^{2} \\
b c & c a & a b
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a-c & b-c & c \\
a^{2}-c^{2} & b^{2}-c^{2} & c^{2} \\
b(c-a) & a(c-b) & a b
\end{array}\right| \quad\left[C_{1} \rightarrow\left(C_{1}-C_{3}\right), C_{2} \rightarrow\left(C_{2}-C_{3}\right)\right] \\
& =(a-c)(b-c) \cdot\left|\begin{array}{ccc}
1 & 1 & c \\
a+c & b+c & c^{2} \\
-b & -a & a b
\end{array}\right|
\end{aligned}
$$

[taking $(a-c)$ common from $C_{1}$ and $(b-c)$ common from $C_{2}$]

$$
\begin{aligned}
& =(a-c)(b-c) \cdot\left|\begin{array}{ccc}
1 & 0 & 0 \\
a+c & b-a & -c a \\
-b & b-a & (a+c) b
\end{array}\right| \\
& =(a-c)(b-c) \cdot 1 \cdot\left|\begin{array}{cc}
b-a & -c a \\
b-a & (a+c) b
\end{array}\right|\left\{\text { expanded by } R_{1}\right\} \\
& =(a-c)(b-c) \cdot(b-a)\left|\begin{array}{cc}
1 & -c a \\
1 & (a+c) b
\end{array}\right| \\
& =(a-b)(b-c)(c-a)(a b+b c+c a) .
\end{aligned}
$$

Hence, $\Delta=(a-b)(b-c)(c-a)(a b+b c+c a)$.

---

### Example 18

Using properties of determinants, prove that

$$
\left|\begin{array}{ccc}
a & b & c \\
a-b & b-c & c-a \\
b+c & c+a & a+b
\end{array}\right|=\left(a^{3}+b^{3}+c^{3}-3 a b c\right) \text {. [CBSE 2006,'09,'12C] }
$$

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a & b & c \\
a-b & b-c & c-a \\
b+c & c+a & a+b
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+b+c & b & c \\
0 & b-c & c-a \\
2(a+b+c) & c+a & a+b
\end{array}\right| \quad\left[C_{1} \rightarrow\left(C_{1}+C_{2}+C_{3}\right)\right]
\end{aligned}
$$

$$
\begin{aligned}
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & b & c \\
0 & b-c & c-a \\
2 & c+a & a+b
\end{array}\right| \\
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & b & c \\
0 & b-c & c-a \\
0 & c+a-2 b & a+b-2 c
\end{array}\right| \quad\left[R_{3} \rightarrow R_{3}-2 R_{1}\right] \\
& =(a+b+c) \cdot 1 \cdot\left|\begin{array}{cc}
b-c & c-a \\
c+a-2 b & a+b-2 c
\end{array}\right| \quad\left[\text { expanded by } C_{1}\right] \\
& =(a+b+c) \cdot\left|\begin{array}{cc}
b-c & c-a \\
a-b & b-c
\end{array}\right| \quad\left[R_{2} \rightarrow R_{2}+R_{1}\right] \\
& =(a+b+c) \cdot\left[(b-c)^{2}-(a-b)(c-a)\right] \\
& =(a+b+c)\left(a^{2}+b^{2}+c^{2}-a b-b c-c a\right) \\
& =\left(a^{3}+b^{3}+c^{3}-3 a b c\right)
\end{aligned}
$$

Hence, $\Delta=\left(a^{3}+b^{3}+c^{3}-3 a b c\right)$.

---

### Example 19

Prove that $\left|\begin{array}{ccc}y+z & z & y \\ z & z+x & x \\ y & x & x+y\end{array}\right|=4 x y z$.

#### Solution:

Given determinant $=\left|\begin{array}{ccc}y+z & z & y \\ z & z+x & x \\ y & x & x+y\end{array}\right|$

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
0 & -2 x & -2 x \\
z & z+x & x \\
y & x & x+y
\end{array}\right| \quad\left[R_{1} \rightarrow R_{1}-\left(R_{2}+R_{3}\right)\right] \\
& =(-2 x) \cdot\left|\begin{array}{ccc}
0 & 1 & 1 \\
z & z+x & x \\
y & x & x+y
\end{array}\right|
\end{aligned}
$$

[taking ( $-2 x$ ) common from $R_{1}$ ]
$=(-2 x) \cdot\left|\begin{array}{ccc}0 & 0 & 1 \\ z & z & x \\ y & -y & x+y\end{array}\right| \quad\left[C_{2} \rightarrow\left(C_{2}-C_{3}\right)\right]$
$=(-2 x) \cdot 1 \cdot\left|\begin{array}{rr}z & z \\ y & -y\end{array}\right| \quad$ [expanded by $R_{1}$ ]
$=(-2 x) \cdot 1 \cdot(-y z-y z)=(-2 x)(-2 y z)=4 x y z$.

---

### Example 20

Prove that $\left|\begin{array}{ccc}a^{2} & b c & c^{2}+a c \\ a^{2}+a b & b^{2} & a c \\ a b & b^{2}+b c & c^{2}\end{array}\right|=4 a^{2} b^{2} c^{2}$. [CBSE 2014]

#### Solution:

$\left|\begin{array}{ccc}a^{2} & b c & c^{2}+a c \\ a^{2}+a b & b^{2} & a c \\ a b & b^{2}+b c & c^{2}\end{array}\right|$

$$
=(a b c) \cdot\left|\begin{array}{ccc}
a & c & c+a \\
a+b & b & a \\
b & b+c & c
\end{array}\right|
$$

[taking $a, b, c$ common from $C_{1}, C_{2}$ and $C_{3}$ respectively]

$$
\begin{aligned}
& =(a b c) \cdot\left|\begin{array}{ccc}
a & c & c+a \\
0 & -2 c & -2 c \\
b & b+c & c
\end{array}\right| \quad\left[R_{2} \rightarrow R_{2}-\left(R_{1}+R_{3}\right)\right] \\
& =(a b c) \cdot\left|\begin{array}{ccc}
a & -a & c+a \\
0 & 0 & -2 c \\
b & b & c
\end{array}\right| \quad\left[C_{2} \rightarrow C_{2}-C_{3}\right] \\
& =(a b c)(2 c) \cdot\left|\begin{array}{cc}
a & -a \\
b & b
\end{array}\right| \quad\left[\text { expanded by } R_{2}\right] \\
& =2 a b c^{2} \cdot(a b+a b)=2 a b c^{2}(2 a b) \\
& =4 a^{2} b^{2} c^{2}
\end{aligned}
$$

---

### Example 21

If $a, b, c$ are positive and unequal, show that the value of the determinant $\left|\begin{array}{lll}a & b & c \\ b & c & a \\ c & a & b\end{array}\right|$ is negative.

#### Solution:

The given determinant

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
a & b & c \\
b & c & a \\
c & a & b
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+b+c & b & c \\
a+b+c & c & a \\
a+b+c & a & b
\end{array}\right| \quad\left[C_{1} \rightarrow\left(C_{1}+C_{2}+C_{3}\right)\right] \\
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & b & c \\
1 & c & a \\
1 & a & b
\end{array}\right|
\end{aligned}
$$

$$
\begin{aligned}
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & b & c \\
0 & c-b & a-c \\
0 & a-b & b-c
\end{array}\right|\left[R_{2} \rightarrow\left(R_{2}-R_{1}\right) \text { and } R_{3} \rightarrow\left(R_{3}-R_{1}\right)\right] \\
& =(a+b+c) \cdot[(c-b)(b-c)-(a-b)(a-c)] \quad\left[\text { expanded by } C_{1}\right] \\
& =(a+b+c) \cdot\left(-a^{2}-b^{2}-c^{2}+a b+b c+c a\right) \\
& =-\frac{1}{2}(a+b+c)\left(2 a^{2}+2 b^{2}+2 c^{2}-2 a b-2 b c-2 c a\right) \\
& =-\frac{1}{2}(a+b+c)\left[(a-b)^{2}+(b-c)^{2}+(c-a)^{2}\right], \text { which is negative } \\
& \quad\left[\because \quad(a+b+c)>0,(a-b)^{2}>0,(b-c)^{2}>0 \text { and }(c-a)^{2}>0\right] .
\end{aligned}
$$

---

### Example 22

Evaluate $\left|\begin{array}{lll}{ }^{m} C_{1} & { }^{m} C_{2} & { }^{m} C_{3} \\ { }^{n} C_{1} & { }^{n} C_{2} & { }^{n} C_{3} \\ { }^{p} C_{1} & { }^{p} C_{2} & { }^{p} C_{3}\end{array}\right|$.

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
m & \frac{1}{2} m(m-1) & \frac{1}{6} \cdot m(m-1)(m-2) \\
n & \frac{1}{2} n(n-1) & \frac{1}{6} \cdot n(n-1)(n-2) \\
p & \frac{1}{2} p(p-1) & \frac{1}{6} \cdot p(p-1)(p-2)
\end{array}\right| \\
& =\left(\frac{1}{2} \times \frac{1}{6} \times m n p\right) \cdot\left|\begin{array}{ccc}
1 & (m-1) & (m-1)(m-2) \\
1 & (n-1) & (n-1)(n-2) \\
1 & (p-1) & (p-1)(p-2)
\end{array}\right| \\
& =\frac{1}{12} \cdot m n p \cdot\left|\begin{array}{ccc}
1 & m-1 & (m-1)(m-2) \\
0 & n-m & (n-m)(n+m-3) \\
0 & p-m & (p-m)(p+m-3)
\end{array}\right| \\
& =\frac{1}{12} \cdot(m n p)(n-m)(p-m) \cdot\left|\begin{array}{ccc}
1 & m-1 & (m-1)(m-2) \\
0 & 1 & (n+m-3) \\
0 & 1 & (p+m-3)
\end{array}\right|
\end{aligned}
$$

[taking $(n-m)$ common from $R_{2}$ and $(p-m)$ common from $R_{3}$ ]

$$
\begin{aligned}
& =\frac{1}{12} \cdot(m n p)(n-m)(p-m) \cdot 1 \cdot\left|\begin{array}{cc}
1 & (n+m-3) \\
1 & (p+m-3)
\end{array}\right| \\
& =\frac{1}{12} \cdot(m n p)(n-m)(p-m)[(p+m-3)-(n+m-3)] \\
& =\frac{1}{12} \cdot(m n p)(n-m)(p-m)(p-n)
\end{aligned}
$$

$$
\begin{gathered}
\qquad \begin{array}{c}
=\frac{1}{12} \cdot(m n p)(m-n)(n-p)(p-m) \\
\text { Hence, } \Delta=\frac{1}{12} \cdot(m n p)(m-n)(n-p)(p-m)
\end{array}
\end{gathered}
$$

---

### Example 23

Prove that $\left|\begin{array}{ccc}(b+c)^{2} & a^{2} & a^{2} \\ b^{2} & (c+a)^{2} & b^{2} \\ c^{2} & c^{2} & (a+b)^{2}\end{array}\right|=2 a b c(a+b+c)^{3}$. [CBSE 2010, '10C]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
(b+c)^{2} & a^{2} & a^{2} \\
b^{2} & (c+a)^{2} & b^{2} \\
c^{2} & c^{2} & (a+b)^{2}
\end{array}\right| \\
& =\left|\begin{array}{ccc}
(b+c)^{2}-a^{2} & 0 & a^{2} \\
0 & (c+a)^{2}-b^{2} & b^{2} \\
c^{2}-(a+b)^{2} & c^{2}-(a+b)^{2} & (a+b)^{2}
\end{array}\right| \\
& =\left|\begin{array}{ccc}
(a+b+c)(b+c-a) & {\left[C_{1} \rightarrow C_{1}-C_{3} \text { and } C_{2} \rightarrow C_{2}-C_{3}\right]} \\
0 & (a+b+c)(c+a-b) & a^{2} \\
(a+b+c)(c-a-b) & (a+b+c)(c-a-b) & (a+b)^{2}
\end{array}\right| \\
& =(a+b+c)^{2} \cdot\left|\begin{array}{ccc}
(b+c-a) & 0 & a^{2} \\
0 & c+a-b & b^{2} \\
c-a-b & c-a-b & (a+b)^{2}
\end{array}\right|
\end{aligned}
$$

[taking $(a+b+c)$ common from $C_{1}$ and $C_{2}$ both]
$=(a+b+c)^{2} \cdot\left|\begin{array}{ccc}(b+c-a) & 0 & a^{2} \\ 0 & c+a-b & b^{2} \\ -2 b & -2 a & 2 a b\end{array}\right| \quad\left[R_{3} \rightarrow R_{3}-\left(R_{1}+R_{2}\right)\right]$
$=(a+b+c)^{2}\left[(b+c-a)\left\{(c+a-b) \cdot 2 a b+2 a b^{2}\right\}+a^{2}\{0+2 b(c+a-b)\}\right]$
$=(a+b+c)^{2}\left[(b+c-a) \cdot 2 a b\{(c+a-b+b)\}+2 a^{2} b(c+a-b)\right]$
$=2 a b(a+b+c)^{2}\{(b+c-a)(c+a)+a(c+a-b)\}$
$=2 a b(a+b+c)^{2} \cdot\left\{b c+a b+c^{2}+a c-a c-a^{2}+a c+a^{2}-a b\right\}$
$=2 a b(a+b+c)^{2}\left\{b c+c^{2}+a c\right\}=2 a b c(a+b+c)^{3}$.
Hence, $\Delta=2 a b c(a+b+c)^{3}$.

---

## Type: Expressing a Given Det. as Sum of Two Determinants

### Example 24

Prove that $\left|\begin{array}{lll}b+c & a & b \\ c+a & c & a \\ a+b & b & c\end{array}\right|=(a+b+c)(a-c)^{2}$. [CBSE 2005C, '07]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
b+c & a & b \\
c+a & c & a \\
a+b & b & c
\end{array}\right| \\
& =\left|\begin{array}{ccc}
b & a & b \\
c & c & a \\
a & b & c
\end{array}\right|+\left|\begin{array}{ccc}
c & a & b \\
a & c & a \\
b & b & c
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a+b+c & a+b+c & a+b+c \\
c & c & a \\
a & b & c
\end{array}\right|+\left|\begin{array}{ccc}
a+b+c & a+b+c & a+b+c \\
a & c & a \\
b & b & c
\end{array}\right| \\
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
c & c & a \\
a & b & c
\end{array}\right|+(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
a & c & a \\
b & b & c
\end{array}\right|
\end{aligned}
$$

[taking out $(a+b+c)$ common from $R_{1}$ in each determinant]

$$
\begin{aligned}
& =(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 0 & 0 \\
c & 0 & a-c \\
a & b-a & c-a
\end{array}\right|+(a+b+c) \cdot\left|\begin{array}{ccc}
1 & 0 & 0 \\
a & c-a & 0 \\
b & 0 & c-b
\end{array}\right| \\
& {\left[C_{2} \rightarrow\left(C_{2}-C_{1}\right) \text { and } C_{3} \rightarrow\left(C_{3}-C_{1}\right) \text { in each }\right]} \\
& =(a+b+c) \cdot 1 \cdot\left|\begin{array}{cc}
0 & a-c \\
b-a & c-a
\end{array}\right|+(a+b+c) \cdot 1 \cdot\left|\begin{array}{cc}
c-a & 0 \\
0 & c-b
\end{array}\right|
\end{aligned}
$$

[each det. expanded by $R_{1}$ ]

$$
\begin{aligned}
& =(a+b+c) \cdot[0-(b-a)(a-c)]+(a+b+c)(c-a)(c-b) \\
& =(a+b+c)(a-b)(a-c)-(a+b+c)(a-c)(c-b) \\
& =(a+b+c)(a-c)\{(a-b)-(c-b)\} \\
& =(a+b+c)(a-c)^{2} .
\end{aligned}
$$

Hence, $\Delta=(a+b+c)(a-c)^{2}$.

---

### Example 25

Prove that $\left|\begin{array}{ccc}1 & a & a^{2}-b c \\ 1 & b & b^{2}-c a \\ 1 & c & c^{2}-a b\end{array}\right|=0$. [CBSE 2005C]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
1 & a & a^{2}-b c \\
1 & b & b^{2}-c a \\
1 & c & c^{2}-a b
\end{array}\right| \\
& =\left|\begin{array}{lll}
1 & a & a^{2} \\
1 & b & b^{2} \\
1 & c & c^{2}
\end{array}\right|+\left|\begin{array}{lll}
1 & a & -b c \\
1 & b & -c a \\
1 & c & -a b
\end{array}\right|
\end{aligned}
$$

$$
\begin{aligned}
= & \left|\begin{array}{ccc}
1 & a & a^{2} \\
0 & b-a & b^{2}-a^{2} \\
0 & c-a & c^{2}-a^{2}
\end{array}\right|+\left|\begin{array}{ccc}
1 & a & -b c \\
0 & b-a & c(b-a) \\
0 & c-a & b(c-a)
\end{array}\right| \\
& \quad\left[R_{2} \rightarrow\left(R_{2}-R_{1}\right) \text { and } R_{3} \rightarrow\left(R_{3}-R_{1}\right) \text { in each determinant }\right] \\
= & (b-a)(c-a) \cdot\left|\begin{array}{ccc}
1 & a & a^{2} \\
0 & 1 & b+a \\
0 & 1 & c+a
\end{array}\right|+(b-a)(c-a) \cdot\left|\begin{array}{ccc}
1 & a & -b c \\
0 & 1 & c \\
0 & 1 & b
\end{array}\right| \\
= & (b-a)(c-a) \cdot 1 \cdot\{(c+a)-(b+a)\}+(b-a)(c-a) \cdot 1 \cdot(b-c) \\
= & (b-a)(c-a)(c-b)+(b-a)(c-a)(b-c) \\
= & (a-b)(b-c)(c-a)-(a-b)(b-c)(c-a)=0
\end{aligned}
$$

Hence, $\Delta=0$.

---

### Example 26

If $x \neq y \neq z$ and $\left|\begin{array}{lll}x & x^{2} & 1+x^{3} \\ y & y^{2} & 1+y^{3} \\ z & z^{2} & 1+z^{3}\end{array}\right|=0$ then prove that $x y z=-1$. [CBSE 2008, '09C, '11]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
x & x^{2} & 1+x^{3} \\
y & y^{2} & 1+y^{3} \\
z & z^{2} & 1+z^{3}
\end{array}\right|=\left|\begin{array}{lll}
x & x^{2} & 1 \\
y & y^{2} & 1 \\
z & z^{2} & 1
\end{array}\right|+\left|\begin{array}{lll}
x & x^{2} & x^{3} \\
y & y^{2} & y^{3} \\
z & z^{2} & z^{3}
\end{array}\right| \\
& =\left|\begin{array}{lll}
x & x^{2} & 1 \\
y & y^{2} & 1 \\
z & z^{2} & 1
\end{array}\right|+(x y z) \cdot\left|\begin{array}{ccc}
1 & x & x^{2} \\
1 & y & y^{2} \\
1 & z & z^{2}
\endarray}\right| \\
& =\left|\begin{array}{lll}
x & x^{2} & 1 \\
y & y^{2} & 1 \\
z & z^{2} & 1
\end{array}\right|+(x y z)(-1)^{2} \cdot\left|\begin{array}{lll}
x & x^{2} & 1 \\
y & y^{2} & 1 \\
z & z^{2} & 1
\end{array}\right|
\end{aligned}
$$

[interchanging the columns of the 2nd det. twice]

$$
\begin{aligned}
& =(1+x y z)\left|\begin{array}{ccc}
x & x^{2} & 1 \\
y & y^{2} & 1 \\
z & z^{2} & 1
\end{array}\right| \\
& =(1+x y z)\left|\begin{array}{ccc}
x & x^{2} & 1 \\
(y-x) & \left(y^{2}-x^{2}\right) & 0 \\
(z-x) & \left(z^{2}-x^{2}\right) & 0
\end{array}\right|\left[R_{2} \rightarrow\left(R_{2}-R_{1}\right), R_{3} \rightarrow\left(R_{3}-R_{1}\right)\right] \\
& =(1+x y z)(y-x)(z-x)\left|\begin{array}{ccc}
x & x^{2} & 1 \\
1 & y+z & 0 \\
1 & z+x & 0
\end{array}\right|
\end{aligned}
$$

$$
\begin{aligned}
& \quad=(1+x y z)(y-x)(z-x) \cdot 1 \cdot\left|\begin{array}{ll}
1 & y+x \\
1 & z+x
\end{array}\right| \quad \text { [expanding by } C_{3} \text { ] } \\
& \quad=(1+x y z)(y-x)(z-x)(z-y) \\
& \quad \therefore \quad \Delta=0 \quad \Rightarrow \quad(1+x y z)(y-x)(z-x)(z-y)=0 \\
& \quad \Rightarrow \quad(1+x y z)=0 \quad[\because \quad(y-x) \neq 0,(z-x) \neq 0,(z-y) \neq 0] \\
& \quad \Rightarrow x y z=-1
\end{aligned}
$$

Hence, $x y z=-1$.

---

### Example 27

For any scalar $p$, prove that

$$
\left|\begin{array}{lll}
x & x^{2} & 1+p x^{3} \\
y & y^{2} & 1+p y^{3} \\
z & z^{2} & 1+p z^{3}
\end{array}\right|=(1+p x y z)(x-y)(y-z)(z-x)
$$
[CBSE 2010]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
x & x^{2} & 1+p x^{3} \\
y & y^{2} & 1+p y^{3} \\
z & z^{2} & 1+p z^{3}
\end{array}\right| \\
& =\left|\begin{array}{ccc}
x & x^{2} & 1 \\
y & y^{2} & 1 \\
z & z^{2} & 1
\end{array}\right|+\left|\begin{array}{ccc}
x & x^{2} & p x^{3} \\
y & y^{2} & p y^{3} \\
z & z^{2} & p z^{3}
\end{array}\right| \quad\left[\text { say } \Delta_{1}+\Delta_{2}\right] \\
& =(-1) \cdot\left|\begin{array}{ccc}
x & 1 & x^{2} \\
y & 1 & y^{2} \\
z & 1 & z^{2}
\end{array}\right|+p \cdot\left|\begin{array}{ccc}
x & x^{2} & x^{3} \\
y & y^{2} & y^{3} \\
z & z^{2} & z^{3}
\end{array}\right| \quad\left[\text { by } C_{2} \leftrightarrow C_{3} \text { in } \Delta_{1}\right] \\
& =(-1)(-1) \cdot\left|\begin{array}{ccc}
1 & x & x^{2} \\
1 & y & y^{2} \\
1 & z & z^{2}
\end{array}\right|+(p x y z) \cdot\left|\begin{array}{ccc}
1 & x & x^{2} \\
1 & y & y^{2} \\
1 & z & z^{2}
\end{array}\right| \quad\left[\text { by } C_{1} \leftrightarrow C_{2}\right]\left[\text { taking } x, y, z \text { common from } R_{1}, R_{2}, R_{3} \text { resp. }\right] \\
& =(1+p x y z)\left|\begin{array}{ccc}
1 & x & x^{2} \\
1 & y & y^{2} \\
1 & z & z^{2}
\end{array}\right| \\
& =(1+p x y z)\left|\begin{array}{ccc}
1 & x & x^{2} \\
0 & y-x & y^{2}-x^{2} \\
0 & z-x & z^{2}-x^{2}
\end{array}\right|
\end{aligned}
$$

[by $R_{2} \rightarrow R_{2}-R_{1}$ and $R_{3} \rightarrow R_{3}-R_{1}$ ]
$=(1+p x y z)(y-x)(z-x) \cdot\left|\begin{array}{ccc}1 & x & x^{2} \\ 0 & 1 & y+x \\ 0 & 1 & z+x\end{array}\right|$
[taking $(y-x)$ common from $R_{2}$ and $(z-x)$ common from $R_{3}$ ]

$$
\begin{aligned}
& =(1+p x y z)(y-x)(z-x) \cdot 1 \cdot\left|\begin{array}{cc}
1 & y+x \\
1 & z+x
\end{array}\right| \\
& =(1+p x y z)(y-x)(z-x) \cdot\{(z+x)-(y+x)\} \\
& =(1+p x y z)(y-x)(z-x)(z-y) \\
& =(1+p x y z)(x-y)(y-z)(z-x)=\text { RHS } . \\
\therefore \quad & \quad \text { LHS }=\text { RHS } .
\end{aligned}
$$

---

## Type: Some More Problems

### Example: 28

Prove that

$$
\left|\begin{array}{ccc}
1+a & 1 & 1 \\
1 & 1+b & 1 \\
1 & 1 & 1+c
\end{array}\right|=(a b c)\left(\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+1\right)=(b c+c a+a b+a b c)
$$

[CBSE 2004, '08, '09, '12, '14]

#### Solution:

The given determinant

$$
\begin{aligned}
& =\left|\begin{array}{ccc}
1+a & 1 & 1 \\
1 & 1+b & 1 \\
1 & 1 & 1+c
\end{array}\right| \\
& =(a b c) \cdot\left|\begin{array}{ccc}
\frac{1}{a}+1 & \frac{1}{a} & \frac{1}{a} \\
\frac{1}{b} & \frac{1}{b}+1 & \frac{1}{b} \\
\frac{1}{c} & \frac{1}{c} & \frac{1}{c}+1
\end{array}\right| \\
& \quad \text { [taking } a, b, c \text { common from } R_{1}, R_{2} \text { and } R_{3} \text { respectively] } \\
& =(a b c)\left(\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+1\right) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
\frac{1}{b} & \frac{1}{b}+1 & \frac{1}{b} \\
\frac{1}{c} & \frac{1}{c} & \frac{1}{c}+1
\end{array}\right| \\
& \quad\left[\text { applying } R_{1} \rightarrow R_{1}+R_{2}+R_{3} \text { and taking out }\left(\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+1\right)\right. \\
& \quad(a b c)\left(\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+1\right) \cdot\left|\begin{array}{ccc}
0 & 0 & 1 \\
0 & 1 & \frac{1}{b} \\
-1 & -1 & \frac{1}{c}+1
\end{array}\right| \\
& \left.\quad \text { [applying } C_{1} \rightarrow\left(C_{1}-C_{3}\right) \text { and } C_{2} \rightarrow\left(C_{2}-C_{3}\right)\right] \\
& \quad \text { [expanding by } 1 \text { st row } \text { ] }
\end{aligned}
$$

$$
\begin{aligned}
& =(a b c)\left(\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+1\right) \cdot 1 \\
& =(a b c)\left(\frac{1}{a}+\frac{1}{b}+\frac{1}{c}+1\right)=(b c+c a+a b+a b c) .
\end{aligned}
$$

Hence, the result follows.

---

### Example: 29

Prove that

$$
\left|\begin{array}{ccc}\frac{1}{a} & a^{2} & b c \\ \frac{1}{b} & b^{2} & c a \\ \frac{1}{c} & c^{2} & a b\end{array}\right|=0
$$

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
\frac{1}{a} & a^{2} & b c \\
\frac{1}{b} & b^{2} & c a \\
\frac{1}{c} & c^{2} & a b
\end{array}\right| \\
& =\frac{1}{a b c} \cdot\left|\begin{array}{ccc}
1 & a^{3} & a b c \\
1 & b^{3} & c b a \\
1 & c^{3} & a b c
\end{array}\right| \quad \text { [multiplying } R_{1}, R_{2}, R_{3} \text { by } a, b, c \\
& =\frac{1}{a b c} \cdot a b c \cdot\left|\begin{array}{ccc}
1 & a^{3} & 1 \\
1 & b^{3} & 1 \\
1 & c^{3} & 1
\end{array}\right| \\
& =(1 \times 0)=0 \quad\left[\because C_{1} \text { and } C_{3} \text { are identical }\right] .
\end{aligned}
$$

Hence, $\Delta=0$.

---

### Example: 30

Prove that

$$
\left|\begin{array}{ccc}
a^{2}+1 & a b & a c \\
a b & b^{2}+1 & b c \\
c a & c b & c^{2}+1
\end{array}\right|=\left(1+a^{2}+b^{2}+c^{2}\right) .
$$

[CBSE 2007, '08, '11C, '14]

#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\Delta=\left|\begin{array}{ccc}
a\left(a+\frac{1}{a}\right) & a b & a c \\
a b & \left(b+\frac{1}{b}\right) b & b c \\
c a & c b & \left(c+\frac{1}{c}\right) c
\end{array}\right|
$$

$$
=(a b c) \cdot\left|\begin{array}{ccc}
a+\frac{1}{a} & a & a \\
b & b+\frac{1}{b} & b \\
c & c & c+\frac{1}{c}
\end{array}\right|
$$

[taking $a, b, c$ common from $C_{1}, C_{2}, C_{3}$ respectively]

$$
=\frac{(a b c)}{(a b c)} \cdot\left|\begin{array}{ccc}
a^{2}+1 & a^{2} & a^{2} \\
b^{2} & b^{2}+1 & b^{2} \\
c^{2} & c^{2} & c^{2}+1
\end{array}\right|
$$

[applying $R_{1} \rightarrow a R_{1}, R_{2} \rightarrow b R_{2}, R_{3} \rightarrow c R_{3}$ and dividing the whole det. by $a b c$ ]

$$
=\left|\begin{array}{ccc}
1+a^{2}+b^{2}+c^{2} & 1+a^{2}+b^{2}+c^{2} & 1+a^{2}+b^{2}+c^{2} \\
b^{2} & b^{2}+1 & b^{2} \\
c^{2} & c^{2} & c^{2}+1
\end{array}\right|
$$

[by $R_{1} \rightarrow R_{1}+R_{2}+R_{3}$ ]

$$
=\left(1+a^{2}+b^{2}+c^{2}\right) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
b^{2} & b^{2}+1 & b^{2} \\
c^{2} & c^{2} & c^{2}+1
\end{array}\right|
$$

[taking out $\left(1+a^{2}+b^{2}+c^{2}\right)$ common from $R_{1}$ ]

$$
=\left(1+a^{2}+b^{2}+c^{2}\right) \cdot\left|\begin{array}{ccc}
1 & 0 & 0 \\
b^{2} & 1 & 0 \\
c^{2} & 0 & 1
\end{array}\right|
$$

[by $C_{2} \rightarrow C_{2}-C_{1}$ and $C_{3} \rightarrow C_{3}-C_{1}$]

$$
=\left(1+a^{2}+b^{2}+c^{2}\right) \cdot 1 \cdot\left|\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right|
$$

[expanded by $R_{1}$]

$$
=\left(1+a^{2}+b^{2}+c^{2}\right) \cdot 1 \cdot(1-0)=\left(1+a^{2}+b^{2}+c^{2}\right) .
$$

Hence, $\Delta=\left(1+a^{2}+b^{2}+c^{2}\right)$.

---

### Example: 31

Prove that

$$
\left|\begin{array}{ccc}
-b c & b^{2}+b c & c^{2}+b c \\
a^{2}+a c & -a c & c^{2}+a c \\
a^{2}+a b & b^{2}+a b & -a b
\end{array}\right|=(a b+b c+a c)^{3}
$$

[CBSE 2007]

#### Solution:

We have

$$
\left|\begin{array}{ccc}
-b c & b^{2}+b c & c^{2}+b c \\
a^{2}+a c & -a c & c^{2}+a c \\
a^{2}+a b & b^{2}+a b & -a b
\end{array}\right|=\frac{1}{a b c}\left|\begin{array}{ccc}
-a b c & a b^{2}+a b c & a c^{2}+a b c \\
a^{2} b+a b c & -a b c & c^{2} b+a b c \\
a^{2} c+a b c & b^{2} c+a b c & -a b c
\end{array}\right|
$$

[$R_{1} \rightarrow a R_{1}, R_{2} \rightarrow b R_{2}$ and $R_{3} \rightarrow c R_{3}$ and dividing the det. by $a b c$]

$$
=\left(\frac{a b c}{a b c}\right)\left|\begin{array}{ccc}
-b c & a b+a c & a c+a b \\
a b+b c & -a c & b c+a b \\
a c+b c & b c+a c & -a b
\end{array}\right|
$$

[taking out $a, b, c$ common from $C_{1}, C_{2}, C_{3}$ respectively]

$$
=\left|\begin{array}{ccc}
a b+b c+a c & a b+b c+a c & a b+b c+a c \\
a b+b c & -a c & b c+a b \\
a c+b c & b c+a c & -a b
\end{array}\right|
$$

[$R_{1} \rightarrow\left(R_{1}+R_{2}+R_{3}\right)$]

$$
=(a b+b c+a c) \cdot\left|\begin{array}{ccc}
1 & 1 & 1 \\
a b+b c & -a c & b c+a b \\
a c+b c & b c+a c & -a b
\end{array}\right|
$$

$$
=(a b+b c+a c) \cdot\left|\begin{array}{ccc}
0 & 0 & 1 \\
0 & -(a b+b c+a c) & b c+a b \\
(a b+b c+a c) & (a b+b c+a c) & -a b
\endV\right|
$$

[$C_{1} \rightarrow\left(C_{1}-C_{3}\right)$ and $C_{2} \rightarrow\left(C_{2}-C_{3}\right)$]

$$
=(a b+b c+a c)^{3} \quad\left[\text { expanding by } R_{1}\right] .
$$

---

### Example: 32

Prove that

$$
\left|\begin{array}{lll}
a^{2} & a^{2}-(b-c)^{2} & b c \\
b^{2} & b^{2}-(c-a)^{2} & c a \\
c^{2} & c^{2}-(a-b)^{2} & a b
\end{array}\right|=\left(a^{2}+b^{2}+c^{2}\right)(a-b)(b-c)(c-a)(a+b+c)
$$

[CBSE 2012C]

#### Solution:

Let the value of the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{lll}
a^{2} & a^{2}-(b-c)^{2} & b c \\
b^{2} & b^{2}-(c-a)^{2} & c a \\
c^{2} & c^{2}-(a-b)^{2} & a b
\end{array}\right| \\
& =\left|\begin{array}{lll}
a^{2} & -(b-c)^{2} & b c \\
b^{2} & -(c-a)^{2} & c a \\
c^{2} & -(a-b)^{2} & a b
\end{array}\right| \quad\left[\text { applying } C_{2} \rightarrow\left(C_{2}-C_{1}\right)\right] \\
& =(-1) \cdot\left|\begin{array}{lll}
a^{2} & (b-c)^{2} & b c \\
b^{2} & (c-a)^{2} & c a \\
c^{2} & (a-b)^{2} & a b
\end{array}\right| \\
& =(-1) \cdot\left|\begin{array}{lll}
a^{2} & b^{2}+c^{2}-2 b c & b c \\
b^{2} & c^{2}+a^{2}-2 c a & c a \\
c^{2} & a^{2}+b^{2}-2 a b & a b
\end{array}\right| \\
& =(-1) \cdot\left|\begin{array}{lll}
a^{2} & a^{2}+b^{2}+c^{2} & b c \\
b^{2} & a^{2}+b^{2}+c^{2} & c a \\
c^{2} & a^{2}+b^{2}+c^{2} & a b
\end{array}\right| \quad\left[C_{2} \rightarrow C_{2}+C_{1}+2 C_{3}\right]
\end{aligned}
$$

$$
\begin{aligned}
& =(-1)\left(a^{2}+b^{2}+c^{2}\right) \cdot\left|\begin{array}{lll}
a^{2} & 1 & b c \\
b^{2} & 1 & c a \\
c^{2} & 1 & a b
\end{array}\right| \\
& =(-1)\left(a^{2}+b^{2}+c^{2}\right) \cdot\left|\begin{array}{ccc}
a^{2} & 1 & b c \\
b^{2}-a^{2} & 0 & c a-b c \\
c^{2}-a^{2} & 0 & a b-b c
\end{array}\right| \\
& =(-1)\left(a^{2}+b^{2}+c^{2}\right) \cdot\left|\begin{array}{ccc}
a^{2} & 1 & b c \\
b^{2}-a^{2} & 0 & (a-b) c \\
c^{2}-a^{2} & 0 & (a-c) b
\end{array}\right| \\
& =(-1)\left(a^{2}+b^{2}+c^{2}\right)(b-a)(c-a) \cdot\left|\begin{array}{ccc}
a^{2} & 1 & b c \\
b+a & 0 & -c \\
c+a & 0 & -b
\end{array}\right|
\end{aligned}
$$

[taking out ( $b-a$ ) common from $R_{2}$ and ( $c-a$ ) common from $R_{3}$ ]

$$
\begin{aligned}
& =(-1)\left(a^{2}+b^{2}+c^{2}\right)(b-a)(c-a)(-1) \cdot\left|\begin{array}{ll}
b+a & -c \\
c+a & -b
\end{array}\right| \\
& =\left(a^{2}+b^{2}+c^{2}\right)(b-a)(c-a) \cdot(-1) \cdot\left|\begin{array}{cc}
b+a & c \\
c+a & b
\end{array}\right| \\
& =\left(a^{2}+b^{2}+c^{2}\right)(a-b)(c-a) \cdot\{b(b+a)-c(c+a)\} \\
& =\left(a^{2}+b^{2}+c^{2}\right)(a-b)(c-a) \cdot\left\{\left(b^{2}-c^{2}\right)+(a b-a c)\right\} \\
& =\left(a^{2}+b^{2}+c^{2}\right)(a-b)(c-a) \cdot\left\{\left(b^{2}-c^{2}\right)+a(b-c)\right\} \\
& =\left(a^{2}+b^{2}+c^{2}\right)(a-b)(b-c)(c-a)(a+b+c) .
\end{aligned}
$$

Hence, $\Delta=\left(a^{2}+b^{2}+c^{2}\right)(a-b)(b-c)(c-a)(a+b+c)$.

---

## TYPE: DETERMINANTS ON TRIGONOMETRY

### Example: 33

Prove that $\left|\begin{array}{ccc}\cos \alpha \cos \beta & \cos \alpha \sin \beta & -\sin \alpha \\ -\sin \beta & \cos \beta & 0 \\ \sin \alpha \cos \beta & \sin \alpha \sin \beta & \cos \alpha\end{array}\right|=1$.

---
#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
& \Delta=\left|\begin{array}{ccc}
\cos \alpha \cos \beta & \cos \alpha \sin \beta & -\sin \alpha \\
-\sin \beta & \cos \beta & 0 \\
\sin \alpha \cos \beta & \sin \alpha \sin \beta & \cos \alpha
\end{array}\right| \\
&=\frac{1}{\sin \alpha \cos \alpha} \cdot\left|\begin{array}{ccc}
\sin \alpha \cos \alpha \cos \beta & \sin \alpha \cos \alpha \sin \beta & -\sin ^{2} \alpha \\
-\sin \beta & \cos \beta & 0 \\
\sin \alpha \cos \alpha \cos \beta & \sin \alpha \cos \alpha \sin \beta & \cos ^{2} \alpha
\end{array}\right| \\
& \qquad \qquad \qquad \qquad \qquad {\left[R_{1} \rightarrow(\sin \alpha) R_{1}, R_{3} \rightarrow(\cos \alpha) R_{3} \text { and dividing } \Delta \text { by }(\sin \alpha \cos \alpha)\right] }
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{\sin \alpha \cos \alpha} \cdot\left|\begin{array}{ccc}
0 & 0 & -1 \\
-\sin \beta & \cos \beta & 0 \\
\sin \alpha \cos \alpha \cos \beta & \sin \alpha \cos \alpha \sin \beta & \cos ^{2} \alpha
\end{array}\right| \\
& \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad {\left[R_{1} \rightarrow\left(R_{1}-R_{3}\right)\right]} \\
& =\frac{1}{\sin \alpha \cos \alpha} \cdot(-1) \cdot\left|\begin{array}{cc}
-\sin \beta & \cos \beta \\
\sin \alpha \cos \alpha \cos \beta & \sin \alpha \cos \alpha \sin \beta
\end{array}\right| \\
& =\frac{(\sin \alpha \cos \alpha)}{(\sin \alpha \cos \alpha)} \cdot(-1) \cdot\left|\begin{array}{cc}
-\sin \beta & \cos \beta \\
\cos \beta & \sin \beta
\end{array}\right| \\
& \qquad \qquad \qquad \qquad \qquad \text { [taking } \sin \alpha \cos \alpha \text { common from } R_{2}\text{]} \\
& =(-1) \cdot\left[-\sin ^{2} \beta-\cos ^{2} \beta\right]=\left(\sin ^{2} \beta+\cos ^{2} \beta\right)=1 .
\end{aligned}
$$

Hence, $\Delta=1$.

---
### Example: 34

If $A+B+C=\pi$, prove that

$$
\left|\begin{array}{ccc}
\sin (A+B+C) & \sin (A+C) & \cos C \\
-\sin B & 0 & \tan C \\
\cos (A+B) & \tan (B+C) & 0
\end{array}\right|=0 .
$$

---
#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
\sin (A+B+C) & \sin (A+C) & \cos C \\
-\sin B & 0 & \tan C \\
\cos (A+B) & \tan (B+C) & 0
\end{array}\right| \\
& =\left|\begin{array}{ccc}
\sin \pi & \sin (\pi-B) & \cos C \\
-\sin B & 0 & \tan C \\
\cos (\pi-C) & \tan (\pi-A) & 0
\end{array}\right| \\
& =\left|\begin{array}{ccc}
0 & \sin B & \cos C \\
-\sin B & 0 & \tan A \\
-\cos C & -\tan A & 0
\end{array}\right|
\end{aligned}
$$

$$
\begin{aligned}
{[\because} & \sin \pi=0, \sin (\pi-B)=\sin B ; \cos (\pi-C)=-\cos C \text { and } \\
& \tan (\pi-A)=-\tan A]
\end{aligned}
$$

$$
\begin{aligned}
& =\sin B \cdot\left|\begin{array}{cc}
\sin B & \cos C \\
-\tan A & 0
\end{array}\right|-\cos C \cdot\left|\begin{array}{cc}
\sin B & \cos C \\
0 & \tan A
\end{array}\right| \\
& \qquad \qquad \qquad \qquad \qquad \qquad \qquad \qquad \left\{\text { expanded by } C_{1}\right\} \\
& =(\sin B \cdot \tan A \cos C)-(\sin B \tan A \cdot \cos C)=0 .
\end{aligned}
$$

Hence, $\Delta=0$.

---
### Example: 35

If $A+B+C=\pi$, show that

$$
\begin{aligned}
& \left|\begin{array}{ccc}
\sin ^{2} A & \sin A \cos A & \cos ^{2} A \\
\sin ^{2} B & \sin B \cos B & \cos ^{2} B \\
\sin ^{2} C & \sin C \cos C & \cos ^{2} C
\end{array}\right| \\
& =-\sin (A-B) \sin (B-C) \sin (C-A) .
\end{aligned}
$$

---
#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
1 & (1 / 2) \sin 2 A & (1 / 2)(1+\cos 2 A) \\
1 & (1 / 2) \sin 2 B & (1 / 2)(1+\cos 2 B) \\
1 & (1 / 2) \sin 2 C & (1 / 2)(1+\cos 2 C)
\end{array}\right| \quad\left[C_{1} \rightarrow C_{1}+C_{3}\right] \\
& =\frac{1}{4} \cdot\left|\begin{array}{ccc}
1 & \sin 2 A & 1+\cos 2 A \\
1 & \sin 2 B & 1+\cos 2 B \\
1 & \sin 2 C & 1+\cos 2 C
\end{array}\right| \\
& =\frac{1}{4} \cdot\left|\begin{array}{ccc}
1 & \sin 2 A & 1+\cos 2 A \\
0 & \sin 2 B-\sin 2 A & \cos 2 B-\cos 2 A \\
0 & \sin 2 C-\sin 2 A & \cos 2 C-\cos 2 A
\end{array}\right|\left\{\begin{array}{l}
R_{2} \rightarrow R_{2}-R_{1} \\
R_{3} \rightarrow R_{3}-R_{1}
\end{array}\right\} \\
& =\frac{1}{4} \cdot\left|\begin{array}{ccc}
1 & \sin 2 A & 1+\cos 2 A \\
0 & 2 \cos (A+B) \sin (B-A) & 2 \sin (A+B) \sin (A-B) \\
0 & 2 \cos (A+C) \sin (C-A) & 2 \sin (A+C) \sin (A-C)
\end{array}\right| \\
& =\sin (A-B) \sin (A-C) \cdot\left|\begin{array}{ccc}
1 & \sin 2 A & 1+\cos 2 A \\
0 & -\cos (A+B) & \sin (A+B) \\
0 & -\cos (A+C) & \sin (A+C)
\end{array}\right|
\end{aligned}
$$

> [taking $2 \sin (A-B)$ common from $R_{2}$ and $2 \sin (A-C)$ common from $R_{3}$]

$$
\begin{aligned}
& =\sin (A-B) \sin (A-C) \cdot \left\lvert\, \begin{array}{ccc}
1 & \sin 2 A & 1+\cos 2 \\
0 & -\cos (\pi-C) & \sin (\pi- \\
0 & -\cos (\pi-B) & \sin (\pi- \\
{[\because} & A+
\end{array}\right. \\
& =\sin (A-B) \sin (A-C) \cdot\left|\begin{array}{ccc}
1 & \sin 2 A & 1+\cos 2 A \\
0 & \cos C & \sin C \\
0 & \cos B & \sin B
\end{array}\right| \\
& =\sin (A-B) \sin (A-C)[\sin B \cos C-\cos B \sin C] \\
& =\sin (A-B) \sin (A-C) \sin (B-C) \\
& =-\sin (A-B) \sin (B-C) \sin (C-A) .
\end{aligned}
$$

Hence, $\Delta=-\sin (A-B) \sin (B-C) \sin (C-A)$.

---
### Example: 36

Prove that $\left|\begin{array}{ccc}\sin \alpha & \cos \alpha & \cos (\alpha+\delta) \\ \sin \beta & \cos \beta & \cos (\beta+\delta) \\ \sin \gamma & \cos \gamma & \cos (\gamma+\delta)\end{array}\right|=0$.

---
#### Solution:

Let the given determinant be $\Delta$.
Then, applying $C_{3} \rightarrow C_{3}+(\sin \delta) C_{1}-(\cos \delta) C_{2}$, we get

$$
\Delta=\left|\begin{array}{ccc}
\sin \alpha & \cos \alpha & 0 \\
\sin \beta & \cos \beta & 0 \\
\sin \gamma & \cos \gamma & 0
\end{array}\right|=0 \quad\left[\because \quad \text { each element in } C_{3} \text { is } 0\right]
$$

---
## TYPE: EQUALITY OF TWO DETERMINANTS

### Example: 37

Without expanding prove that

$$
\left|\begin{array}{ccc}
a+b x & c+d x & p+q x \\
a x+b & c x+d & p x+q \\
u & v & w
\end{array}\right|=\left(1-x^{2}\right)\left|\begin{array}{ccc}
a & c & p \\
b & d & q \\
u & v & w
\end{array}\right| .
$$

---
#### Solution:

We have

$$
\begin{aligned}
\text { LHS } & =\left|\begin{array}{ccc}
a+b x & c+d x & p+q x \\
a x+b & c x+d & p x+q \\
u & v & w
\end{array}\right| \\
& \left.=\left|\begin{array}{ccc}
a-a x^{2} & c-c x^{2} & p-p x^{2} \\
a x+b & c x+d & p x+q \\
u & v & w
\end{array}\right| \quad \text { [applying } R_{1} \rightarrow R_{1}-x R_{2}\right] \\
& =\left|\begin{array}{ccc}
a\left(1-x^{2}\right) & c\left(1-x^{2}\right) & p\left(1-x^{2}\right) \\
a x+b & c x+d & p x+q \\
u & v & w
\end{array}\right| \\
& =\left(1-x^{2}\right)\left|\begin{array}{ccc}
a & c & p \\
a x+b & c x+d & p x+q \\
u & v & w
\end{array}\right|
\end{aligned}
$$

> [taking out $\left(1-x^{2}\right)$ common from $R_{1}$]

$$
\begin{aligned}
& =\left(1-x^{2}\right)\left|\begin{array}{ccc}
a & c & p \\
b & d & q \\
u & v & w
\end{array}\right| \quad\left[\text { applying } R_{2} \rightarrow R_{2}-x R_{1}\right] \\
& =\text { RHS }
\end{aligned}
$$

Hence, **LHS** = **RHS**.

---
### Example: 38

Without expanding the determinant, prove that

$$
\left|\begin{array}{ccc}
a & a^{2} & b c \\
b & b^{2} & c a \\
c & c^{2} & a b
\end{array}\right|=\left|\begin{array}{ccc}
1 & a^{2} & a^{3} \\
1 & b^{2} & b^{3} \\
1 & c^{2} & c^{3}
\end{array}\right| .
$$

[CBSE 2001C]

---
#### Solution:

We have

$$
\text { LHS }=\left|\begin{array}{ccc}
a & a^{2} & b c \\
b & b^{2} & c a \\
c & c^{2} & a b
\end{array}\right|
$$

$$
=\frac{1}{a b c} \cdot\left|\begin{array}{lll}
a^{2} & a^{2} & a b c \\
b^{2} & b^{2} & a b c \\
c^{2} & c^{2} & a b c
\end{array}\right|
$$

> $\left[R_{1} \rightarrow a R_{1}, R_{2} \rightarrow b R_{2}, R_{3} \rightarrow c R_{3} \text { and dividing the whole det. by } a b c\right]$

$$
\begin{aligned}
& \left.=\frac{1}{a b c} \cdot a b c \cdot\left|\begin{array}{ccc}
a^{2} & a^{3} & 1 \\
b^{2} & b^{3} & 1 \\
c^{2} & c^{3} & 1
\end{array}\right| \quad \text { [taking } a b c \text { common from } C_{3}\right] \\
& =\left|\begin{array}{ccc}
1 & a^{2} & a^{3} \\
1 & b^{2} & b^{3} \\
1 & c^{2} & c^{3}
\end{array}\right| \quad\left[C_{2} \leftrightarrow C_{3} \text { and } C_{1} \leftrightarrow C_{2}\right] \\
& =\text { RHS. }
\end{aligned}
$$

Hence, **LHS** = **RHS**.

---
### Example: 39

Using the properties of determinants, prove that

$$
\left|\begin{array}{lll}
a+b & b+c & c+a \\
b+c & c+a & a+b \\
c+a & a+b & b+c
\end{array}\right|=2\left|\begin{array}{lll}
a & b & c \\
b & c & a \\
c & a & b
\end{array}\right|
$$

[CBSE 2007, '10C]

---
#### Solution:

We have

$$
\begin{aligned}
\text { LHS } & =\left|\begin{array}{ccc}
a+b & b+c & c+a \\
b+c & c+a & a+b \\
c+a & a+b & b+c
\end{array}\right| \\
& \left.=\left|\begin{array}{ccc}
-2 c & b+c & c+a \\
-2 a & c+a & a+b \\
-2 b & a+b & b+c
\end{array}\right| \quad \text { [applying } C_{1} \rightarrow C_{1}-\left(C_{2}+C_{3}\right)\right] \\
& \left.=(-2)\left|\begin{array}{lll}
c & b+c & c+a \\
a & c+a & a+b \\
b & a+b & b+c
\end{array}\right| \quad \text { [taking out }(-2) \text { common from } C_{1}\right] \\
& \left.=(-2) \cdot\left|\begin{array}{lll}
c & b & a \\
a & c & b \\
b & a & c
\end{array}\right| \quad \text { [applying } C_{2} \rightarrow C_{2}-C_{1} \text { and } C_{3} \rightarrow C_{3}-C_{1}\right] \\
& \left.=2\left|\begin{array}{lll}
a & b & c \\
b & c & a \\
c & a & b
\end{array}\right| \quad \text { [applying } C_{1} \leftrightarrow C_{3}\right] \\
& =\text { RHS. }
\end{aligned}
$$

Hence, **LHS** = **RHS**.

---
### Example: 40

Show that

$$
\left|\begin{array}{lll}
b+c & c+a & a+b \\
q+r & r+p & p+q \\
y+z & z+x & x+y
\end{array}\right|=2\left|\begin{array}{lll}
a & b & c \\
p & q & r \\
x & y & z
\end{array}\right| .
$$

[CBSE 2008, '10C, '12C, '14]

---
#### Solution:

We have

$$
\begin{aligned}
\text { LHS } & =\left|\begin{array}{lll}
b+c & c+a & a+b \\
q+r & r+p & p+q \\
y+z & z+x & x+y
\end{array}\right| \\
& =2\left|\begin{array}{lll}
a+b+c & c+a & a+b \\
p+q+r & r+p & p+q \\
x+y+z & z+x & x+y
\end{array}\right|
\end{aligned}
$$

> [applying $C_{1} \rightarrow\left(C_{1}+C_{2}+C_{3}\right)$ and taking out 2 common from $C_{1}$]

$$
\begin{aligned}
& =2\left|\begin{array}{lll}
a+b+c & -b & -c \\
p+q+r & -q & -r \\
x+y+z & -y & -z
\end{array}\right| \quad\left[C_{2} \rightarrow\left(C_{2}-C_{1}\right), C_{3} \rightarrow\left(C_{3}-C_{1}\right)\right] \\
& =2(-1)(-1) \cdot\left|\begin{array}{lll}
a+b+c & b & c \\
p+q+r & q & r \\
x+y+z & y & z
\end{array}\right|
\end{aligned}
$$

> [taking out (-1) common from each one of $C_{2}$ and $C_{3}$]

$$
=2\left|\begin{array}{lll}
a & b & c \\
p & q & r \\
x & y & z
\end{array}\right|=\text { RHS } \quad\left[\text { applying } C_{1} \rightarrow C_{1}-\left(C_{2}+C_{3}\right)\right]
$$

Hence, **LHS** = **RHS**.

---
### Example: 41

Show that $\Delta=\Delta_{1}$, where

$$
\Delta=\left|\begin{array}{ccc}
A x & x^{2} & 1 \\
B y & y^{2} & 1 \\
C z & z^{2} & 1
\end{array}\right| \text { and } \Delta_{1}=\left|\begin{array}{ccc}
A & B & C \\
x & y & z \\
z y & z x & x y
\end{array}\right| .
$$

[CBSE 2014C]

---
#### Solution:

We have

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
A x & x^{2} & 1 \\
B y & y^{2} & 1 \\
C z & z^{2} & 1
\end{array}\right| \\
& =\left|\begin{array}{ccc}
A x & B y & C z \\
x^{2} & y^{2} & z^{2} \\
1 & 1 & 1
\end{array}\right| \quad \text { [interchanging the rows and columns] }
\end{aligned}
$$

$$
\begin{aligned}
& =(x y z)\left|\begin{array}{ccc}
A & B & C \\
x & y & z \\
\frac{1}{x} & \frac{1}{y} & \frac{1}{z}
\end{array}\right| \\
& \quad \text { [applying } C_{1} \rightarrow \frac{1}{x} C_{1}, C_{2} \rightarrow \frac{1}{y} C_{2}, C_{3} \rightarrow \frac{1}{z} C_{3} \text { and } \\
& \quad \text { multiplying the whole determinant by } x y z] \\
& =\frac{(x y z)}{(x y z)} \cdot\left|\begin{array}{ccc}
A & B & C \\
x & y & z \\
y z & z x & x y
\end{array}\right|
\end{aligned}
$$

> [applying $R_{3} \rightarrow(x y z) R_{3}$ and dividing the whole determinant by $x y z$]

$$
=\left|\begin{array}{ccc}
A & B & C \\
x & y & z \\
z y & z x & x y
\end{array}\right|=\Delta_{1} .
$$

Hence, $\Delta=\Delta_{1}$.

---
### Example: 42

If $\Delta_{1}=\left|\begin{array}{lll}a & b & c \\ x & y & z \\ p & q & r\end{array}\right|$ and $\Delta_{2}=\left|\begin{array}{ccc}q & -b & y \\ -p & a & -x \\ r & -c & z\end{array}\right|$ then without expanding $\Delta_{1}$ and $\Delta_{2}$, prove that $\Delta_{1}+\Delta_{2}=0$.

---
#### Solution:

We have

$$
\begin{aligned}
\Delta_{2} & =\left|\begin{array}{ccc}
q & -b & y \\
-p & a & -x \\
r & -c & z
\end{array}\right| \\
& =(-1) \cdot\left|\begin{array}{ccc}
q & -b & y \\
p & -a & x \\
r & -c & z
\end{array}\right| \quad \text { [taking (-1) common from } R_{2} \text { ] } \\
& =(-1)(-1) \cdot\left|\begin{array}{ccc}
q & b & y \\
p & a & x \\
r & c & z
\end{array}\right| \quad \text { [taking (-1) common from } C_{2} \text { ] } \\
& =\left|\begin{array}{ccc}
q & b & y \\
p & a & x \\
r & c & z
\end{array}\right|=\left|\begin{array}{ccc}
q & p & r \\
b & a & c \\
y & x & z
\end{array}\right| \quad \text { [interchanging rows and columns] } \\
& =(-1)\left|\begin{array}{ccc}
p & q & r \\
a & b & c \\
x & y & z
\end{array}\right| \quad \text { [applying } C_{1} \leftrightarrow C_{2} \text { ] }
\end{aligned}
$$

$$
\begin{aligned}
&=(-1)(-1) \cdot\left|\begin{array}{lll}
a & b & c \\
p & q & r \\
x & y & z
\end{array}\right| \quad\left[\text { applying } R_{1} \leftrightarrow R_{2}\right] \\
&=\left|\begin{array}{lll}
a & b & c \\
p & q & r \\
x & y & z
\end{array}\right| \\
&=(-1) \cdot\left|\begin{array}{lll}
a & b & c \\
x & y & z \\
p & q & r
\end{array}\right|=-\Delta_{1} \quad\left[\text { applying } R_{2} \leftrightarrow R_{3}\right] \text { . }
\end{aligned}
$$

Thus, $\Delta_{2}=-\Delta_{1}$ and hence $\Delta_{1}+\Delta_{2}=0$.

---
## TYPE: EQUATIONS OF DETERMINANTS

### Example: 43

Solve for $x$:

$$
\left|\begin{array}{ccc}
a+x & a-x & a-x \\
a-x & a+x & a-x \\
a-x & a-x & a+x
\end{array}\right|=0
$$

[CBSE 2004, '05, '11]

---
#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a+x & a-x & a-x \\
a-x & a+x & a-x \\
a-x & a-x & a+x
\end{array}\right| \\
& =\left|\begin{array}{ccc}
3 a-x & a-x & a-x \\
3 a-x & a+x & a-x \\
3 a-x & a-x & a+x
\end{array}\right| \quad\left[C_{1} \rightarrow\left(C_{1}+C_{2}+C_{3}\right)\right] \\
& =(3 a-x) \cdot\left|\begin{array}{ccc}
1 & a-x & a-x \\
1 & a+x & a-x \\
1 & a-x & a+x
\end{array}\right| \quad\left[\text { taking }(3 a-x) \text { common from } C_{1}\right] \\
& =(3 a-x) \cdot\left|\begin{array}{ccc}
1 & a-x & a-x \\
0 & 2 x & 0 \\
0 & 0 & 2 x
\end{array}\right| \quad\left[R_{2} \rightarrow\left(R_{2}-R_{1}\right) \text { and } R_{3} \rightarrow\left(R_{3}-R_{1}\right)\right] \\
& =(3 a-x) \cdot 1 \cdot\left|\begin{array}{cc}
2 x & 0 \\
0 & 2 x
\end{array}\right| \quad\left[\text { expanding by } C_{1}\right] \\
& =4(3 a-x) x^{2} . \\
\therefore & \Delta=0 \Leftrightarrow 4(3 a-x) x^{2}=0 \\
\Leftrightarrow x=0 & \text { or } x=3 a .
\end{aligned}
$$

Hence, solution set $=\{0,3 a\}$.

---
### Example: 44

Solve $\left|\begin{array}{lll}x-2 & 2 x-3 & 3 x-4 \\ x-4 & 2 x-9 & 3 x-16 \\ x-8 & 2 x-27 & 3 x-64\end{array}\right|=0$.
[CBSE 2011]

---
#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
x-2 & 2 x-3 & 3 x-4 \\
x-4 & 2 x-9 & 3 x-16 \\
x-8 & 2 x-27 & 3 x-64
\end{array}\right| \\
& =\left|\begin{array}{crr}
x-2 & 1 & 2 \\
x-4 & -1 & -4 \\
x-8 & -11 & -40
\end{array}\right| \quad\left[C_{2} \rightarrow\left(C_{2}-2 C_{1}\right), C_{3} \rightarrow\left(C_{3}-3 C_{1}\right)\right] \\
& =\left|\begin{array}{crr}
x-2 & 1 & 2 \\
-2 & -2 & -6 \\
-6 & -12 & -42
\end{array}\right| \quad\left[R_{2} \rightarrow\left(R_{2}-R_{1}\right), R_{3} \rightarrow\left(R_{3}-R_{1}\right)\right] \\
& =(-2) \cdot(-6) \cdot\left|\begin{array}{rrr}
x-2 & 1 & 2 \\
1 & 1 & 3 \\
1 & 2 & 7
\end{array}\right| \\
& =12 \cdot\left|\begin{array}{crr}
x-3 & 1 & 2 \\
0 & 1 & 3 \\
-1 & 2 & 7
\end{array}\right| \quad\left[C_{1} \rightarrow\left(C_{1}-C_{2}\right)\right] \\
& =12 \cdot[(x-3)(7-6)-1 \cdot(3-2)] \\
& =12 \cdot(x-4) . \\
\therefore \quad \Delta & =0 \Leftrightarrow 12(x-4)=0 \Leftrightarrow x=4 .
\end{aligned}
$$

Hence, solution set $=\{4\}$.

---
### Example: 45

If $a+b+c=0$ and $\left|\begin{array}{ccc}a-x & c & b \\ c & b-x & a \\ b & a & c-x\end{array}\right|=0$ then show that

$$
x=0 \text { or } x=\sqrt{(3 / 2)\left(a^{2}+b^{2}+c^{2}\right)} .
$$

---
#### Solution:

Let the given determinant be $\Delta$. Then,

$$
\begin{aligned}
\Delta & =\left|\begin{array}{ccc}
a+b+c-x & c & b \\
a+b+c-x & b-x & a \\
a+b+c-x & a & c-x
\end{array}\right| \quad\left[C_{1} \rightarrow\left(C_{1}+C_{2}+C_{3}\right)\right] \\
& =(a+b+c-x)\left|\begin{array}{ccc}
1 & c & b \\
1 & b-x & a \\
1 & a & c-x
\end{array}\right| \\
& =(a+b+c-x)\left|\begin{array}{ccc}
1 & c & b \\
0 & b-x-c & a-b \\
0 & a-c & c-x-b
\end{array}\right| \\
& \qquad \qquad \qquad {\left[R_{2} \rightarrow\left(R_{2}-R_{1}\right) \text { and } R_{3} \rightarrow\left(R_{3}-R_{1}\right)\right]}
\end{aligned}
$$

$$
\begin{aligned}
& \quad \begin{array}{c}
=(a+b+c-x)[(b-x-c)(c-x-b)-(a-c)(a-b)] \\
=(a+b+c-x)\left[x^{2}-\left(a^{2}+b^{2}+c^{2}-a b-b c-c a\right)\right] . \\
\text { Now, } \Delta=0 \Leftrightarrow(a+b+c-x)\left[x^{2}-\left(a^{2}+b^{2}+c^{2}-a b-b c-c a\right)\right]=0 \\
\Leftrightarrow x=a+b+c \text { or } x= \pm \sqrt{\left(a^{2}+b^{2}+c^{2}-a b-b c-c a\right)} \\
\Leftrightarrow x=0 \text { or } x= \pm \sqrt{(3 / 2)\left(a^{2}+b^{2}+c^{2}\right)} \\
\Leftrightarrow \quad a+b+c=0 \Leftrightarrow\left(a^{2}+b^{2}+c^{2}\right)=-2(a b+b c+c a) \\
\left.\Leftrightarrow(a b+b c+c a)=-(1 / 2)\left(a^{2}+b^{2}+c^{2}\right)\right] .
\end{array}
\end{aligned}
$$

---