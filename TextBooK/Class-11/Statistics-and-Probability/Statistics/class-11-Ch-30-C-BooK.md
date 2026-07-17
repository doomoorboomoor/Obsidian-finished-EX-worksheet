## Miscellaneous Word Problems

### Example 1
The mean and variance of seven observations are 8 and 16 respectively. If five of these are $2, 4, 10, 12, 14$, find the remaining two observations.

#### Solution:
Let the remaining two observations be $x$ and $y$. Then,

**Mean** $= 8$
$$
\begin{align*}
& \Rightarrow \frac{2+4+10+12+14+x+y}{7}=8 \\
& \Rightarrow 42+x+y=56 \\
& \Rightarrow x+y=14 \tag{i}
\end{align*}
$$

Also, **variance** $= 16$
$$
\Rightarrow \frac{1}{7}\left(2^{2}+4^{2}+10^{2}+12^{2}+14^{2}+x^{2}+y^{2}\right)-8^{2}=16 \quad \left[\because \sigma^{2}=\frac{\sum x_{i}^{2}}{n}-(\bar{x})^{2}\right]
$$
$$
\Rightarrow \quad \frac{1}{7}\left(460+x^{2}+y^{2}\right)=80
$$
$$
\Rightarrow 460+x^{2}+y^{2}=560
$$
$$
\Rightarrow x^{2}+y^{2}=100 \tag{ii}
$$

Now, using the identity $(x+y)^{2}+(x-y)^{2}=2(x^{2}+y^{2})$:
$$
\begin{align*}
& \Rightarrow (x-y)^{2}=2(x^{2}+y^{2})-(x+y)^{2} \\
& \Rightarrow (x-y)^{2}=(2 \times 100)-(14)^{2}=(200-196)=4 \\
& \Rightarrow x-y= \pm 2
\end{align*}
$$

Now, we solve the system of equations:
- If $x+y=14$ and $x-y=2 \Rightarrow x=8, y=6$.
- If $x+y=14$ and $x-y=-2 \Rightarrow x=6, y=8$.

Hence, the remaining two observations are **6** and **8**.

---

### Example 2
The mean and variance of six observations are 8 and 16 respectively. If each observation is multiplied by 3, find the new mean and new variance of the resulting observations.

#### Solution:
Let the given observations be $x_{1}, x_{2}, x_{3}, x_{4}, x_{5}, x_{6}$.

Given **mean** $= 8$:
$$
\Rightarrow \frac{1}{6}(x_{1}+x_{2}+x_{3}+x_{4}+x_{5}+x_{6})=8
$$
$$
\Rightarrow x_{1}+x_{2}+x_{3}+x_{4}+x_{5}+x_{6}=48 \tag{i}
$$

Given **variance** $= 16$:
$$
\Rightarrow \frac{1}{6}(x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}+x_{5}^{2}+x_{6}^{2})-8^{2}=16 \quad \left[\because \sigma^{2}=\frac{\sum x_{i}^{2}}{n}-(\bar{x})^{2}\right]
$$
$$
\Rightarrow x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}+x_{5}^{2}+x_{6}^{2}=480 \tag{ii}
$$

When each observation is multiplied by 3, the new observations are $3x_{1}, 3x_{2}, 3x_{3}, 3x_{4}, 3x_{5}$ and $3x_{6}$.

**New Mean**:
$$
\begin{align*}
\text{new mean} &= \frac{1}{6}(3x_{1}+3x_{2}+3x_{3}+3x_{4}+3x_{5}+3x_{6}) \\
&= \frac{3}{6}(x_{1}+x_{2}+x_{3}+x_{4}+x_{5}+x_{6}) \\
&= \frac{1}{2} \times 48 = 24 \quad [\text{using (i)}]
\end{align*}
$$

**New Variance**:
$$
\begin{align*}
\text{new variance} &= \frac{(3x_{1})^{2}+(3x_{2})^{2}+(3x_{3})^{2}+(3x_{4})^{2}+(3x_{5})^{2}+(3x_{6})^{2}}{6} - (\text{new mean})^{2} \\
&= \frac{9(x_{1}^{2}+x_{2}^{2}+x_{3}^{2}+x_{4}^{2}+x_{5}^{2}+x_{6}^{2})}{6} - (24)^2 \\
&= \frac{9}{6}(480) - 576 \quad [\text{using (ii)}] \\
&= (720-576) = 144
\end{align*}
$$

The new mean is **24** and the new variance is **144**.

---

### Example 3
The mean and standard deviation of 20 observations are found to be 10 and 2 respectively. On rechecking it was found that an observation 8 was incorrect. Calculate the correct mean and standard deviation when:
(i) the wrong item is omitted,
(ii) the wrong item is replaced by 12.

