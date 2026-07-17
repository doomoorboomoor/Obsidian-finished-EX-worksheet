# Some Special Series

## Sum of First n Natural Numbers

**Theorem 1:** Prove that $(1+2+3+\ldots+n)=\frac{1}{2} n(n+1)$
$$
\text{i.e., } \sum_{k=1}^{n} k=\frac{1}{2} n(n+1)
$$

#### Proof:

Consider the series $(1+2+3+\ldots+n)$.
This is an arithmetic series in which $a=1$, $d=1$ and $l=n$.

$$
\therefore S_{n}=\frac{n}{2}(1+n) \Rightarrow S_{n}=\frac{1}{2} n(n+1) \quad\left[\because S_{n}=\frac{1}{2}(a+l)\right]
$$

Hence, $\sum_{k=1}^{n} k=\frac{1}{2} n(n+1)$.

---

## Sum of the Squares of First n Natural Numbers

**Theorem 2:** Prove that $(1^{2}+2^{2}+3^{2}+\ldots+n^{2})=\frac{1}{6} n(n+1)(2 n+1)$
$$
\text{i.e., } \sum_{k=1}^{n} k^{2}=\frac{1}{6} n(n+1)(2 n+1)
$$

#### Proof:

Let $S_{n}=1^{2}+2^{2}+3^{2}+\ldots+n^{2}$.
Consider the identity: $k^{3}-(k-1)^{3}=3 k^{2}-3 k+1$.

Putting $k=1,2,3, \ldots,(n-1), n$ successively in (i), we get

$$
\begin{aligned}
1^{3}-0^{3} &= 3 \cdot 1^{2}-3 \cdot 1+1 \\
2^{3}-1^{3} &= 3 \cdot 2^{2}-3 \cdot 2+1 \\
3^{3}-2^{3} &= 3 \cdot 3^{2}-3 \cdot 3+1 \\
\ldots \quad \ldots & \quad \ldots \quad \ldots \quad \ldots \\
(n-1)^{3}-(n-2)^{3} &= 3 \cdot(n-1)^{2}-3 \cdot(n-1)+1 \\
n^{3}-(n-1)^{3} &= 3 \cdot n^{2}-3 \cdot n+1
\end{aligned}
$$

Adding columnwise, we get

$$
\begin{aligned}
& \left(n^{3}-0^{3}\right)=3\left(1^{2}+2^{2}+3^{2}+\ldots+n^{2}\right)-3(1+2+3+\ldots+n)+n \\
\Rightarrow & n^{3}=3 \cdot \sum_{k=1}^{n} k^{2}-3 \cdot \frac{1}{2} n(n+1)+n \quad\left[\because(1+2+3+\ldots+n)=\frac{1}{2} n(n+1)\right] \\
\Rightarrow & 3\left(\sum_{k=1}^{n} k^{2}\right)=n^{3}+\frac{3}{2} n(n+1)-n=\frac{1}{2}\left(2 n^{3}+3 n^{2}+n\right) \\
\Rightarrow & \left[\sum_{k=1}^{n} k^{2}\right]=\frac{1}{6}\left(2 n^{3}+3 n^{2}+n\right)=\frac{1}{6} n\left(2 n^{2}+3 n+1\right)=\frac{1}{6} n(n+1)(2 n+1)
\end{aligned}
$$

Hence, $\sum_{k=1}^{n} k^{2}=\frac{1}{6} n(n+1)(2 n+1)$.

---

## Sum of the Cubes of First n Natural Numbers

**Theorem 3:** Prove that $(1^{3}+2^{3}+3^{3}+\ldots+n^{3})=\left\{\frac{1}{2} n(n+1)\right\}^{2}$
$$
\text{i.e., } \sum_{k=1}^{n} k^{3}=\left\{\frac{1}{2} n(n+1)\right\}^{2}
$$

#### Proof:

Let $S_{n}=1^{3}+2^{3}+3^{3}+\ldots+n^{3}$.
Consider the identity: $k^{4}-(k-1)^{4}=4 k^{3}-6 k^{2}+4 k-1$.

