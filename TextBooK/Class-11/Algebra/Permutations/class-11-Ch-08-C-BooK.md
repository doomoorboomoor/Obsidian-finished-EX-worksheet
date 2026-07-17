## Permutations

The different **arrangements** which can be made out of a given number of things by taking some or all at a time, are called **permutations**.

*Remark: In permutations, the order of arrangement of the objects is taken into consideration. When the order is changed, a different permutation is obtained.*

---

## Illustrative Examples

### Example 1

All permutations of the letters $A, B, C$ taking two at a time are:
$AB, BA, AC, CA, BC, CB$.
Thus, we obtain 6 different permutations.

---

### Example 2

All permutations of the letters $A, B, C$ taking all at a time are:
$ABC, ACB, BAC, BCA, CAB, CBA$.
Thus, the 3 letters $A, B, C$ taking all at a time give 6 permutations.

---

### Example 3

All permutations of the letters $A, B, C, D$ taking 3 at a time are:
$$
\begin{aligned}
& ABC, ACB, BAC, BCA, CAB, CBA; \\
& ABD, ADB, BAD, BDA, CAD, CDA; \\
& BCD, BDC, CBD, CDB, DBC, DCB; \\
& ACD, ADC, CAD, CDA, DAC, DCA.
\end{aligned}
$$
Thus, the 4 letters $A, B, C, D$ taking 3 at a time give 24 permutations.

---

## Permutations When All the Objects Are Distinct

**Theorem 1:** The number of permutations of $n$ different objects taken $r$ at a time, where $0 < r \leq n$ and the objects do not repeat, is given by
$$
P(n, r) \text{ or } {}^{n} P_{r} = n(n-1)(n-2) \ldots (n-r+1).
$$

**Proof:** The number of permutations of $n$ different objects taken $r$ at a time is the same as the number of ways of filling in $r$ vacant places by the $n$ objects.

The first place can be filled up by anyone of these $n$ objects. Thus, there are $n$ ways of filling up the first place.

Now, we are left with $(n-1)$ objects. The second place can be filled up by anyone of these $(n-1)$ objects. Thus, there are $(n-1)$ ways of filling up the second place.

Now, we are left with $(n-2)$ objects. The third place can be filled up by any of these $(n-2)$ objects. Thus, there are $(n-2)$ ways of filling up the third place.

Similarly, the 4th place can be filled in $(n-3)$ ways, the 5th place can be filled in $(n-4)$ ways and so on, and the $r$-th place can be filled in $\{n-(r-1)\} = (n-r+1)$ ways.

Thus, the total number of ways of filling in $r$ vacant places by $n$ different objects in succession is $\{n(n-1)(n-2) \ldots (n-r+1)\}$.

Hence, ${}^{n} P_{r} = n(n-1)(n-2) \ldots (n-r+1)$.

*Remark: We have*
$$
\begin{aligned}
{ }^{n} P_{r} & =n(n-1)(n-2) \ldots(n-r+1) \\
& =\frac{n(n-1)(n-2) \ldots(n-r+1)(n-r)(n-r-1) \ldots 3 \cdot 2 \cdot 1}{(n-r)(n-r-1) \ldots 3 \cdot 2 \cdot 1} \\
& =\frac{n!}{(n-r)!}, \text{ where } 0<r \leq n.
\end{aligned}
$$

**Theorem 2:** The number of all permutations of $n$ different objects taken all at a time is given by ${}^{n} P_{n} = n!$.

**Proof:** The number of all permutations of $n$ different objects taken all at a time is the same as the number of ways of filling $n$ vacant places by $n$ different objects. Proceeding as in Theorem 1, we have
$$
{}^{n} P_{n} = n(n-1)(n-2)(n-3) \ldots \times 3 \times 2 \times 1 = n!.
$$

**Theorem 3:** Prove that $0! = 1$.

**Proof:** We have
$$
\begin{array}{rlr}
{ }^{n} P_{r} & =\frac{n!}{(n-r)!}  \tag{i}\\
\Rightarrow & { }^{n} P_{n} & =\frac{n!}{0!} \quad \ldots [\text{putting } r=n \text{ in (i)}] \\
\Rightarrow & n! & =\frac{n!}{0!} \quad [{}^{n} P_{n}=n!] \\
\Rightarrow & 0! & =\frac{n!}{n!}=1.
\end{array}
$$
Hence, $0! = 1$.

