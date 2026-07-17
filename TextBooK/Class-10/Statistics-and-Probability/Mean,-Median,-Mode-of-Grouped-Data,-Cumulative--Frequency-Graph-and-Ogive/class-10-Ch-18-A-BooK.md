# Mean, Median, Mode of Grouped Data, Cumulative Frequency Graph and Ogive

## Introduction

Suppose we want to compare the wage distribution of workers in two factories and determine which factory pays more to its workers. If we compare on the basis of individual workers, we cannot conclude anything. However, if for the given data, we get a representative value that signifies the characteristics of the data, the comparison becomes easy.

A certain value representative of the whole data and signifying its characteristics is called an **average** of the data.

An average tends to lie centrally with the values of the variable arranged in ascending order of magnitude. So, we call an average a **measure of central tendency** of the data.

Three measures of central tendency are useful for analysing the data, namely:
- **Mean**
- **Median**
- **Mode**

---

## Mean of Grouped Data

We already know that

$$
\text{mean} = \frac{\text{sum of observations}}{\text{number of observations}}
$$

Thus, if $x_1, x_2, \ldots, x_n$ are $n$ observations with respective frequencies $f_1, f_2, \ldots, f_n$ then the mean is given by

$$
\bar{x} = \frac{f_1 x_1 + f_2 x_2 + \ldots + f_n x_n}{f_1 + f_2 + \ldots + f_n} = \frac{\sum_{i=1}^{n} f_i x_i}{\sum f_i}
$$

where the Greek letter $\Sigma$ (read as, sigma) stands for summation of the terms.

There are three methods for computing the mean of grouped data.

### I. Direct Method

In this method, the midpoint or **class mark** of each class interval is taken to represent the observations falling in the class. We proceed stepwise as follows:

1.  For each class interval, find the class mark $x_i$ as
    $$
    x_i = \frac{\text{upper class limit} + \text{lower class limit}}{2}
    $$
2.  Calculate $f_i x_i$ for each $i$.
3.  Calculate the mean using the formula
    $$
    \text{mean} = \frac{\Sigma f_i x_i}{\Sigma f_i}
    $$

### Example 1

Find the mean of the following data:

| Class interval | 0-10 | 10-20 | 20-30 | 30-40 | 40-50 |
| :------------: | :--: | :---: | :---: | :---: | :---: |
|   Frequency    |  8   |  12   |  10   |  11   |   9   |

[CBSE 2007]

#### Solution

We may prepare the table as shown:

| Class interval | Frequency $f_i$ | Class mark $x_i$ | ($f_i \times x_i$) |
| :------------- | :-------------- | :--------------- | :----------------- |
| 0-10           | 8               | 5                | 40                 |
| 10-20          | 12              | 15               | 180                |
| 20-30          | 10              | 25               | 250                |
| 30-40          | 11              | 35               | 385                |
| 40-50          | 9               | 45               | 405                |
|                | $\Sigma f_i=50$ |                  | $\Sigma(f_i \times x_i)=1260$ |

$$
\therefore \quad \text{mean} = \frac{\Sigma(f_i \times x_i)}{\Sigma f_i} = \frac{1260}{50} = 25.2
$$

---

### Example 2

The arithmetic mean of the following frequency distribution is 25. Determine the value of $p$.

[CBSE 2006]

| Class     | 0-10 | 10-20 | 20-30 | 30-40 | 40-50 |
| :-------: | :--: | :---: | :---: | :---: | :---: |
| Frequency |  5   |  18   |  15   |  $p$  |   6   |

#### Solution

We have

| Class interval | Frequency $f_i$ | Midvalue $x_i$ | ($f_i \times x_i$) |
| :------------: | :-------------- | :------------- | :----------------- |
| 0-10           | 5               | 5              | 25                 |
| 10-20          | 18              | 15             | 270                |
| 20-30          | 15              | 25             | 375                |
| 30-40          | $p$             | 35             | $35p$              |
| 40-50          | 6               | 45             | 270                |
|                | $\Sigma f_i=(44+p)$ |                | $\Sigma(f_i \times x_i)=(940+35p)$ |

