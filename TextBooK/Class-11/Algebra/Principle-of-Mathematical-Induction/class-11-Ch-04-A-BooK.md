## Principle of Mathematical Induction

Let $P(n)$ be a statement involving the natural number $n$ such that:
1. $P(1)$ is true, and
2. $P(k+1)$ is true whenever $P(k)$ is true.

Then $P(n)$ is true for all $n \in N$.

---
## Solved Examples

### Example 1
Using the principle of mathematical induction, prove that
$$
1+3+5+7+\ldots+(2 n-1)=n^{2} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): 1+3+5+7+\ldots+(2 n-1)=n^{2}
$$
**Step 1: Base Case**

For $n=1$, we have:
$LHS = 1$ and $RHS = 1^{2}=1$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): 1+3+5+7+\ldots+(2 k-1)=k^{2} \tag{i}
$$
**Step 3: Inductive Step**

We now need to prove that $P(k+1)$ is also true.
Consider the sum to $k+1$ terms:
$$
\begin{aligned}
& 1+3+5+\ldots+(2 k-1)+\{2(k+1)-1\} \\
&= \{1+3+5+\ldots+(2 k-1)\}+(2 k+1) \\
&= k^{2}+(2 k+1) \quad \text{[Using (i)]} \\
&= (k+1)^{2}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, the statement $P(n)$ is true for all $n \in N$.

---
### Example 2
Using the principle of mathematical induction, prove that
$$
1+4+7+10+\ldots+(3 n-2)=\frac{1}{2} n(3 n-1) \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): 1+4+7+10+\ldots+(3 n-2)=\frac{1}{2} n(3 n-1)
$$
**Step 1: Base Case**

For $n=1$, we have:
$LHS = 1$ and $RHS = \frac{1}{2} \times 1 \times(3 \times 1-1)=1$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): 1+4+7+10+\ldots+(3 k-2)=\frac{1}{2} k(3 k-1) \tag{i}
$$
**Step 3: Inductive Step**

We now need to prove that $P(k+1)$ is true.
$$
\begin{aligned}
& 1+4+7+\ldots+(3 k-2)+\{3(k+1)-2\} \\
&= \{1+4+7+\ldots+(3 k-2)\}+(3 k+1) \\
&= \frac{1}{2} k(3 k-1)+(3 k+1) \quad \text{[Using (i)]} \\
&= \frac{1}{2}(3 k^{2}-k+6 k+2) \\
&= \frac{1}{2}(3 k^{2}+5 k+2) \\
&= \frac{1}{2}(k+1)(3 k+2) \\
&= \frac{1}{2}(k+1)\{3(k+1)-1\}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, the statement $P(n)$ is true for all $n \in N$.

---
### Example 3
Using the principle of mathematical induction, prove that
$$
1^{2}+2^{2}+3^{2}+\ldots+n^{2}=\frac{1}{6} n(n+1)(2 n+1) \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): 1^{2}+2^{2}+3^{2}+\ldots+n^{2}=\frac{1}{6} n(n+1)(2 n+1)
$$
**Step 1: Base Case**

For $n=1$, we have:
$LHS = 1^{2}=1$ and $RHS = \frac{1}{6} \times 1 \times(1+1) \times(2 \times 1+1)=1$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): 1^{2}+2^{2}+3^{2}+\ldots+k^{2}=\frac{1}{6} k(k+1)(2 k+1) \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& 1^{2}+2^{2}+3^{2}+\ldots+k^{2}+(k+1)^{2} \\
&= \{1^{2}+2^{2}+3^{2}+\ldots+k^{2}\}+(k+1)^{2} \\
&= \frac{1}{6} k(k+1)(2 k+1)+(k+1)^{2} \quad \text{[Using (i)]} \\
&= \frac{1}{6}(k+1)[k(2 k+1)+6(k+1)] \\
&= \frac{1}{6}(k+1)(2 k^{2}+k+6 k+6) \\
&= \frac{1}{6}(k+1)(2 k^{2}+7 k+6) \\
&= \frac{1}{6}(k+1)(k+2)(2 k+3) \\
&= \frac{1}{6}(k+1)\{(k+1)+1\}\{2(k+1)+1\}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 4
Using the principle of mathematical induction, prove that
$$
1^{3}+2^{3}+3^{3}+\ldots+n^{3}=\left\{\frac{n(n+1)}{2}\right\}^{2} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): 1^{3}+2^{3}+3^{3}+\ldots+n^{3}=\left\{\frac{n(n+1)}{2}\right\}^{2}
$$
**Step 1: Base Case**

