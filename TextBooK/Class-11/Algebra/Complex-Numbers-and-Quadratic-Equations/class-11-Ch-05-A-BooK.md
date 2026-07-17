## Complex Numbers and Quadratic Equations

---

## IMAGINARY NUMBERS

If the square of a given number is negative then such a number is called an **imaginary number**.

For example, $\sqrt{-1}, \sqrt{-2}$, etc., are imaginary numbers.
We denote $\sqrt{-1}$ by the Greek letter **iota** '$\imath$', which is transliterated as '**$i$**'.
Thus, $\sqrt{-4}=2i, \sqrt{-9}=3i$ and $\sqrt{-5}=i\sqrt{5}$, etc.

---

## POWERS OF $i$

We have
$$
i^{0}=1, i^{1}=i, i^{2}=-1, i^{3}=i^{2} \times i=(-1) \times i=-i
$$
and
$$
I^{4}=i^{2} \times i^{2}=(-1) \times(-1)=1
$$
Thus, we have
$$
i^{0}=1, i^{1}=i, i^{2}=-1, i^{3}=-i, i^{4}=1
$$
Let us consider $i^{n}$, where $n$ is a positive integer and $n>4$.
On dividing $n$ by 4, let the quotient be $m$ and the remainder be $r$. Then, $n=4m+r$, where $0 \leq r<4$.
$$
\therefore \quad i^{n}=i^{4m+r}=i^{4m} \times i^{r}=\left(i^{4}\right)^{m} \times i^{r}=i^{r} . \quad\left[\because i^{4}=1\right]
$$

---

## EXAMPLES

- (i) $i^{98}=i^{4 \times 24+2}=\left(i^{4}\right)^{24} \times i^{2}=i^{2}=-1 . \quad\left[\because i^{4}=1\right]$
- (ii) $i^{-98}=\frac{1}{i^{98}}=\frac{1}{i^{98}} \times \frac{i^{2}}{i^{2}}=\frac{i^{2}}{i^{(98+2)}}=\frac{-1}{1}=-1 . \quad\left[\because i^{100}=1 \text{ and } i^{2}=-1\right]$

---

## SOLVED EXAMPLES

### Example 1:

Evaluate:
(i) $i^{23}$
(ii) $i^{998}$
(iii) $i^{-998}$
(iv) $i^{-71}$
(v) $(\sqrt{-1})^{91}$
(vi) $\left(i^{37} \times i^{-61}\right)$
(vii) $i^{-1}$

#### Solution:

We have

- (i) $i^{23}=i^{(4 \times 5)+3}=\left(i^{4}\right)^{5} \times i^{3}=i^{3}=-i . \quad\left[\because i^{4}=1\right]$
- (ii) $i^{998}=i^{4 \times 249+2}=\left(i^{4}\right)^{249} \times i^{2}=\left(1 \times i^{2}\right)=i^{2}=-1 . \quad\left[\because i^{4}=1\right]$
- (iii) $i^{-998}=\frac{1}{i^{998}} \times \frac{i^{2}}{i^{2}}=\frac{i^{2}}{i^{1000}}=\frac{-1}{1}=-1 . \quad\left[\because i^{1000}=\left(i^{4}\right)^{250}=1\right]$
- (iv) $i^{-71}=\frac{1}{i^{71}} \times \frac{i}{i}=\frac{i}{i^{72}}=\frac{i}{\left(i^{4}\right)^{18}}=\frac{i}{1}=i . \quad\left[\because i^{4}=1\right]$
- (v) $(\sqrt{-1})^{91}=i^{91}=i^{4 \times 22+3}=\left(i^{4}\right)^{22} \times i^{3}=1 \times(-i)=-i. \quad\left[\because i^{3}=i\right]$
- (vi)
$$
i^{37}=i^{4 \times 9+1}=\left(i^{4}\right)^{9} \times i=1 \times i=i .
$$
$$
i^{-61}=\frac{1}{i^{61}} \times \frac{i^{3}}{i^{3}}=\frac{i^{3}}{i^{64}}=\frac{-i}{\left(i^{4}\right)^{16}}=\frac{-i}{1}=-i .
$$
$$
\therefore \quad\left(i^{37}+i^{-61}\right)=i+(-i)=0 .
$$
- (vii) $i^{-1}=\frac{1}{i}=\frac{1}{i} \times \frac{i^{3}}{i^{3}}=\frac{-i}{i^{4}}=\frac{-i}{1}=-i$.

