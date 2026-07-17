# Three More Special Integrals

## Theorem

$$
\begin{aligned}
& \text { (i) } \int \sqrt{a^{2}-x^{2}} d x=\frac{x}{2} \sqrt{a^{2}-x^{2}}+\frac{a^{2}}{2} \sin ^{-1} \frac{x}{a}+C \\
& \text { (ii) } \int \sqrt{x^{2}-a^{2}} d x=\frac{x}{2} \sqrt{x^{2}-a^{2}}-\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+C \\
& \text { (iii) } \int \sqrt{x^{2}+a^{2}} d x=\frac{x}{2} \sqrt{x^{2}+a^{2}}+\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}+a^{2}}\right|+C
\end{aligned}
$$

### Proof (i)

Integrating by **parts**, taking $1$ as the second function, we get

$$
\begin{aligned}
I & =\int \sqrt{a^{2}-x^{2}} d x=\int\left(\sqrt{a^{2}-x^{2}} \cdot 1\right) d x \\
& =\left(\sqrt{a^{2}-x^{2}}\right) \cdot x-\int \frac{1}{2}\left(a^{2}-x^{2}\right)^{-1 / 2}(-2 x) \cdot x d x \\
& =x\left(\sqrt{a^{2}-x^{2}}\right)+\int \frac{x^{2}}{\sqrt{a^{2}-x^{2}}} d x=x\left(\sqrt{a^{2}-x^{2}}\right)+\int \frac{a^{2}-\left(a^{2}-x^{2}\right)}{\sqrt{a^{2}-x^{2}}} d x \\
& =x\left(\sqrt{a^{2}-x^{2}}\right)+a^{2} \int \frac{d x}{\sqrt{a^{2}-x^{2}}}-\int \sqrt{a^{2}-x^{2}} d x \\
& =x\left(\sqrt{a^{2}-x^{2}}\right)+a^{2} \sin ^{-1} \frac{x}{a}-I+c \\
\therefore \quad 2 I & =x\left(\sqrt{a^{2}-x^{2}}\right)+a^{2} \sin ^{-1} \frac{x}{a}+c \\
\Rightarrow I & \left.=\frac{x}{2}\left(\sqrt{a^{2}-x^{2}}\right)+\frac{a^{2}}{2} \sin ^{-1} \frac{x}{a}+C \text { [taking } \frac{c}{2}=C\right] .
\end{aligned}
$$

Hence, $\int \sqrt{a^{2}-x^{2}} d x=\frac{x}{2}\left(\sqrt{a^{2}-x^{2}}\right)+\frac{a^{2}}{2} \sin ^{-1} \frac{x}{a}+C$.

### Proof (ii)

Integrating by **parts**, taking $1$ as the second function, we get

