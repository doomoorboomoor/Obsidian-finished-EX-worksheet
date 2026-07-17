## Properties of Definite Integrals

**THEOREM 1:** $\int_{a}^{b} f(x) d x=\int_{a}^{b} f(t) d t$.

**PROOF:** Let $\quad \int f(x) d x=F(x)$. Then, $\int f(t) d t=F(t)$.

$\therefore \quad \int_{a}^{b} f(x) d x=[F(x)]_{a}^{b}=F(b)-F(a)$.

And, $\quad \int_{a}^{b} f(t) d t=[F(t)]_{a}^{b}=F(b)-F(a)$.

Hence, $\int_{a}^{b} f(x) d x=\int_{a}^{b} f(t) d t$.

---

**THEOREM 2:** $\int_{a}^{b} f(x) d x=-\int_{b}^{a} f(x) d x$.

**PROOF:** Let $\quad \int f(x) d x=F(x)$.

Then, $\int_{a}^{b} f(x) d x=[F(x)]_{a}^{b}=F(b)-F(a)$.

And, $-\int_{b}^{a} f(x) d x=-[F(x)]_{b}^{a}=-[F(a)-F(b)]=F(b)-F(a)$.

Hence, $\quad \int_{a}^{b} f(x) d x=-\int_{b}^{a} f(x) d x$.

---

**THEOREM 3:** $\int_{a}^{b} f(x) d x=\int_{a}^{c} f(x) d x+\int_{c}^{b} f(x) d x$, where $a<c<b$.

**PROOF:** Let $\int f(x) d x=F(x)$. Then, $\int_{a}^{b} f(x) d x=[F(x)]_{a}^{b}=F(b)-F(a)$.

$$
\begin{aligned}
\int_{a}^{c} f(x) d x+\int_{c}^{b} f(x) d x & =[F(x)]_{a}^{c}+[F(x)]_{c}^{b}=\{F(c)-F(a)\}+\{F(b)-F(c)\} \\
& =F(b)-F(a)=[F(x)]_{a}^{b}=\int_{a}^{b} f(x) d x .
\end{aligned}
$$

Hence, $\int_{a}^{c} f(x) d x+\int_{c}^{b} f(x) d x=\int_{a}^{b} f(x) d x$.

**REMARK:** If $a<c_{1}<c_{2}<\ldots<c_{n}<b$ then

$$
\int_{a}^{b} f(x) d x=\int_{a}^{c_{1}} f(x) d x+\int_{c_{1}}^{c_{2}} f(x) d x+\ldots+\int_{c_{n}}^{b} f(x) d x
$$

---

**THEOREM 4:** $\int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x$. *[CBSE 2002C, '05C, '06]*

**PROOF:** In the RHS integral, put $a-x=t$ so that $d x=-d t$.
Now, when $x=0$ we have $t=a$.
And, when $x=a$ we have $t=0$.

$\therefore \quad \int_{0}^{a} f(a-x) d x=-\int_{a}^{0} f(t) d t=\int_{0}^{a} f(t) d t=\int_{0}^{a} f(x) d x$.

Hence, $\int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x$.

---

**THEOREM 5:** $\int_{a}^{b} f(a+b-x) d x=\int_{a}^{b} f(x) d x$.

**PROOF:** Putting $a+b-x=t$, we get $d x=-d t$.

Now, $x=a \Rightarrow t=b$.
And, $x=b \Rightarrow t=a$.

$\therefore \quad \int_{a}^{b} f(a+b-x) d x=-\int_{b}^{a} f(t) d t=\int_{a}^{b} f(t) d t=\int_{a}^{b} f(x) d x$.

Hence, $\int_{a}^{b} f(a+b-x) d x=\int_{a}^{b} f(x) d x$.

---

**THEOREM 6:** $\int_{a}^{b}\{f(x)+g(x)\} d x=\int_{a}^{b} f(x) d x+\int_{a}^{b} g(x) d x$.

**PROOF:** Let $\int f(x) d x=F(x)$ and $\int g(x) d x=G(x)$.

Then, $\int[f(x)+g(x)] d x=\int f(x) d x+\int g(x) d x=F(x)+G(x)$.

$$
\begin{aligned}
\therefore \quad \int_{a}^{b}\{f(x)+g(x)\} d x & =[F(x)+G(x)]_{a}^{b} \\
& =[F(b)+G(b)]-[F(a)+G(a)] \\
& =[F(b)-F(a)]+[G(b)-G(a)] \\
& =\int_{a}^{b} f(x) d x+\int_{a}^{b} g(x) d x
\end{aligned}
$$

Hence, $\int_{a}^{b}\{f(x)+g(x)\} d x=\int_{a}^{b} f(x) d x+\int_{a}^{b} g(x) d x$.

---

