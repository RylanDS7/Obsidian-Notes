The Dirac Equation describes the wavefunctions of particles in relativistic quantum mechanics. It is written concisely using the Dirac gamma matrices and the 4 derivative as
$$
(i\gamma^\mu\partial_\mu-m)\psi = 0
$$
where
$$ \gamma^0 = \begin{pmatrix} I & 0 \\ 0 & -I \end{pmatrix}, \qquad \gamma^i = \begin{pmatrix} 0 & \sigma^i \\ -\sigma^i & 0 \end{pmatrix} 
$$ for the [[Pauli Matrices]] $\sigma^i$ defined as.
$$ \sigma^1 = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}, \qquad \sigma^2 = \begin{pmatrix} 0 & -i \\ i & 0 \end{pmatrix}, \qquad \sigma^3 = \begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}
$$ Writing out the gamma matrices explicitly:
$$ \gamma^0 = \begin{pmatrix} 1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & -1 & 0 \\ 0 & 0 & 0 & -1 \end{pmatrix}, \qquad \gamma^1 = \begin{pmatrix} 0 & 0 & 0 & 1 \\ 0 & 0 & 1 & 0 \\ 0 & -1 & 0 & 0 \\ -1 & 0 & 0 & 0 \end{pmatrix} 
$$ $$ 
\gamma^2 = \begin{pmatrix} 0 & 0 & 0 & -i \\ 0 & 0 & i & 0 \\ 0 & i & 0 & 0 \\ -i & 0 & 0 & 0 \end{pmatrix}, \qquad \gamma^3 = \begin{pmatrix} 0 & 0 & 1 & 0 \\ 0 & 0 & 0 & -1 \\ -1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \end{pmatrix} 
$$ 
For 2 gamma matrices with $\mu \neq \nu$, the matrices commute, otherwise they are related by the diagonals of the [[Minkowski Metric]] $g^{\mu\nu}$.
$$ \{\gamma^\mu, \gamma^\nu\} = 2g^{\mu\nu} I$$ 
Seen in another way, the adjoint gamma matrices are related in this way: 
$$ (\gamma^0)^\dagger = \gamma^0, \qquad (\gamma^i)^\dagger = -\gamma^i$$

The four linearly independent free particle solutions to the Dirac Equation take the form
$\psi_i = u_i(E, \vec{p})e^{i(\vec{p}\cdot \vec{r} - Et)}$ and are defined by the 4-vector of the particle to be

$$u_1(p) = \sqrt{E+m}\begin{pmatrix} 1 \\ 0 \\ \dfrac{p_z}{E+m} \\[8pt] \dfrac{p_x + i p_y}{E+m} \end{pmatrix}, \qquad u_2(p) = \sqrt{E+m}\begin{pmatrix} 0 \\ 1 \\ \dfrac{p_x - i p_y}{E+m} \\[8pt] \dfrac{-p_z}{E+m} \end{pmatrix}$$
$$
u_3(p) = \sqrt{E-m}\begin{pmatrix} \dfrac{p_z}{E-m} \\[8pt] \dfrac{p_x + i p_y}{E-m} \\[8pt] 1 \\ 0 \end{pmatrix},
\qquad
u_4(p) = \sqrt{E-m}\begin{pmatrix} \dfrac{p_x - i p_y}{E-m} \\[8pt] \dfrac{-p_z}{E-m} \\[8pt] 0 \\ 1 \end{pmatrix}
$$
For the particle solutions $u_3$ and $u_4$, the energies are negative quantities which is not directly physically interpretable. In the Feynman–Stückelberg interpretation, the negative energy particle spinors must propagate backwards in time, making them equivalent to positive energy anti-particles propagating forwards in time. This leads to the anti-particle spinors being found by reversing the sign of $E$ and $\vec{p}$ in the particle spinors to get
$$ v_1(p) = \sqrt{E+m}\begin{pmatrix} \dfrac{p_x - i p_y}{E+m} \\[8pt] \dfrac{-p_z}{E+m} \\[8pt] 0 \\ 1 \end{pmatrix}, \qquad v_2(p) = \sqrt{E+m}\begin{pmatrix} \dfrac{p_z}{E+m} \\[8pt] \dfrac{p_x + i p_y}{E+m} \\[8pt] 1 \\ 0 \end{pmatrix} $$
$$
v_3(p) = \sqrt{E-m}\begin{pmatrix} 1 \\ 0 \\ \dfrac{p_z}{E-m} \\[8pt] \dfrac{p_x + i p_y}{E-m} \end{pmatrix},
\qquad
v_4(p) = \sqrt{E-m}\begin{pmatrix} 0 \\ 1 \\ \dfrac{p_x - i p_y}{E-m} \\[8pt] \dfrac{-p_z}{E-m} \end{pmatrix}
$$
Where now $v_3$ and $v_4$ are negative energy solutions corresponding to particles if the direction of time is flipped.

This all leads to the positive energy spinors $u_1, u_2, v_1, v_2$ to form a practical basis, where the $u$ spinors represent particles and the $v$ spinors represent anti-particles.

If $p_x = p_y = 0$ then these spinors are eigenstates of the $S_z$ spin operator. In this spin basis, $u_1, v_1$ have spin up while $u_2, v_2$ have spin down. To determine a basis of eigenstates, we need to look to [[Helicity]] and [[Chirality]].