Putting $k=1,2,3, \ldots,(n-1), n$ successively in (i), we get

$$
\begin{aligned}
1^{4}-0^{4} &= 4 \cdot 1^{3}-6 \cdot 1^{2}+4 \cdot 1-1 \\
2^{4}-1^{4} &= 4 \cdot 2^{3}-6 \cdot 2^{2}+4 \cdot 2-1 \\
3^{4}-2^{4} &= 4 \cdot 3^{3}-6 \cdot 3^{2}+4 \cdot 3-1 \\
\cdots \quad \cdots & \quad \cdots \quad \cdots \quad \cdots \quad \cdots \\
(n-1)^{4}-(n-2)^{4} &= 4 \cdot(n-1)^{3}-6 \cdot(n-1)^{2}+4 \cdot(n-1)-1 \\
n^{4}-(n-1)^{4} &= 4 \cdot n^{3}-6 \cdot n^{2}+4 \cdot n-1
\end{aligned}
$$

Adding columnwise, we get

$$
\begin{aligned}
& \left(n^{4}-0^{4}\right)=4 \cdot\left\{1^{3}+2^{3}+3^{3}+\ldots+n^{3}\right\}-6 \cdot\left\{1^{2}+2^{2}+3^{2}+\ldots+n^{2}\right\} \\
& \quad +4 \cdot\{1+2+3+\ldots+n\}-(1+1+1+\ldots \text{ to } n \text{ terms}) \\
\Rightarrow & n^{4}=4 \cdot\left(\sum_{k=1}^{n} k^{3}\right)-6 \cdot\left(\sum_{k=1}^{n} k^{2}\right)+4 \cdot\left(\sum_{k=1}^{n} k\right)-n \\
\Rightarrow & n^{4}=4 \cdot\left(\sum_{k=1}^{n} k^{3}\right)-6 \cdot \frac{1}{6} n(n+1)(2 n+1)+4 \cdot \frac{1}{2} n(n+1)-n \\
& \left\{\because \sum_{k=1}^{n} k^{2}=\frac{1}{6} n(n+1)(2 n+1) \text{ and } \sum_{k=1}^{n} k=\frac{1}{2} n(n+1)\right\} \\
\Rightarrow & 4 \cdot\left(\sum_{k=1}^{n} k^{3}\right)=n^{4}+n(n+1)(2 n+1)-2 n(n+1)+n \\
\Rightarrow & \left(\sum_{k=1}^{n} k^{3}\right)=\frac{1}{4} \cdot\left(n^{4}+2 n^{3}+n^{2}\right)=\frac{1}{4} n^{2}\left(n^{2}+2 n+1\right)=\left\{\frac{1}{2} n(n+1)\right\}^{2} \\
\therefore & \left(\sum_{k=1}^{n} k^{3}\right)=\left\{\frac{1}{2} n(n+1)\right\}^{2} \\
\text{i.e., } & \left(1^{3}+2^{3}+3^{3}+\ldots+n^{3}\right)=\left\{\frac{1}{2} n(n+1)\right\}^{2}
\end{aligned}
$$

---

## Sum of the Cubes of First n Odd Natural Numbers

**Theorem 4:** Prove that $[1^{3}+3^{3}+5^{3}+\ldots(2 n-1)^{3}]=n^{2}(2 n^{2}-1)$
$$
\text{i.e., } \sum_{k=1}^{n}(2 k-1)^{3}=n^{2}\left(2 n^{2}-1\right)
$$

#### Proof:

Let $S_{n}=1^{3}+3^{3}+5^{3}+\ldots+(2 n-1)^{3}$.
Then, $S_{n}=\sum_{k=1}^{n}(2 k-1)^{3}$.

