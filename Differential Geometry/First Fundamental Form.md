The first fundamental form of a [[Regular Surfaces]] $S \subset \mathbb{R}^3$ at $p \in S$ is given by the quadratic form    $\mathbf{I}_p : T_p(S) \rightarrow \mathbb{R}$ on the [[Tangent Plane]] $T_p(S)$, defined as
$$
\mathbf{I}_p(w) = \langle w, w\rangle_p = |w|^2 \geq 0
$$
This defines how the surface $S$ inherits the inner product in $\mathbb{R}^3$.

A tangent vector $w \in T_p(S)$ can be expressed as $\alpha'(0)$ where $\alpha(t) = \mathbf{x}(u(t), v(t))$, $t \in (-\varepsilon, \varepsilon)$ is a [[Regularly Parameterized Curve]] with $p = \alpha(0) = \mathbf{x}(u_0, v_0)$. This leads to

$$
\mathbf{I}_p(\alpha'(0)) = \langle \mathbf{x}_u u' + \mathbf{x}_v v', \mathbf{x}_u u' + \mathbf{x}_v v'\rangle_p
$$
$$
\mathbf{I}_p(\alpha'(0)) = (u')^2\langle \mathbf{x}_u, \mathbf{x}_u \rangle_p + 2u'v'\langle \mathbf{x}_u, \mathbf{x}_v \rangle_p + (v')^2\langle \mathbf{x}_v, \mathbf{x}_v \rangle_p
$$
$$
\mathbf{I}_p(\alpha'(0)) = E(u')^2 + 2Fu'v' + G(v')^2
$$
So $E, F, G$ are the coefficients of the first fundamental form in the $\{\mathbf{x}_u, \mathbf{x}_v \}$ basis of $T_p(S)$.

This means an element of arc length $ds$ of $S$ can be written as
$$
ds^2 = Edu^2 + 2Fdudv + Gdv^2
$$
