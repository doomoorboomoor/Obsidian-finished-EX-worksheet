## Sum of $n$ Terms of an AP

### Theorem 1
Prove that the sum of $n$ terms of an AP with **first term** $a$ and **common difference** $d$ is given by:

I. $S_{n}=\frac{n}{2}(a+l)$, where $l$ is the last term.
II. $S_{n}=\frac{n}{2} \cdot[2 a+(n-1) d]$.

#### Proof:
Let us consider an AP containing $n$ terms with the **first term** $a$, the **common difference** $d$ and the **last term** $l$.
Let the sum of these $n$ terms be $S_{n}$. Then,

$$
S_{n}=a+(a+d)+(a+2 d)+\ldots+(l-2 d)+(l-d)+l . \quad \text{(i)}
$$

Writing the above series in a reverse order, we get

$$
S_{n}=l+(l-d)+(l-2 d)+\ldots+(a+2 d)+(a+d)+a . \quad \text{(ii)}
$$

Adding the corresponding terms of (i) and (ii), we get

$$
\begin{aligned}
& 2 S_{n}=\{(a+l)+(a+l)+\ldots \text { to } n \text { times }\}=n(a+l) \\
\therefore \quad & S_{n}=\frac{n}{2}(a+l) .
\end{aligned}
$$

But, the last term $l$ is the $n$-th term, so $l = a+(n-1) d$.

$$
\therefore \quad S_{n}=\frac{n}{2} \cdot\{a+a+(n-1) d\}=\frac{n}{2} \cdot\{2 a+(n-1) d\} .
$$

Hence, $S_{n}=\frac{n}{2} \cdot\{2 a+(n-1) d\}$.

---

## Summary

- **(i)** Sum of $n$ terms of an AP with the **first term** $a$ and the **last term** $l$ is given by
  $$
  S_{n}=\frac{n}{2}(a+l) .
  $$

- **(ii)** Sum of $n$ terms of an AP with the **first term** $a$ and the **common difference** $d$ is given by
  $$
  S_{n}=\frac{n}{2} \cdot\{2 a+(n-1) d\} .
  $$

---

## Solved Examples

### Example 1:

Find the sum of 23 terms of the AP $5,9,13,17, \ldots$.

#### Solution:

Here, $a=5$, $d=(9-5)=4$ and $n=23$.

Now, $S_{n}=\frac{n}{2} \times\{2 a+(n-1) \times d\}$.

$$
\begin{aligned}
\therefore \quad S_{23} & =\frac{23}{2} \times\{2 \times 5+(23-1) \times 4\} \\
& =\frac{23}{2} \times(10+88) \\
& =\left(\frac{23}{2} \times 98\right)=1127 .
\end{aligned}
$$

Hence, the sum of 23 terms of the given AP is **1127**.

---

### Example 2:

The first, second and the last terms of an AP are $a, b, c$ respectively. Prove that the sum of the AP is $\frac{(a+c)(b+c-2 a)}{2(b-a)}$.

#### Solution:

Let $d$ be the common difference of the given AP and let it contain $n$ terms. Then, $d=(b-a)$.

Now, $T_{n}=c \Rightarrow a+(n-1) d=c$

$$
\begin{aligned}
& \Rightarrow a+(n-1)(b-a)=c \\
& \Rightarrow(n-1)=\frac{(c-a)}{(b-a)} \\
& \Rightarrow n=\left\{\frac{(c-a)}{(b-a)}+1\right\}=\frac{(b+c-2 a)}{(b-a)} .
\end{aligned}
$$

The sum of the given AP is $\frac{n}{2}(a+l)$, where $l$ is the last term.

$$
\begin{aligned}
\text{Sum} & =\frac{(b+c-2 a)}{2(b-a)} \times(a+c) \quad\left[\because n=\frac{(b+c-2 a)}{(b-a)} \text{ and } l=c\right] \\
& =\frac{(a+c)(b+c-2 a)}{2(b-a)}
\end{aligned}
$$

---

### Example 3:

How many terms of the AP $-6, \frac{-11}{2},-5, \frac{-9}{2}, \ldots$ are needed to give the sum -25? Explain the double answer.

#### Solution:

