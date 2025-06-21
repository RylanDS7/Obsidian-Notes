A non-inertial reference frame is a reference frame that is being accelerated relative to an inertial frame. This means that inertia and Newton's other laws will not hold in this frame. A result of this is that fictious forces can be added to the force balance in a non-inertial frame depending on what type of acceleration it has. 

In relation to [[Conservation of Momentum (fluids)]], the force balance is changed by some relative acceleration corresponding to how the reference frame is being accelerated.

$$
\sum_{CV}{F} - \int_{CV}\vec{a}_{rel}dm= \frac{d}{dt}\bigg(\int_{CV}\rho\vec{V}{dv}\bigg) + \sum_{CS}\dot{m}\beta \vec{V}_{avg}
$$

Consider that in a non-inertial frame, the sum of forces on the far left goes to zero as the acceleration in this frame is zero.

The relative acceleration term essentially adds fictious forces to the force balance that account for the acceleration of the frame. The relative acceleration is the acceleration of the body as observed from an inertial frame and a formula for it in terms of values observed in the non-inertial frame is

$$
a_{rel} = \frac{d^2}{dt^2}r_{rel} + \bigg(\frac{d}{dt}\Omega\bigg) \times R + 2(\Omega \times V) + \Omega \times (\Omega \times R)
$$

where $R$ and $V$ are the position and velocity in the non-inertial frame, $r_{rel}$ is the position vector from the inertial frame to the non-inertial frame, and $\Omega$ is the angular velocity of the non-inertial frame. 

A potentially easier way to see the significance of this is through the fictious forces induced in a non-inertial rotating frame:

$$
F_{\text{fict}} = 2m\Omega \times V + m\Omega \times (\Omega \times R) + m \alpha \times R
$$

An observer in the non-inertial frame would need to add these fictious forces to their force balance in order for Newton's Laws to hold. This means the inertial observer and non-inertial observer will be in agreement as long as the fictious forces are taken into account.

$$
F_{\text{non-inertial}} + F_{\text{fict}} = F_{\text{inertial}} = ma_{\text{inertial}}
$$

The names of the fictious forces induced by a rotation frame are:
- [[Coriolis Force]]: $2m\Omega \times V$
- [[Centrifugal Force]]: $m\Omega \times (\Omega \times R)$
- [[Euler Force]]: $m \alpha \times R$


For a simply accelerating reference frame that is not rotating, we see that

$$
\vec{F}_{net} - m\vec{a}= m\ddot{\vec{r'}}
$$

so the fictious force $m\vec{a}$ is subtracted from the force balance in the non-inertial frame.