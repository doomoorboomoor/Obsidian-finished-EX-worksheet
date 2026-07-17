## Sum of $n$ Terms of an AP

### Theorem 3
Prove that the sum of $n$ terms of an AP in which **first term** $= a$, **common difference** $= d$ and **last term** $= l$, is given by

$$
S_{n}=\frac{n}{2}(a+l) \text{ and } S_{n}=\frac{n}{2}\{2a+(n-1)d\}
$$

---

#### Proof
Consider an AP having $n$ terms in which **first term** $= a$, **common difference** $= d$ and **last term** $= l$.

Then,
$$
l = a+(n-1)d \quad \ldots \tag{i} \quad [\because l = n\text{th term}]
$$

Also, we may write the given AP as
$$
a, (a+d), (a+2d), \ldots, (l-2d), (l-d), l .
$$

Let $S_{n}$ be the sum of the first $n$ terms of this AP. Then,
$$
S_{n} = a+(a+d)+(a+2d)+\ldots+(l-2d)+(l-d)+l \tag{ii}
$$

Writing the above series in the reverse order, we get
$$
S_{n} = l+(l-d)+(l-2d)+\ldots+(a+2d)+(a+d)+a \tag{iii}
$$

Adding the corresponding terms of (ii) and (iii), we get
$$
\begin{aligned}
& 2S_{n} = (a+l)+(a+l)+(a+l)+\ldots n \text{ times } = n(a+l) \\
\Rightarrow & S_{n} = \frac{n}{2}(a+l) \\
\Rightarrow & S_{n} = \frac{n}{2}[a+a+(n-1)d] = \frac{n}{2}[2a+(n-1)d] \quad [\text{using (i)}].
\end{aligned}
$$

Hence, $S_{n} = \frac{n}{2}(a+l)$ and $S_{n} = \frac{n}{2}[2a+(n-1)d]$.

---

## Summary
Sum of $n$ terms of an AP $a, a+d, a+2d, \ldots, l$ is given by
$$
S_{n} = \frac{n}{2}(a+l) \text{ or } S_{n} = \frac{n}{2} \times \{2a+(n-1)d\}.
$$

---

## Solved Examples

### Example 1
Find the sum of first 24 terms of the AP 5, 8, 11, 14, ...

#### Solution:
Here $a=5$, $d=(8-5)=3$ and $n=24$.
Using the formula, $S_{n}=\frac{n}{2}\{2a+(n-1)d\}$, we get
$$
\begin{aligned}
S_{24} & = \frac{24}{2} \{2 \times 5+(24-1) \times 3\} \quad [\because a=5, d=3 \text{ and } n=24] \\
& = 12 \times (10+69) = 948.
\end{aligned}
$$
Hence, the sum of first 24 terms of the given AP is 948.

---

### Example 2
Find the sum $25+28+31+\ldots+100$.

#### Solution:
Here $a=25$, $d=(28-25)=3$ and $l=100$.
Let the total number of terms be $n$. Then,
$$
\begin{aligned}
T_{n}=100 & \Rightarrow a+(n-1)d=100 \\
& \Rightarrow 25+(n-1) \times 3=100 \\
& \Rightarrow 3n+22=100 \\
& \Rightarrow 3n=78 \Rightarrow n=26.
\end{aligned}
$$
$$
\begin{aligned}
\text{Required sum} & = \frac{n}{2}(a+l) \\
& = \frac{26}{2}(25+100) = 13 \times 125 = 1625.
\end{aligned}
$$
Hence, the required sum is 1625.

---

### Example 3
Find the sum $18+15\frac{1}{2}+13+\ldots+\left(-49\frac{1}{2}\right)$.

#### Solution:
We have, $\frac{31}{2}-18 = 13-\frac{31}{2} = \frac{-5}{2}$.
So, the given series is an arithmetic series.
Here, $a=18$, $d=\frac{-5}{2}$ and $l=\frac{-99}{2}$.
Let the given series contain $n$ terms. Then,
$$
\begin{aligned}
T_{n}=\frac{-99}{2} & \Rightarrow a+(n-1)d=\frac{-99}{2} \\
& \Rightarrow 18+(n-1) \times \left(\frac{-5}{2}\right) = \frac{-99}{2} \\
& \Rightarrow 36-5n+5 = -99 \\
& \Rightarrow -5n = -140 \Rightarrow n=28
\end{aligned}
$$
$$
\begin{aligned}
\therefore \text{ required sum} & = \frac{n}{2}(a+l) \\
& = \frac{28}{2}\left\{18-\frac{99}{2}\right\} = 14\left(\frac{36-99}{2}\right) = 7(-63) = -441
\end{aligned}
$$
Hence, the sum of the given series is -441.

---

### Example 4
Find the sum of first $n$ terms of an AP whose $n$th term is ($5n-1$). Hence, find the sum of first 20 terms.

#### Solution:
The $n$th term of the given AP is given by, $T_{n}=(5n-1)$.
Let $a$ be the first term and $d$ be the common difference of this AP. Then,
$$
\begin{aligned}
& a = T_{1} = (5 \times 1-1) = 4, T_{2} = (5 \times 2-1) = 9. \\
\therefore & d = (T_{2}-T_{1}) = (9-4) = 5. \\
\therefore & \text{ sum of first } n \text{ terms} = \frac{n}{2}\{2a+(n-1)d\} \\
& = \frac{n}{2} \times \{2 \times 4+(n-1) \times 5\} = \frac{1}{2}n(8+5n-5) = \frac{1}{2}n(5n+3).
\end{aligned}
$$
$\therefore$ sum of first 20 terms $= \frac{1}{2} \times 20 \times (5 \times 20+3) = 10 \times 103 = 1030$.
Hence, $S_{n}=\frac{1}{2}n(5n+3)$ and $S_{20}=1030$.

