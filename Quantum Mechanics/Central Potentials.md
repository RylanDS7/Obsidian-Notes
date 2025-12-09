For a central potential you can express the [[Schrödinger Equation]] in spherical coordinates and pick up [[Angular Momentum (Quantum)]] term:
$$
\bigg(\frac{\partial}{\partial r}\bigg(r^2 \frac{\partial}{\partial r}\bigg) - \frac{2mr^2}{\hbar^2}\big(V(r) - E\big)\bigg)\psi(r, \theta, \phi) = \frac{1}{\hbar^2}\hat{L}^2 \psi(r, \theta, \phi)
$$
This can be solved by separating the radial and orbital solutions so $\psi(r, \theta, \phi) = R(r)Y(\theta, \phi)$.

The two equations for $R(r)$ and $Y(\theta, \phi)$ are coupled, but $R(r)$ has 1 degree of freedom and $Y(\theta, \phi)$ has 2. Specifying either one fully placing constraints on the other but it is arbitrary which is solved first, so we can consider the radial solution when angular momentum is 0.

The solutions to this are essentially the [[Infinite Square Well]] adapted to spherical coordinates so that $u(r) = R(r)r$ is the variable that solves the equation. The radial [[Wavefunctions]] for $\hat{L}=0$ are then just the infinite square well sinusoids divided by $r$.

