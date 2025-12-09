Generally, a harmonic oscillator is a system dictated by a potential that is proportional to position squared. The classical example is a mass on a spring moving under the influence of Hook's Law.

In quantum mechanics, a harmonic oscillator is a system governed by [[The Hamiltonian Operator]]
$$
\hat{H} = -\frac{\hbar}{2m}\frac{d^2}{dx^2} + \frac{1}{2}m \omega^2 x^2
$$
The solutions to the harmonic oscillator Hamiltonian can be found using [[Ladder Operators]] derived from [[Commutators]].

Consider carrying out the following unit changes for the typical position and momentum operators:
$$
\hat{X} = \sqrt{\frac{m\omega}{\hbar}}\hat{X}_{\text{original}} \hspace{40px} \hat{P} = \frac{1}{\sqrt{m\omega \hbar}}\hat{P}_{\text{original}}
$$
Then, the Hamiltonian can be expressed as
$$
\hat{H} = \frac{\hbar\omega}{2}\big(\hat{P}^2 + \hat{X}^2\big)
$$
Defining the ladder operators
$$
\hat{a} = \frac{1}{\sqrt{2}}\big(\hat{X} - i \hat{P}\big) \hspace{40px} \hat{a}^\dagger = \frac{1}{\sqrt{2}}\big(\hat{X} + i \hat{P}\big) 
$$
where $[\hat{a}, \hat{a}^\dagger] = 1$.

It can be shown that for eigenfunctions of the Hamiltonian $|n\rangle$, we have
$$
\hat{a}^\dagger|n\rangle = \sqrt{n+1} \ |n+1\rangle \hspace{40px} \hat{a}|n\rangle = \sqrt{n} \ |n-1\rangle
$$
so these are wavefunction raising and lowering operators.

This allows us to find all wavefunctions if we can can find one of them.

The above approach is also used to derive the [[Angular Momentum (Quantum)]] formalism.