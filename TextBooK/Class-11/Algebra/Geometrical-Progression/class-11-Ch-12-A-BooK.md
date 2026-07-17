## Geometrical Progression (GP)

A sequence $a_{1}, a_{2}, a_{3}, \ldots, a_{n}$ is called a **geometrical progression**, if each term is nonzero and $\frac{a_{k+1}}{a_{k}}=r$ (constant) for all $k \geq 1$.

The constant ratio is called its **common ratio**. A geometrical progression is abbreviated as **GP**.

In a GP we usually denote the first term by $a$, the common ratio by $r$ and the $n$-th term by $T_{n}$.

The $n$-th term of a GP is called its **general term**.

---

## Some Examples of GP

### Example 1:

Show that the progression $6, 18, 54, 162, \ldots$ is a GP. Write down its first term and the common ratio.

#### Solution:

We have $\frac{18}{6}=\frac{54}{18}=\frac{162}{54}=3$ (constant).

So, the given progression is a GP in which the **first term** $= 6$ and the **common ratio** $= 3$.

---

### Example 2:

Show that the progression $-16, 4, -1, \frac{1}{4}, \ldots$ is a GP. Write down its first term and the common ratio.

#### Solution:

We have $\frac{4}{-16}=\frac{-1}{4}=\frac{(1 / 4)}{-1}=\frac{-1}{4}$ (constant).

So, the given progression is a GP in which $a=-16$ and $r=\frac{-1}{4}$.

---

### Example 3:

Show that the progression $\frac{1}{2}, \frac{-1}{3}, \frac{2}{9}, \frac{-4}{27}, \ldots$ is a GP. Write down its first term and find the common ratio.

#### Solution:

We have
$$
\left(\frac{-1}{3}\right) \div \frac{1}{2}=\left(\frac{-1}{3} \times 2\right)=\frac{-2}{3}, \quad \frac{2}{9} \div\left(\frac{-1}{3}\right)=\left\{\frac{2}{9} \times \frac{3}{(-1)}\right\}=\frac{-2}{3},
$$
$$
\left(\frac{-4}{27}\right) \div \frac{2}{9}=\left(\frac{-4}{27} \times \frac{9}{2}\right)=\frac{-2}{3} .
$$
So, the given progression is a GP in which $a=\frac{1}{2}$ and $r=\frac{-2}{3}$.

---

### Example 4:

Show that the sequence given by $T_{n}=\left(2 \times 3^{n}\right)$ for all $n \in N$ is a GP. Find its first term and the common ratio.

#### Solution:

We have
$$
T_{n}=\left(2 \times 3^{n}\right) \text { and } T_{n+1}=\left(2 \times 3^{n+1}\right).
$$
$$
\therefore \quad \frac{T_{n+1}}{T_{n}}=\frac{2 \times 3^{n+1}}{2 \times 3^{n}}=3 \text{ (constant) for all } n \in N .
$$
Also, $T_{1}=\left(2 \times 3^{1}\right)=(2 \times 3)=6$.

$\therefore$ the first term $= 6$ and the common ratio $= 3$.

---

### Geometric Series

If $a_{1}, a_{2}, a_{3}, \ldots, a_{n}, \ldots$ is a GP then the sum $a_{1}+a_{2}+a_{3}+\ldots+a_{n}+\ldots$ is called a **geometric series**.

A geometric series is finite or infinite according as the corresponding GP is finite or infinite.

---

## General Term of a GP

### Theorem 1:

Prove that the $n$-th term of a GP with first term $a$ and common ratio $r$ is given by $T_{n}=a r^{n-1}$.

#### Proof:

Let us consider a GP in which first term $=a$ and common ratio $=r$. Then, the GP is $a, a r, a r^{2}, \ldots$.

Its first term, $T_{1}=a=a r^{(1-1)}$;
second term, $T_{2}=a r=a r^{(2-1)}$;
third term, $T_{3}=a r^{2}=a r^{(3-1)}$;
... ... ... ... ...
... ... ... ... ...
$\therefore$ $n$-th term, $T_{n}=a r^{(n-1)}$.

Hence, $T_{n}=a r^{n-1}$ (known as the general term of the GP).

---

> ### REMEMBER
> In a GP with first term $= a$ and common ratio $= r$, we have
> $$
> n\text{-th term, } T_{n}=a r^{n-1}
> $$

---

## Solved Examples

### Example 1:

Find the 10th term and the general term of the progression
$$
\frac{1}{4}, \frac{-1}{2}, 1,-2,4, \ldots
$$

#### Solution:

In the given progression, we have
$$
\left(\frac{-1}{2}\right) \div \frac{1}{4}=\left(\frac{-1}{2} \times 4\right)=-2, \quad 1 \div\left(\frac{-1}{2}\right)=1 \times(-2)=-2,
$$
$$
(-2) \div 1=-2 \text{ and } 4 \div(-2)=-2 .
$$
So, the given progression is a GP in which $a=\frac{1}{4}$ and $r=-2$.

