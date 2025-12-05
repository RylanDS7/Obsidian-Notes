To say a sequence $(x_n)$ "converges to a limit $\hat{x}$" is defined by the following statement:

For all $\varepsilon > 0$, there exists $N\in \mathbb{N}$ such that for all $n > N$, $|x_n - \hat{x}| < \varepsilon$.

This definition intuitively implies that points of the sequence cluster infinitely close to the limit as you move infinitely far in the sequence.

Limits are unique, so if $x_n \rightarrow \hat{x}$ and $x_n \rightarrow \hat{z}$ then $\hat{x} = z$.

The squeeze theorem applies to limits so we know that if $(a_n) \rightarrow L$ and $(b_n) \rightarrow L$ and $\exists N \in \mathbb{N}$ such that $\forall n > N$, $a_n < x_n < b_n$ then $x_n \rightarrow L$.

Every convergent sequence in $\mathbb{R}$ is also a [[Cauchy Sequences]].