A $\sigma$-[algebra](algebra.md) is a [mathematical](mathematics.md) structure which describes a set of objects $x$ within a larger superset $X$ where $x_i \cap x_j = \varnothing$ for all $i,j$, and $x_i \cup x_j$  is $X$. 

This is a very unintuitive definition to say that if you have a set of items, like 
$A = \{A, B, C \}$, any combination of objects the subdivides that total set into subsets where no item is duplicated, e.g. $\{ \{A\}, \{B\}, \{C\} \}$, or $\{\{A,B\}, \{C\}\}$, or $\{\{A\}, \{B, C\}\}$, is a $\sigma$-algebra on set $A$.

The $\sigma$-algebra has much use in the context of [probability theory](probability.md). Under [Kolmogorov's axioms of probability](probability.md) one of the three structures needed to define a probability space is a $\sigma$-algebra which filters the [sample space](sample_space.md) down to a set of feasible events which are mutually exclusive and have total probability $1$. 