# Statistics

## Introduction

In earlier classes we have studied the methods of representing data graphically and in tabular form.

**Mean**, **median** and **mode** are three measures of central tendency, giving us a rough idea about the points where data are centred.

In order to have a better idea as to how the data are scattered, we make a study of (i) **mean deviation** and (ii) **standard deviation**.

---

## Mean Deviations (MD)

- **mean deviation about the mean** The AM of the numerical deviations of the observations from the mean of the data is called the mean deviation about the mean.

- **mean deviation about the median** The AM of the numerical deviations of the observations from the median of the data is called the mean deviation about the median.

---

## Mean Deviations for Ungrouped Data

Let $x_{1}, x_{2}, x_{3}, \ldots, x_{n}$ be the given $n$ observations. Let $\bar{x}$ be the AM and $M$ be the median. Then,

1.  **Mean Deviation about the Mean** $MD(\bar{x})$:
    $$
    MD(\bar{x})=\frac{\sum_{i=1}^{n}\left|x_{i}-\bar{x}\right|}{n}, \text{ where } \bar{x} = \text{mean}
    $$

2.  **Mean Deviation about the Median** $MD(M)$:
    $$
    MD(M)=\frac{\sum_{i=1}^{n}\left|x_{i}-M\right|}{n}, \text{ where } M = \text{median}
    $$

### Summary

1.  $MD(\bar{x})=\frac{\sum_{i=1}^{n}\left|x_{i}-\bar{x}\right|}{n}$, where $\bar{x}$ = mean.
2.  $MD(M)=\frac{\sum_{i=1}^{n}\left|x_{i}-M\right|}{n}$, where $M$ = median.

---

### Example 1

Find the mean deviation about the mean for the following data: $15, 17, 10, 13, 7, 18, 9, 6, 14, 11$.

#### Solution

Let the mean of the given data be $\bar{x}$. Then,
$$
\bar{x}=\frac{\sum_{i=1}^{n} x_{i}}{n}=\frac{120}{10}=12 \quad [\because n=10].
$$
The values of $(x_{i}-\bar{x})$ are:
$3, 5, -2, 1, -5, 6, -3, -6, 2, -1$

So, the values of $|x_{i}-\bar{x}|$ are:
$3, 5, 2, 1, 5, 6, 3, 6, 2, 1.$

$$
\therefore \quad MD(\bar{x})=\frac{\sum_{i=1}^{n}\left|x_{i}-\bar{x}\right|}{n}=\frac{34}{10}=3.4.
$$
Hence, **$MD(\bar{x}) = 3.4$**.

---

### Example 2

Find the mean deviation about the median for the data given below: $11, 3, 8, 7, 5, 14, 10, 2, 9$.

#### Solution

Arranging the given data in an ascending order, we get:
$2, 3, 5, 7, 8, 9, 10, 11, 14.$

Here $n=9$, which is odd.

$$
\therefore \quad \text{median} = \left(\frac{n+1}{2}\right)\text{th observation} = \left(\frac{9+1}{2}\right)\text{th observation} = 5\text{th observation} = 8.
$$

Thus, $M=8$.

The values of $(x_{i}-M)$ are: $-6, -5, -3, -1, 0, 1, 2, 3, 6.$

$$
\therefore \quad \sum_{i=1}^{9}\left|x_{i}-M\right|=(6+5+3+1+0+1+2+3+6)=27
$$

$$
\Rightarrow \quad MD(M)=\frac{\sum_{i=1}^{9}\left|x_{i}-M\right|}{9}=\frac{27}{9}=3.
$$
Hence, **$MD(M) = 3$**.

---

### Example 3

Find the mean deviation about the median for the data given below: $45, 36, 50, 60, 53, 46, 51, 48, 72, 42$.

#### Solution

Arranging the given data in an ascending order, we get:
$36, 42, 45, 46, 48, 50, 51, 53, 60, 72.$

Here $n=10$, which is even.

$$
\begin{aligned}
\therefore \quad \text{median} &= \frac{1}{2} \cdot \left\{ \frac{n}{2}\text{th observation} + \left(\frac{n}{2}+1\right)\text{th observation} \right\} \\
&= \frac{1}{2}(5\text{th observation} + 6\text{th observation}) \\
&= \frac{1}{2}(48+50)=\frac{98}{2}=49
\end{aligned}
$$

Thus, $M=49$.

The values of $(x_{i}-M)$ are: $-13, -7, -4, -3, -1, 1, 2, 4, 11, 23.$