For $n=1$, we have:
$LHS = 1^{3}=1$ and $RHS = \left(\frac{1(1+1)}{2}\right)^{2}=1^{2}=1$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): 1^{3}+2^{3}+3^{3}+\ldots+k^{3}=\left\{\frac{k(k+1)}{2}\right\}^{2} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& 1^{3}+2^{3}+3^{3}+\ldots+k^{3}+(k+1)^{3} \\
&= \{1^{3}+2^{3}+3^{3}+\ldots+k^{3}\}+(k+1)^{3} \\
&= \left\{\frac{k(k+1)}{2}\right\}^{2}+(k+1)^{3} \quad \text{[Using (i)]} \\
&= \frac{k^2(k+1)^2}{4}+(k+1)^{3} \\
&= (k+1)^{2}\left[\frac{k^{2}}{4}+(k+1)\right] \\
&= (k+1)^{2}\left[\frac{k^{2}+4 k+4}{4}\right] \\
&= \frac{(k+1)^{2}(k+2)^{2}}{4} \\
&= \left\{\frac{(k+1)\{(k+1)+1\}}{2}\right\}^{2}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 5
Using the principle of mathematical induction, prove that
$$
1 \cdot 2+2 \cdot 3+3 \cdot 4+\ldots+n(n+1)=\frac{1}{3} n(n+1)(n+2) \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): 1 \cdot 2+2 \cdot 3+3 \cdot 4+\ldots+n(n+1)=\frac{1}{3} n(n+1)(n+2)
$$
**Step 1: Base Case**

For $n=1$, we have:
$LHS = 1 \cdot 2=2$ and $RHS = \frac{1}{3} \times 1 \times (1+1) \times (1+2)=2$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): 1 \cdot 2+2 \cdot 3+3 \cdot 4+\ldots+k(k+1)=\frac{1}{3} k(k+1)(k+2) \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& 1 \cdot 2+2 \cdot 3+\ldots+k(k+1)+(k+1)(k+2) \\
&= \{1 \cdot 2+2 \cdot 3+\ldots+k(k+1)\} + (k+1)(k+2) \\
&= \frac{1}{3} k(k+1)(k+2)+(k+1)(k+2) \quad \text{[Using (i)]} \\
&= \frac{1}{3}(k+1)(k+2)[k+3] \\
&= \frac{1}{3}(k+1)(k+2)(k+3)
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 6
Using the principle of mathematical induction, prove that
$$
1 \cdot 3+3 \cdot 5+5 \cdot 7+\ldots+(2 n-1)(2 n+1)=\frac{1}{3} n(4 n^{2}+6 n-1) \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): 1 \cdot 3+3 \cdot 5+\ldots+(2 n-1)(2 n+1)=\frac{1}{3} n(4 n^{2}+6 n-1)
$$
**Step 1: Base Case**

For $n=1$, we have:
$LHS = 1 \cdot 3=3$ and $RHS = \frac{1}{3} \times 1 \times (4 \cdot 1^{2}+6 \cdot 1-1)=\frac{9}{3}=3$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true.
$$
P(k): 1 \cdot 3+3 \cdot 5+\ldots+(2 k-1)(2 k+1)=\frac{1}{3} k(4 k^{2}+6 k-1) \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& 1 \cdot 3+\ldots+(2 k-1)(2 k+1)+\{2(k+1)-1\}\{2(k+1)+1\} \\
&= \{1 \cdot 3+\ldots+(2 k-1)(2 k+1)\}+(2 k+1)(2 k+3) \\
&= \frac{1}{3} k(4 k^{2}+6 k-1)+(2 k+1)(2 k+3) \quad \text{[Using (i)]} \\
&= \frac{1}{3}[k(4 k^{2}+6 k-1)+3(2 k+1)(2 k+3)] \\
&= \frac{1}{3}[4 k^{3}+6 k^{2}-k+3(4 k^{2}+8 k+3)] \\
&= \frac{1}{3}[4 k^{3}+6 k^{2}-k+12 k^{2}+24 k+9] \\
&= \frac{1}{3}(4 k^{3}+18 k^{2}+23 k+9) \\
&= \frac{1}{3}(k+1)(4 k^{2}+14 k+9) \\
&= \frac{1}{3}(k+1)\{4(k^2+2k+1)+6k+5\} \\
&= \frac{1}{3}(k+1)\{4(k+1)^2+6(k+1)-1\}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 7
Using the principle of mathematical induction, prove that
$$
1 \cdot 2 \cdot 3+2 \cdot 3 \cdot 4+\ldots+n(n+1)(n+2)=\frac{1}{4} n(n+1)(n+2)(n+3) \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$.
$$
P(n): 1 \cdot 2 \cdot 3+\ldots+n(n+1)(n+2)=\frac{1}{4} n(n+1)(n+2)(n+3)
$$
**Step 1: Base Case**

