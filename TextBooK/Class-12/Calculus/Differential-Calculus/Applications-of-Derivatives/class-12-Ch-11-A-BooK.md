## 11. Applications of Derivatives

## 1. Derivative as a Rate Measure

## Rate of Change of Quantities

Let $y=f(x)$. Then, $\frac{d y}{d x}$ denotes the rate of change of $y$ w.r.t. $x$ and its value at $x=a$ is denoted by $\left[\frac{d y}{d x}\right]_{x=a}$.

If $x=f(t)$, $y=g(t)$ then by chain rule, we have

$$
\frac{d y}{d x}=\frac{(d y / d t)}{(d x / d t)}=\left(\frac{d y}{d t} \cdot \frac{d t}{d x}\right)
$$

---

## Solved Examples

### Example 1:

Find the rate of change of the area of a circle with respect to its radius $r$ when $r=6 \mathrm{~cm}$.

#### Solution:

Let $A$ be the area of a circle of radius $r$. Then,

$$
\begin{aligned}
A=\pi r^{2} & \Rightarrow \frac{d A}{d r}=\frac{d}{d r}\left(\pi r^{2}\right)=2 \pi r \\
& \Rightarrow\left[\frac{d A}{d r}\right]_{r=6 \mathrm{~cm}}=(2 \pi \times 6) \mathrm{cm}^{2} / \mathrm{cm}=(12 \pi) \mathrm{cm}^{2} / \mathrm{cm}
\end{aligned}
$$

Hence, the area is changing at the rate of **$(12 \pi) \mathrm{cm}^{2} / \mathrm{cm}$**.

---

### Example 2:

A stone is dropped into a quiet lake and the waves move in circles. If the radius of a circular wave increases at the rate of $4 \mathrm{~cm} / \mathrm{sec}$, find the rate of increase in its area at the instant when its radius is $10 \mathrm{~cm}$.

#### Solution:

At any instant $t$, let the radius of the circle be $r \mathrm{~cm}$ and its area be $A \mathrm{~cm}^{2}$. Then,

$$
\begin{equation*}
\frac{d r}{d t}=4 \mathrm{~cm} / \mathrm{sec} \quad \text { (given) } \tag{i}
\end{equation*}
$$

Now, $A=\pi r^{2} \Rightarrow \frac{d A}{d t}=\left(\frac{d A}{d r} \cdot \frac{d r}{d t}\right)$

$$
\begin{aligned}
& =\frac{d}{d r}\left(\pi r^{2}\right) \cdot 4\left[\because A=\pi r^{2} \text { and } \frac{d r}{d t}=4\right] \\
& =(2 \pi r \times 4) \mathrm{cm}^{2} / \mathrm{sec}=(8 \pi r) \mathrm{cm}^{2} / \mathrm{sec}
\end{aligned}
$$

$\Rightarrow\left[\frac{d A}{d t}\right]_{r=10}=(8 \pi \times 10) \mathrm{cm}^{2} / \mathrm{sec}=(80 \pi) \mathrm{cm}^{2} / \mathrm{sec}$.

Hence, the area of the circle is increasing at the rate of **$(80 \pi) \mathrm{cm}^{2} / \mathrm{sec}$** at the instant when $r=10 \mathrm{~cm}$.

---

### Example 3:

A spherical soap bubble is expanding so that its radius is increasing at the rate of $0.02 \mathrm{~cm} / \mathrm{sec}$. At what rate is the surface area increasing when its radius is $5 \mathrm{~cm}$? (Take $\pi=3.14$.)

#### Solution:

A soap bubble is in the form of a sphere. At an instant $t$, let its radius be $r$ and surface area $S$. Then,

$$
\begin{equation*}
\frac{d r}{d t}=0.02 \mathrm{~cm} / \mathrm{sec} \quad \text { (given) } \tag{i}
\end{equation*}
$$

Now, $S=4 \pi r^{2}$
$\Rightarrow \frac{d S}{d t}=8 \pi r \cdot \frac{d r}{d t}=(8 \times 3.14 \times r \times 0.02) \mathrm{cm}^{2} / \mathrm{sec}$
$\Rightarrow\left[\frac{d S}{d t}\right]_{r=5}=(8 \times 3.14 \times 5 \times 0.02) \mathrm{cm}^{2} / \mathrm{sec}=2.512 \mathrm{~cm}^{2} / \mathrm{sec}$.

