If $a_n \geq a_{n+1} \geq 0$ for all $n$, then the following are equivalent:
$$
S = \sum_{n=1}^\infty a_n < + \infty,
$$
$$
T = \sum_{k=0}^\infty2^ka_{2^k} < + \infty.
$$

This is actually a very awesome test. It implies that for a positive decreasing sequence, we can show convergence or divergence of the series by only looking at every $2^k$ elements, which is really quite a reduction.

An example of how good this is comes when you see how elegantly it can prove $S = \sum_n \frac{1}{n}$ diverges. For this case,
$$
T = \sum_{k=0}^\infty2^k \frac{1}{2^k} = \sum_{k=0}^\infty 1 = +\infty
$$
so we know $S$ diverges.

This test can also be used to easily prove the convergence regions for real valued [[p-Series]].