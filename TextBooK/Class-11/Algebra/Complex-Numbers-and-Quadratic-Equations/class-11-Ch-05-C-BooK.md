## Some Results on Modulus and Conjugate of Complex Numbers

### Theorem 1
For any complex numbers $z$, $z_{1}$ and $z_{2}$ prove that:

1.  $\overline{(\bar{z})}=z$
2.  $z \bar{z}=|z|^{2}=\{\operatorname{Re} z\}^{2}+\{\operatorname{Im}(z)\}^{2}$
3.  $z+\bar{z}=2 \operatorname{Re}(z)$
4.  $z-\bar{z}=2 i \cdot \operatorname{Im}(z)$
5.  $z=\bar{z} \Leftrightarrow z$ is **purely real**
6.  $z+\bar{z}=0 \Leftrightarrow z$ is **purely imaginary**
7.  $\overline{z_{1}+z_{2}}=\bar{z}_{1}+\bar{z}_{2}$
8.  $\overline{z_{1}-z_{2}}=\bar{z}_{1}-\bar{z}_{2}$
9.  $\overline{z_{1} z_{2}}=\left(\bar{z}_{1}\right)\left(\bar{z}_{2}\right)$
10. $\overline{\left(\frac{z_{1}}{z_{2}}\right)}=\frac{\bar{z}_{1}}{\bar{z}_{2}}, z_{2} \neq 0$

#### Proof:
Let $z=(a+ib)$, $z_{1}=(a_{1}+ib_{1})$ and $z_{2}=(a_{2}+ib_{2})$. Then,

1.  $z=(a+ib) \Rightarrow \bar{z}=\overline{(a+ib)}=(a-ib)$
    $$
    \Rightarrow \overline{(\bar{z})}=\overline{(a-ib)}=(a+ib)=z
    $$
    Hence, $\overline{(\bar{z})}=z$.

2.  $z \bar{z}=(a+ib) \overline{(a+ib)}=(a+ib)(a-ib)$
    $$
    \begin{aligned}
    & = (a^{2}+b^{2})=\{\operatorname{Re}(z)\}^{2}+\{\operatorname{Im}(z)\}^{2}=|z|^{2} \\
    \therefore \quad & z \bar{z}=\{\operatorname{Re}(z)\}^{2}+\{\operatorname{Im}(z)\}^{2}=|z|^{2}
    \end{aligned}
    $$

3.  $z+\bar{z}=(a+ib)+\overline{(a+ib)}$
    $$
    \begin{aligned}
    & = (a+ib)+(a-ib)=2a=2 \operatorname{Re}(z) \\
    \therefore \quad & z+\bar{z}=2 \operatorname{Re}(z)
    \end{aligned}
    $$

4.  $z-\bar{z}=(a+ib)-\overline{(a+ib)}$
    $$
    \begin{aligned}
    & = (a+ib)-(a-ib)=2ib=2i \cdot \operatorname{Im}(z) \\
    \therefore \quad & z-\bar{z}=2i \cdot \operatorname{Im}(z)
    \end{aligned}
    $$

5.  $z=\bar{z} \Leftrightarrow (a+ib)=\overline{(a+ib)}$
    $$
    \begin{aligned}
    & \Leftrightarrow (a+ib)=(a-ib) \Leftrightarrow 2ib=0 \\
    & \Leftrightarrow b=0 \Leftrightarrow \operatorname{Im}(z)=0
    \end{aligned}
    $$
    $\therefore z=\bar{z} \Leftrightarrow \operatorname{Im}(z)=0 \Leftrightarrow z$ is **purely real**.

6.  $z+\bar{z}=0 \Leftrightarrow (a+ib)+\overline{(a+ib)}=0$
    $$
    \Leftrightarrow(a+ib)+(a-ib)=0 \Leftrightarrow 2a=0 \Leftrightarrow a=0
    $$
    $\Leftrightarrow z$ is **purely imaginary**.
    $\therefore z+\bar{z}=0 \Leftrightarrow z$ is **purely imaginary**.

7.  $\overline{z_{1}+z_{2}}=\overline{(a_{1}+ib_{1})+(a_{2}+ib_{2})}$
    $$
    \begin{aligned}
    &=\overline{(a_{1}+a_{2})+i(b_{1}+b_{2})} = (a_{1}+a_{2})-i(b_{1}+b_{2}) \\
    &=(a_{1}-ib_{1})+(a_{2}-ib_{2}) = \bar{z}_{1}+\bar{z}_{2}
    \end{aligned}
    $$
    $\therefore \overline{z_{1}+z_{2}} = \bar{z}_{1}+\bar{z}_{2}$.

8.  $\overline{z_{1}-z_{2}} = \overline{(a_{1}+ib_{1})-(a_{2}+ib_{2})}$
    $$
    \begin{aligned}
    & =\overline{(a_{1}-a_{2})+i(b_{1}-b_{2})} = (a_{1}-a_{2})-i(b_{1}-b_{2}) \\
    & =(a_{1}-ib_{1})-(a_{2}-ib_{2}) = \bar{z}_{1}-\bar{z}_{2}
    \end{aligned}
    $$
    $\therefore \overline{z_{1}-z_{2}} = \bar{z}_{1}-\bar{z}_{2}$.

9.  $z_{1} z_{2} = (a_{1}+ib_{1})(a_{2}+ib_{2})=(a_{1}a_{2}-b_{1}b_{2})+i(a_{1}b_{2}+b_{1}a_{2})$
    $$
    \begin{aligned}
    \Rightarrow \quad \overline{z_{1} z_{2}} &= \overline{(a_{1}a_{2}-b_{1}b_{2})+i(a_{1}b_{2}+b_{1}a_{2})} \\
    &= (a_{1}a_{2}-b_{1}b_{2})-i(a_{1}b_{2}+b_{1}a_{2}) \\
    &= (a_{1}-ib_{1})(a_{2}-ib_{2})=\bar{z}_{1}\bar{z}_{2}
    \end{aligned}
    $$
    $\therefore \overline{z_{1}z_{2}} = \bar{z}_{1}\bar{z}_{2}$.

