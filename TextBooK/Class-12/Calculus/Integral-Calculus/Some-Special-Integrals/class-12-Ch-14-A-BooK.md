## 14. Some Special Integrals

### Three Special Integrals

**THEOREM**

1.  $\int \frac{d x}{\left(a^{2}-x^{2}\right)}=\frac{1}{2 a} \log \left|\frac{a+x}{a-x}\right|+C$.
2.  $\int \frac{d x}{\left(x^{2}-a^{2}\right)}=\frac{1}{2 a} \log \left|\frac{x-a}{x+a}\right|+C$.
3.  $\int \frac{d x}{\left(x^{2}+a^{2}\right)}=\frac{1}{a} \tan ^{-1} \frac{x}{a}+C$.

**PROOF**

**(i)** $\int \frac{d x}{\left(a^{2}-x^{2}\right)}=\int \frac{d x}{(a+x)(a-x)}$

$$
\begin{aligned}
& \quad=\int \frac{1}{2 a} \cdot\left\{\frac{(a-x)+(a+x)}{(a+x)(a-x)}\right\} d x=\frac{1}{2 a} \cdot\left[\int \frac{d x}{(a+x)}+\int \frac{d x}{(a-x)}\right] \\
& \quad=\frac{1}{2 a} \cdot[\log |a+x|-\log |a-x|]+C \\
& \quad=\frac{1}{2 a} \cdot \log \left|\frac{a+x}{a-x}\right|+C .
\end{aligned}
$$

$$
\therefore \quad \int \frac{d x}{\left(a^{2}-x^{2}\right)} =\frac{1}{2 a} \cdot \log \left|\frac{a+x}{a-x}\right|+C .
$$

**(ii)** $\int \frac{d x}{\left(x^{2}-a^{2}\right)} =\int \frac{d x}{(x-a)(x+a)}$

$$
\begin{aligned}
& =\int \frac{1}{2 a} \cdot\left\{\frac{(x+a)-(x-a)}{(x-a)(x+a)}\right\} d x=\frac{1}{2 a} \cdot\left[\int \frac{d x}{(x-a)}-\int \frac{d x}{(x+a)}\right] \\
& =\frac{1}{2 a} \cdot[\log |x-a|-\log |x+a|]+C=\frac{1}{2 a} \cdot \log \left|\frac{x-a}{x+a}\right|+C .
\end{aligned}
$$

$$
\therefore \quad \int \frac{d x}{\left(x^{2}-a^{2}\right)} =\frac{1}{2 a} \cdot \log \left|\frac{x-a}{x+a}\right|+C .
$$

**(iii)** $\int \frac{d x}{\left(x^{2}+a^{2}\right)} =\frac{1}{a^{2}} \cdot \int \frac{d x}{\left(1+\frac{x^{2}}{a^{2}}\right)}$

$$
\begin{aligned}
& =\frac{1}{a^{2}} \cdot \int \frac{a d t}{\left(1+t^{2}\right)} \quad\left[\text { putting } \frac{x}{a}=t \text { and } d x=a d t\right] \\
& =\frac{1}{a} \tan ^{-1} t+C=\frac{1}{a} \tan ^{-1} \frac{x}{a}+C .
\end{aligned}
$$

$$
\therefore \quad \int \frac{d x}{\left(x^{2}+a^{2}\right)}=\frac{1}{a} \tan ^{-1} \frac{x}{a}+C .
$$

**REMARK**
If we have an integral of the form $\int \frac{d x}{\left(a x^{2}+b x+c\right)}$ then we put the denominator in the form $\left[(x+\alpha)^{2} \pm \beta^{2}\right]$ and then integrate.

---

## Solved Examples

### Example 1

Evaluate:

1.  $\int \frac{d x}{\left(1-4 x^{2}\right)}$
2.  $\int \frac{d x}{\left(32-2 x^{2}\right)}$
3.  $\int \frac{x^{2}}{\left(1-x^{6}\right)} d x$

#### Solution:

We have

**(i)**
$$
\begin{aligned}
\int \frac{d x}{\left(1-4 x^{2}\right)} & =\frac{1}{4} \cdot \int \frac{d x}{\left(\frac{1}{4}-x^{2}\right)} \\
& =\frac{1}{4} \cdot \int \frac{d x}{\left\{\left(\frac{1}{2}\right)^{2}-x^{2}\right\}} \\
& =\frac{1}{4} \cdot \frac{1}{\left(2 \times \frac{1}{2}\right)} \cdot \log \left|\frac{\frac{1}{2}+x}{\frac{1}{2}-x}\right|+C \\
& \quad\left[\because \int \frac{d x}{\left(a^{2}-x^{2}\right)}=\frac{1}{2 a} \log \left|\frac{a+x}{a-x}\right|+C\right] \\
& =\frac{1}{4} \log \left|\frac{1+2 x}{1-2 x}\right|+C .
\end{aligned}
$$

**(ii)**
$$
\begin{aligned}
\int \frac{d x}{\left(32-2 x^{2}\right)} &=\frac{1}{2} \cdot \int \frac{d x}{\left(16-x^{2}\right)} \\
& =\frac{1}{2} \cdot \int \frac{d x}{\left\{(4)^{2}-x^{2}\right\}} \\
& =\frac{1}{2} \cdot \frac{1}{(2 \times 4)} \log \left|\frac{4+x}{4-x}\right|+C \\
& \quad\left[\because \int \frac{d x}{\left(a^{2}-x^{2}\right)}=\frac{1}{2 a} \log \left|\frac{a+x}{a-x}\right|+C\right] \\
& =\frac{1}{16} \log \left|\frac{4+x}{4-x}\right|+C .
\end{aligned}
$$

**(iii)** Putting $x^{3}=t$ and $3 x^{2} d x=d t$, we get

$$
\int \frac{x^{2}}{\left(1-x^{6}\right)} d x=\frac{1}{3} \cdot \int \frac{1}{\left(1-t^{2}\right)} d t
$$

$$
\begin{aligned}
& =\frac{1}{3} \cdot \frac{1}{(2 \times 1)} \cdot \log \left|\frac{1+t}{1-t}\right|+C \\
& \quad\left[\because \int \frac{d x}{\left(a^{2}-x^{2}\right)}=\frac{1}{2 a} \log \left|\frac{a+x}{a-x}\right|+C\right] \\
& =\frac{1}{6} \log \left|\frac{1+x^{3}}{1-x^{3}}\right|+C .
\end{aligned}
$$

---

### Example 2

Evaluate:

1.  $\int \frac{\sin x}{\left(1-4 \cos ^{2} x\right)} d x$
2.  $\int \frac{\operatorname{cosec}^{2} x}{\left(1-\cot ^{2} x\right)} d x$

#### Solution:

**(i)** Putting $\cos x=t$ and $-\sin x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\sin x}{\left(1-4 \cos ^{2} x\right)} d x & =-\int \frac{d t}{\left(1-4 t^{2}\right)} \\
& =-\frac{1}{4} \cdot \int \frac{d t}{\left(\frac{1}{4}-t^{2}\right)}=-\frac{1}{4} \cdot \int \frac{d t}{\left\{\left(\frac{1}{2}\right)^{2}-t^{2}\right\}} \\
& =-\frac{1}{4} \times \frac{1}{\left(2 \times \frac{1}{2}\right)} \log \left|\frac{\frac{1}{2}+t}{\frac{1}{2}-t}\right|+C \\
& =-\frac{1}{4} \log \left|\frac{1+2 t}{1-2 t}\right|+C=-\frac{1}{4} \log \left|\frac{1+2 \cos x}{1-2 \cos x}\right|+C
\end{aligned}
$$

**(ii)** Putting $\cot x=t$ and $-\operatorname{cosec}^{2} x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\operatorname{cosec}^{2} x}{\left(1-\cot ^{2} x\right)} d x & =-\int \frac{d t}{\left(1-t^{2}\right)}=-\frac{1}{(2 \times 1)} \log \left|\frac{1+t}{1-t}\right|+C \\
& =-\frac{1}{2} \log \left|\frac{1+\cot x}{1-\cot x}\right|+C
\end{aligned}
$$

---

### Example 3

Evaluate:

1.  $\int \frac{d x}{\left(9 x^{2}-1\right)}$
2.  $\int \frac{x}{\left(x^{4}-9\right)} d x$
3.  $\int \frac{x^{2}}{\left(x^{2}-9\right)} d x$

#### Solution:

We have

