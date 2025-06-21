An application of [[Reynolds Transport Theorem]] involving mass and the special case of fluids. We know that mass is conserved fundamentally so for $B = m$ we have

$$
\frac{d}{dt}m_{total} = 0
$$

which reduces the equation to

$$
0 = \frac{d}{dt}\bigg(\int_{CV}\rho{dv}\bigg) + \int_{CS}\rho(\vec{V_r} \cdot \hat{n})dA
$$

which says that the rate of change of mass in the CV equals the negative of the net flow of mass out of the CV across the CS.

For a velocity perpendicular to the CS, we can approximate

$$
\dot{m} = \rho V_{avg} A_{CS}
$$

and so

$$
\frac{d}{dt}m_{CV} = \dot{m}_{in} - \dot{m}_{out} = \rho\big((V_{avg} A_{CS})_{in}-(V_{avg} A_{CS})_{out}\big)
$$