Hence, the surface area of the bubble is increasing at the rate of **$2.512 \mathrm{~cm}^{2} / \mathrm{sec}$** at the instance when its radius is $5 \mathrm{~cm}$.

---

### Example 4:

The volume of a spherical balloon is increasing at the rate of $20 \mathrm{~cm}^{3} / \mathrm{sec}$. Find the rate of change of its surface area at the instant when its radius is $8 \mathrm{~cm}$.

#### Solution:

At any instant $t$, let $r$ be the radius, $V$ the volume and $S$ the surface area of the balloon. Then,

$$
\begin{equation*}
\frac{d V}{d t}=20 \mathrm{~cm}^{3} / \mathrm{sec} \text { (given) } \tag{i}
\end{equation*}
$$

Now, $V=\frac{4}{3} \pi r^{3} \Rightarrow \frac{d V}{d t}=\frac{d V}{d r} \cdot \frac{d r}{d t}$

$$
\begin{align*}
& \Rightarrow 20=\frac{d}{d r}\left(\frac{4}{3} \pi r^{3}\right) \cdot \frac{d r}{d t} \\
& \Rightarrow 20=\frac{4}{3} \pi \times 3 r^{2} \times \frac{d r}{d t}=4 \pi r^{2} \cdot \frac{d r}{d t} \\
& \Rightarrow \frac{d r}{d t}=\frac{5}{\pi r^{2}} \tag{ii}
\end{align*}
$$

$\therefore \quad S=4 \pi r^{2} \Rightarrow \frac{d S}{d t}=\frac{d S}{d r} \cdot \frac{d r}{d t}$

$$
\begin{aligned}
& =\frac{d}{d r}\left(4 \pi r^{2}\right) \cdot \frac{5}{\pi r^{2}} \\
& =\left(8 \pi r \times \frac{5}{\pi r^{2}}\right)=\frac{40}{r}
\end{aligned}
$$

$\Rightarrow\left[\frac{d S}{d t}\right]_{r=8 \mathrm{~cm}}=\left(\frac{40}{8}\right) \mathrm{cm}^{2} / \mathrm{sec}=5 \mathrm{~cm}^{2} / \mathrm{sec}$.

Hence, the rate of change of surface area at the instant when $r=8 \mathrm{~cm}$ is **$5 \mathrm{~cm}^{2} / \mathrm{sec}$**.

---

### Example 5:

The surface area of a spherical balloon is increasing at $2 \mathrm{~cm}^{2} / \mathrm{sec}$. At what rate is the volume of the bubble increasing when the radius of the bubble is $6 \mathrm{~cm}$?
**[CBSE 2005]**

#### Solution:

At any instant $t$, let $r$ be the radius, $V$ the volume and $S$ the surface area of the balloon. Then,

$$
\begin{equation*}
\frac{d S}{d t}=2 \mathrm{~cm}^{2} / \mathrm{sec} \text { (given) } \tag{i}
\end{equation*}
$$

Now, $S=4 \pi r^{2} \Rightarrow \frac{d S}{d t}=\frac{d S}{d r} \cdot \frac{d r}{d t}$

$$
\begin{align*}
& \Rightarrow 2=\frac{d}{d r}\left(4 \pi r^{2}\right) \cdot \frac{d r}{d t} \\
& \Rightarrow 8 \pi r \cdot \frac{d r}{d t}=2 \\
& \Rightarrow \frac{d r}{d t}=\frac{1}{4 \pi r} \tag{ii}
\end{align*}
$$

$$
\begin{aligned}
& \therefore \quad V=\frac{4}{3} \pi r^{3} \Rightarrow \frac{d V}{d t}=\frac{d V}{d r} \cdot \frac{d r}{d t} \\
&=\frac{d}{d r}\left(\frac{4}{3} \pi r^{3}\right) \cdot \frac{d r}{d t}=4 \pi r^{2} \cdot \frac{d r}{d t} \\
&=\left(4 \pi r^{2} \cdot \frac{1}{4 \pi r}\right)=r \quad[\text { using (ii) }] \\
& \Rightarrow\left[\frac{d V}{d t}\right]_{r=6 \mathrm{~cm}}=6 \mathrm{~cm}^{3} / \mathrm{sec} .
\end{aligned}
$$