$$
\begin{aligned}
& I=\int \sqrt{x^{2}-a^{2}} d x=\int\left(\sqrt{x^{2}-a^{2}} \cdot 1\right) d x \\
&=\left(\sqrt{x^{2}-a^{2}}\right) \cdot x-\int \frac{1}{2}\left(x^{2}-a^{2}\right)^{-1 / 2}(2 x) \cdot x d x \\
&=x\left(\sqrt{x^{2}-a^{2}}\right)-\int \frac{x^{2}}{\sqrt{x^{2}-a^{2}}} d x=x\left(\sqrt{x^{2}-a^{2}}\right)-\int \frac{\left(x^{2}-a^{2}\right)+a^{2}}{\sqrt{x^{2}-a^{2}}} d x \\
&=x\left(\sqrt{x^{2}-a^{2}}\right)-\int \sqrt{x^{2}-a^{2}} d x-\int \frac{a^{2}}{\sqrt{x^{2}-a^{2}}} d x \\
&=x\left(\sqrt{x^{2}-a^{2}}\right)-I-a^{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+c . \\
& \therefore \quad 2 I=x\left(\sqrt{x^{2}-a^{2}}\right)-a^{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+c \\
& \Rightarrow I=\frac{x}{2}\left(\sqrt{x^{2}-a^{2}}\right)-\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+C \quad\left[\text { taking } \frac{c}{2}=C\right] . \\
& \text { Hence, } \quad \int \sqrt{x^{2}-a^{2}} d x=\frac{x}{2}\left(\sqrt{x^{2}-a^{2}}\right)-\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+C .
\end{aligned}
$$

### Proof (iii)

Integrating by **parts**, taking $1$ as the second function, we get

$$
\begin{aligned}
& \qquad \begin{aligned}
I=\int \sqrt{x^{2}+a^{2}} d x=\int\left(\sqrt{x^{2}+a^{2}} \cdot 1\right) d x & \\
& =\left(\sqrt{x^{2}+a^{2}}\right) x-\int \frac{1}{2}\left(x^{2}+a^{2}\right)^{-1 / 2}(2 x) \cdot x d x \\
& =x\left(\sqrt{x^{2}+a^{2}}\right)-\int \frac{x^{2}}{\sqrt{x^{2}+a^{2}}} d x=x\left(\sqrt{x^{2}+a^{2}}\right)-\int \frac{\left(x^{2}+a^{2}\right)-a^{2}}{\sqrt{x^{2}+a^{2}}} d x \\
& =x\left(\sqrt{x^{2}+a^{2}}\right)-\int \sqrt{x^{2}+a^{2}} d x+a^{2} \int \frac{d x}{\sqrt{x^{2}+a^{2}}} \\
& =x \cdot\left(\sqrt{x^{2}+a^{2}}\right)-I+a^{2} \log \left|x+\sqrt{x^{2}+a^{2}}\right|+c . \\
\therefore \quad 2 I= & x\left(\sqrt{x^{2}+a^{2}}\right)+a^{2} \log \left|x+\sqrt{x^{2}+a^{2}}\right|+c \\
\text { or } \quad I= & \frac{x}{2}\left(\sqrt{x^{2}+a^{2}}\right)+\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}+a^{2}}\right|+C \quad\left[\text { taking } \frac{c}{2}=C\right] .
\end{aligned} \\
& \text { Hence, } \quad \int \sqrt{x^{2}+a^{2}} d x=\frac{x}{2}\left(\sqrt{x^{2}+a^{2}}\right)+\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}+a^{2}}\right|+C .
\end{aligned}
$$

---

## Solved Examples

### Example 1:

Evaluate:
(i) $\int \sqrt{9-x^{2}} d x$
(ii) $\int \sqrt{1-4 x^{2}} d x$
(iii) $\int \sqrt{16-9 x^{2}} d x$

#### Solution:

We know that $\int \sqrt{a^{2}-x^{2}} d x=\frac{x}{2} \sqrt{a^{2}-x^{2}}+\frac{a^{2}}{2} \sin ^{-1} \frac{x}{a}+C$.

$$
\begin{aligned}
& \therefore \text { (i) } \begin{aligned}
\int \sqrt{9-x^{2}} d x & =\int \sqrt{3^{2}-x^{2}} d x \\
& =\frac{x}{2} \sqrt{9-x^{2}}+\frac{9}{2} \sin ^{-1} \frac{x}{3}+C
\end{aligned} \\
& \text { (ii) } \begin{aligned}
\sqrt{1-4 x^{2}} d x & =2 \int \sqrt{\left(\frac{1}{4}-x^{2}\right)} d x=2 \int\left\{\sqrt{\left(\frac{1}{2}\right)^{2}-x^{2}}\right\} d x \\
& =2\left[\frac{x}{2} \sqrt{\frac{1}{4}-x^{2}}+\frac{1}{8} \sin ^{-1}\left(\frac{x}{\left(\frac{1}{2}\right)}\right)\right]+C \\
& =\frac{x}{2} \sqrt{1-4 x^{2}}+\frac{1}{4} \sin ^{-1}(2 x)+C
\end{aligned} \\
& \text { (iii) } \begin{aligned}
\int \sqrt{16-9 x^{2}} d x & =3 \int\left\{\sqrt{\left(\frac{16}{9}-x^{2}\right)}\right\} d x=3 \int\left\{\sqrt{\left(\frac{4}{3}\right)^{2}-x^{2}}\right\} d x \\
& =3\left[\frac{x}{2} \sqrt{\frac{16}{9}-x^{2}}+\frac{8}{9} \sin ^{-1} \frac{x}{\left(\frac{4}{3}\right)}\right]+C \\
& =\frac{x}{2} \sqrt{16-9 x^{2}}+\frac{8}{3} \sin ^{-1}\left(\frac{3 x}{4}\right)+C
\end{aligned}
\end{aligned}
$$

