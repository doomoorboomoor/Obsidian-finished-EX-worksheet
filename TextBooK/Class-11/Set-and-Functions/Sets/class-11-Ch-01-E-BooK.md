## Laws of Operations on Sets

### THEOREM 1 (**Idempotent laws**)
For any set $A$, prove that:
- (i) **$A \cup A=A$**
- (ii) **$A \cap A=A$**

#### PROOF
We have
- (i) $A \cup A=\{x: x \in A \text{ or } x \in A\}=\{x: x \in A\}=A$.
- (ii) $A \cap A=\{x: x \in A \text{ and } x \in A\}=\{x: x \in A\}=A$.

---

### THEOREM 2 (**Identity laws**)
For any set $A$, prove that:
- (i) **$A \cup \phi=A$**
- (ii) **$A \cap U=A$**, where $U$ is the universal set

#### PROOF
We have
- (i) $A \cup \phi=\{x: x \in A \text{ or } x \in \phi\}=\{x: x \in A\}=A \quad [\because x \notin \phi]$
- (ii) $A \cap U=\{x: x \in A \text{ and } x \in U\}=\{x: x \in A\}=A \quad [\because A \subset U]$

#### NOTE
$\phi$ and $U$ are the identity elements for union and intersection of sets respectively.

---

### THEOREM 3 (**Commutative laws**)
For any two sets $A$ and $B$, prove that:
- I. **$A \cup B=B \cup A$** [Commutative law for union of sets]
- II. **$A \cap B=B \cap A$** [Commutative law for intersection of sets]

#### PROOF
**I.** Let $x$ be an arbitrary element of $A \cup B$. Then,
$$
\begin{align*}
x \in A \cup B & \Rightarrow x \in A \text { or } x \in B \\
& \Rightarrow x \in B \text { or } x \in A \\
& \Rightarrow x \in B \cup A . \\
\therefore \quad A \cup B & \subseteq B \cup A . \tag{i}
\end{align*}
$$
Again, let $y$ be an arbitrary element of $B \cup A$. Then,
$$
\begin{aligned}
y \in B \cup A & \Rightarrow y \in B \text { or } y \in A \\
& \Rightarrow y \in A \text { or } y \in B \\
& \Rightarrow y \in A \cup B
\end{aligned}
$$
$$
\therefore \quad B \cup A \subseteq A \cup B . \tag{ii}
$$
From (i) and (ii), we get $A \cup B=B \cup A$.

**II.** Let $x$ be an arbitrary element of $A \cap B$. Then,
$$
\begin{align*}
x \in A \cap B & \Rightarrow x \in A \text { and } x \in B \\
& \Rightarrow x \in B \text { and } x \in A \\
& \Rightarrow x \in B \cap A . \\
\therefore \quad A \cap B \subseteq B & \cap A . \tag{iii}
\end{align*}
$$
Again, let $y$ be an arbitray element of $B \cap A$. Then,
$$
\begin{align*}
y \in B \cap A & \Rightarrow y \in B \text { and } y \in A \\
& \Rightarrow y \in A \text { and } y \in B \\
& \Rightarrow y \in A \cap B \tag{iv}
\end{align*}
$$
From (iii) and (iv), we get $A \cap B=B \cap A$.

---

### THEOREM 4 (**Associative laws**)
For any sets $A, B, C$, prove that:
- I. **$(A \cup B) \cup C=A \cup(B \cup C)$** [Associative law for union of sets]
- II. **$(A \cap B) \cap C=A \cap(B \cap C)$** [Associative law for intersection of sets]

#### PROOF
**I.** Let $x$ be an arbitrary element of $(A \cup B) \cup C$. Then,
$$
\begin{aligned}
x \in(A \cup B) \cup C & \Rightarrow x \in(A \cup B) \text { or } x \in C \\
& \Rightarrow(x \in A \text { or } x \in B) \text { or } x \in C \\
& \Rightarrow x \in A \text { or }(x \in B \text { or } x \in C) \\
& \Rightarrow x \in A \text { or } x \in(B \cup C) \\
& \Rightarrow x \in A \cup(B \cup C) .
\end{aligned}
$$
$$
\therefore \quad(A \cup B) \cup C \subseteq A \cup(B \cup C) . \tag{i}
$$
Again, let $y$ be an arbitrary element of $A \cup(B \cup C)$. Then,
$$
\begin{align*}
y \in A \cup(B \cup C) & \Rightarrow y \in A \text { or } y \in(B \cup C) \\
& \Rightarrow y \in A \text { or }(y \in B \text { or } y \in C) \\
& \Rightarrow(y \in A \text { or } y \in B) \text { or } y \in C \\
& \Rightarrow y \in(A \cup B) \text { or } y \in C \\
& \Rightarrow y \in(A \cup B) \cup C . \\
\therefore \quad A \cup(B \cup C) \subseteq(A \cup B) \cup C . & \tag{ii}
\end{align*}
$$
From (i) and (ii), we get $(A \cup B) \cup C=A \cup(B \cup C)$.

