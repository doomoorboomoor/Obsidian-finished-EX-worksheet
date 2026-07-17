# Derivative of the Quotient of two Functions

## Theorem: Quotient Rule

If $f(x)$ and $g(x)$ are two differentiable functions and $g(x) \neq 0$, then $\frac{f(x)}{g(x)}$ is also differentiable, and its derivative is given by:

$$
\frac{d}{dx}\left\{\frac{f(x)}{g(x)}\right\} = \frac{g(x) \cdot \frac{d}{dx}\{f(x)\} - f(x) \cdot \frac{d}{dx}\{g(x)\}}{[g(x)]^2}
$$

### Proof

Let $y = \frac{f(x)}{g(x)}$ and $y + \delta y = \frac{f(x + \delta x)}{g(x + \delta x)}$.

Then, $\frac{\delta y}{\delta x} = \frac{1}{\delta x} \cdot \left\{\frac{f(x + \delta x)}{g(x + \delta x)} - \frac{f(x)}{g(x)}\right\}$.

$$
\begin{aligned}
& \therefore \quad \frac{dy}{dx} = \lim_{\delta x \to 0} \frac{\delta y}{\delta x} = \lim_{\delta x \to 0} \frac{1}{\delta x}\left\{\frac{f(x+\delta x)}{g(x+\delta x)}-\frac{f(x)}{g(x)}\right\} \\
&= \lim_{\delta x \to 0} \frac{g(x) \cdot f(x+\delta x) - g(x+\delta x) \cdot f(x)}{\delta x \cdot g(x+\delta x) \cdot g(x)} \\
&= \lim_{\delta x \to 0} \frac{g(x) \cdot f(x+\delta x) - g(x) \cdot f(x) + g(x) \cdot f(x) - g(x+\delta x) \cdot f(x)}{\delta x \cdot g(x+\delta x) \cdot g(x)} \\
&= \left[\lim_{\delta x \to 0} g(x) \cdot\left\{\frac{f(x+\delta x)-f(x)}{\delta x}\right\} - \lim_{\delta x \to 0} f(x) \cdot\left\{\frac{g(x+\delta x)-g(x)}{\delta x}\right\}\right] \\
&= \left[g(x) \cdot \frac{d}{dx}\{f(x)\} - f(x) \cdot \frac{d}{dx}\{g(x)\}\right] \times \frac{1}{[g(x)]^2} \\
&= \frac{g(x) \cdot \frac{d}{dx}\{f(x)\} - f(x) \cdot \frac{d}{dx}\{g(x)\}}{[g(x)]^2} \\
& \therefore \quad \frac{d}{dx}\left\{\frac{f(x)}{g(x)}\right\} = \frac{g(x) \cdot \frac{d}{dx}\{f(x)\} - f(x) \cdot \frac{d}{dx}\{g(x)\}}{[g(x)]^2}
\end{aligned}
$$

Now, since each of $f(x)$ and $g(x)$ are differentiable, it follows that $\frac{d}{dx}\{f(x)\}$ and $\frac{d}{dx}\{g(x)\}$ both exist. So, by the above result, it follows that $\frac{d}{dx}\left\{\frac{f(x)}{g(x)}\right\}$ exists, and hence $\frac{f(x)}{g(x)}$ is differentiable.

### Remark

The above result may be expressed as $\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{\left\{v \cdot \frac{du}{dx} - u \cdot \frac{dv}{dx}\right\}}{v^2}$.

In words, the derivative of the quotient of two functions is:

$$
= \frac{(\textbf{Denominator} \times \textbf{Derivative of Numerator}) - (\textbf{Numerator} \times \textbf{Derivative of Denominator})}{(\textbf{Denominator})^2}
$$

---

# Solved Examples

### Example 1

Differentiate:

(i) $\frac{e^x}{x}$
(ii) $\left(\frac{2x+3}{x^2-5}\right)$
(iii) $\frac{e^x}{(1+\sin x)}$

#### Solution

(i) $\frac{d}{dx}\left(\frac{e^x}{x}\right) = \frac{x \cdot \frac{d}{dx}(e^x) - e^x \cdot \frac{d}{dx}(x)}{x^2} = \frac{x e^x - e^x \cdot 1}{x^2} = \frac{e^x(x-1)}{x^2}$.

(ii)
$$
\begin{aligned}
\frac{d}{dx}\left(\frac{2x+3}{x^2-5}\right) &= \frac{(x^2-5) \cdot \frac{d}{dx}(2x+3) - (2x+3) \cdot \frac{d}{dx}(x^2-5)}{(x^2-5)^2} \\
&= \frac{(x^2-5) \cdot 2 - (2x+3) \cdot 2x}{(x^2-5)^2} = \frac{-2(x^2+3x+5)}{(x^2-5)^2}.
\end{aligned}
$$