---

### Example 2:

Evaluate:
(i) $\int \sqrt{x^{2}-16} d x$
(ii) $\int \sqrt{4 x^{2}-5} d x$
(iii) $\int \sqrt{17 x^{2}-11} d x$

#### Solution:

We know that $\int \sqrt{x^{2}-a^{2}} d x=\frac{x}{2} \sqrt{x^{2}-a^{2}}-\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+C$.

$$
\therefore \quad \begin{aligned}
& \text { (i) } \begin{aligned}
\int \sqrt{x^{2}-16} d x & =\int \sqrt{x^{2}-4^{2}} d x \\
& =\frac{x}{2} \cdot \sqrt{x^{2}-4^{2}}-\frac{16}{2} \log \left|x+\sqrt{x^{2}-16}\right|+C \\
& =\frac{x}{2} \cdot \sqrt{x^{2}-16}-8 \log \left|x+\sqrt{x^{2}-16}\right|+C
\end{aligned} \\
& \text { (ii) } \begin{aligned}
\int \sqrt{4 x^{2}-5} d x & =2 \int \sqrt{x^{2}-\frac{5}{4}} d x=2 \cdot \int \sqrt{x^{2}-\left(\frac{\sqrt{5}}{2}\right)^{2}} d x \\
& =2 \cdot\left[\frac{x}{2} \sqrt{x^{2}-\frac{5}{4}}-\frac{5}{8} \log \left|x+\sqrt{x^{2}-\frac{5}{4}}\right|\right]+C \\
& =x \sqrt{x^{2}-\frac{5}{4}}-\frac{5}{4} \log \left|x+\sqrt{x^{2}-\frac{5}{4}}\right|+C
\end{aligned} \\
& \text { (iii) } \begin{aligned}
\int \sqrt{17 x^{2}-11} & d x \\
& =\sqrt{17} \cdot \int \sqrt{x^{2}-\frac{11}{17}} d x \\
& =\sqrt{17} \cdot\left\{\frac{x}{2} \sqrt{x^{2}-\frac{11}{17}}-\frac{11}{34} \log \left|x+\sqrt{x^{2}-\frac{11}{17}}\right|\right\}+C \\
& =\frac{x}{2} \sqrt{17 x^{2}-11}-\frac{11 \sqrt{17}}{34} \log \left|x+\sqrt{x^{2}-\frac{11}{17}}\right|+C
\end{aligned}
\end{aligned}
$$

---

### Example 3:

Evaluate $\int \sqrt{16 x^{2}+25} d x$.

#### Solution:

We know that $\int \sqrt{x^{2}+a^{2}} d x=\frac{x}{2} \sqrt{x^{2}+a^{2}}+\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}+a^{2}}\right|+C$.

$$
\begin{aligned}
\therefore \int \sqrt{16 x^{2}+25} d x & =4 \int\left\{\sqrt{x^{2}+\frac{25}{16}}\right\} d x=4 \int\left\{\sqrt{x^{2}+\left(\frac{5}{4}\right)^{2}}\right\} d x \\
& =4 \cdot\left\{\frac{x}{2} \sqrt{x^{2}+\frac{25}{16}}+\frac{25}{32} \log \left|x+\sqrt{x^{2}+\frac{25}{16}}\right|\right\}+C \\
& =\frac{x}{2} \cdot \sqrt{16 x^{2}+25}+\frac{25}{8} \log \left|x+\sqrt{x^{2}+\frac{25}{16}}\right|+C
\end{aligned}
$$

