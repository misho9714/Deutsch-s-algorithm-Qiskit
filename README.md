# Deutsch’s Algorithm with Qiskit

This repository contains a simple implementation of **Deutsch’s algorithm**, one of the earliest examples of a quantum algorithm that demonstrates a separation between classical and quantum computation.

## Overview

Deutsch’s algorithm solves the following problem:  
Given a function f: {0,1} → {0,1}, determine whether f is **constant** (returns the same value for all inputs) or **balanced** (returns different values for different inputs).

Classically, this requires **two function evaluations**, but using quantum superposition and interference, the quantum algorithm solves it with **just one oracle call**.

## Contents

- `deutsch_algorithm.ipynb` – Jupyter notebook implementation with:
  - Oracle definitions (`constant0`, `constant1`, `balanced`, `balanced_not`)
  - Quantum circuit construction
  - Simulation on `Aer` backend
  - Visualization of results with `plot_histogram`
  - Step-by-step explanation of the circuit