Hence, the volume is increasing at the rate of **$6 \mathrm{~cm}^{3} / \mathrm{sec}$**.

---

### Example 6:

The volume of a cube is increasing at the rate of $7 \mathrm{~cm}^{3} / \mathrm{sec}$. How fast is its surface area increasing at the instant when the length of an edge of the cube is $12 \mathrm{~cm}$?
**[CBSE 2006C]**

#### Solution:

At any instant $t$, let the length of each edge of the cube be $x$, $V$ be its volume and $S$ be its surface area. Then,

$$
\begin{equation*}
\frac{d V}{d t}=7 \mathrm{~cm}^{3} / \mathrm{sec} \text { (given) } \tag{i}
\end{equation*}
$$

Now, $V=x^{3} \Rightarrow \frac{d V}{d t}=\frac{d V}{d x} \cdot \frac{d x}{d t}$

$$
\begin{aligned}
& \Rightarrow 7=\frac{d}{d x}\left(x^{3}\right) \cdot \frac{d x}{d t} \quad\left[\because \quad V=x^{3}\right] \\
& \Rightarrow 3 x^{2} \cdot \frac{d x}{d t}=7
\end{aligned}
$$

$$
\begin{align*}
& \Rightarrow \frac{d x}{d t}=\frac{7}{3 x^{2}}  \tag{ii}\\
& \therefore S=6 x^{2} \Rightarrow \frac{d S}{d t}=\frac{d S}{d x} \cdot \frac{d x}{d t} \\
& =\frac{d}{d x}\left(6 x^{2}\right) \cdot \frac{7}{3 x^{2}} \\
& =\left(12 x \times \frac{7}{3 x^{2}}\right)=\frac{28}{x} \\
& \Rightarrow\left[\frac{d S}{d t}\right]_{x=12}=\left(\frac{28}{12}\right) \mathrm{cm}^{2} / \mathrm{sec}=2 \frac{1}{3} \mathrm{~cm}^{2} / \mathrm{sec}
\end{align*}
$$

Hence, the surface area of the cube is increasing at the rate of **$2 \frac{1}{3} \mathrm{~cm}^{2} / \mathrm{sec}$** at the instant when its edge is $12 \mathrm{~cm}$.

---

### Example 7:

The length $x$ of a rectangle is decreasing at the rate of $5 \mathrm{~cm} /$ minute and the width $y$ is increasing at the rate of $4 \mathrm{~cm} /$ minute. When $x=8 \mathrm{~cm}$ and $y=6 \mathrm{~cm}$, find the rate of change of (i) the perimeter, and (ii) the area of the rectangle.

#### Solution:

Given that $\frac{d x}{d t}=-5 \mathrm{~cm} /$ minute and $\frac{d y}{d t}=4 \mathrm{~cm} /$ minute.

(i) Let $P$ be the perimeter of the rectangle at any instant. Then,

$$
\begin{aligned}
P=2(x+y) \Rightarrow \frac{d P}{d t} & =2\left(\frac{d x}{d t}+\frac{d y}{d t}\right)=2(-5+4) \mathrm{cm} / \text { minute } \\
& =-2 \mathrm{~cm} / \text { minute } .
\end{aligned}
$$

Hence, the perimeter of the rectangle is **decreasing at the rate of $2 \mathrm{~cm} /$ minute**.

(ii) Let $A$ be the area of the rectangle at any instant. Then,

$$
\begin{aligned}
A=x \cdot y \Rightarrow \frac{d A}{d t} & =\frac{d x}{d t} \cdot y+x \cdot \frac{d y}{d t} \\
& =[(-5) \times 6+8 \times 4] \mathrm{cm}^{2} / \text { minute } \\
& =2 \mathrm{~cm}^{2} / \text { minute } .
\end{aligned}
$$

Hence, the area of the rectangle is **increasing at the rate of $2 \mathrm{~cm}^{2} /$ minute**.

---

### Example 8:

Water is leaking from a conical funnel at the rate of $5 \mathrm{~cm}^{3} / \mathrm{sec}$. If the radius of the base of the funnel is $5 \mathrm{~cm}$ and its altitude is $10 \mathrm{~cm}$, find the rate at which the water level is dropping when it is $2.5 \mathrm{~cm}$ from the top.
**[CBSE 2004]**

#### Solution:

At any instant $t$, let $r$ be the radius of the water level, $h$ the height of the water level and $V$ the volume of the water in the conical funnel. Then,

$$
\begin{equation*}
\frac{d V}{d t}=-5 \quad \text { (given) } \tag{i}
\end{equation*}
$$

From similar $\triangle \mathrm{s} O A B$ and $O C D$, we have

$$
\frac{A B}{O A}=\frac{C D}{O C} \Rightarrow \frac{r}{h}=\frac{5}{10}=\frac{1}{2} \Rightarrow r=\frac{1}{2} h
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-134.jpg?height=366&width=327&top_left_y=149&top_left_x=880)

Now, $V=\frac{1}{3} \pi r^{2} h=\frac{1}{3} \pi \times\left(\frac{1}{2} h\right)^{2} \times h=\frac{1}{12} \pi h^{3}$.

$\therefore \quad \frac{d V}{d t}=\left(\frac{d V}{d h} \times \frac{d h}{d t}\right)=\frac{d}{d h}\left(\frac{1}{12} \pi h^{3}\right) \cdot \frac{d h}{d t}=\frac{\pi h^{2}}{4} \cdot \frac{d h}{d t}$

$\Rightarrow-5=\frac{\pi h^{2}}{4} \cdot \frac{d h}{d t}$

$$
\begin{equation*}
\Rightarrow \frac{d h}{d t}=\frac{-20}{\pi h^{2}} \tag{i}
\end{equation*}
$$

$\Rightarrow\left(\frac{d h}{d t}\right)_{h=7.5 \mathrm{~cm}}=\frac{-20}{\pi \times(7.5)^{2}} \quad[\because h=(10-2.5) \mathrm{cm}=7.5 \mathrm{~cm}]$

$$
=\frac{-16}{45 \pi} \mathrm{~cm} / \mathrm{sec} .
$$

Hence, the rate of change of water level at $h=7.5 \mathrm{~cm}$ is **$\frac{-16}{45 \pi} \mathrm{~cm} / \mathrm{sec}$**.

---

### Example 9:

Sand is pouring from a pipe at the rate of $12 \mathrm{~cm}^{3} / \mathrm{sec}$. The falling sand forms a cone on the ground in such a way that the height of the cone is always one-sixth of the radius of the base. How fast is the height of the sand cone increasing, when the height is $4 \mathrm{~cm}$?
**[CBSE 2011]**

#### Solution:

At any instant $t$, let $r$ be the radius, $h$ the height and $V$ the volume of the cone.
Then, $h=\frac{r}{6} \Rightarrow r=6 h$.

$\therefore V=\frac{1}{3} \pi r^{2} h=\frac{1}{3} \pi(6 h)^{2} h=12 \pi h^{3}$.

Now, $V=12 \pi h^{3} \Rightarrow \frac{d V}{d t}=\frac{d V}{d h} \times \frac{d h}{d t}$

$$
\begin{aligned}
& \Rightarrow 12=\frac{d}{d h}\left(12 \pi h^{3}\right) \times \frac{d h}{d t} \\
& \Rightarrow 12=36 \pi h^{2} \times \frac{d h}{d t} \\
& \Rightarrow \frac{d h}{d t}=\frac{1}{3 \pi h^{2}} \\
& \Rightarrow\left(\frac{d h}{d t}\right)_{h=4 \mathrm{~cm}}=\frac{1}{(3 \times \pi \times 4 \times 4)} \mathrm{cm} / \mathrm{sec} \\
& =\frac{1}{48 \pi} \mathrm{~cm} / \mathrm{sec}
\end{aligned}
$$

Hence, the rate of increase of the height of the sand cone at the instant when $h=4 \mathrm{~cm}$ is **$\frac{1}{48 \pi} \mathrm{~cm} / \mathrm{sec}$**.

---

### Example 10:

A $5-\mathrm{m}$ long ladder is leaning against a wall. The bottom of the ladder is pulled along the ground, away from the wall at the rate of $2 \mathrm{~m} / \mathrm{sec}$. How fast is its height on the wall decreasing when the foot of the ladder is $4 \mathrm{~m}$ away from the wall?

