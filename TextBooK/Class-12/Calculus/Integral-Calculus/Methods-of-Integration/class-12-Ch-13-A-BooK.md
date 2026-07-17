## 13. Methods of Integration

### Integration by Substitution

If we have to evaluate an integral of the type $\int f\{\phi(x)\} \cdot \phi^{\prime}(x) d x$ then we put $\phi(x)=t$ and $\phi^{\prime}(x) d x=d t$. With this substitution, the integrand becomes easily integrable.

-   **Case I:** When the integrand is of the form $f(a x+b)$, we put $(a x+b)=t$ and $d x=\frac{1}{a} d t$.
-   **Case II:** When the integrand is of the form $x^{n-1} \cdot f\left(x^{n}\right)$, we put $x^{n}=t$ and $n x^{n-1} d x=d t$.
-   **Case III:** When the integrand is of the form $\{f(x)\}^{n} \cdot f^{\prime}(x)$, we put $f(x)=t$ and $f^{\prime}(x) d x=d t$.
-   **Case IV:** When the integrand is of the form $\frac{f^{\prime}(x)}{f(x)}$, we put $f(x)=t$ and $f^{\prime}(x) d x=d t$.

#### Theorem 1:

$$
\int(a x+b)^{n} d x=\frac{(a x+b)^{n+1}}{a(n+1)}+C, \quad \text{where } n \neq-1.
$$

**Proof:**
Putting $a x+b=t$, we get $a d x=d t$ or $d x=\frac{1}{a} d t$.

$$
\therefore \quad \int(a x+b)^{n} d x=\frac{1}{a} \int t^{n} d t=\frac{1}{a} \cdot \frac{t^{n+1}}{(n+1)}+C=\frac{(a x+b)^{n+1}}{a(n+1)}+C
$$

#### Theorem 2:

1.  $$\int \cos (a x+b) d x=\frac{1}{a} \sin (a x+b)+C$$
2.  $$\int \operatorname{cosec}^{2}(a x+b) d x=-\frac{1}{a} \cot (a x+b)+C$$

**Proof:**
(i) Put $(a x+b)=t$ so that $d x=\frac{1}{a} d t$.

$$
\begin{aligned}
\therefore \int \cos (a x+b) d x & =\frac{1}{a} \int \cos t d t \\
& =\frac{1}{a} \sin t+C \\
& =\frac{1}{a} \sin (a x+b)+C
\end{aligned}
$$

(ii) Put $(a x+b)=t$ so that $d x=\frac{1}{a} d t$.

$$
\begin{aligned}
\therefore \int \operatorname{cosec}^{2}(a x+b) d x & =\frac{1}{a} \int \operatorname{cosec}^{2} t d t \\
& =-\frac{1}{a} \cot t+C=-\frac{1}{a} \cot (a x+b)+C
\end{aligned}
$$

---

## Solved Examples

### Example 1:

Evaluate:

1.  $\int(3 x+5)^{7} d x$
2.  $\int(4-9 x)^{5} d x$
3.  $\int \frac{1}{(2-3 x)^{4}} d x$
4.  $\int \sqrt{a x+b} d x$

#### Solution:

(i) Put $(3 x+5)=t$ so that $3 d x=d t$ or $d x=\frac{1}{3} d t$.

$$
\therefore \quad \int(3 x+5)^{7} d x=\frac{1}{3} \int t^{7} d t=\frac{1}{3} \cdot \frac{t^{8}}{8}+C=\frac{(3 x+5)^{8}}{24}+C .
$$

(ii) Put $(4-9 x)=t$ so that $-9 d x=d t$ or $d x=-\frac{1}{9} d t$.

$$
\therefore \quad \int(4-9 x)^{5} d x=-\frac{1}{9} \int t^{5} d t=-\frac{1}{9} \cdot \frac{t^{6}}{6}+C=\frac{-(4-9 x)^{6}}{54}+C
$$

(iii) Put $(2-3 x)=t$ so that $-3 d x=d t$ or $d x=-\frac{1}{3} d t$.

$$
\therefore \int \frac{1}{(2-3 x)^{4}} d x=-\frac{1}{3} \int \frac{1}{t^{4}} d t=-\frac{1}{3} \cdot \frac{1}{\left(-3 t^{3}\right)}+C=\frac{1}{9(2-3 x)^{3}}+C .
$$

(iv) Put $(a x+b)=t$ so that $a d x=d t$.

$$
\therefore \quad \int \sqrt{a x+b} d t=\frac{1}{a} \int \sqrt{t} d t=\frac{2}{3 a} t^{3 / 2}+C=\frac{2(a x+b)^{3 / 2}}{3 a}+C
$$

---

### Example 2:

Evaluate:

1.  $\int \cos 2 x d x$
2.  $\int e^{(5 x+3)} d x$
3.  $\int \sec ^{2}(3 x+5) d x$
4.  $\int \sin ^{3} x d x$