---

### Example 5
If the sum of first $n$ terms of an AP is $\frac{1}{2}(3n^{2}+7n)$ then find its $n$th term and hence, write its 20th term.

#### Solution:
We have, $S_{n} = \frac{1}{2}(3n^{2}+7n)$.
$$
\begin{aligned}
\therefore S_{n-1} & = \frac{1}{2}\{3(n-1)^{2}+7(n-1)\} = \frac{1}{2}\{3(n^2-2n+1)+7n-7\} \\
& = \frac{1}{2}\{3n^2-6n+3+7n-7\} = \frac{1}{2}(3n^{2}+n-4). \\
\therefore T_{n} & = (S_{n}-S_{n-1}) = \frac{1}{2}(3n^{2}+7n) - \frac{1}{2}(3n^{2}+n-4) \\
& = \frac{1}{2}(3n^{2}+7n-3n^{2}-n+4) = \frac{1}{2}(6n+4) = (3n+2).
\end{aligned}
$$
$\therefore n$th term $= (3n+2)$.
Hence, 20th term $= (3 \times 20+2) = 62$.

---

### Example 6
How many terms of the AP 3, 5, 7, 9, ... must be added to get the sum 120?

#### Solution:
Here, $a=3$ and $d=(5-3)=2$.
Let the required number of terms be $n$. Then,
$$
\begin{aligned}
S_{n}=120 & \Rightarrow \frac{n}{2}\{2a+(n-1)d\} = 120 \\
& \Rightarrow \frac{n}{2}\{2 \times 3+(n-1) \times 2\} = 120 \\
& \Rightarrow \frac{n}{2}(6+2n-2) = 120 \Rightarrow \frac{n}{2}(2n+4)=120 \\
& \Rightarrow n(n+2)=120 \Rightarrow n^{2}+2n-120=0 \\
& \Rightarrow n^{2}+12n-10n-120=0 \\
& \Rightarrow n(n+12)-10(n+12)=0 \Rightarrow (n+12)(n-10)=0 \\
& \Rightarrow n+12=0 \text{ or } n-10=0 \Rightarrow n=-12 \text{ or } n=10 \\
& \Rightarrow n=10 \quad [\because \text{number of terms cannot be negative}]
\end{aligned}
$$
Hence, the required number of terms is 10.

---

### Example 7
How many terms of the AP 17, 15, 13, 11, ... must be added to get the sum 72? Explain the double answer.

#### Solution:
Here, $a=17$ and $d=(15-17)=-2$.
Let the sum of $n$ terms be 72. Then,
$$
\begin{aligned}
S_{n}=72 & \Rightarrow \frac{n}{2}\{2a+(n-1)d\} = 72 \\
& \Rightarrow n\{2 \times 17+(n-1) \times (-2)\} = 144 \\
& \Rightarrow n(34-2n+2) = 144 \Rightarrow n(36-2n) = 144 \\
& \Rightarrow 36n - 2n^2 = 144 \Rightarrow 2n^{2}-36n+144 = 0 \\
& \Rightarrow n^{2}-18n+72 = 0 \Rightarrow n^{2}-12n-6n+72 = 0 \\
& \Rightarrow n(n-12)-6(n-12) = 0 \Rightarrow (n-12)(n-6)=0 \\
& \Rightarrow n=6 \text{ or } n=12.
\end{aligned}
$$
$\therefore$ sum of first 6 terms $=$ sum of first 12 terms $= 72$.
This means that the sum of all terms from 7th to 12th is zero.

---

### Example 8
The first and the last terms of an AP are 7 and 49 respectively. If sum of all its terms is 420, find its common difference.

#### Solution:
Let the given AP contain $n$ terms.
Here $a=7$, $l=49$ and $S_{n}=420$.
$$
\begin{aligned}
\therefore S_{n} & = \frac{n}{2}(a+l) \\
& \Rightarrow \frac{n}{2}(7+49)=420 \Rightarrow \frac{n}{2} \times 56=420 \\
& \Rightarrow 28n=420 \Rightarrow n=\frac{420}{28}=15.
\end{aligned}
$$
Thus, the given AP contains 15 terms and $T_{15}=49$.
Let $d$ be the common difference of the given AP. Then,
$$
\begin{aligned}
T_{15}=49 & \Rightarrow a+14d=49 \\
& \Rightarrow 7+14d=49 \\
& \Rightarrow 14d=42 \Rightarrow d=3
\end{aligned}
$$
Hence, the common difference of the given AP is 3.

---