**II.** Let $x$ be an arbitrary element of $(A \cap B) \cap C$. Then,
$$
\begin{align*}
& x \in(A \cap B) \cap C \Rightarrow x \in(A \cap B) \text { and } x \in C \\
& \Rightarrow(x \in A \text { and } x \in B) \text { and } x \in C \\
& \Rightarrow x \in A \text { and }(x \in B \text { and } x \in C) \\
& \Rightarrow x \in A \text { and } x \in(B \cap C) \\
& \Rightarrow x \in A \cap(B \cap C) . \\
& \therefore \quad(A \cap B) \cap C \subseteq A \cap(B \cap C) . \tag{iii}
\end{align*}
$$
Again, let $y$ be an arbitrary element of $A \cap(B \cap C)$. Then,
$$
\begin{align*}
& y \in A \cap(B \cap C) \Rightarrow y \in A \text { and } y \in(B \cap C) \\
& \Rightarrow y \in A \text { and }(y \in B \text { and } y \in C) \\
& \Rightarrow(y \in A \text { and } y \in B) \text { and } y \in C \\
& \Rightarrow y \in(A \cap B) \text { and } y \in C \\
& \Rightarrow y \in(A \cap B) \cap C \\
& \therefore \quad A \cap(B \cap C) \subseteq(A \cap B) \cap C . \tag{iv}
\end{align*}
$$
From (iii) and (iv), we get $(A \cap B) \cap C=A \cap(B \cap C)$.

---

### THEOREM 5 (**Distributive laws**)
For any three sets $A, B, C$ prove that:
- I. **$A \cup(B \cap C)=(A \cup B) \cap(A \cup C)$** [Distributive law of union over intersection]
- II. **$A \cap(B \cup C)=(A \cap B) \cup(A \cap C)$** [Distributive law of intersection over union]

#### PROOF
**I.** Let $x$ be an arbitrary element of $A \cup(B \cap C)$. Then,
$$
\begin{align*}
x \in A \cup(B \cap C) & \Rightarrow x \in A \text { or } x \in(B \cap C) \\
& \Rightarrow x \in A \text { or } (x \in B \text{ and } x \in C) \\
& \Rightarrow (x \in A \text{ or } x \in B) \text{ and } (x \in A \text{ or } x \in C)) \\
& \quad [\because \text{ 'or' distributes 'and' }] \\
& \Rightarrow x \in(A \cup B) \text{ and } x \in(A \cup C) .
\end{align*}
$$
Again, let $y$ be an arbitrary element of $(A \cup B) \cap(A \cup C)$. Then,
$$
\begin{align*}
y \in(A \cup B) \cap(A \cup C) & \Rightarrow y \in(A \cup B) \text { and } y \in(A \cup C) \\
& \Rightarrow(y \in A \text { or } y \in B) \text { and } (y \in A \text { or } y \in C) \\
& \Rightarrow y \in A \text { or } (y \in B \text { and } y \in C) \\
& \Rightarrow y \in A \text { or } y \in(B \cap C) \\
& \Rightarrow y \in A \cup(B \cap C) . \\
\therefore \quad(A \cup B) \cap(A \cup C) & \subseteq A \cup(B \cap C) .
\end{align*}
$$
From (i) and (ii), we get $A \cup(B \cap C)=(A \cup B) \cap(A \cup C)$.

