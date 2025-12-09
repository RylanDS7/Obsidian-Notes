The Hamiltonian is an observable central to Hamiltonian Mechanics which is derived from [[The Lagrangian]]. For a set of [[Generalized Coordinates]] $\vec{q}$ with conjugate momenta $\vec{p}$ we define the Hamiltonian as

$$
H(\vec{q},\vec{p}) = \sum_{i}p_i\dot{q}_i - \mathcal{L}
$$

It is important that the Hamiltonian be expressed in terms of generalized coordinates and conjugate momenta instead of generalized coordinates and velocities like it's counterpart the Lagrangian. 

It can be shown that the Hamiltonian is the [[Legendre Transform]] of the Lagrangian.

In many cases (but not all) the Hamiltonian is equal to the total energy in the system, meaning

$$
H = T + U
$$

This will always be the case if the Lagrangian is quadratic in velocities.

We can derive the Hamiltonian Equations which are analogous to the [[Euler-Lagrange Equations]] in Lagrangian mechanics. The equations state that

$$
\dot{q}_i = \frac{\partial H}{\partial p_i} \qquad \qquad \dot{p}_i =-\frac{\partial H}{\partial q_i}
$$

The significance of this is that for $n$ generalized coordinates we have $2n$ first order equations of motion instead of the $n$ second order equations of motion we get from Lagrangian Mechanics. 

Another useful property of using the Hamiltonian is that the generalized coordinates and conjugate momenta hold a kind of symmetry and we can use geometric relationships on Phase Space to better understand the physical system we are studying. An example of how this can be useful can be found in [[Noether's Theorem]]. 

Much of Hamiltonian mechanics can be expressed with [[Poisson Brackets]] to reveal further symmetries. For example, the Hamiltonian equations of motion can be rewritten as

$$
\dot{q}_i = \{q_i, H\} \qquad \qquad \dot{p}_i = \{p_i,H\}
$$

so we can see that expressing the these equations using Poisson brackets inherently takes care of the negative sign.

Furthermore, if we want to see how some observable $A$ evolves with time, we just need take it's Poisson bracket with the Hamiltonian:

$$
\frac{d}{dt}A(\vec{q}, \vec{p}, t) = \{A,H\} +\frac{\partial A}{\partial t}
$$

If the observable has no explicit time dependence then

$$
\frac{d}{dt}A = \{A,H\}
$$

The Hamiltonian can be expressed as an [[Operators]] which results in [[The Hamiltonian Operator]].