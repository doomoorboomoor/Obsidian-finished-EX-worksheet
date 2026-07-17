## 17. Area of Bounded Regions

### 1. Area of a Curve Between Two Ordinates

Let $y=f(x)$ be a continuous and finite function in $[a, b]$.

**Case I: When the curve $y=f(x)$ lies above the x-axis**
The area bounded by the curve $y=f(x)$, the $x$-axis, and the ordinates $x=a$ and $x=b$ is given by

$$
\text { area }=\int_{a}^{b} y d x
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-273.jpg?height=272&width=302&top_left_y=491&top_left_x=911)

**Case II: When the curve $y=f(x)$ lies below the x-axis**
The area between the curve $y=f(x)$, the $x$-axis, and the ordinates $x=a$ and $x=b$ is given by

$$
\text { area }=\int_{a}^{b}(-y) d x
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-273.jpg?height=302&width=292&top_left_y=809&top_left_x=915)

### 2. Area of a Curve Between Two Abscissae

**Case I: When the curve $x=f(y)$ lies to the right of the y-axis**
The area bounded by the curve $x=f(y)$, the $y$-axis, and the abscissae $y=c$ and $y=d$ is given by

$$
\text { area }=\int_{c}^{d} x d y
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-273.jpg?height=271&width=298&top_left_y=1174&top_left_x=915)

**Case II: When the curve $x=f(y)$ lies to the left of the y-axis**
The area bounded by the curve $x=f(y)$, the $y$-axis, and the abscissae $y=c$ and $y=d$ is given by

$$
\text { area }=\int_{c}^{d}(-x) d y
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-273.jpg?height=292&width=314&top_left_y=1497&top_left_x=899)

### 3. Area Between Two Curves

The area bounded by two curves $y=f(x)$ and $y=g(x)$, which are intersected by the ordinates $x=a$ and $x=b$, is given by

$$
\text { area }=\int_{a}^{b}\{f(x)-g(x)\} d x
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-274.jpg?height=270&width=323&top_left_y=149&top_left_x=884)

---

## Solved Examples

### Example 1

Using integration, find the area of the region bounded by the line $2 y+x=8$, the $x$-axis and the lines $x=2$ and $x=4$.
[CBSE 2002C]

#### Solution:

The given line $A B$ is

$$
\begin{equation*}
2 y+x=8 \Rightarrow y=4-\frac{1}{2} x . \tag{i}
\end{equation*}
$$

Required area $=$ area $P L M Q P$
$=$ area between the line $y=4-\frac{1}{2} x$, and the $x$-axis between $x=2$ and $x=4$
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-274.jpg?height=337&width=398&top_left_y=740&top_left_x=809)

$$
=\int_{2}^{4} y_{A B} d x=\int_{2}^{4}\left(4-\frac{1}{2} x\right) d x
$$

$$
=\left[4 x-\frac{1}{4} x^{2}\right]_{2}^{4}=(12-7) \text{ sq units}
$$

$=5$ sq units.

Hence, the required area is **5 sq units**.

---

### Example 2

Using integration, find the area of $\triangle A B C$ whose vertices are $A(2,3)$, $B(4,7)$ and $C(6,2)$.
[CBSE 2001]

#### Solution:

The equation of $A B$ is

$$
\frac{y-3}{x-2}=\frac{7-3}{4-2} \Rightarrow y=2 x-1
$$

The equation of $B C$ is

$$
\frac{y-7}{x-4}=\frac{2-7}{6-4} \Rightarrow y=\frac{-5}{2} x+17
$$

The equation of $A C$ is

$$
\frac{y-3}{x-2}=\frac{2-3}{6-2} \Rightarrow y=\frac{-1}{4} x+\frac{7}{2}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-274.jpg?height=314&width=394&top_left_y=1528&top_left_x=809)

Draw $A L \perp O X$, $B M \perp O X$ and $C N \perp O X$.
Area of $\triangle A B C = (\text{area } A L M B A + \text{area } B M N C B) - (\text{area } A L N C A)$

$$
\begin{aligned}
& =\int_{2}^{4} y_{A B} d x+\int_{4}^{6} y_{B C} d x-\int_{2}^{6} y_{A C} d x \\
& =\int_{2}^{4}(2 x-1) d x+\int_{4}^{6}\left(-\frac{5}{2} x+17\right) d x-\int_{2}^{6}\left(-\frac{1}{4} x+\frac{7}{2}\right) d x \\
& =\left[x^{2}-x\right]_{2}^{4}+\left[-\frac{5}{4} x^{2}+17 x\right]_{4}^{6}-\left[-\frac{1}{8} x^{2}+\frac{7}{2} x\right]_{2}^{6} \\
& =\left[(12-2)+(57-48)-\left(\frac{33}{2}-\frac{13}{2}\right)\right] \text { sq units } \\
& =9 \text { sq units. }
\end{aligned}
$$

Hence, the required area is **9 sq units**.

---

### Example 3

Calculate the area bounded by the parabola $y^{2}=4 a x$ and its latus rectum.

#### Solution:

Let $S(a, 0)$ be the focus of the parabola $y^{2}=4 a x$. Then, its latus rectum $L S L^{\prime}$ is the line parallel to the $y$-axis at a distance $a$ from it. So, its equation is $x=a$.
Since the equation of the parabola contains only even powers of $y$, it is symmetrical about the $x$-axis.
$\therefore$ **Required Area**

$$
\begin{aligned}
& =\operatorname{area} L O L^{\prime} L \\
& =(\operatorname{area} L O S L)+\left(\operatorname{area} S O L^{\prime} S\right) \\
& =2 \times(\operatorname{area} L O S L) \\
& =2 \int_{0}^{a} y d x=2 \cdot \int_{0}^{a} 2 \sqrt{a x} d x \\
& =4 \sqrt{a} \cdot \frac{2}{3}\left[x^{3 / 2}\right]_{0}^{a}=\frac{8}{3} a^{2} \text { sq units. }
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-275.jpg?height=286&width=376&top_left_y=1068&top_left_x=829)

---

### Example 4

Using integration, find the area of the region bounded by the parabola $y^{2}=16 x$ and the line $x=4$.
[CBSE 1996, '97]

#### Solution:

$y^{2}=16 x$ is a right-handed parabola with its vertex at the origin.
And, $x=4$ is the line parallel to the $y$-axis at a distance of 4 units from it.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-275.jpg?height=307&width=498&top_left_y=1599&top_left_x=709)

Also, $y^{2}=16 x$ contains only even powers of $y$.
So, it is symmetrical about the $x$-axis.

$$
\begin{aligned}
\therefore \text { required area } & =\text { area } A O C A+\text { area } B O C B \\
& =2(\text { area } A O C A) \\
& =2 \int_{0}^{4} y d x=2 \int_{0}^{4} \sqrt{16 x} d x \\
& =8 \int_{0}^{4} \sqrt{x} d x=8 \times \frac{2}{3} \times\left[x^{3 / 2}\right]_{0}^{4} \\
& =\frac{16}{3} \times(4)^{3 / 2}=\left(\frac{16}{3} \times 8\right)=\frac{128}{3} \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\frac{128}{3}$ sq units**.

---

### Example 5

Using integration, find the area enclosed by the parabola $y^{2}=4 a x$ and the chord $y=m x$.

#### Solution:

The given equations are

