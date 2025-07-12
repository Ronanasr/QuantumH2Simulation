# QuantumH2Simulation

## Overview
The **QuantumH2Simulation** project demonstrates an interdisciplinary approach to quantum computing and chemistry. It includes:
- Visualization of quantum states on a Bloch sphere using QuTiP.
- Calculation of the ground state energy of the H₂ molecule using the Variational Quantum Eigensolver (VQE) with Qiskit Nature.
This project bridges quantum physics and quantum chemistry, making it suitable for educational and research purposes.

## Features
- Simulates a single qubit with quantum gates (Hadamard, Pauli-X, Rotation).
- Visualizes state evolution on a 3D Bloch sphere.
- Computes the H₂ molecule's ground state energy with VQE.
- Provides high-quality visualizations and energy comparisons with theoretical values.

## Installation
To run this project, ensure you have the required dependencies installed:
```bash
pip install qutip numpy qiskit qiskit-nature
```
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/YourUsername/QuantumH2Simulation.git
cd QuantumH2Simulation
```

## Usage
### Bloch Sphere Simulation
Run the qubit simulation script:
```bash
python qubit_simulation_bloch.py
```
- A 3D Bloch sphere will display with colored points representing quantum states.
- The output image (`bloch_sphere.png`) will be saved if supported.

### VQE Energy Calculation
Run the H₂ energy calculation script:
```bash
python h2_vqe.py
```
- The calculated energy and comparison with the theoretical value will be printed.

## Results
- **Bloch Sphere**: Visualizes the initial |0> state, states after Hadamard, Pauli-X, and a rotation gate.
- **H₂ Energy**: Approximate ground state energy (e.g., ~-1.13 Hartree) with a small deviation from the theoretical value (~-1.137 Hartree).
-![Bloch Sphere](bloch_sphere.png)
## License
This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Built with [QuTiP](https://qutip.org/) and [Qiskit](https://qiskit.org/) libraries.
- Inspired by quantum computing and chemistry educational resources.

## Contact
For questions or contributions, please open an issue on the [GitHub repository](https://github.com/Ronanasr/QuantumH2Simulation) or contact [ronasr82@gmail.com](mailto:ronasr82@gmail.com).