### Example 9
The sum of the first 7 terms of an AP is 63 and the sum of its next 7 terms is 161. Find the 28th term of this AP.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP.
Then, using $S_{n}=\frac{n}{2}[2a+(n-1)d]$, we get
$$
\begin{align*}
S_{7} = \frac{7}{2}(2a+6d) & \Rightarrow 63 = 7(a+3d) \\
& \Rightarrow a+3d=9 \tag{i}
\end{align*}
$$
Clearly, the sum of first 14 terms $= 63+161 = 224$.
$$
\begin{align*}
\therefore S_{14}=224 & \Rightarrow \frac{14}{2}(2a+13d)=224 \\
& \Rightarrow 7(2a+13d)=224 \\
& \Rightarrow 2a+13d=32 \tag{ii}
\end{align*}
$$
Multiplying (i) by 2 and subtracting the result from (ii), we get
$$
(2a+13d) - 2(a+3d) = 32 - 2(9)
$$
$$
2a+13d - 2a - 6d = 32 - 18
$$
$$
7d=14 \Rightarrow d=2
$$
Putting $d=2$ in (i), we get $a+3(2)=9 \Rightarrow a=9-6=3$.
Thus, $a=3$ and $d=2$.
$\therefore$ 28th term of this AP is given by
$$
T_{28} = (a+27d) = (3+27 \times 2) = 3+54=57
$$
Hence, the 28th term of the given AP is 57.

---

### Example 10
The 14th term of an AP is twice its 8th term. If its 6th term is -8 then find the sum of its first 20 terms.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$$
\begin{align*}
T_{14}=2 \times T_{8} & \Rightarrow a+13d=2(a+7d) \\
& \Rightarrow a+13d=2a+14d \\
& \Rightarrow a+d=0 \tag{i}
\end{align*}
$$
Also, $T_{6}=-8 \Rightarrow a+5d=-8$. (ii)

Subtracting (i) from (ii):
$$
(a+5d)-(a+d) = -8 - 0 \Rightarrow 4d = -8 \Rightarrow d = -2
$$
From (i), $a+(-2)=0 \Rightarrow a=2$.
On solving (i) and (ii), we get $a=2$ and $d=-2$.
The sum of first 20 terms is given by
$$
\begin{aligned}
S_{20} & = \frac{n}{2}[2a+(n-1)d], \text{ where } n=20 \\
& = \left(\frac{20}{2}\right) \times \{(2 \times 2 + 19 \times (-2))\} \\
& = 10 \times (4-38) = 10 \times (-34) = -340.
\end{aligned}
$$
Hence, the required sum is -340.

---

### Example 11
The sum of 4th and 8th terms of an AP is 24 and the sum of its 6th and 10th terms is 44. Find the sum of first ten terms of the AP.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$$
\begin{align*}
T_{4}+T_{8}=24 & \Rightarrow (a+3d)+(a+7d)=24 \\
& \Rightarrow 2a+10d=24 \\
& \Rightarrow a+5d=12 \tag{i}
\end{align*}
$$
And, $T_{6}+T_{10}=44 \Rightarrow (a+5d)+(a+9d)=44$
$$
\begin{align*}
& \Rightarrow 2a+14d=44 \\
& \Rightarrow a+7d=22 \tag{ii}
\end{align*}
$$
Subtracting (i) from (ii):
$$
(a+7d)-(a+5d) = 22-12 \Rightarrow 2d = 10 \Rightarrow d=5
$$
Putting $d=5$ in (i):
$$
a+5(5)=12 \Rightarrow a+25=12 \Rightarrow a=-13
$$
On solving (i) and (ii), we get $a=-13$ and $d=5$.
$\therefore$ the sum of first 10 terms of the given AP is given by
$$
\begin{aligned}
S_{10} & = \left(\frac{10}{2}\right)(2a+9d) \quad \left[\text{using } S_{n}=\frac{n}{2}\{2a+(n-1)d\}\right] \\
& = 5 \times \{2 \times (-13)+9 \times 5\} = 5(-26+45) = 5 \times 19=95
\end{aligned}
$$
Hence, the sum of first 10 terms of the given AP is 95.

---

### Example 12
Sum of first 14 terms of an AP is 1505 and its first term is 10. Find its 25th term.

#### Solution:
Here $a=10$ and let $d$ be the common difference. Then,
$$
\begin{aligned}
S_{14}=1505 & \Rightarrow \frac{n}{2}[2a+(n-1)d]=1505, \text{ where } n=14 \text{ and } a=10 \\
& \Rightarrow \frac{14}{2}(2 \times 10+13d)=1505 \Rightarrow 7(20+13d)=1505 \\
& \Rightarrow (20+13d)=\frac{1505}{7}=215 \\
& \Rightarrow 13d=195 \Rightarrow d=\frac{195}{13} = 15
\end{aligned}
$$
Thus, $a=10$ and $d=15$.
$$
\therefore T_{25} = (a+24d) = (10+24 \times 15) = 10+360=370.
$$
Hence, the 25th term is 370.

---

### Example 13
In an AP of 50 terms, the sum of first 10 terms is 210 and the sum of its last 15 terms is 2565. Find the AP.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then, the sum of first $n$ terms is given by
$$
S_{n}=\frac{n}{2}\{2a+(n-1)d\}
$$
$$
\begin{align*}
\therefore S_{10}=\frac{10}{2}(2a+9d) & \Rightarrow 5(2a+9d)=210 \\
& \Rightarrow 2a+9d=42 \tag{i}
\end{align*}
$$
Sum of last 15 terms $= (S_{50}-S_{35})$.
$$
\begin{align*}
\therefore (S_{50}-S_{35}) & =2565 \\
& \Rightarrow \frac{50}{2}(2a+49d)-\frac{35}{2}(2a+34d)=2565 \\
& \Rightarrow 25(2a+49d) - \frac{35}{2}(2a+34d) = 2565 \\
& \Rightarrow 50a + 1225d - (35a + 595d) = 2565 \\
& \Rightarrow 15a+630d=2565 \\
& \Rightarrow a+42d=171 \tag{ii}
\end{align*}
$$
From (i), $2a=42-9d \Rightarrow a = 21 - \frac{9}{2}d$. Substitute into (ii):
$$
\begin{align*}
(21 - \frac{9}{2}d) + 42d &= 171 \\
21 + \frac{-9+84}{2}d &= 171 \\
\frac{75}{2}d &= 150 \Rightarrow d=4
\end{align*}
$$
Substitute $d=4$ into $a+42d=171$: $a+42(4)=171 \Rightarrow a+168=171 \Rightarrow a=3$.
On solving (i) and (ii), we get $a=3$ and $d=4$.
Hence, the required AP is 3, 7, 11, 15, 19, ...