$$
\therefore \quad \sum_{i=1}^{10}\left|x_{i}-M\right|=(13+7+4+3+1+1+2+4+11+23)=69
$$

$$
\Rightarrow \quad MD(M)=\frac{\sum_{i=1}^{10}\left|x_{i}-M\right|}{10}=\frac{69}{10}=6.9.
$$
Hence, **$MD(M) = 6.9$**.

---

## Mean Deviation for Discrete Frequency Distribution

Let the given data consist of $n$ distinct values $x_{1}, x_{2}, \ldots, x_{n}$ occurring with frequencies $f_{1}, f_{2}, \ldots, f_{n}$ respectively.

1.  **Mean deviation about mean:**
    We have:
    $$
    \bar{x}=\frac{\sum_{i=1}^{n} f_{i} x_{i}}{\sum_{i=1}^{n} f_{i}} \Rightarrow \bar{x}=\frac{\sum_{i=1}^{n} f_{i} x_{i}}{N}, \text{ where } N=\sum_{i=1}^{n} f_{i}.
    $$
    $$
    \therefore \quad MD(\bar{x})=\frac{\sum_{i=1}^{n} f_{i}\left|x_{i}-\bar{x}\right|}{\sum_{i=1}^{n} f_{i}}=\frac{\sum_{i=1}^{n} f_{i}\left|x_{i}-\bar{x}\right|}{N}.
    $$

2.  **Mean deviation about median:**
    Let $N=\sum_{i=1}^{n} f_{i}$. First we find the cumulative frequencies and then, identify the observation whose cumulative frequency is equal to or just greater than $\frac{N}{2}$. This value gives the median. Then,
    $$
    MD(M)=\frac{\sum_{i=1}^{n} f_{i}\left|x_{i}-M\right|}{N}
    $$

### Summary

For discrete frequency distribution, we have:

1.  $MD(\bar{x})=\frac{\sum_{i=1}^{n} f_{i}\left|x_{i}-\bar{x}\right|}{N}$, where $\sum_{i=1}^{n} f_{i}=N$.
2.  $MD(M)=\frac{\sum_{i=1}^{n} f_{i}\left|x_{i}-M\right|}{N}$, where $\sum_{i=1}^{n} f_{i}=N$.

---

### Example 4

Find the mean deviation about the mean for the following data:

| $x_{i}$ | 3 | 5 | 7 | 9 | 11 | 13 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $f_{i}$ | 6 | 8 | 15 | 25 | 8 | 4 |

#### Solution

We have $N=\sum_{i=1}^{6} f_{i}=(6+8+15+25+8+4)=66$.

$$
\begin{aligned}
\bar{x} &= \frac{\sum_{i=1}^{6} f_{i} x_{i}}{N} = \frac{(6 \times 3)+(8 \times 5)+(15 \times 7)+(25 \times 9)+(8 \times 11)+(4 \times 13)}{66} \\
&= \frac{18+40+105+225+88+52}{66} = \frac{528}{66}=8.
\end{aligned}
$$

Now, we prepare the table given below:

| $x_{i}$ | $f_{i}$ | $|x_{i}-\bar{x}|$ | $f_{i}|x_{i}-\bar{x}|$ |
| :--- | :--- | :--- | :--- |
| 3 | 6 | 5 | 30 |
| 5 | 8 | 3 | 24 |
| 7 | 15 | 1 | 15 |
| 9 | 25 | 1 | 25 |
| 11 | 8 | 3 | 24 |
| 13 | 4 | 5 | 20 |
|  | **$N=66$** |  | **sum = 138** |

$$
\therefore \quad MD(\bar{x})=\frac{\sum_{i=1}^{6} f_{i}\left|x_{i}-\bar{x}\right|}{N}=\frac{138}{66}=\frac{23}{11} \approx 2.09.
$$
Hence, the mean deviation about the mean is **2.09**.

---

### Example 5

Find the mean deviation about the median for the following data:

| $x_{i}$ | 3 | 5 | 7 | 9 | 11 | 13 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $f_{i}$ | 6 | 8 | 15 | 3 | 8 | 4 |

#### Solution

First, we create a table with cumulative frequencies (cf).

| $x_{i}$ | 3 | 5 | 7 | 9 | 11 | 13 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $f_{i}$ | 6 | 8 | 15 | 3 | 8 | 4 |
| **cf** | 6 | 14 | 29 | 32 | 40 | 44 |

Here, $N=\sum f_{i} = 44$, which is even.

