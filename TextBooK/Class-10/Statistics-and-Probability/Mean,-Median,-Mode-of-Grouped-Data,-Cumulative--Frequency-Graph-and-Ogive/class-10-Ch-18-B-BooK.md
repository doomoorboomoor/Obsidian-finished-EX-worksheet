## MEDIAN FOR GROUPED DATA

The **median** is a measure of central tendency which gives the value of the middlemost observation in the data.

As we have already studied, for an ungrouped data comprising `$n$` observations:

$$
\text{Median} = \begin{cases} \left(\frac{n+1}{2}\right)\text{th observation,} & \text{if } n \text{ is odd} \\ \frac{\left(\frac{n}{2}\right)\text{th observation} + \left(\frac{n}{2}+1\right)\text{th observation}}{2}, & \text{if } n \text{ is even} \end{cases}
$$

---

## METHOD FOR FINDING THE MEDIAN FOR GROUPED DATA

We proceed stepwise as follows:

1.  For the given frequency distribution, find the sum of frequencies, `$N = \Sigma f_{i}$`.
2.  Find the value of `$\frac{N}{2}$`.
3.  Look at the cumulative frequency column and find the cumulative frequency just greater than `$\frac{N}{2}$`. The corresponding class is the **median class**.
4.  Compute the median using the formula:

$$
\text{Median, } M_{e} = l + \left\{h \times \frac{\left(\frac{N}{2} - cf\right)}{f}\right\}
$$

where:
-   `$l$` = lower limit of the median class
-   `$h$` = width of the median class
-   `$f$` = frequency of the median class
-   `$cf$` = cumulative frequency of the class *preceding* the median class
-   `$N$` = `$\Sigma f_{i}$`

---

## SOLVED EXAMPLES

### Example 1:

Find the median of the following data:

| Marks                 | 20-30 | 30-40 | 40-50 | 50-60 | 60-70 | 70-80 | 80-90 |
| :-------------------- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Number of students** | 5     | 15    | 25    | 20    | 7     | 8     | 10    |
*[CBSE 2013]*

#### Solution:

We prepare the cumulative frequency table, as given below.

| Class     | Frequency ($f_i$) | Cumulative frequency |
| :-------- | :---------------- | :------------------- |
| 20-30     | 5                 | 5                    |
| 30-40     | 15                | 20                   |
| 40-50     | 25                | 45                   |
| 50-60     | 20                | 65                   |
| 60-70     | 7                 | 72                   |
| 70-80     | 8                 | 80                   |
| 80-90     | 10                | 90                   |
|           | $N=\Sigma f_i=90$ |                      |

Now, `$N = 90 \Rightarrow \frac{N}{2} = 45$`.

The cumulative frequency just greater than 45 is 65, and the corresponding class is 50-60. Thus, the **median class** is **50-60**.

-   Lower limit, `$l = 50$`
-   Class width, `$h = 10$`
-   Frequency of median class, `$f = 20$`
-   Cumulative frequency of preceding class, `$cf = 45$`
-   `$\frac{N}{2} = 45$`

$$
\text{Median, } M_{e} = l + \left\{h \times \frac{\left(\frac{N}{2} - cf\right)}{f}\right\} = 50 + \left\{10 \times \frac{(45 - 45)}{20}\right\}
$$

$$
= 50 + 0 = 50
$$

Hence, the **median mark** is **50**.

---

### Example 2:

Find the median wage from the following data:

| Wages (in ₹)        | 800-820 | 820-840 | 840-860 | 860-880 | 880-900 | 900-920 | 920-940 |
| :------------------ | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| **Number of workers** | 7       | 14      | 19      | 25      | 20      | 10      | 5       |
*[CBSE 2013]*

#### Solution:

We prepare the cumulative frequency table, as given below.

| Class     | Frequency ($f_i$)  | Cumulative frequency |
| :-------- | :----------------- | :------------------- |
| 800-820   | 7                  | 7                    |
| 820-840   | 14                 | 21                   |
| 840-860   | 19                 | 40                   |
| 860-880   | 25                 | 65                   |
| 880-900   | 20                 | 85                   |
| 900-920   | 10                 | 95                   |
| 920-940   | 5                  | 100                  |
|           | $N=\Sigma f_i=100$ |                      |