$$
\begin{align*}
y^{2} & =4 a x  \tag{i}\\
\text { and } \quad y & =m x \tag{ii}
\end{align*}
$$

Clearly, $y^{2}=4 a x$ is a righthanded parabola, passing through the origin.
And $y=m x$ is a line passing
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-276.jpg?height=297&width=439&top_left_y=884&top_left_x=774)
through the origin.
In order to find the points of intersection of the given parabola and the given line, we solve (i) and (ii) simultaneously.
Putting $y=m x$ from (ii) into (i), we get

$$
\begin{aligned}
m^{2} x^{2}=4 a x & \Rightarrow x\left(m^{2} x-4 a\right)=0 \\
& \Rightarrow x=0 \text { or } x=\frac{4 a}{m^{2}}
\end{aligned}
$$

Now, $(x=0 \Rightarrow y=0)$ and $\left(x=\frac{4 a}{m^{2}} \Rightarrow y=\frac{4 a}{m}\right)$.
So, the points of intersection of the given parabola and the chord are

$$
O(0,0) \text { and } A\left(\frac{4 a}{m^{2}}, \frac{4 a}{m}\right)
$$

Draw $A M \perp O X$.
**Required Area** $= (\text{area } O B A M O) - (\text{area } O A M O)$

$$
\begin{aligned}
& =\int_{0}^{4 a / m^{2}}(y \text { for the parabola }) d x-\int_{0}^{4 a / m^{2}}(y \text { for the line }) d x \\
& =\int_{0}^{4 a / m^{2}} 2 \sqrt{a x} d x-\int_{0}^{4 a / m^{2}} m x d x \\
& =2 \sqrt{a} \cdot \frac{2}{3}\left[x^{3 / 2}\right]_{0}^{4 a / m^{2}}-\left[\frac{m x^{2}}{2}\right]_{0}^{4 a / m^{2}} \\
& =\left[\frac{4 \sqrt{a}}{3} \cdot \frac{8}{m^{3}} a^{3 / 2}-\frac{m}{2} \cdot \frac{16 a^{2}}{m^{4}}\right] \\
& =\left(\frac{32 a^{2}}{3 m^{3}}-\frac{8 a^{2}}{m^{3}}\right)=\left(\frac{8 a^{2}}{3 m^{3}}\right) \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\left(\frac{8 a^{2}}{3 m^{3}}\right)$ sq units**.

---

### Example 6

Find the area of the region $\left\{(x, y): x^{2} \leq y \leq x\right\}$.
[CBSE 2007, '13C]

#### Solution:

Consider the equations

$$
\begin{align*}
y & =x^{2}  \tag{i}\\
\text { and } y & =x \tag{ii}
\end{align*}
$$

Clearly, $y=x^{2}$ is an upward parabola and $y=x$ is a line passing through $(0,0)$.
Solving (i) and (ii) simultaneously, we get

$$
\begin{aligned}
x^{2}=x & \Rightarrow x^{2}-x=0 \Rightarrow x(x-1)=0 \\
& \Rightarrow x=0 \text { or } x=1 .
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-277.jpg?height=380&width=372&top_left_y=911&top_left_x=837)

From (ii), ($x=0 \Rightarrow y=0$) and ($x=1 \Rightarrow y=1$).
So, the points of intersection of (i) and (ii) are $O(0,0)$ and $A(1,1)$.
Draw $A M \perp O X$.
**Required Area** $=$ shaded area

$$
\begin{aligned}
& =(\text { area } O M A O)-(\text { area } O M A C O) \\
& =\int_{0}^{1}(y \text { for line }) d x-\int_{0}^{1}(y \text { for parabola }) d x \\
& =\int_{0}^{1} x d x-\int_{0}^{1} x^{2} d x=\left[\frac{x^{2}}{2}\right]_{0}^{1}-\left[\frac{x^{3}}{3}\right]_{0}^{1}=\left[\frac{1}{2}-\frac{1}{3}\right]=\frac{1}{6} \text { sq unit. }
\end{aligned}
$$

Hence, the required area is **$\frac{1}{6}$ sq unit**.

---

### Example 7

Find the area of the region bounded by the curve $x^{2}=4 y$ and the line

$$
\begin{equation*}
x=4 y-2 . \tag{i}
\end{equation*}
$$

[CBSE 2010, '13]

#### Solution:

The given curve is $x^{2}=4 y$

The given line is $x=4 y-2$
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-278.jpg?height=310&width=506&top_left_y=337&top_left_x=408)

Putting $4 y=(x+2)$ from (ii) into (i), we get

$$
\begin{aligned}
x^{2}=(x+2) & \Leftrightarrow\left(x^{2}-x-2\right)=0 \\
& \Leftrightarrow(x-2)(x+1)=0 \\
& \Leftrightarrow x=2 \text { or } x=-1 .
\end{aligned}
$$

Putting $x=2$ in (i), we get $y=1$.
Putting $x=-1$ in (i), we get $y=\frac{1}{4}$.
Thus, the points of intersection of the given curve (i) and the line (ii) are $A\left(-1, \frac{1}{4}\right)$ and $B(2,1)$.

Draw $A L$ and $B M$ as perpendiculars on the $x$-axis.
$\therefore$ **Required Area** $=$ area $A O B A$

$$
\begin{aligned}
& =(\text { area } A L M B A)-(\text { area } A O B M L A) \\
& =\int_{-1}^{2}\left(\frac{x+2}{4}\right) d x-\int_{-1}^{2} \frac{x^{2}}{4} d x \\
& =\int_{-1}^{2}\left\{\frac{(x+2)}{4}-\frac{x^{2}}{4}\right\} d x=\frac{1}{4}\left[\frac{x^{2}}{2}+2 x-\frac{x^{3}}{3}\right]_{-1}^{2} \\
& =\frac{1}{4}\left[\left(2+4-\frac{8}{3}\right)-\left(\frac{1}{2}-2+\frac{1}{3}\right)\right]=\frac{9}{8} \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\frac{9}{8}$ sq units**.

---

### Example 8

Find the area bounded by the circle $x^{2}+y^{2}=16$ and the line $y=x$ in the first quadrant.
[CBSE 2004]

#### Solution:

The given circle is $x^{2}+y^{2}=16$

The given line is $y=x$
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-279.jpg?height=435&width=467&top_left_y=149&top_left_x=426)

Putting $y=x$ from (ii) into (i), we get
$2 x^{2}=16 \Leftrightarrow x^{2}=8 \Leftrightarrow x=2 \sqrt{2} \quad[\because x$ is +ve in the first quad. $]$.
Thus, the point of intersection of (i) and (ii) in the first quadrant is $A(2 \sqrt{2}, 2 \sqrt{2})$.

Draw $A L$ perpendicular on the $x$-axis.
$\therefore$ **Required Area** $= (\text{area } O L A) + \operatorname{area}(L B A L)$