$$
\begin{aligned}
S_n &=\sum_{k=1}^{n}\left(8 k^{3}-12 k^{2}+6 k-1\right) \\
&=8\left(\sum_{k=1}^{n} k^{3}\right)-12\left(\sum_{k=1}^{n} k^{2}\right)+6\left(\sum_{k=1}^{n} k\right)-n \quad [\because 1+1+\ldots \text{ to } n \text{ terms }=n] \\
&=8 \cdot \frac{1}{4} n^{2}(n+1)^{2}-12 \cdot \frac{1}{6} n(n+1)(2 n+1)+6 \cdot \frac{1}{2} n(n+1)-n \\
&=2 n^{2}(n+1)^{2}-2 n(n+1)(2 n+1)+3 n(n+1)-n \\
&=n(n+1) \cdot\{2 n(n+1)-2(2 n+1)+3\}-n \\
&=n(n+1)\left(2 n^{2}-2 n+1\right)-n=n \cdot\left\{(n+1)\left(2 n^{2}-2 n+1\right)-1\right\} \\
&=n\left(2 n^{3}-n\right)=n^{2}\left(2 n^{2}-1\right)
\end{aligned}
$$

$\therefore \left\{1^{3}+3^{3}+5^{3}+\ldots+(2 n-1)^{3}\right\}=n^{2}\left(2 n^{2}-1\right)$.

---

## Summary

- **(i)** $(1+2+3+\ldots+n)=\frac{1}{2} n(n+1)$
i.e., $\left(\sum_{k=1}^{n} k\right)=\frac{1}{2} n(n+1)$.

- **(ii)** $(1^{2}+2^{2}+3^{2}+\ldots+n^{2})=\frac{1}{6} n(n+1)(2 n+1)$
i.e., $\left(\sum_{k=1}^{n} k^{2}\right)=\frac{1}{6} n(n+1)(2 n+1)$.

- **(iii)** $(1^{3}+2^{3}+3^{3}+\ldots+n^{3})=\left\{\frac{1}{2} n(n+1)\right\}^{2}$
i.e., $\left(\sum_{k=1}^{n} k^{3}\right)=\left\{\frac{1}{2} n(n+1)\right\}^{2}$.

- **(iv)** $\left\{1^{3}+3^{3}+5^{3}+\ldots+(2 n-1)^{3}\right\}=n^{2}\left(2 n^{2}-1\right)$
i.e., $\sum_{k=1}^{n}(2 k-1)^{3}=n^{2}\left(2 n^{2}-1\right)$.

---

## Solved Examples

### Example 1:

If $S_{1}$, $S_{2}$ and $S_{3}$ are the sums of first $n$ natural numbers, their squares and their cubes respectively then show that $9 S_{2}^{2}=S_{3}\left(1+8 S_{1}\right)$.

#### Solution:

We have
$$
\begin{aligned}
S_{1} &=(1+2+3+\ldots+n) \Rightarrow S_{1}=\frac{1}{2} n(n+1) \\
S_{2} &=\left(1^{2}+2^{2}+3^{2}+\ldots+n^{2}\right) \Rightarrow S_{2}=\frac{1}{6} n(n+1)(2 n+1) \\
\text{and } S_{3} &=\left(1^{3}+2^{3}+3^{3}+\ldots+n^{3}\right) \Rightarrow S_{3}=\frac{1}{4} n^{2}(n+1)^{2}
\end{aligned}
$$

$$
\therefore 9 S_{2}^{2}=9 \times \frac{1}{36} \cdot n^{2}(n+1)^{2}(2 n+1)^{2}=\frac{1}{4} n^{2}(n+1)^{2}(2 n+1)^{2}
$$

And,
$$
\begin{aligned}
S_{3}\left(1+8 S_{1}\right) &=\frac{1}{4} n^{2}(n+1)^{2} \cdot\left\{1+8 \cdot \frac{1}{2} n(n+1)\right\} \\
&=\frac{1}{4} n^{2}(n+1)^{2}\left(4 n^{2}+4 n+1\right)=\frac{1}{4} n^{2}(n+1)^{2}(2 n+1)^{2}
\end{aligned}
$$

Hence, $9 S_{2}^{2}=S_{3}\left(1+8 S_{1}\right)$.

---

### Example 2:

Find the sum to $n$ terms of the series whose $n$th term is $n(n+3)$.

#### Solution:

We have, $T_{k}=k(k+3)=\left(k^{2}+3 k\right)$.
$\therefore$ sum to $n$ terms is given by

