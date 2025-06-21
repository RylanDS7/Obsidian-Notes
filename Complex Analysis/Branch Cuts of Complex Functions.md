Complex functions with that are holomorphic everywhere except for lines of discontinuity require branch cuts to properly define them. These branch buts are typical when dealing with the argument function and tend to occur at whatever line in the complex plane the discontinuity of the argument function being used has. This means there is often a choice of where to place a branch cut based on the situation at hand by choosing the discontinuity of the argument to be defined differently. This means many functions have different "branches" for which the branch cuts lie in different parts of the plane.

A common example of a function with a branch cut is the complex logarithm function which is defined as

$$
Log(z) = ln|z| + i Arg(z)
$$

where the branch cut arises from the ambiguity in the argument function. The ambiguity for how the argument is defined is a selection that must be made, and the branch cut of Log will occur wherever the argument function is decided to be discontinuous. When moving along this branch cut, the jump in the function value will be $2\pi i$ which can be confirmed by the [[Argument Principle]]. 

This means that we can picture multiple copies of the complex plane being glued together along the branch cut to visualize where this $2 \pi i$ comes from as is shown here with a plot of the imaginary part of the complex log:

![[Pasted image 20250410172316.png]]

It is clear to see from this picture that where the branch cut is taken is ultimately arbitrary. When the principal branch of the argument function is taken, the branch cut of the complex logarithm becomes the negative real axis.

This explains why many complex functions have infinite roots or solutions, because functions can potentially be defined in an infinite number of ways. For example take an expression that follows from the definition of the complex log:

$$
z^{\alpha} = e^{\alpha Log(z)}
$$

The principal branch of this function is defined from the principal branch of Log which is defined from the principle branch of the argument function (i.e. $Arg(z) \in (-\pi, \pi]$). For $\alpha = \frac{1}{2}$ on this branch we have defined the principle branch of the square root function. At $z = 1$,

$$
1^\frac{1}{2} = e^{\frac{1}{2}(ln(1) + iArg(1))} = e^{0} = 1
$$

Alternatively, a branch defined using $arg(z) \in (0, 2\pi]$ will yield a different result for $z=1$:

$$
1^\frac{1}{2} = e^{\frac{1}{2}(ln(1) + iarg(1))} = e^{\frac{1}{2}(i 2\pi)} = e^{i \pi} = -1
$$

This exercise has yielded the two solutions we expect from the square root of $1$, demonstrating that the multiple solutions of functions come about from whether the branch cut is taken to be on top of the point being observed or not. This means that if we are looking for all solutions to an equation, we must check all branches of any function that has a branch cut.

For example, if $\alpha = \frac{1}{4}$ we have and we are looking for the solutions to the equation $z^4 = 1$ we need to consider all branches of $z^\frac{1}{4}$ where $1^\frac{1}{4}$ evaluates to a unique number. Using the definition above, we have

$$
1^\frac{1}{4} = e^{\frac{1}{4}(ln(1) + iarg(1))} = e^{\frac{1}{4}iarg(1)}
$$

We need to consider all relevant branches of the argument function, in this case they are

$$
arg(z) \in [0, 2\pi), \qquad arg(z) \in [2\pi, 4\pi), \qquad arg(z) \in [4\pi, 6\pi) \qquad arg(z) \in [6\pi, 8\pi)
$$

for which we have 

$$
1^\frac{1}{4} = 0, i, -1, -i 
$$

which are the expected solutions to the fourth root of one. Further branches of the argument function will reproduce the same four solutions in a cyclic fashion. Therefore we have have solved $z^4 = 1$ and found $z=0,i,-1,-i$. This example is a special case of the more general [[Roots of Unity]] which are a general solution to this problem for any fractional $\alpha$ evaluated at $z=1$. 

The important thing to realize here is that choosing different branches allowed for the appearance of multiple solutions and that no one branch is able to define the full set of solutions on its own (for any branching function). This implies branch cuts arise as a result of complex functions being multivalued, meaning whenever a function is one-to-many such as the square root function or the argument function. 

The choice of which branch to take stems from the choice of how to define the argument function. Any function with dependence on the argument of the input necessitates the choice of a branch. These branches can connect any branch points of the function together or go off to infinity in any direction along any non-intersecting path.

