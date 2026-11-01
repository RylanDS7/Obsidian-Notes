Let $F: U \subset \mathbb{R}^n \rightarrow \mathbb{R}^m$ be a differentiable map. For each $p \in U$ we have a linear map $dF_p: \mathbb{R}^n \rightarrow \mathbb{R}^m$ called the differential of $F$ at $p$ defined as follows:
Let $w \in \mathbb{R}^n$ and let $\alpha \in (-\varepsilon, \varepsilon) \rightarrow U$ be a differentiable curve such that $\alpha(0) = p$, $\alpha'(0) = w$. By the chain rule, the curve $\beta = F \circ \alpha : (-\varepsilon, \varepsilon) \rightarrow \mathbb{R}^m$ is also differentiable. Then,
$$
dF_p(w) = \beta'(0)
$$

This definition basically says that for a curve on a surface which passes through a given point and has a certain tangent vector, the evaluation of the differential of a function at that tangent vector is equal to the tangent vector of the curve resulting from a mapping of the original curve by the function.
When applied to surfaces, it takes vectors in a parameterization, to the vector in the tangent space of the surface which gives the direction of the change when moving the original direction in the parameterization space.
This leads to the conclusion that the differential is an operator which multiplies a vector by the [[Jacobian]] matrix of $F$ at $p$.


A related definition: $p \in U$ is a critical point of $F$ if the differential, $dF_p$ is not a surjective mapping. The image $F(p) \in \mathbb{R}^m$ of a critical point is a critical value of $F$. A point of $\mathbb{R}^m$ which is not a critical value is called a regular value of $F$.