---

### Example 4:

Evaluate $\int \sqrt{\frac{16+(\log x)^{2}}{x}} d x$.
[CBSE 2005]

#### Solution:

Putting $\log x=t$ and $\frac{1}{x} d x=d t$, we get
$I=\int \sqrt{16+t^{2}} d t=\int \sqrt{4^{2}+t^{2}} d t$

$$
\begin{aligned}
& =\frac{t}{2} \sqrt{16+t^{2}}+\frac{16}{2} \log \left|t+\sqrt{16+t^{2}}\right|+C \\
& =\frac{1}{2} \log x \cdot \sqrt{16+(\log x)^{2}}+8 \log \left|\log x+\sqrt{16+(\log x)^{2}}\right|+C .
\end{aligned}
$$

---

### Example 5:

Evaluate $\int x \sqrt{x^{4}+1} d x$.
[CBSE 2003]

#### Solution:

Putting $x^{2}=t$ and $x d x=\frac{1}{2} d t$, we get

$$
\begin{aligned}
I & =\frac{1}{2} \int \sqrt{t^{2}+1} d t \\
& =\frac{1}{2} \cdot\left[\frac{t}{2} \sqrt{t^{2}+1}+\frac{1}{2} \log \left|t+\sqrt{t^{2}+1}\right|\right]+C \\
& =\frac{x^{2}}{4} \sqrt{x^{4}+1}+\frac{1}{4} \log \left|x^{2}+\sqrt{x^{4}+1}\right|+C
\end{aligned}
$$

---

### Example 6:

Evaluate $\int e^{x} \sqrt{e^{2 x}+4} d x$.

#### Solution:

Putting $e^{x}=t$ and $e^{x} d x=d t$, we get

$$
\begin{aligned}
I & =\int \sqrt{t^{2}+4} d x \\
& =\frac{t}{2} \cdot \sqrt{t^{2}+4}+\frac{4}{2} \log \left|t+\sqrt{t^{2}+4}\right|+C \\
& =\frac{1}{2} e^{x} \sqrt{e^{2 x}+4}+2 \log \left|e^{x}+\sqrt{e^{2 x}+4}\right|+C
\end{aligned}
$$

---

### Example 7:

Evaluate $\int \cos x \sqrt{4-\sin ^{2} x} d x$.

#### Solution:

Putting $\sin x=t$ and $\cos x d x=d t$, we get

$$
\begin{aligned}
I & =\int \sqrt{4-t^{2}} d t \\
& =\frac{t}{2} \sqrt{4-t^{2}}+\frac{4}{2} \sin ^{-1} \frac{t}{2}+C \\
& =\frac{1}{2} \sin x \sqrt{4-\sin ^{2} x}+2 \sin ^{-1}\left(\frac{1}{2} \sin x\right)+C
\end{aligned}
$$

---

## Integrals of the form $\int \sqrt{\left(a x^{2}+b x+c\right)} d x$

**Method:** Express $\left(a x^{2}+b x+c\right)$ as $a\left[(x+\alpha)^{2} \pm \beta^{2}\right]$ and obtain an integral which can be evaluated easily.

---

### Example 8:

Evaluate $\int \sqrt{x^{2}+3 x} d x$.

#### Solution:

We have

$$
\left(x^{2}+3 x\right)=\left\{x^{2}+3 x+\left(\frac{3}{2}\right)^{2}-\left(\frac{3}{2}\right)^{2}\right\}=\left(x+\frac{3}{2}\right)^{2}-\left(\frac{3}{2}\right)^{2} .
$$