$$
\begin{aligned}
& =\int_{0}^{2 \sqrt{2}} x d x+\int_{2 \sqrt{2}}^{4} \sqrt{16-x^{2}} d x \\
& =\left[\frac{x^{2}}{2}\right]_{0}^{2 \sqrt{2}}+\left[\frac{x \sqrt{16-x^{2}}}{2}+\frac{16}{2} \sin ^{-1} \frac{x}{4}\right]_{2 \sqrt{2}}^{4} \\
& =\frac{1}{2}\left[(2 \sqrt{2})^{2}-0\right]+\left[\left(0+8 \sin ^{-1} 1\right)-\left(4+8 \sin ^{-1} \frac{1}{\sqrt{2}}\right]\right. \\
& =\left[4+\left(8 \times \frac{\pi}{2}\right)-4-\left(8 \times \frac{\pi}{4}\right)\right]=(2 \pi) \text { sq units. }
\end{aligned}
$$

---

### Example 9

Using integration, find the area of $\triangle A B C$, whose vertices are $A(2,0)$, $B(4,5)$ and $C(6,3)$.
[CBSE 2003C, '06C]

#### Solution:

The equation of side $A B$ is

$$
\begin{equation*}
\frac{y-0}{x-2}=\frac{(5-0)}{(4-2)} \Rightarrow y=\frac{5}{2}(x-2) \tag{i}
\end{equation*}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-279.jpg?height=276&width=459&top_left_y=1577&top_left_x=432)

The equation of side $B C$ is

$$
\begin{equation*}
\frac{y-5}{x-4}=\frac{(3-5)}{(6-4)} \Rightarrow y=-x+9 \tag{ii}
\end{equation*}
$$

The equation of side $A C$ is

$$
\begin{equation*}
\frac{y-0}{x-2}=\frac{(3-0)}{(6-2)} \Rightarrow y=\frac{3}{4}(x-2) \tag{iii}
\end{equation*}
$$

Draw perpendiculars $B L$ and $C M$ on the $x$-axis.
$\therefore$ **Area of $\triangle A B C$**

$$
\begin{aligned}
& =\operatorname{ar}(\triangle A L B)+\operatorname{ar}(\text { trap. BLMC })-\operatorname{ar}(\triangle A M C) \\
& =\int_{2}^{4} y_{A B} d x+\int_{4}^{6} y_{B C} d x-\int_{2}^{6} y_{A C} d x \\
& =\frac{5}{2} \int_{2}^{4}(x-2) d x+\int_{4}^{6}(9-x) d x-\frac{3}{4} \int_{2}^{6}(x-2) d x \\
& =\frac{5}{2}\left[\frac{x^{2}}{2}-2 x\right]_{2}^{4}+\left[9 x-\frac{x^{2}}{2}\right]_{4}^{6}-\frac{3}{4} \cdot\left[\frac{x^{2}}{2}-2 x\right]_{2}^{6} \\
& =\frac{5}{2}[0-(-2)]+(36-28)-\frac{3}{4}[6-(-2)] \\
& =(5+8-6) \text { sq units }=7 \text { sq units. }
\end{aligned}
$$

---

### Example 10

Find the area cut off from the parabola $4 y=3 x^{2}$ by the straight line

$$
3 x-2 y+12=0 .
$$

[CBSE 2007, '09]

#### Solution:

Clearly, $4 y=3 x^{2}$ is an upward parabola with its vertex at ( 0,0 ). And, $3 x-2 y+12=0$ is a line.
The given equations are

$$
\begin{align*}
4 y & =3 x^{2}  \tag{i}\\
\text { and } 3 x-2 y+12 & =0 \tag{ii}
\end{align*}
$$

The points of intersection of the given parabola and the given line will be obtained by solving (i) and (ii) simultaneously.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-280.jpg?height=361&width=388&top_left_y=1178&top_left_x=817)

Putting $y=\frac{3}{4} x^{2}$ from (i) in (ii), we get

$$
\begin{aligned}
3 x-\frac{3}{2} x^{2}+12=0 & \Rightarrow x^{2}-2 x-8=0 \\
& \Rightarrow x^{2}-4 x+2 x-8=0 \\
& \Rightarrow x(x-4)+2(x-4)=0 \\
& \Rightarrow(x-4)(x+2)=0 \\
& \Rightarrow x=-2 \text { or } x=4
\end{aligned}
$$

Now, $(x=-2 \Rightarrow y=3)$ and $(x=4 \Rightarrow y=12)$.
So, the points of intersection of (i) and (ii) are $A(-2,3)$ and $B(4,12)$.
Draw $A L \perp O X^{\prime}$ and $B M \perp O X$.
**Required Area** $= (\text{area } A L M B A) - (\text{area } A L O M B O A)$

$$
\begin{aligned}
& =\int_{-2}^{4}(y \text { of the line }) d x-\int_{-2}^{4}(y \text { of the parabola }) d x \\
& =\int_{-2}^{4} \frac{(3 x+12)}{2} d x-\int_{-2}^{4} \frac{3 x^{2}}{4} d x=\left[\frac{3 x^{2}}{4}+6 x\right]_{-2}^{4}-\left[\frac{x^{3}}{4}\right]_{-2}^{4} \\
& =(45-18)=27 \text { sq units. }
\end{aligned}
$$

Hence, the required area is **27 sq units**.

---

### Example 11

Find the area bounded by the line $y=x$, the $x$-axis and the ordinates $x=-1, x=2$.

#### Solution:

We know that $y=x$ is the line passing through the origin and making an angle of $45^{\circ}$ with the $x$-axis, as shown in the given figure.
Now, we have to find the area of the shaded region.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-281.jpg?height=346&width=563&top_left_y=996&top_left_x=379)

**Required Area**

$$
\begin{aligned}
& =(\text { area } O D B O)+(\text { area } O A C O) \\
& =\int_{0}^{2} y d x+\int_{-1}^{0}(-y) d x \quad[\because \text { area } O A C O \text { is below the } x \text {-axis }] \\
& =\int_{0}^{2} x d x+\int_{-1}^{0}(-x) d x \\
& =\left[\frac{x^{2}}{2}\right]_{0}^{2}+\left[\frac{-x^{2}}{2}\right]_{-1}^{0}=\left[2+\frac{1}{2}\right]=\frac{5}{2} \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\frac{5}{2}$ sq units**.

---

### Example 12

Find by integration, the area of the region bounded by the curve $y=2 x-x^{2}$ and the $x$-axis.

#### Solution:

The given curve is $y=2 x-x^{2}$.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-282.jpg?height=408&width=934&top_left_y=286&top_left_x=279)

$$
\begin{aligned}
X=0, Y=0 & \Rightarrow x-1=0 \text { and } y-1=0 \\
& \Rightarrow x=1 \text { and } y=1 .
\end{aligned}
$$

Thus, the vertex of the parabola is $A(1,1)$.
Also, $y=0 \Rightarrow 2 x-x^{2}=0 \Rightarrow x(2-x)=0 \Rightarrow x=0$ or $x=2$.
Thus, the curve cuts the $x$-axis at $O(0,0)$ and $B(2,0)$.
The rough sketch of the curve can now be drawn, as shown in the given figure.

$$
\begin{aligned}
\therefore \text { required area } & =\int_{0}^{2} y d x \\
& =\int_{0}^{2}\left(2 x-x^{2}\right) d x=\left[x^{2}-\frac{x^{3}}{3}\right]_{0}^{2} \\
& =\left(4-\frac{8}{3}\right)=\frac{4}{3} \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\frac{4}{3}$ sq units**.

---

### Example 13

Using integration, find the area of the region bounded by the ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$.

#### Solution:

The given equation contains only even powers of $y$.
So, the curve is symmetrical about the $x$-axis.
Also, the given equation contains only even powers of $x$.
So, the curve is symmetrical about the $y$-axis.
A rough sketch of the ellipse can be drawn, as shown in the figure.

