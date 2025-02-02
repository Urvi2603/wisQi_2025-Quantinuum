<div style="text-align: center;">
  <img src="images/iquhack.png" alt="drawing" width="150"/>
</div>

# Hamiltonian Simulation using Quantum Walks 

---
## Team **wisQi**
Quantinuum Challenge - Members:  [Henry Lin](https://github.com/Henry-Linn/), [Sriram](https://github.com/legendarybladerofmilkywaygalaxy/), [Vinay Swamik](https://github.com/vinayswamik/), [Sparsh](https://github.com/SparshSriva/), [Urvi jain](https://github.com/Urvi2603/).
<div style="text-align: center;">
  <img src="images/uw.png" alt="drawing" width="200"/>
  <img src="images/qu.jpg" alt="drawing" width="200"
  >
</div>

---

## Contents
- [Simulating Hamiltonians using block encoding and quantum walk techniques](#simulating_hamiltonians_using_block_encoding_and_quantum_walk_techniques])
  - [Contents](#contents)
  - [Theoretical Motivation](#theoretical-motivation)
  - [Task 1: ](#task-1)
  - [Task 2: ](#task-2)
  - [Graphs](#graphs)
  - [Task 3: ](#task-3)
  - [Results](#results)
  - [Sources](#sources)
  - [Acknowledgments](#acknowledgments)

## Theoretical Motivation

Quantum simulation is a cornerstone of quantum computing, promising to revolutionize our understanding of complex quantum systems beyond the capabilities of classical computation. The ability to efficiently simulate quantum dynamics has profound implications for fields such as quantum chemistry, condensed matter physics, and materials science. The Quantinuum iQuHack 2025 challenge explores two pivotal aspects of quantum simulation: Hamiltonian and Lindbladian dynamics, providing a platform to develop novel methods for digital quantum computation.

For this Challenge, we picked the Hamiltonian simulation challenge. Using a novel approach, we explored the Quantinuum Nexus and Pytket development frameworks, walked through multiple tasks, and simulated the Ising molecule.

## Task 1: 
Initially, we started working on customized tasks provided by Quantinuum. We built the XXZ and ising Hamiltonias with built-in and personalized functions. We evolve those Hamiltonians using the first-order trotter step and got accurate results by comparing multiple approaches.

<div style="text-align: center;">
  <img src="images/circuit1.png" alt="drawing" width=""/>
</div>

<div style="text-align: center;">
  <img src="images/circuit2.png" alt="drawing" width=""/>
</div>

## Task 2: 
In this task, we Explored physically engaging scenarios for time evolution, such as energy conservation and time-dependent expectation values in different Hamiltonian.
## Graphs
### Energy Conservation
<div style="text-align: center;">
  <img src="images/pl1.png" alt="secdesgraph" width=""/>
</div>

### Expectation Values
<div style="text-align: center;">
  <img src="images/pl2.png" alt="secdesgraph" width=""/>
</div>
<div style="text-align: center;">
  <img src="images/pl3.png" alt="secdesgraph" width=""/>
</div>

## Task 3: 
Here, we try to simulate a Hamiltonian using Block-encoding with a Quantum walk. We build a Hamiltonian and Block encoding of H to satisfy the unitary condition. We evolve that unitary U using the quantum walk operator and reflection operator. We apply the reflection operator multiple times to get a better approximation. 

<div style="text-align: center;">
  <img src="images/qw.png" alt="drawing" width=""/>
</div>

## Results

## Sources

1. [Universal computation by quantum walk](https://arxiv.org/abs/0806.1972) [Paper]

2. [Information about Quantinuum iQuHack2025 challenge](https://github.com/Urvi2603/wisQi_2025-Quantinuum/edit/main/) [Challenge repo]

3. [Quantinuum Pytket Framework](https://docs.quantinuum.com/tket/user-guide/)

## Acknowledgments

***A special thanks to everyone on the Quantinuum team for their support!***
