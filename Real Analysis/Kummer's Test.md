Kummer's test is essentially a generalization of the [[Ratio Test]] which is useful in some cases. It works for $S = \sum_{n=1}^\infty = a_n$ where $a_n > 0$ for all $n$. We let $(D_n)$ be any sequence of positive numbers and define
$$
\underline{L} = \liminf_{k\rightarrow\infty} \frac{D_ka_k - D_{k+1}a_{k+1}}{a_{k+1}}, \hspace{30px} \overline{L} = \limsup_{k\rightarrow\infty} \frac{D_ka_k - D_{k+1}a_{k+1}}{a_{k+1}}.
$$
If $\underline{L} > 0$, then $S$ converges.

If $\overline{L}<0$ and $\sum_{n=1}^\infty \frac{1}{D_n} = +\infty$, then $S$ diverges.

We can see that if $D_k = 1$ we recover the [[Ratio Test]].

To obtain the limiting case for this test, we take $D_k = k$ which leads to [[Raabe's Test]].