Now, `$N = 100 \Rightarrow \frac{N}{2} = 50$`.

The cumulative frequency just greater than 50 is 65, and the corresponding class is 860-880. Thus, the **median class** is **860-880**.

-   Lower limit, `$l = 860$`
-   Class width, `$h = 20$`
-   Frequency of median class, `$f = 25$`
-   Cumulative frequency of preceding class, `$cf = 40$`
-   `$\frac{N}{2} = 50$`

$$
\text{Median, } M_{e} = l + \left\{h \times \frac{\left(\frac{N}{2} - cf\right)}{f}\right\} = 860 + \left\{20 \times \frac{(50 - 40)}{25}\right\}
$$

$$
= 860 + 20 \times \frac{10}{25} = 860 + 8 = 868
$$

Hence, the **median wage** is **₹868**.

---

## MEDIAN FOR INCLUSIVE SERIES

### Example 3:

Find the median for the following frequency distribution:

| Height (in cm) | 160-162 | 163-165 | 166-168 | 169-171 | 172-174 |
| :------------- | :-----: | :-----: | :-----: | :-----: | :-----: |
| **Frequency** | 15      | 117     | 136     | 118     | 14      |

#### Solution:

The given series is in **inclusive form**. We first convert it to an **exclusive form** by subtracting 0.5 from the lower limits and adding 0.5 to the upper limits.

| Class         | Frequency ($f_i$)  | Cumulative frequency |
| :------------ | :----------------- | :------------------- |
| 159.5-162.5   | 15                 | 15                   |
| 162.5-165.5   | 117                | 132                  |
| 165.5-168.5   | 136                | 268                  |
| 168.5-171.5   | 118                | 386                  |
| 171.5-174.5   | 14                 | 400                  |
|               | $N=\Sigma f_i=400$ |                      |

Now, `$N = 400 \Rightarrow \frac{N}{2} = 200$`.

The cumulative frequency just greater than 200 is 268, and the corresponding class is 165.5-168.5. Thus, the **median class** is **165.5-168.5**.

-   Lower limit, `$l = 165.5$`
-   Class width, `$h = 3$`
-   Frequency of median class, `$f = 136$`
-   Cumulative frequency of preceding class, `$cf = 132$`
-   `$\frac{N}{2} = 200$`

$$
\text{Median, } M_{e} = l + \left\{h \times \frac{\left(\frac{N}{2} - cf\right)}{f}\right\} = 165.5 + \left\{3 \times \frac{(200 - 132)}{136}\right\}
$$

$$
= 165.5 + \left(\frac{3 \times 68}{136}\right) = 165.5 + 1.5 = 167
$$

Hence, the **median height** is **167 cm**.

---

### Example 4:

Given below is the distribution of IQ of 100 students. Find the median IQ.

| IQ          | 75-84 | 85-94 | 95-104 | 105-114 | 115-124 | 125-134 | 135-144 |
| :---------- | :---: | :---: | :----: | :-----: | :-----: | :-----: | :-----: |
| **Frequency** | 8     | 11    | 26     | 31      | 18      | 4       | 2       |

#### Solution:

The given series is in **inclusive form**. We convert it to **exclusive form**.

| Class         | Frequency ($f_i$)  | Cumulative frequency |
| :------------ | :----------------- | :------------------- |
| 74.5-84.5     | 8                  | 8                    |
| 84.5-94.5     | 11                 | 19                   |
| 94.5-104.5    | 26                 | 45                   |
| 104.5-114.5   | 31                 | 76                   |
| 114.5-124.5   | 18                 | 94                   |
| 124.5-134.5   | 4                  | 98                   |
| 134.5-144.5   | 2                  | 100                  |
|               | $N=\Sigma f_i=100$ |                      |

Now, `$N = 100 \Rightarrow \frac{N}{2} = 50$`.

The cumulative frequency just greater than 50 is 76, and the corresponding class is 104.5-114.5. Thus, the **median class** is **104.5-114.5**.

