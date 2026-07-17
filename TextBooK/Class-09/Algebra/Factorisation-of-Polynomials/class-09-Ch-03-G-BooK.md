## Factorisation of $(x^3 + y^3 + z^3 - 3xyz)$

### Theorem 1: Prove that
$$
(x^3+y^3+z^3-3xyz) = (x+y+z)(x^2+y^2+z^2-xy-yz-zx)
$$

#### Proof:
We have
$$
\begin{aligned}
(x^3 + y^3 + z^3 - 3xyz) &= (x^3+y^3)+z^3-3xyz \\
&= \left[(x+y)^3 - 3xy(x+y)\right]+z^3 - 3xyz \\
&= u^3 - 3xyu + z^3 - 3xyz, \text{ where } (x+y)=u \\
&= (u^3+z^3) - 3xy(u+z) \\
&= (u+z)(u^2-uz+z^2) - 3xy(u+z) \\
&= (u+z)(u^2+z^2-uz-3xy) \\
&= (x+y+z)\left[(x+y)^2 + z^2 - (x+y)z - 3xy\right] \\
&= (x+y+z)(x^2+y^2+z^2-xy-yz-zx)
\end{aligned}
$$
$\therefore \quad (x^3+y^3+z^3-3xyz)=(x+y+z)(x^2+y^2+z^2-xy-yz-zx)$.

---

### Theorem 2: If $(x+y+z)=0$, prove that $(x^3+y^3+z^3)=3xyz$.

#### Proof:
We have
$$
\begin{aligned}
x+y+z=0 & \Rightarrow x+y=-z \\
& \Rightarrow (x+y)^3=(-z)^3 \\
& \Rightarrow x^3+y^3+3xy(x+y)=-z^3 \\
& \Rightarrow x^3+y^3+3xy(-z)=-z^3 \quad [\because(x+y)=-z] \\
& \Rightarrow x^3+y^3-3xyz=-z^3 \\
& \Rightarrow x^3+y^3+z^3=3xyz
\end{aligned}
$$
Hence, $(x+y+z)=0 \Rightarrow (x^3+y^3+z^3)=3xyz$.

---

## Summary

1.  $(x^3+y^3+z^3-3xyz)=(x+y+z)(x^2+y^2+z^2-xy-yz-zx)$
2.  $(x+y+z)=0 \Rightarrow (x^3+y^3+z^3)=3xyz$.

---

## Solved Examples

### Example 1: Find the product
$$
(2x-y+3z)(4x^2+y^2+9z^2+2xy+3yz-6xz)
$$

#### Solution:
Putting $2x=a$, $-y=b$ and $3z=c$, we get
$$
\begin{aligned}
& (2x-y+3z)(4x^2+y^2+9z^2+2xy+3yz-6xz) \\
= & \ [2x+(-y)+(3z)] \times [(2x)^2+(-y)^2+(3z)^2-(2x)(-y) -(-y)(3z)-(2x)(3z)] \\
= & \ (a+b+c) \times (a^2+b^2+c^2-ab-bc-ca) \\
= & \ a^3+b^3+c^3-3abc \\
= & \ (2x)^3+(-y)^3+(3z)^3-3 \times (2x) \times (-y) \times (3z) \\
= & \ 8x^3-y^3+27z^3+18xyz .
\end{aligned}
$$

---

### Example 2: Find the product
$$
(x-2y-z)(x^2+4y^2+z^2+2xy-2yz+zx)
$$

#### Solution:
Putting $x=a$, $-2y=b$ and $-z=c$, we get
$$
\begin{aligned}
& (x-2y-z)(x^2+4y^2+z^2+2xy-2yz+zx) \\
= & \ [x+(-2y)+(-z)] \times [x^2+(-2y)^2+(-z)^2-x \times (-2y) -(-2y) \times (-z)-(-z) \times x] \\
= & \ (a+b+c) \times (a^2+b^2+c^2-ab-bc-ca) \\
= & \ a^3+b^3+c^3-3abc \\
= & \ x^3+(-2y)^3+(-z)^3-3 \times x \times (-2y) \times (-z) \\
= & \ x^3-8y^3-z^3-6xyz .
\end{aligned}
$$