**(i)**
$$
\begin{aligned}
\int \frac{d x}{\left(9 x^{2}-1\right)} & =\frac{1}{9} \cdot \int \frac{d x}{\left(x^{2}-\frac{1}{9}\right)} \\
& =\frac{1}{9} \cdot \int \frac{d x}{\left\{x^{2}-\left(\frac{1}{3}\right)^{2}\right\}}
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{9} \cdot \frac{1}{\left(2 \times \frac{1}{3}\right)} \log \left|\frac{x-\frac{1}{3}}{x+\frac{1}{3}}\right|+C \\
& \quad\left[\because \int \frac{d x}{\left(x^{2}-a^{2}\right)}=\frac{1}{2 a} \log \left|\frac{x-a}{x+a}\right|+C\right] \\
& =\frac{1}{6} \log \left|\frac{3 x-1}{3 x+1}\right|+C
\end{aligned}
$$

**(ii)** Putting $x^{2}=t$ and $2 x d x=d t$, we get

$$
\begin{aligned}
\int \frac{x}{\left(x^{4}-9\right)} d x & =\frac{1}{2} \int \frac{d t}{\left(t^{2}-9\right)}=\frac{1}{2} \cdot \int \frac{d t}{\left\{t^{2}-(3)^{2}\right\}} \\
& =\frac{1}{2} \cdot \frac{1}{(2 \times 3)} \log \left|\frac{t-3}{t+3}\right|+C \\
& =\frac{1}{12} \log \left|\frac{x^{2}-3}{x^{2}+3}\right|+C
\end{aligned}
$$

**(iii)**
$$
\begin{aligned}
\int \frac{x^{2}}{\left(x^{2}-9\right)} d x & =\int\left\{1+\frac{9}{x^{2}-9}\right\} d x \\
& =\int d x+9 \int \frac{d x}{\left\{x^{2}-(3)^{2}\right\}} \\
& =x+9 \cdot\left[\frac{1}{(2 \times 3)} \log \left|\frac{x-3}{x+3}\right|\right]+C \\
& =x+\frac{3}{2} \log \left|\frac{x-3}{x+3}\right|+C
\end{aligned}
$$

---

### Example 4

Evaluate $\int \frac{d x}{\left(4+25 x^{2}\right)}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\left(4+25 x^{2}\right)} & =\frac{1}{25} \cdot \int \frac{d x}{\left(\frac{4}{25}+x^{2}\right)} \\
& =\frac{1}{25} \cdot \int \frac{d x}{\left\{(2 / 5)^{2}+x^{2}\right\}} \\
& =\frac{1}{25} \cdot \frac{1}{(2 / 5)} \tan ^{-1} \frac{x}{(2 / 5)}+C\left[\because \int \frac{d x}{\left(a^{2}+x^{2}\right)}=\frac{1}{a} \tan ^{-1} \frac{x}{a}+C\right] \\
& =\frac{1}{10} \tan ^{-1}\left(\frac{5 x}{2}\right)+C
\end{aligned}
$$

---

### Example 5

Evaluate $\int \frac{3 x}{\left(1+2 x^{4}\right)} d x$.

#### Solution:

Putting $x^{2}=t$ and $2 x d x=d t$, we get

$$
\begin{aligned}
\int \frac{3 x}{\left(1+2 x^{4}\right)} d x & =\frac{3}{2} \cdot \int \frac{d t}{\left(1+2 t^{2}\right)} \\
& =\frac{3}{4} \cdot \int \frac{d t}{\left(\frac{1}{2}+t^{2}\right)}=\frac{3}{4} \cdot \int \frac{d t}{\left\{\left(\frac{1}{\sqrt{2}}\right)^{2}+t^{2}\right\}} \\
& =\frac{3}{4} \cdot \frac{1}{(1 / \sqrt{2})} \tan ^{-1} \frac{t}{(1 / \sqrt{2})}+C \\
& =\frac{3}{2 \sqrt{2}} \tan ^{-1}(\sqrt{2} t)+C=\frac{3}{2 \sqrt{2}} \tan ^{-1}\left(\sqrt{2} x^{2}\right)+C
\end{aligned}
$$

---

### Example 6

Evaluate $\int \frac{d x}{\left(1+5 \sin ^{2} x\right)}$.

#### Solution:

On dividing num. and denom. by $\cos ^{2} x$, we get

$$
\begin{aligned}
\int \frac{d x}{\left(1+5 \sin ^{2} x\right)} & =\int \frac{\left(1 / \cos ^{2} x\right)}{\left(\frac{1}{\cos ^{2} x}+5 \cdot \frac{\sin ^{2} x}{\cos ^{2} x}\right)} d x \\
& =\int \frac{\sec ^{2} x}{\left(\sec ^{2} x+5 \tan ^{2} x\right)} d x=\int \frac{\sec ^{2} x}{\left\{\left(1+\tan ^{2} x\right)+5 \tan ^{2} x\right\}} d x \\
& =\int \frac{\sec ^{2} x}{\left(1+6 \tan ^{2} x\right)} d x=\int \frac{d t}{\left(1+6 t^{2}\right)}, \text { where } \tan x=t \\
& =\frac{1}{6} \int \frac{d t}{\left(\frac{1}{6}+t^{2}\right)}=\frac{1}{6} \cdot \int \frac{d t}{\left\{\left(\frac{1}{\sqrt{6}}\right)^{2}+t^{2}\right\}} \\
& =\frac{1}{6} \cdot \frac{1}{(1 / \sqrt{6})} \tan ^{-1} \frac{t}{(1 / \sqrt{6})}+C=\frac{1}{\sqrt{6}} \tan ^{-1}(\sqrt{6} t)+C \\
& =\frac{1}{\sqrt{6}} \tan ^{-1}(\sqrt{6} \tan x)+C
\end{aligned}
$$

---

### Example 7

Evaluate $\int \frac{d x}{\left(2+\sin ^{2} x\right)}$.

#### Solution:

On dividing num. and denom. by $\cos ^{2} x$, we get

$$
\begin{aligned}
\int \frac{d x}{\left(2+\sin ^{2} x\right)} & =\int \frac{\sec ^{2} x}{\left(2 \sec ^{2} x+\tan ^{2} x\right)} d x=\int \frac{\sec ^{2} x}{\left\{2\left(1+\tan ^{2} x\right)+\tan ^{2} x\right\}} d x \\
& =\int \frac{\sec ^{2} x}{2+3 \tan ^{2} x} d x=\int \frac{d t}{\left(2+3 t^{2}\right)}, \text { where tan } x=t \\
& =\frac{1}{3} \cdot \int \frac{d t}{\left(t^{2}+\frac{2}{3}\right)}=\frac{1}{3} \cdot \int \frac{d t}{\left(\sqrt{\frac{2}{3}}\right)^{2}+t^{2}}
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{3} \cdot \frac{1}{\sqrt{\frac{2}{3}}} \cdot \tan ^{-1} \frac{t}{\left(\sqrt{\frac{2}{3}}\right)}+C=\frac{1}{\sqrt{6}} \tan ^{-1} \frac{\sqrt{3} t}{\sqrt{2}}+C \\
& =\frac{1}{\sqrt{6}} \tan ^{-1}\left(\frac{\sqrt{3} \tan x}{\sqrt{2}}\right)+C .
\end{aligned}
$$

---

### Example 8

Evaluate $\int \frac{d x}{\left(x^{2}+6 x+13\right)}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\left(x^{2}+6 x+13\right)} & =\int \frac{d x}{\left\{\left(x^{2}+6 x+9\right)+4\right\}} \\
& =\int \frac{d x}{\left\{(x+3)^{2}+2^{2}\right\}}=\int \frac{d t}{\left(t^{2}+2^{2}\right)}, \text { where }(x+3)=t \\
& =\frac{1}{2} \tan ^{-1} \frac{t}{2}+C \\
& =\frac{1}{2} \tan ^{-1} \frac{1}{2}(x+3)+C
\end{aligned}
$$

---

### Example 9 [CBSE 2002C]

Evaluate $\int \frac{d x}{\left(x^{2}+8 x+20\right)}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\left(x^{2}+8 x+20\right)} & =\int \frac{d x}{\left\{(x+4)^{2}+2^{2}\right\}}=\int \frac{d t}{\left(t^{2}+2^{2}\right)}, \text { where }(x+4)=t \\
& =\frac{1}{2} \tan ^{-1} \frac{t}{2}+C \\
& =\frac{1}{2} \tan ^{-1} \frac{1}{2}(x+4)+C
\end{aligned}
$$

---

### Example 10

Evaluate $\int \frac{d x}{\left(9 x^{2}-12 x+8\right)}$.

#### Solution:

We have