10. $\frac{z_{1}}{z_{2}} = \frac{(a_{1}+ib_{1})}{(a_{2}+ib_{2})} = \frac{(a_{1}+ib_{1})}{(a_{2}+ib_{2})} \times \frac{(a_{2}-ib_{2})}{(a_{2}-ib_{2})}$
    $$
    \begin{aligned}
    &= \frac{(a_{1}+ib_{1})(a_{2}-ib_{2})}{(a_{2}^{2}+b_{2}^{2})} = \frac{(a_{1}a_{2}+b_{1}b_{2})+i(b_{1}a_{2}-a_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})} \\
    &= \frac{(a_{1}a_{2}+b_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})}+i\frac{(b_{1}a_{2}-a_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})}
    \end{aligned}
    $$
    $$
    \overline{\left(\frac{z_{1}}{z_{2}}\right)} = \frac{(a_{1}a_{2}+b_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})}-i\frac{(b_{1}a_{2}-a_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})} \quad \text{(i)}
    $$
    Also,
    $$
    \begin{aligned}
    \frac{\bar{z}_{1}}{\bar{z}_{2}} &= \bar{z}_{1} \cdot \frac{1}{\bar{z}_{2}} = (a_{1}-ib_{1}) \cdot \left\{\frac{1}{(a_{2}-ib_{2})} \times \frac{(a_{2}+ib_{2})}{(a_{2}+ib_{2})}\right\} \\
    &= \frac{(a_{1}-ib_{1})(a_{2}+ib_{2})}{(a_{2}^{2}+b_{2}^{2})} = \frac{(a_{1}a_{2}+b_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})}-i\frac{(b_{1}a_{2}-a_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})} \quad \text{(ii)}
    \end{aligned}
    $$
    From (i) and (ii), we get $\overline{\left(\frac{z_{1}}{z_{2}}\right)}=\frac{\bar{z}_{1}}{\bar{z}_{2}}$.

---
### Theorem 2
For all complex numbers $z$, $z_{1}$ and $z_{2}$, prove that:

1.  $z \bar{z}=|z|^{2}$
2.  $|z|=|\bar{z}|=|-z|$
3.  $|z|=0 \Leftrightarrow z=0$
4.  $-|z| \leq \operatorname{Re}(z) \leq|z|$
5.  $-|z| \leq \operatorname{Im}(z) \leq|z|$
6.  $|z_{1} z_{2}|=|z_{1}||z_{2}|$
7.  $\left|\frac{z_{1}}{z_{2}}\right|=\frac{|z_{1}|}{|z_{2}|}, z_{2} \neq 0$

#### Proof:
Let $z=(a+ib)$, $z_{1}=(a_{1}+ib_{1})$ and $z_{2}=(a_{2}+ib_{2})$. Then,

1.  $z\bar{z}=(a+ib)\overline{(a+ib)}=(a+ib)(a-ib)=(a^{2}+b^{2})=|z|^{2}$.
    $\therefore z\bar{z}=|z|^{2}$.

2.  $|z|=|a+ib|=\sqrt{a^{2}+b^{2}}$, $|\bar{z}|=|a-ib|=\sqrt{a^{2}+(-b)^{2}}=\sqrt{a^{2}+b^{2}}$ and $|-z|=|-(a+ib)|=|(-a)+i(-b)|=\sqrt{(-a)^{2}+(-b)^{2}}=\sqrt{a^{2}+b^{2}}$.
    $\therefore |z|=|\bar{z}|=|-z|$.

3.  $|z|=0 \Leftrightarrow |z|^{2}=0 \Leftrightarrow |a+ib|^{2}=0 \Leftrightarrow a^{2}+b^{2}=0 \Leftrightarrow a=0 \text{ and } b=0 \Leftrightarrow z=0$.

4.  Let $z=(a+ib)$. Then, $|z|=\sqrt{a^{2}+b^{2}}$. Clearly, $-\sqrt{a^{2}+b^{2}} \leq a \leq \sqrt{a^{2}+b^{2}}$.
    $\therefore -|z| \leq \operatorname{Re}(z) \leq |z|$.

5.  Let $z=(a+ib)$. Then, $|z|=\sqrt{a^{2}+b^{2}}$. Clearly, $-\sqrt{a^{2}+b^{2}} \leq b \leq \sqrt{a^{2}+b^{2}}$.
    $\therefore -|z| \leq \operatorname{Im}(z) \leq |z|$.

6.  $z_{1}z_{2}=(a_{1}+ib_{1})(a_{2}+ib_{2})=(a_{1}a_{2}-b_{1}b_{2})+i(a_{1}b_{2}+b_{1}a_{2})$.
    $$
    \begin{aligned}
    \therefore |z_{1}z_{2}| &= \sqrt{(a_{1}a_{2}-b_{1}b_{2})^{2}+(a_{1}b_{2}+b_{1}a_{2})^{2}} \\
    &= \sqrt{a_{1}^{2}a_{2}^{2}+b_{1}^{2}b_{2}^{2}+a_{1}^{2}b_{2}^{2}+b_{1}^{2}a_{2}^{2}} \\
    &= \sqrt{a_{1}^{2}(a_{2}^{2}+b_{2}^{2})+b_{1}^{2}(a_{2}^{2}+b_{2}^{2})} = \sqrt{(a_{1}^{2}+b_{1}^{2})(a_{2}^{2}+b_{2}^{2})} \\
    &= \left\{\sqrt{a_{1}^{2}+b_{1}^{2}}\right\}\left\{\sqrt{a_{2}^{2}+b_{2}^{2}}\right\} = |z_{1}|\cdot|z_{2}|
    \end{aligned}
    $$
    $\therefore |z_{1}z_{2}|=|z_{1}|\cdot|z_{2}|$.