$\therefore$ the 10th term, $T_{10}=a r^{(10-1)}=a r^{9}=\frac{1}{4} \times(-2)^{9}=\frac{-512}{4}=-128$.

The general term, $T_{n}=a r^{(n-1)}=\frac{1}{4} \times(-2)^{(n-1)}=(-1)^{(n-1)} \times 2^{(n-3)}$.

---

### Example 2:

Show that the progression
$$
1, \frac{(\sqrt{2}-1)}{2 \sqrt{3}}, \frac{(3-2 \sqrt{2})}{12}, \frac{(5 \sqrt{2}-7)}{24 \sqrt{3}}, \ldots
$$
is a GP. Find its 5th term.

#### Solution:

In the given progression, we have
$\frac{T_{2}}{T_{1}}=\left\{\frac{(\sqrt{2}-1)}{2 \sqrt{3}} \times \frac{1}{1}\right\}=\frac{(\sqrt{2}-1)}{2 \sqrt{3}}$, $\frac{T_{3}}{T_{2}}=\frac{(3-2 \sqrt{2})}{12} \times \frac{2 \sqrt{3}}{(\sqrt{2}-1)}=\frac{(\sqrt{2}-1)}{2 \sqrt{3}}$,
$\frac{T_{4}}{T_{3}}=\frac{(5 \sqrt{2}-7)}{24 \sqrt{3}} \times \frac{12}{(3-2 \sqrt{2})}=\frac{(\sqrt{2}-1)}{2 \sqrt{3}}$.

$\therefore \frac{T_{2}}{T_{1}}=\frac{T_{3}}{T_{2}}=\frac{T_{4}}{T_{3}}=\ldots=\frac{(\sqrt{2}-1)}{2 \sqrt{3}}$ (constant).

So, the given progression is a GP in which $a=1$ and $r=\frac{(\sqrt{2}-1)}{2 \sqrt{3}}$.

$\therefore$ the 5th term,
$$
T_{5}=a r^{(5-1)}=a r^{4}=1 \times\left(\frac{\sqrt{2}-1}{2 \sqrt{3}}\right)^{4}
$$
$$
=\frac{(\sqrt{2}-1)^{4}}{144}=\frac{(3-2 \sqrt{2})^{2}}{144}
$$
$$
=\frac{(17-12 \sqrt{2})}{144} .
$$
Hence, $T_{5}=\frac{(17-12 \sqrt{2})}{144}$.

---

### Example 3:

Which term of the GP $2, 8, 32, 128, \ldots$ is 131072?

#### Solution:

In the given GP, we have $a=2$ and $r=\frac{8}{2}=4$.
Let its $n$-th term be 131072. Then,
$$
\begin{aligned}
T_{n}=131072 & \Rightarrow a r^{(n-1)}=131072 \\
& \Rightarrow 2 \times 4^{(n-1)}=131072 \\
& \Rightarrow 4^{(n-1)}=65536=4^{8} \\
& \Rightarrow n-1=8 \Rightarrow n=9
\end{aligned}
$$
Hence, the 9th term of the given GP is 131072.

---

### Example 4:

Which term of the GP $\sqrt{3}, \frac{1}{\sqrt{3}}, \frac{1}{3 \sqrt{3}}, \frac{1}{9 \sqrt{3}}, \ldots$ is $\frac{1}{729 \sqrt{3}}$?

#### Solution:

In the given GP, we have $a=\sqrt{3}$ and $r=\left(\frac{1}{\sqrt{3}} \times \frac{1}{\sqrt{3}}\right)=\frac{1}{3}$.

Let its $n$-th term be $\frac{1}{729 \sqrt{3}}$. Then,
$$
\begin{aligned}
T_{n}=\frac{1}{729 \sqrt{3}} & \Rightarrow a r^{(n-1)}=\frac{1}{729 \sqrt{3}} \\
& \Rightarrow \sqrt{3} \times\left(\frac{1}{3}\right)^{(n-1)}=\frac{1}{729 \sqrt{3}} \\
& \Rightarrow \frac{1}{3^{(n-1)}}=\frac{1}{(729 \times 3)}=\frac{1}{2187}=\frac{1}{3^{7}} \\
& \Rightarrow n-1=7 \Rightarrow n=8
\end{aligned}
$$
Hence, the 8th term of the given GP is $\frac{1}{729 \sqrt{3}}$.

---

### Example 5:

If the 4th and 9th terms of a GP are 54 and 13122 respectively, find the GP. Also, find its general term.

#### Solution:

Let $a$ be the first term and $r$ be the common ratio of the given GP.
Then, $T_{4}=54 \Rightarrow a r^{(4-1)}=54 \Rightarrow a r^{3}=54$. (i)
And, $T_{9}=13122 \Rightarrow a r^{(9-1)}=13122 \Rightarrow a r^{8}=13122$. (ii)

