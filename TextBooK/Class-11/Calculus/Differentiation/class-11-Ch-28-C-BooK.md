## Some More Results on Differentiation

---

## Derivative of the Product of Functions

**Theorem (Product Rule)**
If $f(x)$ and $g(x)$ are two differentiable functions, then $f(x) \cdot g(x)$ is also differentiable, and

$$
\frac{d}{dx}\{f(x) \cdot g(x)\} = f(x) \cdot \frac{d}{dx}\{g(x)\} + g(x) \cdot \frac{d}{dx}\{f(x)\}.
$$

#### Proof:
Let $y = f(x) \cdot g(x)$ and $y + \delta y = f(x + \delta x) \cdot g(x + \delta x)$.

Then,
$$
\frac{\delta y}{\delta x} = \frac{f(x+\delta x) \cdot g(x+\delta x) - f(x) \cdot g(x)}{\delta x}.
$$

Therefore,
$$
\begin{aligned}
\frac{dy}{dx} &= \lim_{\delta x \to 0} \frac{\delta y}{\delta x} = \lim_{\delta x \to 0} \frac{f(x+\delta x) \cdot g(x+\delta x) - f(x) \cdot g(x)}{\delta x} \\
&= \lim_{\delta x \to 0} \frac{f(x+\delta x) \cdot g(x+\delta x) - f(x+\delta x) \cdot g(x) + f(x+\delta x) \cdot g(x) - f(x) \cdot g(x)}{\delta x} \\
& \qquad \textit{[adding and subtracting $f(x+\delta x) \cdot g(x)$ in the numerator]} \\
&= \lim_{\delta x \to 0} \frac{f(x+\delta x) \cdot \{g(x+\delta x) - g(x)\} + g(x) \cdot \{f(x+\delta x) - f(x)\}}{\delta x} \\
&= \lim_{\delta x \to 0} f(x+\delta x) \cdot \frac{\{g(x+\delta x) - g(x)\}}{\delta x} + \lim_{\delta x \to 0} g(x) \cdot \left\{\frac{f(x+\delta x) - f(x)}{\delta x}\right\} \\
&= \left(\lim_{\delta x \to 0} f(x+\delta x)\right) \cdot \left(\lim_{\delta x \to 0} \frac{g(x+\delta x) - g(x)}{\delta x}\right) + g(x) \cdot \left(\lim_{\delta x \to 0} \frac{f(x+\delta x) - f(x)}{\delta x}\right) \\
&= f(x) \cdot \frac{d}{dx}\{g(x)\} + g(x) \cdot \frac{d}{dx}\{f(x)\}.
\end{aligned}
$$

$$
\therefore \frac{d}{dx}\{f(x) \cdot g(x)\} = f(x) \cdot \frac{d}{dx}\{g(x)\} + g(x) \cdot \frac{d}{dx}\{f(x)\}.
$$

Now, since $f(x)$ and $g(x)$ are differentiable, it follows that $\frac{d}{dx}\{f(x)\}$ and $\frac{d}{dx}\{g(x)\}$ exist. Consequently, $f(x) \cdot \frac{d}{dx}\{g(x)\} + g(x) \cdot \frac{d}{dx}\{f(x)\}$ exists. So, from the above result, we conclude that $\frac{d}{dx}\{f(x) \cdot g(x)\}$ exists and therefore, $f(x) \cdot g(x)$ is differentiable.

#### Remark:
The above result may be expressed as:
$$
\frac{d}{dx}[uv] = u \cdot \frac{dv}{dx} + v \cdot \frac{du}{dx}
$$
It may be remembered as:
> derivative of the product of two functions
> = [(1st function) $\times$ (derivative of 2nd)] + [(2nd function) $\times$ (derivative of 1st)].

---

## Solved Examples

### Example 1:

Differentiate: (i) $x e^{x}$ (ii) $x^{2} e^{x} \sin x$

#### Solution:

(i)
$$
\frac{d}{dx}(x e^{x}) = x \cdot \frac{d}{dx}(e^{x}) + e^{x} \cdot \frac{d}{dx}(x) = (x e^{x} + e^{x} \cdot 1) = e^{x}(x+1).
$$

(ii)
$$
\begin{aligned}
\frac{d}{dx}(x^{2} e^{x} \sin x) &= \frac{d}{dx}[(x^{2} e^{x}) \sin x] \\
&= (x^{2} e^{x}) \cdot \frac{d}{dx}(\sin x) + \sin x \cdot \frac{d}{dx}(x^{2} e^{x}) \\
&= x^{2} e^{x} \cos x + \sin x \cdot \left\{x^{2} \cdot \frac{d}{dx}(e^{x}) + e^{x} \cdot \frac{d}{dx}(x^{2})\right\} \\
&= x^{2} e^{x} \cos x + \sin x \cdot [x^{2} e^{x} + 2x e^{x}] \\
&= x^{2} e^{x} \cos x + x^{2} e^{x} \sin x + 2x e^{x} \sin x \\
&= x e^{x}[x \cos x + x \sin x + 2 \sin x]
\end{aligned}
$$

