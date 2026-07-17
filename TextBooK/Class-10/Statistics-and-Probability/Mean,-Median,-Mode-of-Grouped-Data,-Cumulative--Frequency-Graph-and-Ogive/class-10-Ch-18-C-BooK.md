# Mode of a Grouped Data

**Mode** is that value of a variate which occurs most often, i.e., the value of the observation having the maximum frequency.

More precisely, mode is that value of the variable at which the concentration of the data is maximum.

**Modal class** In a frequency distribution, the class having maximum frequency is called the modal class.

---

## Formula for Calculating Mode

We have the formula:
$$
\text{mode, } M_{o} = x_{k} + h \cdot \left\{\frac{(f_{k} - f_{k-1})}{(2 f_{k} - f_{k-1} - f_{k+1})}\right\}
$$
where:
- **$x_k$**: lower limit of the modal class interval
- **$f_k$**: frequency of the modal class
- **$f_{k-1}$**: frequency of the class preceding the modal class
- **$f_{k+1}$**: frequency of the class succeeding the modal class
- **$h$**: width of the class interval

---

## Solved Examples

### Example 1
Find the mode of the following data: [CBSE 2013]

| Class     | $0-20$ | $20-40$ | $40-60$ | $60-80$ | $80-100$ | $100-120$ | $120-140$ |
| :-------: | :----: | :-----: | :-----: | :-----: | :------: | :-------: | :-------: |
| Frequency | 6      | 8       | 10      | 12      | 6        | 5         | 3         |

#### Solution:

Clearly, the **modal class** is $60-80$, as it has the maximum frequency.

Here, $x_k = 60$, $h = 20$, $f_k = 12$, $f_{k-1} = 10$, $f_{k+1} = 6$.

