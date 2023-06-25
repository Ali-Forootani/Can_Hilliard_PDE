# Can_Hilliard_PDE


The code provided implements a simple Cahn-Hilliard phase-field model. This model is used to simulate the evolution of a scalar field (order parameter) called Phi, which represents the concentration field in this case. The model is based on the Cahn-Hilliard equation, which describes phase separation phenomena.

Cahn-Hilliard Phase-Field Model

## Overview:
------------
This code implements a simple Cahn-Hilliard phase-field model. The model simulates the evolution of a scalar field (order parameter) called Phi, which represents the concentration field. The Cahn-Hilliard equation is used to describe phase separation phenomena.

## Requirements:
------------
- Python 3.x
- NumPy
- Matplotlib

## Usage:
------------
1. Make sure you have Python 3.x installed on your system.
2. Install the required dependencies by running the following command:
```bash
pip install numpy matplotlib
```
3. Save the code to a Python file (e.g., `cahn_hilliard.py`).

## Execution:
------------
Run the code using the following command:
```bash
python cahn_hilliard.py
```

## Code Explanation:
------------
The code is structured as follows:

1. Importing Dependencies:
   - NumPy: For numerical computations.
   - Matplotlib: For visualization.

2. Defining Functions:
   - `calc_del2(phi)`: Calculates the Laplacian of the scalar field `phi` using finite differences and periodic boundary conditions.
   - `calc_force(phi)`: Calculates the driving force for the evolution of Phi. It computes the chemical potential, including contributions from bulk and interface effects.
   - `update_phi(phi, dt)`: Updates the order parameter Phi using an implicit, iterative scheme.

3. Main Execution:
   - Initialization: Sets up the system geometry and parameters, such as system size (Nx, Ny) and the initial value of Phi.
   - Simulation Loop: Iterates over a specified number of steps.
   - Updating Phi: Calls the `update_phi` function to update Phi based on the calculated forces.
   - Visualization: Plots and displays the updated Phi every 100 steps.

Please note that the provided code is incomplete and lacks the necessary import statements and visualization setup at the beginning. Make sure to complete the code by adding the required imports and visualization configuration before running it.

## Contributing:
------------
Feel free to contribute to the project by opening issues or submitting pull requests.

## License:
------------
This code is released under the MIT License. See the LICENSE file for more information.

## Inquiry

You can contact me via: aliforootani@ieee.org



