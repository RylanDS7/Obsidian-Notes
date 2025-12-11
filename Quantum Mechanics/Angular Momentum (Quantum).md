Angular momentum quantum mechanical states require two quantum numbers to be fully specified, one for $L^2$ and one for $L_z$ (or any other component but $z$ is conventional).

The formalism for quantum mechanical angular momentum comes from [[Ladder Operators]] that raise and lower $m$, the quantum number corresponding to $L_z$, but do not change $\ell$, the quantum number corresponding to $L^2$.

These operators have the following [[Eigenvalues]]:
$$
\hat{L}_+ \ |\ell, m \rangle = \hbar \sqrt{(\ell - m) (\ell + m + 1)} \ |\ell, m+1 \rangle
$$
$$
\hat{L}_- \ |\ell, m \rangle = \hbar \sqrt{(\ell + m) (\ell - m + 1)} \ |\ell, m-1 \rangle
$$
We can see that $m$ can range from $-\ell$ to $\ell$ in integer steps.

In this formalism, when adding multiple angular momentum states (such as a physical angular momentum and spin vector) we need to use the Clebsch-Gordon coefficients to switch to the basis of the added states. This process can result in the states of two particles becoming [[Entangled States]].