**II.** Let $x$ be an arbitrary element of $A \cap(B \cup C)$. Then,
$$
\begin{align*}
x \in A \cap(B \cup C) & \Rightarrow x \in A \text { and } x \in(B \cup C) \\
& \Rightarrow x \in A \text { and } (x \in B \text{ or } x \in C) \\
& \Rightarrow (x \in A \text{ and } x \in B) \text{ or } (x \in A \text{ and } x \in C) \\
& \quad [\because \text{ 'and' distributes 'or' }] \\
& \Rightarrow x \in(A \cap B) \text{ or } x \in(A \cap C) \\
& \Rightarrow x \in(A \cap B) \cup(A \cap C) \tag{iii}
\end{align*}
$$
Again, let $y$ be an arbitrary element of $(A \cap B) \cup(A \cap C)$. Then,
$$
\begin{align*}
y \in(A \cap B) \cup(A \cap C) & \Rightarrow y \in(A \cap B) \text{ or } y \in(A \cap C) \\
& \Rightarrow (y \in A \text{ and } y \in B) \text{ or } (y \in A \text{ and } y \in C) \\
& \Rightarrow y \in A \text{ and } (y \in B \text{ or } y \in C) \\
& \quad [\because \text{ 'and' distributes 'or' }] \\
& \Rightarrow y \in A \text{ and } y \in(B \cup C) \\
\therefore \quad(A \cap B) \cup(A \cap C) & \subseteq A \cap(B \cup C) .
\end{align*}
$$
From (iii) and (iv), we get $A \cap(B \cup C)=(A \cap B) \cup(A \cap C)$.

---

### THEOREM 6 (**De Morgan's laws**)
For any two sets $A$ and $B$, prove that:
- I. **$(A \cup B)^{\prime}=\left(A^{\prime} \cap B^{\prime}\right)$**
- II. **$(A \cap B)^{\prime}=\left(A^{\prime} \cup B^{\prime}\right)$**

#### PROOF
**I.** Let $x$ be an arbitrary element of $(A \cup B)^{\prime}$. Then,
$$
\begin{align*}
x \in(A \cup B)^{\prime} & \Rightarrow x \notin A \cup B \\
& \Rightarrow x \notin A \text { and } x \notin B \\
& \Rightarrow x \in A^{\prime} \text { and } x \in B^{\prime} \\
& \Rightarrow x \in\left(A^{\prime} \cap B^{\prime}\right) . \\
\therefore \quad(A \cup B)^{\prime} & \subseteq\left(A^{\prime} \cap B^{\prime}\right) . \tag{i}
\end{align*}
$$
Again, let $y$ be an arbitrary element of $(A^{\prime} \cap B^{\prime})$. Then,
$$
\begin{aligned}
y \in\left(A^{\prime} \cap B^{\prime}\right) & \Rightarrow y \in A^{\prime} \text { and } y \in B^{\prime} \\
& \Rightarrow y \notin A \text { and } y \notin B \\
& \Rightarrow y \notin(A \cup B) \\
& \Rightarrow y \in(A \cup B)^{\prime} .
\end{aligned}
$$
$$
\therefore \quad\left(A^{\prime} \cap B^{\prime}\right) \subseteq(A \cup B)^{\prime} . \tag{ii}
$$
From (i) and (ii), we get $(A \cup B)^{\prime}=\left(A^{\prime} \cap B^{\prime}\right)$.

**II.** Let $x$ be an arbitrary element of $(A \cap B)^{\prime}$. Then,
$$
\begin{align*}
x \in(A \cap B)^{\prime} & \Rightarrow x \notin(A \cap B) \\
& \Rightarrow x \notin A \text { or } x \notin B \\
& \Rightarrow x \in A^{\prime} \text { or } x \in B^{\prime} \\
& \Rightarrow x \in\left(A^{\prime} \cup B^{\prime}\right) \tag{iii}
\end{align*}
$$
Again, let $y$ be an arbitrary element of $\left(A^{\prime} \cup B^{\prime}\right)$. Then,
$$
\begin{align*}
& y \in\left(A^{\prime} \cup B^{\prime}\right) \Rightarrow y \in A^{\prime} \text { or } y \in B^{\prime} \\
& \Rightarrow y \notin A \text { or } y \notin B \\
& \Rightarrow y \notin(A \cap B) \\
& \Rightarrow y \in(A \cap B)^{\prime} \\
& \therefore \quad\left(A^{\prime} \cup B^{\prime}\right) \subseteq(A \cap B)^{\prime} \tag{iv}
\end{align*}
$$
From (iii) and (iv), we get $(A \cap B)^{\prime}=\left(A^{\prime} \cup B^{\prime}\right)$.

---

## Some More Results

