The butterfly lemma compares the instantaneous slope of a function $f$ and it's derivative as per the [[Definition of Derivatives]].

For the following, define $\ell(x) = f(a) + m(x-a)$ to be the line of slope $m$ at $x=a$. 

$(i)$ If $m < f'(a)$, then there exists $\delta > 0$ such that
$$
\ell(x) > f(x), \ \forall x \in (a - \delta, a) \hspace{20px} \underline{\text{and}} \hspace{20px} \ell(x) < f(x), \ \forall x \in (a + \delta, a).
$$
$(ii)$ If $m > f'(a)$, then there exists $\delta > 0$ such that
$$
\ell(x) < f(x), \ \forall x \in (a - \delta, a) \hspace{20px} \underline{\text{and}} \hspace{20px} \ell(x) > f(x), \ \forall x \in (a + \delta, a).
$$
This means that the shaded region captured by lines of slope $f'(a) + \varepsilon$ and $f'(a) - \varepsilon$ must contain some part of $f(x)$ on either side of $a$ no matter how close you get to $a$.