## Fundamental Theorem of Arithmetic

**Every composite number can be uniquely expressed as a product of primes, except for the order in which these prime factors occurs.**

**Examples:**
- (i) $12 = 2 \times 2 \times 3$
- (ii) $69 = 3 \times 23$
- (iii) $105 = 3 \times 5 \times 7$
- (iv) $234 = 2 \times 3 \times 3 \times 13$
- (v) $462 = 2 \times 3 \times 7 \times 11$
- (vi) $651 = 3 \times 7 \times 31$

The above factorisation can easily be verified by actual division.

---
## Solved Examples

### Example 1

Show that each of the following is a composite number:
(i) $5 \times 11 \times 13 + 13$
(ii) $6 \times 5 \times 4 \times 3 \times 2 \times 1 + 5$

#### Solution

We have:

(i) $5 \times 11 \times 13 + 13 = 13 \times (5 \times 11 + 1) = (13 \times 56)$.

Clearly, it shows that the given number has more than two factors. Hence, it is a composite number.

(ii) $6 \times 5 \times 4 \times 3 \times 2 \times 1 + 5 = 5 \times (6 \times 4 \times 3 \times 2 \times 1 + 1)$
$$
= (5 \times 145)
$$
Clearly, it shows that the given number has more than two factors. Hence, it is a composite number.

---
### Example 2

Show that any number of the form $4^n, n \in N$ can never end with the digit 0.

#### Solution

If $4^n$ ends with 0 then it must have 5 as a factor.

But, $4^n = (2^2)^n = 2^{2n}$ shows that 2 is the only prime factor of $4^n$.

Also, we know from the **Fundamental Theorem of Arithmetic** that the prime factorisation of each number is unique.

So, 5 is not a factor of $4^n$.

Hence, $4^n$ can never end with the digit 0.

---
### Example 3

Show that any number of the form $6^n$, where $n \in N$ can never end with the digit 0.

#### Solution

If $6^n$ ends with 0 then it must have 5 as a factor.

But, $6^n = (2 \times 3)^n = (2^n \times 3^n)$ shows that 2 and 3 are the only prime factors of $6^n$.

Also, we know from the **Fundamental Theorem of Arithmetic** that the prime factorisation of each number is unique.

So, 5 is not a factor of $6^n$.

Hence, $6^n$ can never end with the digit 0.

---
### Example 4

Find the **HCF** and **LCM** of 126 and 156 using the prime factorisation method.

#### Solution

We have:
$$
126 = (2 \times 3 \times 3 \times 7) = (2 \times 3^2 \times 7)
$$
and
$$
156 = (2 \times 2 \times 3 \times 13) = (2^2 \times 3 \times 13)
$$
Therefore, **HCF**(126, 156) = product of common terms with lowest power
$$
= (2^1 \times 3^1) = (2 \times 3) = 6
$$
and **LCM**(126, 156) = product of prime factors with highest power
$$
= (2^2 \times 3^2 \times 7 \times 13) = (4 \times 9 \times 7 \times 13) = 3276
$$
So, **HCF** = 6 and **LCM** = 3276.

---
### Example 5

Find the **HCF** and **LCM** of 612 and 1314 using the prime factorisation method.

#### Solution

We have:
$$
612 = (2 \times 2 \times 3 \times 3 \times 17) = (2^2 \times 3^2 \times 17)
$$
and
$$
1314 = (2 \times 3 \times 3 \times 73) = (2 \times 3^2 \times 73)
$$
Therefore, **HCF**(612, 1314) = product of common terms with lowest power
$$
= (2 \times 3^2) = (2 \times 9) = 18
$$
and **LCM**(612, 1314) = product of prime factors with highest power
$$
= (2^2 \times 3^2 \times 17 \times 73) = (4 \times 9 \times 17 \times 73) = 44676
$$
Hence, **HCF** = 18 and **LCM** = 44676.

---
## An Important Property

**Product of two given numbers = product of their HCF and LCM.**

Thus,
$$
(a \times b) = \text{HCF}(a, b) \times \text{LCM}(a, b)
$$
**Caution:** The above result is true for two numbers only.

---
### Example 6

The **HCF** of two numbers is 23 and their **LCM** is 1449. If one of the numbers is 161, find the other.

#### Solution

For two numbers $a$ and $b$, we know that:
$$
(a \times b) = \{\text{HCF}(a, b)\} \times \{\text{LCM}(a, b)\}
$$
Here $a = 161$, **HCF** = 23 and **LCM** = 1449.
And, we have to find $b$.
$$
(161 \times b) = (23 \times 1449) \Rightarrow b = \frac{(23 \times 1449)}{161} = 207
$$
Hence, the other number is 207.

---
### Example 7

Given that **HCF**(252, 594) = 18, find **LCM**(252, 594).

#### Solution

We have:
$$
\text{LCM} = \frac{\text{product of two given numbers}}{\text{their HCF}} = \frac{(252 \times 594)}{18} = 8316
$$
Hence, **LCM**(252, 594) = 8316.

---
### Example 8

Find the simplest form of $\frac{148}{185}$.

#### Solution

We find **HCF**(148, 185), which is 37.

So, we divide the numerator and denominator of the given fraction by 37.
$$
\frac{148}{185} = \frac{148 \div 37}{185 \div 37} = \frac{4}{5}
$$
Hence, the simplest form of the given fraction is $\frac{4}{5}$.

---
### Example 9