---

### Example 2:

Differentiate $x^{2} \tan x$.

#### Solution:

We have
$$
\begin{aligned}
\frac{d}{dx}(x^{2} \tan x) &= \left\{x^{2} \cdot \frac{d}{dx}(\tan x) + \tan x \cdot \frac{d}{dx}(x^{2})\right\} \\
&= (x^{2} \sec^{2} x + 2x \tan x)
\end{aligned}
$$

---

### Example 3:

Differentiate $(e^{x} \sin x + x^{p} \cos x)$.

#### Solution:

We have
$$
\begin{aligned}
\frac{d}{dx}(e^{x} \sin x + x^{p} \cos x) &= \frac{d}{dx}(e^{x} \sin x) + \frac{d}{dx}(x^{p} \cos x) \\
&= \left\{e^{x} \cdot \frac{d}{dx}(\sin x) + \sin x \cdot \frac{d}{dx}(e^{x})\right\} + \left\{x^{p} \cdot \frac{d}{dx}(\cos x) + \cos x \cdot \frac{d}{dx}(x^{p})\right\} \\
&= (e^{x} \cos x + e^{x} \sin x) + [x^{p}(-\sin x) + \cos x \cdot (p x^{p-1})] \\
&= e^{x}(\cos x + \sin x) - x^{p} \sin x + p x^{p-1} \cos x \\
&= e^{x}(\cos x + \sin x) - x^{p-1}(x \sin x - p \cos x)
\end{aligned}
$$

---

### Example 4:

Differentiate $e^{x}(x^{3} + \sqrt{x})$.

#### Solution:
$$
\begin{aligned}
\frac{d}{dx}[e^{x}(x^{3} + \sqrt{x})] &= e^{x} \cdot \frac{d}{dx}(x^{3} + \sqrt{x}) + (x^{3} + \sqrt{x}) \cdot \frac{d}{dx}(e^{x}) \\
&= e^{x}\left\{3x^{2} + \frac{1}{2}x^{-1/2}\right\} + (x^{3} + \sqrt{x}) \cdot e^{x} \\
&= e^{x}\left\{x^{3} + 3x^{2} + \frac{1}{2\sqrt{x}} + \sqrt{x}\right\}.
\end{aligned}
$$

---

### Example 5:

Differentiate $\left(\frac{e^{x} \cos x}{x^{3}}\right)$, using the product rule.

#### Solution:

We have
$$
\begin{aligned}
\frac{d}{dx}\left\{\frac{e^{x} \cos x}{x^{3}}\right\} &= \frac{d}{dx}[(e^{x} \cos x) \cdot x^{-3}] \\
&= (e^{x} \cos x) \cdot \frac{d}{dx}(x^{-3}) + x^{-3} \cdot \frac{d}{dx}(e^{x} \cos x) \\
&= e^{x} \cos x \cdot (-3x^{-4}) + x^{-3} \cdot \left\{e^{x} \cdot \frac{d}{dx}(\cos x) + \cos x \cdot \frac{d}{dx}(e^{x})\right\} \\
&= \frac{-3e^{x} \cos x}{x^{4}} + \frac{1}{x^{3}}[-e^{x} \sin x + e^{x} \cos x] \\
&= \frac{-3e^{x} \cos x - xe^{x} \sin x + xe^{x} \cos x}{x^{4}} \\
&= \frac{e^{x}[(x-3) \cos x - x \sin x]}{x^{4}}.
\end{aligned}
$$

---

### Example 6:

If $u, v, w$ are differentiable functions of $x$, prove that
$$
\frac{d}{dx}(uvw) = (uv) \cdot \frac{dw}{dx} + (wu) \cdot \frac{dv}{dx} + (wv) \cdot \frac{du}{dx}
$$

#### Solution:

We have
$$
\begin{aligned}
\frac{d}{dx}(uvw) &= \frac{d}{dx}\{(uv)w\} \\
&= (uv) \cdot \frac{dw}{dx} + w \cdot \frac{d}{dx}(uv) \\
&= (uv) \cdot \frac{dw}{dx} + w \cdot \left\{u \cdot \frac{dv}{dx} + v \cdot \frac{du}{dx}\right\} \\
&= (uv) \cdot \frac{dw}{dx} + (wu) \cdot \frac{dv}{dx} + (wv) \cdot \frac{du}{dx}.
\end{aligned}
$$

---

