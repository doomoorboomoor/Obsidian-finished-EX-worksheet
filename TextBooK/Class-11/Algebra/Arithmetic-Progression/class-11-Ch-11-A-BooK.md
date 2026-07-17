## Arithmetic Progression

### Sequence

A **sequence** is a succession of numbers arranged in a definite order according to a certain given rule.

The number occurring at the `$n$`th place of a sequence is called its **`$n$`th term** or the **general term**, denoted by `$a_n$`.

A sequence is said to be **finite** or **infinite** according as the number of terms in it is finite or infinite, respectively.

By adding the terms of a sequence, we get a **series**. A series is said to be finite or infinite according as the number of terms in it is finite or infinite, respectively.

---
### Example 1:

Write the first five terms of the sequence given by the rule `$a_n = (2n + 1)$` and obtain the corresponding series.

#### Solution:

We have, `$a_n = (2n + 1)$`.

Putting `$n = 1, 2, 3, 4, 5, \ldots$` successively, we get:

$$
\begin{aligned}
& a_1 = (2 \times 1 + 1) = 3; \\
& a_2 = (2 \times 2 + 1) = 5; \\
& a_3 = (2 \times 3 + 1) = 7; \\
& a_4 = (2 \times 4 + 1) = 9; \\
& a_5 = (2 \times 5 + 1) = 11.
\end{aligned}
$$

Hence, the required sequence is `$3, 5, 7, 9, 11, \ldots$`.
The corresponding series is `$3 + 5 + 7 + 9 + 11 + \ldots$`.

---
### Example 2:

Write the first four terms of the sequence given by `$a_n = \frac{1}{6}(2n - 3)$` and obtain the corresponding series.

#### Solution:

We have, `$a_n = \frac{1}{6}(2n - 3)$`.

Putting `$n = 1, 2, 3, 4, \ldots$` successively, we get:

$$
\begin{aligned}
& a_1 = \frac{1}{6}(2 \times 1 - 3) = \frac{-1}{6}; \\
& a_2 = \frac{1}{6}(2 \times 2 - 3) = \frac{1}{6}; \\
& a_3 = \frac{1}{6}(2 \times 3 - 3) = \frac{3}{6} = \frac{1}{2}; \\
& a_4 = \frac{1}{6}(2 \times 4 - 3) = \frac{5}{6}.
\end{aligned}
$$

Hence, the required sequence is `$\frac{-1}{6}, \frac{1}{6}, \frac{1}{2}, \frac{5}{6}, \ldots$`.
The corresponding series is `$-\frac{1}{6} + \frac{1}{6} + \frac{1}{2} + \frac{5}{6} + \ldots$`.

---
### Example 3:

The Fibonacci sequence is defined by `$1 = a_1 = a_2$` and `$a_n = a_{n-1} + a_{n-2}$`, for `$n > 2$`. Find `$\frac{a_{n+1}}{a_n}$` for `$n = 1, 2, 3, 4, 5$`.

#### Solution:

We have `$a_1=1$`, `$a_2=1$`, and `$a_n=a_{n-1}+a_{n-2}$` for `$n>2$`.

$$
\begin{array}{ll}
\therefore & a_3 = (a_2 + a_1) = (1+1) = 2, \\
& a_4 = (a_3 + a_2) = (2+1) = 3, \\
& a_5 = (a_4 + a_3) = (3+2) = 5.
\end{array}
$$

Therefore:

$$
\frac{a_2}{a_1} = 1, \quad \frac{a_3}{a_2} = \frac{2}{1} = 2, \quad \frac{a_4}{a_3} = \frac{3}{2}, \quad \text{and} \quad \frac{a_5}{a_4} = \frac{5}{3}.
$$

---
## Progressions

Sequences following certain patterns are called **progressions**.

---
## Arithmetic Progression (AP)

An **Arithmetic Progression (AP)** is a sequence in which each term, except the first one, differs from its preceding term by a constant.

This constant difference is called the **common difference** of the AP. In an AP, we usually denote the first term by `*a*`, the common difference by `*d*`, and the `$n$`th term by `$T_n$`.

