## Vector Spaces

A vector space ($V$), sometimes called a **linear space**, is a collection of elements that can be added together and multiplied by scalars [1, 2].

| Concept | Key Definition/Rule | Citation(s) |
| :--- | :--- | :--- |
| **Elements (Members)** | Elements of $V$ can be vectors, matrices, or even functions (like linear polynomials) [1, 3, 4]. They must have properties like associative and commutative addition, and they must include a zero vector and an additive inverse [5]. | [3–5] |
| **Notation** | **V** denotes the vector space [1]. **R** denotes the set of all real numbers [6]. **Rⁿ** (written as $\mathbb{R}^n$) is the set of real vectors with length $n$ [7]. | [1, 6, 7] |
| **The Crucial Test: CLOSURE** | Closure is the important property that **determines if $V$ is a vector space** [8]. Both rules below must be satisfied for a set to be closed [9, 10]. | [8–10] |
| **Closure Rule 1 (Scalar Multiplication)** | Multiplying an element of $V$ by **any scalar** must yield a result that is **also within $V$** [8]. | [8] |
| **Closure Rule 2 (Addition)** | **Adding any two elements** ($a$ and $b$) within $V$ must yield a result that is **also contained within $V$** [8]. | [8] |
| **Example Spaces** | The set of **real numbers ($\mathbb{R}$)** is a vector space [7]. The set of **$\mathbb{R}^n$ vectors** (e.g., $\mathbb{R}^3$) is a vector space [3, 7]. The set of **linear polynomials** ($ax + b$) is a vector space [4, 10]. | [3, 4, 7, 10] |
| **Example Failure** | A set fails to be a vector space if adding two elements produces a result **outside** the original set (e.g., adding two vectors where the second row is 2 results in 4, which is not in the original set) [10, 11]. | [10, 11] |

---

## Test Me!

Please answer the following questions based on the sources:

1. What is the alternate name for a vector space?  
2. What crucial property determines if a set $V$ is considered a vector space?  
3. Name one of the two requirements for this crucial property to be satisfied.  
4. If you add two elements of a vector space, where must the resulting sum be found?  
5. If a set of vectors is defined such that the second row must always have the value 2, why does this set fail the vector space criteria when adding two elements together?


## Subspaces and Span

### I. Subspaces ($S$)

| Concept | Definition/Requirement | Citation |
| :--- | :--- | :--- |
| **Subspace** | A **smaller set ($S$)** within a larger **vector space ($V$)** that is itself a vector space [1]. | [1] |
| **Primary Requirement** | $S$ must satisfy the properties of **closure** [2]. | [2] |
| **Closure Check 1 (Scalar Multiplication)** | Multiplying a vector in $S$ by a scalar ($c$) must result in a vector still contained in $S$ [3, 4]. | [3, 4] |
| **Closure Check 2 (Vector Addition)** | Adding two vectors ($x$ and $y$) from $S$ must result in a vector still contained in $S$ [4, 5]. | [4, 5] |
| **Verification** | If $S$ is closed, it is a vector space; since it is contained in $V$, it is a **subspace of $V$** [2, 5]. | [2, 5] |

---

### II. Linear Combinations and Span

| Concept | Definition/Relationship | Citation |
| :--- | :--- | :--- |
| **Linear Combination** | Any **sum** of elements ($v_1, v_2, ..., v_n$) multiplied by some **scalars** ($a_1, a_2, ..., a_n$): $$a_1v_1 + a_2v_2 + \cdots + a_nv_n$$ [5]. | [5] |
| **Span** | The **set of all possible linear combinations** of those elements [5]. | [5] |
| **Span is a Subspace** | The **span** of any number of elements of a vector space $V$ **is also a subspace of $V$** [6]. | [6] |
| **Smallest Subspace** | The span is the **smallest subspace** of $V$ that contains that set of elements [6]. It is the **intersection of all subspaces** that contain them [7]. | [6, 7] |

---

## Comprehension Test

Please answer the following questions based exclusively on the information presented in the sources:

1. **If $V$ is a vector space, what is the definition of a subspace $S$ of $V$?**  
   (Provide two core components of the definition.)

2. **Assuming that every element of a set $S$ already obeys the properties of the larger vector space $V$, what single requirement must be checked to determine if $S$ is a vector space (and thus a subspace of $V$)?**

3. **What are the two specific properties that must be verified to demonstrate that a set $S$ satisfies the requirement of closure?**

4. **Define a linear combination in terms of elements and scalars.**

5. **The sources state that the span of any number of elements of a vector space $V$ is also a subspace of $V$. Furthermore, what unique characteristic describes the span relative to other subspaces containing that same set of elements?**