### THEOREM 7
For any two sets $A$ and $B$, prove that:
- I. **$A \subseteq B \Rightarrow B^{\prime} \subseteq A^{\prime}$**
- II. **$A-B=A \cap B^{\prime}$**
- III. **$(A-B) \cap B=\phi$**
- IV. **$(A-B) \cup(B-A)=(A \cup B)-(A \cap B)$**
- V. **$(A-B)=A \Leftrightarrow A \cap B=\phi$**

#### PROOF
**I.** Let $A \subseteq B$ be given and let $x$ be an arbitrary element of $B^{\prime}$. Then,
$$
\begin{aligned}
x \in B^{\prime} & \Rightarrow x \notin B \\
& \Rightarrow x \notin A \quad[\because A \subseteq B] \\
& \Rightarrow x \in A^{\prime} . \\
\therefore \quad B^{\prime} \subseteq A^{\prime} . & \\
\text{ Hence, } A \subseteq B & \Rightarrow B^{\prime} \subseteq A^{\prime} .
\end{aligned}
$$
**II.** Let $x$ be an arbitrary element of $(A-B)$. Then,
$$
\begin{align*}
& x \in(A-B) \Rightarrow x \in A \text { and } x \notin B \\
& \Rightarrow x \in A \text { and } x \in B^{\prime} \\
& \Rightarrow x \in A \cap B^{\prime} . \\
& \therefore \quad(A-B) \subseteq A \cap B^{\prime} . \tag{i}
\end{align*}
$$
Again, let $y$ be an arbitrary element of $(A \cap B^{\prime})$. Then,
$$
\begin{align*}
& x \in\left(A \cap B^{\prime}\right) \Rightarrow x \in A \text { and } x \in B^{\prime} \\
& \Rightarrow x \in A \text { and } x \notin B \\
& \Rightarrow x \in(A-B) . \\
& \therefore \quad\left(A \cap B^{\prime}\right) \subseteq(A-B) . \tag{ii}
\end{align*}
$$
Hence, from (i) and (ii), we get $(A-B)=\left(A \cap B^{\prime}\right)$.

**III.** If possible, let $(A-B) \cap B \neq \phi$ and let $x \in(A-B) \cap B$. Then,
$$
x \in(A-B) \cap B \Rightarrow x \in(A-B) \text{ and } x \in B
$$
$$
\begin{aligned}
& \Rightarrow(x \in A \text { and } x \notin B) \text { and } x \in B \\
& \Rightarrow x \in A \text { and } (x \notin B \text { and } x \in B) .
\end{aligned}
$$
But, $x \notin B$ and $x \in B$ can never hold simultaneously. Thus, we arrive at a contradiction. Since the contradiction arises by assuming that $(A-B) \cap B \neq \phi$ and hence $(A-B) \cap B=\phi$.

**IV.** Let $x$ be an arbitrary element of $(A-B) \cup(B-A)$. Then,
$$
\begin{align*}
x \in(A-B) \cup(B-A) & \Rightarrow x \in(A-B) \text { or } x \in(B-A) \\
& \Rightarrow(x \in A \text { and } x \notin B) \text { or } (x \in B \text { and } x \notin A) \\
& \Rightarrow(x \in A \text { or } x \in B) \text { and } (x \notin A \text { or } x \notin B) \\
& \Rightarrow x \in(A \cup B) \text { and } x \notin(A \cap B) \\
& \Rightarrow x \in\{(A \cup B)-(A \cap B)\} . \\
\therefore \quad(A-B) \cup(B-A) \subseteq & \{(A \cup B)-(A \cap B)\} .
\end{align*}
$$
Again, let $y$ be an arbitrary element of $(A \cup B)-(A \cap B)$. Then,
$$
\begin{align*}
y \in(A \cup B)-(A \cap B) & \Rightarrow y \in(A \cup B) \text { and } y \notin(A \cap B) \\
& \Rightarrow(y \in A \text { or } y \in B) \text { and } (y \notin A \text { or } y \notin B) \\
& \Rightarrow(y \in A \text { and } y \notin B) \text { or } (y \in B \text { and } y \notin A) \\
& \Rightarrow y \in(A-B) \text { or } y \in(B-A) \\
& \Rightarrow y \in(A-B) \cup(B-A) . \\
\therefore \quad(A \cup B)-(A \cap B) \subseteq & (A-B) \cup(B-A) .
\end{align*}
$$
From (iii) and (iv), we get $(A-B) \cup(B-A)=(A \cup B)-(A \cap B)$.