Now, $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \Rightarrow y=\frac{b}{a} \cdot \sqrt{a^{2}-x^{2}}$.
Area of the given ellipse

$$
\begin{aligned}
& =4 \times(\operatorname{area} O B C O) \\
& =4 \times \int_{0}^{a} y d x=4 \times \int_{0}^{a} \frac{b}{a} \cdot \sqrt{a^{2}-x^{2}} d x \\
& =\frac{4 b}{a} \cdot \int_{0}^{\pi / 2} a^{2} \cos ^{2} \theta d \theta \quad[\text { putting } x=a \sin \theta \text { so that } d x=a \cos \theta d \theta] \\
& =(4 a b) \cdot \int_{0}^{\pi / 2} \frac{(1+\cos 2 \theta)}{2} d \theta=(2 a b) \cdot\left[\theta+\frac{\sin 2 \theta}{2}\right]_{0}^{\pi / 2} \\
& =(\pi a b) \text { sq units. }
\end{aligned}
$$

Hence, the area of the ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$ is **($\pi a b$) sq units**.

---

### Example 14

By using integration, prove that the area of a circle of radius $r$ units is $\pi r^{2}$ square units.

#### Solution:

The equation of a circle of radius $r$ units with its centre at the origin is

$$
\begin{equation*}
x^{2}+y^{2}=r^{2} \tag{i}
\end{equation*}
$$

This equation contains only even powers of $y$.
So, the curve is symmetrical about the $x$-axis.
Also, the above equation contains only even powers of $x$.
So, the curve is symmetrical about the $y$-axis.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-283.jpg?height=400&width=433&top_left_y=958&top_left_x=776)

Now, $x^{2}+y^{2}=r^{2} \Rightarrow y=\sqrt{r^{2}-x^{2}}$.
Area of the circle $=4 \times($ area $O A B O)$

$$
\begin{aligned}
& =4 \times \int_{0}^{r} y d x=4 \times \int_{0}^{r} \sqrt{r^{2}-x^{2}} d x \\
& \left.=4 \times \int_{0}^{\pi / 2} r^{2} \cos ^{2} \theta d \theta \quad \text { [putting } x=r \sin \theta\right] \\
& =4 r^{2} \cdot \int_{0}^{\pi / 2} \frac{(1+\cos 2 \theta)}{2} d \theta=2 r^{2} \cdot\left[\theta+\frac{\sin 2 \theta}{2}\right]_{0}^{\pi / 2} \\
& =\left(\pi r^{2}\right) \text { sq units. }
\end{aligned}
$$

Hence, the required area is **($\pi r^{2}$) sq units**.

---

### Example 15

Find the area of the smaller region bounded by the ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$ and the straight line $\frac{x}{a}+\frac{y}{b}=1$.
[CBSE 2004, '05C]

#### Solution:

The ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$ and the line $\frac{x}{a}+\frac{y}{b}=1$ can be drawn, as shown in the given figure.

Then, we have to find the area of the shaded region.
**Required Area**
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-284.jpg?height=327&width=451&top_left_y=306&top_left_x=756)
$=\left\{\right.$ area between $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$ and the $x$-axis from $x=0$ to $\left.x=a\right\}$

- \{area between the line $\frac{x}{a}+\frac{y}{b}=1$ and the $x$-axis from $x=0$ to $x=a$ \}
$=\int_{0}^{a}(y$ of the ellipse $) d x-\int_{0}^{a}(y$ of the line $) d x$
$=\int_{0}^{a} \frac{b}{a} \cdot \sqrt{a^{2}-x^{2}} d x-\int_{0}^{a} \frac{b(a-x)}{a} d x$
$=\frac{b}{a} \cdot\left[\frac{x \sqrt{a^{2}-x^{2}}}{2}+\frac{a^{2}}{2} \sin ^{-1} \frac{x}{a}\right]_{0}^{a}-\frac{b}{a} \cdot\left[a x-\frac{x^{2}}{2}\right]_{0}^{a}$
$=\frac{a b}{2}\left(\sin ^{-1} 1-\sin ^{-1} 0\right)-\left(a b-\frac{a b}{2}\right)=\left(\frac{\pi a b}{4}-\frac{a b}{2}\right)$ sq units.

Hence, the required area is **$\left(\frac{\pi a b}{4}-\frac{a b}{2}\right)$ sq units**.

---

### Example 16

Find the area of the region bounded by the parabolas $x^{2}=y$ and $y^{2}=x$.
[CBSE 2012C]

#### Solution:

Clearly, $x^{2}=y$ is an upward parabola with its vertex at $(0,0)$ and $y^{2}=x$ is a right-handed parabola with its vertex also at $(0,0)$.
The shaded region shows the area bounded by these parabolas.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-284.jpg?height=386&width=483&top_left_y=1481&top_left_x=726)

The given equations are

$$
\text { and } \quad \begin{align*}
& x^{2}=y  \tag{i}\\
& y^{2}=x \tag{ii}
\end{align*}
$$

Using (i) in (ii), we get

$$
x^{4}=x \Rightarrow x\left(x^{3}-1\right)=0 \Rightarrow x=0 \text { or } x=1 .
$$

Also, $(x=0 \Rightarrow y=0)$ and $(x=1 \Rightarrow y=1)$.
So, the given curves intersect at $O(0,0)$ and $A(1,1)$.
Draw $A L \perp O X$.

$$
\begin{aligned}
\text { Required area }= & (\text { area } O L A B O)-(\text { area } O L A C O) \\
= & \left\{\text { area bounded by } y^{2}=x \text { from } x=0 \text { to } x=1\right\} \\
& \quad-\left\{\text { area bounded by } x^{2}=y \text { from } x=0 \text { to } x=1\right\} \\
= & \int_{0}^{1} \sqrt{x} d x-\int_{0}^{1} x^{2} d x \\
= & {\left[\frac{2}{3} x^{3 / 2}\right]_{0}^{1}-\left[\frac{x^{3}}{3}\right]_{0}^{1}=\left(\frac{2}{3}-\frac{1}{3}\right)=\frac{1}{3} \text { sq unit. } }
\end{aligned}
$$

Hence, the required area is **$\frac{1}{3}$ sq unit**.

---

### Example 17

Find the area of the region included between the parabolas $y^{2}=4 a x$ and $x^{2}=4 a y$, where $a>0$.
[CBSE 2003, '04, '08, '09, '12C]

#### Solution:

The given parabolas are

$$
\begin{align*}
y^{2} & =4 a x  \tag{i}\\
\text { and } x^{2} & =4 a y \tag{ii}
\end{align*}
$$

In order to find the points of intersection of the given curves, we solve (i) and (ii) simultaneously.
Putting $x=\frac{y^{2}}{4 a}$ from (i) in (ii),
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-285.jpg?height=394&width=490&top_left_y=1104&top_left_x=723)
we get

$$
\begin{aligned}
\frac{y^{4}}{16 a^{2}}=4 a y & \Rightarrow y^{4}-64 a^{3} y=0 \\
& \Rightarrow y\left(y^{3}-64 a^{3}\right)=0 \\
& \Rightarrow y=0 \text { or } y=4 a
\end{aligned}
$$