Let the required number of terms be $n$. Then, $a=-6$, $d = \left\{\frac{-11}{2}-(-6)\right\}=\left(\frac{-11}{2}+6\right)=\frac{1}{2}$ and $S_{n}=-25$.

$$
\begin{aligned}
\therefore \quad S_{n}=-25 & \Rightarrow \frac{n}{2} \cdot[2 a+(n-1) d]=-25 \\
& \Rightarrow \frac{n}{2} \cdot\left[2 \times(-6)+(n-1) \cdot \frac{1}{2}\right]=-25 \\
& \Rightarrow \frac{n}{2} \cdot\left(-12 + \frac{n}{2} - \frac{1}{2}\right) = -25 \\
& \Rightarrow \frac{n}{2} \cdot\left(\frac{n}{2}-\frac{25}{2}\right)=-25 \\
& \Rightarrow \frac{n}{2} \cdot \frac{(n-25)}{2}=-25 \\
& \Rightarrow n(n-25)=-100 \\
& \Rightarrow n^{2}-25 n+100=0 \\
& \Rightarrow(n-5)(n-20)=0 \\
& \Rightarrow n=5 \text { or } n=20 .
\end{aligned}
$$

This shows that the **sum of the first 5 terms** is -25 and the **sum of the first 20 terms** is also -25. This means that the sum of all the terms from the 6th to the 20th is zero.

---

### Example 4:

Find the value of $x$ when $1+6+11+16+\ldots+x=148$.

#### Solution:

The given series is an arithmetic series in which $a=1$ and $d=(6-1)=5$. Let it contain $n$ terms. The last term is $x$.

Now, $S_{n}=148$

$$
\begin{aligned}
& \Rightarrow \quad \frac{n}{2} \cdot[2 a+(n-1) d]=148 \\
& \Rightarrow \quad \frac{n}{2} \cdot[2 \times 1+(n-1) \times 5]=148 \\
& \Rightarrow \quad n(2+5n-5) = 296 \\
& \Rightarrow \quad n(5 n-3)=296 \\
& \Rightarrow \quad 5 n^{2}-3 n-296=0 \\
& \Rightarrow \quad 5 n^{2}-40 n+37 n-296=0 \\
& \Rightarrow \quad 5 n(n-8)+37(n-8)=0 \\
& \Rightarrow \quad(n-8)(5 n+37)=0 \\
& \Rightarrow \quad n=8 \quad\left[\because n \neq \frac{-37}{5}\right] .
\end{aligned}
$$

Since there are 8 terms, $x$ is the 8th term ($T_8$).

$$
\therefore \quad x = T_{8}=a+(8-1)d = 1+(7 \times 5) = 36.
$$

Hence, $x=36$.

---

### Example 5:

Find the sum of all odd integers from 1 to 1001.

#### Solution:

The odd integers from 1 to 1001 are $1,3,5,7, \ldots, 999,1001$. This is an AP in which $a=1$, $d=(3-1)=2$ and $l=1001$.

Let the number of terms be $n$. Then, $T_{n}=1001$.

$$
\begin{aligned}
& \Rightarrow a+(n-1) d=1001 \\
& \Rightarrow 1+(n-1) \times 2=1001 \\
& \Rightarrow 2(n-1) = 1000 \\
& \Rightarrow n-1 = 500 \\
& \Rightarrow n=501 .
\end{aligned}
$$

Now, using the formula $S_{n}=\frac{n}{2}(a+l)$:

$$
\therefore \quad S_{501}=\frac{501}{2}(1+1001)=\frac{501}{2}(1002)=(501 \times 501)=251001.
$$

Hence, the required sum is **251001**.

---

### Example 6:

Find the sum of all natural numbers lying between 100 and 1000, which are multiples of 5.

#### Solution:

The required numbers are $105, 110, 115, \ldots, 995$. This is an AP in which $a=105$, $d=(110-105)=5$ and $l=995$.

Let the number of terms in this AP be $n$. Then, $T_{n}=995$.

$$
\begin{aligned}
& \Rightarrow a+(n-1) d=995 \\
& \Rightarrow 105+(n-1) \times 5=995 \\
& \Rightarrow 5(n-1) = 890 \\
& \Rightarrow(n-1)=\frac{890}{5}=178 \\
& \Rightarrow n=179 .
\end{aligned}
$$

