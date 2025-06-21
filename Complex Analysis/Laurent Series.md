The Laurent Series is essentially an extension of a [[Taylor Series]] with the addition of negative powers. Where the Taylor series is defined on a disc, the Laurent Series is defined on an annulus, where the outer radius is determined by the convergence of the positive powers and the inner radius is determined by the convergence of the negative powers. 

A Laurent Series of a function around the point $c$ can be expressed as

$$
f(z) = \sum_{n = -\infty}^{\infty}a_n(z-c)^n
$$

The coefficients $a_n$ can be determined by the formula

$$
a_n = \frac{1}{2\pi i} \oint_{|z-c| = r} \frac{f(z)}{(z-c)^{(n+1)}}dz
$$

where $r$ is such that the contour is contained within the annulus of convergence. We can see that if there is an isolated singularity at $c$ then we see that

$$
a_{-1} = \frac{1}{2\pi i}\oint_{|z-c| = r} f(z)dz = \text{Res}(f, c)
$$

and so we recover the [[Residue Theorem]]. 

If $f$ is holomorphic on the whole disc including the interior of the annulus, then all negative $a_n$ are zero. Furthermore, the formula for the positive $a_n$ now takes the form for which we can apply [[Cauchy's Integral Formula]] and see that

$$
a_n = \frac{1}{2\pi i} \oint_{|z-c| = r} \frac{f(z)}{(z-c)^{(n+1)}}dz = \frac{ f^{(n)}(c)}{n!}
$$

which are the expected coefficients for the Taylor Expansion around $c$, so we recover the Taylor Series. 