$$
\begin{aligned}
\therefore \quad \text{mean, } \bar{x} = \frac{\Sigma(f_i \times x_i)}{\Sigma f_i} & \Rightarrow \frac{(940+35p)}{(44+p)} = 25 \\
& \Rightarrow (940+35p) = 25(44+p) \\
& \Rightarrow (35p-25p) = (1100-940) \\
& \Rightarrow 10p = 160 \Rightarrow p=16.
\end{aligned}
$$

Hence, $p=16$.

---

### Example 3

If the mean of the following frequency distribution is 65.6, find the missing frequencies $f_1$ and $f_2$.

[CBSE 2010]

| Class     | 10-30 | 30-50 | 50-70 | 70-90 | 90-110 | 110-130 | Total |
| :-------: | :---: | :---: | :---: | :---: | :----: | :-----: | :---: |
| Frequency |   5   |   8   | $f_1$ |  20   | $f_2$  |    2    |  50   |

#### Solution

We have

$5+8+f_1+20+f_2+2=50 \Rightarrow f_2=(15-f_1)$

Now, we may prepare the table given below:

| Class interval | Frequency $f_i$ | Class mark $x_i$ | ($f_i \times x_i$) |
| :------------- | :-------------- | :--------------- | :----------------- |
| 10-30          | 5               | 20               | 100                |
| 30-50          | 8               | 40               | 320                |
| 50-70          | $f_1$           | 60               | $60f_1$            |
| 70-90          | 20              | 80               | 1600               |
| 90-110         | $15-f_1$        | 100              | $1500-100f_1$      |
| 110-130        | 2               | 120              | 240                |
|                | $\Sigma f_i=50$ |                  | $\Sigma(f_i \times x_i)=(3760-40f_1)$ |

$$
\therefore \quad \text{mean} = \frac{\Sigma(f_i \times x_i)}{\Sigma f_i} = \frac{(3760-40f_1)}{50}
$$

But, mean $= 65.6$ (given).

$$
\begin{aligned}
\therefore \quad \frac{(3760-40f_1)}{50} = 65.6 & \Rightarrow 3760-40f_1 = 3280 \\
& \Rightarrow 40f_1 = 480 \Rightarrow f_1 = 12
\end{aligned}
$$

Thus, $f_1=12$ and $f_2=(15-12)=3$.

---

### II. Assumed-Mean Method

This method is usually used when the numerical values of $x_i$ and $f_i$ are large due to which calculations become tedious and time-consuming.

We proceed stepwise as follows:

1.  For each class interval, calculate the class mark $x_i$ by using the formula,
    $$
    x_i = \frac{\text{upper class limit} + \text{lower class limit}}{2}
    $$
2.  Choose a suitable value of $x_i$ in the middle as the **assumed mean** and denote it by $A$.
3.  Calculate the deviations $d_i=(x_i-A)$ for each $i$.
4.  Calculate the product $(f_i d_i)$ for each $i$.
5.  Find $n=\Sigma f_i$.
6.  Calculate the mean, $\bar{x}$, by using the formula,
    $$
    \bar{x} = A + \frac{\Sigma f_i d_i}{n}
    $$

### Mathematical Derivation of Assumed Mean Formula

We have mean of the deviations, $\bar{d}=\frac{\Sigma f_i d_i}{\Sigma f_i}$.

But, $d_i = (x_i-A)$, where $A$ is the assumed mean.

$$
\begin{aligned}
\therefore \bar{d} &= \frac{\Sigma f_i(x_i-A)}{\Sigma f_i} = \frac{\Sigma f_i x_i}{\Sigma f_i} - \frac{\Sigma f_i A}{\Sigma f_i} = \bar{x} - A \frac{\Sigma f_i}{\Sigma f_i} = \bar{x} - A \\
& \Rightarrow \bar{x} = A + \bar{d} \\
& \Rightarrow \bar{x} = A + \frac{\Sigma f_i d_i}{\Sigma f_i}
\end{aligned}
$$