The median is the average of the $(\frac{N}{2})$th and $(\frac{N}{2}+1)$th observations.
$(\frac{44}{2})$th = 22nd observation.
$(\frac{44}{2}+1)$th = 23rd observation.

From the cumulative frequency table, both the 22nd and 23rd observations are 7.

$$
\therefore \quad \text{median} = \frac{1}{2}(22\text{nd observation} + 23\text{rd observation}) = \frac{1}{2}(7+7)=7.
$$

Thus, $M=7$. Now, we calculate the mean deviation about the median.

| $x_{i}$ | $f_{i}$ | $|x_{i}-M|$ | $f_{i}|x_{i}-M|$ |
| :---: | :---: | :---: | :---: |
| 3 | 6 | 4 | 24 |
| 5 | 8 | 2 | 16 |
| 7 | 15 | 0 | 0 |
| 9 | 3 | 2 | 6 |
| 11 | 8 | 4 | 32 |
| 13 | 4 | 6 | 24 |
| | **$N=44$** | | **sum = 102**|

$$
\therefore \quad MD(M)=\frac{\sum_{i=1}^{6} f_{i}\left|x_{i}-M\right|}{N}=\frac{102}{44} \approx 2.32.
$$
Hence, the mean deviation about the median is **2.32**.

---

## Mean Deviation for Continuous Frequency Distribution

### I. Mean Deviation About the Mean for Grouped Data

#### Short Cut Method (Step-deviation method)

1.  Find the class mark $x_{i}$ of each class.
2.  Assume a mean, $A$.
3.  Find deviations, $d_{i}=\frac{(x_{i}-A)}{h}$, where $h=$ class size.
4.  Calculate the mean, $\bar{x}=A+\left(\frac{\sum f_{i} d_{i}}{N} \times h\right)$, where $N=\sum f_{i}$.
5.  Calculate the mean deviation, $MD(\bar{x})=\frac{\sum f_{i}\left|x_{i}-\bar{x}\right|}{N}$.

---

### Example 6

Find the mean deviation about the mean for the following data:

| Marks obtained | 10-20 | 20-30 | 30-40 | 40-50 | 50-60 | 60-70 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Number of students | 8 | 6 | 12 | 5 | 2 | 7 |

#### Solution

Here $h=10$. Let the assumed mean be $A=35$. We prepare the following table.

| Marks obtained | Number of students ($f_{i}$) | Midpoint $x_{i}$ | $d_{i}=\frac{x_{i}-35}{10}$ | $f_{i} d_{i}$ | $|x_{i}-\bar{x}|$ | $f_{i}|x_{i}-\bar{x}|$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 10-20 | 8 | 15 | -2 | -16 | 22 | 176 |
| 20-30 | 6 | 25 | -1 | -6 | 12 | 72 |
| 30-40 | 12 | 35=A | 0 | 0 | 2 | 24 |
| 40-50 | 5 | 45 | 1 | 5 | 8 | 40 |
| 50-60 | 2 | 55 | 2 | 4 | 18 | 36 |
| 60-70 | 7 | 65 | 3 | 21 | 28 | 196 |
|  | **$N = 40$** |  |  | **$\sum f_{i} d_{i}=8$** |  | **$\sum f_{i}|x_{i}-\bar{x}|=544$** |

First, calculate the mean $\bar{x}$:
$$
\bar{x}=A+\left(\frac{\sum f_{i} d_{i}}{N} \times h\right) = 35+\left(\frac{8}{40} \times 10\right) = 35+2 = 37.
$$

Now, calculate the mean deviation about the mean:
$$
\therefore \quad MD(\bar{x})=\frac{\sum f_{i}\left|x_{i}-\bar{x}\right|}{N}=\frac{544}{40}=13.6.
$$
Hence, **$MD(\bar{x}) = 13.6$**.

---

### II. Mean Deviation About the Median for Grouped Data

#### Short Cut Method

1.  Find the class mark $x_{i}$ of each class.
2.  Find the total frequency, $N=\sum f_{i}$.
3.  Find the median class, which is the class interval whose cumulative frequency is greater than or equal to ($N / 2$).
4.  Calculate the median using the formula:
    $$
    M = \text{median} = L+\frac{(\frac{N}{2}-c)}{f} \times h
    $$
    where:
    - $L$ = lower limit of the median class
    - $f$ = frequency of the median class
    - $h$ = width of the median class
    - $c$ = cumulative frequency of the class just preceding the median class
5.  Calculate the mean deviation about the median, $MD(M)=\frac{\sum f_{i}\left|x_{i}-M\right|}{N}$.

---

### Example 7