7.  $\frac{z_{1}}{z_{2}} = z_{1} \cdot \frac{1}{z_{2}} = (a_{1}+ib_{1}) \cdot \left\{\frac{1}{(a_{2}+ib_{2})} \times \frac{(a_{2}-ib_{2})}{(a_{2}-ib_{2})}\right\}$
    $$
    \begin{gathered}
    = \frac{(a_{1}+ib_{1})(a_{2}-ib_{2})}{(a_{2}+ib_{2})(a_{2}-ib_{2})} = \frac{(a_{1}a_{2}+b_{1}b_{2})+i(b_{1}a_{2}-a_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})} \\
    = \frac{(a_{1}a_{2}+b_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})}+i\frac{(a_{2}b_{1}-a_{1}b_{2})}{(a_{2}^{2}+b_{2}^{2})}
    \end{gathered}
    $$
    $$
    \begin{aligned}
    \Rightarrow \left|\frac{z_{1}}{z_{2}}\right| &= \sqrt{\left\{\frac{a_{1}a_{2}+b_{1}b_{2}}{a_{2}^{2}+b_{2}^{2}}\right\}^{2}+\left\{\frac{a_{2}b_{1}-a_{1}b_{2}}{a_{2}^{2}+b_{2}^{2}}\right\}^{2}} \\
    &= \sqrt{\frac{(a_{1}a_{2}+b_{1}b_{2})^{2}+(a_{2}b_{1}-a_{1}b_{2})^{2}}{(a_{2}^{2}+b_{2}^{2})^{2}}} \\
    &= \sqrt{\frac{a_{1}^{2}a_{2}^{2}+b_{1}^{2}b_{2}^{2}+a_{2}^{2}b_{1}^{2}+a_{1}^{2}b_{2}^{2}}{(a_{2}^{2}+b_{2}^{2})^{2}}} \\
    &= \sqrt{\frac{a_{1}^{2}(a_{2}^{2}+b_{2}^{2})+b_{1}^{2}(a_{2}^{2}+b_{2}^{2})}{(a_{2}^{2}+b_{2}^{2})^{2}}} \\
    &= \sqrt{\frac{(a_{2}^{2}+b_{2}^{2})(a_{1}^{2}+b_{1}^{2})}{(a_{2}^{2}+b_{2}^{2})^{2}}} = \sqrt{\frac{(a_{1}^{2}+b_{1}^{2})}{(a_{2}^{2}+b_{2}^{2})}} = \frac{\sqrt{a_{1}^{2}+b_{1}^{2}}}{\sqrt{a_{2}^{2}+b_{2}^{2}}} = \frac{|z_{1}|}{|z_{2}|}
    \end{aligned}
    $$
    Hence, $\left|\frac{z_{1}}{z_{2}}\right|=\frac{|z_{1}|}{|z_{2}|}, z_{2} \neq 0$.

---
### Theorem 3
For all complex numbers $z_{1}$ and $z_{2}$, prove that:

1.  $\operatorname{Re}(z_{1}z_{2})=\operatorname{Re}(z_{1})\cdot\operatorname{Re}(z_{2})-\operatorname{Im}(z_{1})\cdot\operatorname{Im}(z_{2})$
2.  $\operatorname{Im}(z_{1}z_{2})=\operatorname{Re}(z_{1})\cdot\operatorname{Im}(z_{2})+\operatorname{Im}(z_{1})\cdot\operatorname{Re}(z_{2})$

#### Proof:
Let $z_{1}=(a_{1}+ib_{1})$ and $z_{2}=(a_{2}+ib_{2})$. Then,
$$
\begin{aligned}
\Rightarrow \quad z_{1}z_{2}&=(a_{1}+ib_{1})(a_{2}+ib_{2}) \\
\Rightarrow \quad z_{1}z_{2}&=(a_{1}a_{2}-b_{1}b_{2})+i(a_{1}b_{2}+b_{1}a_{2})
\end{aligned}
$$
1.  $\operatorname{Re}(z_{1}z_{2})=(a_{1}a_{2}-b_{1}b_{2}) = \operatorname{Re}(z_{1})\cdot\operatorname{Re}(z_{2})-\operatorname{Im}(z_{1})\cdot\operatorname{Im}(z_{2})$
2.  $\operatorname{Im}(z_{1}z_{2})=(a_{1}b_{2}+b_{1}a_{2}) = \operatorname{Re}(z_{1})\cdot\operatorname{Im}(z_{2})+\operatorname{Im}(z_{1})\cdot\operatorname{Re}(z_{2})$

---
### Theorem 4
For all $a, b \in R$ and $z_{1}, z_{2} \in C$, prove that
$$
|az_{1}-bz_{2}|^{2}+|bz_{1}+az_{2}|^{2}=(a^{2}+b^{2})(|z_{1}|^{2}+|z_{2}|^{2})
$$

#### Proof:
We have
$$
\begin{aligned}
|az_{1}-bz_{2}|^{2} &= (az_{1}-bz_{2})\overline{(az_{1}-bz_{2})} \\
&= (az_{1}-bz_{2})(a\bar{z}_{1}-b\bar{z}_{2}) \quad [\because a, b \in R] \\
&= a^{2}z_{1}\bar{z}_{1}+b^{2}z_{2}\bar{z}_{2}-abz_{1}\bar{z}_{2}-abz_{2}\bar{z}_{1} \\
&= a^{2}|z_{1}|^{2}+b^{2}|z_{2}|^{2}-ab(z_{1}\bar{z}_{2}+z_{2}\bar{z}_{1}) \quad \text{(i)}
\end{aligned}
$$
And
$$
\begin{aligned}
|bz_{1}+az_{2}|^{2} &= (bz_{1}+az_{2})\overline{(bz_{1}+az_{2})} \\
&= (bz_{1}+az_{2})(b\bar{z}_{1}+a\bar{z}_{2}) \\
&= b^{2}z_{1}\bar{z}_{1}+a^{2}z_{2}\bar{z}_{2}+abz_{1}\bar{z}_{2}+abz_{2}\bar{z}_{1} \\
&= b^{2}|z_{1}|^{2}+a^{2}|z_{2}|^{2}+ab(z_{1}\bar{z}_{2}+z_{2}\bar{z}_{1}) \quad \text{(ii)}
\end{aligned}
$$
Adding the corresponding sides of (i) and (ii), we get
$$
|az_{1}-bz_{2}|^{2}+|bz_{1}+az_{2}|^{2}=(a^{2}+b^{2})(|z_{1}|^{2}+|z_{2}|^{2})
$$
---
## Solved Examples

