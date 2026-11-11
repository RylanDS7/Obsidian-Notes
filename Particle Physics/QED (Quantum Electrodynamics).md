QED is the formulation of the electromagnetic force as it pertains to the [[The Standard Model of Particle Physics]]. A proper derivation of the interactions in QED involves [[Quantum Field Theory]], but the formulation essentially describes the microscopic (quantum) picture of the classical [[Maxwell's Equations]]. In principle, interactions between charged particles in QED occurs via the exchange of a virtual photon.

To evaluate the matrix element (and ultimately the [[Interaction Cross Section]]) for a QED interaction, we need to sum over all possible time orderings of the [[Feynman Diagrams]] and also all the polarization states of the virtual photon. In practice, this calculation does not need to be repeated since we can use Feynman rules to evaluate the matrix element generic expression for a given diagram. These rules are as follows:

 - Each internal line (virtual photon) gets a propagator factor
 - Each external spin 1/2 particle gets a corresponding Dirac spinor (given by the solutions to the [[Dirac Equation]])
 - Each vertex gets a QED vertex factor. When multiplying the particle currents the adjoint spinor must be put first (outgoing particle or incoming anti-particle.

The product of all these factor assembled in the correct way will be equal to $-i \mathcal{M}$.

The process of getting a QED matrix element using these rules is:

1. Draw the [[Feynman Diagrams]] for the lowest order process and label the 4-momenta
2. Label each QED vertex with the factor $ie\gamma^\mu$ for spin 1/2 fermions with absolute charge $e$
3. Determine the propagator factor corresponding to each internal line:
	- For photon: $-\frac{ig_{\mu\nu}}{q^2}$ 
	- For fermion: $-\frac{i(\gamma^\mu q_\mu + m)}{q^2-m^2}$
4. Assemble the interaction currents on either side of the propagator with the adjoint spinor written first, then set the entire expression equal to $-i \mathcal{M}$