*Remark: Thus, we have ${}^{n} P_{r} = \frac{n!}{(n-r)!}$, where $0 \leq r \leq n$.*

---

## Solved Examples

### Example 1

Evaluate:
(i) ${}^{12} P_{4}$
(ii) ${}^{75} P_{2}$
(iii) ${}^{8} P_{8}$

#### Solution

We have
(i) ${}^{12} P_{4} = \frac{12!}{(12-4)!} = \frac{12!}{8!} = \frac{12 \times 11 \times 10 \times 9 \times (8!)}{8!} = 11880$.
(ii) ${}^{75} P_{2} = \frac{75!}{(75-2)!} = \frac{75!}{73!} = \frac{75 \times 74 \times (73!)}{73!} = (75 \times 74) = 5550$.
(iii) ${}^{8} P_{8} = 8! = (8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1) = 40320$.

---

### Example 2

Find the value of $n$ such that
(i) ${}^{n} P_{5} = 42 \times {}^{n} P_{3}, n > 4$
(ii) $\frac{{}^{n} P_{4}}{{}^{n-1} P_{4}} = \frac{5}{3}, n > 4$.

#### Solution

We know that ${}^{n} P_{r} = n(n-1)(n-2) \ldots (n-r+1)$.
(i) We have
$$
\begin{aligned}
\frac{{}^{n} P_{5}}{{}^{n} P_{3}}=42 & \Rightarrow \frac{n(n-1)(n-2)(n-3)(n-4)}{n(n-1)(n-2)}=42 \\
& \Rightarrow (n-3)(n-4)=42 \quad [\text{as } n(n-1)(n-2) \neq 0] \\
& \Rightarrow n^{2}-7n-30=0 \Rightarrow (n-10)(n+3)=0 \\
& \Rightarrow n=10 \quad [\because n \neq -3, \text{ as } n \text{ cannot be negative}].
\end{aligned}
$$
Hence, $n=10$.

(ii)
$$
\begin{aligned}
\frac{{}^{n} P_{4}}{{}^{n-1} P_{4}} = \frac{5}{3} & \Rightarrow \frac{n(n-1)(n-2)(n-3)}{(n-1)(n-2)(n-3)(n-4)} = \frac{5}{3} \\
& \Rightarrow 3n = 5(n-4) \quad [\text{as } (n-1)(n-2)(n-3)(n-4) \neq 0] \\
& \Rightarrow 2n = 20 \Rightarrow n=10.
\end{aligned}
$$
Hence, $n=10$.

---

### Example 3

If $5 \times {}^{4} P_{r} = 6 \times {}^{5} P_{r-1}$, find $r$.

#### Solution

We have
$$
\begin{aligned}
& 5 \times {}^{4} P_{r} = 6 \times {}^{5} P_{r-1} \\
\Rightarrow & 5 \times \frac{4!}{(4-r)!} = 6 \times \frac{5!}{\{5-(r-1)\}!} \\
\Rightarrow & \frac{5!}{(4-r)!} = \frac{6 \times (5!)}{(6-r)!} \\
\Rightarrow & \frac{1}{(4-r)!} = \frac{6}{(6-r)!} \Rightarrow \frac{1}{(4-r)!} = \frac{6}{(6-r)(5-r)\{(4-r)!\}} \\
\Rightarrow & \frac{6}{(6-r)(5-r)} = 1 \Rightarrow (6-r)(5-r)-6 = 0 \\
\Rightarrow & r^{2}-11r+24 = 0 \Rightarrow (r-3)(r-8) = 0 \\
\Rightarrow & r=3 \quad [\because r \neq 8, \text{ as } {}^{4} P_{8} \text{ is not defined}].
\end{aligned}
$$
Hence, $r=3$.

---

### Example 4

If ${}^{n} P_{4} = 2 \times {}^{5} P_{3}$, find $n$.

#### Solution