For $n=1$:
$LHS = 1 \cdot 2 \cdot 3=6$ and $RHS = \frac{1}{4} \times 1 \times 2 \times 3 \times 4=6$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): 1 \cdot 2 \cdot 3+\ldots+k(k+1)(k+2) = \frac{1}{4} k(k+1)(k+2)(k+3) \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& 1 \cdot 2 \cdot 3+\ldots+k(k+1)(k+2)+(k+1)(k+2)(k+3) \\
&= \{1 \cdot 2 \cdot 3+\ldots+k(k+1)(k+2)\} + (k+1)(k+2)(k+3) \\
&= \frac{1}{4} k(k+1)(k+2)(k+3)+(k+1)(k+2)(k+3) \quad \text{[Using (i)]} \\
&= \frac{1}{4}(k+1)(k+2)(k+3)[k+4] \\
&= \frac{1}{4}(k+1)(k+2)(k+3)(k+4)
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 8
Using the principle of mathematical induction, prove that
$$
\frac{1}{1 \cdot 2}+\frac{1}{2 \cdot 3}+\frac{1}{3 \cdot 4}+\ldots+\frac{1}{n(n+1)}=\frac{n}{n+1} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): \frac{1}{1 \cdot 2}+\frac{1}{2 \cdot 3}+\ldots+\frac{1}{n(n+1)}=\frac{n}{n+1}
$$
**Step 1: Base Case**

For $n=1$:
$LHS = \frac{1}{1 \cdot 2}=\frac{1}{2}$ and $RHS = \frac{1}{1+1}=\frac{1}{2}$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): \frac{1}{1 \cdot 2}+\frac{1}{2 \cdot 3}+\ldots+\frac{1}{k(k+1)}=\frac{k}{k+1} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& \frac{1}{1 \cdot 2}+\frac{1}{2 \cdot 3}+\ldots+\frac{1}{k(k+1)}+\frac{1}{(k+1)(k+2)} \\
&= \left\{\frac{1}{1 \cdot 2}+\ldots+\frac{1}{k(k+1)}\right\}+\frac{1}{(k+1)(k+2)} \\
&= \frac{k}{k+1}+\frac{1}{(k+1)(k+2)} \quad \text{[Using (i)]} \\
&= \frac{k(k+2)+1}{(k+1)(k+2)} \\
&= \frac{k^2+2k+1}{(k+1)(k+2)} \\
&= \frac{(k+1)^2}{(k+1)(k+2)} \\
&= \frac{k+1}{k+2}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 9
Using the principle of mathematical induction, prove that
$$
\frac{1}{3 \cdot 5}+\frac{1}{5 \cdot 7}+\frac{1}{7 \cdot 9}+\ldots+\frac{1}{(2 n+1)(2 n+3)}=\frac{n}{3(2 n+3)} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$. Then,
$$
P(n): \frac{1}{3 \cdot 5}+\frac{1}{5 \cdot 7}+\ldots+\frac{1}{(2 n+1)(2 n+3)}=\frac{n}{3(2 n+3)}
$$
**Step 1: Base Case**

For $n=1$:
$LHS = \frac{1}{3 \cdot 5}=\frac{1}{15}$ and $RHS = \frac{1}{3(2 \cdot 1+3)}=\frac{1}{15}$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): \frac{1}{3 \cdot 5}+\ldots+\frac{1}{(2 k+1)(2 k+3)}=\frac{k}{3(2 k+3)} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& \frac{1}{3 \cdot 5}+\ldots+\frac{1}{(2 k+1)(2 k+3)}+\frac{1}{(2(k+1)+1)(2(k+1)+3)} \\
&= \left\{\frac{1}{3 \cdot 5}+\ldots+\frac{1}{(2 k+1)(2 k+3)}\right\}+\frac{1}{(2 k+3)(2 k+5)} \\
&= \frac{k}{3(2 k+3)}+\frac{1}{(2 k+3)(2 k+5)} \quad \text{[Using (i)]} \\
&= \frac{k(2 k+5)+3}{3(2 k+3)(2 k+5)} \\
&= \frac{2k^2+5k+3}{3(2 k+3)(2 k+5)} \\
&= \frac{(k+1)(2k+3)}{3(2 k+3)(2 k+5)} \\
&= \frac{k+1}{3(2 k+5)} \\
&= \frac{k+1}{3\{2(k+1)+3\}}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 10
Using the principle of mathematical induction, prove that
$$
\frac{1}{1 \cdot 2 \cdot 3}+\frac{1}{2 \cdot 3 \cdot 4}+\ldots+\frac{1}{n(n+1)(n+2)}=\frac{n(n+3)}{4(n+1)(n+2)} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$.
$$
P(n): \frac{1}{1 \cdot 2 \cdot 3}+\ldots+\frac{1}{n(n+1)(n+2)}=\frac{n(n+3)}{4(n+1)(n+2)}
$$
**Step 1: Base Case**