Now, using the formula $S_{n}=\frac{n}{2}(a+l)$:

$$
\therefore \quad S_{179}=\frac{179}{2} \times(105+995) = \left(\frac{179}{2} \times 1100\right) = (179 \times 550)=98450 .
$$

Hence, the required sum is **98450**.

---

### Example 7:

Find the sum of integers from 1 to 100 that are divisible by 2 or 5.

#### Solution:

The required sum is calculated using the principle of inclusion-exclusion:
(Sum of integers divisible by 2) + (Sum of integers divisible by 5) - (Sum of integers divisible by 10)

- **Sum divisible by 2:** $2+4+6+\ldots+100$. This is an AP with $n=50$, $a=2$, $l=100$.
- **Sum divisible by 5:** $5+10+15+\ldots+100$. This is an AP with $n=20$, $a=5$, $l=100$.
- **Sum divisible by 10:** $10+20+30+\ldots+100$. This is an AP with $n=10$, $a=10$, $l=100$.

$$
\begin{aligned}
\text{Required Sum} & = \left(\frac{50}{2}(2+100)\right) + \left(\frac{20}{2}(5+100)\right) - \left(\frac{10}{2}(10+100)\right) \\
& = (25 \times 102) + (10 \times 105) - (5 \times 110) \\
& = (2550 + 1050 - 550) = 3050
\end{aligned}
$$

Hence, the required sum is **3050**.

---

### Example 8:

Find the sum of all two-digit numbers which when divided by 4 yield 1 as remainder.

#### Solution:

The required numbers form the series $13, 17, 21, 25, \ldots, 97$. This is an AP in which $a=13$, $d=(17-13)=4$ and $l=97$.

Let the number of terms be $n$. Then, $T_{n}=97$.

$$
\begin{aligned}
& \quad T_{n}=97 \Rightarrow a+(n-1) d=97 \\
& \quad \Rightarrow 13+(n-1) \times 4=97 \\
& \quad \Rightarrow 4(n-1) = 84 \\
& \quad \Rightarrow n-1 = 21 \\
& \quad \Rightarrow n=22.
\end{aligned}
$$

Now, using the formula for the sum:

$$
\therefore \quad \text{Required Sum} =\frac{n}{2}(a+l)=\frac{22}{2} \times(13+97)=(11 \times 110)=1210.
$$

Hence, the required sum is **1210**.

---

### Example 9:

The sum of $n$ terms of two arithmetic progressions are in the ratio $(3 n+8):(7 n+15)$. Find the ratio of their 12th terms.

#### Solution:

Let $a_{1}, d_{1}$ and $a_{2}, d_{2}$ be the first terms and common differences of the two APs respectively.

Given the ratio of their sums:
$$
\frac{S_{n,1}}{S_{n,2}} = \frac{\frac{n}{2} \cdot\left[2 a_{1}+(n-1) d_{1}\right]}{\frac{n}{2} \cdot\left[2 a_{2}+(n-1) d_{2}\right]}=\frac{3 n+8}{7 n+15}
$$
$$
\Rightarrow \quad \frac{2 a_{1}+(n-1) d_{1}}{2 a_{2}+(n-1) d_{2}}=\frac{3 n+8}{7 n+15} \quad \text{(i)}
$$

We need the ratio of their 12th terms, which is $\frac{T_{12,1}}{T_{12,2}} = \frac{a_{1}+11 d_{1}}{a_{2}+11 d_{2}}$.

To get this form from equation (i), we can multiply the numerator and denominator by 2:
$$
\frac{a_{1}+11 d_{1}}{a_{2}+11 d_{2}} = \frac{2 a_{1}+22 d_{1}}{2 a_{2}+22 d_{2}}
$$
We need to find a value of $n$ such that $(n-1) = 22$. This gives $n=23$.

Substitute $n=23$ into equation (i):
$$
\frac{2 a_{1}+(23-1) d_{1}}{2 a_{2}+(23-1) d_{2}} = \frac{3 \times 23+8}{7 \times 23+15}
$$
$$
\frac{2 a_{1}+22 d_{1}}{2 a_{2}+22 d_{2}} = \frac{69+8}{161+15} = \frac{77}{176} = \frac{7}{16}
$$

Hence, the ratio of the 12th terms of the given APs is **7:16**.

