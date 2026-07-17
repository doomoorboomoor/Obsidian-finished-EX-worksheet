## 33. Linear Programming

## Linear Inequations in Two Variables

The inequalities of the form

$$
a x+b y \leq c, a x+b y<c, a x+b y \geq c \text { and } a x+b y>c
$$

are called **linear inequations** in two variables $x$ and $y$.
The points $(x, y)$ for which the inequation is true, constitute its **solution set**.

---

## Graph of a Linear Inequation

Let us consider an inequation, $a x+b y \leq c$. For drawing its graph to obtain a solution set, we proceed as under.

1.  Consider the equation $a x+b y=c$, and plot the resulting line. In case of strict inequalities $<$ or $>$, draw the line as **dotted**, otherwise mark it **thick**.
2.  Choose a point [if possible $(0,0)$], not lying on this line. Substitute its coordinates in the inequation. If the inequation is satisfied then **shade the portion** of the plane which contains the chosen point; otherwise shade the portion which does not contain this point.

The **shaded portion** represents the solution set. The dotted line is not a part of the shaded region while the thick line is a part of it.

### Example:

Graph the solution set of the inequation $2 x-y \geq 1$.

#### Solution:

Consider the equation $2 x-y=1$.
We may write it as $\frac{x}{(1 / 2)}+\frac{y}{-1}=1$.

This shows that the line $2 x-y=1$ makes intercepts of $\frac{1}{2}$ and $-1$ on the axes. Thus, the line meets the $x$-axis at $A\left(\frac{1}{2}, 0\right)$ and the $y$-axis at $B(0,-1)$. We plot these points and join them by a thick line.

Consider $O(0,0)$. Clearly, $(0,0)$ does not satisfy the given inequation.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Linear-Programming/Linear-Programming/class-12-Ch-33-A-BooK-001.jpg)

So, out of the portions divided by this line, the one not containing $O(0,0)$, together with the points on the line, forms the solution set.

---

## Simultaneous Inequations

The solution set of a system of linear inequations in two variables is the set of all points $(x, y)$ which satisfy all the inequations in the system simultaneously.

So, we find the region of the plane common to all the portions comprising the solution sets of the given inequations. When there is no region common to all the solutions of the given inequations, we say that the solution set of the system is empty.

The linear inequations are also known as **linear constraints**.

---

## Solved Examples

### Example 1:

Draw the graph of the solution set of the system of inequations

$$
2 x+3 y \geq 6, x+4 y \leq 4, x \geq 0 \text { and } y \geq 0 .
$$

#### Solution:

Consider the equations

$$
2 x+3 y=6, x+4 y=4, x=0 \text { and } y=0 .
$$

Now, $2 x+3 y=6 \Rightarrow \frac{x}{3}+\frac{y}{2}=1$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Linear-Programming/Linear-Programming/class-12-Ch-33-A-BooK-002.jpg)

This line meets the axes at $A(3,0)$ and $B(0,2)$. Join these points and draw a thick line. Clearly, the portion not containing $(0,0)$ represents the solution set of the inequation $2 x+3 y \geq 6$.

Again, $x+4 y=4 \Rightarrow \frac{x}{4}+\frac{y}{1}=1$.
This line meets the axes at $C(4,0)$ and $D(0,1)$. Join these points and draw a thick line. Clearly, the portion containing $(0,0)$ represents the solution set of the inequation $x+4 y \leq 4$.

Clearly, $x \geq 0$ is represented by the $y$-axis and the portion on its right-hand side.
Also, $y \geq 0$ is represented by the $x$-axis and the portion above the $x$-axis.
Hence, the shaded region represents the solution set of the given inequations.

---

### Example 2:

Exhibit graphically the solution set of the system of linear inequations

$$
x+y \geq 1,7 x+9 y \leq 63, y \leq 5, x \leq 6, x \geq 0 \text { and } y \geq 0 .
$$

#### Solution:

$x+y=1$ meets the axes at $A(1,0)$ and $B(0,1)$.
Join these points by a thick line. Clearly, the portion not containing $O(0,0)$ is the solution set of $x+y \geq 1$.

$$
7 x+9 y=63 \Rightarrow \frac{x}{9}+\frac{y}{7}=1
$$

This line meets the axes at $C(9,0)$ and $D(0,7)$. Join these points by a thick line. Clearly, the portion containing $(0,0)$ is the solution set of $7 x+9 y \leq 63$.

$y=5$ is a line parallel to the $x$-axis at a distance 5 from the $x$-axis and the portion containing $O(0,0)$ is the solution set of the inequation $y \leq 5$.

$x=6$ is a line parallel to the $y$-axis at a distance 6 from the $y$-axis and the portion
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Linear-Programming/Linear-Programming/class-12-Ch-33-A-BooK-003.jpg)
containing $(0,0)$ is the solution set of $x \leq 6$.

Clearly, $x \geq 0$ has a solution represented by the $y$-axis and the portion on its right. Also, $y \geq 0$ has a solution represented by the $x$-axis and the portion above it.

The shaded region represents the solution set of the given system of inequations.

---

### Example 3:

Find the linear constraints for which the shaded area in the figure below is the solution set.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Linear-Programming/Linear-Programming/class-12-Ch-33-A-BooK-004.jpg)

#### Solution:

Consider the line $3 x+4 y=18$.
Clearly, $O(0,0)$ satisfies $3 x+4 y \leq 18$.
Clearly, the shaded area and $(0,0)$ lie on the same side of the line $3 x+4 y=18$.
So, we must have $3 x+4 y \leq 18$.

Consider the line $x-6 y=3$.
Clearly, $(0,0)$ satisfies the inequation $x-6 y \leq 3$.
Also, the shaded area and $(0,0)$ lie on the same side of the line $x-6 y=3$.
So, we must have $x-6 y \leq 3$.

Consider the line $2 x+3 y=3$.
Clearly, $(0,0)$ satisfies the inequation $2 x+3 y \leq 3$.
But, the shaded region and the point $(0,0)$ lie on the opposite sides of the line $2 x+3 y=3$.
So, we must have $2 x+3 y \geq 3$.

Consider the line $-7 x+14 y=14$.
Clearly, $(0,0)$ satisfies the inequation $-7 x+14 y \leq 14$.
Also, the shaded region and the point $(0,0)$ lie on the same side of the line $-7 x+14 y=14$.
So, we must have $-7 x+14 y \leq 14$.

The shaded region is above the $x$-axis and on the right-hand side of the $y$-axis, so we have $y \geq 0$ and $x \geq 0$.

Thus, the linear constraints for which the shaded area in the given figure is the solution set, are

$$
\begin{aligned}
& 3 x+4 y \leq 18, x-6 y \leq 3,2 x+3 y \geq 3, \\
& -7 x+14 y \leq 14, x \geq 0 \text { and } y \geq 0 .
\end{aligned}
$$

---