$$
\begin{aligned}
& \left(9 x^{2}-12 x+8\right)=9\left(x^{2}-\frac{4}{3} x+\frac{8}{9}\right) \\
& \quad=9\left\{\left(x^{2}-\frac{4}{3} x+\frac{4}{9}\right)-\frac{4}{9}+\frac{8}{9}\right\}=9\left\{\left(x-\frac{2}{3}\right)^{2}+\left(\frac{2}{3}\right)^{2}\right\}
\end{aligned}
$$

$$
\begin{aligned}
& \therefore \int \frac{d x}{\left(9 x^{2}-12 x+8\right)}=\frac{1}{9} \cdot \int \frac{d x}{\left\{\left(x-\frac{2}{3}\right)^{2}+\left(\frac{2}{3}\right)^{2}\right\}} \\
& \quad=\frac{1}{9} \cdot \frac{1}{\left(\frac{2}{3}\right)} \tan ^{-1}\left\{\frac{\left(x-\frac{2}{3}\right)}{\left(\frac{2}{3}\right)}\right\}+C=\frac{1}{6} \tan ^{-1}\left(\frac{3 x-2}{2}\right)+C
\end{aligned}
$$

---

### Example 11 [CBSE 2003, '07C]

Evaluate $\int \frac{x}{\left(x^{4}-x^{2}+1\right)} d x$.

#### Solution:

Putting $x^{2}=t$ and $2 x d x=d t$, we get

$$
\begin{aligned}
\int \frac{x}{\left(x^{4}-x^{2}+1\right)} d x & =\frac{1}{2} \cdot \int \frac{d t}{\left(t^{2}-t+1\right)}=\frac{1}{2} \cdot \int \frac{d t}{\left\{\left(t-\frac{1}{2}\right)^{2}+\left(\frac{\sqrt{3}}{2}\right)^{2}\right\}} \\
& =\frac{1}{2} \cdot \frac{1}{\left(\frac{\sqrt{3}}{2}\right)} \tan ^{-1} \frac{\left(t-\frac{1}{2}\right)}{\left(\frac{\sqrt{3}}{2}\right)}+C \\
& =\frac{1}{\sqrt{3}} \cdot \tan ^{-1}\left(\frac{2 t-1}{\sqrt{3}}\right)+C=\frac{1}{\sqrt{3}} \tan ^{-1}\left(\frac{2 x^{2}-1}{\sqrt{3}}\right)+C .
\end{aligned}
$$

---

### Example 12

Evaluate $\int \frac{d x}{\left(2 x^{2}+x-1\right)}$.

#### Solution:

We have

$$
\begin{aligned}
& \int \frac{d x}{\left(2 x^{2}+x-1\right)}=\frac{1}{2} \cdot \int \frac{d x}{\left(x^{2}+\frac{1}{2} x-\frac{1}{2}\right)} \\
& \quad=\frac{1}{2} \int \frac{d x}{\left[\left\{x^{2}+\frac{1}{2} x+\left(\frac{1}{4}\right)^{2}\right\}-\frac{1}{16}-\frac{1}{2}\right]}=\frac{1}{2} \int \frac{d x}{\left[\left(x+\frac{1}{4}\right)^{2}-\left(\frac{3}{4}\right)^{2}\right]} \\
& \quad=\frac{1}{2} \cdot \frac{1}{2 \cdot \frac{3}{4}} \log \left|\frac{\left(x+\frac{1}{4}\right)-\frac{3}{4}}{\left(x+\frac{1}{4}\right)+\frac{3}{4}}\right|+C=\frac{1}{3} \log \left|\frac{2 x-1}{2(x+1)}\right|+C .
\end{aligned}
$$
---

### Example 13:

Evaluate $\int \frac{d x}{\left(3 x^{2}+13 x-10\right)}$.

#### Solution:

We have

$$
\begin{aligned}
\left(3 x^{2}+13 x-10\right) & =3\left(x^{2}+\frac{13}{3} x-\frac{10}{3}\right) \\
& =3\left\{\left(x+\frac{13}{6}\right)^{2}-\frac{169}{36}-\frac{10}{3}\right\}=3\left\{\left(x+\frac{13}{6}\right)^{2}-\frac{289}{36}\right\} \\
& =3\left\{\left(x+\frac{13}{6}\right)^{2}-\left(\frac{17}{6}\right)^{2}\right\} \\
\therefore \int \frac{d x}{\left(3 x^{2}+13 x-10\right)} & =\int \frac{d x}{3\left\{\left(x+\frac{13}{6}\right)^{2}-\left(\frac{17}{6}\right)^{2}\right\}}
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{3} \int \frac{d t}{\left\{t^{2}-\left(\frac{17}{6}\right)^{2}\right\}} \text {, where }\left(x+\frac{13}{6}\right)=t \\
& =\frac{1}{3} \cdot \frac{1}{\left(2 \times \frac{17}{6}\right)} \log \left|\frac{t-\frac{17}{6}}{t+\frac{17}{6}}\right|+C \\
& \quad\left[\because \int \frac{d x}{\left(x^{2}-a^{2}\right)}=\frac{1}{2 a} \log \left|\frac{x-a}{x+a}\right|\right] \\
& =\frac{1}{17} \log \left|\frac{6 t-17}{6 t+17}\right|+C \\
& =\frac{1}{17} \log \left|\frac{6\left(x+\frac{13}{6}\right)-17}{6\left(x+\frac{13}{6}\right)+17}\right|=\frac{1}{17} \log \left|\frac{6 x-4}{6 x+30}\right|+C \\
& =\frac{1}{17} \log \left|\frac{3 x-2}{3 x+15}\right|+C=\frac{1}{17} \log \left|\frac{(3 x-2)}{3(x+5)}\right|+C \\
& =\frac{1}{17}\left\{\log \frac{1}{3}+\log \left|\frac{3 x-2}{x+5}\right|\right\}+C \\
& =\frac{1}{17} \log \left|\frac{3 x-2}{x+5}\right|+k, \\
& \text { where } \frac{1}{17} \log \frac{1}{3}+C=k=\text { constant. }
\end{aligned}
$$

---

### Example 14:

Evaluate $\int \frac{d x}{\left(1+x-x^{2}\right)}$.

#### Solution:

We have

$$
\begin{aligned}
& \left.\int \frac{d x}{(1+x}-x^{2}\right)=-\int \frac{d x}{\left(x^{2}-x-1\right)} \\
& \quad=-\int \frac{d x}{\left\{\left(x^{2}-x+\frac{1}{4}\right)-\frac{5}{4}\right\}}=-\int \frac{d x}{\left\{\left(x-\frac{1}{2}\right)^{2}-\left(\frac{\sqrt{5}}{2}\right)^{2}\right\}} \\
& \quad=\int \frac{d x}{\left\{\left(\frac{\sqrt{5}}{2}\right)^{2}-\left(x-\frac{1}{2}\right)^{2}\right\}}=\int \frac{d x}{\left\{\left(\frac{\sqrt{5}}{2}\right)^{2}-u^{2}\right\}}, \text { where }\left(x-\frac{1}{2}\right)=u \\
& \quad=\frac{1}{\left(2 \times \frac{\sqrt{5}}{2}\right)} \cdot \log \left|\frac{\frac{\sqrt{5}}{2}+u}{\frac{\sqrt{5}}{2}-u}\right|+C
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{\sqrt{5}} \log \left|\frac{\sqrt{5}+2 u}{\sqrt{5}-2 u}\right|+C=\frac{1}{\sqrt{5}} \log \left|\frac{\sqrt{5}+2\left(x-\frac{1}{2}\right)}{\sqrt{5}-2\left(x-\frac{1}{2}\right)}\right|+C \\
& =\frac{1}{\sqrt{5}} \log \left|\frac{\sqrt{5}+2 x-1}{\sqrt{5}-2 x+1}\right|+C=\frac{1}{\sqrt{5}} \log \left|\frac{(\sqrt{5}-1)+2 x}{(\sqrt{5}+1)-2 x}\right|+C .
\end{aligned}
$$

---

### Example 15:

Evaluate $\int \frac{d x}{\left(5-8 x-x^{2}\right)}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\left(5-8 x-x^{2}\right)} & =-\int \frac{d x}{\left(x^{2}+8 x-5\right)} \\
& =-\int \frac{d x}{\left\{\left(x^{2}+8 x+16\right)-21\right\}}=-\int \frac{d x}{\left\{(x+4)^{2}-(\sqrt{21})^{2}\right\}} \\
& =\int \frac{d x}{\left\{(\sqrt{21})^{2}-(x+4)^{2}\right\}}=\int \frac{d t}{\left\{(\sqrt{21})^{2}-t^{2}\right\}}, \\
& =\frac{1}{2 \sqrt{21}} \cdot \log \left|\frac{\sqrt{21}+t}{\sqrt{21}-t}\right|+C \quad \text { where }(x+4)=t \\
& =\frac{1}{2 \sqrt{21}} \cdot \log \left|\frac{\sqrt{21}+4+x}{\sqrt{21}-4-x}\right|+C
\end{aligned}
$$

