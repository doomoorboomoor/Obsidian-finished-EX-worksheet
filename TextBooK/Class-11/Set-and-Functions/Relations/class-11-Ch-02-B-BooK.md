## Some Useful Results

### **Theorem 1:** If $A \subseteq B$, prove that $A \times C \subseteq B \times C$ for any set $C$.

#### Proof:
Let $A \subseteq B$ and let $(a, c)$ be an arbitrary element of $A \times C$. Then,

$$
\begin{aligned}
(a, c) \in A \times C & \Rightarrow a \in A \text{ and } c \in C \\
& \Rightarrow a \in B \text{ and } c \in C \quad [\because A \subseteq B] \\
& \Rightarrow (a, c) \in B \times C .
\end{aligned}
$$

Thus, every element of $A \times C$ is contained in $B \times C$.
$\therefore A \times C \subseteq B \times C$.

Hence, $A \subseteq B \Rightarrow A \times C \subseteq B \times C$ for any set $C$.

---

### **Theorem 2:** If $A \subseteq B$ and $C \subseteq D$, prove that $A \times C \subseteq B \times D$.

#### Proof:
Let $A \subseteq B$ and $C \subseteq D$. Then, we have to show that $A \times C \subseteq B \times D$.
Let $(a, c)$ be an arbitrary element of $A \times C$. Then,

$$
\begin{aligned}
(a, c) \in A \times C & \Rightarrow a \in A \text{ and } c \in C \\
& \Rightarrow a \in B \text{ and } c \in D \quad [\because A \subseteq B \text{ and } C \subseteq D] \\
& \Rightarrow (a, c) \in B \times D .
\end{aligned}
$$

Thus, every element of $A \times C$ is contained in $B \times D$.
Hence, $A \times C \subseteq B \times D$.

---

### **Theorem 3:** If $A$ and $B$ are any two nonempty sets, prove that $A \times B = B \times A \Leftrightarrow A = B$.

#### Proof:
Let us first assume that $A=B$. Then,

$$
\begin{aligned}
A \times B & = B \times B \text{ and } B \times A = B \times B \quad [\because A=B] . \\
\therefore \quad A & \times B = B \times A .
\end{aligned}
$$

Conversely, let $A \times B = B \times A$ and we have to show that $A = B$.
Let $a$ be an arbitrary element of $A$. Then,

$$
\begin{aligned}
a \in A & \Rightarrow (a, b) \in A \times B \text{ for some } b \in B \\
& \Rightarrow (a, b) \in B \times A \\
& \Rightarrow a \in B \text{ and } b \in A \\
& \Rightarrow a \in B \quad \text{(surely).} \\
\therefore \quad A & \subseteq B .
\end{aligned}
$$

Again, let $b$ be an arbitrary element of $B$. Then,

$$
\begin{aligned}
b \in B & \Rightarrow (b, a) \in B \times A \text{ for some } a \in A \\
& \Rightarrow (b, a) \in A \times B \\
& \Rightarrow b \in A \text{ and } a \in B \\
& \Rightarrow b \in A \quad \text{(surely).} \\
\therefore \quad B & \subseteq A .
\end{aligned}
$$

Thus, $A \subseteq B$ and $B \subseteq A \Rightarrow A=B$.

$$
\therefore \quad A \times B = B \times A \Rightarrow A=B .
$$

Hence, $A \times B = B \times A \Leftrightarrow A=B$.

---

### **Theorem 4:** If $A \subseteq B$, prove that $A \times A \subseteq (A \times B) \cap (B \times A)$.

#### Proof:
Let $A \subseteq B$ and let $(a, a)$ be an arbitrary element of $A \times A$.

Then, $(a, a) \in A \times A$
$$
\begin{aligned}
& \Rightarrow a \in A \text{ and } a \in A \\
& \Rightarrow a \in A \text{ and } a \in B \quad [\because A \subseteq B] \\
& \Rightarrow (a \in A, a \in B) \text{ and } (a \in B, a \in A) \\
& \Rightarrow (a, b) \in A \times B \text{ and } (a, b) \in B \times A \\
& \Rightarrow (a, b) \in (A \times B) \cap (B \times A) .
\end{aligned}
$$