For $n=1$:
$LHS = \frac{1}{1 \cdot 2 \cdot 3}=\frac{1}{6}$ and $RHS = \frac{1(1+3)}{4(1+1)(1+2)}=\frac{4}{24}=\frac{1}{6}$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): \frac{1}{1 \cdot 2 \cdot 3}+\ldots+\frac{1}{k(k+1)(k+2)}=\frac{k(k+3)}{4(k+1)(k+2)} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& \frac{1}{1 \cdot 2 \cdot 3}+\ldots+\frac{1}{k(k+1)(k+2)}+\frac{1}{(k+1)(k+2)(k+3)} \\
&= \left\{\frac{1}{1 \cdot 2 \cdot 3}+\ldots+\frac{1}{k(k+1)(k+2)}\right\}+\frac{1}{(k+1)(k+2)(k+3)} \\
&= \frac{k(k+3)}{4(k+1)(k+2)}+\frac{1}{(k+1)(k+2)(k+3)} \quad \text{[Using (i)]} \\
&= \frac{k(k+3)^2+4}{4(k+1)(k+2)(k+3)} \\
&= \frac{k(k^2+6k+9)+4}{4(k+1)(k+2)(k+3)} \\
&= \frac{k^3+6k^2+9k+4}{4(k+1)(k+2)(k+3)} \\
&= \frac{(k+1)^2(k+4)}{4(k+1)(k+2)(k+3)} \\
&= \frac{(k+1)(k+4)}{4(k+2)(k+3)}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 11
Using the principle of mathematical induction, prove that
$$
1 \cdot 3+2 \cdot 3^{2}+3 \cdot 3^{3}+\ldots+n \cdot 3^{n}=\frac{(2 n-1) 3^{n+1}+3}{4} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$.
$$
P(n): 1 \cdot 3+2 \cdot 3^{2}+\ldots+n \cdot 3^{n}=\frac{(2 n-1) 3^{n+1}+3}{4}
$$
**Step 1: Base Case**

For $n=1$:
$LHS = 1 \cdot 3 = 3$ and $RHS = \frac{(2 \cdot 1-1) 3^{1+1}+3}{4}=\frac{9+3}{4}=3$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): 1 \cdot 3+2 \cdot 3^{2}+\ldots+k \cdot 3^{k}=\frac{(2 k-1) 3^{k+1}+3}{4} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& 1 \cdot 3+2 \cdot 3^{2}+\ldots+k \cdot 3^{k}+(k+1)3^{k+1} \\
&= \{1 \cdot 3+2 \cdot 3^{2}+\ldots+k \cdot 3^{k}\} + (k+1)3^{k+1} \\
&= \frac{(2 k-1) 3^{k+1}+3}{4}+(k+1)3^{k+1} \quad \text{[Using (i)]} \\
&= \frac{(2 k-1) 3^{k+1}+3+4(k+1)3^{k+1}}{4} \\
&= \frac{(2k-1+4k+4)3^{k+1}+3}{4} \\
&= \frac{(6k+3)3^{k+1}+3}{4} \\
&= \frac{3(2k+1)3^{k+1}+3}{4} \\
&= \frac{(2k+1)3^{k+2}+3}{4} \\
&= \frac{\{2(k+1)-1\}3^{(k+1)+1}+3}{4}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 12
Using the principle of mathematical induction, prove that
$$
\left(1-\frac{1}{2}\right)\left(1-\frac{1}{3}\right)\left(1-\frac{1}{4}\right) \ldots\left(1-\frac{1}{n+1}\right)=\frac{1}{n+1} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$.
$$
P(n):\left(1-\frac{1}{2}\right)\left(1-\frac{1}{3}\right)\ldots\left(1-\frac{1}{n+1}\right)=\frac{1}{n+1}
$$
**Step 1: Base Case**

For $n=1$:
$LHS = \left(1-\frac{1}{2}\right)=\frac{1}{2}$ and $RHS = \frac{1}{1+1}=\frac{1}{2}$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k):\left(1-\frac{1}{2}\right)\left(1-\frac{1}{3}\right)\ldots\left(1-\frac{1}{k+1}\right)=\frac{1}{k+1} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& \left(1-\frac{1}{2}\right)\left(1-\frac{1}{3}\right)\ldots\left(1-\frac{1}{k+1}\right)\left(1-\frac{1}{k+1+1}\right) \\
&= \left\{\left(1-\frac{1}{2}\right)\ldots\left(1-\frac{1}{k+1}\right)\right\} \cdot \left(1-\frac{1}{k+2}\right) \\
&= \frac{1}{k+1} \cdot \left(\frac{k+2-1}{k+2}\right) \quad \text{[Using (i)]} \\
&= \frac{1}{k+1} \cdot \frac{k+1}{k+2} \\
&= \frac{1}{k+2}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 13
Using the principle of mathematical induction, prove that for a geometric progression:
$$
a+a r+a r^{2}+\ldots+a r^{n-1}=\frac{a(r^{n}-1)}{r-1} \text{ for } r>1 \text{ and all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$.
$$
P(n): a+a r+a r^{2}+\ldots+a r^{n-1}=\frac{a(r^{n}-1)}{r-1}
$$
**Step 1: Base Case**

For $n=1$:
$LHS = a$ and $RHS = \frac{a(r^{1}-1)}{r-1}=a$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): a+a r+a r^{2}+\ldots+a r^{k-1}=\frac{a(r^{k}-1)}{r-1} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
& (a+a r+a r^{2}+\ldots+a r^{k-1})+a r^{k} \\
&= \frac{a(r^{k}-1)}{r-1}+a r^{k} \quad \text{[Using (i)]} \\
&= \frac{a(r^{k}-1)+ar^k(r-1)}{r-1} \\
&= \frac{ar^k - a + ar^{k+1} - ar^k}{r-1} \\
&= \frac{a r^{k+1}-a}{r-1} \\
&= \frac{a(r^{k+1}-1)}{r-1}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 14
Let $a$ and $b$ be arbitrary real numbers. Using the principle of mathematical induction, prove that
$$
(a b)^{n}=a^{n} b^{n} \text{ for all } n \in N.
$$
---
#### Solution

