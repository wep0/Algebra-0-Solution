# Ch1. Solution

### 1.1

### Russell’s paradox:

$ A = \{x | x \notin x\},$
$ A\in A \rightarrow A\notin A $
$ A \notin A \rightarrow A\in A $
and they are contradicted.

### 1.2

**Known**: $\sim$ is a equivalence relation on the set $S$ 

By the definition, $\sim$ has the properties of reflexivity, symmetry, and transitivity.

**nonempty**: By the property of reflexivity, $\forall s \in S, s \sim s$, thus $\forall p \in P_{\sim}$, $\exist a \in p, a \in S, a \sim a$, therefore $|p| \ge 1$.

**disjoint**: Suppose there exists two elements $a,b,\ a \in S, b \in S$ and $a \nsim b$. 
If there's one element $x$, suppose $x \in [a]_{\sim},\ x \in [b]_{\sim}$, we know $x\sim a$ and $x\sim b$. 
based on transitivity of $\sim$, $x\sim a, x\sim b \rightarrow a \sim b$, which is contradicted to $a \nsim b$. Thus, it is disjoint.

**Their union is S**: Based on previous proof, because of the reflexivity of $\sim$, $\forall x \in S, \exists! p \in P_{\sim}, x \in p$, also known $p$ are disjoint, we could get $\bigcup_{i \in I}x_i = \bigcup_{i \in I'}p_i = S$.

### 1.3

Consider $a \sim b$ means: $a \in S, b \in S$,  $p \in \mathscr{P}, a \in p, b \in p$  

### 1.4

There are 5 different equivalence relations:  $\mathscr{P} \in \{(1, 2, 3)\}, \{(1, 2), (3)\}\}, \{(1 ), (2, 3)\}\} ,\{(1,3), (2)\}\}, \{(1),(2), (3)\}\} \}$

### 1.5

Consider $a \sim b$ means:  $|a - b| \le q, q>0$

### 1.6

Proof:

$a \sim b$ on $R$ $\rightarrow b-a \in Z$

**reflexivity**:

$a \sim a \rightarrow a - a = 0 \in Z$

**symmetry:** 

$a \sim b \rightarrow a - b \in Z$ 

$b \sim a \rightarrow b - a = -(a-b) \in Z$ 

**transitivity:**

$a \sim b \rightarrow a - b \in Z$ 

$b \sim c \rightarrow b - c \in Z$ 

$a \sim c \rightarrow a - c = (a + b) + (b-c) \in Z$ 

$R / ∼$:  For each $p \in R/\sim, b - a \in Z, a, b \in p$, which means for every equivalence class $p$  of $\sim$ on $R$, every two elements in $p$ have the exactly same fraction part.

$(a_1, a_2)≈(b_1, b_2), (a_1, a_2),(b_1, b_2) \in R × R$:  $a_1 \sim b_1, a_2 \sim b_2$

## 2.2

Assume A != ∅, and let f : A → B be a function. Then 

(2) f has a right-inverse if and only if it is surjective

Assume the right-inverse of $f$ is $g: B \rightarrow A$.  If $f: A \rightarrow B$ is not surjective, the image of $f$ is a subset of $B$ , called $B'$, instead of $B$.  We get $g(b'): B' \rightarrow A', b' \in B'$, and $A'$ is a subset of $A$ as well.  So, there must exist $b' \notin B', b' \in B$.  And $b'$ is not in the domain of $g$.

## 2.3.

Prove that the inverse of a bijection is a bijection and that the composition

of two bijections is a bijection.

1. Assume $f: A \rightarrow B $ is a bijection, and it has an inverse $g: B \rightarrow A$.
   
   Suppose $g$ is not bijection, and $g$ is not surjective or not injective. So, by Proposition 2.1, $g$ could not be a left-inverse or a right-inverse of $f$. However, because $f$ is bijective, it has both a left-inverse: $g \circ f = id_A$ and $f \circ g = id_B $, which is contradicted.  So, $g$ is a bijection.