(iii)
$$
\begin{aligned}
\frac{d}{dx}\left(\frac{e^x}{1+\sin x}\right) &= \frac{(1+\sin x) \cdot \frac{d}{dx}(e^x) - e^x \cdot \frac{d}{dx}(1+\sin x)}{(1+\sin x)^2} \\
&= \frac{(1+\sin x) \cdot e^x - e^x(\cos x)}{(1+\sin x)^2} = \frac{(1+\sin x-\cos x)e^x}{(1+\sin x)^2}.
\end{aligned}
$$

---

### Example 2

Differentiate $\left(\frac{x^2+5x-6}{4x^2-x+3}\right)$.

#### Solution

Using the quotient rule, we have:

$$
\begin{aligned}
\frac{d}{dx}\left(\frac{x^2+5x-6}{4x^2-x+3}\right) &= \frac{(4x^2-x+3) \cdot \frac{d}{dx}(x^2+5x-6) - (x^2+5x-6) \cdot \frac{d}{dx}(4x^2-x+3)}{(4x^2-x+3)^2} \\
&= \frac{(4x^2-x+3)(2x+5) - (x^2+5x-6)(8x-1)}{(4x^2-x+3)^2} = \frac{(9+54x-21x^2)}{(4x^2-x+3)^2}.
\end{aligned}
$$

---

### Example 3

Differentiate $\left(\frac{x^2 \sin x}{1-x}\right)$.

#### Solution

By the quotient rule, we have:

$$
\begin{aligned}
\frac{d}{dx}\left(\frac{x^2 \sin x}{1-x}\right) &= \frac{(1-x) \cdot \frac{d}{dx}(x^2 \sin x) - x^2 \sin x \cdot \frac{d}{dx}(1-x)}{(1-x)^2} \\
&= \frac{(1-x)\left\{x^2 \cdot \frac{d}{dx}(\sin x) + \sin x \cdot \frac{d}{dx}(x^2)\right\} - (x^2 \sin x)(-1)}{(1-x)^2} \\
&= \frac{(1-x)[x^2 \cos x + 2x \sin x] + x^2 \sin x}{(1-x)^2} \\
&= \frac{x^2(1-x) \cos x + (x \sin x)(2-x)}{(1-x)^2}
\end{aligned}
$$

---

### Example 4

If $y = \left\{\frac{1-\tan x}{1+\tan x}\right\}$, show that $\frac{dy}{dx} = \frac{-2}{(1+\sin 2x)}$.

#### Solution

By the quotient rule, we have:

$$
\begin{aligned}
\frac{dy}{dx} &= \frac{(1+\tan x) \cdot \frac{d}{dx}(1-\tan x) - (1-\tan x) \cdot \frac{d}{dx}(1+\tan x)}{(1+\tan x)^2} \\
&= \frac{(1+\tan x)(-\sec^2 x) - (1-\tan x)(\sec^2 x)}{(1+\tan x)^2} \\
&= \frac{-2 \sec^2 x}{(1+\tan x)^2} = \frac{-2}{(\cos^2 x)(1+\tan^2 x+2 \tan x)} \\
&= \frac{-2}{(\cos^2 x)\left\{1+\frac{\sin^2 x}{\cos^2 x}+\frac{2 \sin x}{\cos x}\right\}} = \frac{-2}{(1+\sin 2x)}
\end{aligned}
$$

---

### Example 5

Differentiate:

(i) $\left(\frac{\sin x+\cos x}{\sin x-\cos x}\right)$
(ii) $\left(\frac{\sec x-1}{\sec x+1}\right)$

#### Solution

(i)
$$
\begin{aligned}
\frac{d}{dx}\left(\frac{\sin x+\cos x}{\sin x-\cos x}\right) &= \frac{(\sin x-\cos x) \cdot \frac{d}{dx}(\sin x+\cos x) - (\sin x+\cos x) \cdot \frac{d}{dx}(\sin x-\cos x)}{(\sin x-\cos x)^2} \\
&= \frac{(\sin x-\cos x)(\cos x-\sin x) - (\sin x+\cos x)(\cos x+\sin x)}{(\sin x-\cos x)^2} \\
&= \frac{-[(\sin x-\cos x)^2 + (\sin x+\cos x)^2]}{(\sin x-\cos x)^2} \\
&= \frac{-2(\sin^2 x+\cos^2 x)}{(\sin^2 x+\cos^2 x-2 \sin x \cos x)} = \frac{-2}{(1-\sin 2x)}
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\frac{d}{dx}\left(\frac{\sec x-1}{\sec x+1}\right) &= \frac{(\sec x+1) \cdot \frac{d}{dx}(\sec x-1) - (\sec x-1) \cdot \frac{d}{dx}(\sec x+1)}{(\sec x+1)^2} \\
&= \frac{(\sec x+1) \sec x \tan x - (\sec x-1) \sec x \tan x}{(\sec x+1)^2} = \frac{2 \sec x \tan x}{(\sec x+1)^2}
\end{aligned}
$$

---