$$
\begin{aligned}
\therefore I & =\int \sqrt{x^{2}+3 x} d x \\
& =\int \sqrt{\left(x+\frac{3}{2}\right)^{2}-\left(\frac{3}{2}\right)^{2}} d x=\int \sqrt{t^{2}-\left(\frac{3}{2}\right)^{2}} d t, \text { where }\left(x+\frac{3}{2}\right)=t \\
& =\frac{1}{2} t \sqrt{t^{2}-\frac{9}{4}}-\frac{9}{8} \log \left|t+\sqrt{t^{2}-\frac{9}{4}}\right|+C \\
& \left\{\text { using } \int \sqrt{x^{2}-a^{2}} d x=\frac{x}{2} \sqrt{x^{2}-a^{2}}-\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+C\right\} \\
& =\frac{1}{2}\left(x+\frac{3}{2}\right) \sqrt{x^{2}+3 x}-\frac{9}{8} \log \left|\left(x+\frac{3}{2}\right)+\sqrt{x^{2}+3 x}\right|+C
\end{aligned}
$$

---

### Example 9:

Evaluate $\int \sqrt{2 x^{2}+3 x+4} d x$.

#### Solution:

We have

$$
\begin{aligned}
& \left(2 x^{2}+3 x+4\right)=2\left(x^{2}+\frac{3}{2} x+2\right) \\
& \quad=2 \cdot\left\{\left(x^{2}+\frac{3}{2} x+\frac{9}{16}\right)+\left(2-\frac{9}{16}\right)\right\}=2 \cdot\left\{\left(x+\frac{3}{4}\right)^{2}+\left(\frac{\sqrt{23}}{4}\right)^{2}\right\}
\end{aligned}
$$

$$
\begin{aligned}
& \therefore \sqrt{2 x^{2}+3 x+4}=\sqrt{2} \cdot \sqrt{\left(x+\frac{3}{4}\right)^{2}+\left(\frac{\sqrt{23}}{4}\right)^{2}} \\
& \Rightarrow \int \sqrt{2 x^{2}+3 x+4} d x=\sqrt{2} \cdot \int \sqrt{\left(x+\frac{3}{4}\right)^{2}+\left(\frac{\sqrt{23}}{4}\right)^{2}} d x \\
& =\sqrt{2} \int \sqrt{t^{2}+\left(\frac{\sqrt{23}}{4}\right)^{2}} d t, \text { where }\left(x+\frac{3}{4}\right)=t \\
& =\sqrt{2} \cdot\left\{\frac{t}{2} \cdot \sqrt{t^{2}+\frac{23}{16}}+\frac{23}{32} \log \left|t+\sqrt{t^{2}+\frac{23}{16}}\right|\right\}+C \\
& \left[\text { using } \int \sqrt{t^{2}+a^{2}} d t=\frac{t}{2} \sqrt{t^{2}+a^{2}}+\frac{a^{2}}{2} \log \left|t+\sqrt{t^{2}+a^{2}}\right|+C\right] \\
& =\frac{\sqrt{2}}{2}\left(x+\frac{3}{4}\right) \sqrt{\left(x+\frac{3}{4}\right)^{2}+\frac{23}{16}} \\
& \quad+\frac{23 \sqrt{2}}{32} \log \left|\left(x+\frac{3}{4}\right)+\sqrt{x^{2}+\frac{3}{2} x+2}\right|+C \\
& =\frac{(4 x+3)}{4 \sqrt{2}} \cdot \sqrt{x^{2}+\frac{3}{2} x+2}+\frac{23 \sqrt{2}}{32} \log \left|\frac{(4 x+3)}{4}+\frac{\sqrt{2 x^{2}+3 x+4}}{\sqrt{2}}\right|+C \\
& =\frac{(4 x+3) \sqrt{2 x^{2}+3 x+4}}{8}+\frac{23 \sqrt{2}}{32} \log \left|\frac{(4 x+3)+2 \sqrt{2\left(x^{2}+3 x+4\right)}}{4}\right|+C
\end{aligned}
$$

---

### Example 10:

Evaluate $\int \sqrt{3-2 x-2 x^{2}} d x$.

#### Solution:

We have

