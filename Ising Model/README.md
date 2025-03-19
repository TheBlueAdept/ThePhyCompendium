# Ising Model Simulation

This repository contains an implementation of the **Ising Model** using the **Metropolis algorithm** to simulate the behavior of spins on a lattice. The system evolves over time, and the simulation produces an animated plot showing the lattice configurations as they reach equilibrium.

## Approach

1. **Initialization**:  
   The system starts with a lattice of spins. The spins are initialized randomly or in an ordered configuration.

2. **Metropolis Algorithm**:  
   The **Metropolis algorithm** is used to update the spins. In each Monte Carlo step:
   - A random spin is selected.
   - The energy change due to flipping the spin is calculated.
   - The spin is flipped with a probability determined by the temperature and the energy change.

3. **Animation**:  
   The lattice configurations are plotted after each update to show the system evolving over time. The spins are represented as up (1) or down (-1), and their colors change accordingly.

4. **Plotting**:  
   `matplotlib` is used to generate and animate the lattice configurations at each step.
