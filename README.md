# Quantum_Computing_Two_Qubit_Bell_State
This project demonstrates the creation and analysis of a GHZ (Greenberger–Horne–Zeilinger) state using Qiskit, a Python library for quantum computing. 
As well as the creation and analysis of a GHZ (Greenberger–Horne–Zeilinger) state using Qiskit, a Python library for quantum computing. The GHZ state is a type of entangled quantum state that involves multiple qubits. This project utilizes Qiskit's IBM Quantum Experience to run quantum circuits and estimators, allowing for the exploration of quantum states and their properties.

## Key Features
- **Creation of a GHZ State**: Generates a quantum circuit to create a GHZ state for a specified number of qubits.
- **Quantum Circuit Transpilation**: Transpiles quantum circuits for execution on specified IBM Quantum backends.
- **Expectation Value Calculation**: Uses Qiskit's Estimator to evaluate the expectation values of various Pauli operators.
- **Visualization**: Plots the expectation values to visualize the entanglement properties of the GHZ state.

## Setup

### Prerequisites

- Python 3.7 or higher
- [Qiskit](https://qiskit.org/documentation/getting_started.html)
- An IBM Quantum Experience account

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/quantum-computing-project.git
    cd quantum-computing-project
    ```

2. **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Project

1. **Ensure you have access to the IBM Quantum Experience.**
   - Sign up and create an account if you haven't already.

2. **Update the backend name as needed in the script.**

3. **Run the script:**
    ```bash
    python src/main.py
    ```

### Example Output

The script will print the job ID and wait for the job to complete. Once completed, it will plot the expectation values for different observables, showing the entanglement properties of the GHZ state.

## Usage

- **QuantumCircuit**: Create and visualize quantum circuits.
- **Pauli Operators**: Define and use Pauli operators in quantum circuits.
- **Estimator**: Run quantum circuits and calculate expectation values.
- **Plotting**: Visualize the results using Matplotlib.

## Project Structure
quantum-computing-project/
├── LICENSE
├── README.md
├── requirements.txt
├── .gitignore
└── src/
└── main.py

## Dependencies

- qiskit
- matplotlib
- numpy

