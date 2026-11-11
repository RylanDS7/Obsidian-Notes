Feynman diagrams provide a way to visualization interaction in [[The Standard Model of Particle Physics]] by showing fundamental forces as gauge [[Bosons]] using interaction vertices. The vertices associated with each force are shown here:

![[Pasted image 20261110124808.png]]

For a given interaction, there are usually infinite Feynman Diagrams that can be made to represent it. However, the probability of a certain interaction path actually occurring is determined by the number of interaction vertices and the coupling constant associated with the interacting force carrier. To get the total probability of an interaction occurring, you need to sum up all the possible interaction pathway probabilities, but since $\alpha << 1$ usually, only taking the first order diagram (with the least possible interactions) is typically a good approximation. 

In a Feynman Diagram, all intermediate particles can be considered "virtual" in the sense that they are not observable. This means that it is possible for these particles to exist "off mass shell" which means that $E^2 \neq |\vec{p}|^2 + m^2$ is allowed.

Feynman Diagrams can be "space-like" which is called the t-channel. This happens when the momentum transfer four vector magnitude $q^2 = (p_1 - p_3)^2 < 0$ meaning $(\vec{p_1}-\vec{p_1})^2 > (E_1 - E_3)^2$ so the momentum transferred is more than the energy transferred.
The opposite, "time-like" diagrams, called s-channel, occurs when $q^2 > 0$ so the momentum transferred is less than the energy transferred, which is usually a decay interaction.

![[Pasted image 20261110130636.png]]

There is also the u-channel which is a spatial reordering of the t-channel.

This naming scheme is tied to the Mandelstam Variables:
$$
s = (p_1 + p_2)^2 = (p_3 + p_4)^2 \\
t = (p_1 - p_3)^2 = (p_4 - p_2)^2 \\
u = (p_1 - p_4)^2 = (p_3 - p_2)^2
$$
Since the momentum will cancel in the center of mass frame, the total energy of the interaction in this frame is always given by $\sqrt{s}$.

In a Feynman Diagram, the following should be conserved at each vertex:
- 4-momenta
- Electric charge
- Baryon number (total number of quarks minus anti-quarks)
- Lepton number for each generation (total number of lepton minus anti-lepton)
- Angular momentum and spin