#### Solution:
Given incorrect **Mean** $= 10$ and incorrect **Standard Deviation** $(\sigma) = 2$.
This implies incorrect **Variance** $(\sigma^2) = 4$.

From the mean:
$$
\frac{\sum_{i=1}^{20} x_{i}}{20}=10 \Rightarrow \text{Incorrect } \sum_{i=1}^{20} x_{i}=200
$$

From the variance:
$$
\frac{\sum_{i=1}^{20} x_{i}^{2}}{20}-(10)^{2}=4 \Rightarrow \text{Incorrect } \sum_{i=1}^{20} x_{i}^{2}=2080
$$

**Case (i): When the wrong item (8) is omitted**

We are left with $n=19$ observations.

**Correct Sum**:
$$
\text{Correct } \sum_{i=1}^{19} x_{i} = (\text{Incorrect } \sum x_i) - 8 = 200 - 8 = 192
$$

**Correct Mean**:
$$
\text{Correct Mean} = \frac{192}{19} \approx 10.105
$$

**Correct Sum of Squares**:
$$
\text{Correct } \sum_{i=1}^{19} x_{i}^{2} = (\text{Incorrect } \sum x_i^2) - 8^2 = 2080 - 64 = 2016
$$

**Correct Variance**:
$$
\begin{align*}
\text{Correct Variance} &= \frac{1}{19}\left(\text{Correct } \sum x_{i}^{2}\right)-(\text{Correct Mean})^{2} \\
&= \frac{2016}{19} - \left(\frac{192}{19}\right)^{2} = \frac{2016 \times 19 - 36864}{361} \\
&= \frac{38304-36864}{361} = \frac{1440}{361}
\end{align*}
$$

**Correct Standard Deviation**:
$$
\text{Correct SD} = \sqrt{\frac{1440}{361}} = \frac{12\sqrt{10}}{19} = \frac{12 \times 3.162}{19} \approx 1.997
$$

Thus, the correct mean is $\approx 10.105$ and the correct SD is $\approx 1.997$.

**Case (ii): When incorrect observation 8 is replaced by 12**

The number of observations remains $n=20$.

**Correct Sum**:
$$
\text{Correct } \sum_{i=1}^{20} x_{i} = (\text{Incorrect } \sum x_i) - 8 + 12 = 200 + 4 = 204
$$

**Correct Mean**:
$$
\text{Correct Mean} = \frac{204}{20} = 10.2
$$

**Correct Sum of Squares**:
$$
\text{Correct } \sum_{i=1}^{20} x_{i}^{2} = (\text{Incorrect } \sum x_i^2) - 8^2 + 12^2 = 2080 - 64 + 144 = 2160
$$

**Correct Variance**:
$$
\begin{align*}
\text{Correct Variance} &= \frac{\text{Correct } \sum x_{i}^{2}}{20}-(\text{Correct Mean})^{2} \\
&= \frac{2160}{20} - (10.2)^{2} \\
&= 108 - 104.04 = 3.96
\end{align*}
$$

**Correct Standard Deviation**:
$$
\text{Correct SD} = \sqrt{3.96} \approx 1.989
$$

Thus, in this case, the correct mean is **10.2** and the correct SD is $\approx 1.989$.

---

### Example 4
The mean and standard deviation of 100 observations were calculated as 40 and 5.1 respectively by a student who took by mistake 50 instead of 40 for one observation. What are the correct mean and standard deviation?

#### Solution:
Given incorrect **Mean** $= 40$ and incorrect **Standard Deviation** $(\sigma) = 5.1$.
This implies incorrect **Variance** $(\sigma^2) = (5.1)^2 = 26.01$.

From the mean:
$$
\frac{\sum_{i=1}^{100} x_{i}}{100}=40 \Rightarrow \text{Incorrect } \sum_{i=1}^{100} x_{i}=4000
$$

From the variance:
$$
\frac{\sum_{i=1}^{100} x_{i}^{2}}{100}-(40)^{2}=26.01 \Rightarrow \text{Incorrect } \sum_{i=1}^{100} x_{i}^{2}=162601
$$

Now, we correct the values by removing the incorrect observation (50) and adding the correct one (40).

**Correct Sum**:
$$
\text{Correct } \sum_{i=1}^{100} x_{i} = 4000 - 50 + 40 = 3990
$$

**Correct Mean**:
$$
\text{Correct Mean} = \frac{3990}{100} = 39.9
$$

**Correct Sum of Squares**:
$$
\text{Correct } \sum_{i=1}^{100} x_{i}^{2} = 162601 - (50)^{2} + (40)^{2} = 162601 - 2500 + 1600 = 161701
$$