**V.** Let $(A-B)=A$ be given and we have to show that $A \cap B=\phi$. If possible, let $A \cap B \neq \phi$ and let $x \in A \cap B$. Then,
$$
\begin{aligned}
x \in A \cap B & \Rightarrow x \in A \text { and } x \in B \\
& \Rightarrow x \in(A-B) \text { and } x \in B \quad[\because A=(A-B) \text{ (given) }] \\
& \Rightarrow(x \in A \text { and } x \notin B) \text { and } x \in B \\
& \Rightarrow x \in A \text { and } (x \notin B \text { and } x \in B) .
\end{aligned}
$$
But, $x \notin B$ and $x \in B$ both can never hold simultaneously. Thus, we arrive at a contradiction. Since the contradiction arises by assuming that $A \cap B \neq \phi$, so $A \cap B=\phi$.
Thus, $(A-B)=A \Rightarrow A \cap B=\phi$.

Again, let $(A \cap B)=\phi$ and we have to show that $(A-B)=A$.
Now, $x \in(A-B) \Rightarrow x \in A$ and $x \notin B$
$$
\Rightarrow x \in A \text { (surely). } \tag{v}
$$
$\therefore \quad(A-B) \subseteq A$.
$$
\begin{align*}
& \text { Again, } \begin{aligned}
y \in A & \Rightarrow y \notin B \\
& \Rightarrow y \in A \text { and } y \notin B \\
& \Rightarrow y \in(A-B) .
\end{aligned} \\
& \therefore \quad A \subseteq(A-B) .
\end{align*}
$$
Thus, from (v) and (vi), we get $(A-B)=A$.
$\therefore \quad A \cap B=\phi \Rightarrow(A-B)=A$.
Hence, $(A-B)=A \Leftrightarrow(A \cap B)=\phi$.

---

### THEOREM 8
If $(A \cup B)=(A \cap B)$ then prove that $A=B$.

#### PROOF
Let $(A \cup B)=(A \cap B)$ be given.
Let $x$ be an arbitrary element of $A$. Then,
$$
\begin{align*}
x \in A & \Rightarrow x \in A \cup B & [\because A \subseteq A \cup B] \\
& \Rightarrow x \in A \cap B & [\because A \cup B=A \cap B] \\
& \Rightarrow x \in A \text { and } x \in B \\
& \Rightarrow x \in B \text { (surely). } \\
\therefore \quad A \subseteq B . & \tag{i}
\end{align*}
$$
Again, let $y \in B$. Then,
$$
\begin{array}{rlr}
y \in B & \Rightarrow y \in A \cup B & [\because B \subseteq A \cup B] \\
& \Rightarrow y \in A \cap B & [\because A \cup B=A \cap B] \\
& \Rightarrow y \in A \text { and } y \in B & \\
& \Rightarrow y \in A \text { (surely). } &
\end{array}
$$
$$
\therefore \quad B \subseteq A . \tag{ii}
$$
Thus, from (i) and (ii), we get $A=B$.

---

### THEOREM 9
If $A \subseteq B$ then for any set $C$, prove that $(C-B) \subseteq(C-A)$.

#### PROOF
Let $A \subseteq B$ be given. Let $x \in(C-B)$. Then,
$$
\begin{aligned}
x \in(C-B) & \Rightarrow x \in C \text { and } x \notin B \\
& \Rightarrow x \in C \text { and } x \notin A \quad[\because A \subseteq B] \\
& \Rightarrow x \in(C-A) .
\end{aligned}
$$
Hence, $A \subseteq B \Rightarrow(C-B) \subseteq(C-A)$.

---

### THEOREM 10
For any sets $A$ and $B$, prove that:
- (i) **$A \cup(A \cap B)=A$**
- (ii) **$A \cap(A \cup B)=A$**

#### PROOF
- (i) Since $(A \cap B) \subseteq A$, we have $A \cup(A \cap B)=A \quad [\because X \subseteq Y \Rightarrow X \cup Y=Y]$.
- (ii) Since $A \subseteq(A \cup B)$, we have $A \cap(A \cup B)=A \quad [\because X \subseteq Y \Rightarrow X \cap Y=X]$.

---

### THEOREM 11
For any sets $A$ and $B$, prove that:
- (i) **$(A \cap B) \cup(A-B)=A$**
- (ii) **$A \cup(B-A)=(A \cup B)$**