$$
\begin{aligned}
\left(3-2 x-2 x^{2}\right) & =2 \cdot\left\{\frac{3}{2}-x-x^{2}\right\} \\
& =2 \cdot\left[\frac{3}{2}-\left(x^{2}+x+\frac{1}{4}\right)+\frac{1}{4}\right] \\
& =2 \cdot\left[\frac{7}{4}-\left(x+\frac{1}{2}\right)^{2}\right]=2 \cdot\left\{\left(\frac{\sqrt{7}}{2}\right)^{2}-\left(x+\frac{1}{2}\right)^{2}\right\}
\end{aligned}
$$

$$
\therefore \sqrt{3-2 x-2 x^{2}}=\sqrt{2} \cdot \sqrt{\left(\frac{\sqrt{7}}{2}\right)^{2}-\left(x+\frac{1}{2}\right)^{2}}
$$

$$
\begin{aligned}
& \Rightarrow \int \sqrt{3-2 x-2 x^{2}} d x=\sqrt{2} \cdot \int \sqrt{\left(\frac{\sqrt{7}}{2}\right)^{2}-\left(x+\frac{1}{2}\right)^{2}} d x \\
& =\sqrt{2} \cdot \int \sqrt{\left(\frac{\sqrt{7}}{2}\right)^{2}-t^{2}} d t, \text { where }\left(x+\frac{1}{2}\right)=t \text { and } d x=d t \\
& =\sqrt{2} \cdot\left\{\frac{t}{2} \cdot \sqrt{\frac{7}{4}-t^{2}}+\frac{7}{8} \sin ^{-1} \frac{t}{(\sqrt{7} / 2)}\right\}+C \\
& \quad\left[\because \int \sqrt{a^{2}-t^{2}} d t=\frac{t}{2} \sqrt{a^{2}-t^{2}}+\frac{a^{2}}{2} \cdot \sin ^{-1} \frac{t}{a}+C\right] \\
& =\sqrt{2} \cdot\left\{\frac{1}{2}\left(x+\frac{1}{2}\right) \sqrt{\frac{7}{4}-\left(x+\frac{1}{2}\right)^{2}}+\frac{7}{8} \sin ^{-1} \frac{\left(x+\frac{1}{2}\right)}{(\sqrt{7} / 2)}\right\}+C \\
& =\sqrt{2}\left\{\frac{1}{4}(2 x+1) \cdot \sqrt{\frac{3}{2}-x-x^{2}}+\frac{7}{8} \sin ^{-1}\left(\frac{2 x+1}{\sqrt{7}}\right)\right\}+C \\
& =\frac{1}{4}(2 x+1) \sqrt{3-2 x-2 x^{2}}+\frac{7}{4 \sqrt{2}} \sin ^{-1}\left(\frac{2 x+1}{\sqrt{7}}\right)+C
\end{aligned}
$$

---

## Integrals of the form $\int(p x+q) \sqrt{\left(a x^{2}+b x+c\right)} d x$

**Method:** Let $(p x+q)=A \cdot \frac{d}{d x}\left(a x^{2}+b x+c\right)+B$.
Find **A** and **B**.
Then, we get the integrand which is easily integrable.

---

### Example 11:

Evaluate $\int(x+3) \sqrt{3-4 x-x^{2}} d x$.
[CBSE 2005C]

#### Solution:

Let $(x+3)=A \cdot \frac{d}{d x}\left(3-4 x-x^{2}\right)+B \Leftrightarrow(x+3)=A(-4-2 x)+B$.

Comparing the coefficients of like powers of $x$, we get

$$
-2 A=1 \text { and }-4 A+B=3 \Leftrightarrow A=-\frac{1}{2} \text { and } B=1 .
$$