---

### Example 16:

Evaluate $\int \frac{d x}{\left(1-6 x-9 x^{2}\right)}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\left(1-6 x-9 x^{2}\right)} & =-\int \frac{d x}{\left(9 x^{2}+6 x-1\right)}=-\frac{1}{9} \int \frac{d x}{\left(x^{2}+\frac{2}{3} x-\frac{1}{9}\right)} \\
& =-\frac{1}{9} \cdot \int \frac{d x}{\left\{\left(x^{2}+\frac{2}{3} x+\frac{1}{9}\right)-\frac{2}{9}\right\}} \\
& =-\frac{1}{9} \cdot \int \frac{d x}{\left\{\left(x+\frac{1}{3}\right)^{2}-\left(\frac{\sqrt{2}}{3}\right)^{2}\right\}}=\frac{1}{9} \cdot \int \frac{d x}{\left\{\left(\frac{\sqrt{2}}{3}\right)^{2}-\left(x+\frac{1}{3}\right)^{2}\right\}} \\
& =\frac{1}{9} \cdot \int \frac{d x}{\left\{\left(\frac{\sqrt{2}}{3}\right)^{2}-t^{2}\right\}}, \text { where }\left(x+\frac{1}{3}\right)=t \\
& =\frac{1}{9} \cdot \frac{1}{2 \cdot \frac{\sqrt{2}}{3}} \log \left|\frac{\frac{\sqrt{2}}{3}+t}{\frac{\sqrt{2}}{3}-t}\right|+C=\frac{1}{6 \sqrt{2}} \log \left|\frac{\sqrt{2}+3 t}{\sqrt{2}-3 t}\right|+C
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{6 \sqrt{2}} \log \left|\frac{\sqrt{2}+3\left(x+\frac{1}{3}\right)}{\sqrt{2}-3\left(x+\frac{1}{3}\right)}\right|+C \\
& =\frac{1}{6 \sqrt{2}} \log \left|\frac{\sqrt{2}+1+3 x}{\sqrt{2}-1-3 x}\right|+C .
\end{aligned}
$$

---

### Example 17:

Evaluate $\int \frac{\cos x}{\left(\sin ^{2} x+4 \sin x+5\right)} d x$.

#### Solution:

Putting $\sin x=t$ and $\cos x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\cos x}{\left(\sin ^{2} x+4 \sin x+5\right)} d x & =\int \frac{d t}{\left(t^{2}+4 t+5\right)}=\int \frac{d t}{\left\{\left(t^{2}+4 t+4\right)+1\right\}} \\
& =\int \frac{d t}{\left\{(t+2)^{2}+1^{2}\right\}}=\int \frac{d u}{\left(u^{2}+1\right)} \\
& =\tan ^{-1} u+C=\tan ^{-1}(t+2)+C \\
& =\tan ^{-1}(\sin x+2)+C
\end{aligned}
$$

---

### Example 18:

Evaluate $\int \frac{e^{x}}{\left(e^{2 x}+6 e^{x}+5\right)} d x$.

#### Solution:

Putting $e^{x}=t$ and $e^{x} d x=d t$, we get

$$
\begin{aligned}
\int \frac{e^{x}}{e^{2 x}+6 e^{x}+5} d x & =\int \frac{d t}{\left(t^{2}+6 t+5\right)}=\int \frac{d t}{\left\{\left(t^{2}+6 t+9\right)-4\right\}} \\
& =\int \frac{d t}{\left\{(t+3)^{2}-2^{2}\right\}}=\int \frac{d u}{\left(u^{2}-2^{2}\right)}, \text { where }(t+3)=u \\
& =\frac{1}{(2 \times 2)} \log \left|\frac{u-2}{u+2}\right|+C=\frac{1}{4} \log \left|\frac{t+3-2}{t+3+2}\right|+C \\
& =\frac{1}{4} \log \left|\frac{t+1}{t+5}\right|+C=\frac{1}{4} \log \left|\frac{e^{x}+1}{e^{x}+5}\right|+C
\end{aligned}
$$

---

### Integrals of the form $\int \frac{(p x+q)}{\left(a x^{2}+b x+c\right)} d x$.

#### Method:

Let $(p x+q)=A \cdot \frac{d}{d x}\left(a x^{2}+b x+c\right)+B$

Find $A$ and $B$.

Now, the integrand so obtained can be integrated easily.

---

### Example 19 [CBSE 2013]:

Evaluate $\int \frac{(5 x-2)}{\left(1+2 x+3 x^{2}\right)} d x$.

#### Solution:

Let $(5 x-2)=A \cdot \frac{d}{d x}\left(1+2 x+3 x^{2}\right)+B$.

Then, $(5 x-2)=A(6 x+2)+B$.

Comparing the coefficients of like powers of $x$ on both sides, we get $6 A=5$ and $2 A+B=-2$.
This gives $A=\frac{5}{6}$ and $B=\frac{-11}{3}$.

$$
\begin{aligned}
\therefore \quad I & =\int \frac{\left\{\frac{5}{6}(6 x+2)-\frac{11}{3}\right\}}{\left(1+2 x+3 x^{2}\right)} d x \\
& =\frac{5}{6} \cdot \int \frac{6 x+2}{\left(1+2 x+3 x^{2}\right)} d x-\frac{11}{3} \int \frac{d x}{\left(3 x^{2}+2 x+1\right)} \\
& =\frac{5}{6} \log \left|1+2 x+3 x^{2}\right|-\frac{11}{3} \cdot \frac{1}{3} \int \frac{d x}{\left(x^{2}+\frac{2}{3} x+\frac{1}{3}\right)} \\
& =\frac{5}{6} \log \left|1+2 x+3 x^{2}\right|-\frac{11}{9} \cdot \int \frac{d x}{\left\{\left(x+\frac{1}{3}\right)^{2}+\left(\frac{1}{3}-\frac{1}{9}\right)\right\}} \\
& =\frac{5}{6} \log \left|1+2 x+3 x^{2}\right|-\frac{11}{9} \cdot \int \frac{d x}{\left\{\left(x+\frac{1}{3}\right)^{2}+\left(\frac{\sqrt{2}}{3}\right)^{2}\right\}}+C \\
& =\frac{5}{6} \log \left|1+2 x+3 x^{2}\right|-\frac{11}{9} \cdot \frac{1}{\left(\frac{\sqrt{2}}{3}\right) \tan ^{-1}\left\{\frac{x+\frac{1}{3}}{\left(\frac{\sqrt{2}}{3}\right)}\right\}+C} \\
& =\frac{5}{6} \log \left|1+2 x+3 x^{2}\right|-\frac{11}{3 \sqrt{2}} \tan ^{-1}\left(\frac{3 x+1}{\sqrt{2}}\right)+C .
\end{aligned}
$$

---

### Example 20 [CBSE 2006]:

Evaluate $\int \frac{(3 x+1)}{\left(2 x^{2}-2 x+3\right)} d x$.

#### Solution:

Let $(3 x+1)=A \cdot \frac{d}{d x}\left(2 x^{2}-2 x+3\right)+B$. Then,

$$
\begin{equation*}
(3 x+1)=A(4 x-2)+B \tag{i}
\end{equation*}
$$

Comparing the coefficients of like powers of $x$, we get