$$
\therefore A \times A \subseteq (A \times B) \cap (B \times A) .
$$

Hence, $A \subseteq B \Rightarrow A \times A \subseteq (A \times B) \cap (B \times A)$.

---

### **Theorem 5:** For any sets $A$, $B$ and $C$, prove that $A \times (B \cup C) = (A \times B) \cup (A \times C)$.

#### Proof:
Let $(a, b)$ be an arbitrary element of $A \times (B \cup C)$. Then,

$$
\begin{aligned}
(a, b) \in A \times (B \cup C) & \Rightarrow a \in A \text{ and } b \in B \cup C \\
& \Rightarrow a \in A \text{ and } (b \in B \text{ or } b \in C) \\
& \Rightarrow (a \in A \text{ and } b \in B) \text{ or } (a \in A \text{ and } b \in C) \quad [\because p \text{ and } (q \text{ or } r) \equiv (p \text{ and } q) \text{ or } (p \text{ and } r)] \\
& \Rightarrow (a, b) \in A \times B \text{ or } (a, b) \in A \times C \\
& \Rightarrow (a, b) \in (A \times B) \cup (A \times C) .
\end{aligned}
$$

$$
\therefore \quad A \times (B \cup C) \subseteq (A \times B) \cup (A \times C) . \quad \text{(i)}
$$

Again, let $(x, y)$ be an arbitrary element of $(A \times B) \cup (A \times C)$. Then,

$$
\begin{aligned}
(x, y) \in (A \times B) \cup (A \times C) & \Rightarrow (x, y) \in A \times B \text{ or } (x, y) \in A \times C \\
& \Rightarrow (x \in A \text{ and } y \in B) \text{ or } (x \in A \text{ and } y \in C) \\
& \Rightarrow x \in A \text{ and } (y \in B \text{ or } y \in C) \quad \text{[by distributive law]} \\
& \Rightarrow x \in A \text{ and } y \in (B \cup C) \\
& \Rightarrow (x, y) \in A \times (B \cup C) .
\end{aligned}
$$

$$
\therefore \quad (A \times B) \cup (A \times C) \subseteq A \times (B \cup C) . \quad \text{(ii)}
$$

Hence, from (i) and (ii), we get:
$$
A \times (B \cup C) = (A \times B) \cup (A \times C)
$$

---

### **Theorem 6:** For any sets $A$, $B$ and $C$, prove that $A \times (B \cap C) = (A \times B) \cap (A \times C)$.

#### Proof:
Let $(a, b)$ be an arbitrary element of $A \times (B \cap C)$. Then,

$$
\begin{aligned}
(a, b) \in A \times (B \cap C) & \Rightarrow a \in A \text{ and } b \in (B \cap C) \\
& \Rightarrow a \in A \text{ and } (b \in B \text{ and } b \in C) \\
& \Rightarrow (a \in A \text{ and } b \in B) \text{ and } (a \in A \text{ and } b \in C) \\
& \Rightarrow (a, b) \in A \times B \text{ and } (a, b) \in A \times C \\
& \Rightarrow (a, b) \in (A \times B) \cap (A \times C)
\end{aligned}
$$

$$
\therefore \quad A \times (B \cap C) \subseteq (A \times B) \cap (A \times C) . \quad \text{(i)}
$$

Again, let $(x, y)$ be an arbitrary element of $(A \times B) \cap (A \times C)$. Then,

$$
\begin{aligned}
(x, y) \in (A \times B) \cap (A \times C) & \Rightarrow (x, y) \in A \times B \text{ and } (x, y) \in A \times C \\
& \Rightarrow (x \in A \text{ and } y \in B) \text{ and } (x \in A \text{ and } y \in C) \\
& \Rightarrow x \in A \text{ and } (y \in B \text{ and } y \in C) \\
& \Rightarrow x \in A \text{ and } y \in (B \cap C) \\
& \Rightarrow (x, y) \in A \times (B \cap C)
\end{aligned}
$$