$$
\begin{aligned}
S_{n} & =\sum_{k=1}^{n} T_{k} \\
& =\sum_{k=1}^{n}\left(k^{2}+3 k\right)=\sum_{k=1}^{n} k^{2}+3 \sum_{k=1}^{n} k \\
& =\frac{1}{6} n(n+1)(2 n+1)+3 \cdot \frac{1}{2} n(n+1)=\frac{1}{6}\{n(n+1)(2 n+1)+9 n(n+1)\} \\
& =\frac{1}{6} n(n+1)(2 n+1+9)=\frac{1}{6} n(n+1) \cdot 2(n+5)=\frac{1}{3} n(n+1)(n+5)
\end{aligned}
$$

Hence, the required sum is $\frac{1}{3} n(n+1)(n+5)$.

---

### Example 3:

Find the sum to $n$ terms of the series whose $n$th term is $(2 n-1)^{2}$.

#### Solution:

We have, $T_{k}=(2 k-1)^{2}=\left(4 k^{2}-4 k+1\right)$.
$\therefore$ sum to $n$ terms is given by

$$
\begin{aligned}
S_{n} & =\sum_{k=1}^{n} T_{k} \\
& =\sum_{k=1}^{n}\left(4 k^{2}-4 k+1\right)=4 \cdot \sum_{k=1}^{n} k^{2}-4 \cdot \sum_{k=1}^{n} k+n \\
& =4 \cdot \frac{1}{6} n(n+1)(2 n+1)-4 \cdot \frac{1}{2} n(n+1)+n \\
& =\frac{2}{3} n(n+1)(2 n+1)-2 n(n+1)+n \\
& =\frac{1}{3} \cdot\{2 n(n+1)(2 n+1)-6 n(n+1)+3 n\} \\
& =\frac{1}{3}[n(n+1)\{2(2 n+1)-6\}+3 n]=\frac{1}{3} \cdot[n(n+1)(4 n-4)+3 n] \\
& =\frac{1}{3}\left(4 n\left(n^{2}-1\right)+3 n\right) = \frac{1}{3}\left(4 n^{3}-4n+3n\right) \\
& =\frac{1}{3}\left(4 n^{3}-n\right)=\frac{1}{3} n\left(4 n^{2}-1\right)
\end{aligned}
$$

Hence, the required sum is $\frac{1}{3} n\left(4 n^{2}-1\right)$.

---

### Example 4:

Find the sum to $n$ terms of the series whose $n$th term is $(n^{2}+2^{n})$.

#### Solution:

We have, $T_{k}=\left(k^{2}+2^{k}\right)$.

$$
\begin{aligned}
\therefore S_{n} & =\sum_{k=1}^{n} T_{k} \\
& =\sum_{k=1}^{n}\left(k^{2}+2^{k}\right)=\sum_{k=1}^{n} k^{2}+\sum_{k=1}^{n} 2^{k} \\
& =\frac{1}{6} n(n+1)(2 n+1)+\left(2+2^{2}+2^{3}+\ldots+2^{n}\right) \quad \left[\because \sum_{k=1}^{n} k^{2}=\frac{1}{6} n(n+1)(2 n+1)\right] \\
& =\frac{1}{6} n(n+1)(2 n+1)+\frac{2\left(2^{n}-1\right)}{(2-1)} \quad \left[\because 2+2^{2}+\ldots+2^{n} \text{ is a GP}\right] \\
& =\frac{1}{6} n(n+1)(2 n+1)+2\left(2^{n}-1\right)
\end{aligned}
$$

Hence, the required sum is $\frac{1}{6} n(n+1)(2 n+1)+2\left(2^{n}-1\right)$.

---

### Example 5:

Sum the series $3 \cdot 8+6 \cdot 11+9 \cdot 14+\ldots$ to $n$ terms.

#### Solution:

We have
$$
\begin{aligned}
T_{k} & =(\text{kth term of } 3,6,9, \ldots) \times (\text{kth term of } 8,11,14, \ldots) \\
& =\{3+(k-1) \times 3\} \times\{8+(k-1) \times 3\}=3 k(3 k+5) \\
& =\left(9 k^{2}+15 k\right)
\end{aligned}
$$