$$
\begin{aligned}
& (4 A=3 \text { and } B-2 A=1) \Rightarrow\left(A=\frac{3}{4} \text { and } B=\frac{5}{2}\right) \\
\therefore & \int \frac{(3 x+1)}{\left(2 x^{2}-2 x+3\right)} d x=\int \frac{A \cdot(4 x-2)+B}{\left(2 x^{2}-2 x+3\right)} \\
& =\int \frac{\frac{3}{4} \cdot(4 x-2)+\frac{5}{2}}{\left(2 x^{2}-2 x+3\right)} d x=\frac{3}{4} \cdot \int \frac{(4 x-2)}{\left(2 x^{2}-2 x+3\right)} d x+\frac{5}{2} \int \frac{d x}{2\left(x^{2}-x+\frac{3}{2}\right)}
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{3}{4} \log \left|2 x^{2}-2 x+3\right|+\frac{5}{4} \cdot \int \frac{d x}{\left\{\left(x^{2}-x+\frac{1}{4}\right)+\frac{5}{4}\right\}} \\
& =\frac{3}{4} \log \left|2 x^{2}-2 x+3\right|+\frac{5}{4} \cdot \int \frac{d x}{\left\{\left(x-\frac{1}{2}\right)^{2}+\left(\frac{\sqrt{5}}{2}\right)^{2}\right\}} \\
& =\frac{3}{4} \log \left|2 x^{2}-2 x+3\right|+\frac{5}{4} \cdot \frac{1}{\left(\frac{\sqrt{5}}{2}\right)} \tan ^{-1}\left\{\frac{\left(x-\frac{1}{2}\right)}{\left(\frac{\sqrt{5}}{2}\right)}\right\}+C \\
& =\frac{3}{4} \log \left|2 x^{2}-2 x+3\right|+\frac{\sqrt{5}}{2} \tan ^{-1}\left(\frac{2 x-1}{\sqrt{5}}\right)+C .
\end{aligned}
$$

---

### Example 21 [CBSE 2004C]:

Evaluate $\int \frac{(2 x+1)}{\left(4-3 x-x^{2}\right)} d x$.

#### Solution:

Let $(2 x+1)=A \cdot \frac{d}{d x}\left(4-3 x-x^{2}\right)+B$.
Then, $(2 x+1)=A(-3-2 x)+B$

Comparing the coefficients of like terms, we get

$$
\begin{aligned}
& \quad(-2 A=2 \text { and }-3 A+B=1) \Rightarrow(A=-1, B=-2) \\
& \therefore \int \frac{(2 x+1)}{\left(4-3 x-x^{2}\right)} d x=\int\left\{\frac{(-1) \cdot(-3-2 x)-2}{\left(4-3 x-x^{2}\right)}\right\} d x \\
& \quad=-\int \frac{(-3-2 x)}{\left(4-3 x-x^{2}\right)} d x-2 \int \frac{d x}{\left(4-3 x-x^{2}\right)} \\
& \quad=-\log \left|4-3 x-x^{2}\right|+2 \int \frac{d x}{\left(x^{2}+3 x-4\right)} \\
& \quad=-\log \left|4-3 x-x^{2}\right|+2 \int \frac{d x}{\left(x+\frac{3}{2}\right)^{2}-\left(4+\frac{9}{4}\right)} \\
& \quad=-\log \left|4-3 x-x^{2}\right|+2 \int \frac{d x}{\left\{\left(x+\frac{3}{2}\right)^{2}-\left(\frac{5}{2}\right)^{2}\right\}} \\
& \quad=-\log \left|4-3 x-x^{2}\right|+\frac{2}{\left(2 \times \frac{5}{2}\right)} \log \left|\frac{\left(x+\frac{3}{2}\right)-\frac{5}{2}}{\left(x+\frac{3}{2}\right)+\frac{5}{2}}\right|+C \\
& \quad=-\log \left|4-3 x-x^{2}\right|+\frac{2}{5} \log \left|\frac{x-1}{x+4}\right|+C .
\end{aligned}
$$

---

### Example 22:

Evaluate $\int\left(\frac{x^{2}+5 x+3}{x^{2}+3 x+2}\right) d x$.

#### Solution:

We have

$$
\begin{align*}
& \quad \frac{\left(x^{2}+5 x+3\right)}{\left(x^{2}+3 x+2\right)}=\left\{1+\frac{(2 x+1)}{x^{2}+3 x+2}\right\} \\
& \Rightarrow \int \frac{\left(x^{2}+5 x+3\right)}{\left(x^{2}+3 x+2\right)} d x=\int d x+\int \frac{(2 x+1)}{\left(x^{2}+3 x+2\right)} d x  \tag{i}\\
& \text { Let }(2 x+1)=A \cdot \frac{d}{d x}\left(x^{2}+3 x+2\right)+B . \text { Then, } \\
& \quad(2 x+1)=A(2 x+3)+B \tag{ii}
\end{align*}
$$

Comparing the coefficients of like powers of $x$, we get

$$
\begin{aligned}
& \therefore(2 A=2 \text { and } 3 A+B=1) \Rightarrow(A=1 \text { and } B=-2) \\
& \therefore(2 x+1)=(2 x+3)-2 \\
& \therefore I=x+\int \frac{(2 x+1)}{\left(x^{2}+3 x+2\right)} d x=x+\int \frac{\{(2 x+3)-2\}}{\left(x^{2}+3 x+2\right)} d x \\
& =x+\int \frac{(2 x+3)}{\left(x^{2}+3 x+2\right)} d x-2 \int \frac{d x}{\left(x^{2}+3 x+2\right)} \\
& =x+\log \left|x^{2}+3 x+2\right|-2 \int \frac{d x}{\left\{\left(x^{2}+3 x+\frac{9}{4}\right)+\left(2-\frac{9}{4}\right)\right\}} \\
& =x+\log \left|x^{2}+3 x+2\right|-2 \int \frac{d x}{\left\{\left(x+\frac{3}{2}\right)^{2}-\left(\frac{1}{2}\right)^{2}\right\}} \\
& =x+\log \left|x^{2}+3 x+2\right|-2 \cdot \frac{1}{\left(2 \times \frac{1}{2}\right)} \log \left|\frac{x+\frac{3}{2}-\frac{1}{2}}{x+\frac{3}{2}+\frac{1}{2}}\right|+C \\
& =x+\log \left|x^{2}+3 x+2\right|-2 \log \left|\frac{x+1}{x+2}\right|+C .
\end{aligned}
$$

---

### Integrals of the form $\int \frac{d x}{a+b \cos ^{2} x}, \int \frac{d x}{a+b \sin ^{2} x}$ and $\int \frac{d x}{a \cos ^{2} x+b \sin x \cos x+c \sin ^{2} x}$.

#### Method:

In each such an integral, we divide the numerator and denominator by $\cos ^{2} x$ and put $\tan x=t, \sec ^{2} x d x=d t$ and then integrate.

---

### Example 23 [CBSE 2003C]:

Evaluate $\int \frac{d x}{a^{2} \sin ^{2} x+b^{2} \cos ^{2} x}$.

#### Solution:

Dividing the numerator and the denominator of the given integrand by $\cos ^{2} x$, we get

$$
\begin{aligned}
\int \frac{d x}{\left(a^{2} \sin ^{2} x+b^{2} \cos ^{2} x\right)} & =\int \frac{\sec ^{2} x}{a^{2} \tan ^{2} x+b^{2}} d x \\
& =\int \frac{d t}{\left(a^{2} t^{2}+b^{2}\right)} \quad[\text { putting } \tan x=t] \\
& =\frac{1}{a^{2}} \int \frac{d t}{\left[t^{2}+\left(\frac{b}{a}\right)^{2}\right]}=\frac{1}{a^{2}} \cdot \frac{1}{\left(\frac{b}{a}\right)} \tan ^{-1} \frac{t}{\left(\frac{b}{a}\right)}+C \\
& =\frac{1}{a b} \tan ^{-1}\left(\frac{a t}{b}\right)+C=\frac{1}{a b} \tan ^{-1}\left(\frac{a \tan x}{b}\right)+C
\end{aligned}
$$

---

### Example 24:

Evaluate:

**(i)** $\int \frac{d x}{\left(1+3 \sin ^{2} x\right)}$
**(ii)** $\int \frac{d x}{\left(3+2 \cos ^{2} x\right)}$

#### Solution:

**(i)** Dividing the numerator and denominator by $\cos ^{2} x$, we get

$$
\begin{aligned}
\int \frac{d x}{\left(1+3 \sin ^{2} x\right)} & =\int \frac{\sec ^{2} x}{\sec ^{2} x+3 \tan ^{2} x} d x=\int \frac{\sec ^{2} x}{\left(1+4 \tan ^{2} x\right)} d x \\
& \left.=\int \frac{d t}{\left(1+4 t^{2}\right)} \text { [putting tan } x=t\right] \\
& =\frac{1}{4} \int \frac{d t}{\left[t^{2}+\left(\frac{1}{2}\right)^{2}\right]}=\frac{1}{4} \cdot \frac{1}{(1 / 2)} \tan ^{-1} \frac{t}{(1 / 2)}+C \\
& =\frac{1}{2} \tan ^{-1}(2 t)+C=\frac{1}{2} \tan ^{-1}(2 \tan x)+C
\end{aligned}
$$

**(ii)** Dividing the numerator and denominator by $\cos ^{2} x$, we get

