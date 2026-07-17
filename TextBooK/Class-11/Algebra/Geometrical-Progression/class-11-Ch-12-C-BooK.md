## **Sum of *n* Terms of a GP**

---

### Theorem

Prove that the sum of *$n$ terms* of a GP with the first term *$a$* and the common ratio *$r$* is given by

$$
S_{n}=\left\{\begin{array}{l}
na, \text { when } r=1 \\
\frac{a\left(1-r^{n}\right)}{(1-r)}, \text { when } r<1 \\
\frac{a\left(r^{n}-1\right)}{(r-1)}, \text { when } r>1
\end{array}\right.
$$

---

### Proof

Let us consider a GP with the first term *$a$* and the common ratio *$r$*.
Then,

$$
S_{n}=a+a r+a r^{2}+\ldots+a r^{n-1} \tag{i}
$$

**Case 1:** If $r=1$, we have

$$
S_{n}=a+a+\ldots \text { to } n \text { terms }=n a
$$

**Case 2:** If $r \neq 1$, we have

$$
r S_{n}=a r+a r^{2}+\ldots+a r^{n-1}+a r^{n} \tag{ii}
$$

On subtracting (ii) from (i), we get

$$
(1-r) S_{n}=\left(a-a r^{n}\right)=a\left(1-r^{n}\right)
$$

$$
\Rightarrow \quad S_{n}=\frac{a\left(1-r^{n}\right)}{(1-r)} \text { or } S_{n}=\frac{a\left(r^{n}-1\right)}{(r-1)}.
$$

$$
\therefore \quad S_{n}=\left\{\begin{array}{l}
\frac{a\left(1-r^{n}\right)}{(1-r)}, \text { when } r<1 \\
\frac{a\left(r^{n}-1\right)}{(r-1)}, \text { when } r>1
\end{array}\right.
$$

---

### Remark

If a GP contains *$n$ terms* with first term $=a$, common ratio $=r$ and last term $=l$ then

$$
l=a r^{n-1} \tag{i}
$$

**Case 1:** When $r<1$, we have

$$
S_{n}=\frac{a\left(1-r^{n}\right)}{(1-r)}=\frac{\left(a-a r^{n}\right)}{(1-r)}=\frac{(a-l r)}{(1-r)}
$$
[using (i)].

**Case 2:** When $r>1$, we have

$$
S_{n}=\frac{a\left(r^{n}-1\right)}{(r-1)}=\frac{\left(a r^{n}-a\right)}{(r-1)}=\frac{(l r-a)}{(r-1)} \tag{i}
$$

---

### Summary

In a GP with first term *$a$* and common ratio *$r$*, we have

$$
S_{n}=\left\{\begin{array}{l}
\text {na, when } r=1 \\
\frac{a\left(1-r^{n}\right)}{(1-r)}=\frac{(a-l r)}{(1-r)}, \text { when } r<1 \\
\frac{a\left(r^{n}-1\right)}{(r-1)}=\frac{(l r-a)}{(r-1)}, \text { when } r>1
\end{array}\right.
$$

---

## Solved Examples

### Example 1

Find the sum of 8 terms of the GP $3,6,12,24, \ldots$.

#### Solution

Here $a=3$, $r=2>1$ and $n=8$.
Using the formula, $S_{n}=\frac{a\left(r^{n}-1\right)}{(r-1)}$, we get

$$
S_{8}=\frac{3 \times\left(2^{8}-1\right)}{(2-1)}=3 \times(256-1)=3 \times 255=765 .
$$

---

### Example 2

Find the sum of the geometric series $1+\frac{1}{2}+\frac{1}{4}+\frac{1}{8}+\ldots$ to 12 terms.

#### Solution

Here $a=1$, $r=\frac{1}{2}<1$ and $n=12$.
Using the formula, $S_{n}=\frac{a\left(1-r^{n}\right)}{(1-r)}$, we get

$$
S_{12}=\frac{1 \times\left\{1-\left(\frac{1}{2}\right)^{12}\right\}}{\left(1-\frac{1}{2}\right)}=\frac{\left(1-\frac{1}{2^{12}}\right)}{\left(\frac{1}{2}\right)}=\frac{\left(2^{12}-1\right)}{2^{11}}=\frac{4095}{2048} .
$$

---

### Example 3

How many terms of the geometric series $1+4+16+64+\ldots$ will make the sum 5461?

#### Solution

Let the required number of terms be $n$.
Here, $a=1$, $r=4>1$ and $S_{n}=5461$.

$$
\therefore \quad S_{n}=\frac{a\left(r^{n}-1\right)}{(r-1)} \Rightarrow \frac{1 \times\left(4^{n}-1\right)}{(4-1)}=5461
$$

$$
\Rightarrow \quad\left(4^{n}-1\right)=16383
$$

$$
\Rightarrow \quad 4^{n}=16384=4^{7}
$$

$$
\Rightarrow \quad n=7 .
$$

Hence, the required number of terms is 7.

---

### Example 4

Find the sum of the series $2+6+18+54+\ldots+4374$.

#### Solution

Clearly, the given series is a geometric series in which $a=2$, $r=3>1$ and $l=4374$.

$$
\therefore \quad \text {the required sum}=\frac{(l r-a)}{(r-1)}=\frac{(4374 \times 3-2)}{(3-1)}=\frac{13120}{2}=6560.
$$

Hence, the sum of the given series is 6560.

---

### Example 5

In a GP, it is being given that $T_{1}=3$, $T_{n}=96$ and $S_{n}=189$. Find the value of $n$.

#### Solution

Here, $a=3$, $l=96$ and $S_{n}=189$.
Let the common ratio of the given GP be $r$.
Then, $S_{n}=\frac{(l r-a)}{(r-1)} \Rightarrow \frac{(96 r-3)}{(r-1)}=189$

$$
\Rightarrow(96 r-3)=(189 r-189)
$$

$$
\Rightarrow 93 r=186 \Rightarrow r=2
$$

Now, $l=a r^{n-1} \Rightarrow 3 \times 2^{n-1}=96$

$$
\Rightarrow 2^{n-1}=32=2^{5} \Rightarrow n-1=5 \Rightarrow n=6.
$$

Hence, $n=6$.

---

### Example 6

Sum the series $5+55+555+\ldots$ to $n$ terms.

#### Solution

We have

$$
\begin{aligned}
& 5+55+555+\ldots \text { to } n \text { terms } \\
& =5 \times\{1+11+111+\ldots \text { to } n \text { terms }\} \\
& =\frac{5}{9} \times\{9+99+999+\ldots \text { to } n \text { terms }\} \\
& =\frac{5}{9} \times\left\{(10-1)+\left(10^{2}-1\right)+\left(10^{3}-1\right)+\ldots \text { to } n \text { terms }\right\} \\
& =\frac{5}{9} \times\left\{\left(10+10^{2}+10^{3}+\ldots \text { to } n \text { terms }\right)-n\right\} \\
& =\frac{5}{9} \times\left\{\frac{10 \times\left(10^{n}-1\right)}{(10-1)}-n\right\}=\frac{5}{81} \times\left(10^{n+1}-9 n-10\right)
\end{aligned}
$$

Hence, the required sum is $\frac{5}{81} \times\left(10^{n+1}-9 n-10\right)$.

---

### Example 7

Sum the series $.4+.44+.444+\ldots$ to $n$ terms.

#### Solution

We have

$$
\begin{aligned}
& .4+.44+.444+\ldots \text { to } n \text { terms } \\
& =4 \times\{.1+.11+.111+\ldots \text { to } n \text { terms }\} \\
& =\frac{4}{9} \times\{.9+.99+.999+\ldots \text { to } n \text { terms }\} \\
& =\frac{4}{9} \times\{(1-.1)+(1-.01)+(1-.001)+\ldots \text { to } n \text { terms }\} \\
& =\frac{4}{9} \times\{(1+1+\ldots \text { to } n \text { terms })-(.1+.01+.001+\ldots \text { to } n \text { terms })\} \\
& =\frac{4}{9} \times\left[n-\frac{.1 \times\left\{1-(.1)^{n}\right\}}{(1-.1)}\right] \quad\left\{\because S_{n}=\frac{a\left(1-r^{n}\right)}{(1-r)}\right\} \\
& =\frac{4}{9} \times\left[n-\frac{\frac{1}{10} \cdot\left\{1-\frac{1}{(10)^{n}}\right\}}{\left(1-\frac{1}{10}\right)}\right] \\
& =\frac{4}{9} \times\left\{n-\frac{\left(10^{n}-1\right)}{9 \cdot 10^{n}}\right\}=\frac{4}{9} \times\left[n-\frac{1}{9}\left\{1-\frac{1}{10^{n}}\right\}\right] \\
& =\frac{4}{81} \times\left[9 n-\left\{1-\frac{1}{10^{n}}\right\}\right]=\frac{4}{81} \times\left\{9 n-1+\frac{1}{10^{n}}\right\}
\end{aligned}
$$

Hence, the required sum is $\frac{4}{81} \times\left(9 n-1+\frac{1}{10^{n}}\right)$.

---

### Example 8

The sum of some terms of a GP is 315. Its first term is 5 and the common ratio is 2. Find the number of its terms and the last term.

#### Solution

Let the given GP contain $n$ terms. Then,
$a=5$, $r=2>1$ and $S_{n}=315$.

$$
\begin{aligned}
\therefore \quad S_{n}=315 & \Rightarrow \frac{a\left(r^{n}-1\right)}{(r-1)}=315 \\
& \Rightarrow \frac{5 \times\left(2^{n}-1\right)}{(2-1)}=315 \\
& \Rightarrow\left(2^{n}-1\right)=63 \Rightarrow 2^{n}=64=2^{6} \Rightarrow n=6.
\end{aligned}
$$

Last term $=a r^{(n-1)}=5 \times 2^{(6-1)}=\left(5 \times 2^{5}\right)=(5 \times 32)=160$.
Hence, the given GP contains 6 terms and its last term is 160.

---

### Example 9

The sum of first three terms of a GP is 16 and the sum of its next three terms is 128. Find the sum of $n$ terms of the GP.

#### Solution

Let $a$ be the first term and $r$ be the common ratio of the given GP.
Then, $a+a r+a r^{2}=16$ and $a r^{3}+a r^{4}+a r^{5}=128$.

$$
\Rightarrow \quad a\left(1+r+r^{2}\right)=16 \quad \ldots \text { (i) }
$$

$$
\text {and } a r^{3}\left(1+r+r^{2}\right)=128 \quad \ldots \text { (ii) }
$$

On dividing (ii) by (i), we get $r^{3}=8=2^{3} \Rightarrow r=2$.
Putting $r=2$ in (i), we get

$$
a(1+2+4)=16 \Rightarrow a=\frac{16}{7}
$$

Thus, in the given GP, we have $a=\frac{16}{7}$ and $r=2>1$.

$$
\therefore \quad S_{n}=\frac{a\left(r^{n}-1\right)}{(r-1)}=\frac{\frac{16}{7} \times\left(2^{n}-1\right)}{(2-1)}=\frac{16}{7}\left(2^{n}-1\right).
$$

---

### Example 10

In a GP, the sum of first two terms is -4 and the 5th term is 4 times the 3rd term. Find the GP.

#### Solution

Let $a$ be the first term and $r$ be the common ratio of the given GP. Then,

$$
T_{1}+T_{2}=-4 \text { and } T_{5}=4 \times T_{3}
$$

$$
\Rightarrow a+a r=-4 \text { and } a r^{4}=4 \times a r^{2}
$$

$$
\Rightarrow a(1+r)=-4 \text { and } r^{2}=4
$$

$$
\Rightarrow a(1+r)=-4 \quad \ldots \text { (i) and } r= \pm 2 .
$$

Putting $r=2$ in (i), we get $a=\frac{-4}{3}$.
Putting $r=-2$ in (i), we get $a=4$.

$\therefore \quad a=\frac{-4}{3}$ and $r=2$ gives the GP $\frac{-4}{3}, \frac{-8}{3}, \frac{-16}{3}, \ldots$
and, $a=4$ and $r=-2$ gives the GP $4,-8,16, \ldots$.

Hence, the required GP is $\left\{\frac{-4}{3}, \frac{-8}{3}, \frac{-16}{3}, \ldots\right\}$ or $\{4,-8,16, \ldots\}$.

---

### Example 11

In an increasing GP, the sum of the first and last terms is 66, the product of the second and the last but one is 128 and the sum of the terms is 126. How many terms are there in this GP?

#### Solution

Let the given GP contain $n$ terms. Let $a$ be the first term and $r$ be the common ratio of this GP.
Since the given GP is increasing, we have $r>1$.
Now, $T_{1}+T_{n}=66 \Rightarrow a+a r^{(n-1)}=66$.  **(i)**

And, $T_{2} \times T_{n-1}=128 \Rightarrow a r \times a r^{(n-2)}=128$

$$
\Rightarrow a^{2} r^{(n-1)}=128 \Rightarrow a r^{(n-1)}=\frac{128}{a} \tag{ii}
$$

Using (ii) in (i), we get

$$
a+\frac{128}{a}=66 \Rightarrow a^{2}-66 a+128=0
$$

$$
\Rightarrow a^{2}-2 a-64 a+128=0
$$

$$
\Rightarrow a(a-2)-64(a-2)=0
$$

$$
\Rightarrow(a-2)(a-64)=0
$$

$$
\Rightarrow a=2 \text { or } a=64
$$

Putting $a=2$ in (ii), we get

$$
r^{(n-1)}=\frac{128}{a^{2}}=\frac{128}{4}=32 \tag{iii}
$$

Putting $a=64$ in (ii), we get

$$
r^{(n-1)}=\frac{128}{a^{2}}=\frac{128}{64 \times 64}=\frac{1}{32}, \text { which is rejected, since } r>1 .
$$

Thus, $a=2$ and $r^{(n-1)}=32$.

$$
\text { Now, } S_{n}=126 \Rightarrow \frac{a\left(r^{n}-1\right)}{(r-1)}=126
$$

$$
\Rightarrow 2\left(\frac{r^{n}-1}{r-1}\right)=126 \Rightarrow \frac{r^{n}-1}{r-1}=63
$$

$$
\Rightarrow \frac{r^{(n-1)} \times r-1}{r-1}=63 \Rightarrow \frac{32 r-1}{r-1}=63
$$

$$
\Rightarrow 32 r-1=63 r-63 \Rightarrow 31 r=62 \Rightarrow r=2.
$$

$$
\therefore \quad r^{(n-1)}=32=2^{5} \Rightarrow n-1=5 \Rightarrow n=6.
$$

Hence, there are 6 terms in the given GP.

---

### Remark

Consider two GPs $a, a r, a r^{2}, a r^{3}, \ldots$ and $A, A R, A R^{2}, A R^{3}, \ldots$. Taking the products of their corresponding elements, we get
$a A, a A(r R), a A(r R)^{2}, a A(r R)^{3}, \ldots$
which is clearly a GP with first term $=a A$ and common ratio $=r R$. Based upon this result, we take the following example.

---

### Example 12

Find the sum of the products of the corresponding terms of finite geometrical progressions
$2,4,8,16,32$ and $128,32,8,2, \frac{1}{2}$.

#### Solution

Taking the products of the corresponding terms of two given GPs, we get a new progression
$(2 \times 128),(4 \times 32),(8 \times 8),(16 \times 2),\left(32 \times \frac{1}{2}\right)$,
i.e., $256,128,64,32,16$, which is clearly a GP in which $a=256$ and

$$
r=\frac{16}{32}=\frac{1}{2}<1 .
$$

$\therefore \quad$ the required sum $=\frac{a\left(1-r^{5}\right)}{(1-r)}=\frac{256 \times\left\{1-\left(\frac{1}{2}\right)^{5}\right\}}{\left(1-\frac{1}{2}\right)}$

$$
\begin{aligned}
& =\frac{256 \times\left(1-\frac{1}{2^{5}}\right)}{\left(\frac{1}{2}\right)}=256 \times 2 \times\left(1-\frac{1}{32}\right) \\
& =\left(256 \times 2 \times \frac{31}{32}\right)=496 .
\end{aligned}
$$

---

### Example 13

Find the sum of $n$ terms of the sequence given by $a_{n}=\left(3^{n}+5 n\right)$, $n \in N$.

#### Solution

Let the sum of $n$ terms of the given sequence be $S_{n}$. Then,

$$
\begin{aligned}
S_{n} & =a_{1}+a_{2}+a_{3}+\ldots+a_{n} \\
& =\left(3^{1}+5 \times 1\right)+\left(3^{2}+5 \times 2\right)+\left(3^{3}+5 \times 3\right)+\ldots+\left(3^{n}+5 \times n\right) \\
& =\left(3+3^{2}+3^{3}+\ldots+3^{n}\right)+(5 \times 1+5 \times 2+5 \times 3+\ldots+5 \times n) \\
& =\left(3+3^{2}+3^{3}+\ldots+3^{n}\right)+5 \times(1+2+3+\ldots+n) \\
& =\frac{3\left(3^{n}-1\right)}{(3-1)}+5 \times \frac{n}{2}(1+n) \\
& =\frac{3}{2}\left(3^{n}-1\right)+\frac{5}{2} \times n(n+1)
\end{aligned}
$$

Hence, the required sum is $\frac{3}{2}\left(3^{n}-1\right)+\frac{5}{2} n(n+1)$.

---

### Example 14

If $S_{1}, S_{2}$ and $S_{3}$ be respectively the sum of $n, 2 n$ and $3 n$ terms of a GP then prove that $S_{1}\left(S_{3}-S_{2}\right)=\left(S_{2}-S_{1}\right)^{2}$.

#### Solution

Let $a$ be the first term and $r$ be the common ratio of the given GP. Then,

$$
\begin{aligned}
S_{1}\left(S_{3}-S_{2}\right) & =\frac{a\left(1-r^{n}\right)}{(1-r)} \times\left\{\frac{a\left(1-r^{3 n}\right)}{(1-r)}-\frac{a\left(1-r^{2 n}\right)}{(1-r)}\right\} \\
& =\frac{a\left(1-r^{n}\right)}{(1-r)} \times \frac{\left(a-a r^{3 n}-a+a r^{2 n}\right)}{(1-r)} \\
& =\frac{a\left(1-r^{n}\right)}{(1-r)} \times \frac{a r^{2 n}\left(1-r^{n}\right)}{(1-r)} \\
& =\frac{a^{2} r^{2 n}\left(1-r^{n}\right)^{2}}{(1-r)^{2}}
\end{aligned}
$$

And, $\left(S_{2}-S_{1}\right)^{2}=\left\{\frac{a\left(1-r^{2 n}\right)}{(1-r)}-\frac{a\left(1-r^{n}\right)}{(1-r)}\right\}^{2}$

$$
\begin{aligned}
& =\frac{\left(a-a r^{2 n}-a+a r^{n}\right)^{2}}{(1-r)^{2}} \\
& =\frac{\left\{a r^{n}\left(1-r^{n}\right)\right\}^{2}}{(1-r)^{2}} \\
& =\frac{a^{2} r^{2 n}\left(1-r^{n}\right)^{2}}{(1-r)^{2}}
\end{aligned}
$$

Hence, $S_{1}\left(S_{3}-S_{2}\right)=\left(S_{2}-S_{1}\right)^{2}$.

---

### Example 15

If $S$ be the sum, $P$ be the product and $R$ be the sum of the reciprocals of $n$ terms in a GP, prove that $P^{2}=\left(\frac{S}{R}\right)^{n}$.

#### Solution

Let the given GP be $a, a r, a r^{2}, \ldots, a r^{(n-1)}$. Then,

$$
S=\frac{a\left(1-r^{n}\right)}{(1-r)} \tag{i}
$$

and

$$
P=\left[a \times a r \times a r^{2} \times \ldots \times a r^{(n-1)}\right]
$$

$$
\Rightarrow \quad P=a^{n} r^{[1+2+3+\ldots+(n-1)]}=a^{n} r^{\frac{1}{2}(n-1) n}
$$

$$
\Rightarrow \quad P^{2}=a^{2 n} r^{(n-1) n} \tag{ii}
$$

And, $R=\left\{\frac{1}{a}+\frac{1}{a r}+\ldots+\frac{1}{a r^{n-1}}\right\}=\left(\frac{1}{a}\right) \cdot \frac{\left\{\frac{1}{r^{n}}-1\right\}}{\left\{\frac{1}{r}-1\right\}}$

$$
\Rightarrow \quad R=\left(\frac{r}{a}\right) \cdot \frac{\left(1-r^{n}\right)}{(1-r) \cdot r^{n}} \tag{iii}
$$

$$
\Rightarrow \quad R=\frac{\left(1-r^{n}\right)}{a(1-r) \cdot r^{(n-1)}}
$$

On dividing (i) by (iii), we get

$$
\frac{S}{R}=\frac{a\left(1-r^{n}\right)}{(1-r)} \cdot \frac{a(1-r) \cdot r^{(n-1)}}{\left(1-r^{n}\right)}=a^{2} r^{(n-1)}
$$

$$
\therefore \quad\left(\frac{S}{R}\right)^{n}=\left\{a^{2} r^{(n-1)}\right\}^{n}=a^{2 n} \cdot r^{(n-1) n}=P^{2}
$$
[using (ii)].
Hence, $P^{2}=\left(\frac{S}{R}\right)^{n}$.

---