#### Solution:

(i) Put $2 x=t$ so that $2 d x=d t \quad$ or $\quad d x=\frac{1}{2} d t$.

$$
\therefore \quad \int \cos 2 x d x=\frac{1}{2} \int \cos t d t=\frac{1}{2} \sin t+C=\frac{1}{2} \sin 2 x+C .
$$

(ii) Put $(5 x+3)=t$ so that $5 d x=d t$ or $d x=\frac{1}{5} d t$.

$$
\therefore \quad \int e^{(5 x+3)} d x=\frac{1}{5} \int e^{t} d t=\frac{1}{5} \cdot e^{t}+C=\frac{1}{5} e^{(5 x+3)}+C
$$

(iii) Put $(3 x+5)=t$ so that $3 d x=d t$ or $d x=\frac{1}{3} d t$.

$$
\begin{aligned}
\therefore \int \sec ^{2}(3 x+5) d x & =\frac{1}{3} \int \sec ^{2} t d t=\frac{1}{3} \tan t+C \\
& =\frac{1}{3} \tan (3 x+5)+C
\end{aligned}
$$

(iv) We know that $\sin 3 x=3 \sin x-4 \sin ^{3} x$.

$$
\therefore \quad \sin ^{3} x=\frac{1}{4}(3 \sin x-\sin 3 x) .
$$

So, $\int \sin ^{3} x d x=\int\left(\frac{3}{4} \sin x-\frac{1}{4} \sin 3 x\right) d x$

$$
\begin{aligned}
& =\frac{3}{4} \int \sin x d x-\frac{1}{4} \int \sin 3 x d x \\
& =\frac{3}{4}(-\cos x)-\frac{1}{4} \cdot \frac{(-\cos 3 x)}{3}+C \\
& =-\frac{3}{4} \cos x+\frac{\cos 3 x}{12}+C
\end{aligned}
$$

---

### Example 3:

Evaluate:

1.  $\int \frac{\log x}{x} d x$
2.  $\int \frac{\sec ^{2}(\log x)}{x} d x$
3.  $\int \frac{e^{\tan ^{-1} x}}{\left(1+x^{2}\right)} d x$
4.  $\int \frac{\sin \sqrt{x}}{\sqrt{x}} d x$

#### Solution:

(i) Put $\log x=t$ so that $\frac{1}{x} d x=d t$.

$$
\therefore \quad \int \frac{\log x}{x} d x=\int t d t=\frac{1}{2} t^{2}+C=\frac{1}{2}(\log x)^{2}+C
$$

(ii) Put $\log x=t$ so that $\frac{1}{x} d x=d t$.

$$
\therefore \quad \int \frac{\sec ^{2}(\log x)}{x} d x=\int \sec ^{2} t d t=\tan t+C=\tan (\log x)+C
$$

(iii) Put $\tan ^{-1} x=t$ so that $\frac{1}{\left(1+x^{2}\right)} d x=d t$.

$$
\therefore \int \frac{e^{\tan ^{-1} x}}{\left(1+x^{2}\right)} d x=\int e^{t} d t=e^{t}+C=e^{\tan ^{-1} x}+C
$$

(iv) Put $\sqrt{x}=t$ so that $\frac{1}{2} x^{-1 / 2} d x=d t$ or $\frac{1}{\sqrt{x}} d x=2 d t$.

$$
\begin{aligned}
\therefore \int \frac{\sin \sqrt{x}}{\sqrt{x}} d x & =2 \int \sin t d t \\
& =2(-\cos t)+C=-2 \cos t+C=-2 \cos \sqrt{x}+C .
\end{aligned}
$$

---

### Example 4:

Evaluate:

1.  $\int \cos ^{3} x \sin x d x$
2.  $\int(\sqrt{\sin x}) \cos x d x$
3.  $\int \frac{\operatorname{cosec}^{2} x}{(1+\cot x)} d x$
4.  $\int \frac{\sin x}{(3+4 \cos x)^{2}} d x$

#### Solution:

(i) Put $\cos x=t$ so that $\sin x d x=-d t$.

$$
\therefore \quad \int \cos ^{3} x \sin x d x=-\int t^{3} d t=-\frac{t^{4}}{4}+C=-\frac{1}{4} \cos ^{4} x+C
$$

(ii) Put $\sin x=t$ so that $\cos x d x=d t$.

$$
\therefore \quad \int(\sqrt{\sin x}) \cos x d x=\int \sqrt{t} d t=\frac{2}{3} t^{3 / 2}+C=\frac{2}{3}(\sin x)^{3 / 2}+C .
$$

(iii) Put $(1+\cot x)=t$ so that $-\operatorname{cosec}^{2} x d x=d t$.