Find the **HCF** and **LCM** of 108, 120 and 252 using the prime factorisation method.

#### Solution

By prime factorisation, we get:
$108 = (2^2 \times 3^3)$
$120 = (2^3 \times 3 \times 5)$
$252 = (2^2 \times 3^2 \times 7)$

**HCF**(108, 120, 252) = product of common terms with lowest power
$$
= (2^2 \times 3) = (4 \times 3) = 12
$$
**LCM**(108, 120, 252) = product of prime factors with highest power
$$
= (2^3 \times 3^3 \times 5 \times 7) = 7560
$$
Therefore, **HCF** = 12 and **LCM** = 7560.

---
### Example 10

Find the largest number which divides 245 and 1037, leaving remainder 5 in each case.

#### Solution

Clearly, the required number divides $(245 - 5) = 240$ and $(1037 - 5) = 1032$ exactly.

So, the required number is **HCF**(240, 1032).

Now, $240 = (2^4 \times 3 \times 5)$ and $1032 = (2^3 \times 3 \times 43)$.
$$
\text{HCF}(240, 1032) = (2^3 \times 3) = 24
$$
Hence, the required number is 24.

---
### Example 11

Find the largest number which divides 129 and 545, leaving remainders 3 and 5 respectively.

#### Solution

Clearly, the required number divides $(129 - 3) = 126$ and $(545 - 5) = 540$ exactly.

Therefore, required number = **HCF**(126, 540).

Now, $126 = (2 \times 3 \times 3 \times 7) = (2 \times 3^2 \times 7)$
and $540 = (2 \times 2 \times 3 \times 3 \times 3 \times 5) = (2^2 \times 3^3 \times 5)$.

**HCF**(126, 540) = product of common terms with lowest power
$$
= (2 \times 3^2) = (2 \times 9) = 18
$$
Hence, the required number is 18.

---
### Example 12

Find the largest number that will divide 398, 436 and 542, leaving remainders 7, 11 and 15 respectively.

#### Solution

Clearly, the required number divides $(398 - 7) = 391$, $(436 - 11) = 425$ and $(542 - 15) = 527$ exactly.

Therefore, required number = **HCF**(391, 425, 527).

Now, $391 = (17 \times 23)$, $425 = (5^2 \times 17)$, $527 = (17 \times 31)$.
$$
\text{HCF}(391, 425, 527) = 17
$$
Hence, the required number is 17.

---
### Example 13

Two tanks contain 504 and 735 litres of milk respectively. Find the maximum capacity of a container which can measure the milk of either tank an exact number of times.

#### Solution

Resolving 504 and 735 into prime factors, we get:
$504 = (2^3 \times 3^2 \times 7)$
and $735 = (5 \times 3 \times 7^2)$.
$$
\text{HCF}(504, 735) = (3 \times 7) = 21
$$
Therefore, the capacity of the required container = 21 litres.

---
### Example 14

An army contingent of 612 members is to march behind an army band of 48 members in a parade. The two groups are to march in the same number of columns. What is the maximum number of columns in which they can march?

#### Solution

Clearly, the maximum number of columns = **HCF**(612, 48).

Now, $612 = (2^2 \times 3^2 \times 17)$ and $48 = (2^4 \times 3)$.
$$
\text{HCF}(612, 48) = (2^2 \times 3) = (4 \times 3) = 12
$$
Therefore, the required number of columns = 12.

---
### Example 15

A sweetseller has 420 kaju burfis and 150 badam burfis. He wants to stack them in such a way that each stack has the same number, and they take up the least area of the tray. How many of these can be placed in each stack? How many stacks are formed?

#### Solution

Maximum number of burfis in each stack = **HCF**(420, 150).

Now, $420 = (2^2 \times 3 \times 5 \times 7)$ and $150 = (2 \times 3 \times 5^2)$.
$$
\text{HCF}(420, 150) = (2 \times 3 \times 5) = 30
$$
Therefore, the maximum number of burfis in each stack = 30.

Number of stacks = $(\frac{420}{30} + \frac{150}{30}) = (14 + 5) = 19$.

---
### Example 16

Ravi and Sikha drive around a circular sports field. Ravi takes 16 minutes to take one round, while Sikha completes the round in 20 minutes. If both start at the same point, at the same time and go in the same direction, after how much time will they meet at the starting point?

#### Solution

Required number of minutes = **LCM**(16, 20).

Now, $16 = 2^4$ and $20 = (2^2 \times 5)$.
$$
\text{LCM}(16, 20) = (2^4 \times 5) = (16 \times 5) = 80
$$
Hence, both will meet at the starting point after 80 minutes.

---
### Example 17

In a school there are two sections, namely A and B, of class X. There are 30 students in section A and 28 students in section B. Find the minimum number of books required for their class library so that they can be distributed equally among students of section A or section B.

#### Solution

Clearly, the required number of books are to be distributed equally among the students of section A or B.
So, the number of these books must be a multiple of 30 as well as that of 28.

Consequently, the required number is **LCM**(30, 28).

Now, $30 = 2 \times 3 \times 5$ and $28 = 2^2 \times 7$.

**LCM**(30, 28) = product of prime factors with highest power
$$
= (2^2 \times 3 \times 5 \times 7) = (4 \times 3 \times 5 \times 7) = 420
$$
Hence, the required number of books = 420.

---
 = $(\frac{30}{2} + 1)$ times = 16 times.