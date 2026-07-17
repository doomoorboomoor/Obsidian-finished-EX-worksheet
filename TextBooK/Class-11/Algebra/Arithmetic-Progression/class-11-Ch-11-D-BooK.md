## Arithmetic Mean

If $a, A, b$ are in an Arithmetic Progression (AP), then we say that **A** is the **arithmetic mean (AM)** between $a$ and $b$.

---

## Insertion of a Single Arithmetic Mean Between a and b

Let $a$ and $b$ be two given numbers and let $A$ be the arithmetic mean between $a$ and $b$. Then, $a, A, b$ are in AP.

$$
\begin{aligned}
& \Rightarrow \quad A-a=b-A \\
& \Rightarrow \quad 2 A=a+b \\
& \Rightarrow A=\frac{a+b}{2}
\end{aligned}
$$

Hence, the **arithmetic mean** between $a$ and $b$ is $\frac{a+b}{2}$.

### Example 1:

Find the arithmetic mean between:
1.  14 and -6
2.  $(a-b)$ and $(a+b)$

#### Solution:

1.  Arithmetic mean between 14 and -6:
    $$
    =\frac{14+(-6)}{2}=\frac{8}{2}=4
    $$

2.  Arithmetic mean between $(a-b)$ and $(a+b)$:
    $$
    =\frac{(a-b)+(a+b)}{2}=\frac{2 a}{2}=a
    $$

---

### Example 2:

If $\left(\frac{a^{n}+b^{n}}{a^{n-1}+b^{n-1}}\right)$ is the AM between $a$ and $b$, then find the value of $n$.

#### Solution:

We know that the AM between $a$ and $b$ is $\frac{(a+b)}{2}$.

Given that $\left(\frac{a^{n}+b^{n}}{a^{n-1}+b^{n-1}}\right)$ is the AM between $a$ and $b$, we have:

$$
\frac{a^{n}+b^{n}}{a^{n-1}+b^{n-1}}=\frac{a+b}{2}
$$

$$
\begin{aligned}
& \Rightarrow \quad 2 a^{n}+2 b^{n}=a^{n}+a^{n-1} b+b^{n-1} a+b^{n} \\
& \Rightarrow \quad a^{n}+b^{n}=a^{n-1} b+b^{n-1} a \\
& \Rightarrow \quad a^{n}-a^{n-1} b=b^{n-1} a-b^{n} \\
& \Rightarrow \quad a^{n-1}(a-b)=b^{n-1}(a-b) \\
& \Rightarrow \quad a^{n-1}=b^{n-1} \\
& \Rightarrow \quad\left(\frac{a}{b}\right)^{n-1}=1=\left(\frac{a}{b}\right)^{0} \\
& \Rightarrow n-1=0 \\
& \Rightarrow n=1
\end{aligned}
$$

Hence, the required value of **n is 1**.

---

## n Arithmetic Means Between a and b

If $a, A_{1}, A_{2}, \ldots, A_{n}, b$ are in AP, then we say that $A_{1}, A_{2}, \ldots, A_{n}$ are the **n arithmetic means** between $a$ and $b$.

---

## Insertion of n Arithmetic Means Between a and b

Let $a$ and $b$ be two given numbers and let $A_{1}, A_{2}, \ldots, A_{n}$ be the $n$ arithmetic means between $a$ and $b$. Then, $a, A_{1}, A_{2}, \ldots, A_{n}, b$ are in AP.

In this AP, we have:
- **first term** = $a$
- **last term** = $b$
- **number of terms** = $(n+2)$

Let the common difference be $d$. Then,

$$
\begin{align*}
& b=T_{n+2} \Rightarrow b=a+(n+2-1) d \\
& \Rightarrow d=\frac{b-a}{n+1}
\end{align*}
$$

Therefore, the arithmetic means are:
$$
\begin{align*}
& A_{1}=(a+d) \\
& A_{2}=(a+2 d) \\
& A_{3}=(a+3 d) \\
& \ldots \\
& A_{n}=(a+n d)
\end{align*}
$$

Substituting the value of $d$:
$$
A_{1}=\left\{a+\frac{(b-a)}{(n+1)}\right\}, A_{2}=\left\{a+\frac{2(b-a)}{(n+1)}\right\}, \ldots, A_{n}=\left\{a+\frac{n(b-a)}{(n+1)}\right\}
$$

These are the required $n$ arithmetic means between $a$ and $b$.

### Example 3:

Insert six arithmetic means between 15 and -13.

#### Solution:

