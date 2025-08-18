# Quantum Algorithms with Qiskit

This repository contains Jupyter Notebook implementations of foundational quantum algorithms using Qiskit.  
The goal is to provide clean, educational examples of how these algorithms are built and executed on simulators.  

---

## 📚 Implemented Algorithms  

1. **Deutsch’s Algorithm**  
   Problem: Given a function f: {0,1} → {0,1}, determine if f is constant or balanced.  
   Shows the power of quantum computing with only one query.  

2. **Deutsch–Jozsa Algorithm**  
   Generalization of Deutsch’s problem to f: {0,1}ⁿ → {0,1}.  
   Distinguishes between constant and balanced functions in a single query, versus exponential queries classically.  

3. **Bernstein–Vazirani Problem**  
   Runs using Deutsch–Jozsa Algorithm. Finds a hidden bit string a in f(x) = a · x ⊕ b.  
   Requires only one query, while classical algorithms need n.  

4. **Simon’s Algorithm (work in progress)**  
   Finds the secret string s such that f(x) = f(x ⊕ s).  
   Exponential speedup over classical approaches; precursor to Shor’s algorithm.  

5. **Grover’s Search Algorithm**  
   Searches an unsorted database of size N in O(√N) steps.  
   Demonstrates quantum amplitude amplification.  

6. **Quantum Phase Estimation (QPE)**  
   Estimates eigenvalues (phases) of unitary operators.  
   Foundation for quantum simulations and Shor’s factoring algorithm.  

7. **Shor’s Factoring Algorithm**  
   Factors large integers efficiently using QPE and modular exponentiation.  
   Breaks classical RSA cryptography.  

## 📖 References

1. John Watrous, *Understanding Quantum Information and Computation*  [arXiv 2507.11536](https://arxiv.org/abs/2507.11536)
2. *Quantum Computer Science: An Introduction* — N. David Mermin, Cornell University Press