$$
\therefore \quad (A \times B) \cap (A \times C) \subseteq A \times (B \cap C) . \quad \text{(ii)}
$$

Hence, from (i) and (ii), we get:
$$
A \times (B \cap C) = (A \times B) \cap (A \times C)
$$

---

### **Theorem 7:** For any sets $A$, $B$ and $C$, prove that $A \times (B-C) = (A \times B) - (A \times C)$.

#### Proof:
Let $(a, b)$ be an arbitrary element of $A \times (B-C)$. Then,

$$
\begin{align*}
(a, b) \in A \times (B-C) & \Rightarrow a \in A \text{ and } b \in (B-C) \\
& \Rightarrow a \in A \text{ and } (b \in B \text{ and } b \notin C) \\
& \Rightarrow (a \in A \text{ and } b \in B) \text{ and } (a \in A \text{ and } b \notin C) \\
& \Rightarrow (a, b) \in A \times B \text{ and } (a, b) \notin A \times C \\
& \Rightarrow (a, b) \in (A \times B) - (A \times C) .
\end{align*}
$$

$$
\therefore \quad A \times (B-C) \subseteq (A \times B) - (A \times C) . \quad \text{(i)}
$$

Again, let $(x, y)$ be an arbitrary element of $(A \times B) - (A \times C)$. Then,

$$
\begin{align*}
(x, y) \in (A \times B) - (A \times C) & \Rightarrow (x, y) \in A \times B \text{ and } (x, y) \notin A \times C \\
& \Rightarrow (x \in A \text{ and } y \in B) \text{ and } (x \in A \text{ and } y \notin C) \\
& \Rightarrow x \in A \text{ and } (y \in B \text{ and } y \notin C) \\
& \Rightarrow x \in A \text{ and } y \in (B-C) \\
& \Rightarrow (x, y) \in A \times (B-C) .
\end{align*}
$$

$$
\therefore \quad (A \times B) - (A \times C) \subseteq A \times (B-C) . \quad \text{(ii)}
$$

From (i) and (ii), we get:
$$
A \times (B-C) = (A \times B) - (A \times C)
$$

---

### **Theorem 8:** For any sets $A$, $B$, $C$ and $D$, prove that $(A \times B) \cap (C \times D) = (A \cap C) \times (B \cap D)$.

#### Proof:
Let $(a, b)$ be an arbitrary element of $(A \times B) \cap (C \times D)$. Then,

$$
\begin{align*}
(a, b) \in (A \times B) \cap (C \times D) & \Rightarrow (a, b) \in (A \times B) \text{ and } (a, b) \in (C \times D) \\
& \Rightarrow (a \in A \text{ and } b \in B) \text{ and } (a \in C \text{ and } b \in D) \\
& \Rightarrow (a \in A \text{ and } a \in C) \text{ and } (b \in B \text{ and } b \in D) \\
& \Rightarrow a \in (A \cap C) \text{ and } b \in (B \cap D) \\
& \Rightarrow (a, b) \in (A \cap C) \times (B \cap D) .
\end{align*}
$$
Let's call this result (i). Again, let $(x, y)$ be an arbitrary element of $(A \cap C) \times (B \cap D)$. Then,

$$
\begin{align*}
(x, y) \in (A \cap C) \times (B \cap D) & \Rightarrow x \in A \cap C \text{ and } y \in B \cap D \\
& \Rightarrow (x \in A \text{ and } x \in C) \text{ and } (y \in B \text{ and } y \in D) \\
& \Rightarrow (x \in A \text{ and } y \in B) \text{ and } (x \in C \text{ and } y \in D) \\
& \Rightarrow (x, y) \in A \times B \text{ and } (x, y) \in C \times D \\
& \Rightarrow (x, y) \in (A \times B) \cap (C \times D) .
\end{align*}
$$
Let's call this result (ii). From (i) and (ii), we get:
$$
(A \times B) \cap (C \times D) = (A \cap C) \times (B \cap D)
$$

---

### **Theorem 9:** For any sets $A$ and $B$, prove that $(A \times B) \cap (B \times A) = (A \cap B) \times (B \cap A)$.