#### Solution:

Let $O C$ be the wall. At a certain instant $t$, let $A B$ be the position of the ladder such that $O A=x$ and $O B=y$.
Length of the ladder $A B=5 \mathrm{~m}$.
Given that $\frac{d x}{d t}=2 \mathrm{~m} / \mathrm{sec}$.

From right $\triangle A O B$, we have

$$
\begin{align*}
& x^{2}+y^{2}=25 \\
\Rightarrow & 2 x \cdot \frac{d x}{d t}+2 y \cdot \frac{d y}{d t}=0 \\
\Rightarrow & 2 x \cdot 2+2 y \cdot \frac{d y}{d t}=0 \quad\left[\because \frac{d x}{d t}=2\right] \\
\Rightarrow & \frac{d y}{d t}=\frac{-2 x}{y} \tag{i}
\end{align*}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-135.jpg?height=278&width=292&top_left_y=573&top_left_x=913)

Now, $x=4 \Rightarrow y=\sqrt{5^{2}-4^{2}}=3$.
Putting $x=4$, $y=3$ in (i) we get $\frac{d y}{d t}=\frac{-8}{3}$.

Hence, the required rate of decrease in the height of the ladder on the wall is **$(8 / 3) \mathrm{m} / \mathrm{sec}$**.

---

### Example 11:

The two equal sides of an isosceles triangle with fixed base $b \mathrm{~cm}$ are decreasing at the rate of $3 \mathrm{~cm} / \mathrm{sec}$. How fast is the area decreasing when each of the equal sides is equal to the base?
**[CBSE 2006C]**

#### Solution:

At a certain instant $t$, let $\triangle A B C$ be an isosceles triangle in which $A B=A C=x \mathrm{~cm}$ and $B C=b \mathrm{~cm}$.

$$
\begin{equation*}
\text { Then, } \frac{d x}{d t}=3 \mathrm{~cm} / \mathrm{sec} \text { (given) } \tag{i}
\end{equation*}
$$

Draw $A D \perp B C$. Then, $B D=D C=\frac{b}{2}$.
$\therefore A D=\sqrt{x^{2}-\frac{b^{2}}{4}}=\frac{\sqrt{4 x^{2}-b^{2}}}{2}$

$$
\begin{aligned}
& \therefore \quad A=\frac{1}{2} b \cdot \frac{\sqrt{4 x^{2}-b^{2}}}{2}=\frac{b \sqrt{4 x^{2}-b^{2}}}{4} \\
& \begin{aligned}
\Rightarrow \frac{d A}{d t} & =\frac{d A}{d x} \cdot \frac{d x}{d t} \\
& =\left(\frac{d A}{d x} \times 3\right) \quad\left[\because \frac{d x}{d t}=3 \mathrm{~cm} / \mathrm{sec}\right]
\end{aligned} \\
& \\
& =\frac{d}{d x}\left\{\frac{b \sqrt{4 x^{2}-b^{2}}}{4}\right\} \times 3 \\
& \\
& =\frac{3 b}{4} \cdot \frac{1}{2}\left(4 x^{2}-b^{2}\right)^{-1 / 2} \cdot(8 x)=\frac{3 b x}{\sqrt{4 x^{2}-b^{2}}} \cdot \\
& \therefore\left[\frac{d A}{d t}\right]_{x=b}=\frac{3 b^{2}}{\sqrt{4 b^{2}-b^{2}}}=\frac{3 b^{2}}{\sqrt{3} b}=\sqrt{3} b .
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-136.jpg?height=262&width=260&top_left_y=157&top_left_x=947)

Hence, the area is decreasing at the rate of **$\sqrt{3} b \mathrm{~cm}^{2} / \mathrm{sec}$**.

---

### Example 12:

A point source of light along a straight road is at a height of '$a$' metres. A boy '$b$' metres in height is walking along the road. How fast is his shadow increasing if he is walking away from the light at the rate of '$c$' metres per minute?
**[CBSE 2006C]**

#### Solution:

Let $A B$ be the lamp post, the lamp being at $B$. Then, $A B=a$ metres. At any instant $t$, let $C D$ be the position of the boy and $C E$ be his shadow. Then, $C D=b$ metres.
Let $A C=x$ metres and $C E=y$ metres.
Given that $\frac{d x}{d t}=c$ metres $/ \mathrm{min}$.

Clearly, $\triangle B A E \sim \triangle D C E$.
$\therefore \frac{A B}{C D}=\frac{A E}{C E}$
$\Rightarrow \frac{a}{b}=\frac{x+y}{y}$

![](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-136.jpg?height=204&width=337&top_left_y=1127&top_left_x=868)

$\Rightarrow(a-b) y=b x$
$\Rightarrow(a-b) \frac{d y}{d t}=b \cdot \frac{d x}{d t}=b c \quad\left[\because \frac{d x}{d t}=c\right]$
$\Rightarrow \frac{d y}{d t}=\frac{b c}{(a-b)} \mathrm{m} / \mathrm{min}$.

Hence, the shadow is increasing at the rate of **$\frac{b c}{(a-b)} \mathrm{m} / \mathrm{min}$**.

---

### Example 13:

A man $160 \mathrm{~cm}$ tall, walks away from a source of light situated at the top of a pole $6 \mathrm{~m}$ high, at the rate of $1.1 \mathrm{~m} / \mathrm{s}$. How fast is the length of his shadow increasing when he is $1 \mathrm{~m}$ away from the pole?

#### Solution:

Let $A B$ be the lamp post, the lamp being at $B$.
Then, $A B=6 \mathrm{~m}$.
At any instance $t$, let $M N$ be the position of the man and $M S$ be his shadow. Then, $M N=1.6 \mathrm{~m}$.
Let $A M=x$ metres and $M S=s$ metres.
Given that $\frac{d x}{d t}=1.1 \mathrm{~m} / \mathrm{s}$.

Clearly, $\triangle S A B \sim \triangle S M N$.
$\therefore \frac{A S}{M S}=\frac{A B}{M N}=\frac{6}{1.6}=\frac{15}{4}$

![](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-137.jpg?height=208&width=312&top_left_y=349&top_left_x=895)

$\Rightarrow \frac{x+s}{s}=\frac{15}{4} \Rightarrow x=\frac{11}{4} s$, where $M S=s$.
$\Rightarrow \frac{d x}{d t}=\frac{11}{4} \cdot \frac{d s}{d t} \Rightarrow 1.1=\frac{11}{4} \cdot \frac{d s}{d t}$
$\Rightarrow \frac{d s}{d t}=\left(\frac{1.1 \times 4}{11}\right)=0.4 \mathrm{~m} / \mathrm{s}$.

Hence, the length of the shadow is increasing at the rate of **$0.4 \mathrm{~m} / \mathrm{s}$**.

---

### Example 14:

A particle moves along the curve $6 y=x^{3}+2$. Find the points on the curve at which the $y$-coordinate is changing $8$ times as fast as the $x$-coordinate.
**[CBSE 2002]**

#### Solution:

Let the required point be $(x, y)$.
Given: $\frac{d y}{d t}=8 \frac{d x}{d t}$ (i)

Given curve is $6 y=x^{3}+2$ (ii)

On differentiating both sides of (ii) w.r.t. $t$, we get

$$
\begin{aligned}
& 6 \frac{d y}{d t}=3 x^{2} \frac{d x}{d t} \\
\Rightarrow & 6\left(8 \frac{d x}{d t}\right)=3 x^{2} \frac{d x}{d t} \quad[\text { using (i) }] \\
\Rightarrow & 3 x^{2}=48 \Rightarrow x^{2}=16 \Rightarrow x= \pm 4
\end{aligned}
$$

Putting $x=4$ in (ii), we get $y=11$.
Putting $x=-4$ in (ii), we get $y=\frac{-62}{6}=\frac{-31}{3}$.

Hence, the required points are **$(4,11)$** and **$\left(-4, \frac{-31}{3}\right)$**.

---

### Example 15:

Find the points on the curve $y^{2}=8 x$ for which the abscissa and ordinate change at the same rate.

#### Solution:

Let the required point be $(x, y)$.

Given: $\frac{d y}{d t}=\frac{d x}{d t}$ (i)

Given curve is $y^{2}=8 x$ (ii)