$$
\begin{aligned}
\therefore \int \frac{\operatorname{cosec}^{2} x}{(1+\cot x)} d x & =-\int \frac{1}{t} d t \\
& =-\log t+C=-\log |(1+\cot x)|+C
\end{aligned}
$$

(iv) Put $(3+4 \cos x)=t$ so that $-4 \sin x d x=d t$.

$$
\therefore \int \frac{\sin x}{(3+4 \cos x)^{2}} d x=-\frac{1}{4} \int \frac{1}{t^{2}} d t=\frac{1}{4 t}+C=\frac{1}{4(3+4 \cos x)}+C
$$

---

### Example 5:

Evaluate:

1.  $\int \frac{2 x}{(2 x+1)^{2}} d x$
2.  $\int \frac{(2+3 x)}{(3-2 x)} d x$

#### Solution:

(i) Put $(2 x+1)=t$ so that $2 x=(t-1)$ and $d x=\frac{1}{2} d t$.

$$
\begin{aligned}
\therefore \int \frac{2 x}{(2 x+1)^{2}} d x & =\frac{1}{2} \int \frac{(t-1)}{t^{2}} d t \\
& =\frac{1}{2} \int \frac{1}{t} d t-\frac{1}{2} \int \frac{1}{t^{2}} d t=\frac{1}{2} \log |t|+\frac{1}{2 t}+C \\
& =\frac{1}{2} \log |(2 x+1)|+\frac{1}{2(2 x+1)}+C .
\end{aligned}
$$

(ii) Put $(3-2 x)=t$ so that $x=\left(\frac{3-t}{2}\right)$ and $d x=-\frac{1}{2} d t$.

$$
\begin{aligned}
\therefore \int \frac{(2+3 x)}{(3-2 x)} d t & =-\frac{1}{2} \int \frac{\left[2+\left(\frac{9-3 t}{2}\right)\right]}{t} d t=-\frac{1}{4} \int \frac{(13-3 t)}{t} d t \\
& =\frac{-13}{4} \int \frac{1}{t} d t+\frac{3}{4} \int d t=-\frac{13}{4} \log |t|+\frac{3}{4} t+C \\
& =-\frac{13}{4} \log |(3-2 x)|+\frac{3}{4}(3-2 x)+C .
\end{aligned}
$$

---

### Example 6:

Evaluate:

1.  $\int \frac{3 x^{2}}{\left(1+x^{6}\right)} d x$
2.  $\int \frac{x^{3}}{\left(x^{2}+1\right)^{3}} d x$
3.  $\frac{x^{8}}{\left(1-x^{3}\right)^{1 / 3}} d x$

#### Solution:

(i) Put $x^{3}=t$ so that $3 x^{2} d x=d t$.

$$
\therefore \int \frac{3 x^{2}}{\left(1+x^{6}\right)} d x=\int \frac{d t}{\left(1+t^{2}\right)}=\tan ^{-1} t+C=\tan ^{-1} x^{3}+C
$$

(ii) Put $\left(x^{2}+1\right)=t$ so that $x^{2}=(t-1)$ and $x d x=\frac{1}{2} d t$.

$$
\begin{aligned}
\therefore \int \frac{x^{3}}{\left(x^{2}+1\right)^{3}} d x & =\int \frac{x^{2} \cdot x}{\left(x^{2}+1\right)^{3}} d x \\
& =\frac{1}{2} \int \frac{(t-1)}{t^{3}} d t=\frac{1}{2} \int \frac{1}{t^{2}} d t-\frac{1}{2} \int \frac{1}{t^{3}} d t \\
& =\frac{-1}{2 t}+\frac{1}{4 t^{2}}+C=\frac{-1}{2\left(x^{2}+1\right)}+\frac{1}{4\left(x^{2}+1\right)^{2}}+C \\
& =\frac{-\left(1+2 x^{2}\right)}{4\left(x^{2}+1\right)^{2}}+C
\endend{aligned}
$$

(iii) Put $\left(1-x^{3}\right)=t$ so that $x^{3}=(1-t)$ and $x^{2} d x=-\frac{1}{3} d t$.

$$
\begin{aligned}
\therefore \int \frac{x^{8}}{\left(1-x^{3}\right)^{1 / 3}} d x & =\int \frac{x^{6} \cdot x^{2}}{\left(1-x^{3}\right)^{1 / 3}} d x \\
& =-\frac{1}{3} \int \frac{(1-t)^{2}}{t^{1 / 3}} d t=-\frac{1}{3} \int \frac{\left(1+t^{2}-2 t\right)}{t^{1 / 3}} d t \\
& =-\frac{1}{3} \int t^{-1 / 3} d t-\frac{1}{3} \int t^{5 / 3} d t+\frac{2}{3} \int t^{2 / 3} d t \\
& =-\frac{1}{2} t^{2 / 3}-\frac{1}{8} t^{8 / 3}+\frac{2}{5} t^{5 / 3}+C \\
& =-\frac{1}{2}\left(1-x^{3}\right)^{2 / 3}-\frac{1}{8}\left(1-x^{3}\right)^{8 / 3} \\
& \quad+\frac{2}{5}\left(1-x^{3}\right)^{5 / 3}+C
\end{aligned}
$$