$$
\begin{aligned}
\therefore S_{n} & =\sum_{k=1}^{n} T_{k} \\
& =\sum_{k=1}^{n}\left(9 k^{2}+15 k\right)=9\left(\sum_{k=1}^{n} k^{2}\right)+15\left(\sum_{k=1}^{n} k\right) \\
& =9 \cdot\left\{\frac{1}{6} n(n+1)(2 n+1)\right\}+15 \cdot\left\{\frac{1}{2} n(n+1)\right\} \\
& =\frac{3}{2} n(n+1)\{(2 n+1)+5\} = \frac{3}{2} n(n+1)(2n+6) = 3 n(n+1)(n+3)
\end{aligned}
$$

Hence, the required sum is $3 n(n+1)(n+3)$.

---

### Example 6:

Sum the series $1 \cdot 2 \cdot 3+2 \cdot 3 \cdot 4+3 \cdot 4 \cdot 5+\ldots$ to $n$ terms.

#### Solution:

We have
$$
\begin{aligned}
T_{k} & = (\text{kth term of } 1,2,3, \ldots) \times (\text{kth term of } 2,3,4, \ldots) \times (\text{kth term of } 3,4,5, \ldots) \\
& = \{1+(k-1) \times 1\} \times \{2+(k-1) \times 1\} \times \{3+(k-1) \times 1\} \\
& = k(k+1)(k+2) = (k^2+k)(k+2) = k^3+2k^2+k^2+2k = k^3+3k^2+2k
\end{aligned}
$$

$$
\begin{aligned}
\therefore S_{n} & =\sum_{k=1}^{n} T_{k} \\
& =\sum_{k=1}^{n}\left(k^{3}+3 k^{2}+2 k\right)=\sum_{k=1}^{n} k^{3}+3 \sum_{k=1}^{n} k^{2}+2 \sum_{k=1}^{n} k \\
& =\frac{1}{4} n^{2}(n+1)^{2}+3 \cdot \frac{1}{6} n(n+1)(2 n+1)+2 \cdot \frac{1}{2} n(n+1) \\
& =\frac{1}{4} n(n+1)[n(n+1)+2(2 n+1)+4] \\
& =\frac{1}{4} n(n+1)\left[n^{2}+n+4 n+2+4\right] \\
& =\frac{1}{4} n(n+1)\left(n^{2}+5 n+6\right)=\frac{1}{4} n(n+1)(n+2)(n+3)
\end{aligned}
$$

Hence, the required sum is $\frac{1}{4} n(n+1)(n+2)(n+3)$.

---

### Example 7:

Find the sum of the series $1^{2}+3^{2}+5^{2}+\ldots$ to $n$ terms.

#### Solution:

We have
$$
\begin{aligned}
T_{k} & = \text{kth term of } (1^{2}, 3^{2}, 5^{2}, \ldots) \\
& =\{1+(k-1) \times 2\}^{2}=(2 k-1)^{2}=\left(4 k^{2}-4 k+1\right)
\end{aligned}
$$

$$
\begin{aligned}
\therefore S_{n} & =\sum_{k=1}^{n} T_{k} \\
& =\sum_{k=1}^{n}\left(4 k^{2}-4 k+1\right) \\
& =4 \sum_{k=1}^{n} k^{2}-4 \sum_{k=1}^{n} k+(1+1+\ldots n \text{ times}) \\
& =4 \cdot \frac{1}{6} n(n+1)(2 n+1)-4 \cdot \frac{1}{2} n(n+1)+n \\
& =\frac{n}{3} \cdot\{2(n+1)(2 n+1)-6(n+1)+3\} \\
& =\frac{n}{3} \cdot\{2(2n^2+3n+1) - 6n - 6 + 3\} \\
& =\frac{n}{3} \cdot\{4n^2+6n+2 - 6n - 3\} = \frac{n}{3}(4n^2-1)
\end{aligned}
$$

Hence, the required sum is $\frac{n}{3}\left(4 n^{2}-1\right)$.

---

### Example 8:

