## Logical Connectives

A **simple statement** is a statement which does not contain any other statement as its component part.

**EXAMPLES** Each of the following is a simple statement.
(i) Chennai is the capital of Tamil Nadu.
(ii) The set of real numbers is an infinite set.
(iii) The sum of 6 and 3 is greater than 10.

---

### Compound Statements

A **compound statement** is a combination of two or more simple sentences. The method of combining two or more simple sentences is known as compounding.

---

### Logical Connectives

The words or phrases which connect two or more simple sentences are called **logical connectives** or simply **connectives**.

These connectives are:
- and
- or
- If ... then ....
- if and only if

---

### Connectives and Their Symbols

| Connective | Symbol | Nature of compound statement |
| :--- | :---: | :--- |
| (i) and | `$\wedge$` | Conjunction |
| (ii) or | `$\vee$` | Disjunction |
| (iii) If ... then ... | `$\Rightarrow$` | Implication (or conditional) |
| (iv) if and only if | `$\Leftrightarrow$` | Biconditional (or equivalence) |

**EXAMPLES** Each of the following is a compound statement.
(i) 2 is a rational number and `$\sqrt{2}$` is an irrational number.
(ii) The sum of 3 and 5 is 7 or 8.
(iii) If it rains then the school may be closed.
(iv) A triangle is equiangular if and only if it is equilateral.

The connectives in (i), (ii), (iii) and (iv) are respectively **and**, **or**, **If ... then**, **if and only if**.

---

## Compounding of Sentences

### 1. Conjunction

Two simple sentences connected by the word '**and**' are said to form a **conjunction**.

We use the symbol '`$\wedge$`' to denote '**and**'. The truth table for `$p \wedge q$` is based on the fact that '`$p \wedge q$`' is true **only** when each one of the statements `$p$` and `$q$` is true.

**Truth table for `$p \wedge q$**`
| `$p$` | `$q$` | `$p \wedge q$` |
| :---: | :---: | :---: |
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |

**Remember that:**
(i) The compound statement with '**and**' is true if **all** its component statements are true.
(ii) The compound statement with '**and**' is false if **any** of its component statements is false or **all** of its component statements are false.

### Example 1

Split each of the following compound statements into simple sentences and determine whether it is true or false:
(i) The grass is green and the sky is blue.
(ii) Agra is in Uttar Pradesh and Shimla is in Punjab.
(iii) All rational numbers are real and all real numbers are not complex numbers.
(iv) `$x=5$` and `$x=2$` are the roots of the equation `$3x^2 - x - 10 = 0$`.

#### Solution

(i) Let `$p$`: The grass is green. And `$q$`: The sky is blue.
Clearly, each one of `$p$` and `$q$` is a true statement and therefore, (`$p$` and `$q$`) is true. Hence, the given statement is **true**.

(ii) Let `$p$`: Agra is in Uttar Pradesh. And `$q$`: Shimla is in Punjab.
Clearly, `$p$` is true and `$q$` is false. Therefore, (`$p$` and `$q$`) is false. Hence, the given statement is **false**.

(iii) Let `$p$`: All rational numbers are real. And, `$q$`: All real numbers are not complex numbers.
Clearly, `$p$` is true and `$q$` is false. `$\therefore (p$ and $q)$` is false. Hence, the given statement is **false**.

(iv) Let `$p: x=5$` is a root of the equation `$3x^2 - x - 10 = 0$`. And `$q: x=2$` is a root of the equation `$3x^2 - x - 10 = 0$`.
Clearly, `$3 \times 5^2 - 5 - 10 = 60 \neq 0$`. So, `$x=5$` is not a root of the equation `$3x^2 - x - 10 = 0$`.
And, `$3 \times 2^2 - 2 - 10 = 0$`. So, `$x=2$` is a root of `$3x^2 - x - 10 = 0$`.
`$\therefore p$` is false and `$q$` is true. Consequently, (`$p$` and `$q$`) is false. Hence, the given statement is **false**.

---

### 2. Disjunction

Two simple sentences connected by the word '**or**' are said to form a **disjunction**.

We use the symbol '`$\vee$`' to denote '**or**'. Clearly, (`$p$` or `$q$`) is true when at least one of them is true.

**Truth Table for `$(p \vee q)$`**
Clearly, `$(p \vee q)$` is true only when (`$p$` is true or `$q$` is true) or both are true.

**Truth table for `$(p \vee q)$`**
| `$p$` | `$q$` | `$p \vee q$` |
| :---: | :---: | :---: |
| T | T | T |
| T | F | T |
| F | T | T |
| F | F | F |

**Remember that:**
(i) A compound statement with '**or**' is true when **at least one** of them is true.
(ii) A compound statement with '**or**' is false when **each one** of them is false.

In (`$p$` or `$q$`) we say that **exclusive 'or'** is used when both `$p$` and `$q$` are not true simultaneously. Otherwise, **inclusive 'or'** is used.