On dividing (ii) by (i), we get
$$
\frac{a r^{8}}{a r^{3}}=\frac{13122}{54} \Rightarrow r^{5}=243=3^{5} \Rightarrow r=3
$$
Putting $r=3$ in (i), we get
$$
a \times 3^{3}=54 \Rightarrow 27 a=54 \Rightarrow a=2
$$
Thus, $a=2$ and $r=3$.
So, the required GP is $2, 6, 18, 54, \ldots$.
The general term of the GP is given by
$$
T_{n}=a r^{(n-1)}=\left\{2 \times 3^{(n-1)}\right\}
$$

---

### Example 6:

The first term of a GP is 1 and the sum of its 3rd and 5th terms is 90. Find the common ratio of the GP.

#### Solution:

It is given that the first term of the GP is 1. Let $r$ be the common ratio of this GP. Then,
$$
T_{3}=1 \times r^{(3-1)} =r^{2} \text{ and } T_{5}=1 \times r^{(5-1)}=r^{4} .
$$
$$
\begin{aligned}
\therefore \quad\left(T_{3}+T_{5}\right)=90 & \Rightarrow r^{2}+r^{4}=90 \\
& \Rightarrow r^{4}+r^{2}-90=0 \\
& \Rightarrow t^{2}+t-90=0, \text{ where } r^{2}=t \\
& \Rightarrow(t+10)(t-9)=0 \\
& \Rightarrow t=-10 \text{ or } t=9 \\
& \Rightarrow t=9 \quad\left[\because t=r^{2} \neq-10\right] \\
& \Rightarrow r^{2}=9 \\
& \Rightarrow r=3 \text{ or } r=-3 .
\end{aligned}
$$
Hence, the common ratio of the given GP is 3 or -3.

---

### Example 7:

The 4th, 7th and 10th terms of a GP are $a, b, c$ respectively. Prove that $b^{2}=a c$.

#### Solution:

Let $A$ be the first term and $r$ be the common ratio of the given GP. Then,
$$
a=A r^{(4-1)}=A r^{3}; \quad b=A r^{(7-1)}=A r^{6} \text{ and } c=A r^{(10-1)}=A r^{9}.
$$
$$
\therefore \quad a c=\left(A r^{3}\right) \times\left(A r^{9}\right)=A^{2} r^{12}=\left(A r^{6}\right)^{2}=b^{2} .
$$
Hence, $b^{2}=a c$.

---

### Example 8:

If $a, b, c$ are three consecutive terms of an AP and $x, y, z$ are three consecutive terms of a GP, then prove that
$$
x^{(b-c)} \cdot y^{(c-a)} \cdot z^{(a-b)}=1
$$

#### Solution:

It is given that $a, b, c$ are in AP. Let $d$ be the common difference of this AP. Then,
$$
(b-c)=-(c-b)=-d, \quad (c-a)=\{(c-b)+(b-a)\}=2 d
$$
and $(a-b)=-(b-a)=-d$.

Also, $x, y, z$ are in GP. So, $y=\sqrt{x z}$.
$$
\begin{aligned}
\therefore \quad x^{(b-c)} \cdot y^{(c-a)} \cdot z^{(a-b)} & \\
& = x^{-d} \times(\sqrt{x z})^{2 d} \times z^{-d} \quad [\because(b-c)=-d,(c-a)=2 d,(a-b)=-d \text{ and } y=\sqrt{x z}] \\
& = x^{-d} \times(x z)^{d} \times z^{-d} \\
& = x^{-d} \times x^{d} \times z^{d} \times z^{-d}=x^{(-d+d)} \times z^{(-d+d)}=\left(x^{0} \times z^{0}\right)=1 .
\end{aligned}
$$
Hence, $x^{(b-c)} \cdot y^{(c-a)} \cdot z^{(a-b)}=1$.

---

### Example 9:

If $a, b, c, d$ are in GP, prove that
$$
\left(a^{2}+b^{2}+c^{2}\right)\left(b^{2}+c^{2}+d^{2}\right)=(a b+b c+c d)^{2}
$$

#### Solution:

Let $r$ be the common ratio of the GP $a, b, c, d$.
Then, $b=a r, c=a r^{2}$ and $d=a r^{3}$.
$$
\begin{aligned}
\therefore \quad \text{LHS} & =\left(a^{2}+b^{2}+c^{2}\right)\left(b^{2}+c^{2}+d^{2}\right) \\
& =\left(a^{2}+a^{2} r^{2}+a^{2} r^{4}\right)\left(a^{2} r^{2}+a^{2} r^{4}+a^{2} r^{6}\right) \\
& =a^{4} r^{2}\left(1+r^{2}+r^{4}\right)^{2} .
\end{aligned}
$$
And,
$$
\begin{aligned}
\text{RHS} &= (a b+b c+c d)^{2}=\left(a^{2} r+a^{2} r^{3}+a^{2} r^{5}\right)^{2} \\
&= a^{4} r^{2}\left(1+r^{2}+r^{4}\right)^{2} .
\end{aligned}
$$
Hence, $\left(a^{2}+b^{2}+c^{2}\right)\left(b^{2}+c^{2}+d^{2}\right)=(a b+b c+c d)^{2}$.

