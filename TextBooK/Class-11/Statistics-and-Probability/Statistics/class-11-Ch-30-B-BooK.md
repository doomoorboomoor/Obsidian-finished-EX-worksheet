## Variance and Standard Deviation

The **variance** is the mean of the squares of the deviations from the mean, denoted by $\sigma^2$.

The variance of $n$ observations $x_1, x_2, \ldots, x_n$ is given by:
$$
\sigma^2 = \frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^2
$$

The **standard deviation** is the positive square root of the variance, denoted by $\sigma$.
$$
\sigma = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^2}
$$

---
### Example 1

Find the mean, variance, and standard deviation for the following data:
$5, 9, 8, 12, 6, 10, 6, 8$

#### Solution

Here, the number of observations, $n=8$.

**Mean**, $\bar{x}$:
$$
\bar{x} = \frac{1}{8}(5+9+8+12+6+10+6+8) = \frac{64}{8} = 8
$$

The values of $(x_i - \bar{x})$ are:
$-3, 1, 0, 4, -2, 2, -2, 0$.

The sum of the squares of the deviations is:
$$
\sum (x_i - \bar{x})^2 = (9+1+0+16+4+4+4+0) = 38
$$

**Variance**, $\sigma^2$:
$$
\sigma^2 = \frac{\sum (x_i - \bar{x})^2}{n} = \frac{38}{8} = \frac{19}{4} = 4.75
$$

**Standard Deviation**, $\sigma$:
$$
\sigma = \sqrt{4.75} \approx 2.17
$$

Thus, **mean** = $8$, **variance** = $4.75$, and **standard deviation** = $2.17$.

---
## Short Cut Method

For simple ungrouped data, the variance can also be calculated using a derived formula:
$$
\begin{aligned}
\sigma^2 & = \frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^2 \\
& = \frac{1}{n} \sum_{i=1}^{n} (x_i^2 - 2x_i\bar{x} + \bar{x}^2) \\
& = \frac{\sum x_i^2}{n} - 2\bar{x} \left(\frac{\sum x_i}{n}\right) + \frac{n\bar{x}^2}{n} \\
& = \frac{\sum x_i^2}{n} - 2\bar{x} \cdot \bar{x} + \bar{x}^2 \\
& = \frac{\sum x_i^2}{n} - \bar{x}^2
\end{aligned}
$$

Thus, for the **short cut method**, we have:
$$
\sigma^2 = \frac{\sum x_i^2}{n} - \bar{x}^2
$$

---
### Example 2

Find the mean, standard deviation, and variance of the first $n$ natural numbers.

#### Solution

The first $n$ natural numbers are $1, 2, 3, \ldots, n$.

**Mean**, $\bar{x}$:
$$
\bar{x} = \frac{1+2+3+\ldots+n}{n} = \frac{1}{n} \cdot \frac{n(n+1)}{2} = \frac{n+1}{2}
$$
(Since $\sum n = \frac{n(n+1)}{2}$)

**Variance**, $\sigma^2$:
We use the formula $\sigma^2 = \frac{\sum x_i^2}{n} - \bar{x}^2$.
$$
\begin{aligned}
\sigma^2 & = \frac{\sum n^2}{n} - \left(\frac{n+1}{2}\right)^2 \\
& = \frac{1}{n} \cdot \frac{n(n+1)(2n+1)}{6} - \frac{(n+1)^2}{4} \quad \left[\text{Since } \sum n^2 = \frac{n(n+1)(2n+1)}{6}\right] \\
& = \frac{(n+1)(2n+1)}{6} - \frac{(n+1)^2}{4} \\
& = (n+1) \left[ \frac{2n+1}{6} - \frac{n+1}{4} \right] \\
& = (n+1) \left[ \frac{2(2n+1) - 3(n+1)}{12} \right] \\
& = (n+1) \left[ \frac{4n+2-3n-3}{12} \right] \\
& = \frac{(n+1)(n-1)}{12} = \frac{n^2-1}{12}
\end{aligned}
$$
So, **variance**, $\sigma^2 = \frac{n^2-1}{12}$.

**Standard Deviation**, $\sigma$:
$$
\sigma = \sqrt{\frac{n^2-1}{12}}
$$

---
### Example 3

Find the mean, standard deviation, and variance of the first 10 multiples of 3.

#### Solution

The first 10 multiples of 3 are $3, 6, 9, 12, \ldots, 30$.
This is an AP with $a=3$, $n=10$, and $l=30$.

Sum of observations:
$$
\text{Sum} = \frac{n}{2}(a+l) = \frac{10}{2}(3+30) = 165
$$