Let the given statement be $P(n)$.
$$
P(n): (a b)^{n}=a^{n} b^{n}
$$
**Step 1: Base Case**

For $n=1$:
$LHS = (a b)^{1}=ab$ and $RHS = a^{1} b^{1}=ab$.
Since $LHS = RHS$, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): (a b)^{k}=a^{k} b^{k} \tag{i}
$$
**Step 3: Inductive Step**

We now prove that $P(k+1)$ is true.
$$
\begin{aligned}
(a b)^{k+1} &= (a b)^{k}(a b) \\
&= (a^{k} b^{k})(ab) \quad \text{[Using (i)]} \\
&= (a^{k} \cdot a)(b^{k} \cdot b) \quad \text{[By commutativity and associativity]} \\
&= a^{k+1} b^{k+1}
\end{aligned}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $P(n)$ is true for all $n \in N$.

---
### Example 15
Using the principle of mathematical induction, prove that $(n^{2}+n)$ is even for all $n \in N$.

---
#### Solution

Let $P(n): (n^{2}+n)$ is even.

**Step 1: Base Case**

For $n=1$:
The expression is $(1^{2}+1)=2$, which is an even number.
So, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
This means $(k^{2}+k)$ is even.
So, we can write $k^{2}+k = 2m$ for some integer $m$.

**Step 3: Inductive Step**

We now test $P(k+1)$. The expression is $(k+1)^{2}+(k+1)$.
$$
\begin{aligned}
(k+1)^{2}+(k+1) &= (k^2+2k+1)+(k+1) \\
&= k^2+3k+2 \\
&= (k^2+k) + 2k+2 \\
&= 2m + 2(k+1) \quad \text{[Using the hypothesis]} \\
&= 2[m+(k+1)]
\end{aligned}
$$
Since $m$ and $k$ are integers, $[m+(k+1)]$ is also an integer. Therefore, $2[m+(k+1)]$ is an even number.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $(n^2+n)$ is even for all $n \in N$.

---
### Example 16
Using the principle of mathematical induction, prove that $n(n+1)(n+5)$ is a multiple of 3 for all $n \in N$.

---
#### Solution

Let $P(n): n(n+1)(n+5)$ is a multiple of 3.

**Step 1: Base Case**

For $n=1$:
The expression is $1(1+1)(1+5) = 1 \cdot 2 \cdot 6 = 12$.
Since 12 is a multiple of 3, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
This means $k(k+1)(k+5)$ is a multiple of 3.
So, $k(k+1)(k+5) = 3m$ for some integer $m$.

**Step 3: Inductive Step**

We now test $P(k+1)$. The expression is $(k+1)(k+1+1)(k+1+5) = (k+1)(k+2)(k+6)$.
$$
\begin{aligned}
& (k+1)(k+2)(k+6) \\
&= (k+1)(k+2)(k+5+1) \\
&= (k+1)(k+2)(k+5) + (k+1)(k+2) \\
&= k(k+1)(k+5) + 2(k+1)(k+5) + (k+1)(k+2) \quad \text{[This approach is complex]}
\end{aligned}
$$
Let's try an alternative expansion from the source:
$$
\begin{aligned}
(k+1)(k+2)(k+6) &= k(k+1)(k+2) + 6(k+1)(k+2) \\
&= k(k+1)(k+5-3) + 6(k+1)(k+2) \\
&= k(k+1)(k+5) - 3k(k+1) + 6(k+1)(k+2) \\
&= 3m - 3k(k+1) + 6(k+1)(k+2) \quad \text{[Using the hypothesis]} \\
&= 3[m - k(k+1) + 2(k+1)(k+2)]
\end{aligned}
$$
This expression is a multiple of 3.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $n(n+1)(n+5)$ is a multiple of 3 for all $n \in N$.