---

### Example 10:

If $a, b, c, d$ are in GP, prove that
$$
(b-c)^{2}+(c-a)^{2}+(d-b)^{2}=(a-d)^{2}
$$

#### Solution:

Let $r$ be the common ratio of the GP $a, b, c, d$.
Then, $b=a r, c=a r^{2}$ and $d=a r^{3}$.
$$
\begin{aligned}
\therefore \quad \mathrm{LHS} & =(b-c)^{2}+(c-a)^{2}+(d-b)^{2} \\
& =\left(a r-a r^{2}\right)^{2}+\left(a r^{2}-a\right)^{2}+\left(a r^{3}-a r\right)^{2} \\
& =\left\{a\left(r-r^{2}\right)\right\}^{2}+\left\{a\left(r^{2}-1\right)\right\}^{2}+\left\{a\left(r^{3}-r\right)\right\}^{2} \\
& =a^{2}\left(r-r^{2}\right)^{2}+a^{2}\left(r^{2}-1\right)^{2}+a^{2}\left(r^{3}-r\right)^{2} \\
& =a^{2} \cdot\left\{\left(r-r^{2}\right)^{2}+\left(r^{2}-1\right)^{2}+\left(r^{3}-r\right)^{2}\right\} \\
& =a^{2} \cdot\left\{\left(r^{2}+r^{4}-2 r^{3}\right)+\left(r^{4}+1-2 r^{2}\right)+\left(r^{6}+r^{2}-2 r^{4}\right)\right\} \\
& =a^{2} \cdot\left(r^{6}-2 r^{3}+1\right)=a^{2}\left(1-r^{3}\right)^{2} \\
& =\left(a-a r^{3}\right)^{2}=(a-d)^{2}=\text{RHS.}
\end{aligned}
$$
Hence, $(b-c)^{2}+(c-a)^{2}+(d-b)^{2}=(a-d)^{2}$.

---

### Example 11:

If the pth, qth and rth terms of a GP be $a, b, c$ respectively then prove that
$$
a^{(q-r)} \cdot b^{(r-p)} \cdot c^{(p-q)}=1
$$

#### Solution:

Let $A$ be the first term and $R$ be the common ratio of the given GP. Then,
$$
T_{p} = a \Rightarrow a=A R^{(p-1)}
$$
$$
T_{q} = b \Rightarrow b=A R^{(q-1)}
$$
$$
T_{r} = c \Rightarrow c=A R^{(r-1)}
$$
$$
\begin{aligned}
\therefore \quad a^{(q-r)} \cdot b^{(r-p)} \cdot c^{(p-q)} & \\
& =\left\{A R^{(p-1)}\right\}^{(q-r)} \cdot\left\{A R^{(q-1)}\right\}^{(r-p)} \cdot\left\{A R^{(r-1)}\right\}^{(p-q)} \\
& =A^{(q-r)} \cdot R^{(p-1)(q-r)} \cdot A^{(r-p)} \cdot R^{(q-1)(r-p)} \cdot A^{(p-q)} \cdot R^{(r-1)(p-q)} \\
& =A^{\{(q-r)+(r-p)+(p-q)\}} \cdot R^{\{(p-1)(q-r)+(q-1)(r-p)+(r-1)(p-q)\}} \\
& =A^{0} \cdot R^{p(q-r)+q(r-p)+r(p-q)+(r-q)+(p-r)+(q-p)} \\
& =\left(1 \times R^{0}\right)=(1 \times 1)=1 .
\end{aligned}
$$
Hence, $a^{(q-r)} \cdot b^{(r-p)} \cdot c^{(p-q)}=1$.

---

### Example 12:

If the first and the $n$-th terms of a GP are $a$ and $b$ respectively and $P$ is the product of its first $n$ terms then prove that $P^{2}=(a b)^{n}$.

#### Solution:

Let $r$ be the common ratio of the given GP. Then,
$$
\begin{align*}
& T_{n} = b \Rightarrow a r^{n-1}=b \Rightarrow r^{n-1}=\frac{b}{a} \Rightarrow r=\left(\frac{b}{a}\right)^{\frac{1}{(n-1)}} \\
\therefore \quad P & =\text{ product of first } n \text{ terms of the GP} \\
& =a \cdot a r \cdot a r^{2} \ldots \cdot a r^{n-1} \\
& =a^{n} \cdot r^{\{1+2+3+\ldots+(n-1)\}}=a^{n} \cdot r^{\frac{1}{2} n(n-1)} \\
& =a^{n} \cdot\left\{\left(\frac{b}{a}\right)^{\frac{1}{(n-1)}}\right\}^{\frac{1}{2} n(n-1)} \\
& =a^{n} \cdot\left(\frac{b}{a}\right)^{\left\{\frac{1}{(n-1)} \times \frac{1}{2} n(n-1)\right\}}=a^{n} \cdot\left(\frac{b}{a}\right)^{\frac{n}{2}} \tag{i} \\
\Rightarrow \quad P^{2} &= a^{2 n} \cdot\left(\frac{b}{a}\right)^{n}=\left(a^{2 n} \cdot \frac{b^{n}}{a^{n}}\right)=a^{n} b^{n}=(a b)^{n} . \quad \text{[using (i)] }
\end{align*}
$$
Hence, $P^{2}=(a b)^{n}$.

