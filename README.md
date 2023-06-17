# Can_Hilliard_PDE


The code provided implements a simple Cahn-Hilliard phase-field model. This model is used to simulate the evolution of a scalar field (order parameter) called Phi, which represents the concentration field in this case. The model is based on the Cahn-Hilliard equation, which describes phase separation phenomena.

## Here's a breakdown of the code:

    The `calc_del2(phi)` function calculates the Laplacian of the scalar field phi using finite differences with periodic boundary conditions.
    The `calc_force(phi)` function calculates the driving force for the evolution of Phi. It computes the chemical potential, including contributions from bulk and interface effects, based on the current value of Phi.
    The `update_phi(phi, dt)` function updates the order parameter `Phi` using an implicit, iterative scheme. It computes the force acting on Phi, performs an iterative update, and checks for convergence.
    The main part of the code initializes the system geometry and parameters, such as the system size (Nx, Ny) and the initial value of Phi. It then iterates over a specified number of steps, updating Phi and visualizing the results every 100 steps using matplotlib.

Please note that the code that is provided is incomplete, as it does not include the necessary imports and visualization setup at the beginning. However, based on the code provided, you can run this script in Python 3 to simulate the evolution of the Cahn-Hilliard phase-field model and visualize the results.