### Example 1:
If $\left|\frac{z-5i}{z+5i}\right|=1$, show that $z$ is a real number.

#### Solution:
Let $z=(x+iy)$. Then,
$$
\left|\frac{z-5i}{z+5i}\right|=1 \Rightarrow \frac{|z-5i|}{|z+5i|}=1 \quad \left[\because\left|\frac{z_{1}}{z_{2}}\right|=\frac{|z_{1}|}{|z_{2}|}\right]
$$
$$
\begin{aligned}
& \Rightarrow |z-5i|=|z+5i| \Rightarrow |z-5i|^{2}=|z+5i|^{2} \\
& \Rightarrow |(x+iy)-5i|^{2}=|(x+iy)+5i|^{2} \\
& \Rightarrow |x+i(y-5)|^{2}=|x+i(y+5)|^{2} \\
& \Rightarrow x^{2}+(y-5)^{2}=x^{2}+(y+5)^{2} \quad [\because z=(x+iy)] \\
& \Rightarrow (y+5)^{2}-(y-5)^{2}=0 \Rightarrow 4 \times y \times 5=0 \Rightarrow y=0
\end{aligned}
$$
$\therefore z=x+i0 \Rightarrow z=x$, where $x$ is real. Hence, $z$ is a **real number**.

---
### Example 2:
If $(a+ib) = \frac{(x+i)^{2}}{(2x^{2}+1)}$ then prove that $(a^{2}+b^{2})=\frac{(x^{2}+1)^{2}}{(2x^{2}+1)^{2}}$.

#### Solution:
We have
$$
\begin{aligned}
(a+ib) &= \frac{(x+i)^{2}}{(2x^{2}+1)} = \frac{(x^{2}+i^{2}+2ix)}{(2x^{2}+1)} = \frac{(x^{2}-1)+i(2x)}{(2x^{2}+1)} \\
\Rightarrow (a+ib) &= \frac{(x^{2}-1)}{(2x^{2}+1)} + i \cdot \frac{2x}{(2x^{2}+1)} \\
\Rightarrow |a+ib|^{2} &= \left|\frac{(x^{2}-1)}{(2x^{2}+1)}+i \cdot \frac{2x}{(2x^{2}+1)}\right|^{2} \\
\Rightarrow (a^{2}+b^{2}) &= \left\{\frac{(x^{2}-1)^{2}}{(2x^{2}+1)^{2}}+\frac{4x^{2}}{(2x^{2}+1)^{2}}\right\} \\
&= \frac{(x^{2}-1)^{2}+4x^{2}}{(2x^{2}+1)^{2}} = \frac{(x^{2}+1)^{2}}{(2x^{2}+1)^{2}}
\end{aligned}
$$
Hence, $(a^{2}+b^{2})=\frac{(x^{2}+1)^{2}}{(2x^{2}+1)^{2}}$.

---
### Example 3:
If $(p+iq) = \frac{(a+i)^{2}}{(2a-i)}$ then prove that $(p^{2}+q^{2})=\frac{(a^{2}+1)^{2}}{(4a^{2}+1)}$.

#### Solution:
We have
$$
\begin{aligned}
(p+iq) &= \frac{(a+i)^{2}}{(2a-i)} = \frac{(a^{2}+i^{2}+2ai)}{(2a-i)} = \frac{(a^{2}-1)+2ai}{(2a-i)} \\
\Rightarrow |p+iq|^{2} &= \frac{|(a^{2}-1)+2ai|^{2}}{|2a-i|^{2}} = \frac{(a^{2}-1)^{2}+4a^{2}}{\{4a^{2}+(-1)^{2}\}} = \frac{(a^{2}+1)^{2}}{(4a^{2}+1)} \\
\Rightarrow (p^{2}+q^{2}) &= \frac{(a^{2}+1)^{2}}{(4a^{2}+1)}
\end{aligned}
$$
Hence, $(p^{2}+q^{2})=\frac{(a^{2}+1)^{2}}{(4a^{2}+1)}$.

---
### Example 4:
Let $z$ be a complex number such that $\left|\frac{1-iz}{z-i}\right|=1$. Show that $z$ is **purely real**.

#### Solution:
Let $z=x+iy$. Then,
$$
\begin{aligned}
& \left|\frac{1-iz}{z-i}\right|=1 \Rightarrow \frac{|1-iz|}{|z-i|}=1 \quad \left[\because\left|\frac{z_{1}}{z_{2}}\right|=\frac{|z_{1}|}{|z_{2}|}\right] \\
\Rightarrow & |1-iz|=|z-i| \Rightarrow |1-iz|^{2}=|z-i|^{2} \\
\Rightarrow & |1-i(x+iy)|^{2}=|(x+iy)-i|^{2} \\
\Rightarrow & |(1+y)-ix|^{2}=|x+(y-1)i|^{2} \\
\Rightarrow & (1+y)^{2}+(-x)^{2}=x^{2}+(y-1)^{2} \\
\Rightarrow & 1+y^{2}+2y+x^{2}=x^{2}+y^{2}-2y+1 \\
\Rightarrow & 4y=0 \Rightarrow y=0
\end{aligned}
$$
$\therefore z=x+0y$ and hence $z$ is **purely real**.

---
### Example 5:
If $z_{1}$ and $z_{2}$ are complex numbers such that $\frac{2z_{1}}{3z_{2}}$ is **purely imaginary** then prove that $\left|\frac{z_{1}-z_{2}}{z_{1}+z_{2}}\right|=1$.