Let $A_{1}, A_{2}, A_{3}, A_{4}, A_{5}, A_{6}$ be the six arithmetic means between 15 and -13. Then, $15, A_{1}, A_{2}, A_{3}, A_{4}, A_{5}, A_{6}, -13$ are in AP.

Here, $a=15$, $b=-13$, and $n=6$. The common difference $d$ is:
$$
d=\frac{(b-a)}{(n+1)}=\frac{(-13-15)}{(6+1)}=\frac{-28}{7}=-4
$$

Therefore:
- $A_{1}=(15+d)=(15-4)=11$
- $A_{2}=(15+2 d)=(15-8)=7$
- $A_{3}=(15+3 d)=(15-12)=3$
- $A_{4}=(15+4 d)=(15-16)=-1$
- $A_{5}=(15+5 d)=(15-20)=-5$
- $A_{6}=(15+6 d)=(15-24)=-9$

Hence, the required six AMs between 15 and -13 are **11, 7, 3, -1, -5, and -9**.

---

### Example 4:

If $m$ arithmetic means are inserted between 1 and 31 so that the ratio of the 7th and $(m-1)$th means is $5:9$, find the value of $m$.

#### Solution:

Let $A_{1}, A_{2}, \ldots, A_{m}$ be the $m$ arithmetic means between 1 and 31. Then, $1, A_{1}, A_{2}, \ldots, A_{m}, 31$ are in AP.

Here, $a=1$, $b=31$. The common difference $d$ is:
$$
d=\frac{(b-a)}{(m+1)}=\frac{(31-1)}{(m+1)}=\frac{30}{m+1}
$$

The 7th mean is $A_{7}$:
$$
A_{7} = T_{8} = a+7d = 1+\frac{7 \times 30}{m+1} = \frac{m+1+210}{m+1} = \frac{m+211}{m+1}
$$

The $(m-1)$th mean is $A_{m-1}$:
$$
A_{m-1} = T_{m} = a+(m-1)d = 1+\frac{(m-1) \times 30}{m+1} = \frac{m+1+30m-30}{m+1} = \frac{31m-29}{m+1}
$$

Given the ratio $\frac{A_{7}}{A_{m-1}}=\frac{5}{9}$:
$$
\begin{aligned}
& \Rightarrow \frac{(m+211)}{(m+1)} \times \frac{(m+1)}{(31 m-29)}=\frac{5}{9} \\
& \Rightarrow \frac{(m+211)}{(31 m-29)}=\frac{5}{9} \\
& \Rightarrow 9(m+211) = 5(31m-29) \\
& \Rightarrow 9m+1899=155m-145 \\
& \Rightarrow 146m=2044 \\
& \Rightarrow m=\frac{2044}{146}=14
\end{aligned}
$$

Hence, **m = 14**.

---

### Example 5:

If $x, y, z$ are in AP and $A_{1}$ is the AM between $x$ and $y$, while $A_{2}$ is the AM between $y$ and $z$, then prove that the AM between $A_{1}$ and $A_{2}$ is $y$.

#### Solution:

Since $x, y, z$ are in AP, we have:
$$
x+z=2y \quad \cdots(i)
$$

Since $A_{1}$ is the AM between $x$ and $y$, we have:
$$
A_{1}=\frac{x+y}{2}
$$

Since $A_{2}$ is the AM between $y$ and $z$, we have:
$$
A_{2}=\frac{y+z}{2}
$$

The AM between $A_{1}$ and $A_{2}$ is:
$$
\begin{aligned}
\frac{A_{1}+A_{2}}{2} &= \frac{1}{2}\left(\frac{x+y}{2}+\frac{y+z}{2}\right) \\
&= \frac{1}{4}(x+y+y+z) \\
&= \frac{x+2y+z}{4}
\end{aligned}
$$

Using (i), we substitute $x+z = 2y$:
$$
\frac{2y+2y}{4} = \frac{4y}{4} = y
$$

Hence, the AM between $A_{1}$ and $A_{2}$ is $y$.

---

### Example 6:

If the AM between the pth and qth terms of an AP is equal to the AM between its rth and sth terms, then prove that $p+q=r+s$.

#### Solution:

Let $a$ be the first term and $d$ be the common difference of the given AP.

The AM between the pth and qth terms is $\frac{1}{2}(T_p + T_q)$.
The AM between the rth and sth terms is $\frac{1}{2}(T_r + T_s)$.

