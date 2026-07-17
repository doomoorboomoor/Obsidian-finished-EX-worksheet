## General Equation of a Line

### Theorem 1

Prove that the equation $A x+B y+C=0$ always represents a line, provided $A$ and $B$ are not simultaneously zero.

#### Proof:

Let $A x+B y+C=0$, where $A \neq 0$ or $B \neq 0$.

- **Case 1:** When $A=0$ and $B \neq 0$.
In this case, the given equation becomes

$$
B y+C=0 \Rightarrow y=\left(\frac{-C}{B}\right)
$$

which represents a line parallel to the **x-axis**.

- **Case 2:** When $A \neq 0$ and $B=0$.
In this case, the given equation becomes

$$
A x+C=0 \Rightarrow x=\left(\frac{-C}{A}\right)
$$

which represents a line parallel to the **y-axis**.

- **Case 3:** When $A \neq 0$ and $B \neq 0$.
In this case, we have

$$
\begin{aligned}
A x+B y+C=0 & \Rightarrow B y=-A x+(-C) \\
& \Rightarrow y=\left(\frac{-A}{B}\right) x+\left(\frac{-C}{B}\right) .
\end{aligned}
$$

This is clearly an equation of a line in **slope-intercept form**, $y=m x+c$, where $m=\left(\frac{-A}{B}\right)$ and $c=\frac{-C}{B}$.

Thus, $A x+B y+C=0$, when $A \neq 0$ or $B \neq 0$, always represents a line.

---

### Theorem 2

Prove that every line has an equation of the form $A x+B y+c=0$, where $A, B, C$ are constants.

#### Proof:

For a given line, there are two possibilities.

- **Case 1:** The given line is parallel to the y-axis.
In this case, the equation is of the form, $x=c$.
Now, $x=c \Leftrightarrow 1 \cdot x+0 \cdot y-c=0$

$$
\Leftrightarrow A x+B y+C=0, \text { where } C=-c .
$$

Thus, it is of the form $A x+B y+C=0$.

- **Case 2:** The given line is not parallel to the y-axis.
In this case, the equation is of the form

$$
\begin{aligned}
y=m x+c & \Rightarrow m x-y+c=0 \\
& \Rightarrow A x+B y+C=0
\end{aligned}
$$

where $A=m, B=-1$ and $C=c$.
Thus, it takes the form $A x+B y+C=0$.

---

## Reduction of General Form to Standard Form

Let the given equation of the line be $A x+B y+C=0$.

### I. Slope-Intercept Form

$$
\begin{aligned}
A x+B y+C=0 & \Rightarrow B y=-A x-C \\
& \Rightarrow y=\left(\frac{-A}{B}\right) x+\left(\frac{-C}{B}\right) \\
& \Rightarrow y=m x+c, \text { where } m=\frac{-A}{B} \text { and } c=\frac{-C}{B}
\end{aligned}
$$

This is clearly the equation of a line in **slope-intercept form**, $y=m x+c$, where **slope** $m=\frac{-A}{B}$ and **y-intercept** $c=\frac{-C}{B}$.

### II. Intercepts Form

$$
\begin{aligned}
A x+B y+C=0 & \Rightarrow A x+B y=-C \\
& \Rightarrow\left(\frac{A}{-C}\right) x+\left(\frac{B}{-C}\right) y=1 \\
& \Rightarrow \frac{x}{\left(\frac{-C}{A}\right)}+\frac{y}{\left(\frac{-C}{B}\right)}=1 \\
& \Rightarrow \frac{x}{a}+\frac{y}{b}=1, \text { where } a=\frac{-C}{A} \text { and } b=\frac{-C}{B} .
\end{aligned}
$$

This is clearly the equation of a line in **intercept form**, $\frac{x}{a}+\frac{y}{b}=1$, where **x-intercept** $a=\frac{-C}{A}$ and **y-intercept** $b=\frac{-C}{B}$.

### III. Normal Form