---

### Example 13:

The $(m+n)$-th and the $(m-n)$-th terms of a GP are $p$ and $q$ respectively. Show that the $m$-th and the $n$-th terms of the GP are $\sqrt{p q}$ and $p \cdot\left(\frac{q}{p}\right)^{(m / 2 n)}$ respectively.

#### Solution:

Let $a$ be the first term and $r$ be the common ratio of the given GP. Then,
$$
\begin{align*}
& T_{m+n}=p \text{ and } T_{m-n}=q \\
\Rightarrow \quad & a r^{(m+n-1)}=p \quad \ldots \text{ (i)} \quad \text{ and } a r^{(m-n-1)}=q \quad \ldots \text{ (ii)} \\
\Rightarrow \quad & \frac{a r^{(m+n-1)}}{a r^{(m-n-1)}}=\frac{p}{q} \\
\Rightarrow \quad & r^{((m+n-1)-(m-n-1)\}}=\frac{p}{q} \\
\Rightarrow \quad & r^{2 n}=\frac{p}{q} \Rightarrow r=\left(\frac{p}{q}\right)^{\frac{1}{2 n}} \quad \ldots \text{ (iii)} \\
\Rightarrow \quad & \frac{1}{r}=\left(\frac{q}{p}\right)^{\frac{1}{2 n}} \\
\therefore \quad T_{m} & =a r^{(m-1)} \\
& =a r^{(m+n-1)} \times\left(\frac{1}{r}\right)^{n} \\
& =p \times\left\{\left(\frac{q}{p}\right)^{\frac{1}{2 n}}\right\}^{n} \\
& =p \times\left(\frac{q}{p}\right)^{\left(\frac{1}{2 n} \times n\right)}=p \times\left(\frac{q}{p}\right)^{\frac{1}{2}}=\sqrt{p q} . \\
\text{And, } \quad T_{n} & =a r^{(n-1)} \\
& =a r^{(m+n-1)} \times\left(\frac{1}{r}\right)^{m} \\
& =p \times\left\{\left(\frac{q}{p}\right)^{\frac{1}{2 n}}\right\}^{m}=p \times\left(\frac{q}{p}\right)^{\frac{m}{2 n}}
\end{align*}
$$
Hence, $T_{m} =\sqrt{p q}$ and $T_{n}=p \times\left(\frac{q}{p}\right)^{\frac{m}{2 n}}$.

---

### Example 14:

The pth, qth and rth terms of an AP as well as those of a GP are $a, b, c$, respectively. Prove that
$$
a^{b-c} \cdot b^{c-a} \cdot c^{a-b}=1
$$

#### Solution:

Let $x$ be the first term and $d$ be the common difference of the AP. Then,
$$
a=x+(p-1) d, \quad b=x+(q-1) d \text{ and } c=x+(r-1) d
$$
$$
\therefore (b-c)=(q-r) d \quad \ldots(\mathrm{i}), \quad (c-a)=(r-p) d \quad \ldots(\mathrm{ii})
$$
$$
\text{and } (a-b)=(p-q) d \quad \ldots(\mathrm{iii})
$$
Now, let $A$ be the first term and $R$ be the common ratio of the GP. Then,
$$
a=A R^{(p-1)} \quad \ldots(\mathrm{iv}), \quad b=A R^{(q-1)} \quad \ldots(\mathrm{v}) \quad \text{and} \quad c=A R^{(r-1)} \quad \ldots(\mathrm{vi})
$$
$$
\begin{align*}
& a^{(b-c)} \cdot b^{(c-a)} \cdot c^{(a-b)} \\
& =\left\{A R^{(p-1)}\right\}^{(q-r) d} \times\left\{A R^{(q-1)}\right\}^{(r-p) d} \times\left\{A R^{(r-1)}\right\}^{(p-q) d} \\
& =A^{\{(q-r) d+(r-p) d+(p-q) d\}} \times R^{\{(p-1)(q-r) d+(q-1)(r-p) d+(r-1)(p-q) d\}} \\
& =A^{0} \times R^{0}=(1 \times 1)=1
\end{align*}
$$
$$
\left[\because \begin{array}{l}
(q-r) d+(r-p) d+(p-q) d=0 \\
\text{and } p(q-r) d+q(r-p) d+r(p-q) d-(q-r) d-(r-p) d-(p-q) d=0
\end{array}\right] .
$$
Hence, $a^{(b-c)} \cdot b^{(c-a)} \cdot c^{(a-b)}=1$.

