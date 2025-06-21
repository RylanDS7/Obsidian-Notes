The Lagrangian is a quantity central to Lagrangian Mechanics that is defined for a system as the total kinetic energy minus the total potential energy, or

$$
\mathcal{L}=T-U
$$

The energies of the system must be defined in terms of a consistent set of [[Generalized Coordinates]] that fully define all degrees of freedom that the system has.

The equations of motion for the system can be determined using the Lagrangian via the [[Euler-Lagrange Equations]]. These equations can also be useful in determining the conserved quantities of a system.

We can find an equilibrium point of a system by finding where potential energy is minimized. After doing this, if we take our generalized coordinates to be the displacements from this system, we can make linear approximations for a complicated Lagrangian for small oscillations about the equilibrium points. These systems can reduce to a quadratic Lagrangian from which we can form a generalized eigenvalue problem. For a mass matrix $M$ and stiffness matrix $K$ we can find that the equations of motion for harmonic oscillators is

$$
M\ddot{x} = -Kx
$$

We can find solutions of a single frequency of the form $x(t) = Af(t)$ called normal modes. The vector $A$ is called the normal mode shape vector and describes how the generalized coordinates of the systems oscillate relative to each other. The solution of these frequencies is given by the square root of the eigenvalues solving the generalized eigenvalue problem

$$
\text{det}(\lambda M - K) = 0
$$

where the corresponding shape vectors are the eigenvectors.