## Problems on Geometric Progression (GP)

For solving problems on GP, it is always convenient to take:
- **3 numbers** in GP as $\frac{a}{r}, a, ar$.
- **4 numbers** in GP as $\frac{a}{r^{3}}, \frac{a}{r}, ar, ar^{3}$.
- **5 numbers** in GP as $\frac{a}{r^{2}}, \frac{a}{r}, a, ar, ar^{2}$.
- The terms as $a, ar, ar^{2}, \ldots$ when their product is not given.

---

## Solved Examples

### Example 1:

The sum of first three terms of a GP is $\frac{13}{12}$ and their product is $-1$. Find these terms.

#### Solution:

Let the first three terms of the given GP be $\frac{a}{r}, a,$ and $ar$.

Then, their product is:
$$
\frac{a}{r} \times a \times ar = -1 \Rightarrow a^{3} = -1 \Rightarrow a = -1
$$

And their sum is:
$$
\frac{a}{r} + a + ar = \frac{13}{12}
$$

Substituting $a = -1$:
$$
\frac{-1}{r} - 1 - r = \frac{13}{12}
$$

$$
\begin{aligned}
& \Rightarrow \frac{-1}{r} - r = \frac{13}{12} + 1 \\
& \Rightarrow \frac{-1-r^{2}}{r} = \frac{25}{12} \\
& \Rightarrow 25r = -12 - 12r^{2} \\
& \Rightarrow 12r^{2} + 25r + 12 = 0 \\
& \Rightarrow 12r^{2} + 16r + 9r + 12 = 0 \\
& \Rightarrow 4r(3r+4) + 3(3r+4) = 0 \\
& \Rightarrow (3r+4)(4r+3) = 0 \\
& \Rightarrow r = \frac{-4}{3} \text{ or } r = \frac{-3}{4}
\end{aligned}
$$

So, the required terms are:
$$
\left\{\frac{-1}{(-4 / 3)}, -1, -1\left(\frac{-4}{3}\right)\right\} \text{ or } \left\{\frac{-1}{(-3 / 4)}, -1, -1\left(\frac{-3}{4}\right)\right\}
$$
i.e., $\frac{3}{4}, -1, \frac{4}{3}$ or $\frac{4}{3}, -1, \frac{3}{4}$.

---

### Example 2:

Find three numbers in GP whose sum is 13 and the sum of whose squares is 91.

#### Solution:

Let the required numbers be $\frac{a}{r}, a,$ and $ar$. Then,
$$
\frac{a}{r} + a + ar = 13 \tag{i}
$$
and
$$
\frac{a^{2}}{r^{2}} + a^{2} + a^{2}r^{2} = 91
$$
On squaring both sides of (i), we get:
$$
\begin{align*}
& \left(\frac{a}{r} + a + ar\right)^{2} = 169 \\
\Rightarrow & \left(\frac{a^{2}}{r^{2}} + a^{2} + a^{2}r^{2}\right) + 2\left(\frac{a^{2}}{r} + a^{2} + a^{2}r\right) = 169 \\
\Rightarrow & 91 + 2a\left(\frac{a}{r} + a + ar\right) = 169 \\
\Rightarrow & 91 + 2a(13) = 169 \quad [\text{Using (i)}] \\
\Rightarrow & 91 + 26a = 169 \\
\Rightarrow & 26a = 78 \Rightarrow a = 3.
\end{align*}
$$
Putting $a=3$ in (i), we get:
$$
\begin{aligned}
& \frac{3}{r} + 3 + 3r = 13 \\
\Rightarrow & \frac{3}{r} + 3r = 10 \\
\Rightarrow & 3r^{2} - 10r + 3 = 0 \\
\Rightarrow & (r-3)(3r-1) = 0 \\
\Rightarrow & r=3 \text{ or } r=\frac{1}{3}
\end{aligned}
$$
Hence, the required numbers are **1, 3, 9** or **9, 3, 1**.

---

### Example 3:

Find three numbers in GP whose sum is 52 and the sum of whose products in pairs is 624.

#### Solution:

Let the required numbers be $a, ar, ar^{2}$. Then,
$$
a + ar + ar^{2} = 52 \Rightarrow a(1+r+r^{2}) = 52 \tag{i}
$$
and
$$
(a \cdot ar) + (ar \cdot ar^{2}) + (a \cdot ar^{2}) = 624 \Rightarrow a^{2}r(1+r+r^{2}) = 624 \tag{ii}
$$
On dividing (ii) by (i), we get:
$$
\frac{a^{2}r(1+r+r^{2})}{a(1+r+r^{2})} = \frac{624}{52} \Rightarrow ar = 12
$$
This means $a = \frac{12}{r}$. Putting this in (i), we get:
$$
\begin{aligned}
& \frac{12}{r} \cdot (1+r+r^{2}) = 52 \\
\Rightarrow & 3(1+r+r^{2}) = 13r \\
\Rightarrow & 3r^{2} - 10r + 3 = 0 \\
\Rightarrow & (3r-1)(r-3) = 0 \\
\Rightarrow & r = \frac{1}{3} \text{ or } r = 3
\end{aligned}
$$
If $r = \frac{1}{3}$, then $a = \frac{12}{1/3} = 36$.
If $r = 3$, then $a = \frac{12}{3} = 4$.