---
### Example 1:

Show that the sequence defined by `$T_n = 3n + 5$` is an AP. Find its common difference.

#### Solution:

We have, `$T_n = 3n + 5$`. (i)

Replacing `$n$` by `$(n-1)$` in (i), we get:

$$
T_{n-1} = 3(n-1) + 5 \Rightarrow T_{n-1} = 3n + 2. \quad \text{(ii)}
$$

Subtracting (ii) from (i), we get:
`$(T_n - T_{n-1}) = (3n + 5) - (3n + 2) = 3$`, which is constant.

Hence, the given sequence is an AP with common difference 3.

---
### Example 2:

Show that the sequence `$\log a, \log\left(\frac{a^2}{b}\right), \log\left(\frac{a^3}{b^2}\right), \log\left(\frac{a^4}{b^3}\right), \ldots$` forms an AP. Find its common difference.

#### Solution:

By symmetry, we find that:

$$
T_n = \log\left(\frac{a^n}{b^{n-1}}\right) \quad \text{and} \quad T_{n-1} = \log\left(\frac{a^{n-1}}{b^{n-2}}\right).
$$

Therefore, the difference is:

$$
\begin{aligned}
(T_n - T_{n-1}) & = \log\left(\frac{a^n}{b^{n-1}}\right) - \log\left(\frac{a^{n-1}}{b^{n-2}}\right) \\
& = \log\left(\frac{a^n}{b^{n-1}} \times \frac{b^{n-2}}{a^{n-1}}\right) = \log\left(\frac{a}{b}\right) = \text{constant.}
\end{aligned}
$$

Hence, the given sequence is an AP with common difference `$\log\left(\frac{a}{b}\right)$`.

---
### Example 3:

Show that the sequence defined by `$T_n = 3n^2 + 2$` is not an AP.

#### Solution:

We have `$T_n = 3n^2 + 2$` and `$T_{n-1} = 3(n-1)^2 + 2 \Rightarrow T_{n-1} = 3n^2 - 6n + 5$`.

Therefore, the difference is:
`$(T_n - T_{n-1}) = (3n^2 + 2) - (3n^2 - 6n + 5) \Rightarrow (T_n - T_{n-1}) = (6n - 3)$`.

This shows that `$(T_n - T_{n-1})$` is not independent of `$n$` and therefore, it is not constant. Hence, the given sequence is not an AP.

---
## General Term of an AP

### Theorem 1

Show that the `$n$`th term of an AP with first term *a* and common difference *d* is given by `$T_n = a + (n-1)d$`.

#### Proof:

Let us consider an AP with first term *a* and common difference *d*. The AP is:

$$
a, (a+d), (a+2d), (a+3d), (a+4d), \ldots
$$

In this AP, we have:

$$
\begin{aligned}
& \text{first term, } T_1 = a = (a + 0 \times d) = a + (1-1)d; \\
& \text{second term, } T_2 = (a+d) = a + (2-1)d; \\
& \text{third term, } T_3 = (a+2d) = a + (3-1)d; \\
\end{aligned}
$$

Following this pattern, the `$n$`th term is `$T_n = a + (n-1)d$`.

Hence,
$$
T_n = a + (n-1)d
$$
This is called the **general term** of the AP.

---
## Properties of an AP

- If a constant is added to each term of an AP, then the resulting progression is an AP.
- If a constant is subtracted from each term of an AP, then the resulting progression is an AP.
- If each term of an AP is multiplied by the same nonzero number, then the resulting progression is an AP.
- If each term of an AP is divided by the same nonzero number, then the resulting progression is an AP.

---
## Solved Examples

### Example 1:

Show that the progression `$7, 12, 17, 22, 27, \ldots$` is an AP. Find its general term and the 14th term.

#### Solution:

We have `$(12-7) = (17-12) = (22-17) = (27-22) = 5$`, which is constant.
So, the given progression is an AP in which `$a=7$` and `$d=5$`.

Its general term, `$T_n = \{a + (n-1)d\} = 7 + (n-1) \times 5 \Rightarrow T_n = (5n + 2)$`.
Therefore, the 14th term, `$T_{14} = (5 \times 14 + 2) = 72$`.