On differentiating both sides of (ii) w.r.t. $t$, we get

$$
\begin{aligned}
2 y \frac{d y}{d t} & =8 \frac{d x}{d t} \\
\Rightarrow 2 y \cdot \frac{d x}{d t} & =8 \frac{d x}{d t} \quad \text { [using (i)] } \\
\Rightarrow 2 y=8 & \Rightarrow y=4 .
\end{aligned}
$$

Putting $y=4$ in (ii), we get $8 x=16$ and therefore, $x=2$.
Hence, the required point is **$(2,4)$**.

---

### Example 16:

At what points of the ellipse $16 x^{2}+9 y^{2}=400$ does the ordinate decrease at the same rate at which the abscissa increases?

#### Solution:

Let the required point be $(x, y)$. Then,

$$
\begin{equation*}
\frac{d y}{d t}=-\frac{d x}{d t} \tag{i}
\end{equation*}
$$

Given curve is $16 x^{2}+9 y^{2}=400$ (ii)

On differentiating both sides of (ii) w.r.t. $t$, we get

$$
\begin{aligned}
& 32 x \cdot \frac{d x}{d t}+18 y \cdot \frac{d y}{d t}=0 \\
\Rightarrow & 32 x \cdot \frac{d x}{d t}+18 y \cdot\left(-\frac{d x}{d t}\right)=0 \quad \text { [using (i)] } \\
\Rightarrow & (32 x-18 y)=0 \Rightarrow y=\frac{16}{9} x .
\end{aligned}
$$

Putting $y=\frac{16}{9} x$ in (ii), we get

$$
16 x^{2}+9 \times\left(\frac{16 x}{9}\right)^{2}=400 \Rightarrow x^{2}=9 \Rightarrow x= \pm 3 .
$$

Now, $x=3 \Rightarrow y=\left(\frac{16}{9} \times 3\right)=\frac{16}{3}$,

$$
x=-3 \Rightarrow y=\left[\frac{16}{9} \times(-3)\right]=\frac{-16}{3} .
$$

Hence, the required points are **$\left(3, \frac{16}{3}\right)$** and **$\left(-3, \frac{-16}{3}\right)$**.

---

## Marginal Cost and Marginal Revenue

**Marginal Cost:** Let $C$ be the total cost of producing and marketing $x$ units of a product. Then, the marginal cost ($MC$) is defined as, $MC=\frac{d C}{d x}$.

**Marginal Revenue:** The rate of change of total revenue with respect to the quantity sold is called the marginal revenue ($MR$) and therefore, $MR=\frac{d R}{d x}$.

---

### Example 17:

The total cost $C(x)$ of producing $x$ items in a firm is given by
$$
C(x)=0.005 x^{3}-0.02 x^{2}+30 x+6000 .
$$
Find the marginal cost when $4$ units are produced.

#### Solution:

Given: $C(x)=0.005 x^{3}-0.02 x^{2}+30 x+6000$

$$
\begin{aligned}
& \Rightarrow M C=\frac{d C}{d x} \\
& \quad=\frac{d}{d x}\left(0.005 x^{3}-0.02 x^{2}+30 x+6000\right) \\
& \quad=\left\{\left(0.005 \times 3 x^{2}\right)-(0.02 \times 2 x)+30\right\} \\
& \Rightarrow[M C]_{x=4}=\left\{\left(0.005 \times 3 \times 4^{2}\right)-(0.02 \times 2 \times 4)+30\right\} \\
& \quad=(0.24-0.16+30)=30.08
\end{aligned}
$$

Hence, the required marginal cost is **₹ 30.08**.

---

### Example 18:

The total revenue received from the sale of $x$ units of a product is given by
$$
R(x)=3 x^{2}+40 x+10
$$
Find the marginal revenue when $x=5$.

#### Solution:

Given: $R(x)=3 x^{2}+40 x+10$

$$
\begin{aligned}
\Rightarrow \quad M R & =\frac{d R}{d x} \\
& =\frac{d}{d x}\left(3 x^{2}+40 x+10\right)=6 x+40 \\
\Rightarrow \quad[M R]_{x=5} & =(6 \times 5+40)=70 .
\end{aligned}
$$

Hence, the required marginal revenue is **₹ 70**.

---