We have
$$
\begin{array}{ll} 
& {}^{n} P_{4}=2 \times {}^{5} P_{3} \\
\Rightarrow & n(n-1)(n-2)(n-3)=2 \times 5 \times 4 \times 3 \\
\Rightarrow & n(n-3)(n-1)(n-2)=120 \\
\Rightarrow & (n^{2}-3n)(n^{2}-3n+2)=120 \\
\Rightarrow & m(m+2)-120=0, \text{ where } m=n^{2}-3n \\
\Rightarrow & m^{2}+2m-120=0 \Rightarrow (m+12)(m-10)=0 \\
\Rightarrow & m=-12 \text{ or } m=10.
\end{array}
$$
This gives
$$
\begin{array}{lll} 
& n^{2}-3n=-12 \text{ or } n^{2}-3n=10 \\
\Rightarrow & n^{2}-3n+12=0 \text{ or } n^{2}-3n-10=0 \\
\Rightarrow & n=\frac{3 \pm \sqrt{9-48}}{2} \text{ or } (n-5)(n+2)=0 \\
\Rightarrow & n=\frac{3 \pm i \sqrt{39}}{2} \quad \text{ or } n=5 \text{ or } n=-2
\end{array}
$$
$\Rightarrow n=5$ [neglecting the negative and imaginary values of $n$].
Hence, $n=5$.

---

### Example 5

(i) If ${}^{15} P_{r}=2730$, find the value of $r$.
(ii) If ${}^{10} P_{r}=5040$, find the value of $r$.

#### Solution

(i)
$$
\begin{array}{ll}
& {}^{15} P_{r}=2730 \\
\Rightarrow & {}^{15} P_{r}=15 \times 182 \\
\Rightarrow & {}^{15} P_{r}=15 \times 14 \times 13 \quad \text{(up to 3 factors)} \\
\Rightarrow & r=3
\end{array}
$$
Hence, $r=3$.

(ii)
$$
\begin{array}{ll}
& {}^{10} P_{r}=5040 \\
\Rightarrow & {}^{10} P_{r}=10 \times 504 \\
\Rightarrow & {}^{10} P_{r}=10 \times 9 \times 56 \\
\Rightarrow & {}^{10} P_{r}=10 \times 9 \times 8 \times 7 \quad \text{(up to 4 factors)} \\
\Rightarrow & r=4
\end{array}
$$
Hence, $r=4$.

---

### Example 6

If ${}^{56} P_{r+6} : {}^{54} P_{r+3} = (30800:1)$, find $r$.

#### Solution

We have
$$
{}^{56} P_{r+6}=\frac{56!}{[56-(r+6)]!}=\frac{56!}{(50-r)!}
$$
And,
$$
{}^{54} P_{r+3}=\frac{54!}{[54-(r+3)]!}=\frac{54!}{(51-r)!}
$$
$$
\therefore \quad \begin{aligned}
\frac{{}^{56} P_{r+6}}{{}^{54} P_{r+3}} & =\frac{56!}{(50-r)!} \times \frac{(51-r)!}{54!} \\
& =\frac{56 \times 55 \times(54!)}{(50-r)!} \times \frac{(51-r) \cdot[(50-r)!]}{54!} \\
& =56 \times 55 \times(51-r).
\end{aligned}
$$
Thus, $\frac{{}^{56} P_{r+6}}{{}^{54} P_{r+3}} = \frac{30800}{1} \Rightarrow 56 \times 55 \times (51-r) = 30800$
$$
\Rightarrow (51-r) = 10 \Rightarrow r=41.
$$
Hence, $r=41$.

---

### Example 7

If ${}^{2n+1} P_{n-1} : {}^{2n-1} P_{n} = 3:5$, find $n$.

#### Solution

We have
$$
\begin{aligned}
& {}^{2n+1} P_{n-1} : {}^{2n-1} P_{n} = 3:5 \\
\Rightarrow & \frac{(2n+1)!}{\{(2n+1)-(n-1)\}!} : \frac{(2n-1)!}{\{(2n-1)-n\}!} = \frac{3}{5} \\
\Rightarrow & \frac{(2n+1)!}{(n+2)!} : \frac{(2n-1)!}{(n-1)!} = \frac{3}{5} \\
\Rightarrow & \frac{(2n+1)!}{(n+2)!} \times \frac{(n-1)!}{(2n-1)!} = \frac{3}{5} \\
\Rightarrow & \frac{(2n+1) \times 2n \times [(2n-1)!]}{(n+2) \times (n+1) \times n \times [(n-1)!]} \times \frac{(n-1)!}{(2n-1)!} = \frac{3}{5} \\
\Rightarrow & 10(2n+1) = 3(n+2)(n+1) \\
\Rightarrow & 20n+10 = 3(n^{2}+3n+2) \\
\Rightarrow & 3n^{2}-11n-4 = 0 \\
\Rightarrow & (n-4)(3n+1)=0 \Rightarrow n=4 \quad [\because n \neq \frac{-1}{3}, \text{ as } n \text{ cannot be negative}].
\end{aligned}
$$
Hence, $n=4$.

---