---

### Example 10:

In an AP, the first term is 2 and the sum of first five terms is one-fourth of the sum of next five terms. Show that its 20th term is -112 and the sum of its first 20 terms is -1100.

#### Solution:

Given $a=2$. The condition is:
(Sum of first 5 terms) = $\frac{1}{4}$ (Sum of next 5 terms)
$S_5 = \frac{1}{4} (T_6 + T_7 + T_8 + T_9 + T_{10})$

The sum of the next five terms can be written as $S_{10} - S_5$.
$$
\begin{aligned}
& \Rightarrow S_{5}=\frac{1}{4} \cdot\left(S_{10}-S_{5}\right) \\
& \Rightarrow 4 S_{5}=S_{10}-S_{5} \\
& \Rightarrow 5 S_{5}=S_{10}
\end{aligned}
$$
Now, substitute the formula for the sum:
$$
\begin{aligned}
& \Rightarrow 5 \times \frac{5}{2} \times[2 \times 2+(5-1) d]=\frac{10}{2} \times[2 \times 2+(10-1) d] \\
& \Rightarrow \frac{25}{2} [4+4d] = 5 [4+9d] \\
& \Rightarrow 25(2+2d) = 5(4+9d) \\
& \Rightarrow 5(2+2d) = 4+9d \\
& \Rightarrow 10+10d = 4+9d \\
& \Rightarrow d = -6.
\end{aligned}
$$
So, we have $a=2$ and $d=-6$.

Now, find the 20th term:
$$
T_{20} = a + (20-1)d = 2 + 19 \times (-6) = 2 - 114 = -112
$$
And the sum of the first 20 terms:
$$
S_{20}=\frac{20}{2} \times[2 \times 2+(20-1) \times(-6)] = 10 \times [4 + 19 \times (-6)] = 10 \times [4 - 114] = 10 \times (-110) = -1100.
$$

---

### Example 11:

The difference between any two consecutive interior angles of a polygon is $5^{\circ}$. If the smallest angle is $120^{\circ}$, find the number of sides of the polygon.

#### Solution:

Let the number of sides of the polygon be $n$.
The sum of its interior angles is given by $(n-2) \times 180^{\circ}$.

The angles are in an AP with the first term $a=120$ and common difference $d=5$.
The sum of these $n$ angles is $S_n$.

$$
\begin{aligned}
S_{n} &= \frac{n}{2} \cdot\{2 \times 120+(n-1) \times 5\} \\
\text{We have } S_n &= (n-2) \times 180
\end{aligned}
$$
Equating the two expressions for the sum:
$$
\begin{aligned}
& \Rightarrow \quad \frac{n}{2} \cdot\{240 + 5n - 5\} = 180n - 360 \\
& \Rightarrow \quad n(235 + 5n) = 360n - 720 \\
& \Rightarrow \quad 235n + 5n^2 = 360n - 720 \\
& \Rightarrow \quad 5n^2 - 125n + 720 = 0 \\
& \Rightarrow \quad n^2 - 25n + 144 = 0 \\
& \Rightarrow \quad (n-9)(n-16) = 0 \\
& \Rightarrow \quad n=9 \text{ or } n=16.
\end{aligned}
$$
We must check both solutions. An interior angle of a convex polygon must be less than $180^{\circ}$.
If $n=16$, the last angle is:
$T_{16} = a + (16-1)d = 120 + 15 \times 5 = 120 + 75 = 195^{\circ}$.
This is not possible for a convex polygon.

If $n=9$, the last angle is:
$T_9 = a + (9-1)d = 120 + 8 \times 5 = 120 + 40 = 160^{\circ}$, which is a valid angle.

$\therefore \quad n=9$.

Hence, the number of sides of the polygon is **9**.

---

### Example 12:

The income of a man is ₹ 400,000 in the first year and he receives an increase of ₹ 10,000 to his income per year for 19 years. Find the total amount he received in 20 years.

#### Solution:

The annual incomes form an AP with $a=400000$, $d=10000$ and $n=20$. We need to find the total amount received, which is the sum $S_{20}$.

Using the formula, $S_{n}=\frac{n}{2} \times[2 a+(n-1) d]$, we have