#### Solution:
Let $\frac{2z_{1}}{3z_{2}}=ki$ for some real number $k$. Then,
$$
\frac{2z_{1}}{3z_{2}}=ki \Rightarrow \frac{z_{1}}{z_{2}}=\frac{3ki}{2}
$$
$$
\therefore \left|\frac{z_{1}-z_{2}}{z_{1}+z_{2}}\right| = \frac{|z_{1}-z_{2}|}{|z_{1}+z_{2}|} = \frac{\left|\frac{z_{1}}{z_{2}}-1\right|}{\left|\frac{z_{1}}{z_{2}}+1\right|} = \frac{\left|\frac{3ki}{2}-1\right|}{\left|\frac{3ki}{2}+1\right|} = \frac{|3ki-2|}{|3ki+2|} = \frac{\sqrt{9k^{2}+4}}{\sqrt{9k^{2}+4}}=1
$$
Hence, $\left|\frac{z_{1}-z_{2}}{z_{1}+z_{2}}\right|=1$.

---
### Example 6:
If $|z_{1}|=|z_{2}|=|z_{3}|=\dots=|z_{n}|=1$ then prove that
$$
\left|\frac{1}{z_{1}}+\frac{1}{z_{2}}+\frac{1}{z_{3}}+\dots+\frac{1}{z_{n}}\right|=|z_{1}+z_{2}+z_{3}+\dots+z_{n}|
$$

#### Solution:
We have
$$
\begin{aligned}
& |z_{1}|=|z_{2}|=|z_{3}|=\dots=|z_{n}|=1 \\
\Rightarrow \quad & |z_{1}|^{2}=|z_{2}|^{2}=|z_{3}|^{2}=\dots=|z_{n}|^{2}=1 \\
\Rightarrow \quad & z_{1}\bar{z}_{1}=1, z_{2}\bar{z}_{2}=1, z_{3}\bar{z}_{3}=1, \dots, z_{n}\bar{z}_{n}=1 \\
\Rightarrow \quad & \frac{1}{z_{1}}=\bar{z}_{1}, \frac{1}{z_{2}}=\bar{z}_{2}, \frac{1}{z_{3}}=\bar{z}_{3}, \dots, \frac{1}{z_{n}}=\bar{z}_{n}
\end{aligned}
$$
$$
\begin{aligned}
\Rightarrow \left|\frac{1}{z_{1}}+\frac{1}{z_{2}}+\frac{1}{z_{3}}+\dots+\frac{1}{z_{n}}\right| &= \left|\bar{z}_{1}+\bar{z}_{2}+\bar{z}_{3}+\dots+\bar{z}_{n}\right| \\
&= \left|\overline{z_{1}+z_{2}+z_{3}+\dots+z_{n}}\right| \\
&= |z_{1}+z_{2}+z_{3}+\dots+z_{n}| \quad [\because|\bar{z}|=|z|]
\end{aligned}
$$
$\therefore \left|\frac{1}{z_{1}}+\frac{1}{z_{2}}+\frac{1}{z_{3}}+\dots+\frac{1}{z_{n}}\right|=|z_{1}+z_{2}+z_{3}+\dots+z_{n}|$.

---
### Example 7:
If $\frac{a+ib}{c+id}=x+iy$, prove that
1.  $\frac{a-ib}{c-id}=x-iy$ and
2.  $\frac{a^{2}+b^{2}}{c^{2}+d^{2}}=x^{2}+y^{2}$.

#### Solution:
1.  $\left(\frac{a+ib}{c+id}\right)=(x+iy) \Rightarrow \overline{\left(\frac{a+ib}{c+id}\right)}=\overline{(x+iy)}$
    $$
    \Rightarrow \frac{\overline{(a+ib)}}{\overline{(c+id)}}=(x-iy) \Rightarrow \frac{(a-ib)}{(c-id)}=(x-iy)
    $$
2.  We have $\frac{(a+ib)}{(c+id)}=(x+iy)$ and $\frac{(a-ib)}{(c-id)}=(x-iy)$.
    $$
    \begin{aligned}
    & \Rightarrow \frac{(a+ib)}{(c+id)} \times \frac{(a-ib)}{(c-id)}=(x+iy)(x-iy) \\
    & \Rightarrow \frac{(a+ib)(a-ib)}{(c+id)(c-id)}=(x+iy)(x-iy) \\
    & \Rightarrow \frac{(a^{2}+b^{2})}{(c^{2}+d^{2})}=(x^{2}+y^{2})
    \end{aligned}
    $$

---
### Example 8:
If $(x+iy)=\sqrt{\frac{a+ib}{c+id}}$, prove that $(x^{2}+y^{2})^{2}=\frac{a^{2}+b^{2}}{c^{2}+d^{2}}$.

#### Solution:
We have
$$
\begin{aligned}
& (x+iy)=\sqrt{\frac{a+ib}{c+id}}=\frac{\sqrt{a+ib}}{\sqrt{c+id}} \\
\Rightarrow & (x-iy)=\frac{\sqrt{a-ib}}{\sqrt{c-id}} \\
\Rightarrow & (x+iy)(x-iy) = \frac{\sqrt{a+ib}}{\sqrt{c+id}} \times \frac{\sqrt{a-ib}}{\sqrt{c-id}} = \frac{\sqrt{(a+ib)(a-ib)}}{\sqrt{(c+id)(c-id)}} \\
\Rightarrow & (x^{2}+y^{2}) = \frac{\sqrt{a^{2}+b^{2}}}{\sqrt{c^{2}+d^{2}}} \Rightarrow (x^{2}+y^{2})^{2}=\frac{(a^{2}+b^{2})}{(c^{2}+d^{2})}
\end{aligned}
$$
Hence, $(x^{2}+y^{2})^{2}=\frac{(a^{2}+b^{2})}{(c^{2}+d^{2})}$.