Find the sum $1^{2}+\left(1^{2}+2^{2}\right)+\left(1^{2}+2^{2}+3^{2}\right)+\ldots$ to $n$ terms.

#### Solution:

We have
$$
\begin{aligned}
T_{k} &= \left(1^{2}+2^{2}+3^{2}+\ldots+k^{2}\right) \\
&= \left\{\frac{1}{6} k(k+1)(2 k+1)\right\} \\
&= \frac{1}{6}\left(2 k^{3}+3 k^{2}+k\right)
\end{aligned}
$$

$$
\begin{aligned}
\therefore S_{n} & =\sum_{k=1}^{n} T_{k} \\
& =\frac{1}{6} \sum_{k=1}^{n}\left(2 k^{3}+3 k^{2}+k\right)=\frac{1}{6} \cdot 2 \sum_{k=1}^{n} k^{3}+\frac{1}{6} \cdot 3 \sum_{k=1}^{n} k^{2}+\frac{1}{6} \sum_{k=1}^{n} k \\
& =\frac{1}{3} \sum_{k=1}^{n} k^{3}+\frac{1}{2} \sum_{k=1}^{n} k^{2}+\frac{1}{6} \sum_{k=1}^{n} k \\
& =\frac{1}{3} \cdot\left\{\frac{1}{2} n(n+1)\right\}^{2}+\frac{1}{2} \cdot \frac{1}{6} n(n+1)(2 n+1)+\frac{1}{6} \cdot \frac{1}{2} n(n+1) \\
& =\frac{1}{12} n^{2}(n+1)^{2}+\frac{1}{12} n(n+1)(2 n+1)+\frac{1}{12} n(n+1) \\
& =\frac{1}{12} n(n+1) \cdot\{n(n+1)+(2 n+1)+1\} \\
& =\frac{1}{12} n(n+1) \cdot\{n^2+n+2n+2\} \\
& =\frac{1}{12} n(n+1) \cdot\{n^2+3n+2\} = \frac{1}{12} n(n+1)(n+1)(n+2) = \frac{1}{12} n(n+1)^{2}(n+2)
\end{aligned}
$$

Hence, the required sum is $\frac{1}{12} n(n+1)^{2}(n+2)$.

---

### Example 9:

Prove that $\frac{1 \times 2^{2}+2 \times 3^{2}+\ldots+n \times(n+1)^{2}}{1^{2} \times 2+2^{2} \times 3+\ldots+n^{2} \times(n+1)}=\frac{3 n+5}{3 n+1}$.

#### Solution:

We have
$k$th term of the numerator $=k(k+1)^{2}=\left(k^{3}+2 k^{2}+k\right)$.
$k$th term of the denominator $=k^{2}(k+1)=\left(k^{3}+k^{2}\right)$.

$$
\begin{aligned}
\therefore \text{LHS} & =\frac{\sum_{k=1}^{n}\left(k^{3}+2 k^{2}+k\right)}{\sum_{k=1}^{n}\left(k^{3}+k^{2}\right)}=\frac{\left(\sum_{k=1}^{n} k^{3}\right)+2 \cdot\left(\sum_{k=1}^{n} k^{2}\right)+\left(\sum_{k=1}^{n} k\right)}{\left(\sum_{k=1}^{n} k^{3}\right)+\left(\sum_{k=1}^{n} k^{2}\right)} \\
& =\frac{\frac{1}{4} n^{2}(n+1)^{2}+2 \cdot \frac{1}{6} n(n+1)(2 n+1)+\frac{1}{2} n(n+1)}{\frac{1}{4} n^{2}(n+1)^{2}+\frac{1}{6} n(n+1)(2 n+1)}
\end{aligned}
$$

Let's simplify the numerator and denominator by factoring out $\frac{1}{12}n(n+1)$:

Numerator: $\frac{1}{12}n(n+1)[3n(n+1)+4(2n+1)+6] = \frac{1}{12}n(n+1)[3n^2+3n+8n+4+6] = \frac{1}{12}n(n+1)[3n^2+11n+10] = \frac{1}{12}n(n+1)(n+2)(3n+5)$.