$$
\begin{aligned}
& A x+B y+C=0 \Rightarrow \frac{A}{\sqrt{A^{2}+B^{2}}} x+\frac{B}{\sqrt{A^{2}+B^{2}}} \cdot y+\frac{C}{\sqrt{A^{2}+B^{2}}}=0 \\
& \Rightarrow \frac{-A}{\sqrt{A^{2}+B^{2}}} x+\frac{-B}{\sqrt{A^{2}+B^{2}}} y=\frac{C}{\sqrt{A^{2}+B^{2}}} \\
& \Rightarrow x \cos \alpha+y \sin \alpha=p
\end{aligned}
$$

This is the equation of a line in **normal form**, $x \cos \alpha+y \sin \alpha=p$, where $\cos \alpha=\frac{-A}{\sqrt{A^{2}+B^{2}}}$, $\sin \alpha=\frac{-B}{\sqrt{A^{2}+B^{2}}}$ and $p=\frac{C}{\sqrt{A^{2}+B^{2}}}$.

---

## Solved Examples

### Example 1:

Reduce the equation $\sqrt{3} x+y+2=0$ to:
(i) slope-intercept form and find the slope and $y$-intercept.
(ii) intercepts form and find the intercepts on the axes.

#### Solution:

We have:

(i) $\sqrt{3} x+y+2=0 \Rightarrow y=-\sqrt{3} x-2$.

This is of the form $y=m x+c$, where $m=-\sqrt{3}$ and $c=-2$.
$\therefore y=-\sqrt{3} x-2$ is in **slope-intercept form**.
Here, **slope** $= -\sqrt{3}$ and **y-intercept** $= -2$.

(ii) $\sqrt{3} x+y+2=0 \Rightarrow \sqrt{3} x+y=-2$

$$
\begin{aligned}
& \Rightarrow\left(\frac{\sqrt{3}}{-2}\right) x+\left(\frac{1}{-2}\right) y=1 \\
& \Rightarrow \frac{x}{\left(\frac{-2}{\sqrt{3}}\right)}+\frac{y}{-2}=1
\end{aligned}
$$

This is of the form $\frac{x}{a}+\frac{y}{b}=1$, where $a=\frac{-2}{\sqrt{3}}$ and $b=-2$.
Thus, $\frac{x}{\left(\frac{-2}{\sqrt{3}}\right)}+\frac{y}{-2}=1$ is in **intercepts form**.
Here, **x-intercept** $= \frac{-2}{\sqrt{3}}$ and **y-intercept** $= -2$.

---

### Example 2:

Reduce the equation $3 x-2 y+4=0$ to intercepts form and find the length of the segment intercepted between the axes.

#### Solution:

We have

$$
\begin{aligned}
3 x-2 y+4=0 & \Rightarrow 3 x-2 y=-4 \\
& \Rightarrow \frac{3 x}{-4}+\frac{y}{2}=1 \\
& \Rightarrow \frac{x}{\left(\frac{-4}{3}\right)}+\frac{y}{2}=1
\end{aligned}
$$

This is of the form $\frac{x}{a}+\frac{y}{b}=1$, where $a=\frac{-4}{3}$ and $b=2$.
$\therefore \frac{x}{\left(\frac{-4}{3}\right)}+\frac{y}{2}=1$ is the required equation in **intercepts form**.
**x-intercept** $= \frac{-4}{3}$ and **y-intercept** $= 2$.

If $AB$ is the part of the line intercepted between the axes, then the endpoints of this line segment are $A\left(\frac{-4}{3}, 0\right)$ and $B(0,2)$.

**Length AB** $= \sqrt{\left(\frac{-4}{3}-0\right)^{2}+(0-2)^{2}}=\sqrt{\frac{16}{9}+4}=\frac{2}{3} \sqrt{13}$ units.

---

### Example 3:

Reduce the equation $\sqrt{3} x+y+2=0$ to the normal form $x \cos \alpha+y \sin \alpha=p$, and hence find the values of $\alpha$ and $p$.

