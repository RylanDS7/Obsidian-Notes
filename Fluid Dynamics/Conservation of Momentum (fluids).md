An application of [[Reynolds Transport Theorem]] involving total momentum and the special case of fluids. For $B=m\vec{V}$, the equation becomes

$$
\sum_{CV}{F} = \frac{d}{dt}\bigg(\int_{CV}\rho\vec{V}{dv}\bigg) + \int_{CS}\rho\vec{V}(\vec{V_r} \cdot \hat{n})dA
$$

With a correction factor for the approximation, we can rewrite the flux term as 

$$
\int_{CS}\rho\vec{V}(\vec{V_r} \cdot \hat{n})dA = \dot{m}\beta \vec{V}_{avg}
$$

The $\beta$ correction factor here is different from the intensive property that is used in the generalized Reynolds Transport Theorem. For turbulent flow we can take $\beta$ to be in the range $1.01 - 1.05$. 

The other important point is that $\vec{V}_{avg}$ is still a vector and these quantities are added vectorially. Additionally, this quantity is a *relative velocity* for how quickly the fluid crosses the control surface boundary, so if the control volume is not stationary this will need to be accounted for.

The second term in the equation goes to zero for a steady state system (most of the time) so the the most common situation we have can be solved with

$$
\sum_{CV}{F} = \sum_{CS}\dot{m}\beta \vec{V}_{avg}
$$

(Above equation applying for flux approximation and steady state control volume).