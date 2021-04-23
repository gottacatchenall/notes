Probability is tough to define.

Two main intepretations:
1. [Frequentist](./frequentist_statistics.md) interpretation: limit frequency of outcomes as the number of samples goes to $\infty$.
3. [Bayesian](./bayesian_statistics.md) interpretation: degree of belief that an outcome will occur.


Modern probability theory uses [measure theory](./measure_theory.md) defines a probability space as consisting of 3 things. 

1. Probability [Measure](./measure.md) $P$: assigns each item in $\mathbb{F}$ a value between $0$ and $1$, such that $$\int_{\Omega} P(x) dx = 1$$
2. Sample space $\Omega$: the set of possible [events](./statistical_event.md)
3. Event space/Filter $\mathbb{F}$: a [sigma-algebra](./sigma_algebra.md) of possible outcomes from the sample space. 


e.g. For flipping a coin, $\Omega =\{0,1\}$, $\mathbb{F} = \{\{0\}, \{1\}\}$, $P(e) = 0.5 \forall e \in \mathbb{F}$

