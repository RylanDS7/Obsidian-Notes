The CR equations are a set of two partial differential equations that guarantee that a complex function is complex differentiable if they are satisfied. The equations are

$$
\frac{\partial u}{\partial x} = \frac{\partial v}{\partial y} \qquad \qquad \frac{\partial u}{\partial y} = -\frac{\partial v}{\partial x}
$$

where $u(x,y)$ is the real part of a complex function and $v(x,y)$ is the imaginary part of a complex function. In other words, for $z = x +iy$, both $u$ and $v$ are real functions and 

$$
f(z) = u(z) + iv(z)
$$

If these equations are satisfied by a function $f$, we know that $f$ is complex differentiable. We say that $f$ is holomorphic on a domain where the CR equations are satisfied. By [[Cauchy's Theorem]] we know that such functions are infinitely complex differentiable.

The CR equations can be rewritten using vector notation as follows:

$$
\begin{pmatrix} \partial_x u \\ \partial_y u \end{pmatrix} =
\begin{pmatrix} 0 & 1 \\ -1 & 0 \end{pmatrix}
\begin{pmatrix} \partial_x v \\ \partial_y v \end{pmatrix}
$$

We can notice that the transformation matrix is the rotation matrix by 90 degrees clockwise. This means that the gradient in the complex part of the function must be a 90 degree rotation of the gradient of the real part of the function. This suggests that holomorphic functions have a sort of circular motion, which turns out to be more or less a good way to think about them.

In fact, if a function is holomorphic, this implies that both the real and imaginary parts are harmonic functions. This means that both $u$ and $v$ satisfy [[Laplace's Equation]] meaning the divergence of their gradients is zero. The CR equations can then be interpreted as being satisfied when there is a $u$ and $v$ that satisfy Laplace's Equation and also have the gradient of $u$ being orthogonal to the gradient of $v$. 

For a physical interpretation of what this means, we can think of $f$ as representing a vector field of fluid flow, where $u$ represents a the velocity potential of the incompressible fluid flow. In this situation, the gradient of $u$ points along curves where $v$ is constant since $\nabla{u}$ and $\nabla{v}$ are orthogonal. The curves traced by the gradient of $u$ for constant $v$ are the streamlines of the fluid flow while the curves traced by the gradient of $v$ for constant $u$ are the equipotential curves of the flow.

We can express the derivative of $f$ using the partial derivatives of $u$ and $v$ in two ways:

$$
f'(z) = \partial_x u(x,y) + i \partial_x v(x,y) = \partial_y u(x,y) - i \partial_y v(x,y)
$$

It is worthwhile to note that all polynomials in $z$ are guaranteed to be entire (holomorphic over the whole complex plane).