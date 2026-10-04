For a [[Curves Parameterized by Arc Length]], $\alpha(s)$ the curvature at $s$ is given by
$$
k(s) = |\alpha''(s)|
$$
which represents the rate of change of the tangent vector direction.

A unit vector $n(s)$ in the direction of $k(s)$ is called the normal vector at $s$. The unit tangent and normal vector span the osculating plane.

The binormal vector is $b(s) = t(s) \times n(s)$ so it is normal to the osculating plane. $b(s)$ is a unit vector so $|b'(s)|$ represents how quickly the curve pulls away from the osculating plane at $s$. $b'(s)$ is parallel to $n(s)$ as it represents the "tipping" of the binormal vector towards or away from the osculating plane. This motivates the definition of torsion $\tau(s)$
$$
b'(s) = \tau(s)n(s)
$$
so that torsion is in the direction of the normal with magnitude given by $|b'(s)|$.

These quantities are all related by the [[Frenet Equations]].