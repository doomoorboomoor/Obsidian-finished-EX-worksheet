## Real Numbers

In class IX we studied about real numbers, especially about irrational numbers. In this chapter, we shall continue our discussion on real numbers. We begin with two important results, namely **Euclid's division lemma** and the **fundamental theorem of arithmetic**.

**Lemma:** A lemma is a proven statement used for proving another statement.

---

## Euclid's Division Lemma

For any two given positive integers $a$ and $b$, there exist unique whole numbers $q$ and $r$ such that

$$
a = bq + r, \text{ where } 0 \le r < b
$$

[CBSE 2009C]

Here, we call **$a$** as **dividend**, **$b$** as **divisor**, **$q$** as **quotient** and **$r$** as **remainder**.

$$
\text{Dividend} = (\text{divisor} \times \text{quotient}) + \text{remainder}
$$

For example, suppose we divide $117$ by $14$. Then, we get $8$ as quotient and $5$ as remainder.

Here **dividend** $=117$, **divisor** $=14$, **quotient** $=8$ and **remainder** $=5$.

Clearly, $117 = (14 \times 8) + 5$.

---

### Example 1:
A number when divided by $73$ gives $34$ as quotient and $23$ as remainder. Find the number.

#### Solution:

Here **divisor** $=73$, **quotient** $=34$ and **remainder** $=23$.

By Euclid's division lemma, we have

$$
\begin{aligned}
\text{dividend} &= (\text{divisor} \times \text{quotient}) + \text{remainder} \\
&= (73 \times 34) + 23 \\
&= (2482 + 23) = 2505
\end{aligned}
$$

Hence, the required number is **2505**.

---

**Algorithm:** An algorithm is a series of well-defined steps which gives a method for solving a certain type of problem.

## Euclid's Division Algorithm

It is a technique to compute the **HCF** of two given positive integers, say $a$ and $b$ with $a>b$, in the following steps.

1.  On dividing $a$ by $b$, we get the quotient $q$ and remainder $r$ such that $a=bq+r$, where $0 \leq r<b$.
2.  If $r=0$ then $\operatorname{HCF}(a, b)=b$. If $r \neq 0$ then apply the division lemma to $b$ and $r$.
3.  Continue the process till the remainder is $0$. The last divisor will be the required **HCF**.

---

### Example 2:
Use Euclid's algorithm to find the HCF of $272$ and $1032$.

#### Solution:

We find $\operatorname{HCF}(272, 1032)$ using the following steps.

**Step 1.** Since $1032 > 272$, we divide $1032$ by $272$ to get $3$ as quotient and $216$ as remainder.

```text
      3
   _______
272| 1032
     816
    ----
     216