---
### Example 9:
If $(1+i)(1+2i)(1+3i)\dots(1+ni)=(x+iy)$ then prove that
$$
2 \times 5 \times 10 \times \dots \times (1+n^{2})=(x^{2}+y^{2})
$$

#### Solution:
$(1+i)(1+2i)(1+3i)\dots(1+ni)=(x+iy)$
$$
\begin{aligned}
& \Rightarrow |(1+i)(1+2i)(1+3i)\dots(1+ni)|^{2}=|x+iy|^{2} \\
& \Rightarrow |1+i|^{2} \times |1+2i|^{2} \times |1+3i|^{2} \times \dots \times |1+ni|^{2}=(x^{2}+y^{2}) \\
& \Rightarrow (\sqrt{2})^{2} \times (\sqrt{5})^{2} \times (\sqrt{10})^{2} \times \dots \times (\sqrt{1+n^{2}})^{2}=(x^{2}+y^{2}) \\
& \Rightarrow 2 \times 5 \times 10 \times \dots \times (1+n^{2})=(x^{2}+y^{2})
\end{aligned}
$$
Hence, $2 \times 5 \times 10 \times \dots \times (1+n^{2})=(x^{2}+y^{2})$.

---
### Example 10:
If $(a+ib)(c+id)(e+if)(g+ih)=(A+iB)$ then show that
$$
(a^{2}+b^{2})(c^{2}+d^{2})(e^{2}+f^{2})(g^{2}+h^{2})=(A^{2}+B^{2})
$$

#### Solution:
$(a+ib)(c+id)(e+if)(g+ih)=(A+iB)$
$$
\begin{aligned}
& \Rightarrow |(a+ib)(c+id)(e+if)(g+ih)|=|A+iB| \\
& \Rightarrow |a+ib|\cdot|c+id|\cdot|e+if|\cdot|g+ih|=|A+iB| \\
& \Rightarrow |a+ib|^{2}\cdot|c+id|^{2}\cdot|e+if|^{2}\cdot|g+ih|^{2}=|A+iB|^{2} \\
& \Rightarrow (a^{2}+b^{2})(c^{2}+d^{2})(e^{2}+f^{2})(g^{2}+h^{2})=(A^{2}+B^{2})
\end{aligned}
$$
Hence, $(a^{2}+b^{2})(c^{2}+d^{2})(e^{2}+f^{2})(g^{2}+h^{2})=(A^{2}+B^{2})$.

---
### Example 11:
If $\alpha$ and $\beta$ are different complex numbers such that $|\beta|=1$, show that
$$
\left|\frac{\beta-\alpha}{1-\bar{\alpha}\beta}\right|=1
$$

#### Solution:
We have
$$
\begin{aligned}
\left|\frac{\beta-\alpha}{1-\bar{\alpha}\beta}\right|^{2} &= \left\{\frac{\beta-\alpha}{1-\bar{\alpha}\beta}\right\} \overline{\left\{\frac{\beta-\alpha}{1-\bar{\alpha}\beta}\right\}} \quad [\because|z|^{2}=z\bar{z}] \\
&= \frac{(\beta-\alpha)}{(1-\bar{\alpha}\beta)} \cdot \frac{(\bar{\beta}-\bar{\alpha})}{(1-\alpha\bar{\beta})} = \frac{(\beta-\alpha)(\bar{\beta}-\bar{\alpha})}{(1-\bar{\alpha}\beta)(1-\alpha\bar{\beta})} \\
&= \frac{\beta\bar{\beta}+\alpha\bar{\alpha}-\beta\bar{\alpha}-\alpha\bar{\beta}}{1-\alpha\bar{\beta}-\bar{\alpha}\beta+(\alpha\bar{\alpha})(\beta\bar{\beta})} \\
&= \frac{|\beta|^{2}+|\alpha|^{2}-(\alpha\bar{\beta}+\beta\bar{\alpha})}{1-(\alpha\bar{\beta}+\beta\bar{\alpha})+|\alpha|^{2}|\beta|^{2}} \quad [\because \alpha\bar{\alpha}=|\alpha|^{2}, \beta\bar{\beta}=|\beta|^{2}] \\
&= \frac{1+|\alpha|^{2}-(\alpha\bar{\beta}+\beta\bar{\alpha})}{1+|\alpha|^{2}-(\alpha\bar{\beta}+\beta\bar{\alpha})} = 1 \quad [\because|\beta|=1]
\end{aligned}
$$
Hence, $\left|\frac{\beta-\alpha}{1-\bar{\alpha}\beta}\right|=1$.

---
### Example 12:
If $|z^{2}-1|=|z|^{2}+1$ then show that $z$ is imaginary.

#### Solution:
Let $z=(x+iy)$. Then, $z^{2}=(x^{2}-y^{2})+2ixy$ and $|z|^{2}=(x^{2}+y^{2})$.
Now, $|z^{2}-1|=|z|^{2}+1$
$$
\begin{aligned}
& \Rightarrow |(x^{2}-y^{2}-1)+i(2xy)|=(x^{2}+y^{2}+1) \\
& \Rightarrow |(x^{2}-y^{2}-1)+i(2xy)|^{2}=(x^{2}+y^{2}+1)^{2} \\
& \Rightarrow (x^{2}-y^{2}-1)^{2}+4x^{2}y^{2}=(x^{2}+y^{2}+1)^{2} \\
& \Rightarrow [x^{2}+(y^{2}+1)]^{2}-[x^{2}-(y^{2}+1)]^{2}=4x^{2}y^{2} \\
& \Rightarrow 4x^{2}(y^{2}+1)=4x^{2}y^{2} \Rightarrow 4x^{2}\{(y^{2}+1)-y^{2}\}=0 \\
& \Rightarrow 4x^{2}=0 \Rightarrow x=0
\end{aligned}
$$
Hence, $z=0+iy$, which shows that $z$ is **imaginary**.

---
### Example 13:
If $iz^{3}+z^{2}-z+i=0$ then show that $|z|=1$.