---
### Example 2:

Show that the progression `$\log a, \log(ab), \log(ab^2), \log(ab^3), \ldots$` is an AP. Find its general term and the 10th term.

#### Solution:

We have:

$$
\begin{aligned}
& \log(ab) - \log a = \log a + \log b - \log a = \log b, \\
& \log(ab^2) - \log(ab) = (\log a + 2\log b) - (\log a + \log b) = \log b, \\
& \log(ab^3) - \log(ab^2) = (\log a + 3\log b) - (\log a + 2\log b) = \log b.
\end{aligned}
$$

`$\therefore (T_2 - T_1) = (T_3 - T_2) = (T_4 - T_3) = \log b = \text{constant}$`.
So, the given progression is an AP. Let `$A$` be the first term and `$d$` be the common difference. Then, `$A = \log a$` and `$d = \log b$`.

General term, `$T_n = A + (n-1)d \Rightarrow T_n = \log a + (n-1)\log b$`.
And, 10th term, `$T_{10} = \log a + (10-1)\log b = \log a + 9\log b$`.
`$\Rightarrow T_{10} = \log a + \log(b^9) \Rightarrow T_{10} = \log(ab^9)$`.

---
### Example 3:

Show that the progression `$21, 16, 11, 6, 1, \ldots$` is an AP. Write its first term and the common difference. Which term of this AP is -54?

#### Solution:

The given progression is `$21, 16, 11, 6, 1, \ldots$`.
We have `$(16-21) = (11-16) = (6-11) = (1-6) = -5$`, which is constant.

So, the given progression is an AP. Its first term, `$a = 21$`, and common difference, `$d = -5$`.
Let its `$n$`th term be -54. Then,

$$
\begin{aligned}
T_n = -54 & \Rightarrow a + (n-1)d = -54 \\
& \Rightarrow 21 + (n-1) \times (-5) = -54 \\
& \Rightarrow -5n + 26 = -54 \Rightarrow 5n = 80 \Rightarrow n = 16.
\end{aligned}
$$

Hence, the 16th term of the given AP is -54.

---
### Example 4:

Show that the progression `$-11, -7, -3, 1, 5, \ldots, 161$` is an AP. How many terms does it have?

#### Solution:

We have:
`$(-7) - (-11) = (-7 + 11) = 4$`, `$(-3) - (-7) = (-3 + 7) = 4$`, `$1 - (-3) = (1 + 3) = 4$`, and `$(5 - 1) = 4$`.
Since the difference is constant, the progression is an AP with `$a = -11$` and `$d = 4$`.

Let it have `$n$` terms. Then,
$$
\begin{aligned}
T_n = 161 & \Rightarrow a + (n-1)d = 161 \\
& \Rightarrow (-11) + (n-1) \times 4 = 161 \\
& \Rightarrow 4n = 176 \Rightarrow n = 44.
\end{aligned}
$$
Therefore, there are 44 terms in the given AP.

---
### Example 5:

Is 319 a term of the AP `$11, 17, 23, 29, 35, \ldots$`?

#### Solution:

In the given AP, we have `$a = 11$` and `$d = (17 - 11) = 6$`.
If possible, let the `$n$`th term of this AP be 319. Then,

$$
\begin{aligned}
T_n = 319 & \Rightarrow a + (n-1)d = 319 \\
& \Rightarrow 11 + (n-1) \times 6 = 319 \\
& \Rightarrow 6n + 5 = 319 \Rightarrow 6n = 314 \\
& \Rightarrow 3n = 157 \Rightarrow n = \frac{157}{3} = 52\frac{1}{3}.
\end{aligned}
$$

Since the number of terms cannot be a fraction, it follows that 319 is not a term of the given AP.

---
### Example 6:

Which term of the AP `$30, 29\frac{1}{4}, 28\frac{1}{2}, 27\frac{3}{4}, \ldots$` is the first negative term?

#### Solution:

We have the common difference: `$\left(\frac{117}{4} - 30\right) = \left(\frac{57}{2} - \frac{117}{4}\right) = \left(\frac{111}{4} - \frac{57}{2}\right) = \frac{-3}{4}$`.
So, `$a = 30$` and `$d = \frac{-3}{4}$`.

Let its `$n$`th term be the first negative term. Then,
$$
\begin{aligned}
T_n < 0 & \Rightarrow a + (n-1)d < 0 \\
& \Rightarrow 30 + (n-1) \times \left(\frac{-3}{4}\right) < 0 \\
& \Rightarrow 123 - 3n < 0 \Rightarrow 123 < 3n \\
& \Rightarrow 3n > 123 \Rightarrow n > 41.
\end{aligned}
$$
Hence, the 42nd term of the given AP is the first negative term.

And, `$T_{42} = a + (42-1)d = 30 + 41 \times \left(\frac{-3}{4}\right) = \frac{-3}{4}$`.
Thus, the first negative term of the given AP is `$\frac{-3}{4}$`.

---
### Example 7:

Find the 10th common term between the arithmetic series `$3+7+11+15+\ldots$` and `$1+6+11+16+\ldots$`.

#### Solution:

Clearly, the first common term in the two series is 11.
The common difference of the first series is 4, and for the second series is 5.
LCM of the common differences of the two series = `$\text{LCM}(4, 5) = 20$`.

Let us now consider an AP in which `$a = 11$` and `$d = 20$`. Every term of this AP is a common term of the two given series.
So, the required 10th common term is:
$$
\{11 + (10-1) \times 20\} = (11 + 180) = 191.
$$
Hence, 191 is the 10th common term of the two given series.

---
### Example 8:

If `$a_1, a_2, a_3, \ldots, a_n$` are in AP with common difference `$d$` (where `$d \neq 0$`), then prove that the sum of the series `$\sin d(\csc a_1 \csc a_2 + \csc a_2 \csc a_3 + \ldots + \csc a_{n-1} \csc a_n)$` is equal to `$(\cot a_1 - \cot a_n)$`.

#### Solution:

Since `$a_1, a_2, a_3, \ldots, a_n$` are in AP with common difference `$d$`, we have:
`$(a_2 - a_1) = (a_3 - a_2) = \ldots = (a_n - a_{n-1}) = d$`.

The given expression is:
$$
\begin{aligned}
& \sin d(\csc a_1 \csc a_2 + \csc a_2 \csc a_3 + \ldots + \csc a_{n-1} \csc a_n) \\
& = \frac{\sin d}{\sin a_1 \sin a_2} + \frac{\sin d}{\sin a_2 \sin a_3} + \ldots + \frac{\sin d}{\sin a_{n-1} \sin a_n} \\
& = \frac{\sin(a_2 - a_1)}{\sin a_1 \sin a_2} + \frac{\sin(a_3 - a_2)}{\sin a_2 \sin a_3} + \ldots + \frac{\sin(a_n - a_{n-1})}{\sin a_{n-1} \sin a_n} \\
& = \frac{\sin a_2 \cos a_1 - \cos a_2 \sin a_1}{\sin a_1 \sin a_2} + \frac{\sin a_3 \cos a_2 - \cos a_3 \sin a_2}{\sin a_2 \sin a_3} + \ldots + \frac{\sin a_n \cos a_{n-1} - \cos a_n \sin a_{n-1}}{\sin a_{n-1} \sin a_n} \\
& = \left(\frac{\cos a_1}{\sin a_1} - \frac{\cos a_2}{\sin a_2}\right) + \left(\frac{\cos a_2}{\sin a_2} - \frac{\cos a_3}{\sin a_3}\right) + \ldots + \left(\frac{\cos a_{n-1}}{\sin a_{n-1}} - \frac{\cos a_n}{\sin a_n}\right) \\
& = (\cot a_1 - \cot a_2) + (\cot a_2 - \cot a_3) + \ldots + (\cot a_{n-1} - \cot a_n) \\
& = (\cot a_1 - \cot a_n).
\end{aligned}
$$
Hence, the result is proven.

---
### Example 9:

If `$a_1, a_2, a_3, \ldots, a_n$` are in AP, where `$a_i > 0$` for each *i*, show that:

$$
\frac{1}{\sqrt{a_1} + \sqrt{a_2}} + \frac{1}{\sqrt{a_2} + \sqrt{a_3}} + \ldots + \frac{1}{\sqrt{a_{n-1}} + \sqrt{a_n}} = \frac{n-1}{\sqrt{a_1} + \sqrt{a_n}}
$$

#### Solution:

Let `$d$` be the common difference of the given AP. Then, `$(a_2 - a_1) = (a_3 - a_2) = \ldots = (a_n - a_{n-1}) = d$`.

The LHS can be rationalized term by term:
$$
\begin{aligned}
\text{LHS} & = \frac{\sqrt{a_2} - \sqrt{a_1}}{(\sqrt{a_2} + \sqrt{a_1})(\sqrt{a_2} - \sqrt{a_1})} + \frac{\sqrt{a_3} - \sqrt{a_2}}{(\sqrt{a_3} + \sqrt{a_2})(\sqrt{a_3} - \sqrt{a_2})} + \ldots + \frac{\sqrt{a_n} - \sqrt{a_{n-1}}}{(\sqrt{a_n} + \sqrt{a_{n-1}})(\sqrt{a_n} - \sqrt{a_{n-1}})} \\
& = \frac{\sqrt{a_2} - \sqrt{a_1}}{a_2 - a_1} + \frac{\sqrt{a_3} - \sqrt{a_2}}{a_3 - a_2} + \ldots + \frac{\sqrt{a_n} - \sqrt{a_{n-1}}}{a_n - a_{n-1}} \\
& = \frac{\sqrt{a_2} - \sqrt{a_1}}{d} + \frac{\sqrt{a_3} - \sqrt{a_2}}{d} + \ldots + \frac{\sqrt{a_n} - \sqrt{a_{n-1}}}{d} \\
& = \frac{1}{d} \{(\sqrt{a_2} - \sqrt{a_1}) + (\sqrt{a_3} - \sqrt{a_2}) + \ldots + (\sqrt{a_n} - \sqrt{a_{n-1}})\} \\
& = \frac{1}{d} (\sqrt{a_n} - \sqrt{a_1}) = \frac{1}{d} \left\{ (\sqrt{a_n} - \sqrt{a_1}) \times \frac{\sqrt{a_n} + \sqrt{a_1}}{\sqrt{a_n} + \sqrt{a_1}} \right\} \\
& = \frac{1}{d} \left\{ \frac{a_n - a_1}{\sqrt{a_n} + \sqrt{a_1}} \right\} = \frac{1}{d} \left\{ \frac{a_1 + (n-1)d - a_1}{\sqrt{a_1} + \sqrt{a_n}} \right\} \\
& = \frac{1}{d} \left\{ \frac{(n-1)d}{\sqrt{a_1} + \sqrt{a_n}} \right\} = \frac{n-1}{\sqrt{a_1} + \sqrt{a_n}} = \text{RHS}.
\end{aligned}
$$
Thus, LHS = RHS and the result follows.

---
## Finding the `$n$`-th Term from the End of an AP

### Theorem 2

Show that the `$n$`th term from the end of an AP with the first term *a*, common difference *d*, and the last term *l* is given by `$\{l - (n-1)d\}$`.

#### Proof:

Let *a* be the first term, *d* be the common difference, and *l* be the last term of a given AP. The AP can be written as:
`$a, a+d, a+2d, \ldots, (l-2d), (l-d), l$`.

From the end:
- last term = `$l = l - (1-1)d$`
- 2nd term from the end = `$(l-d) = l - (2-1)d$`
- 3rd term from the end = `$(l-2d) = l - (3-1)d$`

Following the pattern, the `$n$`th term from the end = `$l - (n-1)d$`.

---
### Example 12:

Find the 17th term from the end of the AP `$-36, -31, -26, -21, \ldots, 79$`.

#### Solution:

Here, `$a = -36$`, `$d = \{-31 - (-36)\} = 5$`, and `$l = 79$`.
The 17th term from the end is `$l - (n-1)d$`:
$$
= 79 - (17-1) \times 5 = (79 - 80) = -1.
$$
Hence, the 17th term from the end is -1.