---

### Example 4

Data regarding the weights of students of Class X of a school is given below.

| Weight (in kg) | 50-52 | 52-54 | 54-56 | 56-58 | 58-60 | 60-62 | 62-64 |
| :------------- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Number of students |  18   |  21   |  17   |  28   |  16   |  35   |  15   |

Compute the mean weight of the students. [CBSE 2014]

#### Solution

Let $A=57$ be the assumed mean. Then, we have

| Class interval | Frequency $f_i$ | Class mark $x_i$ | Deviation $d_i=(x_i-A)=(x_i-57)$ | ($f_i \times d_i$) |
| :------------- | :-------------- | :--------------- | :--------------------------------- | :----------------- |
| 50-52          | 18              | 51               | -6                                 | -108               |
| 52-54          | 21              | 53               | -4                                 | -84                |
| 54-56          | 17              | 55               | -2                                 | -34                |
| 56-58          | 28              | $57=A$           | 0                                  | 0                  |
| 58-60          | 16              | 59               | 2                                  | 32                 |
| 60-62          | 35              | 61               | 4                                  | 140                |
| 62-64          | 15              | 63               | 6                                  | 90                 |
|                | $\Sigma f_i=150$ |                  |                                    | $\Sigma(f_i \times d_i)=36$ |

$$
\begin{aligned}
\therefore \quad \bar{x} &= A + \frac{\Sigma(f_i \times d_i)}{\Sigma f_i} = \left(57+\frac{36}{150}\right) = 57+0.24 = 57.24 \\
\end{aligned}
$$

Hence, mean weight = $57.24 \text{ kg}$.

---

### III. Step-Deviation Method

This method is also used to simplify calculations in the process of computing the mean. It is particularly used when the values of $(x_i-A)$ are large and divisible by the class size (= upper limit - lower limit).

We proceed stepwise as shown below.

1.  For each class interval, calculate the class mark $x_i$, where
    $$
    x_i = \frac{\text{upper class limit} + \text{lower class limit}}{2}
    $$
2.  Choose a suitable value of $x_i$ in the middle as the assumed mean and denote it by $A$.
3.  Calculate $h = \text{(upper limit - lower limit)}$, which is the same for all the classes.
4.  Calculate $u_i = \frac{(x_i - A)}{h}$ for each class.
5.  Calculate $f_i u_i$ for each class.
6.  Calculate $\Sigma f_i$ and $\Sigma f_i u_i$.
7.  Calculate the mean by using the formula
    $$
    \bar{x} = A + \left\{h \times \frac{\Sigma f_i u_i}{\Sigma f_i}\right\}
    $$

### Mathematical Derivation of Step-Deviation Formula

We have $\bar{u} = \frac{\Sigma(f_i u_i)}{\Sigma f_i}$.

But, $u_i = \frac{x_i - A}{h}$.

$$
\begin{aligned}
\therefore \quad \bar{u} &= \frac{\Sigma f_i \frac{(x_i-A)}{h}}{\Sigma f_i} = \frac{1}{h}\left[\frac{\Sigma(f_i x_i - A \Sigma f_i)}{\Sigma f_i}\right] \\
&= \frac{1}{h}\left[\frac{\Sigma(f_i x_i)}{\Sigma f_i} - A \frac{\Sigma f_i}{\Sigma f_i}\right] \\
&= \frac{1}{h}(\bar{x}-A) \\
\Rightarrow \quad h \bar{u} &= \bar{x} - A \\
\Rightarrow \quad \bar{x} &= A + h \bar{u} \\
\Rightarrow \quad \bar{x} &= A + h\left(\frac{\Sigma(f_i u_i)}{\Sigma f_i}\right)
\end{aligned}
$$