#### Solution:
We have
$$
\begin{aligned}
& iz^{3}+z^{2}-z+i=0 \\
\Rightarrow & z^{3}-iz^{2}+iz+1=0 \\
\Rightarrow & z^{2}(z-i)+i(z-i)=0 \\
\Rightarrow & (z-i)(z^{2}+i)=0 \\
\Rightarrow & z=i \text{ or } z^{2}=-i.
\end{aligned}
$$
Now, $z=i \Rightarrow |z|=|i| \Rightarrow |z|=1$.
And, $z^{2}=-i \Rightarrow |z^{2}|=|-i|=1 \Rightarrow |z|^{2}=1 \Rightarrow |z|=1$.
Hence, in either case, we have $|z|=1$.

---
### Example 14:
Find all nonzero complex numbers $z$ satisfying $\bar{z}=iz^{2}$.

#### Solution:
Let $z=x+iy$. Then, $\bar{z}=x-iy$ and $z^{2}=(x^{2}-y^{2})+2ixy$.
$$
\begin{aligned}
\therefore \quad \bar{z}=iz^{2} &\Rightarrow x-iy=i(x^{2}-y^{2})-2xy \\
& \Rightarrow (x+2xy)-i(x^{2}-y^{2}+y)=0 \quad \text{(i)}
\end{aligned}
$$
On equating real parts and imaginary parts on both sides of (i) separately, we get
$$
x+2xy=0 \quad \text{(ii)} \quad \text{and} \quad x^{2}-y^{2}+y=0 \quad \text{(iii)}
$$
From (ii), we get
$$
x+2xy=0 \Rightarrow x(1+2y)=0 \Rightarrow x=0 \text{ or } 1+2y=0 \Rightarrow x=0 \text{ or } y=\frac{-1}{2}
$$
**Case I:** When $x=0$.
Putting $x=0$ in (iii), we get
$$
-y^{2}+y=0 \Rightarrow -y(y-1)=0 \Rightarrow y=0 \text{ or } y=1
$$
Thus, $(x=0, y=0)$ or $(x=0, y=1)$.
$\therefore z=(0+i0)$ or $z=(0+1 \cdot i)$.

**Case II:** When $y=\frac{-1}{2}$.
Putting $y=\frac{-1}{2}$ in (iii), we get
$$
\begin{aligned}
& x^{2}-\left(\frac{-1}{2}\right)^{2}+\left(\frac{-1}{2}\right)=0 \Rightarrow x^{2}-\frac{1}{4}-\frac{1}{2}=0 \\
\Rightarrow & x^{2}=\left(\frac{1}{4}+\frac{1}{2}\right)=\frac{3}{4} \Rightarrow x=\pm\frac{\sqrt{3}}{2}
\end{aligned}
$$
$\therefore (x=\frac{\sqrt{3}}{2}, y=\frac{-1}{2})$ or $(x=\frac{-\sqrt{3}}{2}, y=\frac{-1}{2})$.
$\therefore z=(\frac{\sqrt{3}}{2}-\frac{1}{2}i)$ or $z=(\frac{-\sqrt{3}}{2}-\frac{1}{2}i)$.

Hence, the required **nonzero** complex numbers are $i, (\frac{\sqrt{3}}{2}-\frac{1}{2}i)$ and $(\frac{-\sqrt{3}}{2}-\frac{1}{2}i)$.

---
### Example 15:
Solve the equation, $z^{2}=\bar{z}$, where $z$ is a complex number.

#### Solution:
Let $z=x+iy$. Then,
$$
\begin{aligned}
z^{2}=\bar{z} & \Rightarrow (x+iy)^{2}=x-iy \\
& \Rightarrow (x^{2}-y^{2})+2ixy=x-iy \quad \text{(i)}
\end{aligned}
$$
Equating real parts and imaginary parts on both sides of (i) separately, we get
$$
x^{2}-y^{2}=x \quad \text{(ii)} \quad \text{and} \quad 2xy=-y \quad \text{(iii)}
$$
From (iii), we get
$$
2xy+y=0 \Rightarrow y(2x+1)=0 \Rightarrow y=0 \text{ or } x=\frac{-1}{2}
$$
**Case I:** When $y=0$.
Putting $y=0$ in (ii), we get
$$
x^{2}-x=0 \Rightarrow x(x-1)=0 \Rightarrow x=0 \text{ or } x=1
$$
$\therefore (x=0, y=0)$ or $(x=1, y=0)$.
Thus, $z=(0+i0)$ or $z=(1+i0)$.

**Case II:** When $x=\frac{-1}{2}$.
Putting $x=\frac{-1}{2}$ in (ii), we get
$$
\left(\frac{-1}{2}\right)^{2}-y^{2}=\left(\frac{-1}{2}\right) \Rightarrow y^{2}=\left(\frac{1}{4}+\frac{1}{2}\right)=\frac{3}{4} \Rightarrow y=\pm\frac{\sqrt{3}}{2}
$$
$\therefore (x=\frac{-1}{2}, y=\frac{\sqrt{3}}{2})$ or $(x=\frac{-1}{2}, y=\frac{-\sqrt{3}}{2})$.
Thus, $z=(\frac{-1}{2}+\frac{\sqrt{3}}{2}i)$ or $z=(\frac{-1}{2}-\frac{\sqrt{3}}{2}i)$.

Hence, $z=0, 1, (\frac{-1}{2}+\frac{\sqrt{3}}{2}i)$ and $(\frac{-1}{2}-\frac{\sqrt{3}}{2}i)$ are the required roots of the given equation.

---
### Example 16:
For all complex numbers $z_{1}$ and $z_{2}$, prove that
$$
|z_{1}+z_{2}|^{2}+|z_{1}-z_{2}|^{2}=2(|z_{1}|^{2}+|z_{2}|^{2})
$$