---
## Important Results on AP

### Theorem 1

If the `$n$`th term of a progression is a linear expression in `$n$`, then show that it is an AP.

#### Proof:

Let the `$n$`th term of a progression be a linear expression in `$n$`.
Then, `$T_n = an + b$`, where *a* and *b* are constants. (i)

Replacing `$n$` by `$(n-1)$` in (i), we get:
`$T_{n-1} = a(n-1) + b$`. (ii)

On subtracting (ii) from (i), we get:
`$(T_n - T_{n-1}) = a$`, which is constant.
This shows that the difference between any two consecutive terms is constant. Hence, the progression is an AP.

---
### Theorem 2

If the `$m$`th term of an AP is `$(1/n)$` and its `$n$`th term is `$(1/m)$`, then show that its `$(mn)``th term is 1.

#### Proof:

Let the first term be *a* and the common difference be *d*.
Then, `$T_m = 1/n$` and `$T_n = 1/m$`.

$$
a + (m-1)d = \frac{1}{n} \quad \ldots(i)
$$
$$
a + (n-1)d = \frac{1}{m} \quad \ldots(ii)
$$

On subtracting (ii) from (i), we get:
`$(m-n)d = \left(\frac{1}{n} - \frac{1}{m}\right) \Rightarrow (m-n)d = \frac{m-n}{mn} \Rightarrow d = \frac{1}{mn}$`.

Putting `$d = \frac{1}{mn}$` in (i), we get:
`$a + \frac{m-1}{mn} = \frac{1}{n} \Rightarrow a = \frac{1}{n} - \frac{m-1}{mn} = \frac{m-(m-1)}{mn} \Rightarrow a = \frac{1}{mn}$`.

Thus, `$a = \frac{1}{mn}$` and `$d = \frac{1}{mn}$`.
`$\therefore (mn)`th term = `$a + (mn-1)d = \frac{1}{mn} + \frac{mn-1}{mn} = \frac{mn}{mn} = 1$`.
Hence, the `$(mn)`th term is 1.

---
### Theorem 3

If the `$m$`th term of a given AP is `$n$` and its `$n$`th term is `$m$`, then show that its `$p$`th term is `$(n+m-p)$`.

#### Proof:

Let the first term be *a* and the common difference be *d*.
Then, `$T_m = n$` and `$T_n = m$`.

$$
a + (m-1)d = n \quad \ldots(i)
$$
$$
a + (n-1)d = m \quad \ldots(ii)
$$

On subtracting (ii) from (i), we get:
`$(m-n)d = (n-m) \Rightarrow d = -1$`.

Putting `$d=-1$` in (i), we get `$a = (n+m-1)$`.
`$\therefore p$`th term = `$a + (p-1)d = (n+m-1) + (p-1) \times (-1) = (n+m-p)$`.
Hence, the `$p$`th term is `$(n+m-p)$`.

---
### Theorem 4

If `$m$` times the `$m$`th term of an AP is equal to `$n$` times its `$n$`th term, show that the `$(m+n)``th term of the AP is zero.

#### Proof:

Let the first term be *a* and the common difference be *d*.
Given, `$m \cdot T_m = n \cdot T_n$`.
`$\Rightarrow m \cdot [a + (m-1)d] = n \cdot [a + (n-1)d]$`.
`$\Rightarrow [(m^2 - n^2) - (m-n)] \times d = (n-m) \times a$`.
`$\Rightarrow (m+n-1)d = -a$`.
`$\Rightarrow a + (m+n-1)d = 0$`.
`$\Rightarrow T_{m+n} = 0$`.
Hence, the `$(m+n)``th term is zero.

---
### Theorem 5

If the `$p$`th, `$q$`th, and `$r$`th terms of an AP are `$a, b, c$` respectively, show that `$(q-r)a + (r-p)b + (p-q)c = 0$`.

#### Proof:

Let `$x$` be the first term and `$d$` be the common difference of the given AP.
Then, `$T_p = a, T_q = b, T_r = c$`.
`$\Rightarrow x + (p-1)d = a \quad \ldots(i)$`
`$\Rightarrow x + (q-1)d = b \quad \ldots(ii)$`
`$\Rightarrow x + (r-1)d = c \quad \ldots(iii)$`

On subtracting (ii) from (i), we get `$(p-q)d = (a-b) \Rightarrow d = \frac{a-b}{p-q}$`.
Again, subtracting (iii) from (ii), we get `$(q-r)d = (b-c) \Rightarrow d = \frac{b-c}{q-r}$`.

`$\therefore \frac{a-b}{p-q} = \frac{b-c}{q-r}$`.
`$\Rightarrow (q-r)(a-b) = (p-q)(b-c)$`.
`$\Rightarrow (q-r)a - (q-r)b = (p-q)b - (p-q)c$`.
`$\Rightarrow (q-r)a + (r-p)b + (p-q)c = 0$`.

---
## Solving Problems Based on AP

For solving problems based on AP, it is always convenient to make the following choices:
- **3 numbers in AP:** `$(a-d), a, (a+d)$`
- **4 numbers in AP:** `$(a-3d), (a-d), (a+d), (a+3d)$`
- **5 numbers in AP:** `$(a-2d), (a-d), a, (a+d), (a+2d)$`
- **6 numbers in AP:** `$(a-5d), (a-3d), (a-d), (a+d), (a+3d), (a+5d)$`

---
### Example 13:

The sum of three numbers in AP is 24 and their product is 440. Find the numbers.

#### Solution:

Let the required numbers be `$(a-d), a, (a+d)$`.
Sum: `$(a-d) + a + (a+d) = 24 \Rightarrow 3a = 24 \Rightarrow a = 8$`.

The numbers are `$(8-d), 8, (8+d)$`.
Product: `$(8-d) \times 8 \times (8+d) = 440$`.
`$\Rightarrow (8-d)(8+d) = 55$`.
`$\Rightarrow 64 - d^2 = 55 \Rightarrow d^2 = 9 \Rightarrow d = \pm 3$`.
Hence, the required numbers are `5, 8, 11` or `11, 8, 5`.

---
### Example 14:

The product of three numbers in AP is 224 and the largest number is 7 times the smallest. Find the numbers.

#### Solution:

Let the required numbers be `$(a-d), a, (a+d)$`.
Largest number = `$(a+d)$` and smallest number = `$(a-d)$`.

Given, `$a+d = 7(a-d) \Rightarrow 6a = 8d \Rightarrow d = \frac{3a}{4}$`. (i)
Product: `$(a-d) \times a \times (a+d) = 224 \Rightarrow a(a^2 - d^2) = 224$`.
`$\Rightarrow a\left(a^2 - \frac{9a^2}{16}\right) = 224 \Rightarrow a^3 = \left(224 \times \frac{16}{7}\right) = 512 = 8^3 \Rightarrow a=8$`.

Putting `$a=8$` in (i), we get `$d = \left(\frac{3}{4} \times 8\right) = 6$`.
The required numbers are `(8-6), 8, (8+6)`, i.e., `2, 8, 14`.

---
### Example 15:

Find four numbers in AP whose sum is 20 and the sum of whose squares is 120.

#### Solution:

Let the required numbers be `$(a-3d), (a-d), (a+d), (a+3d)$`.
Sum: `$(a-3d)+(a-d)+(a+d)+(a+3d) = 20 \Rightarrow 4a = 20 \Rightarrow a=5$`.

Sum of squares: `$(a-3d)^2+(a-d)^2+(a+d)^2+(a+3d)^2 = 120$`.
`$\Rightarrow 2(a^2+9d^2) + 2(a^2+d^2) = 120$`.
`$\Rightarrow 4a^2 + 20d^2 = 120 \Rightarrow a^2 + 5d^2 = 30$`.
`$\Rightarrow 25 + 5d^2 = 30 \Rightarrow 5d^2 = 5 \Rightarrow d^2 = 1 \Rightarrow d = \pm 1$`.

Hence, the required numbers are `2, 4, 6, 8` or `8, 6, 4, 2`.

---
