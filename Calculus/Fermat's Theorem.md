For $X \subseteq \mathbb{R}$ and $f : X \rightarrow \mathbb{R}$ has a local minimum at some point $a \in X^o$ (a is in the [[Set Interior]] of $X$), then either:

$(i)$ $f'(a)$ does not exist (singular point)
$(ii)$ $f'(a)$ = 0 (critical point)

This is the principle that is often used to apply [[Definition of Derivatives]] in optimizing a function.

This leads into the important corollary that if $X$ is [[Compact Sets]] and $f$ is a [[Continuous Functions]], then both of the below sets are nonempty:
$$
\text{arg}\min_{X}f = \{a \in X \ : \ \forall x \in X, \ f(a) \leq f(x)\},
$$
$$
\text{arg}\max_{X}f = \{a \in X \ : \ \forall x \in X, \ f(a) \geq f(x)\}.
$$
Also, both of the above are subsets of
$$
\partial X \cup \{x \in X^o \ : \ f'(x) = 0\} \ cup \{x \in X^o \ : \ f'(x) \text{ DNE}\}.
$$
That is to say, the argmax and argmin values are either [[Boundary Points]], critical points, or singular points.