---

### Example 15:

If $x, 2y, 3z$ are in AP, where the distinct numbers $x, y, z$ are in GP then find the common ratio of the GP.

#### Solution:

It is given that the distinct numbers $x, y, z$ are in GP. Let $r$ be the common ratio of this GP. Then,
$$
y=x r \text{ and } z=x r^{2}
$$
Now, $x, 2 y, 3 z$ are in AP
$$
\begin{aligned}
& \Rightarrow \quad x, 2 x r, 3 x r^{2} \text{ are in AP} \\
& \Rightarrow \quad 2 x r-x=3 x r^{2}-2 x r \\
& \Rightarrow \quad 3 x r^{2}-4 x r+x=0 \\
& \Rightarrow \quad 3 r^{2}-4 r+1=0 \quad[\because x \neq 0, \text{ as it is a term of GP}] \\
& \Rightarrow \quad(r-1)(3 r-1)=0 \Rightarrow r=\frac{1}{3} \quad[\because x \neq y \neq z \Rightarrow r \neq 1].
\end{aligned}
$$
Hence, the common ratio of the GP is $\frac{1}{3}$.

---

### Example 16:

In a GP of positive terms, if any term is equal to the sum of the next two terms then show that the common ratio of the GP is $2 \sin 18^{\circ}$.

#### Solution:

Let us consider a GP of positive terms with first term $=a$ and common ratio $=r$. Then, $a>0$ and $r>0$.
It is given that $T_{n}=T_{n+1}+T_{n+2}$.
$$
\begin{aligned}
\text{Now, } T_{n}=T_{n+1}+T_{n+2} & \\
& \Rightarrow \quad a r^{n-1}=a r^{n}+a r^{n+1} \\
& \Rightarrow 1=r+r^{2} \quad \text{[dividing both sides by } a r^{n-1} \text{]} \\
& \Rightarrow \quad r^{2}+r-1=0 \\
& \Rightarrow \quad r=\frac{-1 \pm \sqrt{1+4}}{2}=\frac{-1 \pm \sqrt{5}}{2} \\
& \Rightarrow \quad r=\frac{-1+\sqrt{5}}{2}=2\left(\frac{\sqrt{5}-1}{4}\right)=2 \sin 18^{\circ} \quad[\because r>0].
\end{aligned}
$$
Hence, the common ratio of the GP is $2 \sin 18^{\circ}$.

---

### Example 17:

If $p, q, r$ are in AP, prove that the $p$-th, $q$-th and $r$-th terms of any GP are in GP.

#### Solution:

Since $p, q, r$ are in AP, we have $(q-p)=(r-q)$.

Let us consider a GP with first term $=A$ and common ratio $=R$.
Then, $T_{p}=A R^{(p-1)}, T_{q}=A R^{(q-1)}$ and $T_{r}=A R^{(r-1)}$.
$$
\therefore \quad \frac{T_{q}}{T_{p}}=\frac{A R^{(q-1)}}{A R^{(p-1)}}=R^{(q-p)}=R^{(r-q)} \quad \ldots \text{(i)}
$$
and
$$
\frac{T_{r}}{T_{q}}=\frac{A R^{(r-1)}}{A R^{(q-1)}}=R^{(r-q)}.
$$
Thus, $\frac{T_{q}}{T_{p}}=\frac{T_{r}}{T_{q}}$ and therefore, $T_{p}, T_{q}, T_{r}$ are in GP.

Hence, the $p$-th, $q$-th and $r$-th terms of any GP are in GP.

---

### Example 18:

Let $S$ be the sum, $P$ be the product and $R$ be the sum of the reciprocals of three terms of a GP. Then, prove that $P^{2} R^{3}=S^{3}$.

#### Solution:

Let the three terms of the given GP be $\frac{a}{r}, a$ and $a r$. Then,
$$
S=\left(\frac{a}{r}+a+a r\right)=a\left(\frac{1+r+r^{2}}{r}\right), \quad P=\left(\frac{a}{r} \times a \times a r\right)=a^{3}
$$
and
$$
R=\left(\frac{r}{a}+\frac{1}{a}+\frac{1}{a r}\right)=\frac{1}{a}\left(r+1+\frac{1}{r}\right)=\frac{1}{a}\left(\frac{r^{2}+r+1}{r}\right)=\frac{1}{a}\left(\frac{1+r+r^{2}}{r}\right) .
$$
$$
\therefore \quad P^{2} R^{3}=a^{6} \times \frac{\left(1+r+r^{2}\right)^{3}}{a^{3} r^{3}}=a^{3}\left(\frac{1+r+r^{2}}{r}\right)^{3}=S^{3} .
$$
Hence, $P^{2} R^{3}=S^{3}$.

---

### Example 19:

