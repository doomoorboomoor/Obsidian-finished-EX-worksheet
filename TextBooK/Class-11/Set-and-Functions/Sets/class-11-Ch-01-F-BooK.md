## Venn Diagrams

In order to express the relationship among sets in perspective, we represent them pictorially by means of diagrams, called **Venn diagrams**.

In these diagrams, the **universal set** is represented by a rectangular region and its **subsets** by circles inside the rectangle. We represent **disjoint sets** by disjoint circles and **intersecting sets** by intersecting circles.

## Venn Diagrams in Different Situations

### Case 1: When the universal set and its subset are given

Let $U$ be the **universal set** and let $A \subseteq U$.
We draw a circle inside a rectangle.
The rectangular region represents $U$ and the circular region represents $A$.

### Example:

Let $U=\{1,2,3,4,5,6,7\}$ and

$$
A=\{1,3,5,7\} .
$$

Then, we draw the Venn diagram, as shown in the given figure.
Clearly, $A^{\prime}=\{2,4,6\}$.
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-35.jpg?height=272&width=410&top_left_y=169&top_left_x=785)

---

### Case 2: When two intersecting subsets of $U$ are given

For representing two intersecting **subsets** $A$ and $B$ of $U$, we draw two intersecting circles within the rectangle.
The common region of these circles represents $A \cap B$.
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-35.jpg?height=269&width=410&top_left_y=469&top_left_x=785)

Excluding the region of $B$ from that of $A$ shows $(A-B)$.
Excluding the region of $A$ from that of $B$ shows $(B-A)$.

### Example:

Let $U=\{1,2,3,4,5,6,7,8\}$ be the universal set, and let
$A=\{1,3,4,5\}$ and $B=\{2,4,5,6\}$ be its subsets.
Then, $A \cap B=\{4,5\}$.
We draw the Venn diagram, as
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-35.jpg?height=267&width=406&top_left_y=855&top_left_x=789)
shown in the given figure.
Clearly, $(A-B)=\{1,3\}$ and $(B-A)=\{2,6\}$.

---

### Case 3: When two disjoint subsets of a set are given

In order to represent two **disjoint subsets** $A$ and $B$ of the universal set $U$, we draw two disjoint circles within a rectangle.

### Example:

Let $U=\{1,2,3,4,5,6,7\}$ be the universal set, and let $A=\{1,3,5\}$ and $B=\{2,4\}$ be two of its **disjoint subsets**.
Clearly, $A \cap B=\phi$.
So, we may draw the Venn diagram, as shown in the adjoining figure.
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-35.jpg?height=278&width=412&top_left_y=1339&top_left_x=783)

Clearly, $A \cap B=\phi,(A-B)=\{1,3,5\}=A$ and $(B-A)=\{2,4\}=B$.
$A^{\prime}=\{2,4,6,7\}$ and $B^{\prime}=\{1,3,5,6,7\}$.

---

### Case 4: When $B \subseteq A \subseteq U$

In this case, we draw two concentric circles within a rectangular region.
The inner circle represents $B$ and the outer circle represents $A$.

### Example:

Let $U=\{1,2,3,4,5,6,7,8\}$ be the universal set, and let $A=\{1,3,5,7\}$ and $B=\{3,7\}$ be its subsets.
Then, clearly $B \subseteq A$.
Now, we may draw the Venn diagram, as shown in the given figure.
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-36.jpg?height=270&width=410&top_left_y=171&top_left_x=781)

$$
\begin{aligned}
& A \cap B=B=\{3,7\}, A \cup B=A=\{1,3,5,7\}, \\
& (A-B)=\{1,5\},(B-A)=\phi, \\
& A^{\prime}=\{2,4,6,8\} \text { and } B^{\prime}=\{1,5,2,4,6,8\} .
\end{aligned}
$$

---

## Important Results from Venn Diagrams

Let $A$ and $B$ be two intersecting **subsets** of $U$.
In counting the elements of $(A \cup B)$, the elements of $A \cap B$ are counted twice, once in counting the elements of $A$ and second time in counting the elements of $B$.

$$
\therefore \quad n(A \cup B)=n(A)+n(B)-n(A \cap B) .
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-36.jpg?height=247&width=364&top_left_y=662&top_left_x=833)

If $A \cap B=\phi$, then $n(A \cap B)=0$ and therefore, in this case, we have

$$
n(A \cup B)=n(A)+n(B) .
$$

From the Venn diagram, it is also clear that:
1.  $n(A-B)+n(A \cap B)=n(A)$
2.  $n(B-A)+n(A \cap B)=n(B)$
3.  $n(A-B)+n(A \cap B)+n(B-A)=n(A \cup B)$.

---