---
### Example 17
Using the principle of mathematical induction, prove that $(7^{n}-3^{n})$ is divisible by 4 for all $n \in N$.

---
#### Solution

Let $P(n): (7^{n}-3^{n})$ is divisible by 4.

**Step 1: Base Case**

For $n=1$:
The expression is $(7^{1}-3^{1}) = 4$.
Since 4 is divisible by 4, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
This means $(7^{k}-3^{k})$ is divisible by 4.
So, $7^{k}-3^{k} = 4m$ for some integer $m$, which implies $7^k = 4m + 3^k$.

**Step 3: Inductive Step**

We now test $P(k+1)$. The expression is $7^{k+1}-3^{k+1}$.
$$
\begin{aligned}
7^{k+1}-3^{k+1} &= 7 \cdot 7^k - 3 \cdot 3^k \\
&= 7(4m + 3^k) - 3 \cdot 3^k \quad \text{[Using the hypothesis]} \\
&= 28m + 7 \cdot 3^k - 3 \cdot 3^k \\
&= 28m + 4 \cdot 3^k \\
&= 4(7m + 3^k)
\end{aligned}
$$
This expression is clearly divisible by 4.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $(7^n-3^n)$ is divisible by 4 for all $n \in N$.

---
### Example 18
Using the principle of mathematical induction, prove that $(10^{2 n-1}+1)$ is divisible by 11 for all $n \in N$.

---
#### Solution

Let $P(n): (10^{2 n-1}+1)$ is divisible by 11.

**Step 1: Base Case**

For $n=1$:
The expression is $(10^{2 \cdot 1-1}+1) = 10^1+1 = 11$.
Since 11 is divisible by 11, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
This means $(10^{2 k-1}+1)$ is divisible by 11.
So, $10^{2k-1}+1 = 11m$ for some integer $m$, which implies $10^{2k-1} = 11m-1$.

**Step 3: Inductive Step**

We now test $P(k+1)$. The expression is $10^{2(k+1)-1}+1$.
$$
\begin{aligned}
10^{2(k+1)-1}+1 &= 10^{2k+2-1}+1 \\
&= 10^{2k+1}+1 \\
&= 10^2 \cdot 10^{2k-1} + 1 \\
&= 100 \cdot (11m-1) + 1 \quad \text{[Using the hypothesis]} \\
&= 1100m - 100 + 1 \\
&= 1100m - 99 \\
&= 11(100m - 9)
\end{aligned}
$$
This expression is clearly divisible by 11.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $(10^{2n-1}+1)$ is divisible by 11 for all $n \in N$.

---
### Example 19
Using the principle of mathematical induction, prove that $(2 \cdot 7^{n}+3 \cdot 5^{n}-5)$ is divisible by 24 for all $n \in N$.

---
#### Solution

Let $P(n): (2 \cdot 7^{n}+3 \cdot 5^{n}-5)$ is divisible by 24.

**Step 1: Base Case**

For $n=1$:
The expression is $(2 \cdot 7^{1}+3 \cdot 5^{1}-5) = 14+15-5=24$.
Since 24 is divisible by 24, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
So, $2 \cdot 7^{k}+3 \cdot 5^{k}-5 = 24m$ for some integer $m$.
This implies $2 \cdot 7^k = 24m - 3 \cdot 5^k + 5$.

**Step 3: Inductive Step**

We now test $P(k+1)$. The expression is $2 \cdot 7^{k+1}+3 \cdot 5^{k+1}-5$.
$$
\begin{aligned}
& 2 \cdot 7^{k+1}+3 \cdot 5^{k+1}-5 \\
&= 7 \cdot (2 \cdot 7^k) + 15 \cdot 5^k - 5 \\
&= 7(24m - 3 \cdot 5^k + 5) + 15 \cdot 5^k - 5 \quad \text{[Using the hypothesis]} \\
&= 168m - 21 \cdot 5^k + 35 + 15 \cdot 5^k - 5 \\
&= 168m - 6 \cdot 5^k + 30 \\
&= 168m - 6(5^k - 5) \\
&= 168m - 30(5^{k-1} - 1)
\end{aligned}
$$
We know that $(a^n-b^n)$ is divisible by $(a-b)$. So, $(5^{k-1}-1^{k-1})$ is divisible by $(5-1)=4$.
Let $5^{k-1}-1 = 4p$ for some integer $p$.
Substituting this back:
$$
\begin{aligned}
& 168m - 30(4p) \\
&= 168m - 120p \\
&= 24(7m - 5p)
\end{aligned}
$$
This expression is clearly divisible by 24.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, the given expression is divisible by 24 for all $n \in N$.

---
### Example 20
Using the principle of mathematical induction, prove that $(x^{n}-y^{n})$ is divisible by $(x-y)$ for all $n \in N$.

---
#### Solution

Let $P(n): (x^{n}-y^{n})$ is divisible by $(x-y)$.

