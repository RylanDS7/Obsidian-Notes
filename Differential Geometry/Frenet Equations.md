The Frenet equations are a set of [[Ordinary Differential Equations]] which associate the derivatives of a unit basis in $\mathbb{R}^3$ for a [[Curves Parameterized by Arc Length]] where [[Curvature and Torsion]] are given by $k(s)$ and $\tau(s)$. For $\tau(s)$ to be defined locally we require $k(s) \neq 0$. The equations are given by
$$
t' = kn
$$
$$
n' = -kt -\tau b
$$
$$
b' =\tau n
$$
with a matrix formulation
$$
\begin{bmatrix} t \\ n \\ b \end{bmatrix}' = \begin{bmatrix} 0 & k & 0 \\ -k & 0 & -\tau \\ 0 & \tau & 0 \end{bmatrix}\begin{bmatrix} t \\ n \\ b \end{bmatrix}
$$
These equations define how the tangent and binormal change in the direction of the normal according to the [[Curvature and Torsion]] parameters.

The $nb$ plane is called the normal plane and the $tb$ plane is called the rectifying plane which tips according to the torsion or the curvature.