# Single Qubit Operation Quantum Simulator

This repository contains a Python-based simulation of a simple quantum operation on a single qubit using basic quantum gates and measurement. The code demonstrates how to initialize a qubit, apply a quantum transformation using a Hadamard gate, and measure the state multiple times to observe the outcome probabilities.

## Table of Contents
- [Overview](#overview)
- [Quantum Concepts Used](#quantum-concepts-used)
- [Setup](#setup)
- [Code Explanation](#code-explanation)
- [Usage](#usage)

## Overview
This simulation performs a basic quantum computation by:
1. Initializing a qubit in the \( |0\rangle \) state.
2. Applying a Hadamard gate to create a superposition of \( |0\rangle \) and \( |1\rangle \).
3. Measuring the qubit 100 times to observe the outcomes based on the probabilities defined by the quantum state.

## Quantum Concepts Used
- **Qubit States**: In quantum computing, a qubit's state is represented as a vector. The computational basis states \( |0\rangle \) and \( |1\rangle \) are the fundamental building blocks.
- **Hadamard Gate**: The Hadamard gate creates superpositions, transforming a \( |0\rangle \) or \( |1\rangle \) state into a balanced superposition.
- **Measurement**: Measuring a qubit collapses its state to either \( |0\rangle \) or \( |1\rangle \) with probabilities based on its state vector.

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/single-qubit-operation-quantum-simulator.git

2. Navigate to the project directory:
   ```bash
   cd single-qubit-operation-quantum-simulator

3. Install the required dependencies from requirements.txt:
   ```bash
   pip install -r requirements.txt


## Code Explanation

-- initialize_state(): Prepares the qubit in the ∣0⟩ state, represented as [1, 0].
-- apply_u(state): Applies the Hadamard gate 𝑈 to the qubit, creating a superposition. This is done via matrix multiplication.
-- measure_state(state, num_meas): Simulates measuring the qubit num_meas times, returning a list of results (0 or 1). The measurement outcome probabilities are determined by the amplitudes of the state.
-- quantum_algorithm(): Combines the steps above into a simple algorithm that initializes, transforms, and measures a quantum state.

## Usage

 ```bash
 python quantum_simulator.py


## Expected Output

-- The output should be an array containing 0s and 1s, where the distribution of 0s and 1s reflects the probabilities determined by the final quantum state.