---

### Example 7:

Evaluate $\int \frac{d x}{x \cdot \sqrt{x^{6}-1}}$.

#### Solution:

Put $x^{3}=t$ so that $3 x^{2} d x=d t \quad$ or $\quad x^{2} d x=\frac{1}{3} d t$.

$$
\therefore \int \frac{d x}{x \cdot \sqrt{x^{6}-1}}=\int \frac{x^{2}}{x^{3} \cdot \sqrt{x^{6}-1}} d x
$$

*\[multiplying numerator and denominator by $x^{2}$\]*

$$
=\frac{1}{3} \int \frac{1}{t \sqrt{t^{2}-1}} d t=\frac{1}{3} \sec ^{-1} t+C=\frac{1}{3} \sec ^{-1} x^{3}+C .
$$

---

### Example 8:

Evaluate $\int \frac{1}{(\sqrt{x}+x)} d x$.
**[CBSE 2003]**

#### Solution:

$$
\int \frac{1}{(\sqrt{x}+x)} d x=\int \frac{1}{\sqrt{x}(1+\sqrt{x})} d x
$$

Now, put $(1+\sqrt{x})=t$ so that $\frac{1}{\sqrt{x}} d x=2 d t$.

$$
\begin{aligned}
\therefore \int \frac{1}{(\sqrt{x}+x)} d x & =\int \frac{1}{\sqrt{x}(1+\sqrt{x})} d x \\
& =2 \int \frac{1}{t} d t=2 \log |t|+C=2 \log |(1+\sqrt{x})|+C
\end{aligned}
$$

---

### Example 9:

Evaluate:

1.  $\int \frac{(x-1)}{\sqrt{x+4}} d x$
2.  $\int x \sqrt{x+2} d x$
3.  $\int(4 x+2) \sqrt{x^{2}+x+1} d x$
4.  $\int \frac{(4 x+3)}{\sqrt{2 x^{2}+3 x+1}} d x$

#### Solution:

(i) Put $(x+4)=t^{2}$ so that $x=\left(t^{2}-4\right)$ and $d x=2 t d t$.

$$
\begin{aligned}
\therefore \int \frac{(x-1)}{\sqrt{x+4}} d x & =2 \int \frac{\left(t^{2}-5\right) t}{t} d t \\
& =2 \int t^{2} d t-10 \int d t=\frac{2 t^{3}}{3}-10 t+C \\
& =\frac{2}{3}(x+4)^{3 / 2}-10(x+4)^{1 / 2}+C
\end{aligned}
$$

(ii) Put $(x+2)=t^{2}$ so that $x=\left(t^{2}-2\right)$ and $d x=2 t d t$.

$$
\begin{aligned}
\therefore \int x \sqrt{x+2} d x & =\int\left(t^{2}-2\right) 2 t^{2} d t=2 \int t^{4} d t-4 \int t^{2} d t \\
& =\frac{2 t^{5}}{5}-\frac{4 t^{3}}{3}+C=\frac{2(x+2)^{5 / 2}}{5}-\frac{4(x+2)^{3 / 2}}{3}+C .
\end{aligned}
$$

(iii) Put $\left(x^{2}+x+1\right)=t$ so that $(2 x+1) d x=d t$.

$$
\begin{aligned}
\therefore \int(4 x+2)\left(\sqrt{x^{2}+x+1}\right) d x & =2 \int \sqrt{t} d t \\
& =\frac{4}{3} t^{3 / 2}+C=\frac{4}{3}\left(x^{2}+x+1\right)^{3 / 2}+C
\end{aligned}
$$

(iv) Put $\left(2 x^{2}+3 x+1\right)=t$ so that $(4 x+3) d x=d t$.

$$
\therefore \int \frac{(4 x+3)}{\sqrt{2 x^{2}+3 x+1}} d x=\int \frac{d t}{\sqrt{t}}=2 \sqrt{t}+C=2 \sqrt{2 x^{2}+3 x+1}+C .
$$

---

### Example 10:

Evaluate:

1.  $\int \frac{(2 x+5)}{\left(x^{2}+5 x+9\right)} d x$
2.  $\int \frac{(6 x-7)}{\left(3 x^{2}-7 x+5\right)^{2}} d x$
3.  $\int \frac{(\cos x-\sin x)}{(\cos x+\sin x)} d x$
4.  $\int \frac{\sec x}{\log (\sec x+\tan x)} d x$

#### Solution:

(i) Put $\left(x^{2}+5 x+9\right)=t$ so that $(2 x+5) d x=d t$.