$$
\begin{aligned}
\int \frac{d x}{\left(3+2 \cos ^{2} x\right)} & =\int \frac{\sec ^{2} x}{\left(3 \sec ^{2} x+2\right)} d x=\int \frac{\sec ^{2} x}{5+3 \tan ^{2} x} d x \\
= & \left.\int \frac{d t}{\left(5+3 t^{2}\right)} \quad \text { [putting tan } x=t\right] \\
= & \frac{1}{3} \int \frac{d t}{\left[t^{2}+\left(\frac{5}{3}\right)\right]}=\frac{1}{3} \cdot \int \frac{d t}{\left[t^{2}+\left(\frac{\sqrt{5}}{\sqrt{3}}\right)^{2}\right]} \\
= & \frac{1}{3} \cdot \frac{1}{\left(\frac{\sqrt{5}}{\sqrt{3}}\right)} \tan ^{-1} \frac{t}{\left(\frac{\sqrt{5}}{\sqrt{3}}\right)}+C=\frac{1}{\sqrt{15}} \tan ^{-1}\left(\frac{\sqrt{3} t}{\sqrt{5}}\right)+C \\
= & \frac{1}{\sqrt{15}} \tan ^{-1}\left(\frac{\sqrt{3} \tan x}{\sqrt{5}}\right)+C
\end{aligned}
$$

---

### Example 25:

Evaluate $\int \frac{d x}{\left(4 \sin ^{2} x+5 \cos ^{2} x\right)}$.

#### Solution:

On dividing the numerator and denominator by $\cos ^{2} x$, we get

$$
\begin{aligned}
\int \frac{d x}{\left(4 \sin ^{2} x+5 \cos ^{2} x\right)} & =\int \frac{\sec ^{2} x}{\left(4 \tan ^{2} x+5\right)} d x \\
& =\int \frac{d t}{4 t^{2}+5} \quad[\text { putting } \tan x=t] \\
& =\frac{1}{4} \int \frac{d t}{\left(t^{2}+\frac{5}{4}\right)}=\frac{1}{4} \cdot \int \frac{d t}{\left[t^{2}+\left(\frac{\sqrt{5}}{2}\right)^{2}\right]} \\
& =\frac{1}{4} \cdot \frac{1}{\left(\frac{\sqrt{5}}{2}\right)} \tan ^{-1} \frac{t}{\left(\frac{\sqrt{5}}{2}\right)}+C \\
& =\frac{1}{2 \sqrt{5}} \tan ^{-1}\left(\frac{2 t}{\sqrt{5}}\right)+C=\frac{1}{2 \sqrt{5}} \tan ^{-1}\left(\frac{2 \tan x}{\sqrt{5}}\right)+C
\end{aligned}
$$

---

### Example 26:

Evaluate $\int \frac{d x}{\left(1+3 \sin ^{2} x+8 \cos ^{2} x\right)}$.

#### Solution:

On dividing the numerator and denominator by $\cos ^{2} x$, we get

$$
\begin{aligned}
\int \frac{d x}{\left(1+3 \sin ^{2} x+8 \cos ^{2} x\right)} & =\int \frac{\sec ^{2} x d x}{\sec ^{2} x+3 \tan ^{2} x+8} \\
& =\int \frac{\sec ^{2} x}{9+4 \tan ^{2} x} d x=\int \frac{d t}{9+4 t^{2}} \\
& =\frac{1}{4} \int \frac{d t}{\left(t^{2}+\frac{9}{4}\right)}=\frac{1}{4} \cdot \int \frac{d t}{\left[t^{2}+\left(\frac{3}{2}\right)^{2}\right]} \\
& =\frac{1}{4} \cdot \frac{1}{(3 / 2)} \cdot \tan ^{-1}\left\{\frac{t}{(3 / 2)}\right\}+C \\
& =\frac{1}{6} \tan ^{-1}\left(\frac{2 t}{3}\right)+C=\frac{1}{6} \tan ^{-1}\left(\frac{2 \tan x}{3}\right)+C
\end{aligned}
$$

---

### Example 27:

Evaluate $\int \frac{\sin x}{\sin 3 x} d x$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{\sin x}{\sin 3 x} d x & =\int \frac{\sin x}{\left(3 \sin x-4 \sin ^{3} x\right)} d x \\
& =\int \frac{1}{\left(3-4 \sin ^{2} x\right)} d x[\text { dividing num. and denom. by } \sin x]
\end{aligned}
$$

$$
\begin{aligned}
& =\int \frac{\sec ^{2} x}{3 \sec ^{2} x-4 \tan ^{2} x} d x \quad \text { [dividing num. and denom. by } \cos ^{2} x \text { ] } \\
& =\int \frac{\sec ^{2} x}{3\left(1+\tan ^{2} x\right)-4 \tan ^{2} x} d x=\int \frac{\sec ^{2} x}{\left(3-\tan ^{2} x\right)} d x \\
& =\int \frac{d t}{\left(3-t^{2}\right)}, \text { where } \tan x=t \text { and } \sec ^{2} x d x=d t \\
& =\int \frac{d t}{\left[(\sqrt{3})^{2}-t^{2}\right]}=\frac{1}{2 \sqrt{3}} \log \left|\frac{\sqrt{3}+t}{\sqrt{3}-t}\right|+C \\
& =\frac{1}{2 \sqrt{3}} \log \left|\frac{\sqrt{3}+\tan x}{\sqrt{3}-\tan x}\right|+C
\end{aligned}
$$

---

### Example 28:

Evaluate $\int \frac{\cos x}{\cos 3 x} d x$.

#### Solution:

We have

$$
\begin{aligned}
& \int \frac{\cos x}{\cos 3 x} d x=\int \frac{\cos x}{\left(4 \cos ^{3} x-3 \cos x\right)} d x \\
& \quad=\int \frac{d x}{4 \cos ^{2} x-3}=\int \frac{d x}{4 \cos ^{2} x-3\left(\sin ^{2} x+\cos ^{2} x\right)} \\
& \quad=\int \frac{d x}{\cos ^{2} x-3 \sin ^{2} x}=\int \frac{\sec ^{2} x}{1-3 \tan ^{2} x} d x
\end{aligned}
$$

[on dividing the num. and denom. by $\cos ^{2} x$ ]

$$
=\int \frac{d t}{1-3 t^{2}}, \text { where } \tan x=t \text { and } \sec ^{2} x d x=d t
$$

$$
\begin{aligned}
& =\frac{1}{3} \cdot \int \frac{d t}{\left(\frac{1}{3}-t^{2}\right)}=\frac{1}{3} \cdot \int \frac{d t}{\left[\left(\frac{1}{\sqrt{3}}\right)^{2}-t^{2}\right]}=\frac{1}{3} \cdot \frac{1}{2 \cdot \frac{1}{\sqrt{3}}} \log \left|\frac{\frac{1}{\sqrt{3}}+t}{\frac{1}{\sqrt{3}}-t}\right|+C \\
& =\frac{1}{2 \sqrt{3}} \log \left|\frac{1+\sqrt{3} t}{1-\sqrt{3} t}\right|+C=\frac{1}{2 \sqrt{3}} \log \left|\frac{1+\sqrt{3} \tan x}{1-\sqrt{3} \tan x}\right|+C
\end{aligned}
$$

---

### Example 29:

Evaluate $\int \frac{d x}{(2+\cos x)}$.

#### Solution:

We have

$$
\int \frac{d x}{(2+\cos x)}=\int \frac{d x}{1+(1+\cos x)}=\int \frac{d x}{1+2 \cos ^{2}(x / 2)}=\int \frac{\sec ^{2}(x / 2) d x}{\sec ^{2}(x / 2)+2}
$$

[dividing the num. and denom. by $\cos ^{2}(x / 2)$ ]

$$
\begin{aligned}
& =\int \frac{\sec ^{2}(x / 2)}{3+\tan ^{2}(x / 2)} d x=2 \int \frac{d t}{3+t^{2}}, \text { where } \tan (x / 2)=t \\
& =2 \cdot \int \frac{d t}{(\sqrt{3})^{2}+t^{2}}=2 \cdot \frac{1}{\sqrt{3}} \tan ^{-1} \frac{t}{\sqrt{3}}+C \\
& =\frac{2}{\sqrt{3}} \tan ^{-1}\left[\frac{\tan (x / 2)}{\sqrt{3}}\right]+C .
\end{aligned}
$$

---

## Some More Special Integrals

---

### Example 30: [CBSE 2006C, '07, '11C]

Evaluate $\int \frac{\left(x^{2}+1\right)}{\left(x^{4}+1\right)} d x$.

