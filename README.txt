# Analysis of Potential Magic in Quantum Graph States

This project provides tools to calculate the potential magic resource for a given quantum graph state using two different methods.

## Description of Methods

#### 1. Brute-Force Method
This method performs an exhaustive, deterministic calculation of the potential magic.

-   **Pros:** The results are **stable** and exact.
-   **Cons:** This approach is computationally intensive and requires a pre-defined measurement order for the qubits.

#### 2. Adaptive Method
This method uses a heuristic algorithm to estimate the potential magic resource.

-   **Pros:** Significantly faster than the brute-force approach.
-   **Cons:** The results are **not guaranteed to be stable** and may vary between runs, providing an approximation rather than an exact value.

## Requirements

-   Python >= 3.7
-   Libraries:
    -   `numpy`
    -   `scipy`
    -   `qiskit`
    -   `networkx`
    -   `itertools`, `functools`, `math`, `time` (standard libraries)