-   Lower limit, `$l = 104.5$`
-   Class width, `$h = 10$`
-   Frequency of median class, `$f = 31$`
-   Cumulative frequency of preceding class, `$cf = 45$`
-   `$\frac{N}{2} = 50$`

$$
\text{Median, } M_{e} = l + \left\{h \times \frac{\left(\frac{N}{2} - cf\right)}{f}\right\} = 104.5 + \left\{10 \times \frac{(50 - 45)}{31}\right\}
$$

$$
= 104.5 + \frac{50}{31} = 104.5 + 1.6 = 106.1
$$

Hence, the **median IQ** is **106.1**.

---

### Example 5:

Calculate the median for the following data:

| Marks obtained | No. of students |
| :------------- | :-------------- |
| Below 10       | 6               |
| Below 20       | 15              |
| Below 30       | 29              |
| Below 40       | 41              |
| Below 50       | 60              |
| Below 60       | 70              |

#### Solution:

This is a cumulative frequency distribution. We need to convert it into a standard frequency distribution table.

| Class interval | Frequency ($f_i$) | Cumulative frequency |
| :------------- | :---------------- | :------------------- |
| 0-10           | 6                 | 6                    |
| 10-20          | $15 - 6 = 9$      | 15                   |
| 20-30          | $29 - 15 = 14$    | 29                   |
| 30-40          | $41 - 29 = 12$    | 41                   |
| 40-50          | $60 - 41 = 19$    | 60                   |
| 50-60          | $70 - 60 = 10$    | 70                   |
|                | $N=\Sigma f_i=70$ |                      |

Now, `$N = 70 \Rightarrow \frac{N}{2} = 35$`.

The cumulative frequency just greater than 35 is 41, and the corresponding class is 30-40. Thus, the **median class** is **30-40**.

-   Lower limit, `$l = 30$`
-   Class width, `$h = 10$`
-   Frequency of median class, `$f = 12$`
-   Cumulative frequency of preceding class, `$cf = 29$`
-   `$\frac{N}{2} = 35$`

$$
\text{Median, } M_{e} = l + \left\{h \times \frac{\left(\frac{N}{2} - cf\right)}{f}\right\} = 30 + \left\{10 \times \frac{(35 - 29)}{12}\right\} = 35
$$

Hence, the required **median** is **35**.

---

### Example 6:

Find the missing frequencies in the following frequency distribution table, if `$N = 100$` and the median is 32.

| Marks                 | 0-10 | 10-20 | 20-30 | 30-40 | 40-50 | 50-60 | **Total** |
| :-------------------- | :--: | :---: | :---: | :---: | :---: | :---: | :-------: |
| **Number of students** | 10   | ?     | 25    | 30    | ?     | 10    | 100       |
*[CBSE 2013]*

#### Solution:

Let `$f_1$` and `$f_2$` be the missing frequencies of class intervals 10-20 and 40-50 respectively.

Given `$N = 100$`, so:
$10 + f_1 + 25 + 30 + f_2 + 10 = 100$
$75 + f_1 + f_2 = 100$
$f_1 + f_2 = 25$  (Equation 1)

The median is 32, which lies in the interval 30-40. So, the **median class** is **30-40**.

-   Lower limit, `$l = 30$`
-   Class width, `$h = 10$`
-   Frequency of median class, `$f = 30$`
-   Total frequency, `$N = 100 \Rightarrow \frac{N}{2} = 50$`
-   Cumulative frequency of preceding class, `$cf = 10 + f_1 + 25 = 35 + f_1$`

Using the median formula:
$$
\text{Median, } M_{e} = l + \left\{h \times \frac{\left(\frac{N}{2} - cf\right)}{f}\right\}
$$

$$
32 = 30 + \left\{10 \times \frac{50 - (35 + f_1)}{30}\right\}
$$

$$
2 = \frac{10 \times (50 - 35 - f_1)}{30}
$$

$$
2 = \frac{15 - f_1}{3}
$$

$$
6 = 15 - f_1
$$

$$
f_1 = 15 - 6 = 9
$$

Substitute `$f_1 = 9$` into Equation 1:
$9 + f_2 = 25$
$f_2 = 25 - 9 = 16$

Hence, the missing frequencies are `$f_1 = 9$` and `$f_2 = 16$`.

---