Denominator: $\frac{1}{12}n(n+1)[3n(n+1)+2(2n+1)] = \frac{1}{12}n(n+1)[3n^2+3n+4n+2] = \frac{1}{12}n(n+1)[3n^2+7n+2] = \frac{1}{12}n(n+1)(n+2)(3n+1)$.

$$
\text{LHS} = \frac{\frac{1}{12}n(n+1)(n+2)(3 n+5)}{\frac{1}{12}n(n+1)(n+2)(3 n+1)} = \frac{(3 n+5)}{(3 n+1)} = \text{RHS}
$$

---

### Example 10:

Find the sum of $n$ terms of the series $\frac{1}{(2 \times 5)}+\frac{1}{(5 \times 8)}+\frac{1}{(8 \times 11)}+\ldots$

#### Solution:

We have
$$
\begin{align*}
T_{k} & =\frac{1}{(\text{kth term of } 2,5,8, \ldots) \times (\text{kth term of } 5,8,11, \ldots)} \\
& =\frac{1}{\{2+(k-1) \times 3\} \times\{5+(k-1) \times 3\}} \\
& =\frac{1}{(3 k-1)(3 k+2)}=\frac{1}{3}\left\{\frac{1}{(3 k-1)}-\frac{1}{(3 k+2)}\right\}
\end{align*}
$$

Putting $k=1,2,3, \ldots, n$ successively, we get
$$
\begin{aligned}
T_{1} &= \frac{1}{3}\left(\frac{1}{2}-\frac{1}{5}\right) \\
T_{2} &= \frac{1}{3}\left(\frac{1}{5}-\frac{1}{8}\right) \\
T_{3} &= \frac{1}{3}\left(\frac{1}{8}-\frac{1}{11}\right) \\
\cdots & \quad \cdots \quad \cdots \quad \cdots \\
T_{n} &= \frac{1}{3}\left\{\frac{1}{(3 n-1)}-\frac{1}{(3 n+2)}\right\}
\end{aligned}
$$

Adding columnwise, we get
$$
\begin{aligned}
S_{n} & =\left(T_{1}+T_{2}+T_{3}+\ldots+T_{n}\right) \\
& =\frac{1}{3}\left(\frac{1}{2}-\frac{1}{3 n+2}\right) = \frac{1}{3}\left(\frac{3n+2-2}{2(3n+2)}\right) = \frac{n}{2(3 n+2)}
\end{aligned}
$$

---

### Example 11:

Find the sum of $n$ terms of the series $5+11+19+29+41+\ldots$.

#### Solution:

Let $S_{n}=5+11+19+29+\ldots+T_{n-1}+T_{n}$
Also, $S_{n}=\quad 5+11+19+\ldots+T_{n-2}+T_{n-1}+T_{n}$

On subtraction, we get
$$
\begin{aligned}
0 & =5+[6+8+10+12+\ldots \text{ to }(n-1) \text{ terms }]-T_{n} \\
\Rightarrow T_{n} & =5+\frac{(n-1)}{2}[2 \times 6+(n-1-1) \times 2] \\
\Rightarrow T_{n} & =5+\frac{(n-1)}{2}[12+2n-4] = 5+(n-1)(n+4) \\
\Rightarrow T_{n} & =5+n^2+3n-4 = n^{2}+3 n+1
\end{aligned}
$$

$$
\begin{aligned}
\therefore S_{n} & =\sum_{k=1}^{n} T_{k}=\sum_{k=1}^{n}\left(k^{2}+3 k+1\right)=\sum_{k=1}^{n} k^{2}+3 \sum_{k=1}^{n} k+n \\
& =\frac{1}{6} n(n+1)(2 n+1)+3 \cdot \frac{1}{2} n(n+1)+n \\
& =\frac{n}{6}[(n+1)(2n+1)+9(n+1)+6] \\
& =\frac{n}{6}[2n^2+3n+1+9n+9+6] \\
& =\frac{n}{6}[2n^2+12n+16] = \frac{n}{3}[n^2+6n+8] = \frac{1}{3} n(n+2)(n+4)
\end{aligned}
$$

---

### Example 12:

Find the sum of the first $n$ terms of the series $3+7+13+21+31+\ldots$.

