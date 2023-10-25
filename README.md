# Qiskit Fall Fest UCLA 2023 Solutions

This repository contains solutions developed by our team for the Qiskit Fall Fest UCLA 2023.

**Team Members (MQST Students):**

🔹 **Manvi Agrawal** - [🔗 LinkedIn](https://www.linkedin.com/in/manvi-a-0a95b1171/)  
🔹 **Robert Negrin** - [🔗 LinkedIn](https://www.linkedin.com/in/rsnegrin)  
🔹 **Saleh Naghdi** - [🔗 LinkedIn](https://www.linkedin.com/in/saleh-naghdi/)  
🔹 **Yarin Heffes** - [🔗 LinkedIn](https://www.linkedin.com/in/yarinheffes/)  

**Affiliation**  
University of California, Los Angeles

--- 

# Quantum Simulation of the H<sub>2</sub> Molecule

## Introduction
Our project focuses on simulating the behavior and energy of the $H_2$ molecule in various quantum scenarios. We evaluated the time evolution of the Hydrogen molecule by itself, its response to a static perturbation such as that induced by an external magnetic field, and its behavior when exposed to a time-dependent external magnetic field.

## Abstract
The project delves deep into the quantum dynamics of the $H_2$ molecule. We employ the Trotterisation method to evaluate its time evolution and further introduce Riemann-Sums to handle time-dependent perturbations. Our final exploration showcases the Adiabatic Theorem in quantum mechanics, highlighting the behavior of the $H_2$ molecule under changing external magnetic fields.

## Motivation
As MQST master's students deeply rooted in physics and computer science, we aimed to break away from the oft-discussed Hydrogen atom and instead focus on the richer dynamics of the Hydrogen molecule. This venture allowed us to bring together our collective backgrounds and expertise, driving a detailed and nuanced exploration of the $H_2$ molecule in various quantum scenarios.

## Code & Results

All the code and results are in the `Solutions` folder in a Jupyter notebook file. 
Additionally, the Jupyter notebook contains detailed explanations and conclusions for the different sections.

## Project Accomplishments

### 1. Simulating the Ground State with VQE
- Defined the $H_2$ molecule using Qiskit's `PySCFDriver`.
- Utilized the Jordan-Wigner Transformation for fermion-to-qubit mapping.
- Employed the Variational Quantum Eigensolver (VQE) to determine the ground state.

### 2. Simulating just the H<sub>2</sub> Hamiltonian
- Applied Trotterisation method with Qiskit's `SuzukiTrotter` to ascertain the time evolution operator of $H_2$.

### 3. Static Perturbation with Trotterisation
- Investigated the time-evolution of $H_2$ in the presence of a weak static magnetic field.
- Enhanced accuracy by increasing the order of Trotterisation.

### 4. Time-dependent Perturbation using Riemann-Sums and Trotterisation
- Addressed challenges posed by time-dependent Hamiltonian by discretizing it over intervals.
- Utilized Trotterisation within each interval.

### 5. Demonstrating the Adiabatic Theorem
- Illustrated the Adiabatic Theorem by evolving the $H_2$ molecule under changing external magnetic fields.

## Conclusions
Our deep dive into the quantum behavior of the $H_2$ molecule yielded insights into its ground state, time evolution, and response to external magnetic fields, both static and dynamic. The project highlights the strength of quantum simulations in unraveling the intricate properties of physical systems.


## Further Topics

1. **Hybrid Method Comparison:**
   - Involve both Trotterisation and Exact methods.
   - Compare the noisiness of both on real machines.

2. **Topological Properties of Molecule**

3. **Neural Network Representations**

4. **Renormalisation Group**
   
5. **Real life ODE**

# 📚 Essential Resources:
- [Quantum Real Time Evolution using Trotterization](https://qiskit.org/ecosystem/algorithms/tutorials/13_trotterQRTE.html)
- [Nature Article on Quantum Simulations](https://www.nature.com/articles/s41467-021-25196-0)
- [Trotterization Explained by V. Tomole](https://vtomole.com/blog/2019/04/07/trotter)
- [Microsoft Quantum Development Guide on Chemistry Algorithms](https://learn.microsoft.com/en-us/azure/quantum/user-guide/libraries/chemistry/concepts/algorithms)
- [Adaptive Trotterization for time-dependent Hamiltonian](https://arxiv.org/abs/2307.10327)
- [How to perform trotterization of a time-dependent Hamiltonian simulation](https://quantumcomputing.stackexchange.com/questions/32315/how-to-perfrom-a-time-dependent-hamiltonian-simultation-using-the-trotter-suzuki)
- [Simulating Topological Systems with Qiskit Pulse](https://medium.com/qiskit/simulating-topological-systems-with-qiskit-pulse-9afac342ab09)
- [Efficient quantum algorithm for dissipative nonlinear differential equations](https://www.pnas.org/doi/10.1073/pnas.2026805118)
---