For $a, b, c$ to be in GP, what is the value of $\frac{a-b}{b-c}$?

#### Solution:

For $a, b, c$ to be in GP, we must have
$$
\frac{b}{a}=\frac{c}{b}=r \quad \text{or} \quad \frac{b}{a}=\frac{c}{b}=\frac{1}{r}
$$
**Case I:** When $\frac{b}{a}=\frac{c}{b}=r$.
In this case, $b=a r$ and $c=b r$.
$$
\therefore \quad \frac{a-b}{b-c}=\frac{a-a r}{b-b r}=\frac{a(1-r)}{b(1-r)}=\frac{a}{b}
$$
**Case II:** When $\frac{b}{a}=\frac{c}{b}=\frac{1}{r}$.
In this case, $a=b r$ and $b=c r$.
$$
\therefore \quad \frac{a-b}{b-c}=\frac{b r-b}{c r-c}=\frac{b(r-1)}{c(r-1)}=\frac{b}{c}
$$
Hence, the value of $\left(\frac{a-b}{b-c}\right)$ is $\frac{a}{b}$ or $\frac{b}{c}$.

---

### Example 20:

If $a, b, c$ are in GP and $a^{1 / x}=b^{1 / y}=c^{1 / z}$, prove that $x, y, z$ are in AP.

#### Solution:

Since $a, b, c$ are in GP, we have
$$
b^{2}=a c \quad \ldots \text{(i)}
$$
Let $a^{1 / x}=b^{1 / y}=c^{1 / z}=k$ (say).
Then, $a=k^{x}, b=k^{y}$ and $c=k^{z}$.
Putting these values in (i), we get
$$
\left(k^{y}\right)^{2}=\left(k^{x}\right) \times\left(k^{z}\right) \Rightarrow k^{2 y}=k^{(x+z)} .
$$
$$
\therefore \quad 2 y=x+z .
$$
Hence, $x, y, z$ are in AP.

---

### Example 21:

If $a, b, c$ are in AP; $b, c, d$ are in GP and $\frac{1}{c}, \frac{1}{d}, \frac{1}{e}$ are in AP, then show that $a, c, e$ are in GP.

#### Solution:

$a, b, c$ are in AP $\Rightarrow 2 b=a+c$. (i)
$b, c, d$ are in GP $\Rightarrow c^{2}=b d$. (ii)
$$
\begin{align*}
\frac{1}{c}, \frac{1}{d}, \frac{1}{e} \text{ are in AP} & \Rightarrow \frac{2}{d}=\left(\frac{1}{c}+\frac{1}{e}\right)=\frac{(c+e)}{c e} \\
& \Rightarrow d=\frac{2 c e}{(c+e)} \quad \ldots \text{(iii)}
\end{align*}
$$
Now, $c^{2}=b d \Rightarrow c^{2}=\frac{(a+c)}{2} \cdot \frac{2 c e}{(c+e)}$ [from (i) and (iii)]
$$
\begin{aligned}
& \Rightarrow c=\frac{(a+c) e}{(c+e)} \\
& \Rightarrow c(c+e)=(a+c) e \\
& \Rightarrow c^{2}=a e \\
& \Rightarrow a, c, e \text{ are in GP.}
\end{aligned}
$$
Hence, $a, c, e$ are in GP.

---

### Example 22:

If $p, q, r$ are in GP and the equations
$$
p x^{2}+2 q x+r=0 \text{ and } d x^{2}+2 e x+f=0
$$
have a common root then show that $\frac{d}{p}, \frac{e}{q}, \frac{f}{r}$ are in AP.

#### Solution:

Since $p, q, r$ are in GP, we have
$$
q^{2}=p r \quad \ldots \text{(i)}
$$
On solving $p x^{2}+2 q x+r=0$, we get
$$
x=\frac{-2 q \pm \sqrt{4 q^{2}-4 p r}}{2 p}=\frac{-2 q}{2 p}=\frac{-q}{p} \quad \text{[using (i)]}
$$
Thus, $x=\frac{-q}{p}$ is a repeated root of $p x^{2}+2 q x+r=0$.
$\therefore x=\frac{-q}{p}$ is also a root of $d x^{2}+2 e x+f=0$.
$$
\Rightarrow \quad d \cdot\left(\frac{-q}{p}\right)^{2}+2 e\left(\frac{-q}{p}\right)+f=0
$$
$$
\Rightarrow \quad d q^{2}-2 e q p+f p^{2}=0 \quad \ldots \text{(ii)}
$$
$$
\begin{aligned}
& \Rightarrow \quad \frac{d}{p}-\frac{2 e}{q}+\frac{f p}{q^{2}}=0 \quad \text{[on dividing (ii) by } p q^{2} \text{]} \\
& \Rightarrow \quad \frac{d}{p}-\frac{2 e}{q}+\frac{f}{r}=0 \quad \left[\because q^{2}=p r\right] \\
& \Rightarrow \quad \frac{d}{p}+\frac{f}{r}=\frac{2 e}{q} .
\end{aligned}
$$
Hence, $\frac{d}{p}, \frac{e}{q}, \frac{f}{r}$ are in AP.