#### PROOF
- (i) We have
$$
\begin{array}{rlrl}
(A \cap B) \cup(A-B) & =(A \cap B) \cup\left(A \cap B^{\prime}\right) & & {\left[\because(A-B)=\left(A \cap B^{\prime}\right)\right]} \\
& =A \cap\left(B \cup B^{\prime}\right) & & {[\text { by distributive law }]} \\
& =A \cap U & & {\left[\because B \cup B^{\prime}=U\right]} \\
& =A . & &
\end{array}
$$
Hence, $(A \cap B) \cup(A-B)=A$.

- (ii) We have
$$
\begin{aligned}
A \cup(B-A) & =A \cup\left(B \cap A^{\prime}\right) & & {\left[\because(B-A)=\left(B \cap A^{\prime}\right)\right] } \\
& =(A \cup B) \cap\left(A \cup A^{\prime}\right) & & {[\text { by distributive law }] } \\
& =(A \cup B) \cap U & & {\left[\because A \cup A^{\prime}=U\right] } \\
& =(A \cup B) . &
\end{aligned}
$$
Hence, $A \cup(B-A)=(A \cup B)$.

---

### THEOREM 12
If $A \cap B^{\prime}=\phi$ then prove that $A=A \cap B$ and hence show that $A \subseteq B$.

#### PROOF
Let $A \cap B^{\prime}=\phi$ be given. Then,
$$
\begin{array}{rlr}
A & =(A \cap U), \text{ where } U \text{ is the universal set } & \\
& =A \cap\left(B \cup B^{\prime}\right) & {\left[\because B \cup B^{\prime}=U\right]} \\
& =(A \cap B) \cup\left(A \cap B^{\prime}\right) & \\
& =(A \cap B) \cup \phi & {\left[\because A \cap B^{\prime}=\phi\right]} \\
& =(A \cap B) . &
\end{array}
$$
Hence, $A=(A \cap B)$.

Further, let $A=A \cap B$ and let $x \in A$. Then,
$$
\begin{array}{rlr}
x \in A & \Rightarrow x \in A \cap B & {[\because A=A \cap B]} \\
& \Rightarrow x \in A \text { and } x \in B & \\
& \Rightarrow x \in B \text { (surely). } & \\
\therefore \quad A \subseteq B . & &
\end{array}
$$

---

### THEOREM 13
If $A, B$ and $C$ be the sets such that $A \cup B=A \cup C$ and $A \cap B=A \cap C$ then prove that $B=C$.

#### PROOF
Let $A \cup B=A \cup C$ and $A \cap B=A \cap C$ be given. Then,
$$
\begin{array}{ll} 
& A \cup B=A \cup C \\
\Rightarrow & (A \cup B) \cap B=(A \cup C) \cap B \text{ and } (A \cup B) \cap C=(A \cup C) \cap C \\
\Rightarrow & B=(A \cap B) \cup(C \cap B) \text{ and } (A \cap C) \cup(B \cap C)=C \\
& \quad [\because B \subseteq(A \cup B) \text{ and } C \subseteq(A \cup C)] \\
\Rightarrow & B=(A \cap B) \cup(B \cap C) \text{ and } (A \cap B) \cup(B \cap C)=C \quad [\because A \cap C=A \cap B] \\
\Rightarrow & B=C .
\end{array}
$$
Hence, $B=C$.

---

### THEOREM 14
For any sets $A, B$ and $C$, prove that:
- (i) **$A-(B \cup C)=(A-B) \cap(A-C)$**
- (ii) **$A-(B \cap C)=(A-B) \cup(A-C)$**
- (iii) **$(A \cup B)-C=(A-C) \cup(B-C)$**
- (iv) **$(A \cap B)-C=(A-C) \cap(B-C)$**