#### Solution:

We have

$$
\begin{aligned}
\int\left(\frac{x^{2}+1}{x^{4}+1}\right) d x & \left.=\int \frac{\left(1+\frac{1}{x^{2}}\right)}{\left(x^{2}+\frac{1}{x^{2}}\right)} d x \quad \text { [dividing num. and denom. by } x^{2}\right] \\
& =\int \frac{\left(1+\frac{1}{x^{2}}\right)}{\left(x-\frac{1}{x}\right)^{2}+2} d x \\
& =\int \frac{d t}{\left[t^{2}+(\sqrt{2})^{2}\right]}, \text { where }\left(x-\frac{1}{x}\right)=t \text { and }\left(1+\frac{1}{x^{2}}\right) d x=d t \\
& =\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{t}{\sqrt{2}}\right)+C=\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{x-\frac{1}{x}}{\sqrt{2}}\right)+C \\
& =\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{x^{2}-1}{\sqrt{2} x}\right)+C .
\end{aligned}
$$

---

### Example 31: [CBSE 2007C, '11C]

Evaluate $\int \frac{\left(x^{2}+4\right)}{\left(x^{4}+16\right)} d x$.

#### Solution:

We have

$$
\begin{aligned}
\int\left(\frac{x^{2}+4}{x^{4}+16}\right) d x & =\int \frac{\left(1+\frac{4}{x^{2}}\right)}{\left(x^{2}+\frac{16}{x^{2}}\right)} d x \text { [dividing num. and denom. by } x^{2} \text { ] } \\
& =\int \frac{\left(1+\frac{4}{x^{2}}\right)}{\left(x-\frac{4}{x}\right)^{2}+8} d x
\end{aligned}
$$

$$
\begin{aligned}
& =\int \frac{d t}{\left(t^{2}+8\right)} \quad \text { [putting }\left(x-\frac{4}{x}\right)=t \text { and }\left(1+\frac{4}{x^{2}}\right) d x=d t \text { ] } \\
& =\int \frac{d t}{t^{2}+(\sqrt{8})^{2}}=\frac{1}{\sqrt{8}} \tan ^{-1}\left(\frac{t}{\sqrt{8}}\right)+C \\
& =\frac{1}{\sqrt{8}} \tan ^{-1} \frac{\left(x-\frac{4}{x}\right)}{\sqrt{8}}+C=\frac{1}{2 \sqrt{2}} \tan ^{-1}\left(\frac{x^{2}-4}{2 \sqrt{2} x}\right)+C
\end{aligned}
$$

---

### Example 32:

Evaluate $\int \frac{\left(x^{2}-1\right)}{\left(x^{4}+x^{2}+1\right)} d x$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{\left(x^{2}-1\right)}{\left(x^{4}+x^{2}+1\right)} d x & =\int \frac{\left(1-\frac{1}{x^{2}}\right)}{\left(x^{2}+\frac{1}{x^{2}}+1\right)} d x \\
& =\int \frac{\left(1-\frac{1}{x^{2}}\right)}{\left[\left(x+\frac{1}{x}\right)^{2}-1\right]} d x=\int \frac{d t}{\left(t^{2}-1\right)} \\
& {\left[\text { putting }\left(x+\frac{1}{x}\right)=t \text { and }\left(1-\frac{1}{x^{2}}\right) d x=d t\right] } \\
& =\frac{1}{2} \log \left|\frac{t-1}{t+1}\right|+C=\frac{1}{2} \log \left|\frac{x+\frac{1}{x}-1}{x+\frac{1}{x}+1}\right|+C \\
& =\frac{1}{2} \log \left|\frac{x^{2}-x+1}{x^{2}+x+1}\right|+C
\end{aligned}
$$

---

### Example 33:

Evaluate $\int \frac{d x}{\left(x^{4}+1\right)}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\left(x^{4}+1\right)} & =\int \frac{\left(x^{2}+1\right)-\left(x^{2}-1\right)}{2\left(x^{4}+1\right)} d x \\
& =\frac{1}{2} \int \frac{\left(x^{2}+1\right)}{\left(x^{4}+1\right)} d x-\frac{1}{2} \int \frac{\left(x^{2}-1\right)}{\left(x^{4}+1\right)} d x
\end{aligned}
$$

$$
=\frac{1}{2}\left[\int \frac{\left(1+\frac{1}{x^{2}}\right)}{\left(x^{2}+\frac{1}{x^{2}}\right)} d x-\int \frac{\left(1-\frac{1}{x^{2}}\right)}{\left(x^{2}+\frac{1}{x^{2}}\right)} d x\right]
$$

[dividing num. and denom. of each integral by $x^{2}$ ]

$$
\begin{aligned}
& =\frac{1}{2}\left[\int \frac{\left(1+\frac{1}{x^{2}}\right)}{\left[\left(x-\frac{1}{x}\right)^{2}+2\right]} d x-\int \frac{\left(1-\frac{1}{x^{2}}\right)}{\left[\left(x+\frac{1}{x}\right)^{2}-2\right]} d x\right] \\
& =\frac{1}{2}\left[\int \frac{d t}{\left[t^{2}+(\sqrt{2})^{2}\right]}-\int \frac{d u}{\left[u^{2}-(\sqrt{2})^{2}\right]}\right]
\end{aligned}
$$

[putting $\left(x-\frac{1}{x}\right)=t$ in the 1st integral, and $\left(x+\frac{1}{x}\right)=u$ in the 2nd]

$$
\begin{aligned}
& =\frac{1}{2}\left\{\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{t}{\sqrt{2}}\right)-\frac{1}{2 \sqrt{2}} \log \left|\frac{u-\sqrt{2}}{u+\sqrt{2}}\right|\right\}+C \\
& =\frac{1}{2 \sqrt{2}} \tan ^{-1}\left(\frac{x-\frac{1}{x}}{\sqrt{2}}\right)-\frac{1}{4 \sqrt{2}} \log \left|\frac{x+\frac{1}{x}-\sqrt{2}}{x+\frac{1}{x}+\sqrt{2}}\right|+C \\
& =\frac{1}{2 \sqrt{2}} \tan ^{-1}\left(\frac{x^{2}-1}{\sqrt{2} x}\right)-\frac{1}{4 \sqrt{2}} \log \left|\frac{x^{2}+1-\sqrt{2} x}{x^{2}+1+\sqrt{2} x}\right|+C .
\end{aligned}
$$

---

### Example 34: [CBSE 2008C]

Evaluate $\int \frac{x^{2}}{\left(x^{4}+x^{2}+1\right)} d x$.

#### Solution:

We have

$$
\begin{aligned}
I & =\frac{1}{2} \int \frac{2 x^{2}}{\left(x^{4}+x^{2}+1\right)} d x \\
& =\frac{1}{2} \cdot \int \frac{\left(x^{2}-1\right)+\left(x^{2}+1\right)}{\left(x^{4}+x^{2}+1\right)} d x \\
& =\frac{1}{2} \int \frac{\left(x^{2}-1\right)}{\left(x^{4}+x^{2}+1\right)} d x+\frac{1}{2} \int \frac{\left(x^{2}+1\right)}{\left(x^{4}+x^{2}+1\right)} d x \\
& =\frac{1}{2} \int \frac{\left(1-\frac{1}{x^{2}}\right)}{\left(x^{2}+1+\frac{1}{x^{2}}\right)} d x+\frac{1}{2} \int \frac{\left(1+\frac{1}{x^{2}}\right)}{\left(x^{2}+1+\frac{1}{x^{2}}\right)} d x
\end{aligned}
$$

[on dividing num. and denom. of each by $x^{2}$ ]

