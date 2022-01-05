# Ch1. Solution

### 1.1

### Russell’s paradox:

$$A = \{x | x \notin x\},\\
A\in A \rightarrow A\notin A,\\ 
A \notin A \rightarrow A\in A $$
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





## 2.3

Prove that the inverse of a bijection is a bijection and that the composition of two bijections is a bijection



Assume $A \neq ∅$.  Let $f : A → B$ be a bijection, and $g: B \rightarrow A$ is the inverse of $f$.  