Now, $(y=0 \Rightarrow x=0)$ and $\left(y=4 a \Rightarrow x=\frac{16 a^{2}}{4 a}=4 a\right)$.
Thus, the points of intersection of the two parabolas are $O(0,0)$ and $A(4 a, 4 a)$.

Draw $A D \perp O X$. Then, point $D$ is ($4 a, 0$).

$$
\begin{aligned}
\text { Required area } & =\text { area } O C A B O \\
& =(\text { area } O B A D O)-(\text { area } O C A D O) \\
& =\int_{0}^{4 a} y d x \text { for }\left(y^{2}=4 a x\right)-\int_{0}^{4 a} y d x \text { for }\left(x^{2}=4 a y\right) \\
& =\int_{0}^{4 a} 2 \sqrt{a x} d x-\int_{0}^{4 a} \frac{x^{2}}{4 a} d x \\
& =\left[2 \sqrt{a} \cdot \frac{2}{3} \cdot x^{3 / 2}\right]_{0}^{4 a}-\frac{1}{4 a}\left[\frac{x^{3}}{3}\right]_{0}^{4 a} \\
& =\left[\frac{4 \sqrt{a}}{3} \cdot(4 a)^{3 / 2}-\frac{1}{12 a} \times 64 a^{3}\right] \\
& =\left(\frac{32 a^{2}}{3}-\frac{16 a^{2}}{3}\right)=\left(\frac{16 a^{2}}{3}\right) \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\left(\frac{16 a^{2}}{3}\right)$ sq units**.

---

### Example 18

Using integration, find the area of the region common to the circle $x^{2}+y^{2}=16$ and the parabola $y^{2}=6 x$.
[CBSE 2012C]

#### Solution:

$x^{2}+y^{2}=16$ is a circle with its centre at ( 0,0 ) and radius $=4$ units. And, $y^{2}=6 x$ is a right-handed parabola with its vertex at ( 0,0 ).
Now, we have to find the area of the shaded region.
The given equations are

$$
\begin{align*}
x^{2}+y^{2} & =16  \tag{i}\\
\text { and } \quad y^{2} & =6 x \tag{ii}
\end{align*}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-286.jpg?height=453&width=482&top_left_y=1043&top_left_x=725)

Using (ii) in (i), we get

$$
\begin{aligned}
x^{2}+6 x-16=0 & \Rightarrow(x+8)(x-2)=0 \\
& \Rightarrow x=-8 \text { or } x=2 .
\end{aligned}
$$

Now, $x=-8 \Rightarrow y^{2}=-48$
$\Rightarrow y$ is imaginary.
And, $x=2 \Rightarrow y^{2}=(6 \times 2)=12$

$$
\Rightarrow y= \pm 2 \sqrt{3} .
$$

Thus, the points of intersection of the given curves are $A(2,2 \sqrt{3})$ and $B(2,-2 \sqrt{3})$.

Since each of the given equations contains only even powers of $y$, each one is symmetrical about the $x$-axis.

$$
\begin{aligned}
\therefore \text { required area } & =2(\text { area } O C D A O) \\
& =2(\text { area } O C A O+\text { area } C D A C) \\
& =2\left[\int_{0}^{2} y d x \text { for curve }(\mathrm{ii})+\int_{2}^{4} y d x \text { for curve }(\mathrm{i})\right] \\
& =2\left[\int_{0}^{2} \sqrt{6 x} d x+\int_{2}^{4} \sqrt{16-x^{2}} d x\right] \\
& =2\left\{\left[\frac{2 \sqrt{6}}{3} x^{3 / 2}\right]_{0}^{2}+\left[x \sqrt{\frac{16-x^{2}}{2}}+\frac{16}{2} \sin ^{-1} \frac{x}{4}\right]_{2}^{4}\right\} \\
& =\left\{\left(\frac{2 \sqrt{6}}{3} \cdot 2^{3 / 2}-0\right)+8 \sin ^{-1} 1-\left(2 \sqrt{3}+8 \sin ^{-1} \frac{1}{2}\right)\right\} \\
& =2\left(\frac{8 \sqrt{3}}{3}+4 \pi-2 \sqrt{3}-\frac{4 \pi}{3}\right)=2\left(\frac{2 \sqrt{3}}{3}+\frac{8 \pi}{3}\right) \\
& =\frac{4}{3}(\sqrt{3}+4 \pi) \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\frac{4}{3}(\sqrt{3}+4 \pi)$ sq units**.

---

### Example 19

Using integration, find the area of the region enclosed between the circles

$$
x^{2}+y^{2}=4 \text { and }(x-2)^{2}+y^{2}=4 .
$$

[CBSE 2009, '13C]

#### Solution:

$x^{2}+y^{2}=4$ is a circle with its centre at $O(0,0)$ and radius $=2$ units.
And, $(x-2)^{2}+y^{2}=4$ is a circle with its centre at $C(2,0)$ and radius $=2$ units.

The given circles are

$$
\begin{array}{r}
x^{2}+y^{2}=4 \\
\text { and }(x-2)^{2}+y^{2}=4 \tag{ii}
\end{array}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-287.jpg?height=426&width=569&top_left_y=1473&top_left_x=373)

Eliminating $y$ from (i) and (ii), we get

$$
4-x^{2}=4-(x-2)^{2} \Rightarrow 4 x=4 \Rightarrow x=1 .
$$

Putting $x=1$ in (i), we get $y^{2}=3 \Rightarrow y= \pm \sqrt{3}$.
Thus, the points of intersection of the two circles are $A(1, \sqrt{3})$ and $B(1,-\sqrt{3})$.
Both the circles are symmetrical about the $x$-axis.

$$
\begin{aligned}
\text { Required area } & =2(\text { area } A O C A) \\
& =2(\text { area } A O D A+\text { area } C A D C) \\
& =2 \int_{0}^{1} y d x \text { for circle }(\text { ii })+2 \int_{1}^{2} y d x \text { for circle }(\mathrm{i}) \\
& =2 \int_{0}^{1} \sqrt{4-(x-2)^{2}} d x+2 \int_{1}^{2} \sqrt{4-x^{2}} d x \\
& =\left[\frac{(x-2) \sqrt{4-(x-2)^{2}}}{2}+\frac{4}{2} \cdot \sin ^{-1} \frac{(x-2)}{2}\right]_{0}^{1} \\
& \quad+\left[\frac{x \sqrt{4-x^{2}}}{2}+\frac{4}{2} \cdot \sin ^{-1} \frac{x}{2}\right]_{1}^{2} \\
& =2\left[\left\{\frac{-\sqrt{3}}{2}+2 \sin ^{-1}\left(\frac{-1}{2}\right)\right\}-\left\{0+2 \sin ^{-1}(-1)\right\}\right. \\
& \left.\quad+\left\{2 \sin ^{-1}(1)-\frac{\sqrt{3}}{2}-2 \sin ^{-1}\left(\frac{1}{2}\right)\right\}\right] \\
& =2\left\{\frac{-\sqrt{3}}{2}+2\left(-\frac{\pi}{6}\right)-2\left(-\frac{\pi}{2}\right)+\left(2 \cdot \frac{\pi}{2}-\frac{\sqrt{3}}{2}-2 \times \frac{\pi}{6}\right)\right\} \\
& =2\left(\frac{4 \pi}{3}-\sqrt{3}\right) \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$2\left(\frac{4 \pi}{3}-\sqrt{3}\right)$ sq units**.

---

### Example 20