$$
\begin{aligned}
S_{20}&=\frac{20}{2} \times[2 \times 400000+19 \times 10000] \\
&=10 \times [800000 + 190000] \\
&=10 \times 990000=9900000 .
\end{aligned}
$$

Hence, the man received **₹ 9,900,000** as the total amount in 20 years.

---

### Example 13:

A man saved ₹ 660,000 in 20 years. In each succeeding year after the first year he saves ₹ 2000 more than what he saved in the previous year. How much did he save in the first year?

#### Solution:

The savings form an AP. We are given $S_{20}=660000$, $n=20$, $d=2000$. We need to find the first term, $a$.

Using the formula, $S_{n}=\frac{n}{2} \times[2 a+(n-1) d]$, we get:

$$
\begin{aligned}
S_{20} &= \frac{20}{2} \times[2 a+(20-1) \times 2000] \\
660000 &= 10 \times[2a+19 \times 2000] \\
66000 &= 2a + 38000 \\
2a &= 66000 - 38000 \\
2a &= 28000 \\
a &= 14000 .
\end{aligned}
$$

Hence, the man saved **₹ 14,000** in the first year.

---

### Example 14:

In a potato race, 20 potatoes are placed in a line at intervals of 4 metres with the first potato 24 metres from the starting point. A contestant is required to bring the potatoes back to the starting place, one at a time. How far would he run in bringing back all the potatoes?

#### Solution:

To bring the 1st potato, the contestant runs $2 \times 24 = 48$ m.
To bring the 2nd potato, at $24+4=28$ m, the contestant runs $2 \times 28 = 56$ m.
To bring the 3rd potato, at $28+4=32$ m, the contestant runs $2 \times 32 = 64$ m.
... and so on for 20 potatoes.

The total distance is the sum of an AP: $48+56+64+72+\ldots$ to 20 terms.
Here, $a=48$, $d=(56-48)=8$ and $n=20$.

$$
\begin{aligned}
\text{Total distance} &= S_{20} = \frac{20}{2} \times[2 \times 48+(20-1) \times 8] \text{ m} \\
&= 10 \times[96 + 19 \times 8] \text{ m} \\
&= 10 \times(96+152) \text{ m} \\
&= 10 \times 248 \text{ m} = 2480 \text{ m}.
\end{aligned}
$$

Hence, the total distance covered is **2480 m**.

---

### Example 15:

In a cricket tournament 16 school teams participated. A sum of ₹ 16,000 is to be awarded among themselves as prize money. If the team in the last place is awarded ₹ 550 in prize money and the award increases by the same amount for successive finishing places, how much amount will the team in the first place receive?

#### Solution:

The prizes form an AP. Let the first prize be $T_1$ and the last prize be $T_{16}$.
Let's consider the prizes in reverse order. The first term is $a=550$ (last prize), number of terms $n=16$, and the sum is $S_{16}=16000$. We need to find the last term of this sequence, which is the first prize.

Let the AP of prizes be $p_1, p_2, ..., p_{16}$, where $p_1$ is the first prize.
Then $p_{16}=550$ and $S_{16}=16000$.
Using the formula $S_n = \frac{n}{2}(a+l)$, where $a$ is the first term and $l$ is the last term.

$$
\begin{aligned}
& S_{16} = \frac{16}{2}(p_1 + p_{16}) \\
& 16000 = 8(p_1 + 550) \\
& \frac{16000}{8} = p_1 + 550 \\
& 2000 = p_1 + 550 \\
& p_1 = 2000 - 550 = 1450.
\end{aligned}
$$

Hence, the team in the first place receives **₹ 1,450**.

---

### Example 16:

The first term of an AP is $a$ and the sum of the first $p$ terms is zero. Show that the sum of the next $q$ terms is $\frac{-a(p+q) q}{(p-1)}$.

#### Solution:

Let the common difference of the AP be $d$.
Given $S_p=0$.

$$
\begin{align*}
S_{p}=0 & \Rightarrow \frac{p}{2} \times[2 a+(p-1) d]=0 \\
& \Rightarrow 2 a+(p-1) d=0 \quad (\text{since } p \neq 0) \\
& \Rightarrow d=\frac{-2 a}{(p-1)} \quad \text{(i)}
\end{align*}
$$

