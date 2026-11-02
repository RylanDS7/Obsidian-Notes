The [[Differential]], $dN_p : T_p(S) \rightarrow T_p(S)$ is a self-adjoint linear map, meaning $\langle dN_p(w_1), w_2\rangle = \langle w1, dN_p(w_2)\rangle$ which allows for the definition of a quadratic form $Q$ in $T_p(S)$, given by $Q = \langle dN_p(v), v\rangle$, $v \in T_p(S)$. This quadratic form is used to define the second fundamental form of $S$ at $p$ by
$$
\mathbf{II}_p(v) = -\langle dN_p(v), v\rangle
$$
For a curve $\alpha$ in $S$ passing through a point $p$ and tangent to a vector $v \in T_p(S)$ we can show that
$$
\mathbf{II}_p(\alpha'(0)) = k_n(p)
$$
where $k_n(p)$ is the [[Normal Curvature]] of the curve $\alpha$ at $p$.
This implies that the normal curvature of a curve is entirely dependent on it's tangent vector at $p$.

For a coordinate map with basis $\{\mathbf{x}_u, \mathbf{x}_v\}$ of $T_p(S)$ we can express tangent vector to the curve by $u'\mathbf{x}_u + v'\mathbf{x}_v$ which can be used to calculate the second fundamental form:
$$
\mathbf{II}_p(u'\mathbf{x}_u + v'\mathbf{x}_v) = -\langle dN_p(u'\mathbf{x}_u + v'\mathbf{x}_v), u'\mathbf{x}_u + v'\mathbf{x}_v\rangle = -\langle N_uu' + N_vv', u'\mathbf{x}_u + v'\mathbf{x}_v\rangle
$$
$$
\mathbf{II}_p(u'\mathbf{x}_u + v'\mathbf{x}_v) = e(u')^2+2fu'v' + g(v')^2
$$
where
$$
e = -\langle N_u, \mathbf{x}_{u} \rangle = \langle N, \mathbf{x}_{uu} \rangle
$$
$$
f = -\langle N_v, \mathbf{x}_{u} \rangle =  -\langle N_u, \mathbf{x}_{v} \rangle =\langle N, \mathbf{x}_{uv} \rangle
$$
$$
g = -\langle N_v, \mathbf{x}_{v} \rangle = \langle N, \mathbf{x}_{vv} \rangle
$$
similarly to the definition of the E,F,G parameters in the [[First Fundamental Form]].

In fact, if $N_u$ and $N_v$ are expressed in the $\{\mathbf{x}_u, \mathbf{x}_v\}$ basis as
$$
N_u = a_{11}\mathbf{x}_u + a_{12}\mathbf{x}_v
$$
$$
N_v = a_{21}\mathbf{x}_u + a_{22}\mathbf{x}_v
$$
then
$$
-f = a_{11}F + a_{21}G
$$
$$
-f = a_{12}E + a_{22}F
$$
$$
-e = a_{11}E + a_{21}F
$$
$$
-g = a_{12}F + a_{22}G
$$
Since the $a_{ij}$ values give the components of the matrix defining the [[Differential]] operator, we can use them to express equations for the [[Gaussian and Mean Curvature]] given our coordinate parameterization:
$$
K = det(a_{ij}) = \frac{eg-f^2}{EG-F^2}
$$
$$
H = - \frac{1}{2} (a_{11} + a_{22}) = \frac{1}{2}\frac{eG - 2fF+gE}{EG - F^2}
$$
