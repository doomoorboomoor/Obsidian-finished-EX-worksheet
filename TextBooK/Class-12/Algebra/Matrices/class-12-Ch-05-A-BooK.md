## 5. Matrices

**Matrix**: A rectangular array of $mn$ numbers in the form of $m$ horizontal lines (called **rows**) and $n$ vertical lines (called **columns**) is called a **matrix** of order $m$ by $n$, written as an $m \times n$ matrix.

Such an array is enclosed by **[ ]** or **( )**.

Each of the $mn$ numbers constituting the matrix is called an **element** or an **entry** of the matrix.

Usually, we denote a matrix by a capital letter.
The plural of **matrix** is **matrices**.

- **Example (i):** $A=\left[\begin{array}{rrr}3 & 5 & -4 \\ 0 & 1 & 9\end{array}\right]$ is a matrix, having 2 rows and 3 columns. Its order is $2 \times 3$ and it has 6 elements.
- **Example (ii):** $B=\left[\begin{array}{rrrr}9 & 4 & \sqrt{2} & -1 \\ 1 & 8 & -3 & 2 \\ 6 & 0 & 5 & 7\end{array}\right]$ is a matrix, having 3 rows and 4 columns. Its order is $3 \times 4$ and it has 12 elements.

---

## How to Describe a Matrix

In order to locate the position of a particular element of a matrix, we have to specify the number of the row and that of the column in which the element occurs.

An element occurring in the **$i$th row** and **$j$th column** of a matrix $A$ will be called the **$(i, j)$th element** of $A$, to be denoted by $a_{i j}$.

In general, an $m \times n$ matrix $A$ may be written as

$$
A=\left[\begin{array}{ccccc}
a_{11} & a_{12} & a_{13} & \ldots & a_{1 n} \\
a_{21} & a_{22} & a_{23} & \ldots & a_{2 n} \\
\ldots & \ldots & \ldots & \ldots & \ldots \\
a_{i 1} & a_{i 2} & a_{i 3} & \ldots & a_{i n} \\
\ldots & \ldots & \ldots & \ldots & \ldots \\
a_{m 1} & a_{m 2} & a_{m 3} & \ldots & a_{m n}
\end{array}\right]=\left[a_{i j}\right]_{m \times n} .
$$

---

### Example 1:

Consider the matrix $A=\left[\begin{array}{rrr}3 & -2 & 5 \\ 6 & 9 & 1\end{array}\right]$.

Clearly, the element in the 1st row and 2nd column is -2.
So, we write $a_{12}=-2$.
Similarly, $a_{11}=3 ; a_{12}=-2 ; a_{13}=5 ; a_{21}=6 ; a_{22}=9$ and $a_{23}=1$.

---

### Example 2:

Construct a $3 \times 2$ matrix whose elements are given by $a_{i j}=(i+2 j)$.

#### Solution:

A $3 \times 2$ matrix has 3 rows and 2 columns.

In general, a $3 \times 2$ matrix is given by

$$
A=\left[\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22} \\
a_{31} & a_{32}
\end{array}\right]_{3 \times 2}
$$

Thus $a_{i j}=(i+2 j)$ for $i=1,2,3$ and $j=1,2$.

$$
\begin{aligned}
& \therefore \quad a_{11}=(1+2 \times 1)=3 ; a_{12}=(1+2 \times 2)=5 ; \\
& \qquad a_{21}=(2+2 \times 1)=4 ; a_{22}=(2+2 \times 2)=6 ; \\
& \qquad a_{31}=(3+2 \times 1)=5 ; a_{32}=(3+2 \times 2)=7 . \\
& \text { Hence, } A=\left[\begin{array}{ll}
3 & 5 \\
4 & 6 \\
5 & 7
\end{array}\right]_{3 \times 2} .
\end{aligned}
$$

---

### Example 3:

Construct a $2 \times 3$ matrix whose elements are given by $a_{i j}=\frac{1}{2}|5 i-3 j|$.

#### Solution:

A $2 \times 3$ matrix has 2 rows and 3 columns.
In general, a $2 \times 3$ matrix is given by

$$
A=\left[\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23}
\end{array}\right]_{3 \times 2}
$$

Thus, $a_{i j}=\frac{1}{2}|5 i-3 j|$ where $i=1,2$ and $j=1,2,3$.

$$
\begin{aligned}
\therefore \quad & a_{11}=\frac{1}{2}|5 \times 1-3 \times 1|=\frac{1}{2} \cdot|2|=\frac{1}{2} \times 2=1 ; \\
& a_{12}=\frac{1}{2}|5 \times 1-3 \times 2|=\frac{1}{2} \cdot|5-6|=\frac{1}{2} \cdot|-1|=\frac{1}{2} \times 1=\frac{1}{2} ; \\
& a_{13}=\frac{1}{2}|5 \times 1-3 \times 3|=\frac{1}{2} \cdot|5-9|=\frac{1}{2} \cdot|-4|=\frac{1}{2} \times 4=2 ; \\
& a_{21}=\frac{1}{2}|5 \times 2-3 \times 1|=\frac{1}{2} \cdot|10-3|=\frac{1}{2} \cdot|7|=\frac{1}{2} \times 7=\frac{7}{2} ; \\
& a_{22}=\frac{1}{2}|5 \times 2-3 \times 2|=\frac{1}{2} \cdot|10-6|=\frac{1}{2} \cdot|4|=\frac{1}{2} \times 4=2 ; \\
& a_{23}=\frac{1}{2}|5 \times 2-3 \times 3|=\frac{1}{2} \cdot|10-9|=\frac{1}{2} \cdot|1|=\frac{1}{2} \times 1=\frac{1}{2} .
\end{aligned}
$$

Hence, $A=\left[\begin{array}{ccc}1 & \frac{1}{2} & 2 \\ \frac{7}{2} & 2 & \frac{1}{2}\end{array}\right]$.

---

### Example 4:

If a matrix has 12 elements, what are the possible orders it can have?

#### Solution:

We know that a matrix of order $m \times n$ has $m n$ elements.
Hence, all possible orders of a matrix having 12 elements are $(12 \times 1)$, $(1 \times 12)$, $(6 \times 2)$, $(2 \times 6)$, $(4 \times 3)$ and $(3 \times 4)$.

---