#### Solution:
We have
$$
\begin{aligned}
|z_{1}+z_{2}|^{2} &= (z_{1}+z_{2})(\overline{z_{1}+z_{2}}) \\
&= (z_{1}+z_{2})(\bar{z}_{1}+\bar{z}_{2}) \\
&= z_{1}\bar{z}_{1}+z_{2}\bar{z}_{2}+z_{1}\bar{z}_{2}+z_{2}\bar{z}_{1} \\
&= |z_{1}|^{2}+|z_{2}|^{2}+z_{1}\bar{z}_{2}+z_{2}\bar{z}_{1} \quad \text{(i)}
\end{aligned}
$$
$$
\begin{aligned}
|z_{1}-z_{2}|^{2} &= (z_{1}-z_{2})(\overline{z_{1}-z_{2}}) = (z_{1}-z_{2})(\bar{z}_{1}-\bar{z}_{2}) \\
&= z_{1}\bar{z}_{1}+z_{2}\bar{z}_{2}-z_{1}\bar{z}_{2}-z_{2}\bar{z}_{1} \\
&= |z_{1}|^{2}+|z_{2}|^{2}-z_{1}\bar{z}_{2}-z_{2}\bar{z}_{1} \quad \text{(ii)}
\end{aligned}
$$
On adding the corresponding sides of (i) and (ii), we get
$$
|z_{1}+z_{2}|^{2}+|z_{1}-z_{2}|^{2}=2(|z_{1}|^{2}+|z_{2}|^{2})
$$
---
\\
\Rightarrow x &= a^{3}-3ab^{2} \text{ and } y=3a^{2}b-b^{3} \\
\Rightarrow \left(\frac{x}{a}+\frac{y}{b}\right) &= (a^{2}-3b^{2})+(3a^{2}-b^{2})=4(a^{2}-b^{2})
\end{aligned}
$$

**5.** $(1-2i)^{-3}=\frac{1}{(1-2i)^{3}}=\frac{1}{\{1-8i^{3}-6i(1-2i)\}}$
$$
= \frac{1}{(-11+2i)} \times \frac{(-11-2i)}{(-11-2i)} = \frac{(-11-2i)}{125}
$$

**6.** $(x^{4}-3x^{2})+i(2x-y)=4+(2y-5)i$
$$
\begin{aligned}
& \Rightarrow (x^{4}-3x^{2}-4)+i(2x-y-2y+5)=0 \\
& \Rightarrow x^{4}-3x^{2}-4=0 \text{ and } 2x-3y+5=0
\end{aligned}
$$
Now, $x^{4}-3x^{2}-4=0 \Rightarrow (x^{2}-4)(x^{2}+1)=0 \Rightarrow x=2$ or $x=-2$.
$(x=2 \Rightarrow y=3)$ and $(x=-2 \Rightarrow y=\frac{1}{3})$.

**7.** Let $z=(x+iy)$. Then,
$$
z^{2}+|z|^{2}=0 \Rightarrow x^{2}-y^{2}+2ixy+x^{2}+y^{2}=0 \Rightarrow 2x^{2}+2ixy=0
$$
Equating the real and imaginary parts to zero: $2x^2=0 \Rightarrow x=0$.
$\therefore z$ is **purely imaginary**.

**8.** Let $z=(x+iy)$. Then,
$$
\frac{z-1}{z+1}=\frac{(x+iy)-1}{(x+iy)+1}=\frac{(x-1)+iy}{(x+1)+iy} \times \frac{(x+1)-iy}{(x+1)-iy}=\frac{(x^{2}+y^{2}-1)+2iy}{(x+1)^{2}+y^{2}}
$$
$\frac{z-1}{z+1}$ is **purely imaginary** $\Leftrightarrow x^{2}+y^{2}-1=0 \Leftrightarrow x^{2}+y^{2}=1 \Leftrightarrow |z|=1$.

**9.** Let $z_{1}=x_{1}+iy_{1}$. Then, $|z_{1}|=1 \Rightarrow |z_{1}|^{2}=1 \Rightarrow x_{1}^{2}+y_{1}^{2}=1$.
$$
\begin{aligned}
z_{2} &= \frac{z_{1}-1}{z_{1}+1} = \frac{(x_{1}+iy_{1})-1}{(x_{1}+iy_{1})+1} = \frac{(x_{1}-1)+iy_{1}}{(x_{1}+1)+iy_{1}} \times \frac{(x_{1}+1)-iy_{1}}{(x_{1}+1)-iy_{1}} \\
&= \frac{(x_{1}^{2}+y_{1}^{2}-1)+2iy_{1}}{(x_{1}+1)^{2}+y_{1}^{2}} = \frac{2iy_{1}}{(x_{1}+1)^{2}+y_{1}^{2}}, \text{ which is purely imaginary.} \quad [\because |z_{1}|^{2}=1]
\end{aligned}
$$

**12.** We have
$$
\begin{aligned}
\frac{1-ix}{1+ix}=\frac{a-ib}{1} &\Rightarrow \frac{(1-ix)+(1+ix)}{(1-ix)-(1+ix)}=\frac{(a-ib)+1}{(a-ib)-1} \quad \text{[by componendo and dividendo]} \\
&\Rightarrow \frac{2}{-2ix}=\frac{(a+1)-ib}{(a-1)-ib} \Rightarrow \frac{i}{x}=\frac{(a+1)-ib}{(a-1)-ib} \times \frac{(a-1)+ib}{(a-1)+ib} \\
&\Rightarrow \frac{i}{x}=\frac{(a^{2}-1+b^{2})+\{(a+1)b-(a-1)b\}i}{(a-1)^{2}+b^{2}} \\
&\Rightarrow \frac{i}{x}=\frac{(a^{2}+b^{2}-1)+2bi}{(a-1)^{2}+b^{2}} \quad [\because a^{2}+b^{2}=1] \\
&\Rightarrow \frac{i}{x}=\frac{2bi}{(a-1)^{2}+b^{2}} \\
&\Rightarrow x=\frac{(a-1)^{2}+b^{2}}{2b}, \text{ which is purely real.}
\end{aligned}
$$