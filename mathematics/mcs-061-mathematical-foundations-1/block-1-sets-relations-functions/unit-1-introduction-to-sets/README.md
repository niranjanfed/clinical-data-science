# Unit 1 — Introduction to Sets

**Course:** MCS-061 — Mathematical Foundations-I  
**Block:** 1 — Sets, Relations and Functions  
**Study Unit:** 1 — Introduction to Sets

---

## 1. Learning Objectives

After studying this unit, I should be able to:

- Define a set and understand the concept of a well-defined collection.
- Represent sets using different methods.
- Explain relationships between sets.
- Determine cardinality of finite sets.
- Identify different types of sets.
- Construct and interpret Venn diagrams.
- Perform operations on sets.
- Apply important laws of set theory.
- Understand ordered pairs and Cartesian products.
- Understand intervals and convex sets.
- Recognise Russell's Paradox.
- Apply set theory to counting and problem-solving.

---

# 2. Concept of a Set

A **set** is a well-defined collection of distinct objects.

The objects belonging to a set are called its **elements** or **members**.

For example:

$$
A = \{1,2,3,4\}
$$

Here:

- $A$ is the set.
- $1,2,3,4$ are elements of $A$.

The term **well-defined** means that, given an object, we can determine whether it belongs to the set or does not belong to the set.

### Examples

The following are sets:

$$
\{1,2,3,4\}
$$

and:

$$
\{x : x \text{ is a natural number less than } 5\}
$$

The following are not well-defined sets:

- intelligent students
- good cricketers
- rich people

The problem is that membership depends on subjective judgement.

---

# 3. Elements and Membership

Sets are generally represented using capital letters:

$$
A,B,C,\ldots
$$

Elements are commonly represented using lowercase letters:

$$
a,b,c,\ldots
$$

The symbol $\in$ means **"belongs to"** or **"is an element of"**.

If:

$$
A=\{1,2,3\}
$$

then:

$$
2\in A
$$

The symbol $\notin$ means **"does not belong to"**.

Therefore:

$$
5\notin A
$$

---

## Element vs Subset

This distinction is important.

If:

$$
A=\{1,2,3\}
$$

then:

$$
2\in A
$$

but:

$$
\{2\}\subseteq A
$$

These statements mean different things.

- $2$ is an **element** of $A$.
- $\{2\}$ is a **set containing 2**, and this set is a subset of $A$.

---

# 4. Methods of Representing a Set

IGNOU discusses two important methods.

## 4.1 Roster Method

The elements of the set are explicitly listed inside braces.

Example:

$$
A=\{a,e,i,o,u\}
$$

For natural numbers:

$$
N=\{1,2,3,4,5,\ldots\}
$$

For whole numbers:

$$
W=\{0,1,2,3,\ldots\}
$$

For integers:

$$
Z=\{\ldots,-3,-2,-1,0,1,2,3,\ldots\}
$$

Repeated elements are written only once.

For example, the letters in **ASSIGNMENT** form the set:

$$
\{A,S,I,G,N,M,E,T\}
$$

---

## 4.2 Set-Builder Method

In the set-builder method, a set is described using a property satisfied by its elements.

Example:

$$
A=\{x : x \text{ is a vowel of the English alphabet}\}
$$

The symbol `:` is read as **"such that"**.

Another example:

$$
A=\{x : x \text{ is a natural number and } x \text{ is a multiple of } 3\}
$$

This represents:

$$
\{3,6,9,12,\ldots\}
$$

---

# 5. Relationships Between Sets

## 5.1 Equality of Sets

Two sets are equal if they contain exactly the same elements.

Formally:

$$
X=Y
$$

if every element of $X$ belongs to $Y$, and every element of $Y$ belongs to $X$.

Therefore:

$$
X=Y
\iff
X\subseteq Y \text{ and } Y\subseteq X
$$

The order in which elements are written does not matter.

For example:

$$
\{1,2,3\}=\{3,2,1\}
$$

---

# 6. Subsets

Set $A$ is a subset of set $B$ if every element of $A$ is also an element of $B$.

Notation:

$$
A\subseteq B
$$

Example:

$$
A=\{1,2\}
$$

$$
B=\{1,2,3,4\}
$$

Then:

$$
A\subseteq B
$$

Every set is a subset of itself:

$$
A\subseteq A
$$

---

## 6.1 Proper Subset

$A$ is a proper subset of $B$ if:

$$
A\subseteq B
$$

and:

$$
A\neq B
$$

In other words, $B$ contains at least one element that is not in $A$.

Example:

$$
\{1,2\}\subset\{1,2,3\}
$$

---

## 6.2 Superset

If:

$$
A\subseteq B
$$

then $B$ is called a **superset** of $A$.

It may be written:

$$
B\supseteq A
$$

---

# 7. Cardinality

The **cardinality** of a finite set is the number of elements in the set.

It is denoted by:

$$
n(A)
$$

or equivalently:

$$
|A|
$$

Example:

$$
A=\{2,4,6,8\}
$$

Therefore:

$$
n(A)=4
$$

Repeated elements are counted only once.

For example:

$$
A=\{1,1,2,2,3\}
$$

has:

$$
n(A)=3
$$

---

# 8. Empty Set

A set containing no elements is called the **empty set**, **null set**, or **void set**.

Notation:

$$
\emptyset
$$

or:

$$
\{\}
$$

Example:

$$
A=\{x : x \text{ is an even integer and } x^2=9\}
$$

has no elements, so:

$$
A=\emptyset
$$

An important property is:

$$
\boxed{\emptyset\subseteq A}
$$

for every set $A$.

### Important distinction

$$
\emptyset
$$

and:

$$
\{\emptyset\}
$$

are different.

- $\emptyset$ has **zero elements**.
- $\{\emptyset\}$ has **one element**, namely $\emptyset$.

---

# 9. Power Set

The **power set** of $A$, denoted by $P(A)$, is the set of **all subsets of $A$**.

Example:

$$
A=\{1,2,3\}
$$

Then:

$$
P(A)=
\{
\emptyset,
\{1\},
\{2\},
\{3\},
\{1,2\},
\{1,3\},
\{2,3\},
\{1,2,3\}
\}
$$

Therefore:

$$
n(P(A))=8
$$

If:

$$
n(A)=n
$$

then:

$$
\boxed{n(P(A))=2^n}
$$

Two subsets are always present:

$$
\emptyset
$$

and:

$$
A
$$

---

# 10. Types of Sets

## 10.1 Empty Set

A set with no elements:

$$
\emptyset
$$

## 10.2 Singleton Set

A set containing exactly one element.

Example:

$$
A=\{2\}
$$

## 10.3 Finite Set

A set containing a finite number of elements.

Example:

$$
A=\{1,2,3,4\}
$$

## 10.4 Infinite Set

A set that is not finite.

Example:

$$
N=\{1,2,3,\ldots\}
$$

## 10.5 Equivalent Sets

Two finite sets are equivalent if they have the same number of elements.

$$
A\sim B
$$

if:

$$
n(A)=n(B)
$$

Equivalent sets need not contain the same elements.

## 10.6 Equal Sets

Two sets are equal only when they contain exactly the same elements.

Thus:

- **Equal sets** → same elements.
- **Equivalent sets** → same cardinality.

---

# 11. Hierarchy of Sets

Under the convention used in this IGNOU unit:

$$
N\subset W\subset Z\subset Q\subset R
$$

where:

- $N$ = Natural numbers
- $W$ = Whole numbers
- $Z$ = Integers
- $Q$ = Rational numbers
- $R$ = Real numbers

The inclusions are proper in this hierarchy.

---

# 12. Universal Set

A **universal set** is a set containing all the objects under consideration in a particular context.

It is commonly denoted by:

$$
U
$$

Every set being discussed is a subset of $U$:

$$
A\subseteq U
$$

The universal set depends on the context.

For example, if we are discussing students in a class, the universal set could be described in words as:

> $U$ = the set of all students in the class.

---

# 13. Venn Diagrams

A Venn diagram represents sets graphically.

The universal set is generally represented by a rectangle.

Individual sets are represented by closed curves or regions.

Venn diagrams can illustrate:

- subsets
- disjoint sets
- overlapping sets
- union
- intersection
- complements
- differences

The actual size of a region in a Venn diagram does not necessarily represent the number of elements in that set.

---

# 14. Set Operations

## 14.1 Union

The union of $A$ and $B$ is:

$$
A\cup B
$$

It contains all elements that belong to $A$, $B$, or both.

Example:

$$
A=\{1,2,3\}
$$

$$
B=\{3,4,5\}
$$

Then:

$$
A\cup B=\{1,2,3,4,5\}
$$

Think of union as **inclusive OR**.

---

## 14.2 Intersection

The intersection of $A$ and $B$ is:

$$
A\cap B
$$

It contains elements common to both sets.

Example:

$$
A\cap B=\{3\}
$$

If:

$$
A\cap B=\emptyset
$$

then $A$ and $B$ are called **disjoint sets**.

---

## 14.3 Complement

The complement of $A$, relative to universal set $U$, contains all elements of $U$ that are not in $A$.

It may be written:

$$
A^c
$$

and:

$$
A^c=U-A
$$

---

## 14.4 Difference

The difference $A-B$ consists of elements that are in $A$ but not in $B$.

$$
A-B=\{x : x\in A,\ x\notin B\}
$$

Similarly, $B-A$ contains elements in $B$ but not $A$.

---

## 14.5 Symmetric Difference

The symmetric difference is:

$$
A\triangle B=(A-B)\cup(B-A)
$$

It contains elements belonging to exactly one of the two sets.

Example:

$$
A=\{1,2,3,4\}
$$

$$
B=\{3,4,5,6,7\}
$$

Then:

$$
A\triangle B=\{1,2,5,6,7\}
$$

---

# 15. Important Laws of Sets

## 15.1 Idempotent Laws

$$
A\cup A=A
$$

$$
A\cap A=A
$$

---

## 15.2 Identity Laws

$$
A\cup\emptyset=A
$$

$$
A\cap U=A
$$

---

## 15.3 Commutative Laws

$$
A\cup B=B\cup A
$$

$$
A\cap B=B\cap A
$$

---

## 15.4 Associative Laws

$$
(A\cup B)\cup C=A\cup(B\cup C)
$$

$$
(A\cap B)\cap C=A\cap(B\cap C)
$$

---

## 15.5 Distributive Laws

$$
A\cup(B\cap C)
=
(A\cup B)\cap(A\cup C)
$$

and:

$$
A\cap(B\cup C)
=
(A\cap B)\cup(A\cap C)
$$

---

## 15.6 Complement Laws

$$
A\cup A^c=U
$$

$$
A\cap A^c=\emptyset
$$

---

# 16. De Morgan's Laws

The two De Morgan laws are:

$$
\boxed{(A\cup B)^c=A^c\cap B^c}
$$

and:

$$
\boxed{(A\cap B)^c=A^c\cup B^c}
$$

A useful way to remember them:

- Complement of **union** → intersection of complements.
- Complement of **intersection** → union of complements.

---

# 17. Duality Principle

The duality principle allows one set-theoretic statement to be transformed into its dual.

Use these substitutions:

$$
\cup\leftrightarrow\cap
$$

and:

$$
U\leftrightarrow\emptyset
$$

For example:

$$
A\cup B=B\cup A
$$

has the dual:

$$
A\cap B=B\cap A
$$

Another example:

$$
A\cup\emptyset=A
$$

has the dual:

$$
A\cap U=A
$$

The important point is to replace **every occurrence** of the relevant symbol.

---

# 18. Convex Set

A set $S$ is called **convex** if, for any two points $x_1,x_2\in S$, the entire line segment joining those points lies within $S$.

The mathematical condition given in the unit is:

$$
\lambda x_1+(1-\lambda)x_2\in S
$$

for:

$$
0<\lambda<1
$$

Intuitively:

> Pick any two points in a convex set. The straight line joining them must remain completely inside the set.

A filled circle is an example of a convex set.

---

# 19. Russell's Paradox

Russell's Paradox demonstrates a problem with unrestricted or naive set formation.

Consider:

$$
R=\{x:x\notin x\}
$$

In words:

> $R$ is the set of all sets that are not members of themselves.

Now ask:

$$
R\in R?
$$

If:

$$
R\in R
$$

then, by the definition of $R$, it must be true that:

$$
R\notin R
$$

Contradiction.

But if:

$$
R\notin R
$$

then $R$ satisfies the defining condition for membership in $R$, implying:

$$
R\in R
$$

Again, contradiction.

Thus:

$$
R\in R\iff R\notin R
$$

This is Russell's Paradox.

IGNOU also explains the idea using the **barber analogy**.

---

# 20. Intervals

An interval is a subset of the real numbers with the property that if two numbers belong to the interval, then all numbers between them also belong to it.

## 20.1 Open Interval

$$
(a,b)
$$

means:

$$
a<x<b
$$

Neither endpoint is included.

Example:

$$
(2,5)
$$

---

## 20.2 Closed Interval

$$
[a,b]
$$

means:

$$
a\leq x\leq b
$$

Both endpoints are included.

---

## 20.3 Half-Open Intervals

$$
(a,b]
$$

means:

$$
a<x\leq b
$$

while:

$$
[a,b)
$$

means:

$$
a\leq x<b
$$

### Memory rule

- Round bracket $( )$ → endpoint excluded.
- Square bracket $[ ]$ → endpoint included.

Infinity is not an actual real-number endpoint, so intervals extending to infinity use round brackets.

Example:

$$
(3,\infty)
$$

means:

$$
x>3
$$

---

# 21. Ordered Pairs

An ordered pair is written:

$$
(a,b)
$$

The order of elements matters.

In general:

$$
(a,b)\neq(b,a)
$$

when:

$$
a\neq b
$$

Two ordered pairs are equal if and only if their corresponding elements are equal:

$$
(a,b)=(c,d)
$$

if:

$$
a=c
$$

and:

$$
b=d
$$

---

# 22. Cartesian Product

The Cartesian product of $A$ and $B$ is denoted:

$$
A\times B
$$

It consists of all ordered pairs whose first element belongs to $A$ and whose second element belongs to $B$.

Example:

$$
A=\{1,2\}
$$

$$
B=\{a,b\}
$$

Then:

$$
A\times B=
\{(1,a),(1,b),(2,a),(2,b)\}
$$

If:

$$
n(A)=m
$$

and:

$$
n(B)=n
$$

then:

$$
\boxed{n(A\times B)=mn}
$$

---

## Cartesian Product Is Not Generally Commutative

In general:

$$
A\times B\neq B\times A
$$

because:

$$
(a,b)\neq(b,a)
$$

in general.

For example:

$$
\{1,2\}\times\{3,4\}
$$

contains:

$$
(1,3),(1,4),(2,3),(2,4)
$$

whereas:

$$
\{3,4\}\times\{1,2\}
$$

contains:

$$
(3,1),(3,2),(4,1),(4,2)
$$

---

## Cartesian Product with the Empty Set

$$
A\times\emptyset=\emptyset
$$

because there is no element available from the empty set to form an ordered pair.

---

# 23. Geometric Interpretation of Cartesian Products

Consider:

$$
\{2\}\times\mathbb R
$$

This gives all points:

$$
(2,y),\quad y\in\mathbb R
$$

Geometrically, this represents the vertical line:

$$
x=2
$$

Similarly:

$$
\mathbb R\times\{3\}
$$

gives:

$$
(x,3),\quad x\in\mathbb R
$$

which represents the horizontal line:

$$
y=3
$$

---

# 24. Tuples

An ordered pair is a **2-tuple**:

$$
(a,b)
$$

An ordered triple is a **3-tuple**:

$$
(a,b,c)
$$

More generally:

$$
(a_1,a_2,\ldots,a_n)
$$

is an **$n$-tuple**.

Cartesian products of more than two sets produce such $n$-tuples.

For example:

$$
A\times B\times C
$$

produces ordered triples:

$$
(a,b,c)
$$

---

# 25. Cardinality Formulas

For two finite sets:

$$
\boxed{
n(A\cup B)
=
n(A)+n(B)-n(A\cap B)
}
$$

The intersection is subtracted because its elements were counted twice.

Other useful formulas:

$$
\boxed{
n(A-B)=n(A)-n(A\cap B)
}
$$

$$
\boxed{
n(B-A)=n(B)-n(A\cap B)
}
$$

Also:

$$
\boxed{
n(A\cup B)
=
n(A-B)+n(A\cap B)+n(B-A)
}
$$

---

# 26. Inclusion–Exclusion for Three Sets

For three finite sets:

$$
\boxed{
\begin{aligned}
n(A\cup B\cup C)
={}&n(A)+n(B)+n(C)\\
&-n(A\cap B)-n(A\cap C)-n(B\cap C)\\
&+n(A\cap B\cap C)
\end{aligned}
}
$$

The pattern is:

$$
+\text{ individual sets}
$$

$$
-\text{ pairwise intersections}
$$

$$
+\text{ three-way intersection}
$$

The three-way intersection is added back because the preceding subtraction removes those elements too many times.

---

# 27. Example of Cardinality

Suppose:

$$
n(A)=50
$$

$$
n(B)=40
$$

and:

$$
n(A\cap B)=15
$$

Then:

$$
n(A\cup B)
=
50+40-15
$$

$$
=\boxed{75}
$$

