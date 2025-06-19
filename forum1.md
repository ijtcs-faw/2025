
---
id: forum1
title: Forum 1: Quantum computing
sidebar_label: Forum 1
---


## Talk 1

### Title: On the Computational Power of QAC0 with Barely Superlinear Ancillae

$\mathrm{QAC}^0$ is the family of constant-depth polynomial-size quantum circuits consisting of arbitrary single qubit unitaries and multi-qubit Toffoli gates. It was introduced by Moore [arXiv: 9903046] as a quantum counterpart of $\mathrm{AC}^0$, along with the conjecture that $\mathrm{QAC}^0$ circuits can not compute PARITY. In this work we make progress on this longstanding conjecture: we show that any depth-$d$ $\mathrm{QAC}^0$ circuit requires $n^{1+3^{-d}}$ ancillae to compute a function with approximate degree $\Theta(n)$, which includes PARITY, MAJORITY and $\mathrm{MOD}_k$. This is the first superlinear lower bound on the size of the ancillae required for computing parity. We further establish superlinear lower bounds on quantum state synthesis and quantum channel synthesis. These lower bounds are derived by giving low-degree approximations to $\mathrm{QAC}^0$ circuits. We show that a depth-$d$ $\mathrm{QAC}^0$ circuit with $a$ ancillae, when applied to low-degree operators, has a degree $(n+a)^{1-3^{-d}}$ polynomial approximation in the spectral norm. This implies that the class $\mathrm{QLC}^0$, corresponding to linear size $\mathrm{QAC}^0$ circuits, has approximate degree $o(n)$. This is a quantum generalization of the result that $\mathrm{LC}^0$ circuits have approximate degree $o(n)$ by Bun, Kothari, and Thaler [SODA 2019]. Our result also implies that $\mathrm{QLC}^0\neq\mathrm{NC}^1$.


### bio 
Penghui Yao is a professor in the Department of Computer Science and Technology, Nanjing University. He obtained his doctoral degree from Centre for Quantum Technology, National University of Singapore. Prior to joining Nanjing University, He was a postdoctoral researcher at CWI Netherlands;  IQC University of Waterloo and QuICS University of Maryland. His research mainly focuses on quantum algorithms, quantum information theory and quantum computational complexity.


## Talk 2
### Title: State Similarity in Modular Superconducting Quantum Processors with Classical Communications

As quantum devices continue to scale, distributed quantum computing emerges as a promising strategy for executing large-scale tasks across modular quantum processors. A central challenge in this paradigm is verifying the correctness of computational outcomes when subcircuits are executed independently following circuit cutting. In this work, we propose a cross-platform fidelity estimation algorithm tailored for modular architectures. Our method achieves substantial reductions in sample complexity compared to previous approaches designed for single-processor systems. We experimentally implement the protocol on modular superconducting quantum processors with up to 6 qubits to verify the similarity of two 11-qubit GHZ states. Beyond verification, we show that our algorithm enables a federated quantum kernel method that preserves data privacy. As a proof of concept, we apply it to a 5-qubit quantum phase learning task using six 3-qubit modules, successfully extracting phase information with just eight training samples. These results establish a practical path for
scalable verification and trustworthy quantum machine learning of modular quantum processors.

Reference: Wu, Bujiao, et al. "State Similarity in Modular Superconducting Quantum Processors with Classical Communications." arXiv preprint arXiv:2506.01657 (2025).

### Bio
Bujiao Wu, an associate researcher at the International Quantum Academy. Her main research areas include the design of quantum algorithms, optimization of quantum circuits, quantum randomized measurements, quantum machine learning, and quantum advantages.


## Talk 3

### Title: Learning unitary process with autoregressive neural network

Characterizing quantum processes is a cornerstone of quantum information science, but conventional techniques like quantum process tomography (QPT) demand extensive resources and suffer from poor scalability. Here, we propose a learning-based approach that leverages the generative model to efficiently learn Hamiltonian dynamics. By decomposing such dynamics into a linear combination of Pauli operators, with the expansion coefficients parameterized by an autoregressive neural network (ARNN), we design an infidelity loss and then train the ARNN to learn such unitary process. Our numerical experiments demonstrate that our proposed model offers a scalable and flexible pathway for characterizing quantum operations with potential applications in quantum computing and quantum information processing.

### Bio
Yiming Huang, a postdoctoral fellow at the Center on Frontiers of Computing Studies, Peking University, mainly focus on quantum algorithm and optimization for NISQ devices, and leveraging machine learning to tackle problems in quantum chemistry and many-body physics. His work aims to advance the application of quantum computing and machine learning in complex optimization and data processing.