Given that these are equal:
$$
\begin{aligned}
& \frac{1}{2}\left(T_{p}+T_{q}\right)=\frac{1}{2}\left(T_{r}+T_{s}\right) \\
& \Rightarrow T_{p}+T_{q}=T_{r}+T_{s} \\
& \Rightarrow \{a+(p-1) d\}+\{a+(q-1) d\}=\{a+(r-1) d\}+\{a+(s-1) d\} \\
& \Rightarrow 2 a+(p+q-2) d=2 a+(r+s-2) d \\
& \Rightarrow (p+q-2) d=(r+s-2) d \\
& \Rightarrow p+q-2=r+s-2 \\
& \Rightarrow p+q=r+s
\end{aligned}
$$

Hence, proved.

---

### Example 7:

The $n$ arithmetic means between 20 and 80 are such that the first mean : last mean = 1 : 3. Find the value of $n$.

#### Solution:

Let $A_{1}, A_{2}, \ldots, A_{n}$ be $n$ AMs between 20 and 80. Then, $20, A_{1}, A_{2}, \ldots, A_{n}, 80$ are in AP.

Let their common difference be $d$. The last term is $T_{n+2} = 80$.
$$
\begin{aligned}
& T_{n+2}=80 \\
& \Rightarrow 20+(n+2-1) d=80 \\
& \Rightarrow (n+1)d = 60 \\
& \Rightarrow d=\frac{60}{n+1}
\end{aligned}
$$

First mean, $A_{1} = T_{2} = 20+d$:
$$
A_1 = 20+\frac{60}{n+1} = \frac{20(n+1)+60}{n+1} = \frac{20n+80}{n+1}
$$

Last mean, $A_{n} = T_{n+1} = 20 + nd$:
$$
A_n = 20+\frac{n \times 60}{n+1} = \frac{20(n+1)+60n}{n+1} = \frac{80n+20}{n+1}
$$

Given the ratio $\frac{A_{1}}{A_{n}}=\frac{1}{3}$:
$$
\begin{aligned}
& \Rightarrow \frac{(20 n+80)}{(n+1)} \times \frac{(n+1)}{(80 n+20)}=\frac{1}{3} \\
& \Rightarrow \frac{20n+80}{80n+20} = \frac{1}{3} \\
& \Rightarrow 3(20n+80) = 1(80n+20) \\
& \Rightarrow 60n+240 = 80n+20 \\
& \Rightarrow 20n=220 \\
& \Rightarrow n=11
\end{aligned}
$$

Hence, **n = 11**.

---

### Example 8:

If $n$ arithmetic means are inserted between two numbers, prove that the sum of the means equidistant from the beginning and the end is constant.

#### Solution:

Let $A_{1}, A_{2}, \ldots, A_{n}$ be $n$ AMs between $a$ and $b$. Then, $a, A_{1}, A_{2}, \ldots, A_{n}, b$ are in AP.

The **mth mean from the beginning** is $A_m$, which is the $(m+1)$th term of the AP.
$A_m = a + md$.

The **mth mean from the end** is $A_{n-m+1}$, which is the $(n-m+2)$th term of the AP.
Alternatively, it is the $(m+1)$th term from the end of the sequence. The $(m+1)$th term from the end is $b - md$.

The sum of the means equidistant from the beginning and the end is:
$$
A_m + A_{n-m+1} = (a+md) + (b-md) = a+b
$$

Since $a$ and $b$ are the two given numbers, their sum is a **constant**. Hence, the sum of the means equidistant from the beginning and the end is constant.

---

### Example 9:

Show that the sum of $n$ arithmetic means between two numbers is $n$ times the single arithmetic mean between them.

#### Solution:

Let $a$ and $b$ be two given numbers. The single AM between them is $A = \frac{a+b}{2}$.

Let $A_{1}, A_{2}, \ldots, A_{n}$ be the $n$ arithmetic means between $a$ and $b$. Then $a, A_{1}, A_{2}, \ldots, A_{n}, b$ form an AP.

The sum of these $n$ means is $S_n = A_{1}+A_{2}+\ldots+A_{n}$. Using the formula for the sum of an AP, $S_n = \frac{n}{2}(\text{first term} + \text{last term})$:
$$
A_{1}+A_{2}+\ldots+A_{n} = \frac{n}{2}(A_{1}+A_{n})
$$

In an AP, the sum of terms equidistant from the beginning and end is constant. Therefore, $A_1 + A_n = a+b$.
$$
\begin{aligned}
\text{Sum} &= \frac{n}{2}(a+b) \\
&= n \times \left(\frac{a+b}{2}\right) \\
&= n \times (\text{AM between } a \text{ and } b)
\end{aligned}
$$

Hence, the sum of $n$ arithmetic means between $a$ and $b$ is $n$ times the AM between $a$ and $b$.

---