$$
\begin{aligned}
\therefore \int \frac{(2 x+5)}{\left(x^{2}+5 x+9\right)} d x & =\int \frac{1}{t} d t=\log |t|+C \\
& =\log \left|\left(x^{2}+5 x+9\right)\right|+C
\end{aligned}
$$

(ii) Put $\left(3 x^{2}-7 x+5\right)=t$ so that $(6 x-7) d x=d t$.

$$
\therefore \int \frac{(6 x-7)}{\left(3 x^{2}-7 x+5\right)^{2}} d x=\int \frac{1}{t^{2}} d t=-\frac{1}{t}+C=\frac{-1}{\left(3 x^{2}-7 x+5\right)}+C
$$

(iii) Put $(\cos x+\sin x)=t$ so that $(\cos x-\sin x) d x=d t$.

$$
\begin{aligned}
\therefore \int \frac{(\cos x-\sin x)}{(\cos x+\sin x)} d x & =\int \frac{1}{t} d t \\
& =\log |t|+C=\log |(\cos x+\sin x)|+C
\endC
$$

(iv) Put $\log (\sec x+\tan x)=t$.

Then, on differentiation, we get

$$
\begin{array}{ll} 
& \frac{1}{(\sec x+\tan x)} \cdot\left(\sec x \tan x+\sec ^{2} x\right) d x=d t \\
\text{or} & \sec x d x=d t \\
\therefore & \int \frac{\sec x}{\log (\sec x+\tan x)} d x=\int \frac{1}{t} d t \\
& \quad=\log |t|+C=\log |\log (\sec x+\tan x)|+C
\end{array}
$$

---

### Example 11:

Evaluate $\int \frac{\sin 2 x}{\left(a^{2} \sin ^{2} x+b^{2} \cos ^{2} x\right)} d x$.
**[CBSE 2005]**

#### Solution:

Put $\left(a^{2} \sin ^{2} x+b^{2} \cos ^{2} x\right)=t$ so that

$$
\begin{aligned}
& 2\left(a^{2}-b^{2}\right) \sin x \cos x d x =d t \\
\Leftrightarrow & \sin 2 x d x=\frac{d t}{\left(a^{2}-b^{2}\right)}
\end{aligned}
$$

$$
\begin{aligned}
\therefore \quad I=\int \frac{\sin 2 x}{\left(a^{2} \sin ^{2} x+b^{2} \cos ^{2} x\right)} d x & =\int \frac{d t}{\left(a^{2}-b^{2}\right) t} \\
& =\frac{1}{\left(a^{2}-b^{2}\right)} \log |t|+C \\
& =\frac{1}{\left(a^{2}-b^{2}\right)} \log \left(a^{2} \sin ^{2} x+b^{2} \cos ^{2} x\right)+C
\end{aligned}
$$

---

### Example 12:

Evaluate $\int \frac{x^{2} \tan ^{-1} x^{3}}{\left(1+x^{6}\right)} d x$.

#### Solution:

Put $\tan ^{-1} x^{3}=t$ so that $\frac{3 x^{2}}{\left(1+x^{6}\right)} d x=d t$ or $\frac{x^{2}}{\left(1+x^{6}\right)} d x=\frac{1}{3} d t$.

$$
\therefore \int \frac{x^{2} \tan ^{-1} x^{3}}{\left(1+x^{6}\right)} d x=\frac{1}{3} \int t d t=\frac{1}{6} t^{2}+C=\frac{1}{6}\left(\tan ^{-1} x^{3}\right)^{2}+C
$$

---

### Example 13:

Evaluate $\int \frac{\sqrt{\tan x}}{\sin x \cos x} d x$.

#### Solution:

$$
\int \frac{\sqrt{\tan x}}{\sin x \cos x} d x=\int \frac{\tan x}{(\sqrt{\tan x}) \cdot \sin x \cos x} d x=\int \frac{\sec ^{2} x}{\sqrt{\tan x}} d x
$$

$$
\begin{aligned}
& =\int \frac{1}{\sqrt{t}} d t, \text { where } \tan x=t \text { and } \sec ^{2} x d x=d t \\
& =2 \sqrt{t}+C=2 \sqrt{\tan x}+C
\end{aligned}
$$

---

### Example 14:

Evaluate $\int \frac{d x}{(\sqrt{2 x+3}+\sqrt{2 x-3})}$.

#### Solution:

$$
\int \frac{d x}{(\sqrt{2 x+3}+\sqrt{2 x-3})}
$$

$$
\begin{aligned}
& =\int \frac{1}{(\sqrt{2 x+3}+\sqrt{2 x-3})} \times \frac{(\sqrt{2 x+3})-\sqrt{2 x-3})}{(\sqrt{2 x+3})-\sqrt{2 x-3})} d x \\
& =\int \frac{(\sqrt{2 x+3}-\sqrt{2 x-3})}{[(2 x+3)-(2 x-3)]} d x=\frac{1}{6} \int(2 x+3)^{1 / 2} d x-\frac{1}{6} \int(2 x-3)^{1 / 2} d x \\
& =\frac{1}{18}(2 x+3)^{3 / 2}-\frac{1}{18}(2 x-3)^{3 / 2}+C
\end{aligned}
$$

