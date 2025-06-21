A magnetic scalar potential can be defined for a region where there are no external currents flowing in it and is somewhat analogous to the [[Electric Potential]] for electrostatics. In the case where external currents are present it is necessary to instead look at the [[Magnetic Vector Potential]].

The reason for this condition comes from the fact that the [[Magnetic Field Strength (H)]] needs to be curl-free for to form a magnetic scalar potential. This is because we define the magnetic scalar potential $\psi$ as the scalar field satisfying

$$
\vec{H} = -\nabla \psi
$$

which only exists when $\nabla \times \vec{H} = 0$. For the H field to be curl-free given a constant electric field we see from [[Ampere's Law]] that

$$
\nabla \times \vec{H} = \vec{J} = 0
$$

so the external current density must be zero.

Therefore, if a region has no external currents and no changing electric field then we can define the magnetic scalar potential field $\psi$, for which taking the negative gradient results in the H field. 

The important feature of $\psi$ appears when you visualize the equipotential planes in space. These planes will not intersect and the normal of the surface at every point gives the direction of the H field (by the definition of the gradient). This means that the equipotential planes can give a picture of how the H field evolves while being much simpler to solve mathematically. 

By [[Gauss's Law]] we know that $\nabla \cdot \vec{H} = 0$ and so $\nabla \cdot (-\nabla \psi) = 0$ which implies that

$$
{\nabla}^{2} \psi = 0
$$

so $\psi$ satisfies [[Laplace's Equation]]. This means that the magnetic scalar potential field can be fully solved given the necessary boundary conditions, and can then be used to find the H field.

Another interesting usage for the magnetic scalar potential is to help generate the coil windings that will produce a desired magnetic field for a fixed winding surface. This can be done by starting with the desired H field and finding a corresponding $\psi$ field (which will not be unique). After this is done the equipotential planes of the $\psi$ field can be plotted and used to find the locations the wires should be placed at. It turns out that the ideal place to wind the wires to get the desired magnetic field is along the intersection of the equipotential planes and the winding surface. This is somewhat analogous to the electrostatics case where conductors are always equipotential in the electric potential. For the current electrodynamics problem, the wires lie in a discrete set of equipotential planes of the magnetic scalar potential, which approximately produces a $\psi$ field that will induce the desired H field. 

The accuracy of this method will increase with the density of wires used (a continuous surface current would theoretically produce the desired field perfectly). Since discrete wires are necessary to actually manufacture a coil, a tradeoff needs to made between more precise, finer wires at lower currents and larger less accurate wires at higher currents.