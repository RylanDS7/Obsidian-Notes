These quantities characterize the [[Supremum and Infimum]] for tail subsets of a real valued sequence as the indices go to infinity. The formal definitions are
$$
\limsup_{n\rightarrow\infty} x_n = \inf_{n \in \mathbb{N}} \bigg[\sup_{k \geq n} x_k\bigg], \hspace{30px} \liminf_{n\rightarrow\infty} x_n = \sup_{n \in \mathbb{N}} \bigg[\inf_{k \geq n} x_k\bigg].
$$
Limiting operations always respect non-strict inequalities, so if you have $y_n > x_n$ then you know
$$
\limsup_{n\rightarrow\infty} y_n \geq \limsup_{n\rightarrow\infty} x_n, \hspace{30px} \liminf_{n\rightarrow\infty} y_n \geq \liminf_{n\rightarrow\infty} x_n.
$$
Notice the above are not strict inequalities.

There is a connection to the [[Formal Definition of Limits]] where $x_n \rightarrow L$ if and only if $\liminf_{n\rightarrow\infty} x_n = L = \limsup_{n\rightarrow\infty} x_n$ .

By the [[Bolzano-Weirstrauss Theorem]] we know that each bounded sequence must contain a subsequence which converges to the limsup and liminf of the original sequence.