---

### Example 15:

Evaluate:

1.  $\int \frac{1}{(1+\tan x)} d x$
2.  $\int \frac{1}{(1+\cot x)} d x$
3.  $\int\left(\frac{1-\tan x}{1+\tan x}\right) d x$ **[CBSE 2000C]**
4.  $\int \frac{\tan x}{(\sec x+\cos x)} d x$

#### Solution:

(i)
$$
\begin{aligned}
\int \frac{1}{(1+\tan x)} d x & =\int \frac{1}{\left(1+\frac{\sin x}{\cos x}\right)} d x \\
& =\int \frac{\cos x}{(\cos x+\sin x)} d x=\int \frac{(\cos x+\sin x)+(\cos x-\sin x)}{2(\cos x+\sin x)} d x \\
& =\frac{1}{2} \int d x+\frac{1}{2} \int \frac{(\cos x-\sin x)}{(\cos x+\sin x)} d x \\
& =\frac{1}{2} \int d x+\frac{1}{2} \int \frac{1}{t} d t, \text{ where } (\cos x+\sin x)=t \text{ and } (\cos x-\sin x) d x=d t \\
& =\frac{1}{2} x+\frac{1}{2} \log |t|+C=\frac{1}{2} x+\frac{1}{2} \log |\cos x+\sin x|+C
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\int \frac{1}{(1+\cot x)} d x & =\int \frac{1}{\left(1+\frac{\cos x}{\sin x}\right)} d x=\int \frac{\sin x}{(\sin x+\cos x)} d x \\
& =\int \frac{(\sin x+\cos x)-(\cos x-\sin x)}{2(\sin x+\cos x)} d x \\
& =\frac{1}{2} \int d x-\frac{1}{2} \int \frac{(\cos x-\sin x)}{(\sin x+\cos x)} d x \\
& =\frac{1}{2} \int d x-\frac{1}{2} \int \frac{1}{t} d t, \text{ where } \sin x+\cos x=t \text{ and } (\cos x-\sin x) d x=d t \\
& =\frac{1}{2} x-\frac{1}{2} \log |t|+C=\frac{1}{2} x-\frac{1}{2} \log |\sin x+\cos x|+C .
\end{aligned}
$$