---

### Example 5

Calculate the arithmetic mean of the following frequency distribution, using the step-deviation method:

[CBSE 2001C]

| Class interval | Frequency |
| :------------: | :-------: |
| 0-50           |    17     |
| 50-100         |    35     |
| 100-150        |    43     |
| 150-200        |    40     |
| 200-250        |    21     |
| 250-300        |    24     |

#### Solution

Here, $h=50$. Let the assumed mean be $A=125$.

For calculating the mean, we prepare the table given as follows:

| Class interval | Frequency $f_i$ | Midvalue $x_i$ | $u_i = \frac{(x_i - A)}{h}$ | ($f_i \times u_i$) |
| :------------: | :-------------- | :------------- | :-------------------------- | :----------------- |
| 0-50           | 17              | 25             | -2                          | -34                |
| 50-100         | 35              | 75             | -1                          | -35                |
| 100-150        | 43              | $125=A$        | 0                           | 0                  |
| 150-200        | 40              | 175            | 1                           | 40                 |
| 200-250        | 21              | 225            | 2                           | 42                 |
| 250-300        | 24              | 275            | 3                           | 72                 |
|                | $\Sigma f_i=180$ |                |                             | $\Sigma(f_i u_i) = 154-69=85$ |

Thus, we have
$A=125, h=50, \Sigma f_i=180$ and $\Sigma(f_i u_i)=85$.

$$
\begin{aligned}
\text{Mean, } \bar{x} &= A + \left\{h \times \frac{\Sigma(f_i u_i)}{\Sigma f_i}\right\} \\
&= 125 + \left\{50 \times \frac{85}{180}\right\} = 125 + 23.61 = 148.61
\end{aligned}
$$

Hence, the mean of the given frequency is 148.61.

---

### Example 6

The following table gives the distribution of expenditures of different families on education. Find the mean expenditure on education of a family.

[CBSE 2004C]

| Expenditure (in ₹) | Number of families |
| :----------------- | :----------------: |
| 1000-1500          |         24         |
| 1500-2000          |         10         |
| 2000-2500          |         33         |
| 2500-3000          |         28         |
| 3000-3500          |         30         |
| 3500-4000          |         22         |
| 4000-4500          |         16         |
| 4500-5000          |         7          |

#### Solution

Here, $h=500$.

For calculating the mean, we prepare the table given as follows:

| Class interval | Frequency $f_i$ | Midvalue $x_i$ | $u_i = \frac{(x_i - A)}{h}$ | ($f_i \times u_i$) |
| :------------: | :-------------- | :------------- | :-------------------------- | :----------------- |
| 1000-1500      | 24              | 1250           | -3                          | -72                |
| 1500-2000      | 10              | 1750           | -2                          | -20                |
| 2000-2500      | 33              | 2250           | -1                          | -33                |
| 2500-3000      | 28              | $2750=A$       | 0                           | 0                  |
| 3000-3500      | 30              | 3250           | 1                           | 30                 |
| 3500-4000      | 22              | 3750           | 2                           | 44                 |
| 4000-4500      | 16              | 4250           | 3                           | 48                 |
| 4500-5000      | 7               | 4750           | 4                           | 28                 |
|                | $\Sigma f_i=170$ |                |                             | $\Sigma(f_i \times u_i)=25$ |

Thus, $A=2750, h=500, \Sigma f_i=170$ and $\Sigma(f_i \times u_i)=25$.

$$
\begin{aligned}
\therefore \quad \text{mean} &= A + \left\{h \times \frac{\Sigma(f_i \times u_i)}{\Sigma f_i}\right\} \\
&= 2750 + \left(\frac{500 \times 25}{170}\right) = 2750 + 73.53 = 2823.53
\end{aligned}
$$

Hence, the required mean expenditure = ₹2823.53.

---

### Example 7

