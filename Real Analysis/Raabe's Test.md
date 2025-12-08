An implementation of [[Kummer's Test]] for $D_k = k$.

Define the following value:
$$
R = \lim_{k\rightarrow\infty} k \bigg(\frac{a_k}{a_{k+1}}-1\bigg).
$$
If $R > 1$, then $S$ converges.
If $R < 1$, then $S$ diverges.

This test basically checks whether the ratio between subsequent elements approaches $1$ fast enough to "beat" the growth of $k$. If it doesn't, you know you've got a problem because $\sum_{k=1}^\infty\frac{1}{k}$ is a divergent [[p-Series]].