**Mean**, $\bar{x}$:
$$
\bar{x} = \frac{165}{10} = 16.5
$$

**Variance**, $\sigma^2$:
$$
\begin{aligned}
\sigma^2 & = \frac{\sum x_i^2}{n} - \bar{x}^2 \\
& = \frac{3^2 + 6^2 + 9^2 + \ldots + 30^2}{10} - (16.5)^2 \\
& = \frac{3^2(1^2 + 2^2 + 3^2 + \ldots + 10^2)}{10} - (16.5)^2 \\
& = \frac{9 \times \frac{10(10+1)(2 \times 10+1)}{6}}{10} - 272.25 \\
& = \frac{9 \times 10 \times 11 \times 21}{6 \times 10} - 272.25 \\
& = \frac{9 \times 11 \times 21}{6} - 272.25 \\
& = 346.5 - 272.25 = 74.25
\end{aligned}
$$
So, **variance**, $\sigma^2 = 74.25$.

**Standard Deviation**, $\sigma$:
$$
\sigma = \sqrt{74.25} \approx 8.61
$$

---
## Variance and Standard Deviation of a Discrete Frequency Distribution

For a given frequency distribution:
| Variable ($x_i$) | $x_1$ | $x_2$ | $x_3$ | $\ldots$ | $x_n$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Frequency ($f_i$) | $f_1$ | $f_2$ | $f_3$ | $\ldots$ | $f_n$ |

- **Variance**:
$$
\sigma^2 = \frac{1}{N} \sum_{i=1}^{n} f_i (x_i - \bar{x})^2, \quad \text{where } N = \sum_{i=1}^{n} f_i
$$
- **Standard Deviation**:
$$
\sigma = \sqrt{\frac{1}{N} \sum_{i=1}^{n} f_i (x_i - \bar{x})^2}
$$

---
### Example 4

Find the variance and standard deviation for the following data:

| $x_i$ | 10 | 15 | 18 | 20 | 25 |
| :---: | :-: | :-: | :-: | :-: | :-: |
| $f_i$ | 3 | 2 | 5 | 8 | 2 |

#### Solution

First, we calculate the mean, $\bar{x}$.
$$
\bar{x} = \frac{\sum f_i x_i}{\sum f_i} = \frac{10(3) + 15(2) + 18(5) + 20(8) + 25(2)}{3+2+5+8+2} = \frac{30+30+90+160+50}{20} = \frac{360}{20} = 18
$$
Here, $N = \sum f_i = 20$. Now we can prepare the table for calculation:

| $x_i$ | $f_i$ | $f_i x_i$ | $(x_i - \bar{x})$ | $(x_i - \bar{x})^2$ | $f_i (x_i - \bar{x})^2$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 10 | 3 | 30 | -8 | 64 | 192 |
| 15 | 2 | 30 | -3 | 9 | 18 |
| 18 | 5 | 90 | 0 | 0 | 0 |
| 20 | 8 | 160 | 2 | 4 | 32 |
| 25 | 2 | 50 | 7 | 49 | 98 |
| **Total**| **$N=20$**| **360** | | | **$\sum f_i (x_i - \bar{x})^2 = 340$** |

**Variance**, $\sigma^2$:
$$
\sigma^2 = \frac{1}{N} \sum f_i (x_i - \bar{x})^2 = \frac{1}{20} \times 340 = 17
$$

**Standard Deviation**, $\sigma$:
$$
\sigma = \sqrt{17} \approx 4.12
$$

---
### Short Cut Method

Let $A$ be the **assumed mean** and let $d_i = (x_i - A)$. Then, the variance is given by:
$$
\sigma^2 = \frac{\sum f_i d_i^2}{N} - \left(\frac{\sum f_i d_i}{N}\right)^2
$$

---
### Example 5

Find the mean, variance, and standard deviation for the following data using the short cut method:

| $x_i$ | 60 | 61 | 62 | 63 | 64 | 65 | 66 | 67 | 68 |
| :---: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| $f_i$ | 2 | 1 | 12 | 29 | 25 | 12 | 10 | 4 | 5 |

#### Solution

Let the assumed mean be $A=64$. We prepare the following table:

