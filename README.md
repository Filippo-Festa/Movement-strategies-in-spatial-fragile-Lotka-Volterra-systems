# Movement Strategies in Spatial Fragile Lotka-Volterra Systems

This repository contains the research and simulation code for the project **"Movement Strategies in Spatial Fragile Lotka-Volterra Systems"**. This study builds upon the foundational work by [Giometto et al.](https://www.pnas.org/doi/abs/10.1073/pnas.1719889115) to explore predator-prey dynamics through various movement strategies, focusing on the spatial Lotka-Volterra model.

## Overview

The research examines how different movement strategies, including Gaussian, Exponential, and Lévy flight distributions, influence predator-prey interactions in spatially extended systems. Our approach integrates both analytical and simulation-based methods to reveal complex behaviors that differ significantly between these two perspectives.

### Key Contributions

- **Extension Beyond Previous Work:** While Giometto et al. laid the groundwork, our study delves deeper into how different displacement distributions impact the predator's abundance and the overall stability of the ecosystem.
  
- **Analytical vs. Simulation Discrepancies:** We observed that the analytical models and simulation results show fundamentally different behaviors. This divergence could be attributed to:
  - The presence of stochastic noise in simulations, which favors local extinction events.
  - The finite size of the simulated system, which does not fully capture the infinite theoretical assumptions.
  - Geometric differences between the analytical models and the spatial implementation in simulations.

- **Optimal Movement Strategy:** Our findings suggest that, irrespective of the specific jump distribution, an average jump length that aligns with the prey patch radius maximizes predator abundance. This balance between exploration and exploitation is crucial for the survival and dominance of predators in such systems.

## Conclusion

The study provides insights into the critical factors that influence predator-prey dynamics in spatially explicit models. The significant difference between analytical and simulation outcomes highlights the importance of considering both perspectives when studying ecological systems.

Moreover, the observed coherence in optimal average jump lengths across different distributions suggests a universal principle governing movement strategies in spatial predator-prey interactions.
