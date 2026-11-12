The chirality of a particle determines whether it transforms in a right or left handed way. In general, the chirality eigenstates are **not** equal to the [[Helicity]] eigenstates, although in the relativistic limit, $E >> m$ they are the same. The chirality operator is defined using the gamma matrices from the [[Dirac Equation]] as
$$
\gamma^5 = i\gamma^0\gamma^1\gamma^2\gamma^3\gamma^4 = \begin{pmatrix} 0 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \\ 1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \end{pmatrix} = \begin{pmatrix} 0 & I \\ I & 0 \end{pmatrix}
$$
So the right and left handed chiral eigenstates are given by
$$
\gamma^5u_R=u_R, \qquad \gamma^5u_L=-u_L, \qquad \gamma^5v_R=-v_R, \qquad \gamma^5v_L=v_L
$$
meaning the righthanded particles are positive eigenstates and lefthanded antiparticles are positive eigenstates.
In the limit $E >> m$, these eigenstates equal the helicity eigenstates, so
$$
u_R = u_\uparrow, \qquad u_L = u_\downarrow, \qquad v_R = v_\uparrow, \qquad v_L = v_\downarrow
$$
We can define chiral projection operators by
$$
P_R = \frac{1}{2}(1+\gamma^5), \qquad P_L = \frac{1}{2}(1-\gamma^5)
$$
which project out the right and left chiral eigenstates. These can be used to decompose any helicity spinor into it's left and right chiral parts.