# certified-quantum-randomness
Experimental analysis of randomness in noisy quantum systems using structured circuits and cross-entropy benchmarking.

# Aaronson-Inspired Quantum Randomness via Cross-Entropy

## Overview
This project implements an Aaronson-inspired approach to randomness certification using structured non-Clifford quantum circuits and cross-entropy benchmarking. Experiments are run in ideal simulation, noisy simulation, and on real IBM quantum hardware.

## Motivation
The randomness of quantum computer differs from a classical one not only by the quality (real random source) but by verifiability- where the random number ensemble can be verified as coming from a quantum computer by the statistical test cross-entropy benchmarking. Thus this code is not only useful for post quantum cryptography, but shed light on the depth of quantum information when serving as an entropy source.

## Method
- Construct excitation-preserving, non-Clifford circuits
- Execute across multiple noise regimes
- Compare outcome distributions
- Apply cross-entropy benchmarking

## What this demonstrates
- Translating theoretical ideas into experiments
- Working with real quantum hardware
- Statistical reasoning under noise
- Research-oriented Python code

## Limitations
This is not a device-independent or cryptographic certification. The focus is on experimental methodology and interpretability.
