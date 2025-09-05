# Bernstein–Vazirani Algorithm Implementation

This repository contains an implementation of the **Bernstein–Vazirani quantum algorithm** using [Qiskit](https://qiskit.org/).  
The project was developed as part of the **Quantum Computing course (CIN0039)**.  

The Bernstein–Vazirani algorithm demonstrates the efficiency of quantum computation in identifying a hidden binary string with a **single oracle query**, in contrast to the **O(n)** queries required in the classical model.  

---

## Overview

- Construction of quantum circuits for the Bernstein–Vazirani algorithm  
- Simulation with noiseless and noisy environments using Qiskit Aer  
- Visualization of measurement results with histograms  

**Classical complexity:** O(n)  
**Quantum complexity:** O(1)  

Reference: [Quantum complexity theory – Bernstein, Vazirani (1993)](https://dl.acm.org/doi/pdf/10.1145/167088.167097)  

---

## Technologies

- **Python**  
- **Qiskit** (qiskit, qiskit-aer)  

---
## Example

The algorithm generates a random hidden binary string (or uses a predefined one) and retrieves it through quantum computation.
Results are displayed as histograms of measurement counts.

<img width="410" height="216" alt="image" src="https://github.com/user-attachments/assets/26afe60e-5171-4eb4-a958-7fddb3f2367a" />

---
## Authors

This project was developed by:
- [Amanda Arruda](https://github.com/amandaarruda)  
- [João Vitor Mergulhão](https://github.com/JVMergulho)
- [Ricardo Bezerra](https://github.com/ricardobizerra)
