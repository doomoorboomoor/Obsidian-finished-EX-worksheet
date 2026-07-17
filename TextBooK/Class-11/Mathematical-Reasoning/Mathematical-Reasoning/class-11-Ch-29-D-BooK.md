## Validating Statements

We shall list some general rules for checking whether a given compound statement is true or not.

**Rule 1: Statements with 'And'**
Let $p$ and $q$ be two statements. Then, in order to prove that '$p$ and $q$' is true, the following steps are taken.
1.  Show that $p$ is true.
2.  Show that $q$ is true.

**Rule 2: Statements with 'Or'**
Let $p$ and $q$ be two statements. Then, in order to prove that '$p$ or $q$' is true, we proceed as under.
-   **Case 1.** Assume that $p$ is false and show that $q$ is true.
-   **Case 2.** Assume that $q$ is false and show that $p$ is true.

**Rule 3: Statements with 'If .... then'**
Let $p$ and $q$ be two statements. Then, in order to prove that '$p \Rightarrow q$' is true, we need to prove any one of the following.
-   **Direct Method:** Assume that $p$ is true and prove that $q$ is true.
-   **Contrapositive Method:** Assume that $q$ is false and prove that $p$ is false.

**Rule 4: Statements with 'If and only if'**
In order to prove that '$p \Rightarrow q$', we need to show that:
-   (i) If $p$ is true, then $q$ is true.
-   (ii) If $q$ is true, then $p$ is true.

---

## Solved Examples

### Example 1:

Prove that the following statement is true:
If $x, y \in Z$ such that $x$ and $y$ are odd, then $xy$ is odd.

#### Solution:

Let $p: x, y \in Z$ such that $x$ and $y$ are odd.
And $q: xy$ is odd.
Then, we have to prove that $xy$ is odd.

**Direct Method**

We assume that $p$ is true and show that $q$ is true.
$p$ is true means $x$ and $y$ are odd integers. Then,

$$
\begin{aligned}
x & =(2 m+1) \text{ for some integer } m \\
\text{and } y & =(2 n+1) \text{ for some integer } n \\
\therefore \quad xy & =(2 m+1)(2 n+1) \\
& =(4 m n+2 m+2 n+1) \\
& =2(2 m n+m+n)+1, \text{ which is clearly odd. }
\end{aligned}
$$

Thus, $p \Rightarrow q$.
Hence, the given statement is true.

**Contrapositive Method**

We will show that $\sim q \Rightarrow \sim p$.
Here $\sim q$: It is false that both $x$ and $y$ are odd.
This means at least one of $x$ and $y$ is even.
Let $x$ be even. Then, $x=2n$ for some integer $n$.
$\therefore \quad xy=2ny$ for some integer $n$.
This shows that $xy$ is even.
Thus, $\sim p$ is true [$\because \sim p: xy$ is even].
$\therefore \quad \sim q \Rightarrow \sim p$.
So, the given statement is true.

---

### Example 2:

Prove that the necessary and sufficient condition for an integer $n$ to be odd is that $n^2$ is odd.

#### Solution:

Let $p$: The integer $n$ is odd.
And $q: n^2$ is odd.
First we prove that $p \Rightarrow q$.
Let $n$ be odd. Then, $n=(2k+1)$ for some integer $k$.

$$
\text{Then, } n^2 = (2k+1)^2 = (4k^2+4k+1) = 2(2k^2+2k)+1
$$

Thus, $n^2$ is 1 more than an even number and therefore, it is odd.
Thus, $p \Rightarrow q$.
Now, in order to prove that $q \Rightarrow p$, it is sufficient to show that $\sim p \Rightarrow \sim q$ [Contrapositive method].
Clearly, $\sim p$: The integer $n$ is even.
Let $n=2k$ for some integer $k$.
Then, $n^2 = 4k^2$, which is even.
$\therefore n$ is even $\Rightarrow n^2$ is even.
Consequently, $\sim p \Rightarrow \sim q$ and therefore, $q \Rightarrow p$.
Hence, $p \Leftrightarrow q$, i.e., the integer $n$ is odd if and only if $n^2$ is odd.

---

## Proving Results by Contradiction

In order to check whether a given statement $p$ is true, we assume that $p$ is false, i.e., $\sim p$ is true.

From this we arrive at a result which contradicts our assumption. Hence, we conclude that $p$ is true.

---

### Example 3:

By using the method of contradiction verify that $p: \sqrt{5}$ is irrational.

#### Solution:

If possible, let $\sqrt{5}$ be rational and let its simplest form be $\frac{a}{b}$.
Then, $a$ and $b$ are integers having no common factor other than 1 and $b \neq 0$.
Now, $\sqrt{5} = \frac{a}{b} \Rightarrow 5 = \frac{a^2}{b^2}$ [on squaring both sides]

$$
\begin{align*}
& \Rightarrow 5 b^2=a^2  \tag{i}\\
& \Rightarrow 5 \text{ divides } a^2 \quad [\because 5 \text{ divides } 5b^2] \\
& \Rightarrow 5 \text{ divides } a \quad [\because 5 \text{ is prime and divides } a^2 \Rightarrow 5 \text{ divides } a].
\end{align*}
$$

Let $a=5c$ for some integer $c$.
Putting $a=5c$ in (i), we get:

$$
\begin{aligned}
5b^2=25c^2 & \Rightarrow b^2=5c^2 \\
& \Rightarrow 5 \text{ divides } b^2 \quad [\because 5 \text{ divides } 5c^2] \\
& \Rightarrow 5 \text{ divides } b \quad [\because 5 \text{ is prime and divides } b^2 \Rightarrow 5 \text{ divides } b]
\end{aligned}
$$

Thus, 5 is a common factor of $a$ and $b$.
But, this contradicts the fact that $a$ and $b$ have no common factor other than 1.
Hence, $\sqrt{5}$ is irrational.

---

### Example 4:

By using the method of contradiction, prove that the sum of an irrational number and a rational number is irrational.

#### Solution:

Let $\sqrt{a}$ be irrational and $b$ be rational.

Then, we have to prove that $(\sqrt{a}+b)$ is irrational.
If possible, let $(\sqrt{a}+b)$ be rational. Then,
$(\sqrt{a}+b)$ is rational, $b$ is rational.
$\Rightarrow \{(\sqrt{a}+b)-b\}$ is rational [$\because$ difference of rationals is rational]
$\Rightarrow \sqrt{a}$ is rational.
This contradicts the fact that $\sqrt{a}$ is irrational.
Since the contradiction arises by assuming that $(\sqrt{a}+b)$ is rational, hence $(\sqrt{a}+b)$ is irrational.

---

### Example 5:

Using contradiction method, check the validity of the following statement:
If $n$ is a real number with $n>3$, then $n^2>9$.

#### Solution:

Let $n$ be a real number such that $n>3$ and if possible, let $n^2$ be not greater than 9.
Then, $n^2 \leq 9$.
Let $n^2=(9-a)$, where $a$ is a real number such that $a \geq 0$.
Then, $n = \sqrt{n^2} = \sqrt{9-a} \leq 3 \quad [\because (9-a) \leq 9]$.
But, this is a contradiction since $n>3$.
Since the contradiction arises by assuming that $n^2$ is not greater than 9, therefore, $n^2>9$.
Hence, the given statement is valid.

---

### Example 6:

Consider the statement:
$p$: If $x$ a real number such that $x^3+4x=0$, then $x=0$.
Prove that $p$ is a true statement, using:
(i) direct method
(ii) method of contradiction
(iii) method of contrapositive

#### Solution:

**(i) Direct Method:**
Let $x^3+4x=0$, where $x \in R$. Then,
$$
x^3+4x=0 \Rightarrow x(x^2+4)=0
$$
$$
\Rightarrow x=0 \quad [\because x^2+4 \neq 0 \text{ for } x \in R]
$$
Hence, $p$ is a true statement.

**(ii) Method of contradiction:**
If possible, let $x^3+4x=0$ and $x \neq 0$. Then,
$$
x(x^2+4)=0 \text{ and } x \neq 0 \Rightarrow x^2+4=0.
$$
But, this is a contradiction, since $x^2+4 \neq 0$ for $x \in R$.
Since, the contradiction arises by assuming that $x^2+4=0$ and $x \neq 0$, so $x=0$.
Hence, $x^3+4x=0 \Rightarrow x=0$ is a true statement.

**(iii) Method of contrapositive:**
We have to prove that $x^3+4x=0 \Rightarrow x=0$.
Let $p: x^3+4x=0$ and $q: x=0$.
We shall prove that $\sim q \Rightarrow \sim p$.
Let $x \neq 0$. Then, $x^3+4x = x(x^2+4) \neq 0$ [$\because x \neq 0$ and $x^2+4 \neq 0$].
Thus, $\sim q \Rightarrow \sim p$ and therefore, $p \Rightarrow q$.

---

