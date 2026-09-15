# Variational Algorithm Design

This repository contains my coursework, code, and Jupyter notebooks for the IBM Quantum Learning course: **[Variational Algorithm Design](https://quantum.cloud.ibm.com/learning/en/courses/variational-algorithm-design)**.

## Course Overview

Variational algorithms are hybrid quantum-classical algorithms that are considered prime candidates for achieving quantum advantage in the near term. This course covers how to write these algorithms and optimize them using Qiskit Runtime primitives.

### Directory Structure

- `01-workflow-design/`: Steps involved in building hybrid quantum-classical algorithms.
- `02-ansatz-construction/`: Methods for creating parameterized quantum circuits (`RealAmplitudes`, `EfficientSU2`, custom ansätze).
- `03-optimization/`: Using Qiskit Runtime primitives (`EstimatorV2`, `SamplerV2`) and classical optimizers (COBYLA, SPSA).
- `04-applications/`: Practical examples such as finding minimum eigenvalues (VQE) and solving combinatorial optimization problems (QAOA).

## Prerequisites

- Qiskit 1.x
- Qiskit IBM Runtime
- Python 3.10+