(iii)
$$
\begin{aligned}
\int\left(\frac{1-\tan x}{1+\tan x}\right) d x & =\int \frac{\left(1-\frac{\sin x}{\cos x}\right)}{\left(1+\frac{\sin x}{\cos x}\right)} d x=\int \frac{(\cos x-\sin x)}{(\cos x+\sin x} d x \\
& =\int \frac{1}{t} d t, \text{ where } (\cos x+\sin x)=t \text{ and } (\cos x-\sin x) d x=d t \\
& =\log |t|+C=\log |(\cos x+\sin x)|+C .
\end{aligned}
$$

(iv)
$$
\begin{aligned}
\int \frac{\tan x}{(\sec x+\cos x)} d x & =\int \frac{\sin x}{1+\cos ^{2} x} d x \\
& =-\int \frac{1}{\left(1+t^{2}\right)} d t, \text{ where } \cos x=t \text{ and } \sin x d x=-d t \\
& =-\tan ^{-1} t+C=-\tan ^{-1}(\cos x)+C .
\end{aligned}
$$

---

### Example 16:

Evaluate:

1.  $\int \tan x d x$
2.  $\int \cot x d x$
3.  $\int \sec x d x$
4.  $\int \operatorname{cosec} x d x$

#### Solution:

(i)
$$
\begin{aligned}
\int \tan x d x & =\int \frac{\sin x}{\cos x} d x \\
& =-\int \frac{1}{t} d t, \text{ where } \cos x=t \text{ and } \sin x d x=-d t \\
& =-\log |t|+C=-\log |\cos x|+C
\end{aligned}
$$

$$
\therefore \int \tan x d x=-\log |\cos x|+C
$$

(ii)
$$
\begin{aligned}
\int \cot x d x & =\int \frac{\cos x}{\sin x} d x \\
& =\int \frac{1}{t} d t, \text{ where } \sin x=t \text{ and } \cos x d x=d t \\
& =\log |t|+C=\log |\sin x|+C .
\end{aligned}
$$

$$
\therefore \quad \int \cot x d x=\log |\sin x|+C .
$$

(iii)
$$
\int \sec x d x=\int \frac{\sec x(\sec x+\tan x)}{(\sec x+\tan x)} d x
$$

*\[multiplying numerator and denominator by $(\sec x+\tan x)$\]*

$$
\begin{gathered}
=\int \frac{1}{t} d t, \text { where }(\sec x+\tan x)=t \\
\text{ and } \sec x(\sec x+\tan x) d x=d t \\
=\log |t|+C=\log |(\sec x+\tan x)|+C
\end{gathered}
$$

$$
\therefore \int \sec x d x=\log |(\sec x+\tan x)|+C
$$

**Alternative form**

$$
\sec x+\tan x=\left(\frac{1}{\cos x}+\frac{\sin x}{\cos x}\right)=\frac{(1+\sin x)}{\cos x}
$$

Putting $\quad \sin x=\frac{2 \tan (x / 2)}{1+\tan ^{2}(x / 2)}$ and $\cos x=\frac{1-\tan ^{2}(x / 2)}{1+\tan ^{2}(x / 2)}$.

$$
\therefore \quad \sec x+\tan x=\frac{1+\tan (x / 2)}{1-\tan (x / 2)}=\tan \left(\frac{\pi}{4}+\frac{x}{2}\right) .
$$

$$
\therefore \quad \int \sec x d x=\log |\sec x+\tan x|+C = \log \left|\tan \left(\frac{\pi}{4}+\frac{x}{2}\right)\right|+C .
$$

(iv)
$$
\int \operatorname{cosec} x d x=\int \frac{\operatorname{cosec} x(\operatorname{cosec} x-\cot x)}{(\operatorname{cosec x}-\cot x)} d x
$$

*\[multiplying numerator and denominator by $(\operatorname{cosec} x-\cot x)$\]*

$$
\begin{aligned}
& =\int \frac{1}{t} d t, \begin{array}{l}
\text{ where } (\operatorname{cosec} x-\cot x)=t \\
\text{ and } \operatorname{cosec} x(\operatorname{cosec} x-\cot x) d x=d t
\end{array} \\
& =\log |t|+C=\log |\operatorname{cosec} x-\cot x|+C
\end{aligned}
$$

$$
\therefore \quad \int \operatorname{cosec} x d x =\log |\operatorname{cosec} x-\cot x|+C
$$

**Alternative form**

$$
\begin{aligned}
\operatorname{cosec} x-\cot x & =\left(\frac{1}{\sin x}-\frac{\cos x}{\sin x}\right)=\frac{1-\cos x}{\sin x} \\
& =\frac{2 \sin ^{2}(x / 2)}{2 \sin (x / 2) \cos (x / 2)}=\tan \frac{x}{2}
\end{aligned}
$$

$$
\begin{aligned}
\therefore \quad \int \operatorname{cosec} x d x & =\log |\operatorname{cosec} x-\cot x|+C \\
& =\log \left|\tan \frac{x}{2}\right|+C
\end{aligned}
$$

As a consequence of the above results, the integral of trigonometric functions may be listed as given below:

1.  $\int \sin x d x=-\cos x+C$
2.  $\int \cos x d x=\sin x+C$
3.  $\int \tan x d x=-\log |\cos x|+C$
4.  $\int \cot x d x=\log |\sin x|+C$
5.  $\int \sec x d x=\log |\sec x+\tan x|+C=\log \left|\tan \left(\frac{\pi}{4}+\frac{x}{2}\right)\right|+C$
6.  $\int \operatorname{cosec} x d x=\log |\operatorname{cosec} x-\cot x|+C=\log \left|\tan \frac{x}{2}\right|+C$

---

### Example 17:

Evaluate:

1.  $\int \frac{(1+\cos x)}{(1-\cos x)} d x$ **[CBSE 2000C]**
2.  $\int \frac{(1+\sin x)}{(1+\cos x)} d x$

#### Solution:

(i)
$$
\int \frac{(1+\cos x)}{(1-\cos x)} d x=\int \frac{2 \cos ^{2}(x / 2)}{2 \sin ^{2}(x / 2)} d x
$$

$$
\begin{aligned}
& =\int \cot ^{2}\left(\frac{x}{2}\right) d x=\int\left(\operatorname{cosec}^{2} \frac{x}{2}-1\right) d x \\
& =\int \operatorname{cosec}^{2} \frac{x}{2} d x-\int d x \\
& =2 \int \operatorname{cosec}^{2} t d t-\int d x, \text { where } \frac{x}{2}=t \text { and } d x=2 d t \\
& =-2 \cot t-x+C=-2 \cot \left(\frac{x}{2}\right)-x+C .
\end{aligned}
$$

(ii)
$$
\int\left(\frac{1+\sin x}{1+\cos x}\right) d x=\int \frac{1}{(1+\cos x)} d x+\int \frac{\sin x}{(1+\cos x)} d x
$$

$$
\begin{aligned}
& =\int \frac{1}{2 \cos ^{2}(x / 2)} d x+\int \frac{2 \sin (x / 2) \cos (x / 2)}{2 \cos ^{2}(x / 2)} d x \\
& =\frac{1}{2} \int \sec ^{2}\left(\frac{x}{2}\right) d x+\int \tan \frac{x}{2} d x \\
& =\int \sec ^{2} t d t+2 \int \tan t d t, \text{ where } \frac{x}{2}=t \\
& =\tan t-2 \log |\cos t|+C \\
& =\tan \left(\frac{x}{2}\right)-2 \log \left|\cos \left(\frac{x}{2}\right)\right|+C .
\end{aligned}
$$

---

### Example 18:

Evaluate:

1.  $\int \frac{d x}{1+\sqrt{x}}$
2.  $\int \frac{x+\sqrt{x+1}}{x+2} d x$

#### Solution:

(i) Put $\sqrt{x}=t$ so that $x=t^{2}$ and $d x=2 t d t$.

$$
\begin{aligned}
\therefore \int \frac{d x}{1+\sqrt{x}} & =\int \frac{2 t}{(1+t)} d t=\int \frac{2(1+t)-2}{(1+t)} d t \\
& =2 \int d t-2 \int \frac{d t}{1+t}=2 t-2 \log |1+t|+C \\
& =2 \sqrt{x}-2 \log |1+\sqrt{x}|+C
\end{aligned}
$$

(ii) Put $\sqrt{x+1}=t$ so that $x+1=t^{2}$ and $d x=2 t d t$.

$$
\begin{aligned}
\therefore \quad \int \frac{x+\sqrt{x+1}}{(x+2)} d x & =2 \int \frac{\left(t^{2}-1+t\right) t}{\left(t^{2}+1\right)} d t \\
& =2 \int\left(\frac{t^{3}+t^{2}-t}{t^{2}+1}\right) d t \\
& =2 \int\left(t+1-\frac{2 t+1}{t^{2}+1}\right) d t \quad \text{[by division]} \\
& =2 \int\left(t+1-\frac{2 t}{t^{2}+1}-\frac{1}{t^{2}+1}\right) d t \\
& =2 \int t d t+2 \int d t-2 \int \frac{2 t}{t^{2}+1} d t-2 \int \frac{1}{t^{2}+1} d t \\
& =t^{2}+2 t-2 \log \left|t^{2}+1\right|-2 \tan ^{-1} t+C \\
& =(x+1)+2 \sqrt{x+1}-2 \log |x+2|-2 \tan ^{-1} \sqrt{x+1}+C
\ends{aligned}
$$

---

### Example 19:

Evaluate $\int \sqrt{\frac{1+x}{1-x}} d x$.
**[CBSE 2006]**

#### Solution:

$$
\int \sqrt{\frac{1+x}{1-x}} d x=\int \frac{\sqrt{1+x}}{\sqrt{1-x}} \times \frac{\sqrt{1+x}}{\sqrt{1+x}} d x
$$

$$
\begin{aligned}
& =\int \frac{1+x}{\sqrt{1-x^{2}}} d x=\int \frac{d x}{\sqrt{1-x^{2}}}+\int \frac{x}{\sqrt{1-x^{2}}} d x \\
& =\int \frac{d x}{\sqrt{1-x^{2}}}-\frac{1}{2} \int \frac{1}{\sqrt{t}} d t, \text{ where } \left(1-x^{2}\right)=t \\
& =\sin ^{-1} x-\sqrt{t}+C \\
& =\sin ^{-1} x-\sqrt{1-x^{2}}+C
\end{aligned}
$$

---

### Example 20:

Evaluate $\int \frac{(3 \sin x-2) \cos x}{\left(5-\cos ^{2} x-4 \sin x\right)} d x$.
**[CBSE 2013C]**

#### Solution:

We have

$$
\begin{align*}
I & =\int \frac{(3 \sin x-2) \cos x}{\left\{5-\left(1-\sin ^{2} x\right)-4 \sin x\right\}} d x \\
& =\int \frac{(3 \sin x-2) \cos x}{\left\{4+\sin ^{2} x-4 \sin x\right\}} d x=\int \frac{(3 \sin x-2) \cos x}{(2-\sin x)^{2}} d x \tag{i}
\end{align*}
$$

Putting $2-\sin x=t$, we get $\sin x=2-t$ and $\cos x d x=-d t$.

$$
\begin{aligned}
\therefore \quad I & =-\int \frac{\{3(2-t)-2\}}{t^{2}} d t=-\int \frac{(4-3 t)}{t^{2}} d t=\int \frac{(3 t-4)}{t^{2}} d t \\
& =\int\left(\frac{3}{t}-\frac{4}{t^{2}}\right) d t=3 \log |t|+\frac{4}{t}+C \\
& =3 \log |(2-\sin x)|+\frac{4}{(2-\sin x)}+C .
\ends{aligned}
$$

---