Using integration, find the area of the region

$$
\left\{(x, y): y^{2} \leq 4 x, 4 x^{2}+4 y^{2} \leq 9\right\} .
$$

[CBSE 2008, '13]

#### Solution:

Clearly, we have to find the area enclosed between the curves $y^{2}=4 x$ and $4 x^{2}+4 y^{2}=9$.
The curve $y^{2}=4 x$ is a right-handed parabola with its vertex at $(0,0)$.
$4 x^{2}+4 y^{2}=9 \Rightarrow x^{2}+y^{2}=\left(\frac{3}{2}\right)^{2}$, which represents a circle with its centre at $O(0,0)$ and radius equal to ($3 / 2$) units.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-289.jpg?height=494&width=581&top_left_y=145&top_left_x=420)

The shaded region shows the required area.
Now,

$$
\begin{align*}
& & y^{2} & =4 x  \tag{i}\\
& & \text { and } & 4 x^{2}+4 y^{2} \tag{ii}
\end{align*}=9
$$

Putting the value of $y^{2}$ from (i) into (ii), we get

$$
\begin{aligned}
& 4 x^{2}+16 x-9=0 \\
\Rightarrow & 4 x^{2}+18 x-2 x-9=0 \\
\Rightarrow & 2 x(2 x+9)-(2 x+9)=0 \\
\Rightarrow & (2 x+9)(2 x-1)=0 \\
\Rightarrow & x=-\frac{9}{2} \text { or } x=\frac{1}{2} .
\end{aligned}
$$

Putting $x=-\frac{9}{2}$ in (i), we get

$$
y^{2}=-18 \Rightarrow y \text { is imaginary. }
$$

Putting $x=\frac{1}{2}$ in (i), we get $y^{2}=2 \Rightarrow y= \pm \sqrt{2}$.
So, the given curves intersect at the points $A\left(\frac{1}{2}, \sqrt{2}\right)$ and $B\left(\frac{1}{2},-\sqrt{2}\right)$.

Since the equation of each of the given curves contains only even powers of $y$, each curve is symmetrical about the $x$-axis.

$$
\begin{aligned}
\text { Required area } & =2(\text { area } O D C A O) \\
& =2(\text { area } O D A O+\text { area } D C A D) \\
& =2\left\{\int_{0}^{1 / 2}(y \text { of the parabola }) d x+\int_{1 / 2}^{3 / 2}(y \text { of the circle }) d x\right\}
\end{aligned}
$$

$$
\begin{aligned}
& =2\left\{\int_{0}^{1 / 2} 2 \sqrt{x} d x+\int_{1 / 2}^{3 / 2} \sqrt{\frac{9}{4}-x^{2}} d x\right\} \\
& =2\left\{\left[\frac{4}{3} x^{3 / 2}\right]_{0}^{1 / 2}+\left[\frac{x \sqrt{\frac{9}{4}-x^{2}}}{2}+\frac{9}{8} \sin ^{-1}\left(\frac{x}{3 / 2}\right)\right]_{1 / 2}\right\} \\
& =\frac{4}{3 \sqrt{2}}+\left(\frac{9}{4} \sin ^{-1} 1\right)-\left(\frac{\sqrt{2}}{2}+\frac{9}{4} \sin ^{-1} \frac{1}{3}\right) \\
& =\left(\frac{2 \sqrt{2}}{3}-\frac{\sqrt{2}}{2}\right)+\frac{9}{4}\left(\sin ^{-1} 1-\sin ^{-1} \frac{1}{3}\right) \\
& =\left\{\frac{\sqrt{2}}{6}+\frac{9}{4}\left(\frac{\pi}{2}-\sin ^{-1} \frac{1}{3}\right)\right\} \text { sq units } \\
& =\left\{\frac{\sqrt{2}}{6}+\frac{9}{4} \cos ^{-1}\left(\frac{1}{3}\right)\right\} \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\left\{\frac{\sqrt{2}}{6}+\frac{9}{4} \cos ^{-1} \frac{1}{3}\right\}$ sq units**.

---

### Example 21

Find the area of the region $\left\{(x, y): x^{2}+y^{2} \leq 1 \leq x+y\right\}$.

#### Solution:

Let $R=\left\{(x, y): x^{2}+y^{2} \leq 1 \leq x+y\right\}$

$$
\begin{aligned}
& =\left\{(x, y): x^{2}+y^{2} \leq 1\right\} \cap\{(x, y): x+y \geq 1\} \\
& =R_{1} \cap R_{2}
\end{aligned}
$$

Clearly, $R_{1}$ is the interior of the circle $x^{2}+y^{2}=1$ with its centre at $O(0,0)$ and radius $=1$ unit.
And, $R_{2}$ is the region lying above the line $x+y=1$.
Consider the equations

$$
\text { and } \quad \begin{align*}
x^{2}+y^{2} & =1  \tag{i}\\
x+y & =1 \tag{ii}
\end{align*}
$$

Putting $y=(1-x)$ from (ii) in (i), we get

$$
\begin{aligned}
x^{2}+(1-x)^{2}=1 & \Rightarrow 2 x^{2}-2 x=0 \\
& \Rightarrow 2 x(x-1)=0 \\
& \Rightarrow x=0 \text { or } x=1
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-290.jpg?height=390&width=425&top_left_y=1406&top_left_x=782)

Now, $(x=0 \Rightarrow y=1)$ and $(x=1 \Rightarrow y=0)$.
Thus, the points of intersection of (i) and (ii) are $A(0,1)$ and $B(1,0)$.
So, the required area is the shaded region.

$$
\begin{aligned}
\text { Required area } & =\text { area } B C A B \\
& =(\text { area } A O B C A)-(\text { area } O B A O) \\
& =\int_{0}^{1} \sqrt{1-x^{2}} d x-\int_{0}^{1}(1-x) d x \\
& =\left[\frac{1}{2} \sin ^{-1} x+\frac{x}{2} \sqrt{1-x^{2}}\right]_{0}^{1}-\left[x-\frac{x^{2}}{2}\right]_{0}^{1} \\
& =\left(\frac{1}{2} \sin ^{-1} 1\right)-\frac{1}{2}=\left(\frac{1}{2} \times \frac{\pi}{2}\right)-\frac{1}{2}=\left(\frac{\pi}{4}-\frac{1}{2}\right) \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\left(\frac{\pi}{4}-\frac{1}{2}\right)$ sq units**.

---

### Example 22

Find the area of the region $\left\{(x, y): x^{2}+y^{2} \leq 2 a x, y^{2} \geq a x, x \geq 0, y \geq 0\right\}$.

#### Solution:

Clearly, we have to find the area of the region lying in the first quadrant ($x \geq 0, y \geq 0$), included between the circle $x^{2}+y^{2}=2 a x$ and the parabola $y^{2}=a x$.
Thus, the equations of the given curves are

$$
\begin{align*}
x^{2}+y^{2} & =2 a x  \tag{i}\\
\text { and } \quad y^{2} & =a x \tag{ii}
\end{align*}
$$

Now, clearly $x^{2}+y^{2}=2 a x$ is a circle with its centre $B(a, 0)$ and radius $=a$ units.
And, $y^{2}=a x$ is a parabola with $O(0,0)$ as its vertex and the $x$-axis as its axis.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-291.jpg?height=437&width=469&top_left_y=833&top_left_x=738)

