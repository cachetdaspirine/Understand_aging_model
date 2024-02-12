# Summarize of the different controls
## Rate of diffusion vs binding/unbinding rate
By construction, the rate of binding and the rate of unbinding of always almost equal (up to a factor of order $N$. In practice, $N_{step}\gg N$).
As illustrated by the Polland-Scheraga model, there is a phase transition when the binding energy is lowered. Once the critical binding energy $E_c$ is reached, all the linkers are bound to the polymer. In this case, we have:
$$
Ec \propto k_B T \log(L/N),
$$
where $k_B$ is the Boltzmann constant, $T$ the temperature, $L$ the total length of the polymer and $N$ the number of linkers. Assuming:
$$
\frac{k_{ub}}{k_b} \ll 1
$$
In this case, diffusion essentially never occur unless a linker unbinds, diffuse before rebinding. To compute the rate of diffusion move, we must compare $k_b$ and $k_{diff}$. 

## Binding distance