### Example 2

For each of the following statements, determine whether an inclusive 'or' or exclusive 'or' is used. Give reasons for your answer.
(i) For identification you need a passport or an Adhar Card.
(ii) The school is closed if it is a holiday or a Sunday.
(iii) `$\sqrt{3}$` is a rational number or an irrational number.
(iv) Two lines intersect at a point or are parallel.
(v) Students can take Sanskrit or French as their third language.

#### Solution

(i) Here '**or**' is **inclusive** since a person can have both a passport and an Adhar Card for identification.
(ii) Here '**or**' is **inclusive** since the school is closed on holiday as well as on Sunday.
(iii) Let `$p: \sqrt{3}$` is a rational number. And, `$q: \sqrt{3}$` is an irrational number.
Clearly, `$p$` is false and `$q$` is true. `$\therefore$` (`$p$` or `$q$`) is true and '**or**' is **exclusive**.
(iv) Here '**or**' is **exclusive** because it is not possible for two lines to intersect and be parallel together.
(v) Here '**or**' is **exclusive** because a student cannot take both Sanskrit and French.

---

## Open Sentences and Their Truth Sets

Let `$p(x)$` be a declarative sentence involving a variable `$x$` and let `$A$` be a given set such that for `$a \in A$`, `$p(a)$` is true or false.

Then, `$p(x)$` is called an **open sentence** defined on `$A$`.
The subset of `$A$` consisting of all those values of `$x$` which convert `$p(x)$` into a true statement is called a **Truth Set** of the open sentence `$p(x)$`.

### Example 3

Write down the truth set of each of the following open sentences:
(i) `$p(x): x+5 < 9, x \in N$`.
(ii) `$p(x): x+3 < 3, x \in N$`.
(iii) `$p(x): x+5 > 7, x \in R$`.
(iv) `$p(x): 2x^2 + 5x - 3 = 0, x \in I$`.

#### Solution

We have:
(i)
$$
\begin{aligned}
\text{Truth Set} &= \{x \in N: x+5 < 9\} \\
&= \{x \in N: x < 4\} = \{1, 2, 3\}.
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\text{Truth Set} &= \{x \in N: x+3 < 3\} \\
&= \{x \in N: x < 0\} = \phi.
\end{aligned}
$$

(iii)
$$
\begin{aligned}
\text{Truth Set} &= \{x \in R: x+5 > 7\} \\
&= \{x \in R: x > 2\} = ]2, \infty[.
\end{aligned}
$$

(iv)
$$
2x^2 + 5x - 3 = 0 \Rightarrow 2x^2 + 6x - x - 3 = 0 \Rightarrow 2x(x+3) - (x+3) = 0
$$
$$
\Rightarrow (x+3)(2x-1) = 0 \Rightarrow x = -3 \text{ or } x = \frac{1}{2}
$$
$$
\therefore \text{truth set} = \{x \in I: 2x^2 + 5x - 3 = 0\} = \{-3\} \quad [\because \frac{1}{2} \notin I].
$$

---

## Quantifiers and Quantified Statements

### Two Important Symbols

(i) The symbol '`$\forall$`' stands for '**for all values of**'. This is known as the **universal quantifier**.
(ii) The symbol '`$\exists$`' stands for '**there exists**'. This is known as the **existential quantifier**.

### Quantified Statement

An open sentence with a quantifier becomes a statement, called a **quantified statement**.

### Example 4

Use quantifiers to convert each of the following open sentences defined on `$N$`, into a true statement:
(i) `$x+5 = 8$`
(ii) `$x^2 > 0$`
(iii) `$x+2 < 4$`

#### Solution

(i) `$\exists x \in N$` such that `$x+5=8$` is a true statement, since `$x=3 \in N$` satisfies `$x+5=8$`.
(ii) `$x^2 > 0 \forall x \in N$` is a true statement, since the square of every natural number is positive.
(iii) `$\exists x \in N$` such that `$x+2 < 4$` is a true statement, since `$x=1 \in N$` satisfies `$x+2 < 4$`.

---

### Example 5

Let `$A = \{1, 2, 3, 4\}$`. Examine whether the statements given below are true or false.
(i) `$\exists x \in A$` such that `$x+3=8$`.
(ii) `$\forall x \in A, x+2 < 7$`.
(iii) `$\exists x \in A$` such that `$x+1 < 3$`.
(iv) `$\forall x \in A, x+3 \ge 5$`.

#### Solution

(i) Clearly, no number in `$A$` satisfies `$x+3=8$`. `$\therefore$` the given statement is **false**.
(ii) Every number in `$A$` satisfies `$x+2 < 7$`. So, the given statement is **true**.
(iii) Clearly, `$x=1 \in A$` satisfies `$x+1 < 3$`. `$\therefore$` the given statement is **true**.
(iv) Since `$x=1 \in A$` does not satisfy `$x+3 \ge 5$`, the given statement is **false**.

---