---

### Example 14
The sum of first 6 terms of an AP is 42. The ratio of its 10th term to 30th term is $1:3$. Find the first and the 13th term of the AP.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$$
\begin{aligned}
& T_{10}=a+9d \text{ and } T_{30}=a+29d \\
\therefore & \frac{T_{10}}{T_{30}}=\frac{1}{3} \Rightarrow \frac{a+9d}{a+29d}=\frac{1}{3} \\
& \Rightarrow 3(a+9d) = a+29d \\
& \Rightarrow 3a+27d=a+29d \\
& \Rightarrow 2a=2d \Rightarrow a=d
\end{aligned}
$$
Also, $S_{n}=\frac{n}{2}[2a+(n-1)d]$ and $S_6 = 42$.
$$
\begin{aligned}
S_{6} & = \frac{6}{2}(2a+5d) = 3(2a+5d) = 42 \\
& \Rightarrow 2a+5d = 14
\end{aligned}
$$
Since $a=d$, we have $2a+5a=14 \Rightarrow 7a=14 \Rightarrow a=2$.
Thus, $a=2$ and $d=2$.
$$
\therefore \text{ 13th term, } T_{13}=(a+12d)=(2+12 \times 2)=2+24=26.
$$
Hence, the first term is 2 and the 13th term is 26.

---

### Example 15
If $S_{n}$ denotes the sum of first $n$ terms of an AP, prove that $S_{12}=3(S_{8}-S_{4})$.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$$
S_{n}=\frac{n}{2}[2a+(n-1)d].
$$
$$
\begin{aligned}
\therefore 3(S_{8}-S_{4}) & = 3\left[\frac{8}{2}(2a+7d)-\frac{4}{2}(2a+3d)\right] \\
& = 3[4(2a+7d)-2(2a+3d)] \\
& = 3[8a+28d-4a-6d] = 3[4a+22d] \\
& = 6(2a+11d)
\end{aligned}
$$
And,
$$
S_{12} = \frac{12}{2}(2a+11d) = 6(2a+11d)
$$
Hence, $S_{12}=3(S_{8}-S_{4})$.

---

### Example 16
If the sum of first $n, 2n$ and $3n$ terms of an AP be $S_{1}, S_{2}$ and $S_{3}$ respectively then prove that $S_{3}=3(S_{2}-S_{1})$.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$S_{1}=$ sum of first $n$ terms,
$S_{2}=$ sum of first $2n$ terms,
$S_{3}=$ sum of first $3n$ terms.
$$
\begin{aligned}
\therefore S_{1} & = \frac{n}{2}\{2a+(n-1)d\} \\
S_{2} & = \frac{2n}{2}\{2a+(2n-1)d\} = n\{2a+(2n-1)d\} \\
S_{3} & = \frac{3n}{2}\{2a+(3n-1)d\}
\end{aligned}
$$
Now, consider the right-hand side:
$$
\begin{aligned}
3(S_{2}-S_{1}) & = 3\left[ n\{2a+(2n-1)d\} - \frac{n}{2}\{2a+(n-1)d\} \right] \\
& = 3 \frac{n}{2} \left[ 2\{2a+(2n-1)d\} - \{2a+(n-1)d\} \right] \\
& = \frac{3n}{2} [4a + (4n-2)d - 2a - (n-1)d] \\
& = \frac{3n}{2} [2a + (4n-2 - n+1)d] \\
& = \frac{3n}{2} [2a + (3n-1)d] = S_{3}
\end{aligned}
$$
Hence, $S_{3}=3(S_{2}-S_{1})$.

---

### Example 17
If the sum of the first $p$ terms of an AP is the same as the sum of its first $q$ terms (where $p \neq q$) then show that the sum of its first $(p+q)$ terms is zero.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$$
\begin{align*}
S_{p}=S_{q} & \Rightarrow \frac{p}{2}[2a+(p-1)d]=\frac{q}{2}[2a+(q-1)d] \\
& \Rightarrow p[2a+(p-1)d] = q[2a+(q-1)d] \\
& \Rightarrow 2ap + p(p-1)d = 2aq + q(q-1)d \\
& \Rightarrow 2a(p-q) + [p(p-1) - q(q-1)]d = 0 \\
& \Rightarrow 2a(p-q) + [p^2-p - q^2+q]d = 0 \\
& \Rightarrow 2a(p-q) + [(p^2-q^2) - (p-q)]d = 0 \\
& \Rightarrow 2a(p-q) + [(p-q)(p+q) - (p-q)]d = 0
\end{align*}
$$
Since $p \neq q$, we can divide by $(p-q)$:
$$
\begin{align*}
& \Rightarrow 2a + [p+q-1]d = 0 \tag{i}
\end{align*}
$$
Sum of the first $(p+q)$ terms of the given AP is
$$
\begin{aligned}
S_{p+q} & = \frac{p+q}{2} \{2a+(p+q-1)d\} \\
& = \frac{p+q}{2} \{0\} \quad [\text{using (i)}] \\
& = 0
\end{aligned}
$$

