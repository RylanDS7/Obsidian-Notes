For a meromorphic function $f$ inside and on a closed contour $\alpha$ where $f$ has no poles or zeros on the curve $\alpha$ then

$$
\frac{1}{2\pi i}\oint_{\alpha}\frac{f'(z)}{f(z)}dz = Z-P
$$

where $Z$ and $P$ denote the number of poles and zeros of $f$ inside of $\alpha$. It is important that these are the poles and zeros of $f$ itself and not the poles and zeros of $\frac{f'(z)}{f(z)}$.

This contour integral can be interpreted as $2\pi i$ times the [[Winding Number]] of $f(\alpha)$ around the origin. This is equivalent to the total change in the argument of $f$ as it travels along the curve $\alpha$. 

Another way to see this relationship uses the fact that

$$
\frac{d}{dz}Log(f(z)) = \frac{f'(z)}{f(z)}
$$

and so 

$$
\frac{1}{2\pi i}\oint_{\alpha}\frac{f'(z)}{f(z)}dz = \frac{1}{2\pi i}\oint_{\alpha}\frac{d}{dz}Log(f(z))dz = \frac{1}{2\pi i}\big(Log(f(z_f))-Log(f(z_i))\big)
$$

The difference in the values of the Log function at the beginning and ending point on the contour may seem to be equal, but it is actually not as we are integrating along branch cuts (see [[Branch Cuts of Complex Functions]]). If we imagine appending a series of branches of the complex log such that it is continuous we will see that 

$$
\big(Log(f(z_f))-Log(f(z_i))\big) = i \Delta_{\alpha} arg(f)
$$

and so

$$
\frac{1}{2\pi i}\oint_{\alpha}\frac{f'(z)}{f(z)}dz = \frac{\Delta_{\alpha} arg(f)}{2\pi}
$$

Since the winding number of $f$ is equal to $Z - P$ in this case and the winding number is the number of times $f$ goes around the origin, we can see that

$$
\Delta_{\alpha} arg(f) = 2\pi(Z-P)
$$

and so we recover

$$
\frac{1}{2\pi i}\oint_{\alpha}\frac{f'(z)}{f(z)}dz = Z-P
$$


This is not really a proof of the argument principle because we use the argument principle to show that the winding number is equal to $Z - P$ in the special case of simple closed curve encircling a set of zeros and poles. If we make the change of variables $w=f(z)$ to the formula we see that $dw = f'(z)dz$ and so

$$
\frac{1}{2\pi i}\oint_{\alpha}\frac{f'(z)}{f(z)}dz = \frac{1}{2\pi i}\oint_{f(\alpha)}\frac{dw}{w}
$$

Using [[Cauchy's Integral Formula]] we know that the right hand integral is equal to $2\pi i N$ where $N$ is the winding number around the origin, therefore

$$
\frac{1}{2\pi i}\oint_{\alpha}\frac{f'(z)}{f(z)}dz = N = Z - P
$$

and so in this special case, the winding number is equal to the number of zeros minus the number of poles encircled by $\alpha$.