The Residue Theorem revolves around the idea that singularities of a function in the complex plane have an associated residue that can be used to compute the integral of the function around the singularity.

For a meromorphic function $f$ on a domain $\Omega$ with a closed simple contour $\alpha$ containing a set of poles $a_1, a_2, ... , a_n$ on its interior we can find that

$$
\oint_{\alpha} f(z)dz = 2\pi i \sum_{k=1}^{n}Res(f,a_k)
$$

where $Res(f, a_k)$ are the residues of the function $f$ at the point $a_k$.

Finding the residues is more complicated for higher order poles, but there are generally two methods.

The residue can be found for non-essential poles using this formula where $p$ is the order of the pole.

$$
	Res(f,c) = \frac{1}{(p-1)!}\lim_{z\rightarrow c}\frac{d^{p-1}}{dz^(p-1)}((z-c)^p f(z))
$$

Alternatively, if the residue is difficult or impossible to calculate this way, it can be found as the coefficient of the $-1$ term of the [[Laurent Series]]. This means that if the function can be expressed as a Laurent Series around a pole $c$, the residue of that pole will be given by the coefficient of $(z-c)^{-1}$. 

We can observe that the for the case of a single simple pole of $f$ at $w$ we can write that

$$
f(z) = \frac{g(z)}{z-w}
$$

where $g(z)$ is holomorphic. Using the formula for the residue it is clear that $Res(f, w) = g(w)$ and so we can recover [[Cauchy's Integral Formula]].