---

### Example 18
If the sum of the first $m$ terms of an AP be $n$ and the sum of its first $n$ terms be $m$ then show that the sum of its first $(m+n)$ terms is $-(m+n)$.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$$
\begin{align*}
S_{m}=n & \Rightarrow \frac{m}{2}[2a+(m-1)d]=n \\
& \Rightarrow 2am+m(m-1)d=2n \tag{i}
\end{align*}
$$
And,
$$
\begin{align*}
S_{n}=m & \Rightarrow \frac{n}{2}[2a+(n-1)d]=m \\
& \Rightarrow 2an+n(n-1)d=2m \tag{ii}
\end{align*}
$$
On subtracting (ii) from (i), we get
$$
\begin{align*}
& (2am-2an) + [m(m-1)-n(n-1)]d = 2n-2m \\
& \Rightarrow 2a(m-n) + [m^2-m-n^2+n]d = -2(m-n) \\
& \Rightarrow 2a(m-n) + [(m^2-n^2)-(m-n)]d = -2(m-n) \\
& \Rightarrow 2a(m-n) + [(m-n)(m+n)-(m-n)]d = -2(m-n)
\end{align*}
$$
Since $m \neq n$, we divide by $(m-n)$:
$$
\begin{align*}
& \Rightarrow 2a+(m+n-1)d=-2 \tag{iii}
\end{align*}
$$
Sum of the first $(m+n)$ terms of the given AP
$$
\begin{aligned}
S_{m+n} & = \frac{m+n}{2}\{2a+(m+n-1)d\} \\
& = \frac{m+n}{2}(-2) = -(m+n) \quad [\text{using (iii)}]
\end{aligned}
$$
Hence, the sum of first $(m+n)$ terms of the given AP is $-(m+n)$.

---

### Example 19
The ratio of the sums of first $m$ and first $n$ terms of an AP is $m^{2}:n^{2}$. Show that the ratio of its $m$th and $n$th terms is $(2m-1):(2n-1)$.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP. Then,
$S_{m} =$ sum of first $m$ terms of the given AP;
$S_{n} =$ sum of first $n$ terms of the given AP.
$$
\begin{aligned}
\frac{S_{m}}{S_{n}}=\frac{m^{2}}{n^{2}} & \Rightarrow \frac{\frac{m}{2}[2a+(m-1)d]}{\frac{n}{2}[2a+(n-1)d]}=\frac{m^{2}}{n^{2}} \\
& \Rightarrow \frac{m[2a+(m-1)d]}{n[2a+(n-1)d]}=\frac{m^{2}}{n^{2}} \\
& \Rightarrow \frac{2a+(m-1)d}{2a+(n-1)d}=\frac{m}{n} \\
& \Rightarrow n[2a+(m-1)d] = m[2a+(n-1)d] \\
& \Rightarrow 2an+n(m-1)d = 2am+m(n-1)d \\
& \Rightarrow 2an+mnd-nd=2am+mnd-md \\
& \Rightarrow 2an-2am=nd-md \\
& \Rightarrow 2a(n-m)=d(n-m) \Rightarrow 2a=d \quad [\text{since } n \neq m]
\end{aligned}
$$
Now, the ratio of the $m$th and $n$th terms:
$$
\begin{aligned}
\frac{T_{m}}{T_{n}} & = \frac{a+(m-1)d}{a+(n-1)d} = \frac{a+(m-1)(2a)}{a+(n-1)(2a)} \quad [\because d=2a] \\
& = \frac{a(1+2(m-1))}{a(1+2(n-1))} = \frac{1+2m-2}{1+2n-2} = \frac{2m-1}{2n-1}
\end{aligned}
$$
Thus, the ratio is $(2m-1):(2n-1)$.

---

### Example 20
The ratio of the 11th term to the 18th term of an AP is $2:3$. Find the ratio of the 5th term to the 21st term, and also the ratio of the sum of the first 5 terms to the sum of first 21 terms.

#### Solution:
Let $a$ be the first term and $d$ be the common difference of the given AP.
Then,
$$
\begin{align*}
& \frac{T_{11}}{T_{18}} = \frac{2}{3} \Rightarrow \frac{a+(11-1)d}{a+(18-1)d}=\frac{2}{3} \\
& \Rightarrow \frac{a+10d}{a+17d}=\frac{2}{3} \Rightarrow 3(a+10d)=2(a+17d) \\
& \Rightarrow 3a+30d=2a+34d \\
& \Rightarrow a=4d \tag{i}
\end{align*}
$$
Ratio of 5th term to 21st term:
$$
\begin{aligned}
\frac{T_{5}}{T_{21}} & = \frac{a+(5-1)d}{a+(21-1)d} = \frac{a+4d}{a+20d} \\
& = \frac{4d+4d}{4d+20d} \quad [\text{from (i)}] \\
& = \frac{8d}{24d}=\frac{1}{3} = 1:3.
\end{aligned}
$$
Ratio of sum of first 5 terms to sum of first 21 terms:
$$
\begin{align*}
\frac{S_{5}}{S_{21}} & = \frac{\frac{5}{2}[2a+(5-1)d]}{\frac{21}{2}[2a+(21-1)d]} = \frac{5(2a+4d)}{21(2a+20d)} \\
& = \frac{10(a+2d)}{42(a+10d)} = \frac{5(a+2d)}{21(a+10d)} \\
& = \frac{5(4d+2d)}{21(4d+10d)} \quad [\text{from (i)}] \\
& = \frac{5(6d)}{21(14d)} = \frac{30d}{294d} = \frac{30}{294} = \frac{5}{49} = 5:49.
\end{align*}
$$

