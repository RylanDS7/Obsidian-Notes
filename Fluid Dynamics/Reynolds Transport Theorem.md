For a some fixed or moving control volume bounded by a control surface,

$$
\frac{d}{dt}B_{total} = \frac{d}{dt}\bigg(\int_{CV}\rho\beta{dv}\bigg) + \int_{CS}\rho\beta(\vec{V_r} \cdot \hat{n})dA
$$

is true for any extensive property $B$ with corresponding intensive property $\beta$ (i.e. $\beta = \frac{dB}{dm}$). This formula essentially states that the rate of change of $B$ in the system is equal to the rate of change of the total $B$ in the control volume plus the net flow of $B$ across the control surface. This formula is a generalization of the [[Leibniz Integral Rule]].

$\vec{V_r}$ is equal to the relative velocity of the area component of the CS at a point, *not the velocity of the flow.* This means that if we have a fixed and closed control volume, the equation simplifies to

$$
\frac{d}{dt}B_{total} = \frac{d}{dt}\bigg(\int_{CV}\rho\beta{dv}\bigg)
$$

This theorem can be applied to any property of a system, some notable examples include:
- [[Conservation of Mass (fluids)]]
- [[Conservation of Momentum (fluids)]]
- [[Conservation of Angular Momentum (fluids)]]

