A [[Regular Surfaces]] $S$ is called orientable if it is possible to cover it with a family of coordinate neighborhoods in such a way that if a point $p \in S$ belongs to two neighborhoods of this family, then the change of coordinates between them has positive [[Jacobian]] at $p$. The choice of such a family is called an orientation of $S$, and $S$ is called orientable if such a choice exists. Otherwise, the surface is non-orientable. 

This basically means that the orientation of the coordinate neighborhoods stays the same for overlapping neighborhoods, meaning it stays the same globally on a connected surface.

This is equivalent to saying that a regular surface is orientable if and only if there exists a differentiable field of unit normal vectors $N : S \rightarrow \mathbb{R}^3$. $N$ is typically defined for a parameterization as
$$
N(p) = \frac{\mathbf{x}_u \times \mathbf{x}_v}{|\mathbf{x}_u \times \mathbf{x}_v|}
$$

If a regular surface is given by $S = \{(x,y,z) \in \mathbb{R}^3 ; f(x,y,z) = a\}$ where $f : U \subset \mathbb{R}^3 \rightarrow \mathbb{R}$ is differentiable and $a$ is a regular value of $S$, then $S$ is orientable.