---

### Example 21
If the ratio of the sum of the first $n$ terms of two APs is $(7n+1):(4n+27)$ then find the ratio of their 9th terms.

#### Solution:
Let $a_{1}$ and $a_{2}$ be the first terms and $d_{1}$ and $d_{2}$ be the common difference of the two APs respectively.
Let $S_{n}$ and $S'_{n}$ be the sums of the first $n$ terms of the two APs and $T_{n}$ and $T'_{n}$ be their $n$th terms respectively.
Then,
$$
\begin{align*}
\frac{S_{n}}{S'_{n}} & = \frac{7n+1}{4n+27} \Rightarrow \frac{\frac{n}{2}[2a_{1}+(n-1)d_{1}]}{\frac{n}{2}[2a_{2}+(n-1)d_{2}]}=\frac{7n+1}{4n+27} \\
& \Rightarrow \frac{2a_{1}+(n-1)d_{1}}{2a_{2}+(n-1)d_{2}}=\frac{7n+1}{4n+27} \tag{i}
\end{align*}
$$
We want to find the ratio of the 9th terms, which is $\frac{T_9}{T'_9} = \frac{a_1+8d_1}{a_2+8d_2}$.
To get this form from equation (i), we need the coefficients of $d_1$ and $d_2$ to be 8. We can achieve this by setting $\frac{n-1}{2}=8$.
So, $n-1 = 16 \Rightarrow n=17$.
Replacing $n$ by 17 on both sides in (i), we get
$$
\begin{aligned}
\frac{2a_{1}+(17-1)d_{1}}{2a_{2}+(17-1)d_{2}} & = \frac{7 \times 17+1}{4 \times 17+27} \\
& \Rightarrow \frac{2a_{1}+16d_{1}}{2a_{2}+16d_{2}}=\frac{119+1}{68+27} = \frac{120}{95} \\
& \Rightarrow \frac{2(a_{1}+8d_{1})}{2(a_{2}+8d_{2})}=\frac{24}{19} \\
& \Rightarrow \frac{a_{1}+8d_{1}}{a_{2}+8d_{2}}=\frac{24}{19} \\
& \Rightarrow \frac{T_{9}}{T'_{9}}=\frac{24}{19}
\end{aligned}
$$
$\therefore$ required ratio $= 24:19$.

---

## Word Problems

### Example 22
Find the sum of all multiples of 7 lying between 500 and 900.

#### Solution:
All multiples of 7 lying between 500 and 900 are $504, 511, 518, \ldots, 896$.
This is an AP in which $a=504, d=7$ and $l=896$.
Let the given AP contain $n$ terms. Then,
$$
\begin{aligned}
T_{n}=896 & \Rightarrow a+(n-1)d=896 \\
& \Rightarrow 504+(n-1) \times 7=896 \\
& \Rightarrow (n-1) \times 7=392 \Rightarrow n-1 = 56 \Rightarrow n=57.
\end{aligned}
$$
$$
\begin{aligned}
\therefore \text{ required sum} & = \frac{n}{2}(a+l) \\
& = \frac{57}{2}(504+896) = \frac{57}{2} \times 1400 = 57 \times 700 = 39900.
\end{aligned}
$$
Hence, the required sum is 39900.

---

### Example 23
Find the sum of all 3-digit natural numbers which are multiples of 11.

#### Solution:
All 3-digit natural numbers, which are multiples of 11 are given as $110, 121, 132, \ldots, 990$.
This is an AP in which $a=110, d=11$ and $l=990$.
Let the given AP contain $n$ terms. Then,
$$
\begin{aligned}
T_{n}=990 & \Rightarrow a+(n-1)d=990 \\
& \Rightarrow 110+(n-1) \times 11=990 \\
& \Rightarrow (n-1) \times 11=880 \Rightarrow n-1=80 \Rightarrow n=81.
\end{aligned}
$$
$$
\begin{aligned}
\therefore \text{ required sum} & = \frac{n}{2}(a+l) = \frac{81}{2} \times (110+990) \\
& = \frac{81}{2} \times 1100 = 81 \times 550 = 44550.
\end{aligned}
$$
Hence, the required sum is 44550.

---

### Example 24
Ramkali required ₹2500 after 12 weeks to send her daughter to school. She saved ₹100 in the first week and increased her weekly saving by ₹20 every week. Find whether she will be able to send her daughter to school after 12 weeks. What value is generated in the above situation?

#### Solution:
The amounts saved by Ramkali in successive weeks are ₹100, ₹120, ₹140, ₹160, ... up to 12 terms.
These amounts form an AP in which $a=100, d=20$ and $n=12$.
Using $S_{n}=\frac{n}{2}[2a+(n-1)d]$, we get
$$
S_{12}=\frac{12}{2}[2 \times 100+11 \times 20] = 6(200+220) = (6 \times 420) = 2520.
$$
Since ₹2520 > ₹2500, Ramkali will be able to deposit her daughter's fees and so she can send her to school.
The value generated is the importance of regular and disciplined savings to achieve future goals.

---

### Example 25
200 logs are stacked in such a way that there are 20 logs in the bottom row, 19 in the next row, 18 in the next row, and so on. In how many rows are 200 logs placed and how many logs are there in the top row?

#### Solution:
Let the required number of rows be $n$. Then,
$$
20+19+18+\ldots \text{ to } n \text{ terms} = 200
$$
This is an arithmetic series in which $a=20, d=(19-20)=-1$ and $S_{n}=200$.
We know that $S_{n}=\frac{n}{2}\{2a+(n-1)d\}$.
$$
\begin{aligned}
\therefore & \frac{n}{2}\{2 \times 20+(n-1) \times (-1)\}=200 \\
& \Rightarrow \frac{n}{2}(40-n+1)=200 \\
& \Rightarrow n(41-n)=400 \Rightarrow 41n - n^2 = 400 \\
& \Rightarrow n^{2}-41n+400=0 \\
& \Rightarrow n^{2}-25n-16n+400=0 \Rightarrow n(n-25)-16(n-25)=0 \\
& \Rightarrow (n-25)(n-16)=0 \Rightarrow n=25 \text{ or } n=16.
\end{aligned}
$$
Case 1: $n=25$. The number of logs in the 25th row is $T_{25} = (a+24d) = 20+24 \times (-1)=-4$. This is meaningless as the number of logs cannot be negative. So, we reject the value $n=25$.

Case 2: $n=16$. The number of logs in the 16th row is $T_{16} = (a+15d) = 20+15 \times (-1)=20-15=5$. This is a valid solution.

Thus, there are 16 rows in the whole stack and there are 5 logs in the top row.

---

### Example 26
The production of TV sets in a factory increases uniformly by a fixed number every year. It produced 16000 sets in 6th year and 22600 in 9th year. Find the production during (i) first year (ii) 8th year (iii) first 6 years.

#### Solution:
Let the production during the first year be $a$ and let $d$ be the increase in production every year. Then,
$$
\begin{align*}
T_{6} & =16000 \Rightarrow a+5d=16000 \tag{i}\\
\text{and } T_{9} & =22600 \Rightarrow a+8d=22600 \tag{ii}
\end{align*}
$$
On subtracting (i) from (ii), we get
$$
3d=6600 \Rightarrow d=2200
$$
Putting $d=2200$ in (i), we get
$$
a+5 \times 2200=16000 \Rightarrow a+11000=16000 \Rightarrow a=5000.
$$
Thus, $a=5000$ and $d=2200$.

(i) Production during first year, $a=5000$.
(ii) Production during 8th year is given by
$$
T_{8} = (a+7d) = (5000+7 \times 2200) = (5000+15400) = 20400
$$
(iii) Production during first 6 years is given by
$$
\begin{aligned}
S_{6} & = \frac{6}{2}\{2a+5d\} = 3(2 \times 5000+5 \times 2200) \\
& = 3(10000+11000) = 3(21000) = 63000
\end{aligned}
$$

---

### Example 27
A spiral is made up of successive semicircles, with centres alternately at A and B, starting with centre at A, of radii $0.5 \text{ cm, } 1 \text{ cm, } 1.5 \text{ cm, } 2 \text{ cm, } \ldots$ as shown in the given figure. What is the total length of such a spiral made up of 13 consecutive semicircles? (Take $\pi=\frac{22}{7}$)
![](https://cdn.mathpix.com/cropped/2025_09_25_6a90a2ac4c85e1f600e0g-35.jpg?height=202&width=261&top_left_y=1494&top_left_x=938)

#### Solution:
Let $L_{1}, L_{2}, L_{3}, \ldots, L_{13}$ be the lengths of semicircles of radii $r_1=0.5 \text{ cm}, r_2=1 \text{ cm}, r_3=1.5 \text{ cm}, \ldots, r_{13}=13 \times 0.5 = 6.5 \text{ cm}$ respectively. The length of a semicircle is $\pi r$.
$$
\begin{aligned}
L_{1} & = (\pi \times 0.5) \text{ cm} = \frac{\pi}{2} \text{ cm} \\
L_{2} & = (\pi \times 1) \text{ cm} = \pi \text{ cm} = 2\left(\frac{\pi}{2}\right) \text{ cm} \\
L_{3} & = (\pi \times 1.5) \text{ cm} = 3\left(\frac{\pi}{2}\right) \text{ cm} \\
... \\
L_{13} & = \left(\pi \times 6.5\right) \text{ cm} = 13\left(\frac{\pi}{2}\right) \text{ cm}
\end{aligned}
$$
Total length of the spiral $= L_{1}+L_{2}+L_{3}+\ldots+L_{13}$
$$
\begin{aligned}
& = \left\{\frac{\pi}{2} + 2\left(\frac{\pi}{2}\right) + 3\left(\frac{\pi}{2}\right) + \ldots + 13\left(\frac{\pi}{2}\right)\right\} \text{ cm} \\
& = \frac{\pi}{2}(1+2+3+\ldots+13) \text{ cm}
\end{aligned}
$$
The sum $1+2+3+\ldots+13$ is an AP with $n=13, a=1, l=13$.
The sum is $\frac{n}{2}(a+l) = \frac{13}{2}(1+13) = \frac{13}{2} \times 14 = 91$.
$$
\begin{aligned}
\text{Total Length} & = \frac{\pi}{2} \times 91 = \frac{1}{2} \times \frac{22}{7} \times 91 \\
& = 11 \times 13 = 143 \text{ cm}.
\end{aligned}
$$
Hence, the required length of the spiral is 143 cm.

---

### Example 28
A ladder has rungs 25 cm apart. The rungs decrease uniformly in length from 45 cm at the bottom to 25 cm at the top. If the top and bottom rungs are 2.5 m apart, what is the length of the wood required for the rungs?
![](https://cdn.mathpix.com/cropped/2025_09_25_6a90a2ac4c85e1f600e0g-36.jpg?height=563&width=322&top_left_y=716&top_left_x=877)

#### Solution:
The distance between the top and bottom rungs is $2.5 \text{ m} = 250 \text{ cm}$. The gap between two consecutive rungs is 25 cm.
Number of gaps $= \frac{250}{25} = 10$.
Number of rungs = Number of gaps + 1 = $10+1=11$.
The lengths of the rungs form an AP.
The first term (bottom rung) is $a=45$ cm.
The last term (top rung, which is the 11th rung) is $l=25$ cm.
The number of rungs is $n=11$.
The total length of the wood required is the sum of this AP.
$$
\text{Total length } = S_{n} = \frac{n}{2}(a+l) = \frac{11}{2}(45+25) = \frac{11}{2} \times 70 = 11 \times 35 = 385 \text{ cm}.
$$
Hence, the required length of the wood to form these rungs is 385 cm or 3.85 m.

---

### Example 29
The houses of a row in a colony are numbered consecutively from 1 to 49. Show that there is a value of $x$ such that the sum of the numbers of the houses preceding the house numbered $x$ is equal to the sum of the numbers of the houses following it. Find the value of $x$.

#### Solution:
We are given an AP: $1, 2, 3, \ldots, (x-1), x, (x+1), \ldots, 49$.
The condition is that the sum of numbers of houses before house $x$ equals the sum of numbers of houses after house $x$.
Sum of numbers before $x = 1+2+\ldots+(x-1) = S_{x-1}$.
Sum of numbers after $x = (x+1)+(x+2)+\ldots+49$.
This can also be written as (Sum of all numbers from 1 to 49) - (Sum of numbers from 1 to $x$).
So, $S_{x-1} = S_{49}-S_{x}$.
Using the formula $S_{n} = \frac{n(n+1)}{2}$ (which is a special case of AP sum with $a=1, d=1$), we have:
$$
\begin{aligned}
& \frac{(x-1)(x-1+1)}{2} = \frac{49(49+1)}{2} - \frac{x(x+1)}{2} \\
& \Rightarrow \frac{x(x-1)}{2} = \frac{49 \times 50}{2} - \frac{x(x+1)}{2} \\
& \Rightarrow x(x-1) = 2450 - x(x+1) \\
& \Rightarrow x^2 - x = 2450 - x^2 - x \\
& \Rightarrow 2x^2 = 2450 \\
& \Rightarrow x^2 = 1225 \Rightarrow x = \sqrt{1225} = 35
\end{aligned}
$$
Hence, $x=35$.

---

### Example 30
Find the middle term of the sequence formed by all three-digit numbers which leave a remainder 3 when divided by 4. Also, find the sum of all numbers on both sides of the middle term.

#### Solution:
The three-digit numbers which leave a remainder 3 when divided by 4 are of the form $4k+3$.
Smallest 3-digit number: $100 = 4 \times 25$. Next number is $103 = 4 \times 25 + 3$.
Largest 3-digit number: $999 = 4 \times 249 + 3$.
The sequence is $103, 107, 111, \ldots, 999$.
This is an AP with $a=103$, $d=4$, and $l=999$.
Let the total number of terms be $n$.
$$
\begin{aligned}
T_{n}=999 & \Rightarrow a+(n-1)d=999 \\
& \Rightarrow 103+(n-1) \times 4=999 \\
& \Rightarrow (n-1) \times 4=896 \Rightarrow n-1=224 \Rightarrow n=225.
\end{aligned}
$$
Since $n=225$ is odd, the middle term is the $(\frac{n+1}{2})$th term = $(\frac{225+1}{2})$th term = 113th term.
$$
T_{113} = (a+112d) = (103+112 \times 4) = 103+448=551.
$$
The middle term is 551.
There are 112 terms before the middle term and 112 terms after it.
Sum of numbers before the middle term ($S_{112}$):
$$
S_{112} = \frac{112}{2}(2a + (112-1)d) = 56(2 \times 103 + 111 \times 4) = 56(206+444) = 56 \times 650 = 36400.
$$
Sum of numbers after the middle term:
This is the sum of terms from $T_{114}$ to $T_{225}$. This can be calculated as $S_{225} - S_{113}$.
First, let's find $S_{225}$ and $S_{113}$.
$$
S_{225} = \frac{225}{2}(a+l) = \frac{225}{2}(103+999) = \frac{225}{2}(1102) = 225 \times 551 = 123975.
$$
$$
S_{113} = S_{112} + T_{113} = 36400 + 551 = 36951.
$$
Sum of numbers after middle term = $S_{225} - S_{113} = 123975 - 36951 = 87024$.

Sum of all numbers on LHS of the middle term is 36400.
Sum of all numbers on RHS of the middle term is 87024.

---