The sum of the next $q$ terms is the sum of the first $(p+q)$ terms minus the sum of the first $p$ terms.
Sum of next $q$ terms = $S_{p+q} - S_p$.
Since $S_p=0$, the required sum is just $S_{p+q}$.

$$
\begin{aligned}
S_{p+q} &= \frac{(p+q)}{2} \cdot[2 a+(p+q-1) d] \\
&= \frac{(p+q)}{2} \cdot\left[2 a+(p+q-1) \times \frac{(-2 a)}{(p-1)}\right] \quad \text{[from (i)]} \\
&= a(p+q) \cdot\left[1 - \frac{(p+q-1)}{(p-1)}\right] \\
&= a(p+q) \cdot\left[\frac{(p-1) - (p+q-1)}{p-1}\right] \\
&= a(p+q) \cdot\left[\frac{p-1 - p - q + 1}{p-1}\right] \\
&= a(p+q) \cdot\left[\frac{-q}{p-1}\right] = \frac{-a(p+q) q}{(p-1)} .
\end{aligned}
$$

---

### Example 17:

If the $m$-th term of an AP is $a$ and its $n$-th term is $b$, show that the sum of its $(m+n)$ terms is $\frac{(m+n)}{2} \cdot\left\{a+b+\frac{(a-b)}{(m-n)}\right\}$.

#### Solution:

Let the first term be $A$ and the common difference be $d$.
Given:
$T_m = A+(m-1)d = a \quad \text{(i)}$
$T_n = A+(n-1)d = b \quad \text{(ii)}$

Subtracting (ii) from (i):
$(m-1-n+1)d = a-b$
$$
(m-n) d=(a-b) \Rightarrow d=\frac{(a-b)}{(m-n)} \quad \text{(iii)}
$$

Adding (i) and (ii):
$$
\begin{aligned}
& 2 A+(m-1+n-1) d=a+b \\
& 2 A+(m+n-2) d=a+b \\
\end{aligned}
$$

We need to find $S_{m+n} = \frac{(m+n)}{2} \cdot[2 A+(m+n-1) d]$.
Let's manipulate the expression from adding (i) and (ii):
$$
\begin{aligned}
& 2A + (m+n-1)d - d = a+b \\
& 2A + (m+n-1)d = a+b+d
\end{aligned}
$$
Substitute the value of $d$ from (iii):
$$
2A+(m+n-1)d = a+b+\frac{a-b}{m-n}
$$
Now, substitute this into the sum formula:
$$
S_{m+n} = \frac{(m+n)}{2} \cdot \left[ a+b+\frac{a-b}{m-n} \right]
$$

---

### Example 18:

If the ratio of the sums of $m$ and $n$ terms of an AP be $(m^{2}: n^{2})$, show that the ratio of their $m$-th and $n$-th terms is $(2 m-1):(2 n-1)$.

#### Solution:

Let the first term be $a$ and the common difference be $d$.
Given:
$$
\begin{aligned}
\frac{S_{m}}{S_{n}} &= \frac{m^{2}}{n^{2}} \\
& \Rightarrow \frac{\frac{m}{2} \cdot[2 a+(m-1) d]}{\frac{n}{2} \cdot[2 a+(n-1) d]}=\frac{m^{2}}{n^{2}} \\
& \Rightarrow \frac{2 a+(m-1) d}{2 a+(n-1) d}=\frac{m}{n} \\
& \Rightarrow n[2 a+(m-1) d]=m[2 a+(n-1) d] \\
& \Rightarrow 2an + mn d - nd = 2am + mn d - md \\
& \Rightarrow 2an - 2am = nd - md \\
& \Rightarrow 2a(n-m) = d(n-m)
\end{aligned}
$$
Since $m \neq n$, we can divide by $(n-m)$:
$$
d=2a
$$

Now, find the ratio of the $m$-th and $n$-th terms:
$$
\begin{aligned}
\frac{T_m}{T_n} &= \frac{a+(m-1)d}{a+(n-1)d} \\
&= \frac{a+(m-1)(2a)}{a+(n-1)(2a)} \\
&= \frac{a[1+2(m-1)]}{a[1+2(n-1)]} \\
&= \frac{1+2m-2}{1+2n-2} = \frac{2m-1}{2n-1}
\end{aligned}
$$
Hence, the ratio is **(2m-1):(2n-1)**.

---