**Step 1: Base Case**

For $n=1$:
The expression is $(x^1 - y^1) = x-y$.
This is clearly divisible by $(x-y)$. So, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
This means $(x^{k}-y^{k})$ is divisible by $(x-y)$.
So, $x^k - y^k = m(x-y)$ for some polynomial $m$.

**Step 3: Inductive Step**

We now test $P(k+1)$. The expression is $x^{k+1}-y^{k+1}$.
We add and subtract the term $x^k y$:
$$
\begin{aligned}
x^{k+1}-y^{k+1} &= x^{k+1} - x^k y + x^k y - y^{k+1} \\
&= x^k(x-y) + y(x^k - y^k) \\
&= x^k(x-y) + y(m(x-y)) \quad \text{[Using the hypothesis]} \\
&= (x-y)(x^k + my)
\end{aligned}
$$
This expression is clearly divisible by $(x-y)$.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $(x^n-y^n)$ is divisible by $(x-y)$ for all $n \in N$.

---
### Example 21
Using the principle of mathematical induction, prove that
$$
(1+x)^{n} \geq (1+n x) \text{ for all } n \in N, \text{ where } x>-1.
$$
---
#### Solution

Let $P(n): (1+x)^{n} \geq (1+n x)$ for $x>-1$.

**Step 1: Base Case**

For $n=1$:
$LHS = (1+x)^1 = 1+x$ and $RHS = 1+1 \cdot x = 1+x$.
The inequality $(1+x) \geq (1+x)$ is true. So, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): (1+x)^{k} \geq (1+k x)
$$
**Step 3: Inductive Step**

We now test $P(k+1)$. We want to prove $(1+x)^{k+1} \geq 1+(k+1)x$.
$$
(1+x)^{k+1} = (1+x)^k (1+x)
$$
Since $x>-1$, $(1+x)>0$. We can multiply both sides of the inductive hypothesis by $(1+x)$ without changing the inequality direction.
$$
\begin{aligned}
(1+x)^k (1+x) &\geq (1+kx)(1+x) \\
(1+x)^{k+1} &\geq 1+x+kx+kx^2 \\
(1+x)^{k+1} &\geq 1+(k+1)x + kx^2
\end{aligned}
$$
Since $k$ is a positive integer and $x^2 \geq 0$, the term $kx^2$ is non-negative ($kx^2 \geq 0$).
Therefore, $1+(k+1)x + kx^2 \geq 1+(k+1)x$.
Combining the inequalities, we get:
$$
(1+x)^{k+1} \geq 1+(k+1)x
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, the inequality holds for all $n \in N$.

---
### Example 22
Using the principle of mathematical induction, prove that $n<2^{n}$ for all $n \in N$.

---
#### Solution

Let $P(n): n<2^{n}$.

**Step 1: Base Case**

For $n=1$:
$LHS = 1$ and $RHS = 2^1 = 2$.
The inequality $1 < 2$ is true. So, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): k < 2^k
$$
**Step 3: Inductive Step**

We want to prove $P(k+1)$, i.e., $k+1 < 2^{k+1}$.
From the hypothesis, we have $k < 2^k$. Multiplying by 2:
$$
2k < 2 \cdot 2^k = 2^{k+1}
$$
We can write $2k$ as $k+k$.
So, $k+k < 2^{k+1}$.
Since $k$ is a natural number, $k \geq 1$. Therefore, $k+k \geq k+1$.
Combining these facts:
$$
k+1 \leq k+k < 2^{k+1}
$$
This simplifies to $k+1 < 2^{k+1}$.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, $n < 2^n$ for all $n \in N$.

---
### Example 23
Using the principle of mathematical induction, prove that
$$
(2 n+7)<(n+3)^{2} \text{ for all values of } n \in N.
$$
---
#### Solution

Let $P(n): (2 n+7)<(n+3)^{2}$.

**Step 1: Base Case**

For $n=1$:
$LHS = (2 \cdot 1+7) = 9$ and $RHS = (1+3)^2 = 16$.
The inequality $9 < 16$ is true. So, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): (2k+7) < (k+3)^2
$$
**Step 3: Inductive Step**

We want to prove $P(k+1)$, i.e., $2(k+1)+7 < ((k+1)+3)^2$.
Let's start with the LHS of $P(k+1)$:
$$
2(k+1)+7 = (2k+7)+2
$$
From the hypothesis, we know $(2k+7) < (k+3)^2$. So,
$$
(2k+7)+2 < (k+3)^2 + 2
$$
Expanding the right side:
$$
(k+3)^2 + 2 = k^2+6k+9+2 = k^2+6k+11
$$
Now let's look at the RHS of $P(k+1)$:
$$
((k+1)+3)^2 = (k+4)^2 = k^2+8k+16
$$
We need to check if $k^2+6k+11 < k^2+8k+16$.
This simplifies to $0 < 2k+5$. Since $k \in N$, $k \geq 1$, so $2k+5$ is always positive.
Therefore, $k^2+6k+11 < k^2+8k+16$ is true for all $k \in N$.
So we have:
$$
2(k+1)+7 < (k+3)^2+2 < (k+4)^2
$$
This shows $2(k+1)+7 < ((k+1)+3)^2$.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, the inequality holds for all $n \in N$.