---

### Example 2:

Prove that:
(i) $i^{n}+i^{n+1}+i^{n+2}+i^{n+3}=0$
(ii) $i^{107}+i^{112}+i^{117}+i^{122}=0$
(iii) $(1+i)^{4} \times\left(1+\frac{1}{i}\right)^{4}=16$.

#### Solution:

We have

- (i)
$$
\begin{aligned}
& i^{n}+i^{n+1}+i^{n+2}+i^{n+3} \\\\
&=i^{n}\left(1+i+i^{2}+i^{3}\right) \\\\
&=i^{n}(1+i-1-i)=\left(i^{n} \times 0\right)=0 . \quad\left[\because i^{2}=-1 \text{ and } i^{3}=-i\right]
\end{aligned}
$$

- (ii)
$$
\begin{aligned}
& i^{107}+i^{112}+i^{117}+i^{122} \\\\
&=i^{107}\left(1+i^{5}+i^{10}+i^{15}\right)=i^{107}\left(1+i^{4} \times i+i^{8} \times i^{2}+i^{12} \times i^{3}\right) \\\\
&=i^{107}\left(1+i+i^{2}+i^{3}\right) \quad\left[\because i^{4}=1, i^{8}=1 \text{ and } i^{12}=1\right] \\\\
&=i^{107}(1+i-1-i)=\left(i^{107} \times 0\right)=0 . \quad\left[\because i^{2}=-1, i^{3}=-i\right]
\end{aligned}
$$

- (iii)
$$
\begin{aligned}
& (1+i)^{4} \times\left(1+\frac{1}{i}\right)^{4} \\\\
&=(1+i)^{4} \times\left(1+\frac{1}{i} \times \frac{i}{i}\right)^{4}=(1+i)^{4}(1-i)^{4} \quad\left[\because i^{2}=-1\right] \\\\
&=\{(1+i)(1-i)\}^{4}=\left(1-i^{2}\right)^{4}=\{1-(-1)\}^{4}=2^{4}=16
\end{aligned}
$$

---

### Example 3:

Show that $\left\{i^{23}+\left(\frac{1}{i}\right)^{29}\right\}^{2}=-4$.

#### Solution:

We have
$$
i^{23}=i^{(4 \times 5+3)}=\left(i^{4}\right)^{5} \times i^{3}=1 \times(-i)=-i . \quad\left[\because i^{4}=1 \text{ and } i^{3}=-i\right]
$$
$$
\left(\frac{1}{i}\right)^{29}=\frac{1}{i^{29}}=\frac{1}{i^{29}} \times \frac{i^{3}}{i^{3}}=\frac{i^{3}}{i^{32}}=\frac{-i}{1}=-i . \quad\left[\because i^{3}=-i \text{ and } i^{32}=1\right]
$$
$$
\therefore \quad\left\{i^{23}+\left(\frac{1}{i}\right)^{29}\right\}^{2}=(-i-i)^{2}=(-2 i)^{2}=4 i^{2}=4 \times(-1)=-4 .
$$

---

### Example 4:

Simplify:
(i) $(-2 i)\left(\frac{1}{6} i\right)$
(ii) $(-i)(3 i)\left(\frac{-1}{6} i\right)^{3}$
(iii) $4 \sqrt{-4}+5 \sqrt{-9}-3 \sqrt{-16}$

#### Solution:

We have

- (i) $(-2 i)\left(\frac{1}{6} i\right)=\left(-2 \times \frac{1}{6}\right) \times i^{2}=\frac{-1}{3} \times(-1)=\frac{1}{3}$.
- (ii)
$$
\begin{aligned}
(-i)(3 i)\left(\frac{-1}{6} i\right)^{3} &= \left(-3 i^{2}\right)\left(\frac{-1}{216} i^{3}\right) \\\\
&= (-3) \times(-1)\left[\frac{-1}{216} \times(-i)\right] \quad\left[\because i^{3}=-i\right] \\\\
&= \left(3 \times \frac{1}{216} \times i\right)=\frac{1}{72} i .
\end{aligned}
$$
- (iii)
$$
\begin{aligned}
& 4 \sqrt{-4}+5 \sqrt{-9}-3 \sqrt{-16} \\\\
&=(4 \times 2 i)+(5 \times 3 i)-(3 \times 4 i) \quad[\because \sqrt{-4}=2 i, \sqrt{-9}=3 i, \sqrt{-16}=4 i] \\\\
&=(8 i+15 i-12 i)=(11) i .
\end{aligned}
$$