We can draw the figure, as shown.
Their points of intersection may be obtained by solving (i) and (ii) and keeping in view that $x \geq 0$ and $y \geq 0$.
Using (ii) in (i), we get

$$
\begin{aligned}
x^{2}-a x=0 & \Rightarrow x(x-a)=0 \\
& \Rightarrow x=0 \text { or } x=a .
\end{aligned}
$$

Now, $(x=0 \Rightarrow y=0)$ and $(x=a \Rightarrow y=a)$.
Thus, the two curves intersect at $O(0,0)$ and $A(a, a)$.

$$
\begin{aligned}
\therefore \text { required area } & =\int_{0}^{a} \sqrt{2 a x-x^{2}} d x-\int_{0}^{a} \sqrt{a x} d x \\
& =\int_{0}^{a} \sqrt{a^{2}-(x-a)^{2}} d x-\sqrt{a} \cdot \int_{0}^{a} \sqrt{x} d x
\end{aligned}
$$

$$
\begin{aligned}
& =\left[\frac{(x-a) \sqrt{a^{2}-(x-a)^{2}}}{2}+\frac{a^{2}}{2} \sin ^{-1}\left(\frac{x-a}{a}\right)\right]_{0}^{a} \\
& =\left\{\frac{a^{2}}{2} \sin ^{-1}(0)-\frac{a^{2}}{2} \sin ^{-1}(-1)-\frac{2}{3} x^{3 / 2}\right]_{0}^{a} \\
& =\left(\frac{\pi a^{2}}{4}-\frac{2}{3} a^{2}\right) \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\left(\frac{\pi a^{2}}{4}-\frac{2}{3} a^{2}\right)$ sq units**.

---

### Example 23

Find the area of the region $\left\{(x, y): x^{2} \leq y \leq|x|\right\}$.
[CBSE 2009, '12C, '13]

#### Solution:

Consider the equations

$$
\begin{array}{rlrl}
x^{2} & =y \\
\text { and } & y & =|x| \tag{ii}
\end{array}
$$

Clearly, $x^{2}=y$ represents an upward parabola with its vertex at $O(0,0)$. All the points inside this parabola represent $x^{2} \leq y$.
Also, $y=|x|=\left\{\begin{array}{r}x, \text { when } x \geq 0 \\ -x, \text { when } x<0 .\end{array}\right.$
The lines $O A$ and $O B$, each equally inclined to the axes, represent $y=|x|$.
All the points below the lines $O A$ and $O B$, and above the $x$-axis represent $y \leq|x|$.
Thus, the shaded portion is the
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-292.jpg?height=318&width=353&top_left_y=1013&top_left_x=854)
required region.
In each of the given equations, the equation remains unchanged when $x$ is replaced by $-x$.
So, each of the given curves is symmetrical about the $y$-axis.
$\therefore$ **Required Area** $= 2(\text{area } O E A O)$.
In this region, we have

$$
\text { and } \quad \begin{align*}
x^{2} & =y  \tag{iii}\\
y & =x \tag{iv}
\end{align*}
$$

Using (iv) in (iii), we get $x^{2}=x \Rightarrow x(x-1)=0 \Rightarrow x=0$ or $x=1$.
Now, $(x=0 \Rightarrow y=0)$ and $(x=1 \Rightarrow y=1)$.
Thus, the line $y=x$ and the curve $x^{2}=y$ intersect at $O(0,0)$ and $A(1,1)$. Draw $A D \perp O X$ and $B C \perp O X^{\prime}$.
$\therefore$ **Required Area**

$$
\begin{aligned}
= & 2(\text { area } O E A O)=2[(\text { area } O D A O)-(\text { area } O D A E O)] \\
= & 2[(\text { area between } y=x \text { and the } x \text {-axis from } x=0 \text { to } x=1) \\
& \left.-\left(\text { area between } x^{2}=y \text { and the } x \text {-axis from } x=0 \text { to } x=1\right)\right] \\
= & 2\left(\int_{0}^{1} y d x \text { for the line } O A-\int_{0}^{1} y d x \text { for the curve } O E A\right) \\
= & 2\left[\int_{0}^{1} x d x-\int_{0}^{1} x^{2} d x\right]=2\left\{\left[\frac{x^{2}}{2}\right]_{0}^{1}-\left[\frac{x^{3}}{3}\right]_{0}^{1}\right\}=2\left[\frac{1}{2}-\frac{1}{3}\right] \\
= & \left(2 \times \frac{1}{6}\right)=\frac{1}{3} \text { sq unit. }
\end{aligned}
$$

Hence, the required area is **$\frac{1}{3}$ sq unit**.

---

### Example 24

Find the area bounded by the line $y=x$ and the curve $y=x^{3}$.

#### Solution:

The given equations are

$$
\text { and } \quad \begin{array}{ll}
y & =x \\
y & =x^{3} \tag{ii}
\end{array}
$$

Using (i) in (ii), we get

$$
\begin{aligned}
x-x^{3}=0 & \Rightarrow x\left(1-x^{2}\right)=0 \Rightarrow x(1-x)(1+x)=0 \\
& \Rightarrow x=0 \text { or } x=1 \text { or } x=-1 .
\end{aligned}
$$

Also, $(x=0 \Rightarrow y=0)$, $(x=1 \Rightarrow y=1)$ and $(x=-1 \Rightarrow y=-1)$.
So, the given curve and the line intersect at the points $O(0,0)$, $A(1,1)$ and $B(-1,-1)$.
Now, $y=x$ is a line passing through the origin and making an angle of $45^{\circ}$ with the $x$-axis. Thus, the line $y=x$ can be drawn.
For the curve $y=x^{3}$ some values for $x$ and the corresponding values of $y$ are given below:

| $x$ | -1 | $-\frac{1}{2}$ | 0 | $\frac{1}{2}$ | 1 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $y$ | -1 | $-\frac{1}{8}$ | 0 | $\frac{1}{8}$ | 1 |

Plotting the points $(-1,-1)$, $\left(-\frac{1}{2},-\frac{1}{8}\right),(0,0),\left(\frac{1}{2}, \frac{1}{8}\right)$, and
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-293.jpg?height=317&width=477&top_left_y=1434&top_left_x=730)
$(1,1)$, and joining them, we get a rough sketch of $y=x^{3}$, as shown in the given figure.

**Required Area**

$$
\begin{aligned}
& =(\operatorname{area} A C O A)+(\operatorname{area} O D B O) \\
& =(\operatorname{area} O A L O)-(\operatorname{area} O C A L O)+(\operatorname{area} O B M O)-(\operatorname{area} O D B M O) \\
& =\int_{0}^{1}\{y \text { for }(\mathrm{i})\} d x-\int_{0}^{1}\{y \text { for }(\mathrm{ii})\} d x+\int_{-1}^{0}\{(-y) \text { for }(\mathrm{i})\} d x \\
& =\int_{0}^{1} x d x-\int_{0}^{1} x^{3} d x+\int_{-1}^{0}\{(-y) \text { for }(\mathrm{ii})\} d x \\
& =\left[\frac{x^{2}}{2}\right]_{0}^{1}-\left[\frac{x^{4}}{4}\right]_{0}^{1}+\left[\frac{-x^{2}}{2}\right]_{-1}^{0}+\left[\frac{x^{4}}{4}\right]_{-1}^{0}-x^{3} d x \\
& =\left(\frac{1}{2}-\frac{1}{4}+\frac{1}{2}-\frac{1}{4}\right)=\frac{1}{2} \text { sq unit. }
\end{aligned}
$$

