The Fourier Transform is a generalization of the [[Laplace Transform]] in the complex plane. This transform is used to visualize the different frequency components that are present in a given signal or function as represented in the [[Fourier Series]].

The Fourier Transform of a function can be calculated with the formula

$$
\hat{f}(k) = \int_{-\infty}^{\infty}f(x)e^{-i2\pi kx}dx
$$

and the inverse transform can be found with

$$
f(x) = \int_{-\infty}^{\infty}\hat{f}(k)e^{i2\pi kx}dk
$$

These equations can sometimes be represented with different notations or scaling with the $2\pi$.

The Fourier Transform is equal to the Laplace transform up to a factor of $2\pi$ for a purely imaginary input, and vice versa. In other words,

$$
\mathcal{L}\{f\}(s)=\hat{f}(-is) \qquad \qquad \hat{f}(\omega)=\mathcal{L}\{f\}(i\omega)
$$

