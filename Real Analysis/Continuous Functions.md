Let $f: X \rightarrow Y$ be a single valued mapping between [[Hausdorff Topological Spaces]]. To say that $f$ is continuous of $X$ means
$$
\forall G \in \mathcal{T}_Y, \hspace{30px} f^{-1}(G) \in \mathcal{T}_X.
$$
In other words, "the preimage of an [[Open Sets]] is always open".

If you apply a continuous $f$ to a [[Compact Sets]] it will produce a compact set.

A set is said to be continuous at a point $x$ if every [[Neighborhoods]] of $f(x)$ has a preimage in the neighborhood of $x$.

For a function $f:X \rightarrow Y$ where $X,Y$ are [[Metric Spaces]] we have a sequential characterization that says the following are all equivalent:

(a) $f:X \rightarrow Y$ is continuous at $x$
(b) $\forall \varepsilon > 0, \ \exists \delta > 0 \ : \ \forall x'\in \mathbb{B}[x, \delta), \ d_Y(f(x'), f(x)) < \varepsilon$  
(c) For every sequence $(x_n)$ in $X$ obeying $x_n \rightarrow x$, one has $f(x_n) \rightarrow f(x)$ in Y

For metric spaces you can also define [[Uniform Continuity]] in a similar fashion.

By using the [[Butterfly Lemma]], we can show that if $f$ is differentiable at $a$, then it must also be continuous at $a$.