#### Proof:
Let $(a, b)$ be an arbitrary element of $(A \times B) \cap (B \times A)$. Then,

$$
\begin{align*}
(a, b) \in (A \times B) \cap (B \times A) & \Rightarrow (a, b) \in A \times B \text{ and } (a, b) \in B \times A \\
& \Rightarrow (a \in A \text{ and } b \in B) \text{ and } (a \in B \text{ and } b \in A) \\
& \Rightarrow (a \in A \text{ and } a \in B) \text{ and } (b \in B \text{ and } b \in A) \\
& \Rightarrow a \in (A \cap B) \text{ and } b \in (B \cap A) \\
& \Rightarrow (a, b) \in (A \cap B) \times (B \cap A) .
\end{align*}
$$

$$
\therefore \quad (A \times B) \cap (B \times A) \subseteq (A \cap B) \times (B \cap A) . \quad \text{(i)}
$$

Again, let $(x, y)$ be an arbitrary element of $(A \cap B) \times (B \cap A)$. Then,

$$
\begin{align*}
(x, y) \in (A \cap B) \times (B \cap A) & \Rightarrow x \in A \cap B \text{ and } y \in B \cap A \\
& \Rightarrow (x \in A \text{ and } x \in B) \text{ and } (y \in B \text{ and } y \in A) \\
& \Rightarrow (x \in A \text{ and } y \in B) \text{ and } (x \in B \text{ and } y \in A) \\
& \Rightarrow (x, y) \in A \times B \text{ and } (x, y) \in B \times A \\
& \Rightarrow (x, y) \in (A \times B) \cap (B \times A) .
\end{align*}
$$

$$
\therefore \quad (A \cap B) \times (B \cap A) \subseteq (A \times B) \cap (B \times A) . \quad \text{(ii)}
$$

Thus, from (i) and (ii), we get:
$$
(A \times B) \cap (B \times A) = (A \cap B) \times (B \cap A) .
$$

---

**An Important Result:** If $A$ and $B$ are two nonempty sets having $n$ elements in common, then $(A \times B)$ and $(B \times A)$ have $n^2$ elements in common.

### Example:

Let $A$ and $B$ be two nonempty sets such that $n(A)=5$, $n(B)=6$ and $n(A \cap B)=3$.
Find (i) $n(A \times B)$, (ii) $n(B \times A)$ and (iii) $n\{(A \times B) \cap (B \times A)\}$.

#### Solution:

- **(i)** $n(A \times B) = n(A) \times n(B) = (5 \times 6) = 30$.
- **(ii)** $n(B \times A) = n(B) \times n(A) = (6 \times 5) = 30$.
- **(iii)** Given: $n(A \cap B)=3$.
$\therefore$ $A$ and $B$ have 3 elements in common.
So, $(A \times B)$ and $(B \times A)$ have $3^2=9$ elements in common.
Hence, $n\{(A \times B) \cap (B \times A)\} = 9$.

---

### **Theorem 10:** If $A$, $B$ and $C$ be three nonempty sets given in such a way that $A \times B = A \times C$, then prove that $B=C$.

#### Proof:
Let $A \times B = A \times C$ and we have to prove that $B=C$.
Let $b \in B$. Then,

$$
\begin{align*}
b \in B & \Rightarrow (a, b) \in A \times B \text{ for every } a \in A \\
& \Rightarrow (a, b) \in A \times C \text{ for every } a \in A \quad [\because A \times B = A \times C] \\
& \Rightarrow b \in C
\end{align*}
$$

So, $B \subseteq C$. (i)

Again, let $c \in C$. Then,

$$
\begin{align*}
c \in C & \Rightarrow (a, c) \in A \times C \text{ for every } a \in A \\
& \Rightarrow (a, c) \in A \times B \text{ for every } a \in A \quad [\because A \times C = A \times B] \\
& \Rightarrow c \in B
\end{align*}
$$

So, $C \subseteq B$. (ii)

From (i) and (ii), we get $B=C$.
Hence, $A \times B = A \times C \Rightarrow B=C$.

---

