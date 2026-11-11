A particle decay rate, $\Gamma$, defines the exponential decay rate of a population of that particle, 
$N(t) = N(0)e^{-\Gamma t}$ . Thus, the mean lifetime for the particle is defined as $\tau = 1/ \Gamma$. Since there are multiple decay pathways, the total decay rate is given by the sum of all the decay rates of each decay channel. This leads to the definition of the branching ratio of a specific decay path which is defined as the fraction of particles decaying through this channel:
$$
BR_i = \frac{\Gamma_i}{\Gamma_{tot}}
$$
To calculate the state transition rate (or particle decay rate) we use [[Fermi's Golden Rule]]. For particle decays, the matrix element for the interaction is still dependent on the [[Phase Space]], since the initial particle can have initial momentum. If we integrate over the phase space for a general 2 body decay with final momentum $\vec{p^*}$ we get
$$
\Gamma = \frac{|\vec{p^*}|}{32\pi^2m_i^2}\int|\mathcal{M}_{fi}|^2 d\Omega
$$
and if we go to the center of mass frame, with an unpolarized population, the matrix element is independent of phase space so we get
$$
\Gamma = \frac{S}{8\pi m_i^2}|\vec{p^*}||\mathcal{M}_{fi}|^2
$$
since the integration over all solid angles is $4\pi$. Here $S$ is a symmetry factor which is $1$ if both decay particles are different, and $1/2!$ if they are the same, to avoid double counting the phase space.
If the daughter particles are massless (or very light), we can work in the center of mass frame to see that $|\vec{p^*}| = E_f = E_i/2 = m_i/2$ so the decay rate in this case is
$$
\Gamma = \frac{S}{16\pi m_i}|\mathcal{M}_{fi}|^2
$$