Calculate the mean deviation about the median for the following data:

| Height (in cm) | 95-105 | 105-115 | 115-125 | 125-135 | 135-145 | 145-155 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Number of boys | 9 | 13 | 25 | 30 | 13 | 10 |

#### Solution

First, we find the median.

| Class | Frequency ($f_{i}$) | Cumulative frequency (cf) | Midpoint ($x_{i}$) |
| :--- | :--- | :--- | :--- |
| 95-105 | 9 | 9 | 100 |
| 105-115 | 13 | 22 | 110 |
| 115-125 | 25 | 47 | 120 |
| **125-135** | **30** | **77** | **130** |
| 135-145 | 13 | 90 | 140 |
| 145-155 | 10 | 100 | 150 |
|  | **$N=100$** |  |  |

Here, $N=100$, so $\frac{N}{2}=50$. The cumulative frequency just greater than 50 is 77, so the **median class is 125-135**.
We have $L=125$, $f=30$, $h=10$, and $c=47$.

$$
\text{median} = L+\frac{(\frac{N}{2}-c)}{f} \times h = 125+\frac{(50-47)}{30} \times 10 = 125 + \frac{3}{3} = 126.
$$
$\therefore \quad M=126$.

Now, we calculate the mean deviation about the median.

| $f_{i}$ | $x_{i}$ | $|x_{i}-M|$ | $f_{i}|x_{i}-M|$ |
| :--- | :--- | :--- | :--- |
| 9 | 100 | 26 | 234 |
| 13 | 110 | 16 | 208 |
| 25 | 120 | 6 | 150 |
| 30 | 130 | 4 | 120 |
| 13 | 140 | 14 | 182 |
| 10 | 150 | 24 | 240 |
| **$N=100$** |  |  | **sum = 1134**|

$$
\therefore \quad MD(M)=\frac{\sum f_{i}\left|x_{i}-M\right|}{N}=\frac{1134}{100}=11.34.
$$
Hence, the mean deviation about the median is **11.34**.

---

### Example 8

Calculate the mean deviation about the median for the following data:

| Class | 16-20 | 21-25 | 26-30 | 31-35 | 36-40 | 41-45 | 46-50 | 51-55 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Frequency | 5 | 6 | 12 | 14 | 26 | 12 | 16 | 9 |

#### Solution

The given series is inclusive. To convert it into an exclusive series, we subtract 0.5 from the lower limits and add 0.5 to the upper limits.

| Class | Frequency ($f_{i}$) | cf | Midpoint ($x_{i}$) |
| :--- | :--- | :--- | :--- |
| 15.5-20.5 | 5 | 5 | 18 |
| 20.5-25.5 | 6 | 11 | 23 |
| 25.5-30.5 | 12 | 23 | 28 |
| 30.5-35.5 | 14 | 37 | 33 |
| **35.5-40.5** | **26** | **63** | **38** |
| 40.5-45.5 | 12 | 75 | 43 |
| 45.5-50.5 | 16 | 91 | 48 |
| 50.5-55.5 | 9 | 100 | 53 |
|  | **$N=100$** |  |  |

Here, $N=100$, so $\frac{N}{2}=50$. The cumulative frequency just greater than 50 is 63, so the **median class is 35.5-40.5**.
We have $L=35.5$, $f=26$, $h=5$, and $c=37$.

$$
\text{median} = L+\frac{(\frac{N}{2}-c)}{f} \times h = 35.5+\frac{(50-37)}{26} \times 5 = 35.5 + \frac{13 \times 5}{26} = 35.5+2.5=38.
$$
Thus, $M=38$.

Now, we calculate the mean deviation about the median.

| $f_{i}$ | $x_{i}$ | $|x_{i}-M|$ | $f_{i}|x_{i}-M|$ |
| :--- | :--- | :--- | :--- |
| 5 | 18 | 20 | 100 |
| 6 | 23 | 15 | 90 |
| 12 | 28 | 10 | 120 |
| 14 | 33 | 5 | 70 |
| 26 | 38 | 0 | 0 |
| 12 | 43 | 5 | 60 |
| 16 | 48 | 10 | 160 |
| 9 | 53 | 15 | 135 |
| **$N=100$** |  |  | **sum = 735**|

Thus, $\sum f_{i}\left|x_{i}-M\right|=735$ and $N=100$.

$$
\therefore \quad MD(M)=\frac{\sum f_{i}\left|x_{i}-M\right|}{N}=\frac{735}{100}=7.35.
$$
Hence, the mean deviation about the median is **7.35**.

---