$$
\begin{gathered}
\therefore \quad(x+3)=-\frac{1}{2}(-4-2 x)+1 \\
\Rightarrow \quad I=\int\left\{-\frac{1}{2}(-4-2 x)+1\right\} \sqrt{3-4 x-x^{2}} d x \\
=-\frac{1}{2} \int(-4-2 x) \sqrt{3-4 x-x^{2}} d x+\int \sqrt{3-4 x-x^{2}} d x \\
=-\frac{1}{2} \int \sqrt{t} d t+\int \sqrt{7-\left(4 x+x^{2}+4\right)} d x, \text { where } 3-4 x-x^{2}=t \\
=\left(-\frac{1}{2} \times t^{3 / 2} \times \frac{2}{3}\right)+\int \sqrt{(\sqrt{7})^{2}-(x+2)^{2}} d x \\
=-\frac{1}{3}\left(3-4 x-x^{2}\right)^{3 / 2}+\frac{1}{2}(x+2) \sqrt{3-4 x-x^{2}}+\frac{7}{2} \sin ^{-1}\left(\frac{x+2}{\sqrt{7}}\right)+C \\
\quad\left[\because \int \sqrt{a^{2}-x^{2}} d x=\frac{x}{2} \sqrt{a^{2}-x^{2}}+\frac{a^{2}}{2} \cdot \sin ^{-1} \frac{x}{a}+C\right] .
\end{gathered}
$$

---

### Example 12:

Evaluate $\int(3 x-2) \sqrt{x^{2}+x+1} d x$.

#### Solution:

Let $(3 x-2)=A \cdot \frac{d}{d x}\left(x^{2}+x+1\right)+B$.
Then, $(3 x-2)=A(2 x+1)+B$.

Comparing the coefficients of like powers of $x$, we get
$2 A=3$ and $A+B=-2$. So, $A=\frac{3}{2}$ and $B=\frac{-7}{2}$.
$\therefore \quad(3 x-2)=\frac{3}{2}(2 x+1)-\frac{7}{2}$.

So, $\int(3 x-2) \sqrt{x^{2}+x+1} d x$

$$
\begin{aligned}
& =\int\left\{\frac{3}{2}(2 x+1)-\frac{7}{2}\right\} \sqrt{x^{2}+x+1} d x \\
& =\frac{3}{2} \int(2 x+1) \sqrt{x^{2}+x+1} d x-\frac{7}{2} \int \sqrt{x^{2}+x+1} d x \\
& =\frac{3}{2} \int \sqrt{t} d t-\frac{7}{2} \int \sqrt{\left(x^{2}+x+\frac{1}{4}\right)+\frac{3}{4}} d x
\end{aligned}
$$

where $x^{2}+x+1=t$ in the 1st integral
$=t^{3 / 2}-\frac{7}{2} \int \sqrt{\left\{\left(x+\frac{1}{2}\right)^{2}+\left(\frac{\sqrt{3}}{2}\right)^{2}\right\}} d x$
$=\left(x^{2}+x+1\right)^{3 / 2}-\frac{7}{2} \cdot \int \sqrt{u^{2}+\left(\frac{\sqrt{3}}{2}\right)^{2}} d u$, where $u=\left(x+\frac{1}{2}\right)$

$$
\begin{aligned}
& =\left(x^{2}+x+1\right)^{3 / 2}-\frac{7}{2}\left\{\frac{u}{2} \cdot \sqrt{u^{2}+\frac{3}{4}}+\frac{3}{8} \log \left|u+\sqrt{u^{2}+\frac{3}{4}}\right|\right\}+C \\
& \quad\left\{\because \int \sqrt{u^{2}+a^{2}} d u=\frac{u}{2} \sqrt{u^{2}+a^{2}}+\frac{a^{2}}{2} \log \left|u+\sqrt{u^{2}+a^{2}}\right|+C\right\} \\
& =\left(x^{2}+x+1\right)^{3 / 2}-\frac{7 u}{8} \sqrt{4 u^{2}+3}-\frac{21}{16} \log \left|u+\sqrt{u^{2}+\frac{3}{4}}\right|+C \\
& =\left(x^{2}+x+1\right)^{3 / 2}-\frac{7}{8}\left(x+\frac{1}{2}\right) \sqrt{4\left(x+\frac{1}{2}\right)^{2}+3} \\
& \quad-\frac{21}{16} \log \left|\left(x+\frac{1}{2}\right)+\sqrt{\left(x+\frac{1}{2}\right)^{2}+\frac{3}{4}}\right|+C \\
& =\left(x^{2}+x+1\right)^{3 / 2}-\frac{7(2 x+1)}{8} \sqrt{x^{2}+x+1} \\
& \quad-\frac{21}{16} \log \left|\frac{(2 x+1)}{2}+\sqrt{x^{2}+x+1}\right|+C
\end{aligned}
$$

