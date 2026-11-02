The Gauss map of an [[Orientable Surfaces]] $S$ with orientation $N$ is defined as follows. 
The map $\hat{N} : S \rightarrow \mathbb{R}^3$ takes values in the unit sphere:
$$
S^2 = \{(x,y,z) \in \mathbb{R}^3; x^2 + y^2 + z^2 = 1\}
$$
We can identify this vector with the unit sphere so that the map $N : S \rightarrow S^2$ defines the Gauss Map of $S$.

The [[Differential]] of $N$ at $p \in S$ is a linear map from $T_p(S)$ to $T_{N(p)}(S^2)$. These tangent spaces are actually the same vector space so $dN_p$ must be a linear map on $T_p(S)$.
This means $dN_p : T_p(S) \rightarrow T_p(S)$ gives the rate of change (and direction of change) of the normal vector as you move in some direction in the [[Tangent Plane]]. This is equivalent to the scalar curvature ([[Curvature and Torsion]]) in the case of curves, but here it is a linear map.