#### PROOF
We have
- (i)
$$
\begin{array}{rlr}
A-(B \cup C) & =A \cap(B \cup C)^{\prime} & {\left[\because X-Y=X \cap Y^{\prime}\right]} \\
& =A \cap\left(B^{\prime} \cap C^{\prime}\right) & {[\text { by De Morgan's law }]} \\
& =\left(A \cap B^{\prime}\right) \cap\left(A \cap C^{\prime}\right) & \\
& =(A-B) \cap(A-C) . & \\
\therefore A-(B \cup C) & =(A-B) \cap(A-C) . &
\end{array}
$$
- (ii)
$$
\begin{array}{rlr}
A-(B \cap C) & =A \cap(B \cap C)^{\prime} & {\left[\because X-Y=X \cap Y^{\prime}\right]} \\
& =A \cap\left(B^{\prime} \cup C^{\prime}\right) & {[\text { by De Morgan's law] }} \\
& =\left(A \cap B^{\prime}\right) \cup\left(A \cap C^{\prime}\right) & {[\text { by distributive law] }} \\
& =(A-B) \cup(A-C) & {\left[\because X \cap Y^{\prime}=X-Y\right] .} \\
\therefore A-(B \cap C) & =(A-B) \cup(A-C) . &
\end{array}
$$
- (iii)
$$
\begin{array}{rlr}
(A \cup B)-C & =(A \cup B) \cap C^{\prime} & {\left[\because X-Y=X \cap Y^{\prime}\right]} \\
& =\left(A \cap C^{\prime}\right) \cup\left(B \cap C^{\prime}\right) & {[\text { by distributive law }]} \\
& =(A-C) \cup(B-C) . & {\left[\because X \cap Y^{\prime}=X-Y\right]} \\
\therefore (A \cup B)-C & =(A-C) \cup(B-C) .
\end{array}
$$
- (iv)
$$
\begin{array}{rlr}
(A \cap B)-C & =(A \cap B) \cap C^{\prime} & {\left[\because X-Y=X \cap Y^{\prime}\right]} \\
& =\left(A \cap C^{\prime}\right) \cap\left(B \cap C^{\prime}\right) & \\
& =(A-C) \cap(B-C) . & {\left[\because X \cap Y^{\prime}=X-Y\right]} \\
\therefore (A \cap B)-C & =(A-C) \cap(B-C) .
\end{array}
$$

---

### THEOREM 15
Let $A$ and $B$ be sets. If $A \cap X=B \cap X=\phi$ and $A \cup X=B \cup X$ for some set $X$, show that $A=B$.

#### PROOF
$A \cup X=B \cup X$ [given]
$$
\begin{array}{llr}
\Rightarrow & A \cap(A \cup X)=A \cap(B \cup X) & \\
\Rightarrow & (A \cap A) \cup(A \cap X)=(A \cap B) \cup(A \cap X) & \text{ [by distributive law] } \\
\Rightarrow & A \cup \phi=(A \cap B) \cup \phi & {[\because A \cap X=\phi]} \\
\Rightarrow & A=(A \cap B) & \\
\Rightarrow & A \subseteq B & \dots (i)
\end{array}
$$
Again, $A \cup X=B \cup X$
$$
\begin{array}{llr}
\Rightarrow & B \cap(A \cup X)=B \cap(B \cup X) & \\
\Rightarrow & (B \cap A) \cup(B \cap X)=(B \cap B) \cup(B \cap X) & \text{ [by distributive law] } \\
\Rightarrow & (A \cap B) \cup \phi=B \cup \phi & {[\because B \cap X=\phi \text{ and } B \cap A=A \cap B]} \\
\Rightarrow & A \cap B=B & \\
\Rightarrow & B \subseteq A & \dots (ii)
\end{array}
$$
From (i) and (ii), we get $A=B$.

---

### THEOREM 16
Show that the following four conditions are equivalent:
- (i) **$A \subset B$**
- (ii) **$A-B=\phi$**
- (iii) **$A \cup B=B$**
- (iv) **$A \cap B=A$**

#### PROOF
In order to prove the required result, we will show that:
$$
\text{(i)} \Rightarrow \text{(ii)} \Rightarrow \text{(iii)} \Rightarrow \text{(iv)} \Rightarrow \text{(i)}.
$$
Now, **(i) $\Rightarrow$ (ii):**
Let $A \subset B$ be given. Then, there is no element of $A$ which is not in $B$.
$$
\therefore \quad A-B=\{x: x \in A \text { and } x \notin B\}=\phi
$$
[$\because$ there is no element of $A$ which is not in $B$].
Hence, $A \subset B \Rightarrow A-B=\phi$ and therefore, (i) $\Rightarrow$ (ii).

**(ii) $\Rightarrow$ (iii):**
Let $A-B=\phi$ be given. Then,
$$
\begin{aligned}
A-B=\phi & \Rightarrow \text{ every element of } A \text{ is in } B \\
& \Rightarrow A \subset B \\
& \Rightarrow A \cup B=B .
\end{aligned}
$$
Thus, $A-B=\phi \Rightarrow A \cup B=B$ and therefore, (ii) $\Rightarrow$ (iii).

**(iii) $\Rightarrow$ (iv):**
Let $A \cup B=B$ be given. Then,
$$
A \cup B=B \Rightarrow A \subset B \Rightarrow A \cap B=A
$$
Thus, $A \cup B=B \Rightarrow A \cap B=A$ and therefore, (iii) $\Rightarrow$ (iv).

**(iv) $\Rightarrow$ (i):**
Let $A \cap B=A$ be given. Then,
$$
x \in A \Rightarrow x \in A \cap B \quad [\because A=A \cap B]
$$
$$
\begin{aligned}
& \Rightarrow x \in A \text { and } x \in B \\
& \Rightarrow x \in B \text { (surely). } \\
\therefore \quad A \subseteq B . &
\end{aligned}
$$
Thus, $A \cap B=A \Rightarrow A \subseteq B$ and therefore, (iv) $\Rightarrow$ (i).

$\therefore \quad$ (i) $\Rightarrow$ (ii) $\Rightarrow$ (iii) $\Rightarrow$ (iv) $\Rightarrow$ (i).
Hence, the given four conditions are equivalent.

---

### THEOREM 17
For any sets $A$ and $B$, prove that $P(A \cap B)=P(A) \cap P(B)$.

#### PROOF
Let $X \in P(A \cap B)$. Then,
$$
\begin{align*}
& X \in P(A \cap B) \Rightarrow X \subseteq A \cap B \\
& \Rightarrow X \subseteq A \text { and } X \subseteq B \\
& \Rightarrow X \in P(A) \text { and } X \in P(B) \\
& \Rightarrow X \in P(A) \cap P(B) . \\
& \therefore \quad P(A \cap B) \subseteq P(A) \cap P(B) . \tag{i}
\end{align*}
$$
Again, let $Y \in P(A) \cap P(B)$. Then,
$$
\begin{aligned}
Y \in P(A) \cap P(B) & \Rightarrow Y \in P(A) \text { and } Y \in P(B) \\
& \Rightarrow Y \subseteq A \text { and } Y \subseteq B \\
& \Rightarrow Y \subseteq A \cap B \\
& \Rightarrow Y \in P(A \cap B) .
\end{aligned}
$$
$$
\therefore \quad P(A) \cap P(B) \subseteq P(A \cap B) . \tag{ii}
$$
From (i) and (ii), we get $P(A \cap B)=P(A) \cap P(B)$.

---

### THEOREM 18
For any two sets $A$ and $B$, prove that $P(A) \cup P(B) \subset P(A \cup B)$.
But, $P(A \cup B)$ is not necessarily a subset of $P(A) \cup P(B)$.

#### PROOF
Let $X$ be an arbitrary element of $P(A) \cup P(B)$. Then,
$$
\begin{aligned}
X \in P(A) \cup P(B) & \Rightarrow X \in P(A) \text { or } X \in P(B) \\
& \Rightarrow X \subset A \text { or } X \subset B \\
& \Rightarrow X \subset(A \cup B) \\
& \Rightarrow X \in P(A \cup B) .
\end{aligned}
$$
$\therefore \quad P(A) \cup P(B) \subset P(A \cup B)$.

However, $P(A \cup B) \subset P(A) \cup P(B)$ is not always true.
For example, let $A=\{1\}$ and $B=\{2\}$. Then, $A \cup B=\{1,2\}$.
$\therefore \quad P(A)=\{\phi,\{1\}\}, P(B)=\{\phi,\{2\}\}$
and $P(A \cup B)=\{\phi,\{1\},\{2\},\{1,2\}\}$.
Also, $P(A) \cup P(B)=\{\phi,\{1\},\{2\}\}$.
$\therefore \quad P(A \cup B) \not \subset P(A) \cup P(B)$.
Hence, in general, $P(A \cup B) \neq P(A) \cup P(B)$.

---

### THEOREM 19
If $P(A)=P(B)$, prove that $A=B$.

#### PROOF
Let $P(A)=P(B)$. Then,
$$
\begin{align*}
A \subseteq A & \Rightarrow A \in P(A) \\
& \Rightarrow A \in P(B) \\
& \Rightarrow A \subseteq B . \tag{i}
\end{align*}
$$
Again, $B \subseteq B \Rightarrow B \in P(B)$
$$
\begin{align*}
& \Rightarrow B \in P(A) \\
& \Rightarrow B \subseteq A . \tag{ii}
\end{align*}
$$
From (i) and (ii), we get $A \subseteq B$ and $B \subseteq A$.
Hence, $A=B$.

---