---
### Example 24
Using the principle of mathematical induction, prove that
$$
(1^{2}+2^{2}+\ldots+n^{2})>\frac{n^{3}}{3} \text{ for all values of } n \in N.
$$
---
#### Solution

Let $P(n): (1^{2}+2^{2}+\ldots+n^{2})>\frac{n^{3}}{3}$.

**Step 1: Base Case**

For $n=1$:
$LHS = 1^2 = 1$ and $RHS = \frac{1^3}{3} = \frac{1}{3}$.
The inequality $1 > \frac{1}{3}$ is true. So, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): (1^{2}+2^{2}+\ldots+k^{2}) > \frac{k^{3}}{3}
$$
**Step 3: Inductive Step**

We want to prove $P(k+1)$, i.e., $1^{2}+\ldots+(k+1)^{2} > \frac{(k+1)^3}{3}$.
Start with the LHS of $P(k+1)$:
$$
1^{2}+2^{2}+\ldots+k^{2}+(k+1)^{2}
$$
From the hypothesis, we have:
$$
\{1^{2}+\ldots+k^{2}\}+(k+1)^{2} > \frac{k^3}{3} + (k+1)^2
$$
Now, let's work with the right side of this new inequality:
$$
\begin{aligned}
\frac{k^3}{3} + (k+1)^2 &= \frac{k^3 + 3(k^2+2k+1)}{3} \\
&= \frac{k^3+3k^2+6k+3}{3}
\end{aligned}
$$
We want to show this is greater than $\frac{(k+1)^3}{3} = \frac{k^3+3k^2+3k+1}{3}$.
Let's compare the numerators:
$k^3+3k^2+6k+3$ vs $k^3+3k^2+3k+1$.
The difference is $(k^3+3k^2+6k+3) - (k^3+3k^2+3k+1) = 3k+2$.
Since $k \in N$, $3k+2$ is always positive.
Therefore, $k^3+3k^2+6k+3 > k^3+3k^2+3k+1$.
This means $\frac{k^3+3k^2+6k+3}{3} > \frac{(k+1)^3}{3}$.
So, we have shown that:
$$
1^{2}+\ldots+(k+1)^{2} > \frac{k^3}{3} + (k+1)^2 > \frac{(k+1)^3}{3}
$$
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, the inequality holds for all $n \in N$.

---
### Example 25
Using the principle of mathematical induction, prove that
$$
(1+2+3+\ldots+n)<\frac{1}{8}(2 n+1)^{2} \text{ for all values of } n \in N.
$$
---
#### Solution

Let $P(n): (1+2+3+\ldots+n)<\frac{1}{8}(2 n+1)^{2}$.
We know the sum of the first $n$ integers is $\frac{n(n+1)}{2}$. So the statement is equivalent to proving $\frac{n(n+1)}{2} < \frac{1}{8}(2n+1)^2$.

**Step 1: Base Case**

For $n=1$:
$LHS = 1$ and $RHS = \frac{1}{8}(2 \cdot 1+1)^2 = \frac{9}{8}$.
The inequality $1 < \frac{9}{8}$ is true. So, $P(1)$ is true.

**Step 2: Inductive Hypothesis**

Let's assume $P(k)$ is true for some positive integer $k$.
$$
P(k): (1+2+3+\ldots+k) < \frac{1}{8}(2 k+1)^{2}
$$
**Step 3: Inductive Step**

We want to prove $P(k+1)$.
Start with the LHS of $P(k+1)$:
$$
1+2+3+\ldots+k+(k+1) = \{1+2+\ldots+k\} + (k+1)
$$
Using the hypothesis:
$$
\{1+2+\ldots+k\} + (k+1) < \frac{1}{8}(2k+1)^2 + (k+1)
$$
Now, let's simplify the right side:
$$
\begin{aligned}
& \frac{1}{8}(2k+1)^2 + (k+1) \\
&= \frac{(4k^2+4k+1) + 8(k+1)}{8} \\
&= \frac{4k^2+4k+1+8k+8}{8} \\
&= \frac{4k^2+12k+9}{8} \\
&= \frac{(2k+3)^2}{8} \\
&= \frac{\{2(k+1)+1\}^2}{8}
\end{aligned}
$$
So we have shown that $(1+2+\ldots+(k+1)) < \frac{\{2(k+1)+1\}^2}{8}$.
Thus, $P(k+1)$ is true whenever $P(k)$ is true.

By the principle of mathematical induction, the inequality holds for all $n \in N$.

---