**THEOREM 7:** $\int_{-a}^{a} f(x) d x=\left\{\begin{array}{l}0, \text { when } f(x) \text { is an odd function } \\ 2 \int_{0}^{a} f(x) d x, \text { when } f(x) \text { is an even function. }\end{array}\right.$ *[CBSE 2005C]*

**PROOF:** We have $\int_{-a}^{a} f(x) d x=\int_{-a}^{0} f(x) d x+\int_{0}^{a} f(x) d x$ ... (i)

In the first integral on the RHS of (i), put $x=-t$ so that $d x=-d t$.
When $x=-a$, we have $t=a$. And, when $x=0$, we have $t=0$.

$$
\begin{align*}
& \therefore \quad \int_{-a}^{0} f(x) d x=-\int_{a}^{0} f(-t) d t=\int_{0}^{a} f(-t) d t=\int_{0}^{a} f(-x) d x \\
& \text { Thus, } \quad \int_{-a}^{0} f(x) d x=\int_{0}^{a} f(-x) d x \tag{ii}
\end{align*}
$$

Using (ii) in (i), we have

$$
\begin{aligned}
\int_{-a}^{a} f(x) d x & =\int_{0}^{a} f(-x) d x+\int_{0}^{a} f(x) d x=\int_{0}^{a}[f(-x)+f(x)] d x \\
& =\left\{\begin{array}{l}
0, \text { when } f(x) \text { is odd } \\
2 \int_{0}^{a} f(x) d x, \text { when } f(x) \text { is even. }
\end{array}\right. \\
& \left.\qquad \begin{array}{r}
\because f(x) \text { is odd } \Rightarrow f(-x)=-f(x) \\
f(x) \text { is even } \Rightarrow f(-x)=f(x)
\end{array}\right]
\end{aligned}
$$

---

**THEOREM 8:** $\int_{0}^{2 a} f(x) d x=\left\{\begin{array}{l}0, \text { if } f(2 a-x)=-f(x) \\ 2 \int_{0}^{a} f(x) d x, \text { if } f(2 a-x)=f(x) .\end{array}\right.$

**PROOF:** We have $\int_{0}^{2 a} f(x) d x=\int_{0}^{a} f(x) d x+\int_{a}^{2 a} f(x) d x$ ... (i)

Now, in the second integral on the RHS of (i), put $x=2 a-t$ so that $d x=-d t$.
When $x=a$, we have $t=a$. When $x=2 a$, we have $t=0$.

$$
\begin{align*}
& \begin{aligned}
\therefore \quad \int_{a}^{2 a} f(x) d x & =-\int_{a}^{0} f(2 a-t) d t=\int_{0}^{a} f(2 a-t) d t \\
& =\int_{0}^{a} f(2 a-x) d x
\end{aligned} \\
& \text { Thus, } \int_{a}^{2 a} f(x) d x=\int_{0}^{a} f(2 a-x) d x \tag{ii}
\end{align*}
$$

Using (ii) in (i), we get

$$
\begin{aligned}
& \qquad \begin{aligned}
\int_{0}^{2 a} f(x) d x & =\int_{0}^{a} f(x) d x+\int_{0}^{a} f(2 a-x) d x \\
& =\int_{0}^{a}\{f(x)+f(2 a-x)\} d x \\
& =\left\{\begin{array}{l}
0, \text { when } f(2 a-x)=-f(x) \\
2 \int_{0}^{a} f(x) d x, \text { when } f(2 a-x)=f(x)
\end{array}\right. \\
\text { Hence, } \quad \int_{0}^{2 a} f(x) d x & =\left\{\begin{array}{c}
0, \text { when } f(2 a-x)=-f(x) \\
2 \int_{0}^{a} f(x) d x, \text { when } f(2 a-x)=f(x)
\end{array}\right.
\end{aligned}
\end{aligned}
$$

---

## Solved Examples

### Example 1:

Prove that $\int_{0}^{\pi / 2} \frac{\sin x}{(\sin x+\cos x)} d x=\frac{\pi}{4}$. *[CBSE 2002C, '07C]*

#### Solution:

Let $I=\int_{0}^{\pi / 2} \frac{\sin x}{(\sin x+\cos x)} d x$ ... (i)

Using the result $\int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x$ in (i), we get

$$
\begin{align*}
& \quad I=\int_{0}^{\pi / 2} \frac{\sin [(\pi / 2)-x]}{\sin [(\pi / 2)-x]+\cos [(\pi / 2)-x]} d x \\
& \text { or } \quad I=\int_{0}^{\pi / 2} \frac{\cos x}{(\cos x+\sin x)} d x=\int_{0}^{\pi / 2} \frac{\cos x}{(\sin x+\cos x)} d x \tag{ii}
\end{align*}
$$

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\int_{0}^{\pi / 2} \frac{\sin x}{(\sin x+\cos x)} d x+\int_{0}^{\pi / 2} \frac{\cos x}{(\sin x+\cos x)} d x \\
& =\int_{0}^{\pi / 2} \frac{(\sin x+\cos x)}{(\sin x+\cos x)} d x=\int_{0}^{\pi / 2} d x=[x]_{0}^{\pi / 2}=\frac{\pi}{2} \\
\therefore I & =\frac{\pi}{4}, \text { i.e., } \int_{0}^{\pi / 2} \frac{\sin x}{(\sin x+\cos x)} d x=\frac{\pi}{4}
\end{aligned}
$$

---

### Example 2:

Prove that $\int_{0}^{\pi / 2} \frac{\sqrt{\cos x}}{(\sqrt{\sin x}+\sqrt{\cos x})} d x=\frac{\pi}{4}$.

#### Solution:

Let $I=\int_{0}^{\pi / 2} \frac{\sqrt{\cos x}}{(\sqrt{\sin x}+\sqrt{\cos x})} d x$ ... (i)

Using the result $\int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x$ in (i), we get

$$
\begin{align*}
& I=\int_{0}^{\pi / 2} \frac{\sqrt{\cos [(\pi / 2)-x]}}{\sqrt{\sin [(\pi / 2)-x]}+\sqrt{\cos [(\pi / 2)-x]}} d x \\
\text { or } \quad I & =\int_{0}^{\pi / 2} \frac{\sqrt{\sin x}}{\sqrt{\cos x}+\sqrt{\sin x}} d x=\int_{0}^{\pi / 2} \frac{\sqrt{\sin x}}{\sqrt{\sin x}+\sqrt{\cos x}} d x \tag{ii}
\end{align*}
$$

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\int_{0}^{\pi / 2} \frac{\sqrt{\cos x}}{(\sqrt{\sin x}+\sqrt{\cos x})} d x+\int_{0}^{\pi / 2} \frac{\sqrt{\sin x}}{(\sqrt{\sin x}+\sqrt{\cos x})} d x \\
& =\int_{0}^{\pi / 2} \frac{(\sqrt{\sin x}+\sqrt{\cos x})}{(\sqrt{\sin x}+\sqrt{\cos x})} d x=\int_{0}^{\pi / 2} d x=[x]_{0}^{\pi / 2}=\frac{\pi}{2} \\
\therefore I & =\frac{\pi}{4}, \text { i.e., } \int_{0}^{\pi / 2} \frac{\sqrt{\cos x}}{(\sqrt{\sin x}+\sqrt{\cos x})} d x=\frac{\pi}{4}
\end{aligned}
$$

---

### Example 3:

Evaluate:
- (i) $\int_{0}^{1} x(1-x)^{n} d x$
- (ii) $\int_{0}^{1} x(1-x)^{3 / 2} d x$

#### Solution:

**(i)** We have $\quad \int_{0}^{1} x(1-x)^{n} d x=\int_{0}^{1}(1-x)[1-(1-x)]^{n} d x$

$$
\begin{aligned}
0 & {\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right] } \\
= & \int_{0}^{1}(1-x) x^{n} d x=\int_{0}^{1} x^{n} d x-\int_{0}^{1} x^{n+1} d x
\end{aligned}
$$

$$
\begin{aligned}
& =\left[\frac{x^{n+1}}{(n+1)}\right]_{0}^{1}-\left[\frac{x^{n+2}}{n+2}\right]_{0}^{1}=\left(\frac{1}{n+1}-\frac{1}{n+2}\right) \\
& =\frac{1}{(n+1)(n+2)}
\end{aligned}
$$

**(ii)** We have $\int_{0}^{1} x(1-x)^{3 / 2} d x=\int_{0}^{1}(1-x)[1-(1-x)]^{3 / 2} d x$

$$
\begin{aligned}
& {\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right] } \\
= & \int_{0}^{1}(1-x) x^{3 / 2} d x=\int_{0}^{1} x^{3 / 2} d x-\int_{0}^{1} x^{5 / 2} d x \\
= & {\left[\frac{2}{5} x^{5 / 2}\right]_{0}^{1}-\left[\frac{2}{7} x^{7 / 2}\right]_{0}^{1}=\left(\frac{2}{5}-\frac{2}{7}\right)=\frac{4}{35} }
\end{aligned}
$$

---

### Example 4:

Show that $\quad \int_{0}^{\pi / 2} \log (\tan x) d x=0$.

#### Solution:

Let $I=\int_{0}^{\pi / 2} \log (\tan x) d x$ ... (i)

Then, $I=\int_{0}^{\pi / 2} \log \left[\tan \left(\frac{\pi}{2}-x\right)\right] d x \quad\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right]$

or $\quad I=\int_{0}^{\pi / 2} \log (\cot x) d x=\int_{0}^{\pi / 2} \log \left(\frac{1}{\tan x}\right) d x=-\int_{0}^{\pi / 2} \log \tan x d x=-I$.

$\therefore \quad I=-I$ or $2 I=0$ or $I=0$.

Hence, $\quad \int_{0}^{\pi / 2} \log (\tan x) d x=0$.

---

### Example 5:

Prove that $\int_{0}^{\pi / 4} \log (1+\tan x) d x=\frac{\pi}{8}(\log 2)$. *[CBSE 2007,'11,'13C]*

#### Solution:

Let $I=\int_{0}^{\pi / 4} \log (1+\tan x) d x$ ... (i)

Then, $\quad I=\int_{0}^{\pi / 4} \log \left[1+\tan \left(\frac{\pi}{4}-x\right)\right] d x \quad\left[\because \quad \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right]$

or

$$
I=\int_{0}^{\pi / 4} \log \left[1+\frac{1-\tan x}{1+\tan x}\right] d x
$$

or $\quad I=\int_{0}^{\pi / 4} \log \left(\frac{2}{1+\tan x}\right) d x$

or

$$
I=\int_{0}^{\pi / 4}[\log 2-\log (1+\tan x)] d x
$$

or

$$
\begin{equation*}
I=(\log 2) \cdot \int_{0}^{\pi / 4} d x-\int_{0}^{\pi / 4} \log (1+\tan x) d x \tag{ii}
\end{equation*}
$$

Adding (i) and (ii), we get

$2 I=(\log 2) \int_{0}^{\pi / 4} d x=(\log 2) \cdot[x]_{0}^{\pi / 4}=\frac{\pi}{4}(\log 2)$.

$\therefore \quad I=\frac{\pi}{8}(\log 2)$, i.e., $\int_{0}^{\pi / 4} \log (1+\tan x) d x=\frac{\pi}{8}(\log 2)$.

---

### Example 6:

Prove that $\int_{0}^{\pi / 2} \log (\sin x) d x=\int_{0}^{\pi / 2} \log (\cos x) d x=-\frac{\pi}{2}(\log 2)$. *[CBSE 2004, '07C, '08]*

#### Solution:

Let $I=\int_{0}^{\pi / 2} \log (\sin x) d x$ ... (i)

Then, $I=\int_{0}^{\pi / 2} \log \left[\sin \left(\frac{\pi}{2}-x\right)\right] d x \quad\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right]$

or $\quad I=\int_{0}^{\pi / 2} \log (\cos x) d x$ ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\int_{0}^{\pi / 2}[\log (\sin x)+\log (\cos x)] d x \\
& =\int_{0}^{\pi / 2} \log (\sin x \cos x) d x=\int_{0}^{\pi / 2} \log \left(\frac{\sin 2 x}{2}\right) d x \\
& =\int_{0}^{\pi / 2} \log (\sin 2 x) d x-\int_{0}^{\pi / 2}(\log 2) d x=\frac{1}{2} \int_{0}^{\pi} \log \sin t d t-(\log 2) \cdot \int_{0}^{\pi / 2} d x \\
& =\frac{1}{2} \int_{0}^{\pi} \log \sin t d t-(\log 2) \cdot[x]_{0}^{\pi / 2} \\
& =\left(\frac{1}{2} \times 2\right) \cdot \int_{0}^{\pi / 2} \log \sin t d t-\frac{\pi}{2}(\log 2) \\
& =\int_{0}^{\pi / 2} \log (\sin x) d x-\frac{\pi}{2}(\log 2)
\end{aligned}
$$

$\therefore \quad 2 I=I-\frac{\pi}{2}(\log 2)$ or $I=-\frac{\pi}{2}(\log 2)$.

$\therefore \quad \int_{0}^{\pi / 2} \log (\sin x) d x=\int_{0}^{\pi / 2} \log (\cos x) d x=-\frac{\pi}{2}(\log 2)$.

---

### Example 7:

Prove that:
- (a) $\int_{0}^{\pi / 2} \sin 2 x \log (\tan x)$
- (b) $\int_{0}^{1} \log \left(\frac{1}{x}-1\right) d x=0$ *[CBSE 2003C, '06C]*

#### Solution:

**(a)** Let $I=\int_{0}^{\pi / 2} \sin 2 x \log (\tan x) d x$ ... (i)

Then, $I=\int_{0}^{\pi / 2} \sin 2\left(\frac{\pi}{2}-x\right) \log \tan \left(\frac{\pi}{2}-x\right) d x$

$$
\begin{equation*}
\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right] \tag{ii}
\end{equation*}
$$

or $\quad I=\int_{0}^{\pi / 2} \sin 2 x \log (\cot x) d x$

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\int_{0}^{\pi / 2}[\sin 2 x \log (\tan x)+\sin 2 x \log (\cot x)] d x \\
& =\int_{0}^{\pi / 2} \sin 2 x\{\log (\tan x)+\log (\cot x)\} d x \\
& =\int_{0}^{\pi / 2} \sin 2 x \cdot \log (\tan x \cdot \cot x) d x=\int_{0}^{\pi / 2} \sin 2 x \cdot \log (1) d x=0 \\
\therefore I & =0 \Rightarrow \int_{0}^{\pi / 2} \sin 2 x \log (\tan x) d x=0 .
\end{aligned}
$$

**(b)** Put $x=\cos ^{2} t$ so that $d x=-\sin 2 t d t$.

When $\quad x=0$, we have $\cos t=0$ or $t=\frac{\pi}{2}$.
When $x=1$, we have $\cos t=1$ or $t=0$.

$$
\begin{aligned}
\therefore \quad \int_{0}^{1} \log \left(\frac{1}{x}-1\right) d x & =-\int_{\pi / 2}^{0} \log \left(\tan ^{2} t\right) \cdot \sin 2 t d t \\
& =2 \int_{0}^{\pi / 2} \sin 2 t \cdot \log (\tan t) d t=0 \quad[\text { from (a) }]
\end{aligned}
$$

---

### Example 8:

Prove that:
- (a) $\int_{0}^{\pi / 2} \frac{\sin ^{2} x}{(\sin x+\cos x)} d x=\frac{1}{\sqrt{2}} \log (\sqrt{2}+1)$ *[CBSE 2012, '14C]*
- (b) $\int_{0}^{\pi / 2} \frac{\sin ^{2} x}{(1+\sin x \cos x)} d x=\frac{\pi}{3 \sqrt{3}}$

#### Solution:

**(a)** Let $I=\int_{0}^{\pi / 2} \frac{\sin ^{2} x}{(\sin x+\cos x)} d x$ ... (i)

$$
\begin{align*}
& \text { Then, } \quad I=\int_{0}^{\pi / 2} \frac{\sin ^{2}\left(\frac{\pi}{2}-x\right)}{\left[\sin \left(\frac{\pi}{2}-x\right)+\cos \left(\frac{\pi}{2}-x\right)\right]} d x  \\
& \text { or } \quad I=\int_{0}^{\pi / 2} \frac{\cos ^{2} x}{(\cos x+\sin x)} d x=\int_{0}^{\pi / 2} \frac{\cos ^{2} x}{(\sin x+\cos x)} d x \tag{ii}
\end{align*}
$$

Adding (i) and (ii), we get

$$
\begin{aligned}
& 2 I=\int_{0}^{\pi / 2} \frac{\left(\sin ^{2} x+\cos ^{2} x\right)}{(\sin x+\cos x)} d x=\int_{0}^{\pi / 2} \frac{d x}{(\sin x+\cos x)} \\
&=\int_{0}^{\pi / 2} \frac{d x}{\left[\frac{2 \tan (x / 2)}{1+\tan ^{2}(x / 2)}+\frac{1-\tan ^{2}(x / 2)}{1+\tan ^{2}(x / 2)}\right]} \\
&=\int_{0}^{\pi / 2} \frac{\sec ^{2}(x / 2)}{\left[1-\tan ^{2}(x / 2)+2 \tan (x / 2)\right]} d x \\
&=2 \int_{0}^{1} \frac{d t}{\left(1-t^{2}+2 t\right)}, \quad \text { where } \tan \frac{x}{2}=t \\
&=2 \int_{0}^{1} \frac{d t}{2-(t-1)^{2}}=2 \int_{0}^{1} \frac{d t}{(\sqrt{2})^{2}-(t-1)^{2}} \\
&=2 \cdot \frac{1}{2 \sqrt{2}}\left\{\log \left\lvert\, \frac{\sqrt{2}+t-1}{\sqrt{2}-t+1}\right.\right\}_{0}^{1}=\frac{1}{\sqrt{2}}\left[0-\log \left(\frac{\sqrt{2}-1}{\sqrt{2}+1}\right)\right] \\
&=\frac{1}{\sqrt{2}} \log \left(\frac{\sqrt{2}+1}{\sqrt{2}-1}\right)=\frac{1}{\sqrt{2}} \log \frac{(\sqrt{2}+1)}{(\sqrt{2}-1)} \times \frac{(\sqrt{2}+1)}{(\sqrt{2}+1)} \\
&=\frac{1}{\sqrt{2}} \log (\sqrt{2}+1)^{2}=\frac{1}{\sqrt{2}} \times 2 \log (\sqrt{2}+1) \\
&=\sqrt{2} \log (\sqrt{2}+1) \\
& \therefore I=\frac{1}{2} \sqrt{2} \log (\sqrt{2}+1)=\frac{1}{\sqrt{2}} \log (\sqrt{2}+1)
\end{aligned}
$$

**(b)** Let $I=\int_{0}^{\pi / 2} \frac{\sin ^{2} x}{(1+\sin x \cos x)} d x$ ... (i)

Then, $I=\int_{0}^{\pi / 2} \frac{\sin ^{2}[(\pi / 2)-x]}{1+\sin [(\pi / 2)-x] \cos [(\pi / 2)-x]} d x$

or $\quad I=\int_{0}^{\pi / 2} \frac{\cos ^{2} x}{(1+\sin x \cos x)} d x$ ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\int_{0}^{\pi / 2} \frac{\left(\sin ^{2} x+\cos ^{2} x\right)}{(1+\sin x \cos x)} d x=\int_{0}^{\pi / 2} \frac{d x}{(1+\sin x \cos x)} \\
& {\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right] } \\
& =\int_{0}^{\pi / 2} \frac{\sec ^{2} x}{\left(\sec ^{2} x+\tan x\right)} d x
\end{aligned}
$$

[dividing num. and denom. by $\cos ^{2} x$ ]

$$
\begin{aligned}
& =\int_{0}^{\pi / 2} \frac{\sec ^{2} x}{\left(1+\tan ^{2} x+\tan x\right)} d x=\int_{0}^{\infty} \frac{d t}{\left(t^{2}+t+1\right)}, \text { where } \tan x=t \\
& \quad\left[x=0 \Rightarrow t=0 \text { and } x=\frac{\pi}{2} \Rightarrow t=\infty\right] \\
& =\int_{0}^{\infty} \frac{d t}{\left(t+\frac{1}{2}\right)^{2}+\left(\frac{\sqrt{3}}{2}\right)^{2}}=\left[\frac{2}{\sqrt{3}} \tan ^{-1}\left(\frac{2 t+1}{\sqrt{3}}\right)\right]_{0}^{\infty} \\
& =\frac{2}{\sqrt{3}}\left[\tan ^{-1}(\infty)-\tan ^{-1}\left(\frac{1}{\sqrt{3}}\right)\right]=\frac{2}{\sqrt{3}} \cdot\left(\frac{\pi}{2}-\frac{\pi}{6}\right)=\frac{2 \pi}{3 \sqrt{3}} .
\end{aligned}
$$

Hence, $I=\frac{\pi}{3 \sqrt{3}}$.

---

### Example 9:

Prove that $\int_{0}^{\pi} \frac{x \tan x}{(\sec x+\tan x)} d x=\pi\left(\frac{\pi}{2}-1\right)$. *[CBSE 2008, '10]*

#### Solution:

Let $I=\int_{0}^{\pi} \frac{x \tan x}{(\sec x+\tan x)} d x$ ... (i)

Then, $I=\int_{0}^{\pi} \frac{(\pi-x) \tan (\pi-x)}{[\sec (\pi-x)+\tan (\pi-x)]} d x \quad\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right]$

or $\quad I=\int_{0}^{\pi} \frac{(\pi-x) \tan x}{(\sec x+\tan x)} d x$ ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\pi \int_{0}^{\pi} \frac{\tan x}{(\sec x+\tan x)} d x=\pi \int_{0}^{\pi} \frac{\tan x(\sec x-\tan x)}{\left(\sec ^{2} x-\tan ^{2} x\right)} d x \\
& =\pi \cdot\left[\int_{0}^{\pi} \sec x \tan x d x-\int_{0}^{\pi} \tan ^{2} x d x\right] \\
& =\pi \cdot\left\{[\sec x]_{0}^{\pi}-\int_{0}^{\pi}\left(\sec ^{2} x-1\right) d x\right\} \\
& =\pi \cdot\left\{-2-[\tan x]_{0}^{\pi}+[x]_{0}^{\pi}\right\}=\pi(\pi-2) \\
\therefore \quad I & =\pi\left(\frac{\pi}{2}-1\right) \text { i.e., } \int_{0}^{\pi} \frac{x \tan x}{\sec x+\tan x} d x=\pi\left(\frac{\pi}{2}-1\right)
\end{aligned}
$$

---

### Example 10:

Evaluate $\int_{0}^{\pi} \frac{x}{(1+\sin x)} d x$. *[CBSE 2010, '11, '12C]*

#### Solution:

Let $I=\int_{0}^{\pi} \frac{x}{(1+\sin x)} d x$ ... (i)

Then, $I=\int_{0}^{\pi} \frac{(\pi-x)}{1+\sin (\pi-x)} d x=\int_{0}^{\pi} \frac{(\pi-x)}{(1+\sin x)} d x$ ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
& \quad 2 I=\pi \int_{0}^{\pi} \frac{d x}{(1+\sin x)}=\pi \cdot \int_{0}^{\pi} \frac{1}{(1+\sin x)} \times \frac{(1-\sin x)}{(1-\sin x)} d x \\
& \text { or } \quad 2 I=\pi \int_{0}^{\pi}\left(\frac{1-\sin x}{\cos ^{2} x}\right) d x=\pi \cdot\left[\int_{0}^{\pi} \sec ^{2} x d x-\int_{0}^{\pi} \sec x \tan x d x\right] \\
& \quad=\pi \cdot\left\{[\tan x]_{0}^{\pi}-[\sec x]_{0}^{\pi}\right\}=2 \pi \\
& \therefore \quad I=\pi, \text { i.e., } \int_{0}^{\pi} \frac{x}{(1+\sin x)} d x=\pi
\end{aligned}
$$

---

### Example 11:

Evaluate $\int_{0}^{\pi} \frac{x \sin x}{\left(1+\cos ^{2} x\right)} d x$. *[CBSE 2009C, '11C, '12, '14]*

#### Solution:

Let $I=\int_{0}^{\pi} \frac{x \sin x}{\left(1+\cos ^{2} x\right)} d x$ ... (i)

Then, $I=\int_{0}^{\pi} \frac{(\pi-x) \sin (\pi-x)}{1+\cos ^{2}(\pi-x)} d x$

or $\quad I=\int_{0}^{\pi} \frac{(\pi-x) \sin x}{\left(1+\cos ^{2} x\right)} d x$ ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\pi \int_{0}^{\pi} \frac{\sin x}{\left(1+\cos ^{2} x\right)} d x=-\pi \int_{1}^{-1} \frac{d t}{\left(1+t^{2}\right)}, \text { where } \cos x=t \\
& =\pi \int_{-1}^{1} \frac{d t}{\left(1+t^{2}\right)}=\pi\left[\tan ^{-1} t\right]_{-1}^{1} \\
& =\pi\left[\tan ^{-1} 1-\tan ^{-1}(-1)\right]=\pi\left[\frac{\pi}{4}-\left(-\frac{\pi}{4}\right)\right]=\frac{\pi^{2}}{2} . \\
\therefore \quad I= & \frac{\pi^{2}}{4} .
\end{aligned}
$$

---

### Example 12:

Evaluate $\int_{0}^{\pi / 2} \frac{x}{(\sin x+\cos x)} d x$. *[CBSE 2003C, '08]*

#### Solution:

Let $I=\int_{0}^{\pi / 2} \frac{x}{(\sin x+\cos x)} d x$ ... (i)

Then, $I=\int_{0}^{\pi / 2} \frac{\left(\frac{\pi}{2}-x\right)}{\sin [(\pi / 2)-x]+\cos [(\pi / 2)-x]} d x$

or $\quad I=\int_{0}^{\pi / 2} \frac{\left(\frac{\pi}{2}-x\right)}{(\cos x+\sin x)} d x=\int_{0}^{\pi / 2} \frac{\left(\frac{\pi}{2}-x\right)}{(\sin x+\cos x)} d x$ ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\frac{\pi}{2} \int_{0}^{\pi / 2} \frac{d x}{(\sin x+\cos x)} \\
\therefore \quad I & =\frac{\pi}{4} \int_{0}^{\pi / 2} \frac{d x}{(\sin x+\cos x)}=\frac{\pi}{4} \int_{0}^{\pi / 2} \frac{d x}{\left[\frac{2 \tan (x / 2)}{1+\tan ^{2}(x / 2)}+\frac{1-\tan ^{2}(x / 2)}{1+\tan ^{2}(x / 2)}\right]} \\
& =\frac{\pi}{4} \int_{0}^{\pi / 2} \frac{\sec ^{2}(x / 2)}{1-\tan ^{2}(x / 2)+2 \tan (x / 2)} d x \\
& =\frac{\pi}{4} \int_{0}^{1} \frac{2 d t}{\left(1-t^{2}+2 t\right)}, \quad \text { where } t=\tan \frac{x}{2} \\
& =\frac{\pi}{2} \int_{0}^{1} \frac{d t}{\left[(\sqrt{2})^{2}-(t-1)^{2}\right]} d t \\
& =\frac{\pi}{2} \cdot \frac{1}{2 \sqrt{2}} \log \left|\frac{\sqrt{2}+(t-1)}{\sqrt{2}-(t-1)}\right|_{0}^{1}=\frac{\pi}{4 \sqrt{2}} \log \left|\frac{\sqrt{2}+1}{\sqrt{2}-1}\right| .
\end{aligned}
$$

---

### Example 13:

Prove that $\int_{0}^{\pi / 2}(2 \log \sin x-\log \sin 2 x) d x=-\frac{\pi}{2}(\log 2)$. *[CBSE 2009]*

#### Solution:

Let $I=\int_{0}^{\pi / 2}(2 \log \sin x-\log \sin 2 x) d x$. ... (i)

Then, $I=\int_{0}^{\pi / 2}\left[2 \log \sin \left(\frac{\pi}{2}-x\right)-\log \sin 2\left(\frac{\pi}{2}-x\right)\right] d x$

or $\quad I=\int_{0}^{\pi / 2}(2 \log \cos x-\log \sin 2 x) d x$ ... (ii)

Adding (i) and (ii), we get

$$
\text { or } \quad \begin{aligned}
2 I & =\int_{0}^{\pi / 2}[2(\log \sin x+\log \cos x)-2 \log \sin 2 x] d x \\
& =2 \int_{0}^{\pi / 2}[\log (\sin x \cos x)-\log \sin 2 x] d x \\
& =2 \int_{0}^{\pi / 2}\left[\log \left(\frac{\sin 2 x}{2}\right)-\log \sin 2 x\right] d x \\
& =2 \int_{0}^{\pi / 2}(\log \sin 2 x-\log 2-\log \sin 2 x) d x \\
& =-2 \log 2 \cdot \int_{0}^{\pi / 2} d x=(-2 \log 2) \cdot[x]_{0}^{\pi / 2}=-\pi(\log 2)
\end{aligned}
$$

$\therefore \quad I=-\frac{\pi}{2}(\log 2)$.

---

### Example 14:

Evaluate $\int_{0}^{\pi} \frac{x}{\left(a^{2} \cos ^{2} x+b^{2} \sin ^{2} x\right)} d x$. *[CBSE 2003C, '09]*

#### Solution:

Let $I=\int_{0}^{\pi} \frac{x}{\left(a^{2} \cos ^{2} x+b^{2} \sin ^{2} x\right)} d x$ ... (i)

Then, $I=\int_{0}^{\pi} \frac{(\pi-x)}{\left(a^{2} \cos ^{2}(\pi-x)+b^{2} \sin ^{2}(\pi-x)\right]} d x$

or $\quad I=\int_{0}^{\pi} \frac{(\pi-x)}{\left(a^{2} \cos ^{2} x+b^{2} \sin ^{2} x\right)} d x$. ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\int_{0}^{\pi} \frac{(x+\pi-x)}{\left(a^{2} \cos ^{2} x+b^{2} \sin ^{2} x\right)} d x=\pi \int_{0}^{\pi} \frac{d x}{\left(a^{2} \cos ^{2} x+b^{2} \sin ^{2} x\right)} \\
& =2 \pi \int_{0}^{\pi / 2} \frac{d x}{\left(a^{2} \cos ^{2} x+b^{2} \sin ^{2} x\right)}=2 \pi \int_{0}^{\pi / 2} \frac{\sec ^{2} x}{\left(a^{2}+b^{2} \tan ^{2} x\right)} d x
\end{aligned}
$$

[dividing num. and denom. by $\cos ^{2} x$ ]

$$
\begin{aligned}
= & 2 \pi \int_{0}^{\infty} \frac{d t}{\left(a^{2}+b^{2} t^{2}\right)}, \text { where } \tan x=t \\
& =\frac{2 \pi}{b^{2}} \int_{0}^{\infty} \frac{d t}{\left(\frac{a^{2}}{b^{2}}+t^{2}\right)}=\left[\frac{2 \pi}{b^{2}} \cdot \frac{b}{a} \tan ^{-1}\left(\frac{b t}{a}\right)\right]_{0}^{\infty} \\
& =\frac{2 \pi}{a b}\left[\tan ^{-1}(\infty)-\tan ^{-1}(0)\right]=\frac{2 \pi}{a b}\left(\frac{\pi}{2}-0\right)=\left(\frac{2 \pi}{a b} \times \frac{\pi}{2}\right)=\frac{\pi^{2}}{a b} . \\
\therefore \quad I= & \frac{\pi^{2}}{2 a b} \Rightarrow \int_{0}^{\pi} \frac{x}{\left(a^{2} \cos ^{2} x+b^{2} \sin ^{2} x\right)} d x=\frac{\pi^{2}}{2 a b} .
\end{aligned}
$$

---

### Example 15:

Prove that $\int_{0}^{\pi} x \sin ^{3} x d x=\frac{2 \pi}{3}$.

#### Solution:

Let $I=\int_{0}^{\pi} x \sin ^{3} x d x$ ... (i)

Then, $\quad I=\int_{0}^{\pi}(\pi-x) \sin ^{3}(\pi-x) d x$

or $\quad I=\int_{0}^{\pi}(\pi-x) \sin ^{3} x d x$ ... (ii)

Adding (i) and (ii), we get

$$
\begin{aligned}
2 I & =\int_{0}^{\pi} \pi \sin ^{3} x d x=\pi \int_{0}^{\pi} \sin ^{2} x \cdot \sin x d x \\
& =\pi \int_{0}^{\pi}\left(1-\cos ^{2} x\right) \sin x d x \\
& =-\pi \int_{1}^{-1}\left(1-t^{2}\right) d t, \text { where } \cos x=t \\
& \quad[x=0 \Rightarrow t=1 \text { and } x=\pi \Rightarrow t=-1] \\
& =\pi \int_{-1}^{1}\left(1-t^{2}\right) d t=\pi\left[t-\frac{t^{3}}{3}\right]_{-1}^{1}=\frac{4 \pi}{3}
\end{aligned}
$$

Hence, $I=\frac{2 \pi}{3} \Rightarrow \int_{0}^{\pi} x \sin ^{3} x d x=\frac{2 \pi}{3}$.

---

### Example 16:

Evaluate $\int_{0}^{1} \cot ^{-1}\left\{1-x+x^{2}\right\} d x$. *[CBSE 2008]*

#### Solution:

We have

$$
I=\int_{0}^{1} \cot ^{-1}\left\{1-x+x^{2}\right\} d x
$$

$$
\begin{aligned}
& =\int_{0}^{1} \tan ^{-1}\left(\frac{1}{1-x+x^{2}}\right) d x=\int_{0}^{1} \tan ^{-1}\left\{\frac{x+(1-x)}{1-x(1-x)}\right\} d x \\
& =\int_{0}^{1}\left\{\tan ^{-1} x+\tan ^{-1}(1-x)\right\} d x \\
& =\int_{0}^{1} \tan ^{-1} x d x+\int_{0}^{1} \tan ^{-1}(1-x) d x \\
& =\int_{0}^{1} \tan ^{-1} x d x+\int_{0}^{1} \tan ^{-1}\{1-(1-x)\} d x \quad\left[\because \int_{0}^{a} f(x) d x=\int_{0}^{a} f(a-x) d x\right] \\
& =\int_{0}^{1} \tan ^{-1} x d x+\int_{0}^{1} \tan ^{-1} x d x=2 \int_{0}^{1} \tan ^{-1} x d x \\
& =2 \int_{0}^{1}\left(\tan ^{-1} x \cdot 1\right) d x \\
& =2\left[\left(\tan ^{-1} x\right) x-\int \frac{1}{\left(1+x^{2}\right)} \cdot x d x\right]_{0}^{1} \\
& =2\left[\left(\tan ^{-1} x\right) \cdot x\right]_{0}^{1}-2 \int_{0}^{1} \frac{x}{\left(1+x^{2}\right)} d x \\
& =2\left\{\left(\tan ^{-1} 1\right) \cdot 1-0\right\}-\left[\log \left(1+x^{2}\right)\right]_{0}^{1} \\
& =\left(2 \times \frac{\pi}{4}\right)-(\log 2-\log 1)=\left(\frac{\pi}{2}-\log 2\right)
\end{aligned}
$$

---

### Example 17:

Evaluate $\int_{\pi / 5}^{3 \pi / 10} \frac{\sin x}{(\sin x+\cos x)} d x$. *[CBSE 2009]*

#### Solution:

Let $I=\int_{\pi / 5}^{3 \pi / 10} \frac{\sin x}{(\sin x+\cos x)} d x$ ... (i)

Here, $a=\frac{\pi}{5}$ and $b=\frac{3 \pi}{10} \Rightarrow(a+b)=\left(\frac{\pi}{5}+\frac{3 \pi}{10}\right)=\frac{\pi}{2}$.

Using $\int_{a}^{b} f(x) d x=\int_{a}^{b} f(a+b-x) d x$, we have

$$
\begin{align*}
& I=\int_{\pi / 5}^{3 \pi / 10} \frac{\sin \left(\frac{\pi}{2}-x\right)}{\sin \left(\frac{\pi}{2}-x\right)+\cos \left(\frac{\pi}{2}-x\right)} d x \\
\Rightarrow \quad I & =\int_{\pi / 5}^{3 \pi / 10} \frac{\cos x}{(\cos x+\sin x)} d x \tag{ii}
\end{align*}
$$

Adding (i) and (ii), we get

$$
2 I=\int_{\pi / 5}^{3 \pi / 10} d x=[x]_{\pi / 5}^{3 \pi / 10}=\left(\frac{3 \pi}{10}-\frac{\pi}{5}\right)=\frac{\pi}{10}
$$

$\Rightarrow \quad I=\frac{\pi}{20}$.

---

## Integrals of the form $\int_{-a}^{a} f(x) d x$, where $f(x)$ is even or odd

We know that
- (i) $f(x)$ is odd, if $f(-x)=-f(x)$;
- (ii) $f(x)$ is even, if $f(-x)=f(x)$;
- (iii) $\int_{-a}^{a} f(x) d x=0$, when $f(x)$ is odd;
- (iv) $\int_{-a}^{a} f(x) d x=2 \int_{0}^{a} f(x) d x$, when $f(x)$ is even.

---

### Example 18:

Show that $\int_{-\pi / 2}^{\pi / 2} \sin ^{7} x d x=0$.

#### Solution:

Let $f(x)=\sin ^{7} x$. Then,
$f(-x)=[\sin (-x)]^{7}=(-\sin x)^{7}=-\sin ^{7} x=-f(x)$.

$\therefore f(x)$ is an odd function of $x$.

But, $\int_{-a}^{a} f(x) d x=0$, when $f(x)$ is odd.

$\therefore \quad \int_{-\pi / 2}^{\pi / 2} \sin ^{7} x d x=0$.

---

### Example 19:

Evaluate $\int_{-\pi / 2}^{\pi / 2} \sin ^{2} x d x$.

#### Solution:

Let $f(x)=\sin ^{2} x$.

Then, $f(-x)=[\sin (-x)]^{2}=(-\sin x)^{2}=\sin ^{2} x=f(x)$.

$\therefore \quad f(x)$ is an even function.

So, $\quad \int_{-\pi / 2}^{\pi / 2} \sin ^{2} x d x=2 \int_{0}^{\pi / 2} \sin ^{2} x d x=2 \int_{0}^{\pi / 2}\left(\frac{1-\cos 2 x}{2}\right) d x$

$$
=\int_{0}^{\pi / 2}(1-\cos 2 x) d x=\left[x-\frac{\sin 2 x}{2}\right]_{0}^{\pi / 2}=\frac{\pi}{2}
$$

---

### Example 20:

Prove that $\int_{-1}^{1} \log \left(\frac{2-x}{2+x}\right) d x=0$. *[CBSE 2005C]*

#### Solution:

Let $f(x)=\log \left(\frac{2-x}{2+x}\right)$.

Then, $f(-x)=\log \left(\frac{2+x}{2-x}\right)=\log \left(\frac{2-x}{2+x}\right)^{-1}=-\log \left(\frac{2-x}{2+x}\right)=-f(x)$.

$\therefore f(x)$ is an odd function of $x$.

But, we know that $\int_{-a}^{a} f(x) d x=0$, when $f(x)$ is an odd function of $x$.

$\therefore \quad \int_{-1}^{1} \log \left(\frac{2-x}{2+x}\right) d x=0$.

---

### Example 21:

Evaluate $\int_{1}^{4} f(x) d x$, where
$$f(x)=\left\{\begin{array}{lll}4 x+3, & \text { if } & 1 \leq x \leq 2 \\ 3 x+5, & \text { if } & 2 \leq x \leq 4 .\end{array}\right.$$

#### Solution:

$\int_{1}^{4} f(x) d x=\int_{1}^{2} f(x) d x+\int_{2}^{4} f(x) d x$

$$
\begin{aligned}
& =\int_{1}^{2}(4 x+3) d x+\int_{2}^{4}(3 x+5) d x \\
& =\left[2 x^{2}+3 x\right]_{1}^{2}+\left[\frac{3 x^{2}}{2}+5 x\right]_{2}^{4} \\
& =[(8+6)-(2+3)] + [(\frac{3 \cdot 16}{2} + 20) - (\frac{3 \cdot 4}{2} + 10)] \\
& = [14 - 5] + [(24+20) - (6+10)] \\
& = 9 + [44 - 16] = 9 + 28 = 37
\end{aligned}
$$
*(Note: Original solution's intermediate step $(9+28)=37$ calculation is correct, steps expanded for clarity)*

---

## Integrals of Modulus Functions

### Example 22:

Evaluate:
- (i) $\int_{-1}^{2}|x| d x$
- (ii) $\int_{0}^{1}|5 x-3| d x$
- (iii) $\int_{0}^{\pi}|\cos x| d x$

#### Solution:

**(i)** Clearly,
$$|x|=\left\{\begin{array}{rrr}-x & \text { when } & -1 \leq x \leq 0 \\ x & \text { when } & 0 \leq x \leq 2 .\end{array}\right.$$

$$
\begin{aligned}
\therefore \quad \int_{-1}^{2}|x| d x & =\int_{-1}^{0}|x| d x+\int_{0}^{2}|x| d x \\
& =\int_{-1}^{0}(-x) d x+\int_{0}^{2} x d x=\left[\frac{-x^{2}}{2}\right]_{-1}^{0}+\left[\frac{x^{2}}{2}\right]_{0}^{2} \\
& = [0 - (-\frac{1}{2})] + [2 - 0] = \left(\frac{1}{2}+2\right)=\frac{5}{2}
\end{aligned}
$$

**(ii)** Clearly,
$$|5 x-3|=\left\{\begin{array}{rr}-(5 x-3) & \text { when } 0 \leq x \leq \frac{3}{5} \\ (5 x-3) & \text { when } \frac{3}{5} \leq x \leq 1 .\end{array}\right.$$

$$
\begin{aligned}
\therefore \int_{0}^{1}|5 x-3| d x & =\int_{0}^{3 / 5}|5 x-3| d x+\int_{3 / 5}^{1}|5 x-3| d x \\
& =\int_{0}^{3 / 5}-(5 x-3) d x+\int_{3 / 5}^{1}(5 x-3) d x
\end{aligned}
$$

$$
\begin{aligned}
& =\left[3 x-\frac{5 x^{2}}{2}\right]_{0}^{3 / 5}+\left[\frac{5 x^{2}}{2}-3 x\right]_{3 / 5}^{1} \\
& =\left(\frac{9}{5}-\frac{5}{2}(\frac{9}{25})\right) - 0 + \left(\frac{5}{2}-3\right) - \left(\frac{5}{2}(\frac{9}{25}) - 3(\frac{3}{5})\right) \\
& =\left(\frac{9}{5}-\frac{9}{10}\right)+\left(-\frac{1}{2}\right) - \left(\frac{9}{10} - \frac{9}{5}\right) \\
& = \left(\frac{18-9}{10}\right) - \frac{5}{10} - \left(\frac{9-18}{10}\right) \\
& = \frac{9}{10} - \frac{5}{10} - (-\frac{9}{10}) = \frac{9-5+9}{10} = \frac{13}{10}
\end{aligned}
$$

**(iii)** Clearly,
$$|\cos x|=\left\{\begin{array}{c}\cos x \text { when } 0 \leq x \leq \frac{\pi}{2} \\ -\cos x \text { when } \frac{\pi}{2} \leq x \leq \pi\end{array}\right.$$

$$
\begin{aligned}
\therefore \quad \int_{0}^{\pi}|\cos x| d x & =\int_{0}^{\pi / 2}|\cos x| d x+\int_{\pi / 2}^{\pi}|\cos x| d x \\
& =\int_{0}^{\pi / 2} \cos x d x+\int_{\pi / 2}^{\pi}-\cos x d x \\
& =[\sin x]_{0}^{\pi / 2}-[\sin x]_{\pi / 2}^{\pi} \\
& = (\sin(\frac{\pi}{2}) - \sin(0)) - (\sin(\pi) - \sin(\frac{\pi}{2})) \\
& = (1 - 0) - (0 - 1) = (1+1)=2
\end{aligned}
$$

---

### Example 23:

Evaluate $\int_{1}^{4} f(x) d x$, where $f(x)=|x-1|+|x-2|+|x-3|$. *[CBSE 2013]*

#### Solution:

We split the integral at the points where the absolute value expressions change sign: $x=2$ and $x=3$.

$\int_{1}^{4} f(x) d x=\int_{1}^{2} f(x) d x+\int_{2}^{3} f(x) d x+\int_{3}^{4} f(x) d x$

-   **For $1 \leq x \leq 2$:**
    -   $|x-1| = x-1$
    -   $|x-2| = -(x-2) = -x+2$
    -   $|x-3| = -(x-3) = -x+3$
    -   $f(x) = (x-1) + (-x+2) + (-x+3) = -x+4$

-   **For $2 \leq x \leq 3$:**
    -   $|x-1| = x-1$
    -   $|x-2| = x-2$
    -   $|x-3| = -(x-3) = -x+3$
    -   $f(x) = (x-1) + (x-2) + (-x+3) = x$

-   **For $3 \leq x \leq 4$:**
    -   $|x-1| = x-1$
    -   $|x-2| = x-2$
    -   $|x-3| = x-3$
    -   $f(x) = (x-1) + (x-2) + (x-3) = 3x-6$

$$
\begin{aligned}
& = \int_{1}^{2}(-x+4) d x + \int_{2}^{3} (x) d x + \int_{3}^{4}(3 x-6) d x \\
& = \left[\frac{-x^{2}}{2}+4 x\right]_{1}^{2}+\left[\frac{x^{2}}{2}\right]_{2}^{3}+\left[\frac{3 x^{2}}{2}-6 x\right]_{3}^{4} \\
& = [(-2+8) - (-\frac{1}{2}+4)] + [\frac{9}{2} - \frac{4}{2}] + [(\frac{3 \cdot 16}{2} - 24) - (\frac{3 \cdot 9}{2} - 18)] \\
& = [6 - \frac{7}{2}] + [\frac{5}{2}] + [(24 - 24) - (\frac{27}{2} - \frac{36}{2})] \\
& = [\frac{12-7}{2}] + [\frac{5}{2}] + [0 - (-\frac{9}{2})] \\
& = \frac{5}{2}+\frac{5}{2}+\frac{9}{2}=\frac{19}{2}
\end{aligned}
$$

---

### Example 24:

Evaluate:
- (i) $\int_{-\pi / 2}^{\pi / 2}|\sin x| d x$
- (ii) $\int_{-1}^{1} e^{|x|} d x$
- (iii) $\int_{-2}^{1}|2 x+1| d x$

#### Solution:

**(i)** Let $f(x) = |\sin x|$. Then $f(-x) = |\sin(-x)| = |-\sin x| = |\sin x| = f(x)$.
Clearly, $|\sin x|$ is an **even function** of $x$.

$$
\begin{aligned}
\therefore \quad \int_{-\pi / 2}^{\pi / 2}|\sin x| d x & =2 \int_{0}^{\pi / 2}|\sin x| d x \\
& =2 \int_{0}^{\pi / 2} \sin x d x \quad\left[\because \sin x \geq 0, \text { when } 0 \leq x \leq \frac{\pi}{2}\right] \\
& =[-2 \cos x]_{0}^{\pi / 2} \\
& = -2\cos(\frac{\pi}{2}) - (-2\cos(0)) \\
& = -2(0) - (-2(1)) = 2
\end{aligned}
$$

**(ii)** Let $f(x) = e^{|x|}$. Then $f(-x) = e^{|-x|} = e^{|x|} = f(x)$.
Clearly, $e^{|x|}$ is an **even function** of $x$.

$$
\begin{aligned}
& \therefore \int_{-1}^{1} e^{|x|} d x=2 \int_{0}^{1} e^{|x|} d x \\
& =2 \int_{0}^{1} e^{x} d x \quad[\because|x|=x, \text { when } 0 \leq x \leq 1] \\
& =\left[2 e^{x}\right]_{0}^{1}=(2 e^{1}-2e^{0})=(2 e-2)=2(e-1)
\end{aligned}
$$

**(iii)** We split the integral at $x = -1/2$, where $2x+1 = 0$.
$\left[-2 \leq x<-\frac{1}{2} \Rightarrow 2 x+1<0\right]$ and $\left[-\frac{1}{2} \leq x \leq 1 \Rightarrow 2 x+1 \geq 0\right]$

$$
\begin{aligned}
\therefore \int_{-2}^{1}|2 x+1| d x & =\int_{-2}^{-1 / 2}|2 x+1| d x+\int_{-1 / 2}^{1}|2 x+1| d x \\
&=\int_{-2}^{-1 / 2}-(2 x+1) d x+\int_{-1 / 2}^{1}(2 x+1) d x \\
&=\left[-x^{2}-x\right]_{-2}^{-1 / 2}+\left[x^{2}+x\right]_{-1 / 2}^{1} \\
&=\left[ -(-\frac{1}{2})^2 - (-\frac{1}{2}) \right] - \left[ -(-2)^2 - (-2) \right] + \left[ 1^2+1 \right] - \left[ (-\frac{1}{2})^2 + (-\frac{1}{2}) \right] \\
&=\left(-\frac{1}{4}+\frac{1}{2}\right)-(-4+2)+\left[2-\left(\frac{1}{4}-\frac{1}{2}\right)\right] \\
&=\left(\frac{1}{4}\right)-(-2)+\left[2-(-\frac{1}{4})\right] \\
&=\frac{1}{4}+2+2+\frac{1}{4} = 4 + \frac{2}{4} = 4.5 = \frac{9}{2}
\end{aligned}
$$

---

### Example 25:

Evaluate $\int_{0}^{2 \pi}|\sin x| d x$.

#### Solution:

We know that $\sin x$ is positive when $0 \leq x \leq \pi$ and $\sin x$ is negative when $\pi \leq x \leq 2 \pi$.

$$
\therefore \quad|\sin x|=\left\{\begin{aligned}
\sin x, & \text { when } 0 \leq x \leq \pi \\
-\sin x, & \text { when } \pi \leq x \leq 2 \pi
\end{aligned}\right.
$$

$$
\begin{aligned}
\therefore \quad \int_{0}^{2 \pi}|\sin x| d x & =\int_{0}^{\pi}|\sin x| d x+\int_{\pi}^{2 \pi}|\sin x| d x \\
& =\int_{0}^{\pi} \sin x d x+\int_{\pi}^{2 \pi}(-\sin x) d x \\
& =[-\cos x]_{0}^{\pi}+[\cos x]_{\pi}^{2 \pi} \\
& = [-\cos(\pi) - (-\cos(0))] + [\cos(2\pi) - \cos(\pi)] \\
& = [-(-1) - (-1)] + [1 - (-1)] \\
& = (1+1) + (1+1) = (2+2)=4
\end{aligned}
$$

---

### Example 26:

Evaluate $\int_{-\pi / 2}^{\pi / 2} f(x) d x$, where $f(x)=\sin |x|+\cos |x|$. *[CBSE 2000]*

#### Solution:

$f(x)=\sin |x|+\cos |x|$
$\Rightarrow f(-x)=\sin |-x|+\cos |-x|=\sin |x|+\cos |x|=f(x)$
$\Rightarrow f(x)$ is an **even function**.

$\therefore \quad I=\int_{-\pi / 2}^{\pi / 2} f(x) d x$

$$
\begin{aligned}
& =2 \int_{0}^{\pi / 2} f(x) d x=2 \int_{0}^{\pi / 2}\{\sin |x|+\cos |x|\} d x \\
& =2 \int_{0}^{\pi / 2}(\sin x+\cos x) d x \quad\left[\because|x|=x \text { in } 0 \leq x < \frac{\pi}{2}\right] \\
& =2 \cdot[-\cos x+\sin x]_{0}^{\pi / 2} \\
& =2\left[\left(-\cos \frac{\pi}{2}+\sin \frac{\pi}{2}\right)-(-\cos 0+\sin 0)\right] \\
& =2[(0+1) - (-1+0)] = 2[1 - (-1)] = 2(2) = 4
\end{aligned}
$$

---