| $x_i$ | $f_i$ | $d_i = (x_i - 64)$ | $d_i^2$ | $f_i d_i$ | $f_i d_i^2$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 60 | 2 | -4 | 16 | -8 | 32 |
| 61 | 1 | -3 | 9 | -3 | 9 |
| 62 | 12 | -2 | 4 | -24 | 48 |
| 63 | 29 | -1 | 1 | -29 | 29 |
| 64=A | 25 | 0 | 0 | 0 | 0 |
| 65 | 12 | 1 | 1 | 12 | 12 |
| 66 | 10 | 2 | 4 | 20 | 40 |
| 67 | 4 | 3 | 9 | 12 | 36 |
| 68 | 5 | 4 | 16 | 20 | 80 |
| **Total**| **$N=100$**| | | **$\sum f_i d_i=0$** | **$\sum f_i d_i^2=286$** |

We have $N=100$, $\sum f_i d_i = 0$, and $\sum f_i d_i^2 = 286$.

**Mean**, $\bar{x}$:
$$
\bar{x} = A + \frac{\sum f_i d_i}{N} = 64 + \frac{0}{100} = 64
$$

**Variance**, $\sigma^2$:
$$
\sigma^2 = \frac{\sum f_i d_i^2}{N} - \left(\frac{\sum f_i d_i}{N}\right)^2 = \frac{286}{100} - \left(\frac{0}{100}\right)^2 = 2.86
$$

**Standard Deviation**, $\sigma$:
$$
\sigma = \sqrt{2.86} \approx 1.69
$$

---
## When Mean is a Decimal Fraction

In cases where the mean is a decimal, direct calculation can be tedious. The following formulas are more convenient:

- **Variance**:
$$
\sigma^2 = \frac{1}{N^2} \left[ N \sum_{i=1}^{n} f_i x_i^2 - \left(\sum_{i=1}^{n} f_i x_i\right)^2 \right]
$$
- **Standard Deviation**:
$$
\sigma = \frac{1}{N} \sqrt{N \sum_{i=1}^{n} f_i x_i^2 - \left(\sum_{i=1}^{n} f_i x_i\right)^2}
$$

---
### Example 6

Find the standard deviation for the following data:

| $x_i$ | 3 | 8 | 13 | 18 | 23 |
| :---: | :-: | :-: | :-: | :-: | :-: |
| $f_i$ | 6 | 10 | 14 | 10 | 10 |

#### Solution

First, let's calculate the mean to see if it's a decimal.
$$
\bar{x} = \frac{\sum f_i x_i}{\sum f_i} = \frac{3(6)+8(10)+13(14)+18(10)+23(10)}{6+10+14+10+10} = \frac{18+80+182+180+230}{50} = \frac{690}{50} = 13.8
$$
Since the mean is a decimal, we use the alternate formula. We prepare the following table:

| $x_i$ | $f_i$ | $f_i x_i$ | $x_i^2$ | $f_i x_i^2$ |
| :---: | :---: | :---: | :---: | :---: |
| 3 | 6 | 18 | 9 | 54 |
| 8 | 10 | 80 | 64 | 640 |
| 13 | 14 | 182 | 169 | 2366 |
| 18 | 10 | 180 | 324 | 3240 |
| 23 | 10 | 230 | 529 | 5290 |
| **Total**| **$N=50$**| **$\sum f_i x_i=690$** | | **$\sum f_i x_i^2=11590$** |

We have $N=50$, $\sum f_i x_i = 690$, and $\sum f_i x_i^2 = 11590$.

**Standard Deviation**, $\sigma$:
$$
\begin{aligned}
\sigma & = \frac{1}{N} \sqrt{N \sum f_i x_i^2 - (\sum f_i x_i)^2} \\
& = \frac{1}{50} \sqrt{50 \times 11590 - (690)^2} \\
& = \frac{1}{50} \sqrt{579500 - 476100} \\
& = \frac{1}{50} \sqrt{103400} \\
& \approx \frac{321.5}{50} \approx 6.43
\end{aligned}
$$
Hence, $\sigma \approx 6.43$.

---
## Shorter Method For Standard Deviation of Continuous Frequency Distribution

Let $A$ be the **assumed mean**, $h$ be the **class width**, and let $y_i = \frac{x_i - A}{h}$, where $x_i$ is the midpoint of the class. Then we have:

- **Variance**:
$$
\sigma^2 = \frac{h^2}{N^2} \left[ N \sum_{i=1}^{n} f_i y_i^2 - \left(\sum_{i=1}^{n} f_i y_i\right)^2 \right]
$$
- **Standard Deviation**:
$$
\sigma = \frac{h}{N} \sqrt{N \sum_{i=1}^{n} f_i y_i^2 - \left(\sum_{i=1}^{n} f_i y_i\right)^2}
$$

---
### Example 7

Calculate mean, variance, and standard deviation for the following frequency distribution:

| Class | 0-30 | 30-60 | 60-90 | 90-120 | 120-150 | 150-180 | 180-210 |
| :---: | :--: | :---: | :---: | :----: | :-----: | :-----: | :-----: |
| Frequency | 2 | 3 | 5 | 10 | 3 | 5 | 2 |

#### Solution

Here, the class width is $h=30$. Let the assumed mean be $A=105$ (the midpoint of the class 90-120). We prepare the table:

| Class | Freq ($f_i$) | Midpoint ($x_i$) | $y_i=\frac{x_i-105}{30}$ | $y_i^2$ | $f_i y_i$ | $f_i y_i^2$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| 0-30 | 2 | 15 | -3 | 9 | -6 | 18 |
| 30-60 | 3 | 45 | -2 | 4 | -6 | 12 |
| 60-90 | 5 | 75 | -1 | 1 | -5 | 5 |
| 90-120 | 10 | $105=A$ | 0 | 0 | 0 | 0 |
| 120-150 | 3 | 135 | 1 | 1 | 3 | 3 |
| 150-180 | 5 | 165 | 2 | 4 | 10 | 20 |
| 180-210 | 2 | 195 | 3 | 9 | 6 | 18 |
| **Total** | **$N=30$** | | | | **$\sum f_i y_i=2$** | **$\sum f_i y_i^2=76$** |

We have $A=105$, $h=30$, $N=30$, $\sum f_i y_i = 2$, and $\sum f_i y_i^2 = 76$.

**Mean**, $\bar{x}$:
$$
\bar{x} = A + \left(\frac{\sum f_i y_i}{N}\right) \times h = 105 + \left(\frac{2}{30}\right) \times 30 = 105 + 2 = 107
$$

**Variance**, $\sigma^2$:
$$
\sigma^2 = \frac{h^2}{N^2} \left[ N \sum f_i y_i^2 - (\sum f_i y_i)^2 \right] = \frac{30^2}{30^2} [30 \times 76 - (2)^2] = 2280 - 4 = 2276
$$

**Standard Deviation**, $\sigma$:
$$
\sigma = \sqrt{2276} \approx 47.71
$$

---
### Example 8

Given below are the diameters of circles (in mm) drawn in a design. Calculate the mean diameter, variance, and standard deviation.

| Diameter | 33-36 | 37-40 | 41-44 | 45-48 | 49-52 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| No. of circles | 15 | 17 | 21 | 22 | 25 |

#### Solution

The given series is inclusive. To make it exclusive, we subtract 0.5 from the lower limit and add 0.5 to the upper limit of each class. The class width $h=4$. Let the assumed mean be $A=42.5$.

| Class | Freq ($f_i$) | Midpoint ($x_i$) | $y_i=\frac{x_i-42.5}{4}$ | $y_i^2$ | $f_i y_i$ | $f_i y_i^2$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| 32.5-36.5 | 15 | 34.5 | -2 | 4 | -30 | 60 |
| 36.5-40.5 | 17 | 38.5 | -1 | 1 | -17 | 17 |
| 40.5-44.5 | 21 | $42.5=A$ | 0 | 0 | 0 | 0 |
| 44.5-48.5 | 22 | 46.5 | 1 | 1 | 22 | 22 |
| 48.5-52.5 | 25 | 50.5 | 2 | 4 | 50 | 100 |
| **Total** | **$N=100$** | | | | **$\sum f_i y_i=25$** | **$\sum f_i y_i^2=199$** |

We have $A=42.5$, $h=4$, $N=100$, $\sum f_i y_i = 25$, and $\sum f_i y_i^2 = 199$.

**Mean**, $\bar{x}$:
$$
\bar{x} = A + \left(\frac{\sum f_i y_i}{N}\right) \times h = 42.5 + \left(\frac{25}{100}\right) \times 4 = 42.5 + 1 = 43.5 \text{ mm}
$$

**Variance**, $\sigma^2$:
$$
\begin{aligned}
\sigma^2 & = \frac{h^2}{N^2} \left[ N \sum f_i y_i^2 - (\sum f_i y_i)^2 \right] \\
& = \frac{4^2}{100^2} [100 \times 199 - (25)^2] \\
& = \frac{16}{10000} [19900 - 625] \\
& = \frac{16}{10000} \times 19275 = \frac{308400}{10000} = 30.84
\end{aligned}
$$

**Standard Deviation**, $\sigma$:
$$
\sigma = \sqrt{30.84} \approx 5.55
$$
Hence, **mean** = $43.5$ mm, **variance** = $30.84$, and **standard deviation** = $5.55$.

---