Thus 75 elements belong to at least one of the two sets.

---

# 28. Key Concepts to Remember

### Set

A well-defined collection of distinct objects.

### Element

An individual object belonging to a set.

### Subset

Every element of $A$ is also an element of $B$:

$$
A\subseteq B
$$

### Proper subset

$$
A\subseteq B,\quad A\neq B
$$

### Cardinality

Number of elements in a finite set:

$$
n(A)
$$

### Empty set

$$
\emptyset
$$

### Power set

Set of all subsets:

$$
P(A)
$$

### Power-set cardinality

$$
n(P(A))=2^{n(A)}
$$

### Union

$$
A\cup B
$$

Elements in either set or both.

### Intersection

$$
A\cap B
$$

Elements common to both sets.

### Complement

$$
A^c
$$

Elements in $U$ but not in $A$.

### Difference

$$
A-B
$$

Elements in $A$ but not $B$.

### Cartesian product

$$
A\times B
$$

Set of ordered pairs.

---

# 29. Common Mistakes

## Mistake 1: Confusing element and subset

Incorrect:

$$
\{2\}\in\{1,2,3\}
$$

Correct:

$$
2\in\{1,2,3\}
$$

and:

$$
\{2\}\subseteq\{1,2,3\}
$$

---

## Mistake 2: Counting duplicates

$$
\{1,1,2,2,3\}
$$

has:

$$
n(A)=3
$$

not 5.

---

## Mistake 3: Thinking subset means proper subset

$$
A\subseteq A
$$

is always true.

But $A$ is **not** a proper subset of itself.

---

## Mistake 4: Forgetting the intersection in union cardinality

Wrong:

$$
n(A\cup B)=n(A)+n(B)
$$

Correct:

$$
n(A\cup B)
=
n(A)+n(B)-n(A\cap B)
$$

---

## Mistake 5: Treating Cartesian products as commutative

Generally:

$$
A\times B\neq B\times A
$$

because ordered pairs preserve order.

---

# 30. Data Science Connection

Set theory provides foundational ideas that appear throughout data science.

Examples include:

- membership testing
- filtering observations
- categorical groups
- database operations
- joins and intersections
- feature spaces
- sample spaces in probability
- classification into groups
- Cartesian products in combinatorics and feature construction

### Clinical example

Let $A$ represent the set of patients receiving Drug A.

Let $B$ represent the set of patients experiencing an ADR.

Then:

$$
A\cap B
$$

represents patients who are receiving Drug A **and** experiencing an ADR.

Similarly:

$$
A\cup B
$$

represents patients who are receiving Drug A, experiencing an ADR, or both.

> **Note:** This is a conceptual data-science/clinical connection and is not additional IGNOU course content.

---

# 31. Exam-Oriented Checklist

Before considering Unit 1 complete, I should be able to:

- [ ] Define a set.
- [ ] Explain "well-defined".
- [ ] Identify whether a collection is a set.
- [ ] Use $\in$ and $\notin$.
- [ ] Distinguish element from subset.
- [ ] Write sets using roster notation.
- [ ] Write sets using set-builder notation.
- [ ] Determine whether two sets are equal.
- [ ] Determine whether one set is a subset of another.
- [ ] Identify proper subsets and supersets.
- [ ] Calculate cardinality.
- [ ] Identify an empty set.
- [ ] Construct a power set.
- [ ] Calculate $n(P(A))$.
- [ ] Distinguish equal and equivalent sets.
- [ ] Explain the hierarchy $N\subset W\subset Z\subset Q\subset R$.
- [ ] Identify the universal set.
- [ ] Interpret Venn diagrams.
- [ ] Perform union and intersection.
- [ ] Find complements and differences.
- [ ] Calculate symmetric difference.
- [ ] Apply set laws.
- [ ] Apply De Morgan's laws.
- [ ] Apply the duality principle.
- [ ] Explain convex sets.
- [ ] Explain Russell's Paradox.
- [ ] Interpret open and closed intervals.
- [ ] Work with ordered pairs.
- [ ] Construct Cartesian products.
- [ ] Explain why Cartesian products are generally not commutative.
- [ ] Understand tuples.
- [ ] Apply cardinality and inclusion–exclusion formulas.

---

# 32. Source

**Primary source:**

IGNOU, MCS-061 Mathematical Foundations-I, Block 1, Unit 1 — Introduction to Sets.

This document is a study note derived from the IGNOU study material and is not a replacement for the official university material.