---

### Example 3: Factorise $8x^3+y^3+27z^3-18xyz$.

#### Solution:
We have
$$
\begin{aligned}
& 8x^3+y^3+27z^3-18xyz \\
= & \ (2x)^3+y^3+(3z)^3-3 \times (2x) \times y \times (3z) \\
= & \ a^3+b^3+c^3-3abc, \text{ where } 2x=a, y=b \text{ and } 3z=c \\
= & \ (a+b+c)(a^2+b^2+c^2-ab-bc-ca) \\
= & \ (2x+y+3z)(4x^2+y^2+9z^2-2xy-3yz-6xz) .
\end{aligned}
$$

---

### Example 4: Factorise $a^3-8b^3-64c^3-24abc$.

#### Solution:
We have
$$
\begin{aligned}
& a^3-8b^3-64c^3-24abc \\
= & \ (a)^3+(-2b)^3+(-4c)^3-3 \times a \times (-2b) \times (-4c) \\
= & \ x^3+y^3+z^3-3xyz, \text{ where } a=x, -2b=y \text{ and } -4c=z \\
= & \ (x+y+z)(x^2+y^2+z^2-xy-yz-zx) \\
= & \ (a-2b-4c)(a^2+4b^2+16c^2+2ab-8bc+4ac) .
\end{aligned}
$$

---

### Example 5: Factorise $2\sqrt{2}a^3+8b^3-27c^3+18\sqrt{2}abc$.

#### Solution:
We have
$$
\begin{aligned}
& 2\sqrt{2}a^3+8b^3-27c^3+18\sqrt{2}abc \\
= & \ (\sqrt{2}a)^3+(2b)^3+(-3c)^3-3 \times (\sqrt{2}a) \times (2b) \times (-3c) \\
= & \ x^3+y^3+z^3-3xyz, \text{ where } \sqrt{2}a=x, (2b)=y \text{ and } (-3c)=z \\
= & \ (x+y+z)(x^2+y^2+z^2-xy-yz-zx) \\
= & \ (\sqrt{2}a+2b-3c)(2a^2+4b^2+9c^2-2\sqrt{2}ab+6bc+3\sqrt{2}ca) .
\end{aligned}
$$

---

### Example 6: Factorise $a^3-b^3+1+3ab$.

#### Solution:
We have
$$
\begin{aligned}
& a^3-b^3+1+3ab \\
= & \ a^3+(-b)^3+(1)^3-3 \times a \times (-b) \times 1 \\
= & \ x^3+y^3+z^3-3xyz, \text{ where } a=x, (-b)=y \text{ and } 1=z \\
= & \ (x+y+z)(x^2+y^2+z^2-xy-yz-zx) \\
= & \ (a-b+1)(a^2+b^2+1+ab+b-a) \\
= & \ (a-b+1)(a^2+b^2+ab-a+b+1)
\end{aligned}
$$

---

### Example 7: If $a+b+c=5$ and $ab+bc+ca=10$ then prove that $a^3+b^3+c^3-3abc=-25$.

#### Solution:
We have
$$
\begin{aligned}
(a^3+b^3+c^3-3abc) &= (a+b+c)(a^2+b^2+c^2-ab-bc-ca) \\
&= (a+b+c)\left[(a+b+c)^2-3(ab+bc+ca)\right] \\
&= 5 \times \left[(5)^2-(3 \times 10)\right] \\
&= 5 \times (25-30) = 5 \times (-5) = -25
\end{aligned}
$$
Hence, $(a^3+b^3+c^3-3abc)=-25$.

---

### Example 8: Factorise $(x-2y)^3+(2y-3z)^3+(3z-x)^3$.