2. Assume $f: A \rightarrow B$ is a bijection, and $g: B \rightarrow C$ is a bijection. We want to prove $q = g \circ f$ is a bijection.
   
   **Lemma 1.1**: $q$ is surjective $\Rightarrow \forall a \in A, \exist c \in C, q(a) = c$
   
   (Known: $f, g$ are surjective)
   
   Since $f$ is surjective: $\forall b \in B, \exist a \in A, f(a) = b$
   
   Since $g$ is surjective: $\forall c \in C, \exist b \in B, g(b) = c$
   
   $\implies \forall c \in C, \exist a \in A, g(f(a)) = c$
   
   $\implies \forall c \in C, \exist a \in A, q(a) = c$
   
   **Lemma 1.2**: $q$ is injective 
   
   $a' \neq a'' \implies q(a') \neq q(a'')$ 
   
   $\implies g(f(a')) \neq g(f(a''))$
   
   Since $f$ is injective:
   
   $a' \neq a'' \implies f(a') \neq f(a'')$
   
   Since $g$ is injective:
   
   $f(a') \neq f(a'') \implies g(f(a')) \neq g(f(a'')$
   
   Thus,
   
   $a' \neq a'' \implies g(f(a')) \neq g(f(a'')$
   
   With *Lemma 1.1* and *Lemma 1.2*, we know $q$ is bijective.

## 2.4

Prove that ‘isomorphism’ is an equivalence relation (on any set of sets).

Assume that $A, B$ are isomorphic sets, or $A \rightarrow B$ is a bijection. If its an equivalence relation we want to prove:

**reflexivity**： $A \rightarrow A$ is a bijection.

**symmetry**:    $A \rightarrow B$ is a bijection, proved in *Question 2.2*, its inverse $B \rightarrow A$ is also a bijection.

**transitivity**:   As proved in *question 2.3*, $A \rightarrow B$ is a bijection,  $B \rightarrow C$ is a bijection, their composition $A \rightarrow B \rightarrow C \implies A \rightarrow C$  is a bijection as well.

        

## 2.5

Suppose a function $f: A \rightarrow A'$ is epimorphism:

For all sets $Z$ and all functions $a': Z\rightarrow A'$

$\exist a: Z\rightarrow A, f \circ a = a'$

*Proposition: A function is surjective iff it is a epimorphism.*

**Proof**:

Suppose a function $f: A \rightarrow A'$ is surjective, assume $z \in Z$.

$\exist a(z) \in A, f \circ a(z) = a'(z)$

$\implies f(a(z)) = a'(z), a'(z) \in A'$

$\implies f(x) = y, y \in A'$

## 2.6

With notation as in Example 2.4, explain how any function $f : A → B$
determines a section of $π_A$.

Suppose $ a\in A, A \times B = (a, f(a))$

$\pi_A = A\times B \rightarrow A = A\times (A \rightarrow B)(A) \rightarrow A$

Construct a $g$ that makes $g \circ \pi_A = f$.

## 2.7

Let $f : A → B $ be any function. Prove that the graph $Γ_f$ of $f$ is isomorphic
to$ A$.

$Γ_A = \{(a,b) \in A \times B | b=f(a) \}\subseteq A \times B$

**Surjective**: $ Γ_A = \{(a,b) \in A \times B | b=f(a) \}\subseteq A \times B$

$\implies Γ_A = (a, f(a))$

$\forall f: A \rightarrow B, \exist a \in A,\exist b = f(a)\implies \exist Γ_A = (a, f(a))$

**Injective**:  

Prove: $f \neq f' \implies Γ_A \neq Γ_A'$

$Γ_A = {(a,f(a)) \subseteq \ A \times B }$

$Γ_A' = {(a,f'(a)) \subseteq A \times B}$

$f \neq f' \implies \exist a \in A, f(a) \neq f'(a)$

$\implies \exist a \in A, (a,f(a)) \neq (a,f'(a))$

$\implies Γ_A \neq Γ_A'$

With subjectivity and injectivity, $Γ_A$ is isomorphic.

## 2.8



## 2.9

We want to show $A' \cup B' \cong A'' \cup B'' \implies u: A'\cup B' \rightarrow A'' \cup B''$ is bijective.

Known: $f: A' \rightarrow A'', g: B' \rightarrow B''$ are bijective.

Since $A' \cap B' = \empty, A'' \cap B'' = \empty$

$\implies \forall a' \in A', b' \in B' ,\ a' \notin B', b' \notin A' $



$\forall y \in A'', y \notin B'', \exist x \in A', f(x) = y$

$\forall y' \in B'', y \notin A'', \exist x' \in B', g(x') = y'$

$\implies \forall y \in A'' \cup B'', \exist x \in A' \cup B', u(x)=y$, and it is surjective.



$x', x'' \in A' \cup B', u(x') \neq u(x'') \implies x' \neq x''$

Since $A' \cap B' = \empty$, for each $x \in A' \cup B'$, there are only two circustances:

When $x \in A', x \notin B'$:

$f: A' \rightarrow A''$ is injective, so $u$ is injectivein this circumstance. 

When $x \notin A', x \in B'$:

$g: B' \rightarrow B''$ is injective, so $u$ is injective in this circumstance.

so, $u: A' \cup B' \rightarrow A'' \cup B''$ is injective.

In conclusion, it is bijective.



## 2.10

Show that if $A$ and $B$ are finite sets, then $|B^A| = |B|^{|A|}$

   
