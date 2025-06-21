This equation is a generalization of conservation of energy in application to fluid dynamics. In full generality,

$$
\dot{Q}_{net,in} + \dot{W}_{net,in} = \frac{dE_{sys}}{dt} = \frac{d}{dt}\bigg(\int_{CV}e\rho dv \bigg) + \int_{CS}e\rho (\vec{V_r} \cdot \vec{n}) dA
$$

which uses [[Reynolds Transport Theorem]] to find the rate of change of system energy with respect to time.

In application to laminar pipe flow, we can divide through by mass flow rate and simplify with [[Bernoulli's Equation]] to get

$$
w_{pump} + \frac{V_1^2}{2} + \frac{P_1}{\rho} +gz_1 = \frac{V_2^2}{2} + \frac{P_2}{\rho} +gz_2 + w_{turbine} + e_{mech,loss}
$$

which is a much more applicable formula.

We can also divide through by $g$ to get the head form of this equation which is commonly done to have all terms of the equation in length units.

$$
h_{pump} + \frac{V_1^2}{2g} + \frac{P_1}{\rho g} + z_1 = \frac{V_2^2}{2g} + \frac{P_2}{\rho g} + z_2 + h_{turbine} + h_{L}
$$

The $h_L$ term encompasses all forms of mechanically lost energy. In the context of pipe flow, this encompasses [[Frictional Losses in Pipes]] and minor losses due to the geometry of the pipe network.