#### Solution:
Putting $(x-2y)=a$, $(2y-3z)=b$ and $(3z-x)=c$, we get
$$
\begin{aligned}
& (x-2y)^3+(2y-3z)^3+(3z-x)^3 \\
= & \ a^3+b^3+c^3, \text{ where } a+b+c=(x-2y)+(2y-3z)+(3z-x)=0 \\
= & \ 3abc \quad [\because a+b+c=0 \Rightarrow a^3+b^3+c^3=3abc] \\
= & \ 3(x-2y)(2y-3z)(3z-x) .
\end{aligned}
$$
$\therefore (x-2y)^3+(2y-3z)^3+(3z-x)^3 = 3(x-2y)(2y-3z)(3z-x)$.

---

### Example 9: Factorise $(p-q)^3+(q-r)^3+(r-p)^3$.

#### Solution:
Putting $(p-q)=x$, $(q-r)=y$ and $(r-p)=z$, we get
$$
\begin{aligned}
& (p-q)^3+(q-r)^3+(r-p)^3 \\
= & \ x^3+y^3+z^3, \text{ where } (x+y+z)=(p-q)+(q-r)+(r-p)=0 \\
= & \ 3xyz \quad [\because(x+y+z)=0 \Rightarrow (x^3+y^3+z^3)=3xyz] \\
= & \ 3(p-q)(q-r)(r-p) .
\end{aligned}
$$

---

### Example 10: Find the value of
(i) $(\frac{1}{2})^3+(\frac{1}{3})^3-(\frac{5}{6})^3$
(ii) $(0.2)^3-(0.3)^3+(0.1)^3$

#### Solution:
We have
(i)
$$
\begin{aligned}
& \left(\frac{1}{2}\right)^3+\left(\frac{1}{3}\right)^3-\left(\frac{5}{6}\right)^3 \\
= & \ \left(\frac{1}{2}\right)^3+\left(\frac{1}{3}\right)^3+\left(\frac{-5}{6}\right)^3 \\
= & \ a^3+b^3+c^3, \text{ where } a+b+c=\frac{1}{2}+\frac{1}{3}+\left(\frac{-5}{6}\right)=0 \\
= & \ 3abc \\
= & \ 3 \times \frac{1}{2} \times \frac{1}{3} \times \frac{(-5)}{6}=\frac{-5}{12}
\end{aligned}
$$
(ii)
$$
\begin{aligned}
& (0.2)^3-(0.3)^3+(0.1)^3 \\
= & \ (0.2)^3+(-0.3)^3+(0.1)^3 \\
= & \ a^3+b^3+c^3, \text{ where } a+b+c=0.2+(-0.3)+0.1=0 \\
= & \ 3abc \\
= & \ 3 \times 0.2 \times (-0.3) \times 0.1=-0.018
\end{aligned}
$$

---

### Example 11: Find the value of $x^3+y^3-12xy+64$, when $x+y=-4$.

#### Solution:
We have
$$
\begin{aligned}
& x^3+y^3-12xy+64 \\
= & \ x^3+y^3+4^3-3 \times x \times y \times 4 \\
= & \ x^3+y^3+z^3-3xyz, \text{ where } 4=z \\
= & \ (x+y+z)(x^2+y^2+z^2-xy-yz-zx) \\
= & \ (x+y+4)(x^2+y^2+16-xy-4y-4x) & [\because z=4] \\
= & \ (-4+4)(x^2+y^2+16-xy-4y-4x) & [\because(x+y)=-4] \\
= & \ 0 \times (x^2+y^2+16-xy-4y-4x)=0 .
\end{aligned}
$$
Hence, $x^3+y^3-12xy+64=0$.

---

### Example 12: Find the value of $x^3-8y^3-36xy-216$, when $x=2y+6$.

#### Solution:
We have
$$
\begin{aligned}
& x^3-8y^3-36xy-216 \\
= & \ x^3+(-8y^3)+(-216)-36xy \\
= & \ x^3+(-2y)^3+(-6)^3-3 \times x \times (-2y) \times (-6) \\
= & \ a^3+b^3+c^3-3abc, \text{ where } a=x, b=-2y \text{ and } c=-6 \\
= & \ (a+b+c)(a^2+b^2+c^2-ab-bc-ca) \\
= & \ (x-2y-6)(x^2+4y^2+36+2xy-12y+6x) \\
= & \ 0 \times (x^2+4y^2+36+2xy-12y+6x)=0 & [\because x-2y-6=0 \text{ (given)}]
\end{aligned}
$$
Hence, $x^3-8y^3-36xy-216=0$.