### Example 8

If ${}^{22} P_{r+1} : {}^{20} P_{r+2} = 11:52$, find $r$.

#### Solution

We have
$$
\begin{aligned}
& {}^{22} P_{r+1} : {}^{20} P_{r+2} = 11:52 \\
\Rightarrow & \frac{22!}{\{22-(r+1)\}!} : \frac{20!}{\{20-(r+2)\}!} = 11:52 \\
\Rightarrow & \frac{22!}{(21-r)!} : \frac{20!}{(18-r)!} = \frac{11}{52} \\
\Rightarrow & \frac{22!}{(21-r)!} \times \frac{(18-r)!}{20!} = \frac{11}{52} \\
\Rightarrow & \frac{22 \times 21 \times (20!)}{(21-r)(20-r)(19-r) \times [(18-r)!]} \times \frac{(18-r)!}{20!} = \frac{11}{52} \\
\Rightarrow & \frac{22 \times 21}{(21-r)(20-r)(19-r)} = \frac{11}{52} \\
\Rightarrow & (19-r)(20-r)(21-r) = 2 \times 21 \times 52 = 2 \times 3 \times 7 \times 4 \times 13 \\
\Rightarrow & (19-r)(20-r)(21-r) = 12 \times 13 \times 14 \\
\Rightarrow & 19-r = 12 \Rightarrow r = (19-12) = 7.
\end{aligned}
$$
Hence, $r=7$.

---

### Example 9

Prove that:
(i) ${}^{n} P_{n} = {}^{n} P_{n-1}$
(ii) ${}^{n} P_{r} = n \cdot {}^{n-1} P_{r-1}$
(iii) ${}^{n-1} P_{r} + r \cdot {}^{n-1} P_{r-1} = {}^{n} P_{r}$

#### Solution

By using the formula for ${}^{n} P_{r}$, we have
(i) ${}^{n} P_{n-1} = \frac{n!}{\{n-(n-1)\}!} = \frac{n!}{1!} = n! = {}^{n} P_{n}$.
(ii) ${}^{n} P_{r} = \frac{n!}{(n-r)!} = \frac{n \cdot (n-1)!}{[(n-1)-(r-1)]!} = n \cdot {}^{n-1} P_{r-1}$.
(iii)
$$
\begin{aligned}
& {}^{n-1} P_{r} + r \cdot {}^{n-1} P_{r-1} \\
& = \left\{\frac{(n-1)!}{(n-1-r)!} + r \cdot \frac{(n-1)!}{[(n-1)-(r-1)]!}\right\} \\
& = \left\{\frac{(n-1)!}{(n-1-r)!} + r \cdot \frac{(n-1)!}{(n-r)!}\right\} \\
& = \left\{\frac{(n-1)!}{(n-r-1)!} + r \cdot \frac{(n-1)!}{(n-r) \cdot [(n-r-1)!]}\right\} \\
& = \frac{(n-1)!}{(n-r-1)!}\left\{1+\frac{r}{(n-r)}\right\} = \frac{n \cdot [(n-1)!]}{(n-r) \cdot [(n-r-1)!]} \\
& = \frac{n!}{(n-r)!} = {}^{n} P_{r}.
\end{aligned}
$$
Hence, ${}^{n-1} P_{r} + r \cdot {}^{n-1} P_{r-1} = {}^{n} P_{r}$.

---

### Example 10

If $r < s \leq n$ then prove that ${}^{n} P_{s}$ is divisible by ${}^{n} P_{r}$.

#### Solution

We have
$$
\begin{aligned}
{}^{n} P_{s} & = n(n-1)(n-2) \ldots (n-r+1)(n-r) \ldots (n-s+1) \\
& = \{n(n-1)(n-2) \ldots (n-r+1)\} \times \{(n-r)(n-r-1) \ldots (n-s+1)\} \\
& = {}^{n} P_{r} \times \{(n-r)(n-r-1) \ldots (n-s+1)\}
\end{aligned}
$$
which is clearly divisible by ${}^{n} P_{r}$.
Hence, ${}^{n} P_{s}$ is divisible by ${}^{n} P_{r}$.

---

### Example 11

Find the number of permutations of 7 objects, taken 3 at a time.

#### Solution

Number of permutations of 7 objects, taken 3 at a time
$$
\begin{aligned}
& = {}^{7} P_{3} = 7 \times 6 \times 5 \quad \text{[up to three terms]} \\
& = 210.
\end{aligned}
$$

---