$$
\begin{aligned}
& =\frac{1}{2} \int \frac{\left(1-\frac{1}{x^{2}}\right)}{\left\{\left(x+\frac{1}{x}\right)^{2}-1\right\}} d x+\frac{1}{2} \int \frac{\left(1+\frac{1}{x^{2}}\right)}{\left\{\left(x-\frac{1}{x}\right)^{2}+(\sqrt{3})^{2}\right\}} d x \\
& =\frac{1}{2} \int \frac{d u}{\left(u^{2}-1\right)}+\frac{1}{2} \int \frac{d v}{\left\{v^{2}+(\sqrt{3})^{2}\right\}} \\
& \quad\left\{\begin{array}{c}
\text { putting }\left(x+\frac{1}{x}\right)=u \text { and }\left(1-\frac{1}{x^{2}}\right)=d u \text { in } I_{1}, \\
\text { and } \left.\left(x-\frac{1}{x}\right)=v \text { and }\left(1+\frac{1}{x^{2}}\right) d x=d v \text { in } I_{2}\right\}
\end{array}\right. \\
& =\frac{1}{2} \log \left|\frac{u-1}{u+1}\right|+\frac{1}{2} \cdot \frac{1}{\sqrt{3}} \tan ^{-1} \frac{v}{\sqrt{3}}+C \\
& =\frac{1}{2} \log \left|\frac{x+\frac{1}{x}-1}{x+\frac{1}{x}+1}\right|+\frac{1}{2 \sqrt{3}} \tan ^{-1}\left(\frac{x^{2}-1}{\sqrt{3} x}\right)+C \\
& =\frac{1}{2} \log \left|\frac{x^{2}-x+1}{x^{2}+x+1}\right|+\frac{1}{2 \sqrt{3}} \tan ^{-1}\left(\frac{x^{2}+1}{\sqrt{3} x}\right)+C .
\end{aligned}
$$

---

### Example 35:

Evaluate $\int \sqrt{\cot x} d x$.

#### Solution:

Put **$\cot x=t^{2}$** so that $-\operatorname{cosec}^{2} x d x=2 t d t$ or $d x=\frac{-2 t}{\left(1+t^{4}\right)} d t$.

$$
\begin{aligned}
\therefore \int \sqrt{\cot x} d x & =-\int \frac{2 t^{2}}{\left(t^{4}+1\right)} d t \\
& =-\int \frac{\left[\left(t^{2}+1\right)+\left(t^{2}-1\right)\right]}{\left(t^{4}+1\right)} d t=-\int \frac{\left(t^{2}+1\right)}{\left(t^{4}+1\right)} d t-\int \frac{\left(t^{2}-1\right)}{\left(t^{4}+1\right)} d t \\
& =-\int \frac{\left(1+\frac{1}{t^{2}}\right)}{\left(t^{2}+\frac{1}{t^{2}}\right)} d t-\int \frac{\left(1-\frac{1}{t^{2}}\right)}{\left(t^{2}+\frac{1}{t^{2}}\right)} d t \\
& =-\int \frac{\left(1+\frac{1}{t^{2}}\right)}{\left[\left(t-\frac{1}{t}\right)^{2}+2\right]} d t-\int \frac{\left(1-\frac{1}{t^{2}}\right)}{\left[\left(t+\frac{1}{t}\right)^{2}-2\right]} d t \\
& =-\int \frac{d u}{\left[u^{2}+(\sqrt{2})^{2}\right]}-\int \frac{d v}{\left[v^{2}-(\sqrt{2})^{2}\right]}
\end{aligned}
$$

[putting $\left(t-\frac{1}{t}\right)=u$ in the 1st integral, and $\left(t+\frac{1}{t}\right)=v$ in the 2nd]

$$
\begin{aligned}
& =-\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{u}{\sqrt{2}}\right)-\frac{1}{2 \sqrt{2}} \log \left|\frac{v-\sqrt{2}}{v+\sqrt{2}}\right|+C \\
& =-\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{t-\frac{1}{t}}{\sqrt{2}}\right)-\frac{1}{2 \sqrt{2}} \log \left|\frac{t+\frac{1}{t}-\sqrt{2}}{t+\frac{1}{t}+\sqrt{2}}\right|+C \\
& =-\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{t^{2}-1}{\sqrt{2} t}\right)-\frac{1}{2 \sqrt{2}} \log \left|\frac{t^{2}-\sqrt{2} t+1}{t^{2}+\sqrt{2} t+1}\right|+C \\
& =-\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{\cot x-1}{\sqrt{2 \cot x}}\right)-\frac{1}{2 \sqrt{2}} \log \left|\frac{\cot x-\sqrt{2 \cot x}+1}{\cot x+\sqrt{2 \cot x}+1}\right|+C .
\end{aligned}
$$

---

### Example 36: [CBSE 2010C, '13C]

Evaluate $\int(\sqrt{\tan x}+\sqrt{\cot x}) d x$.

#### Solution:

We have

$$
\begin{aligned}
& \int(\sqrt{\tan x}+\sqrt{\cot x}) d x \\
& =\int\left(\sqrt{\tan x}+\frac{1}{\sqrt{\tan x}}\right) d x=\int \frac{(\tan x+1)}{\sqrt{\tan x}} d x \\
& =\int \frac{\left(t^{2}+1\right)}{t} \cdot \frac{2 t}{\left(1+t^{4}\right)} d t, \text { where } \tan x=t^{2} \Rightarrow x=\tan ^{-1} t^{2} \\
& \Rightarrow d x=\frac{2 t}{\left(1+t^{4}\right)} d t \\
& \left.=2 \int \frac{\left(t^{2}+1\right)}{\left(t^{4}+1\right)} d t=2 \int \frac{\left(1+\frac{1}{t^{2}}\right)}{\left(t^{2}+\frac{1}{t^{2}}\right)} d t \text { [on dividing num. and denom. by } t^{2}\right] \\
& =2 \int \frac{\left(1+\frac{1}{t^{2}}\right)}{\left(t-\frac{1}{t}\right)^{2}+2} d t \\
& =2 \int \frac{d u}{\left(u^{2}+2\right)}, \text { where }\left(t-\frac{1}{t}\right)=u \text { and }\left(1+\frac{1}{t^{2}}\right) d t=d u \\
& =2 \cdot \frac{1}{\sqrt{2}} \tan ^{-1} \frac{u}{\sqrt{2}}+C=\sqrt{2} \tan ^{-1} \frac{\left(t-\frac{1}{t}\right)}{\sqrt{2}}+C \quad\left[\because \quad u=\left(t-\frac{1}{t}\right)\right] \\
& =\sqrt{2} \tan ^{-1} \frac{\left(t^{2}-1\right)}{(\sqrt{2} t)}+C=\sqrt{2} \tan ^{-1}\left(\frac{\tan x-1}{\sqrt{2 \tan x}}\right)+C \quad\left[\because \quad t^{2}=\tan x\right]
\end{aligned}
$$

---

### Example 37: [CBSE 2006]

Evaluate $\int \sqrt{\tan \theta} d \theta$.

#### Solution:

Putting **$\tan \theta=t^{2}$**, we get $\theta=\tan ^{-1} t^{2} \Rightarrow d \theta=\frac{2 t}{\left(1+t^{4}\right)} d t$.

$$
\begin{aligned}
\therefore I & =\int t \cdot \frac{2 t}{\left(1+t^{4}\right)} d t=\int \frac{2 t^{2}}{\left(t^{4}+1\right)} d t \\
& =\int \frac{\left(t^{2}+1\right)+\left(t^{2}-1\right)}{\left(t^{4}+1\right)} d t=\int \frac{\left(t^{2}+1\right)}{\left(t^{4}+1\right)} d t+\int \frac{\left(t^{2}-1\right)}{\left(t^{4}+1\right)} d t \\
& =\int \frac{\left(1+\frac{1}{t^{2}}\right)}{\left(t^{2}+\frac{1}{t^{2}}\right)} d t+\int \frac{\left(1-\frac{1}{t^{2}}\right)}{\left(t^{2}+\frac{1}{t^{2}}\right)} d t \\
& =\int \frac{\left(1+\frac{1}{t^{2}}\right)}{\left(t-\frac{1}{t}\right)^{2}+2} d t+\int \frac{\left(1-\frac{1}{t^{2}}\right)}{\left\{\left(t+\frac{1}{t}\right)^{2}-2\right\}} d t \\
& =\int \frac{d u}{\left(u^{2}+2\right)}+\int \frac{d v}{\left(v^{2}-2\right)}, \\
& =\frac{1}{\sqrt{2}} \tan ^{-1} \frac{u}{\sqrt{2}}+\frac{1}{2 \sqrt{2}} \cdot \log \left|\frac{v-\sqrt{2}}{v+\sqrt{2}}\right|+C \\
& =\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{t-\frac{1}{t}}{\sqrt{2}}\right)+\frac{1}{2 \sqrt{2}} \cdot\left|\frac{t+\frac{1}{t}-\sqrt{2}}{t+\frac{1}{t}+\sqrt{2}}\right|+C \\
& =\frac{1}{\sqrt{2}} \tan ^{-1}\left(\frac{t^{2}-1}{\sqrt{2} t}\right)+\frac{1}{2 \sqrt{2}} \cdot\left|\frac{t^{2}-\sqrt{2} t+1}{t^{2}+\sqrt{2} t+1}\right|+C, \text{ where } t=\sqrt{\tan \theta}
\end{aligned}
$$

---