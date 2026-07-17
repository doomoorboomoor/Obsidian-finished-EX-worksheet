## Equation of a Line in Normal Form

### Theorem 1

Let *$p$* be the length of the perpendicular (or normal) from the origin to a given non-vertical line *$L$*, and let *$\alpha$* be the angle between the normal and the positive direction of the $x$-axis. Then, prove that the equation of the line *$L$* is given by

$$
x \cos \alpha + y \sin \alpha = p
$$

---

#### Proof

Let $X'OX$ and $YOY'$ be the coordinate axes and let $L$ be the given line. Draw $ON$ perpendicular to $L$.

Let $ON = p$, and let the angle between the positive direction of the $x$-axis and $ON$ be $\alpha$. Draw perpendicular $NM$ on the $x$-axis.

All possible positions of the line $L$ are shown below.

In each case, we have:
$$
\frac{OM}{ON} = \cos \alpha \quad \text{and} \quad \frac{NM}{ON} = \sin \alpha
$$
$$
\Leftrightarrow OM = p \cos \alpha \quad \text{and} \quad NM = p \sin \alpha
$$

Thus, the coordinates of $N$ are **($p \cos \alpha, p \sin \alpha$)**.

Moreover, line $L$ is perpendicular to $ON$.

Therefore, the **slope of the line L** is:
$$
m = \frac{-1}{\text{slope of } ON} = \frac{-1}{\tan \alpha} = \frac{-\cos \alpha}{\sin \alpha}
$$

Thus, the line $L$ passes through the point $N(p \cos \alpha, p \sin \alpha)$ and has a slope $m = \frac{-\cos \alpha}{\sin \alpha}$.

So, the equation of the line $L$ is given by the point-slope form:
$$
\frac{y - p \sin \alpha}{x - p \cos \alpha} = \frac{-\cos \alpha}{\sin \alpha}
$$
$$
\Leftrightarrow (y - p \sin \alpha) \sin \alpha = -\cos \alpha(x - p \cos \alpha)
$$
$$
\Leftrightarrow x \cos \alpha + y \sin \alpha = p(\cos^2 \alpha + \sin^2 \alpha)
$$
$$
\Leftrightarrow \mathbf{x \cos \alpha + y \sin \alpha = p}
$$
This is the required equation.

---

## Solved Examples

### Example 1

Find the equation of a line whose perpendicular distance from the origin is 5 units and the angle between the positive direction of the $x$-axis and the perpendicular is $30^{\circ}$.

#### Solution:

Here, we are given $p = 5$ units and $\alpha = 30^{\circ}$.

The equation of the line in **normal form** is $x \cos \alpha + y \sin \alpha = p$.

Substituting the given values:
$$
x \cos 30^{\circ} + y \sin 30^{\circ} = 5
$$
$$
\Leftrightarrow x \left(\frac{\sqrt{3}}{2}\right) + y \left(\frac{1}{2}\right) = 5
$$
$$
\Leftrightarrow \sqrt{3}x + y = 10
$$
Thus, the required equation is **$\sqrt{3}x + y - 10 = 0$**.

---

### Example 2

Find the equation of the line whose perpendicular distance from the origin is 3 units and the angle between the positive direction of the $x$-axis and the perpendicular is $15^{\circ}$.

#### Solution:

Here, we are given $p = 3$ units and $\alpha = 15^{\circ}$.

The equation of the line in **normal form** is $x \cos \alpha + y \sin \alpha = p$.

Substituting the given values:
$$
x \cos 15^{\circ} + y \sin 15^{\circ} = 3
$$
We know that:
- $\cos 15^{\circ} = \cos(45^{\circ} - 30^{\circ}) = \cos 45^{\circ} \cos 30^{\circ} + \sin 45^{\circ} \sin 30^{\circ} = \frac{\sqrt{3}+1}{2\sqrt{2}}$
- $\sin 15^{\circ} = \sin(45^{\circ} - 30^{\circ}) = \sin 45^{\circ} \cos 30^{\circ} - \cos 45^{\circ} \sin 30^{\circ} = \frac{\sqrt{3}-1}{2\sqrt{2}}$

Substituting these values into the equation:
$$
\Leftrightarrow x\left(\frac{\sqrt{3}+1}{2\sqrt{2}}\right) + y\left(\frac{\sqrt{3}-1}{2\sqrt{2}}\right) = 3
$$
$$
\Leftrightarrow (\sqrt{3}+1)x + (\sqrt{3}-1)y = 6\sqrt{2}
$$
Thus, the required equation is **$(\sqrt{3}+1)x + (\sqrt{3}-1)y - 6\sqrt{2} = 0$**.

---

### Example 3

Find the equation of a line whose perpendicular distance from the origin is $\sqrt{8}$ units and the angle between the positive direction of the $x$-axis and the perpendicular is $135^{\circ}$.

#### Solution:

Here, we are given $p = \sqrt{8}$ units and $\alpha = 135^{\circ}$.

The equation of the line in **normal form** is $x \cos \alpha + y \sin \alpha = p$.

Substituting the given values:
$$
x \cos 135^{\circ} + y \sin 135^{\circ} = \sqrt{8}
$$
$$
\Leftrightarrow x\left(\frac{-1}{\sqrt{2}}\right) + y\left(\frac{1}{\sqrt{2}}\right) = 2\sqrt{2}
$$
$$
\Leftrightarrow -x + y = (2\sqrt{2}) \times \sqrt{2}
$$
$$
\Leftrightarrow -x + y = 4
$$
Thus, the required equation is **$x - y + 4 = 0$**.

---

### Example 4

Find the equation of a line whose perpendicular distance from the origin is 2 units and the angle between the perpendicular segment and the positive direction of the $x$-axis is $240^{\circ}$.

#### Solution:

Here, we are given $p = 2$ units and $\alpha = 240^{\circ}$.

The equation of the line in **normal form** is $x \cos \alpha + y \sin \alpha = p$.

Substituting the given values:
$$
x \cos 240^{\circ} + y \sin 240^{\circ} = 2
$$
We know that:
- $\cos 240^{\circ} = \cos(180^{\circ} + 60^{\circ}) = -\cos 60^{\circ} = -\frac{1}{2}$
- $\sin 240^{\circ} = \sin(180^{\circ} + 60^{\circ}) = -\sin 60^{\circ} = -\frac{\sqrt{3}}{2}$

Substituting these values into the equation:
$$
\Leftrightarrow x\left(\frac{-1}{2}\right) + y\left(\frac{-\sqrt{3}}{2}\right) = 2
$$
$$
\Leftrightarrow -x - \sqrt{3}y = 4
$$
Thus, the required equation is **$x + \sqrt{3}y + 4 = 0$**.

---