#### Solution:

We have

$$
\begin{aligned}
\sqrt{3} x+y+2=0 & \Rightarrow -\sqrt{3} x-y=2 \\
& \Rightarrow \left(\frac{-\sqrt{3}}{2}\right) x+\left(\frac{-1}{2}\right) y=1 \quad \left[\text { on dividing throughout by } \sqrt{(\sqrt{3})^{2}+1^{2}}\right] \\
& \Rightarrow x \cos \alpha+y \sin \alpha=p
\end{aligned}
$$

where $\cos \alpha=\frac{-\sqrt{3}}{2}$, $\sin \alpha=\frac{-1}{2}$ and $p=1$.

Since $\cos \alpha<0$ and $\sin \alpha<0$, $\alpha$ lies in the **third quadrant**.

Now, $\tan \alpha=\frac{\sin \alpha}{\cos \alpha}=\left(\frac{-1}{2}\right) \times\left(\frac{-2}{\sqrt{3}}\right)=\frac{1}{\sqrt{3}}=\tan \left(180^{\circ}+30^{\circ}\right)=\tan 210^{\circ}$
$\Rightarrow \alpha=210^{\circ}$

Thus, $\alpha=210^{\circ}$ and $p=1$.
Hence, the given equation in **normal form** is given by

$$
x \cos 210^{\circ}+y \sin 210^{\circ}=1
$$

---

### Example 4:

Reduce the equation $x+\sqrt{3} y+5=0$ to the normal form $x \cos \alpha+y \sin \alpha=p$, and hence find the values of $\alpha$ and $p$.

#### Solution:

We have

$$
\begin{aligned}
x+\sqrt{3} y+5=0 & \Rightarrow -x-\sqrt{3} y=5 \\
& \Rightarrow\left(\frac{-1}{2}\right) x+\left(\frac{-\sqrt{3}}{2}\right) y=\frac{5}{2} \quad \left[\text { on dividing throughout by } \sqrt{(-1)^{2}+(-\sqrt{3})^{2}} \right] \\
& \Rightarrow x \cos \alpha+y \sin \alpha=p
\end{aligned}
$$

where $\cos \alpha=\frac{-1}{2}$, $\sin \alpha=\frac{-\sqrt{3}}{2}$ and $p=\frac{5}{2}$.

Since $\cos \alpha<0$ and $\sin \alpha<0$, $\alpha$ lies in the **third quadrant**.

Now, $\tan \alpha=\frac{\sin \alpha}{\cos \alpha}=\left(\frac{-\sqrt{3}}{2}\right) \times(-2)=\sqrt{3}=\tan \left(180^{\circ}+60^{\circ}\right)=\tan 240^{\circ}$
$\therefore \alpha=240^{\circ}$.

Thus, $\alpha=240^{\circ}$ and $p=\frac{5}{2}$.
Hence, the given equation in **normal form** is

$$
x \cos 240^{\circ}+y \sin 240^{\circ}=\frac{5}{2}
$$

---

### Example 5:

Reduce the equation $y+4=0$ to the normal form $x \cos \alpha+y \sin \alpha=p$, and hence find the values of $\alpha$ and $p$.

#### Solution:

We have

$$
\begin{aligned}
y+4=0 & \Rightarrow -y=4 \\
& \Rightarrow 0 \cdot x + (-1) \cdot y = 4
\end{aligned}
$$

Comparing this with $x \cos \alpha+y \sin \alpha=p$, we get $\cos \alpha=0$, $\sin \alpha=-1$ and $p=4$.

Now, $(\cos \alpha=0$ and $\sin \alpha=-1) \Rightarrow \alpha=270^{\circ}$.
Hence, the required **normal form** of the given equation is

$$
x \cos 270^{\circ}+y \sin 270^{\circ}=4 .
$$

Clearly, $\alpha=270^{\circ}$ and $p=4$.

---