---

### Example 13:

Evaluate $\int x \sqrt{x+x^{2}} d x$.
[CBSE 2005C]

#### Solution:

Let $x=A \cdot \frac{d}{d x}\left(x+x^{2}\right)+B$. Then,

$$
\begin{equation*}
x=A(1+2 x)+B \tag{i}
\end{equation*}
$$

Comparing the coefficients of various powers of $x$, we get

$$
\begin{aligned}
& \quad(2 A=1 \text { and } A+B=0) \Rightarrow\left(A=\frac{1}{2} \text { and } B=\frac{-1}{2}\right) \\
& \therefore \quad x=\frac{1}{2}(1+2 x)-\frac{1}{2}
\end{aligned}
$$

$$
\begin{aligned}
& \Rightarrow \int x \sqrt{x+x^{2}} d x \\
& \quad=\int\left\{\frac{1}{2}(1+2 x)-\frac{1}{2}\right\} \sqrt{x+x^{2}} d x \\
& \quad=\frac{1}{2} \int(1+2 x) \sqrt{x+x^{2}} d x-\frac{1}{2} \int \sqrt{x+x^{2}} d x \\
& \quad=\frac{1}{2} \int \sqrt{t} d t-\frac{1}{2} \int \sqrt{\left\{\left(x^{2}+x+\frac{1}{4}\right)-\frac{1}{4}\right\}} d x \\
& \quad \text { where }\left(x+x^{2}\right)=t \text { in the first integral } \\
& \quad=\frac{1}{2} \cdot \frac{t^{3 / 2}}{(3 / 2)}-\frac{1}{2} \int \sqrt{\left\{\left(x+\frac{1}{2}\right)^{2}-\left(\frac{1}{2}\right)^{2}\right\}} d x \\
& \quad=\frac{1}{3}\left(x+x^{2}\right)^{3 / 2}-\frac{1}{2} \cdot \int \sqrt{u^{2}-\left(\frac{1}{2}\right)^{2}} d u, \text { where }\left(x+\frac{1}{2}\right)=u
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{3}\left(x+x^{2}\right)^{3 / 2}-\frac{1}{2}\left\{\frac{u}{2} \cdot \sqrt{u^{2} \frac{-1}{4}}-\frac{1}{8} \log \left|u+\sqrt{u^{2}-\frac{1}{4}}\right|\right\}+C \\
& \quad\left\{\because \int \sqrt{x^{2}-a^{2}} d x=\frac{x}{2} \sqrt{x^{2}-a^{2}}-\frac{a^{2}}{2} \log \left|x+\sqrt{x^{2}-a^{2}}\right|+C\right\} \\
& =\frac{1}{3}\left(x+x^{2}\right)^{3 / 2}-\frac{1}{4}\left(x+\frac{1}{2}\right) \sqrt{\left(x+\frac{1}{2}\right)^{2}-\frac{1}{4}} \\
& \quad+\frac{1}{16} \log \left|\left(x+\frac{1}{2}\right) \sqrt{\left(x+\frac{1}{2}\right)^{2}-\frac{1}{4}}\right|+C \\
& =\frac{1}{3}\left(x+x^{2}\right)^{3 / 2}-\frac{1}{8}(2 x+1) \sqrt{x+x^{2}}+\frac{1}{16} \log \left|\frac{(2 x+1)}{2} \cdot \sqrt{x+x^{2}}\right|+C
\end{aligned}
$$

---