---

### Example 23:

Find all sequences which are simultaneously AP and GP.

#### Solution:

Let $a_{1}, a_{2}, a_{3}, \ldots, a_{n}, \ldots$ be a sequence which is both an AP as well as a GP.
Consider three consecutive terms $a_{n}, a_{n+1}, a_{n+2}$ of this AP and GP.

Then, $2 a_{n+1}=a_{n}+a_{n+2} \quad \ldots \text{(i)} \quad \left[\because a_{n}, a_{n+1}, a_{n+2} \text{ are in AP}\right]$.

And, if $r$ be the common ratio of the GP, then
$$
a_{n}=a_{1} r^{n-1}, a_{n+1}=a_{1} r^{n} \text{ and } a_{n+2}=a_{1} r^{n+1}
$$
Putting these values in (i), we get
$$
2 a_{1} r^{n}=a_{1} r^{n-1}+a_{1} r^{n+1} \Rightarrow r^{2}-2 r+1=0 \Rightarrow(r-1)^{2}=0 \Rightarrow r=1 .
$$
Putting $r=1$, we get $a_{n}=a_{1}, a_{n+1}=a_{1}$ and $a_{n+2}=a_{1}$.
Thus, we get a constant sequence $a_{1}, a_{1}, a_{1}, a_{1}, \ldots$.
Hence, a constant sequence is the only sequence which is both AP and GP.

---

### Example 24:

If the pth, qth, rth and sth terms of an AP be in GP then prove that $(p-q),(q-r),(r-s)$ are in GP.

#### Solution:

Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$$
T_{p}=a+(p-1) d, \quad T_{q}=a+(q-1) d,
$$
$$
T_{r}=a+(r-1) d, \quad T_{s}=a+(s-1) d .
$$
It is given that $T_{p}, T_{q}, T_{r}$ and $T_{s}$ are in GP.
Let the first term of this GP be $A$ and its common ratio be $R$. Then,
$$
T_{p}=A \Rightarrow a+(p-1) d=A \quad \ldots \text{(i)}
$$
$$
T_{q}=A R \Rightarrow a+(q-1) d=A R \quad \ldots \text{(ii)}
$$
$$
T_{r}=A R^{2} \Rightarrow a+(r-1) d=A R^{2} \quad \ldots \text{(iii)}
$$
and $T_{s}=A R^{3} \Rightarrow a+(s-1) d=A R^{3} \quad \ldots \text{(iv)}$.

On subtracting (ii) from (i), we get
$$
(p-q) d=A(1-R) \quad \ldots \text{(v)}
$$
On subtracting (iii) from (ii), we get
$$
(q-r) d=A R(1-R) \quad \ldots \text{(vi)}
$$
On subtracting (iv) from (iii), we get
$$
(r-s) d=A R^{2}(1-R) \quad \ldots \text{(vii)}
$$
Now, we have
$$
(q-r)^{2} d^{2}=A^{2} R^{2}(1-R)^{2} \text{ and } (p-q) d \times(r-s) d=A^{2} R^{2}(1-R)^{2} .
$$
$$
\begin{aligned}
\therefore & (q-r)^{2} d^{2}=(p-q) d \times(r-s) d \\
\Rightarrow & (q-r)^{2}=(p-q) \times(r-s) \\
\Rightarrow & (p-q),(q-r) \text{ and } (r-s) \text{ are in GP.}
\end{aligned}
$$
Hence, $(p-q),(q-r),(r-s)$ are in GP.

---

## $n$-th Term From the End of a GP

### Theorem 2:

Show that the $n$-th term from the end of a GP with the first term $a$, the common ratio $r$ and the last term $l$ is given by $\frac{l}{r^{(n-1)}}$.

#### Proof:

Let $a$ be the first term, $r$ be the common ratio and $l$ be the last term of a given GP. Then,

2nd term from the end $=\frac{l}{r}=\frac{l}{r^{(2-1)}}$;
3rd term from the end $=\frac{l}{r^{2}}=\frac{l}{r^{(3-1)}}$;
... ... ... ... ... ... ... ...
... ... ... ... ... ... ... ...
$n$-th term from the end $=\frac{l}{r^{(n-1)}}$.

Hence, the $n$-th term from the end $=\frac{l}{r^{(n-1)}}$.

---

### Example 25:

Find the 8th term from the end of the GP $3, 6, 12, 24, \ldots, 12288$.

#### Solution:

Here $r=2$ and $l=12288$.
$$
\therefore \quad \text{8th term from the end} =\frac{l}{r^{(8-1)}}=\frac{l}{r^{7}}=\frac{12288}{2^{7}}=\frac{12288}{128}=96 .
$$
Hence, the 8th term from the end $= 96$.

---