---

### Example 13: If $p=2-a$, prove that $a^3+6ap+p^3-8=0$.

#### Solution:
We have
$$
\begin{aligned}
& p=2-a \\
\Rightarrow & \ a+p-2=0 \\
\Rightarrow & \ x+y+z=0, \text{ where } a=x, p=y \text{ and } (-2)=z \\
\Rightarrow & \ x^3+y^3+z^3=3xyz \quad [\because x+y+z=0 \Rightarrow x^3+y^3+z^3=3xyz] \\
\Rightarrow & \ a^3+p^3+(-2)^3=3 \times a \times p \times (-2) \\
\Rightarrow & \ a^3+6ap+p^3-8=0 .
\end{aligned}
$$
Hence, $a^3+6ap+p^3-8=0$.

---

### Example 14: Prove that
$$
a^3+b^3+c^3-3abc=\frac{1}{2}(a+b+c) \times \left[(a-b)^2+(b-c)^2+(c-a)^2\right]
$$

#### Solution:
We have
$$
\begin{aligned}
& a^3+b^3+c^3-3abc \\
= & \ (a+b+c)(a^2+b^2+c^2-ab-bc-ca) \\
= & \ \frac{1}{2}(a+b+c) \times [2a^2+2b^2+2c^2-2ab-2bc-2ca] \\
= & \ \frac{1}{2}(a+b+c) \times [(a^2-2ab+b^2)+(b^2-2bc+c^2)+(c^2-2ca+a^2)] \\
= & \ \frac{1}{2}(a+b+c) \times [(a-b)^2+(b-c)^2+(c-a)^2] .
\end{aligned}
$$
$\therefore \quad a^3+b^3+c^3-3abc=\frac{1}{2}(a+b+c) \times [(a-b)^2+(b-c)^2+(c-a)^2]$.

---

### Example 15: Simplify $\frac{(a^2-b^2)^3+(b^2-c^2)^3+(c^2-a^2)^3}{(a-b)^3+(b-c)^3+(c-a)^3}$.

#### Solution:
Putting $a^2-b^2=x$, $b^2-c^2=y$ and $c^2-a^2=z$, we get
$$
\begin{align*}
& x+y+z=(a^2-b^2)+(b^2-c^2)+(c^2-a^2)=0 \\
\Rightarrow & \ x^3+y^3+z^3=3xyz \quad [\because x+y+z=0 \Rightarrow x^3+y^3+z^3=3xyz] \\
\Rightarrow & \ (a^2-b^2)^3+(b^2-c^2)^3+(c^2-a^2)^3=3(a^2-b^2)(b^2-c^2)(c^2-a^2) . \tag{i}
\end{align*}
$$
Again, putting $a-b=p$, $b-c=q$ and $c-a=r$, we get
$$
\begin{align*}
& (p+q+r)=(a-b)+(b-c)+(c-a)=0 \\
\Rightarrow & \ p^3+q^3+r^3=3pqr \quad [\because p+q+r=0 \Rightarrow p^3+q^3+r^3=3pqr] \\
\Rightarrow & \ (a-b)^3+(b-c)^3+(c-a)^3=3(a-b)(b-c)(c-a) . \tag{ii}
\end{align*}
$$
From (i) and (ii), we get
$$
\begin{aligned}
\frac{(a^2-b^2)^3+(b^2-c^2)^3+(c^2-a^2)^3}{(a-b)^3+(b-c)^3+(c-a)^3} & = \frac{3(a^2-b^2)(b^2-c^2)(c^2-a^2)}{3(a-b)(b-c)(c-a)} \\
& = (a+b)(b+c)(c+a)
\end{aligned}
$$

---

