Modularity is a measure of the assortativity or disassortativity of edges in [networks](./network.md).


## Definition Using Divergence from the Configuration Model
Given a network of $m$ nodes, where node $i$ has degree $k_i$, modularity is defined as 

$$Q = \frac{1}{2m} \sum_{i \neq j} \bigg( A_{ij} - \frac{k_ik_j}{2m} \bigg)$$

The term inside the sum $(A_{ij} - \frac{k_i k_j}{2m})$ is used to determine the difference between the actual presence of an edge ($A_{ij}$) and the expectation of the edges existance as computed as the fraction of total edges in the network expected to be between $i$ and $j$ based on those nodes' degree: $\frac{k_ik_j}{2m}$.


## Definition Using Groups of Nodes

Let $U$ and $V$ be two groups of nodes $U$ and $V$ that do not overlap (i.e. $U \cap V = \varnothing$)

Let $e_{uv}$ be the proportion of realized edges between these two groups, 

$$e_{uv} = \frac{1}{2m} \sum_{i,j} A_{ij} \delta(i, U) \delta(j, V)$$

where $$\delta(i, S) = \begin{cases}1 \quad & i \in S \\ 0 & i \notin S\end{cases}$$