Compute the arithmetic mean for the following data:

| Marks obtained | Number of students |
| :------------- | :----------------: |
| Less than 10   |         14         |
| Less than 20   |         22         |
| Less than 30   |         37         |
| Less than 40   |         58         |
| Less than 50   |         67         |
| Less than 60   |         75         |

#### Solution

The above data may be written as:

| Class     | 0-10 | 10-20 | 20-30 | 30-40 | 40-50 | 50-60 |
| :-------: | :--: | :---: | :---: | :---: | :---: | :---: |
| Frequency |  14  |   8   |  15   |  21   |   9   |   8   |

Here, $h=10$.

Let assumed mean = midpoint of (30-40) = 35.

Now, we form the table as under.

| Class | Frequency $f_i$ | Midvalue $x_i$ | $u_i = \frac{(x_i - A)}{h} = \frac{(x_i - 35)}{10}$ | ($f_i \times u_i$) |
| :---- | :-------------- | :------------- | :------------------------------------------------- | :----------------- |
| 0-10  | 14              | 5              | -3                                                 | -42                |
| 10-20 | 8               | 15             | -2                                                 | -16                |
| 20-30 | 15              | 25             | -1                                                 | -15                |
| 30-40 | 21              | $35=A$         | 0                                                  | 0                  |
| 40-50 | 9               | 45             | 1                                                  | 9                  |
| 50-60 | 8               | 55             | 2                                                  | 16                 |
|       | $\Sigma f_i=75$ |                |                                                    | $\Sigma(f_i \times u_i)=-48$ |

$$
\begin{aligned}
\therefore \quad \text{mean, } \bar{x} &= \left\{A + \frac{h \times (\Sigma f_i \times u_i)}{\Sigma f_i}\right\} = \left\{35 + \left(\frac{10 \times (-48)}{75}\right)\right\} \\
&= 35 - 6.4 = 28.6
\end{aligned}
$$

---

## Mean for an Inclusive Series

### Example 8

Find the arithmetic mean of the following frequency distribution:

| Class     | 25-29 | 30-34 | 35-39 | 40-44 | 45-49 | 50-54 | 55-59 |
| :-------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Frequency |  14   |  22   |  16   |   6   |   5   |   3   |   4   |

[CBSE 2006C]

#### Solution

The given series is an inclusive series. Making it an exclusive series, we get

| Class       | Frequency $f_i$ | Midvalue $x_i$ | $u_i = \frac{(x_i - A)}{h} = \frac{(x_i - 42)}{5}$ | ($f_i \times u_i$) |
| :---------- | :-------------- | :------------- | :------------------------------------------------- | :----------------- |
| 24.5-29.5   | 14              | 27             | -3                                                 | -42                |
| 29.5-34.5   | 22              | 32             | -2                                                 | -44                |
| 34.5-39.5   | 16              | 37             | -1                                                 | -16                |
| 39.5-44.5   | 6               | $42=A$         | 0                                                  | 0                  |
| 44.5-49.5   | 5               | 47             | 1                                                  | 5                  |
| 49.5-54.5   | 3               | 52             | 2                                                  | 6                  |
| 54.5-59.5   | 4               | 57             | 3                                                  | 12                 |
|             | $\Sigma f_i=70$ |                |                                                    | $\Sigma(f_i \times u_i)=-79$ |

Thus, $A=42, h=5, \Sigma f_i=70$ and $\Sigma(f_i \times u_i)=-79$.

$$
\begin{aligned}
\therefore \quad \text{mean, } \bar{x} &= A + \left\{h \times \frac{\Sigma(f_i \times u_i)}{\Sigma f_i}\right\} = 42 + \left\{5 \times \frac{(-79)}{70}\right\} \\
&= 42 - 5.64 = 36.36
\end{aligned}
$$

Hence, the required arithmetic mean is 36.36.

**Remember:** The value of mean obtained by all the above three methods is the same.

---