**Correct Variance**:
$$
\begin{align*}
\text{Correct Variance} &= \frac{\text{Correct } \sum x_{i}^{2}}{100}-(\text{Correct Mean})^{2} \\
&= \frac{161701}{100} - (39.9)^{2} \\
&= 1617.01 - 1592.01 = 25
\end{align*}
$$

**Correct Standard Deviation**:
$$
\text{Correct SD} = \sqrt{25} = 5
$$

Hence, the correct mean is **39.9** and the correct standard deviation is **5**.

---

### Example 5
If each of the observations $x_{1}, x_{2}, x_{3}, \ldots, x_{n}$ is increased by an amount $a$, where $a$ is a negative or positive number, then show that the variance remains unchanged.

#### Solution:
Let $\bar{x}$ be the mean of $x_{1}, x_{2}, x_{3}, \ldots, x_{n}$. Then,
$$
\bar{x}=\frac{1}{n}\sum_{i=1}^{n} x_{i}
$$

Let the new observations be $y_{i} = x_{i}+a$ for each $i=1, 2, \ldots, n$.
Let $\bar{y}$ be the mean of $y_{1}, y_{2}, y_{3}, \ldots, y_{n}$.
$$
\begin{align*}
\bar{y} &= \frac{1}{n} \sum_{i=1}^{n} y_{i} = \frac{1}{n} \sum_{i=1}^{n} (x_{i}+a) \\
&= \frac{1}{n} \left( \sum_{i=1}^{n} x_{i} + \sum_{i=1}^{n} a \right) \\
&= \frac{1}{n} \sum_{i=1}^{n} x_{i} + \frac{1}{n}(na) \\
&= \bar{x} + a
\end{align*}
$$
So, $\bar{y} = \bar{x}+a$.

Now, the variance of the new observations is given by:
$$
\begin{align*}
\text{Variance}(y) &= \sigma_{y}^{2} = \frac{1}{n} \sum_{i=1}^{n}(y_{i}-\bar{y})^{2} \\
&= \frac{1}{n} \sum_{i=1}^{n} ((x_{i}+a)-(\bar{x}+a))^{2} \\
&= \frac{1}{n} \sum_{i=1}^{n} (x_{i}+a-\bar{x}-a)^{2} \\
&= \frac{1}{n} \sum_{i=1}^{n} (x_{i}-\bar{x})^{2} \\
&= \text{Variance}(x)
\end{align*}
$$
Hence, the variance of the new observations is the same as the variance of the original observations.

---

### Example 6
If the mean and variance of the observations $x_{1}, x_{2}, x_{3}, \ldots, x_{n}$ are $\bar{x}$ and $\sigma^{2}$ respectively and $a$ be a nonzero real number, then show that the mean and variance of $ax_{1}, ax_{2}, ax_{3}, \ldots, ax_{n}$ are $a\bar{x}$ and $a^{2}\sigma^{2}$ respectively.

#### Solution:
Let $\bar{x}$ be the mean of $x_{1}, x_{2}, \ldots, x_{n}$.
$$
\bar{x}=\frac{1}{n} \sum_{i=1}^{n} x_{i}
$$
Let the new observations be $y_{i}=ax_{i}$ for each $i=1, 2, \ldots, n$. The new mean $\bar{y}$ is:
$$
\bar{y} = \frac{1}{n} \sum_{i=1}^{n} y_{i} = \frac{1}{n} \sum_{i=1}^{n} (ax_{i}) = a \left( \frac{1}{n} \sum_{i=1}^{n} x_{i} \right) = a\bar{x}
$$
Thus, the new mean is $\bar{y} = a\bar{x}$.

Now, the variance of the new observations is given by:
$$
\begin{align*}
\text{Variance}(y) &= \sigma_{y}^{2} = \frac{1}{n} \sum_{i=1}^{n}(y_{i}-\bar{y})^{2} \\
&= \frac{1}{n} \sum_{i=1}^{n}(ax_{i}-a\bar{x})^{2} \\
&= \frac{1}{n} \sum_{i=1}^{n} a^{2}(x_{i}-\bar{x})^{2} \\
&= a^{2} \left( \frac{1}{n} \sum_{i=1}^{n} (x_{i}-\bar{x})^{2} \right) \\
&= a^{2} \cdot \{\text{Variance}(x)\} = a^{2}\sigma^{2}
\end{align*}
$$
Thus, the new variance is $a^{2}\sigma^{2}$.

**Remark:** The new standard deviation is $\sigma_{y} = \sqrt{a^{2}\sigma^{2}} = |a|\sigma$.

---