Using the formula for mode:
$$
M_{o} = x_{k} + \left\{h \times \frac{(f_{k} - f_{k-1})}{(2 f_{k} - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
& = 60 + \left\{20 \times \frac{(12 - 10)}{(2 \times 12 - 10 - 6)}\right\} \\
& = 60 + \left\{20 \times \frac{2}{(24 - 16)}\right\} \\
& = 60 + \left\{20 \times \frac{2}{8}\right\} \\
& = 60 + 5 = 65.
\end{aligned}
$$
Hence, **mode** = $65$.

---

### Example 2
The distribution of sale of shirts sold in a month in a departmental store is as under. Calculate the modal size of shirts sold. [CBSE 2014]

| Size (in cm)        | $80-85$ | $85-90$ | $90-95$ | $95-100$ | $100-105$ | $105-110$ | $110-115$ |
| :------------------: | :-----: | :-----: | :-----: | :------: | :-------: | :-------: | :-------: |
| Number of shirts sold | 33      | 27      | 85      | 155      | 110       | 45        | 15        |

#### Solution:

Clearly, the **modal class** is $95-100$ as it has the maximum frequency.

Here, $x_k = 95$, $h = 5$, $f_k = 155$, $f_{k-1} = 85$, $f_{k+1} = 110$.

Using the formula for mode:
$$
M_{o} = x_{k} + \left\{h \times \frac{(f_{k} - f_{k-1})}{(2 f_{k} - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
& = 95 + \left\{5 \times \frac{(155 - 85)}{(2 \times 155 - 85 - 110)}\right\} \\
& = 95 + \left\{5 \times \frac{70}{(310 - 195)}\right\} \\
& = 95 + \left\{5 \times \frac{70}{115}\right\} \\
& = 95 + \frac{70}{23} \\
& = 95 + 3.04 = 98.04
\end{aligned}
$$
Therefore, the **modal size** = $98.04 \text{ cm}$.

---

### Example 3
Given below is the frequency distribution of the heights of players in a school. Find the modal height and interpret it.

| Height (in cm)      | $160-162$ | $163-165$ | $166-168$ | $169-171$ | $172-174$ |
| :------------------: | :-------: | :-------: | :-------: | :-------: | :-------: |
| Number of students | 15        | 118       | 142       | 127       | 18        |

#### Solution:

The given data is an inclusive series. So, we convert it into an exclusive form by subtracting $0.5$ from the lower limit and adding $0.5$ to the upper limit of each class.

| Class     | $159.5-162.5$ | $162.5-165.5$ | $165.5-168.5$ | $168.5-171.5$ | $171.5-174.5$ |
| :--------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| Frequency | 15            | 118           | 142           | 127           | 18            |

Clearly, the class $165.5-168.5$ has the maximum frequency, so it is the **modal class**.

Here, $x_k = 165.5$, $f_k = 142$, $f_{k-1} = 118$, $f_{k+1} = 127$, and $h = 3$.

Using the formula for mode:
$$
M_{o} = x_{k} + \left\{h \times \frac{(f_{k} - f_{k-1})}{(2 f_{k} - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
& = 165.5 + \left\{3 \times \frac{(142 - 118)}{(2 \times 142 - 118 - 127)}\right\} \\
& = 165.5 + \left\{\frac{3 \times 24}{39}\right\} \\
& = 165.5 + \frac{24}{13} \\
& = 165.5 + 1.85 = 167.35
\end{aligned}
$$
Thus, the **modal height** is $167.35 \text{ cm}$.

**Interpretation**: This means that the height of the maximum number of players in the school is approximately $167.35 \text{ cm}$.

---

### Example 4
The following table shows the ages of the patients admitted in a hospital during a month. Find the mode and the mean of the data given above. Compare and interpret the two measures of central tendency.

| Age (in years)      | $6-15$ | $16-25$ | $26-35$ | $36-45$ | $46-55$ | $56-65$ |
| :------------------: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| Number of patients | 6      | 11      | 21      | 23      | 14      | 5       |

#### Solution:

The given data is an inclusive series. Making it an exclusive series, we get:

| Class       | Frequency $f_i$ | Class mark $x_i$ | $u_i = \frac{(x_i - A)}{h} = \frac{(x_i - 40.5)}{10}$ | $f_i u_i$       |
| :---------- | :-------------- | :--------------- | :---------------------------------------------------- | :-------------- |
| $5.5-15.5$  | 6               | 10.5             | -3                                                    | -18             |
| $15.5-25.5$ | 11              | 20.5             | -2                                                    | -22             |
| $25.5-35.5$ | 21              | 30.5             | -1                                                    | -21             |
| $35.5-45.5$ | 23              | $40.5 = A$       | 0                                                     | 0               |
| $45.5-55.5$ | 14              | 50.5             | 1                                                     | 14              |
| $55.5-65.5$ | 5               | 60.5             | 2                                                     | 10              |
|             | $\Sigma f_i=80$ |                  |                                                       | $\Sigma f_i u_i=-37$ |

**Calculation of Mean:**
Here, Assumed Mean $A = 40.5$, $h = 10$, $\Sigma f_i = 80$, $\Sigma f_i u_i = -37$.
$$
\text{Mean, } \bar{x} = A + \left\{h \times \frac{\Sigma f_i u_i}{\Sigma f_i}\right\}
$$
$$
\begin{aligned}
& = 40.5 + \left\{10 \times \frac{(-37)}{80}\right\} = 40.5 - \frac{37}{8} \\
& = 40.5 - 4.63 = 35.87
\end{aligned}
$$

**Calculation of Mode:**
The **modal class** is $35.5-45.5$, as it has the maximum frequency.
Here, $x_k = 35.5$, $f_k = 23$, $f_{k-1} = 21$, $f_{k+1} = 14$, and $h = 10$.
$$
\text{Mode, } M_o = x_k + \left\{h \times \frac{(f_k - f_{k-1})}{(2 f_k - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
& = 35.5 + \left\{10 \times \frac{(23 - 21)}{(2 \times 23 - 21 - 14)}\right\} = 35.5 + \left(\frac{10 \times 2}{11}\right) \\
& = 35.5 + 1.82 = 37.32
\end{aligned}
$$
Clearly, **mode** > **mean** ($37.32 > 35.87$).

**Interpretation**: The **modal age** is $37.32$ years. This means that the maximum number of patients admitted in the hospital during the given month are of the age $37.32$ years (approx.). The **mean age** is $35.87$ years. This means that on average, the age of a patient admitted to the hospital is $35.87$ years.

---

### Example 5
The mode of the following series is 36. Find the missing frequency in it.

| Class interval | $0-10$ | $10-20$ | $20-30$  | $30-40$ | $40-50$ | $50-60$ | $60-70$ |
| :------------: | :----: | :-----: | :------: | :-----: | :-----: | :-----: | :-----: |
| Frequency      | 8      | 10      | $\ldots$ | 16      | 12      | 6       | 7       |

#### Solution:

Since the mode of the given series is $36$, which lies in the class $30-40$, the **modal class** is $30-40$.
Let the missing frequency be $x$.
Then, from the data, we have:
$x_k = 30$, $f_k = 16$, $f_{k-1} = x$, $f_{k+1} = 12$, and $h = 10$.
We are given that the mode, $M_o = 36$.

Using the formula:
$$
M_o = x_k + \left\{h \times \frac{(f_k - f_{k-1})}{(2 f_k - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
36 &= 30 + \left\{10 \times \frac{(16 - x)}{(2 \times 16 - x - 12)}\right\} \\
6 &= \frac{10 \times (16 - x)}{(32 - x - 12)} \\
6 &= \frac{10(16 - x)}{(20 - x)} \\
6(20 - x) &= 10(16 - x) \\
120 - 6x &= 160 - 10x \\
10x - 6x &= 160 - 120 \\
4x &= 40 \\
x &= 10
\end{aligned}
$$
Hence, the **missing frequency** is $10$.

---

### Example 6
Compare the modal ages of two groups of students appearing for an entrance examination.

| Age (in years) | $16-18$ | $18-20$ | $20-22$ | $22-24$ | $24-26$ |
| :-------------: | :-----: | :-----: | :-----: | :-----: | :-----: |
| Group A        | 50      | 78      | 46      | 28      | 23      |
| Group B        | 54      | 89      | 40      | 25      | 17      |

#### Solution:

**Case I: Computation of Modal Age of Group A**
In Group A, the class $18-20$ has the maximum frequency ($78$). So, $18-20$ is the **modal class**.
Here, $x_k = 18$, $f_k = 78$, $f_{k-1} = 50$, $f_{k+1} = 46$, and $h = 2$.
$$
\text{mode, } M_o = x_k + \left\{h \times \frac{(f_k - f_{k-1})}{(2 f_k - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
& = 18 + \left\{2 \times \frac{(78 - 50)}{(2 \times 78 - 50 - 46)}\right\} = 18 + \left\{\frac{2 \times 28}{156 - 96}\right\} \\
& = 18 + \left\{\frac{56}{60}\right\} = 18 + \frac{14}{15} \\
& = 18 + 0.93 = 18.93
\end{aligned}
$$

**Case II: Computation of Modal Age of Group B**
In Group B, the class $18-20$ has the maximum frequency ($89$). So, $18-20$ is the **modal class**.
Here, $x_k = 18$, $f_k = 89$, $f_{k-1} = 54$, $f_{k+1} = 40$, and $h = 2$.
$$
\text{mode, } M_o = x_k + \left\{h \times \frac{(f_k - f_{k-1})}{(2 f_k - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
& = 18 + \left\{2 \times \frac{(89 - 54)}{(2 \times 89 - 54 - 40)}\right\} = 18 + \frac{(2 \times 35)}{(178 - 94)} \\
& = 18 + \frac{70}{84} = 18 + \frac{5}{6} \\
& = 18 + 0.83 = 18.83
\end{aligned}
$$
**Comparison**: The modal ages of students in groups A and B are $18.93$ years and $18.83$ years respectively. Therefore, the modal age in group A is greater than the modal age in group B.

---

### Example 7
The following table shows the marks obtained by 100 students of Class X in a school during a particular academic session. Find the mode of this distribution. [CBSE 2013]

| Marks              | Less than 10 | Less than 20 | Less than 30 | Less than 40 | Less than 50 | Less than 60 | Less than 70 | Less than 80 |
| :-----------------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: |
| Number of students | 7            | 21           | 34           | 46           | 66           | 77           | 92           | 100          |

#### Solution:

First, we convert the cumulative frequency distribution to a simple frequency distribution.

| Class     | Frequency       |
| :--------: | :--------------: |
| $0-10$    | 7               |
| $10-20$   | $21 - 7 = 14$   |
| $20-30$   | $34 - 21 = 13$  |
| $30-40$   | $46 - 34 = 12$  |
| $40-50$   | $66 - 46 = 20$  |
| $50-60$   | $77 - 66 = 11$  |
| $60-70$   | $92 - 77 = 15$  |
| $70-80$   | $100 - 92 = 8$  |

Clearly, the **modal class** is $40-50$, as it has the maximum frequency of $20$.

Here, $x_k = 40$, $f_k = 20$, $f_{k-1} = 12$, $f_{k+1} = 11$, $h = 10$.

$$
\text{Mode, } M_o = x_k + \left\{h \times \frac{(f_k - f_{k-1})}{(2 f_k - f_{k-1} - f_{k+1})}\right\}
$$
$$
\begin{aligned}
& = 40 + \left\{10 \times \frac{(20 - 12)}{(2 \times 20 - 12 - 11)}\right\} \\
& = 40 + \left\{10 \times \frac{8}{(40 - 23)}\right\} = 40 + \left\{10 \times \frac{8}{17}\right\} \\
& = 40 + \frac{80}{17} = 40 + 4.71 = 44.71
\end{aligned}
$$
Hence, the **mode** = $44.71$.

---