Hence, the required area is **0.5 sq unit**.

---

### Example 25

Find the area bounded by the curve $y=\sin x$ between $x=0$ and $x=2 \pi$.

#### Solution:

The given curve is $y=\sin x$.
Some values of $x$ and the corresponding values of $y$ are given below:

| $x$ | 0 | $\frac{\pi}{6}$ | $\frac{\pi}{2}$ | $\pi$ | $\frac{3 \pi}{2}$ | $2 \pi$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $y$ | 0 | $\frac{1}{2}$ | 1 | 0 | -1 | 0 |

Taking a fixed unit (distance) for $\pi$ along the $x$-axis, we can plot the points $(0,0),\left(\frac{\pi}{6}, \frac{1}{2}\right),\left(\frac{\pi}{2}, 1\right),(\pi, 0),\left(\frac{3 \pi}{2},-1\right)$ and $(2 \pi, 0)$.

Join these points freehand to obtain a rough sketch of the given curve.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-294.jpg?height=313&width=458&top_left_y=1544&top_left_x=503)

$$
\begin{aligned}
\text { Required area } & =(\text { area } O A B O)+(\text { area } B C D B) \\
& =\int_{0}^{\pi} y d x+\int_{\pi}^{2 \pi}(-y) d x[\because \text { area } B C D B \text { is below the } x \text {-axis }] \\
& =\int_{0}^{\pi} \sin x d x-\int_{\pi}^{2 \pi} \sin x d x \\
& =[-\cos x]_{0}^{\pi}-[-\cos x]_{\pi}^{2 \pi}=(2+2)=4 \text { sq units. }
\end{aligned}
$$

Hence, the required area is **4 sq units**.

---

### Example 26

Find the area of the region bounded by the curve $y=x^{2}+2$, and the lines $y=x, x=0$ and $x=3$.

#### Solution:

$y=x^{2}+2 \Rightarrow x^{2}=(y-2)$.
Clearly, $x^{2}=(y-2)$ represents an upward parabola with its vertex at $A(0,2)$.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-295.jpg?height=367&width=518&top_left_y=785&top_left_x=404)

Also, $y=x$ represents the straight line, making an angle of $45^{\circ}$ with the positive direction of the $x$-axis.
And, $x=0$ is the $y$-axis, while $x=3$ represents a line parallel to the $y$-axis at a distance of 3 units from it.

Thus, the shaded region in the given figure is the required area.
$\therefore$ **Required Area** $= (\text{area } O D C A O) - (\text{area } O D B O)$

$$
\begin{aligned}
& =\int_{0}^{3}\left(x^{2}+2\right) d x-\int_{0}^{3} x d x \\
& =\left[\frac{x^{3}}{3}+2 x\right]_{0}^{3}-\left[\frac{x^{2}}{2}\right]_{0}^{3}=\left(15-\frac{9}{2}\right)=\frac{21}{2} \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\frac{21}{2}$ sq units**.

---

### Example 27

Find the area of the region

$$
\left\{(x, y): 0 \leq y \leq\left(x^{2}+1\right), 0 \leq y \leq(x+1), 0 \leq x \leq 2\right\} .
$$

[CBSE 2009]

#### Solution:

Let $R=\left\{(x, y): 0 \leq y \leq\left(x^{2}+1\right), 0 \leq y \leq(x+1), 0 \leq x \leq 2\right\}$

$$
\begin{array}{lrl}
= & \left\{(x, y): 0 \leq y \leq\left(x^{2}+1\right)\right\} \cap\{(x, y): 0 \leq y \leq(x+1)\} & \\
& & \cap\{(x, y): 0 \leq x \leq 2\}
\end{array}
$$

Clearly, $R_{1}$ is the region consisting of the right-hand side of the $y$-axis, lying below the parabola $y=x^{2}+1$.
Also, $R_{2}$ is the region consisting of the right-hand side of the $y$-axis, lying below the line $y=(x+1)$.
And, $R_{3}$ is the region above the $x$-axis, lying between the ordinates $x=0$ and $x=2$.
Thus, $R_{1} \cap R_{2} \cap R_{3}$ is the shaded region.
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-296.jpg?height=392&width=532&top_left_y=656&top_left_x=455)

We have, $y=x^{2}+1$ and $y=x+1$

$$
\Rightarrow x^{2}+1=x+1 \Rightarrow x(x-1)=0 \Rightarrow x=0 \text { or } x=1 .
$$

Now, $(x=0 \Rightarrow y=1)$ and $(x=1 \Rightarrow y=2)$.
Thus, the parabola $y=\left(x^{2}+1\right)$ and the line $y=x+1$ intersect at the points $A(0,1)$ and $C(1,2)$.
$\therefore$ **Required Area** $=$ area of the shaded region

$$
\begin{aligned}
& =(\text { area } O D C B A)+(\text { area } C D F E C) \\
& =\int_{0}^{1}(y \text { of the parabola }) d x+\int_{1}^{2}(y \text { of the line }) d x \\
& =\int_{0}^{1}\left(x^{2}+1\right) d x+\int_{1}^{2}(x+1) d x \\
& =\left[\frac{x^{3}}{3}+x\right]_{0}^{1}+\left[\frac{x^{2}}{2}+x\right]_{1}^{2} \\
& =\left(\frac{1}{3}+1\right)+\left(4-\frac{3}{2}\right)=\frac{23}{6} \text { sq units. }
\end{aligned}
$$

Hence, the required area is **$\frac{23}{6}$ sq units**.

---

### Example 28

Find the area of the region bounded by the curve $y^{2}=2 y-x$ and the $y$-axis.

#### Solution:

$$
\begin{aligned}
y^{2}=2 y-x & \Rightarrow y^{2}-2 y=-x \\
& \Rightarrow y^{2}-2 y+1=-x+1 \\
& \Rightarrow(y-1)^{2}=-(x-1) \\
& \Rightarrow Y^{2}=-X
\end{aligned}
$$

where $y-1=Y$ and $(x-1)=X$.
This is a left-handed parabola with vertex at ($X=0, Y=0$).
![](https://cdn.mathpix.com/cropped/2025_09_25_93c93c897264abc3217bg-297.jpg?height=325&width=353&top_left_y=222&top_left_x=860)
$X=0, Y=0 \Rightarrow -x+1=0$ and $y-1=0$

$$
\Rightarrow x=1 \text { and } y=1 .
$$

Thus, the vertex of the given parabola is $A(1,1)$.
Also, $x=0 \Rightarrow y^{2}-2 y=0 \Rightarrow y(y-2)=0 \Rightarrow y=0$ or $y=2$.
Thus, the curve meets the $y$-axis at $O(0,0)$ and $B(0,2)$.
A rough sketch of the curve can be drawn, as shown in the figure.
$\therefore$ **Required Area** $=\int_{0}^{2} x d y=\int_{0}^{2}\left(2 y-y^{2}\right) d y$

$$
=\left[y^{2}-\frac{y^{3}}{3}\right]_{0}^{2}=\left(4-\frac{8}{3}\right)=\frac{4}{3} \text { sq units. }
$$

Hence, the required area is **$\frac{4}{3}$ sq units**.

---