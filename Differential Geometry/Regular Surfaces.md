A subset $S \subset \mathbb{R}^3$ is a regular surface if, for each point $p \in S$, there exists a [[Neighborhoods]] $V$ in $\mathbb{R}^3$ and a map $\textbf{x}: U \rightarrow V$ of an open set $U \subset \mathbb{R}^2$ onto $V \cap S \subset  \mathbb{R}^3$ such that $\textbf{x}$ satisfies the following properties:

1. $\textbf{x}$ is differentiable, meaning$$
\textbf{x}(u,v) = \big(x(u,v), y(u,v), z(u,v)\big)
$$ has continuous partial derivatives of of all orders for all components.
2.  $\textbf{x}$ is a homeomorphism, meaning $\textbf{x}$ has a continuous inverse.
3. For each $q \in U$, the [[Differential]] $d\textbf{x}_q: \mathbb{R}^2 \rightarrow \mathbb{R}^3$ is one to one. (regularity condition)


This defines regular surfaces as a set of points such that all points of the surface can be locally given by a map which is fully continuous and differentiable.

We know that if $f : U \rightarrow \mathbb{R}^3$ is a differentiable function on an [[Open Sets]] U of $\mathbb{R}^2$, then the graph of $f$, given by the subset of $\mathbb{R}^3$ that is $(x, y, f(x,y))$ for $(x,y) \in U$, is always a regular surface.
The converse of this is locally true (not globally). For regular surface $S \in \mathbb{R}^3$ and $p \in S$, there exists a neighborhood $V$ of $p$ in $S$ such that $V$ is the graph of a differentiable function which has one of the following forms: $z = f(x,y)$, $y = g(x,z)$, $x = h(y,z)$.

We also know that if $f : U \subset \mathbb{R}^3 \rightarrow \mathbb{R}$  is a differentiable function and $a \in f(U)$ is a regular value of $f$, then $f^{-1}(a)$ is a regular surface in $\mathbb{R}^3$. These can be thought of as the "level curves" of $f$.

Another useful property is that for a regular surface with a parameterization satisfying properties 1 and 3, we can automatically conclude that $\textbf{x}^{-1}$ is continuous given we know that $\textbf{x}$ is one to one.