#### Solution:

Let $S_{n}=3+7+13+21+31+\ldots+T_{n}$
Also, $S_{n}=\quad 3+7+13+21+\ldots+T_{n-1}+T_{n}$

On subtraction, we get
$$
\begin{aligned}
0 & =3+[4+6+8+10+\ldots \text{ to }(n-1) \text{ terms }]-T_{n} \\
\Rightarrow T_{n} & =3+[4+6+8+\ldots \text{ to }(n-1) \text{ terms }] \\
& =3+\frac{(n-1)}{2}[2 \times 4+(n-1-1) \times 2] \\
& =3+\frac{(n-1)}{2}[8+2n-4] = 3+(n-1)(n+2) = 3 + n^2+n-2 = \left(n^{2}+n+1\right)
\end{aligned}
$$

$$
\begin{aligned}
\therefore S_{n} & =\sum_{k=1}^{n} T_{k}=\sum_{k=1}^{n}\left(k^{2}+k+1\right) \\
& =\sum_{k=1}^{n} k^{2}+\sum_{k=1}^{n} k+n \\
& =\frac{1}{6} n(n+1)(2 n+1)+\frac{1}{2} n(n+1)+n \\
& =\frac{n}{6}[(n+1)(2n+1)+3(n+1)+6] \\
& =\frac{n}{6}[2n^2+3n+1+3n+3+6] = \frac{n}{6}[2n^2+6n+10] = \frac{1}{3} n\left(n^{2}+3 n+5\right)
\end{aligned}
$$

---

### Example 13:

Find the 50th term of the series $2+3+6+11+18+\ldots$.

#### Solution:

Let $S_{n}=2+3+6+11+18+\ldots+T_{n}$.
Again $S_{n}=\quad 2+3+6+11+\ldots+T_{n-1}+T_{n}$.

On subtracting, we get
$$
\begin{aligned}
0 &= 2+[1+3+5+7+\ldots \text{ to }(n-1) \text{ terms }]-T_{n} \\
\Rightarrow T_{n} &= 2+[1+3+5+7+\ldots \text{ to }(n-1) \text{ terms }] \\
&= 2+\frac{(n-1)}{2} \cdot[2 \times 1+(n-1-1) \times 2] \\
&= 2+\frac{(n-1)}{2} \cdot[2+2n-4] = 2+(n-1)^2
\end{aligned}
$$

$$
\Rightarrow T_{50}=\left\{(50-1)^{2}+2\right\}=\left\{(49)^{2}+2\right\}=(2401+2)=2403
$$

---

### Example 14:

Find the sum of the series $(3^{3}-2^{3})+(5^{3}-4^{3})+(7^{3}-6^{3})+\ldots$ to (i) $n$ terms (ii) 10 terms.

#### Solution:

We have
$$
\begin{aligned}
T_{k} & =\left\{(2 k+1)^{3}-(2 k)^{3}\right\} \\
& =\left\{(8k^3+12k^2+6k+1)-8 k^{3}\right\}=\left(12 k^{2}+6 k+1\right)
\end{aligned}
$$

(i) Sum to $n$ terms is given by
$$
\begin{aligned}
S_{n} & = \sum_{k=1}^{n} (12k^2+6k+1) \\
& = 12 \sum_{k=1}^{n} k^{2}+6 \sum_{k=1}^{n} k+n \\
& =12 \cdot \frac{1}{6} n(n+1)(2 n+1)+6 \cdot \frac{1}{2} n(n+1)+n \\
& =2 n(n+1)(2 n+1)+3 n(n+1)+n \\
& =n[(2n+2)(2n+1) + 3(n+1) + 1] \\
& =n[4n^2+6n+2+3n+3+1] \\
& =n\left(4 n^{2}+9 n+6\right)=\left(4 n^{3}+9 n^{2}+6 n\right)
\end{aligned}
$$

(ii) Sum to 10 terms is given by
$$
S_{10}=10 \cdot [4 \cdot 10^{2}+9 \cdot 10+6] = 10 \cdot [400+90+6] = 10 \cdot [496] = 4960
$$
---