Hence, the required numbers are **36, 12, 4** or **4, 12, 36**.

---

### Example 4:

If the product of three numbers in GP is 216 and the sum of their products in pairs is 156, find the numbers.

#### Solution:

Let the required numbers be $\frac{a}{r}, a,$ and $ar$. Then,
$$
\frac{a}{r} \times a \times ar = 216 \Rightarrow a^{3} = 216 = 6^{3} \Rightarrow a=6
$$
And,
$$
\begin{align*}
& \left(\frac{a}{r} \times a\right) + (a \times ar) + \left(\frac{a}{r} \times ar\right) = 156 \\
\Rightarrow & a^{2}\left(\frac{1}{r} + r + 1\right) = 156 \\
\Rightarrow & (6^{2})\left(\frac{1+r+r^{2}}{r}\right) = 156 \quad [\because a=6] \\
\Rightarrow & 36(r^{2}+r+1) = 156r \\
\Rightarrow & 3(r^{2}+r+1) = 13r \\
\Rightarrow & 3r^{2} - 10r + 3 = 0 \\
\Rightarrow & (3r-1)(r-3) = 0 \\
\Rightarrow & r = \frac{1}{3} \text{ or } r=3
\end{align*}
$$
So, the required numbers are **18, 6, 2** or **2, 6, 18**.

---

### Example 5:

Find four numbers in GP such that the third term is greater than the first by 9 and the second term is greater than the fourth by 18.

#### Solution:

Let the required numbers be $a, ar, ar^{2},$ and $ar^{3}$. Then,
$$
T_{3} - T_{1} = 9 \Rightarrow ar^{2} - a = 9 \Rightarrow a(r^{2}-1) = 9 \tag{i}
$$
and
$$
T_{2} - T_{4} = 18 \Rightarrow ar - ar^{3} = 18 \Rightarrow ar(1-r^{2}) = 18 \tag{ii}
$$
On dividing (ii) by (i), we get:
$$
\frac{ar(1-r^{2})}{a(r^{2}-1)} = \frac{18}{9} \Rightarrow \frac{-ar(r^{2}-1)}{a(r^{2}-1)} = 2 \Rightarrow r = -2
$$
Putting $r=-2$ in (i), we get $a(4-1) = 9 \Rightarrow 3a = 9 \Rightarrow a=3$.

Hence, the required numbers are **3, -6, 12, and -24**.

---

### Example 6:

The sum of three numbers in GP is 56. If we subtract 1, 7, 21 from these numbers in that order, we get an AP. Find the numbers.

#### Solution:

Let the required numbers be $a, ar,$ and $ar^{2}$. Then,
$$
a + ar + ar^{2} = 56 \tag{i}
$$
Also, $(a-1), (ar-7),$ and $(ar^{2}-21)$ are in AP.
$$
\therefore 2(ar-7) = (a-1) + (ar^{2}-21) \Rightarrow a + ar^{2} = 2ar + 8 \tag{ii}
$$
Using (ii) in (i), we get:
$$
ar + (2ar+8) = 56 \Rightarrow 3ar = 48 \Rightarrow ar=16 \Rightarrow a = \frac{16}{r}
$$
Substituting $ar=16$ into (ii):
$$
a + ar^{2} = 2(16) + 8 \Rightarrow a + a\left(\frac{16}{a}\right)^2 = 40
$$
$$
a + \frac{256}{a} = 40
$$
Substituting $a+ar^2 = 2ar+8$ into $a+ar+ar^2=56$, we get
$$
ar + (2ar+8) = 56 \Rightarrow 3ar = 48 \Rightarrow ar = 16 \Rightarrow r = \frac{16}{a}
$$
Putting $ar=16$ back into (i):
$$
\begin{aligned}
& a + 16 + a\left(\frac{16}{a}\right)^2 = 56 \\
\Rightarrow & a + 16 + \frac{256}{a} = 56 \\
\Rightarrow & a + \frac{256}{a} = 40 \\
\Rightarrow & a^{2} - 40a + 256 = 0 \\
\Rightarrow & a^{2} - 8a - 32a + 256 = 0 \\
\Rightarrow & a(a-8) - 32(a-8) = 0 \\
\Rightarrow & (a-8)(a-32) = 0 \\
\Rightarrow & a=8 \text{ or } a=32
\end{aligned}
$$
Now, if $a=8 \Rightarrow r = \frac{16}{8} = 2$.
And, if $a=32 \Rightarrow r = \frac{16}{32} = \frac{1}{2}$.

Hence, the required numbers are **(8, 16, 32)** or **(32, 16, 8)**.

---