---

### Example 5:

Show that $(-\sqrt{-1})^{4 n+3}=i$, where $n$ is a positive integer.

#### Solution:

We have
$$
\begin{aligned}
(-\sqrt{-1})^{4 n+3} &= (-i)^{4 n+3} \quad[\because \sqrt{-1}=i] \\\\
&=(-i)^{4 n} \times(-i)^{3} \\\\
&=\left\{(-i)^{4}\right\}^{n} \times\left(-i^{3}\right)=(1 \times i)=i \quad\left[\because(-i)^{4}=1 \text{ and } -i^{3}=-(-i)=i\right]
\end{aligned}
$$
Hence, $(-\sqrt{-1})^{4 n+3}=i$.

---

### Example 6:

Show that the sum $\left(1+i^{2}+i^{4}+\ldots+i^{2 n}\right)$ is 0 when $n$ is odd and 1 when $n$ is even.

#### Solution:

Let $S=1+i^{2}+i^{4}+\ldots+i^{2 n}$.
This is clearly a GP having $(n+1)$ terms with $a=1$ and $r=i^{2}=-1$.
$$
\begin{aligned}
\therefore \quad S &= \frac{a\left(1-r^{n+1}\right)}{(1-r)}=\frac{1 \times\left\{1-\left(i^{2}\right)^{n+1}\right\}}{\left(1-i^{2}\right)} \\\\
&= \frac{\left\{1-(-1)^{n+1}\right\}}{1-(-1)}=\frac{\left\{1-(-1)^{n+1}\right\}}{2} \\\\
&= \left\{\begin{array}{l}
\frac{1}{2}(1-1)=0, \text{ when } n \text{ is odd} \\\\
\frac{1}{2}(1+1)=1, \text{ when } n \text{ is even. }
\end{array}\right.
\end{aligned}
$$

---

## AN IMPORTANT RESULT

For any two real numbers $a$ and $b$, the result $\sqrt{a} \times \sqrt{b}=\sqrt{a b}$ is true only when at least one of the given numbers is either zero or positive.

Thus, $\sqrt{-2} \times \sqrt{-3}=\sqrt{(-2) \times(-3)}=\sqrt{6}$ is **wrong**.
In fact, $\sqrt{-2} \times \sqrt{-3}=(i \sqrt{2})(i \sqrt{3})=i^{2} \times \sqrt{6}=-\sqrt{6}$.

---

### Example 7:

Explain the fallacy:
$$
-1=(i \times i)=\sqrt{-1} \times \sqrt{-1}=\sqrt{(-1) \times(-1)}=\sqrt{1}=1
$$

#### Solution:

We know that for any real numbers $a$ and $b, \sqrt{a} \times \sqrt{b}=\sqrt{a b}$ is true only when at least one of $a$ and $b$ is either 0 or positive.
$\therefore \quad \sqrt{-1} \times \sqrt{-1} \neq \sqrt{(-1) \times(-1)}$.

---

### Example 8:

Evaluate:
(i) $\sqrt{-25} \times \sqrt{-49}$
(ii) $\sqrt{-36} \times \sqrt{16}$

#### Solution:

We have

- (i) $\sqrt{-25} \times \sqrt{-49}=(5 i) \times(7 i)=\left(35 \times i^{2}\right)=35 \times(-1)=-35$.
- (ii) $\sqrt{-36} \times \sqrt{16}=(6 i) \times 4=24 i$.

---

### Example 9:

Evaluate $\sqrt{-16}+3 \sqrt{-25}+\sqrt{-36}-\sqrt{-625}$.

#### Solution:

We have
$$
\begin{aligned}
& \sqrt{-16}+3 \sqrt{-25}+\sqrt{-36}-\sqrt{-625} \\\\
&=(4 i+3 \times 5 i+6 i-25 i)=(4 i+15 i+6 i-25 i)=0 .
\end{aligned}
$$

---

