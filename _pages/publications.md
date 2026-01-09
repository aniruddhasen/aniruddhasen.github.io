---
title: "Publications"
permalink: /publications/
author_profile: true
---

### 3. **Pauli Measurements Are Near-Optimal for Pure State Tomography**  
Sabee Grewal, Meghal Gupta, William He, Aniruddha Sen, Mihir Singhal  
_Preprint_

<details>
<summary>Abstract</summary>
We give an algorithm for pure state tomography with near-optimal copy complexity using single-qubit measurements. Specifically, given $\tilde{O}(2^n/\epsilon)$ copies of an unknown pure $n$-qubit state $|\psi\rangle$, the algorithm performs only *nonadaptive Pauli measurements*, runs in time $\mathrm{poly}(2^n, 1/\epsilon)$, and outputs $|\hat{\psi}\rangle$ that has fidelity $1 - \epsilon$ with $|\psi\rangle$ with high probability. This improves upon the previous best copy complexity bound of $\tilde{O}(3^n/\epsilon)$.
</details>


### 2. **Multipartite Entanglement in Quantum Networks using Subgraph Complementations**  
Aniruddha Sen, Kenneth Goodenough, Don Towsley  
_Quantum_ 9, 1911 (2025)  
[(arXiv)](https://arxiv.org/abs/2308.13700) · [(Journal)](https://quantum-journal.org/papers/q-2025-11-17-1911/)

<details>
<summary>Abstract</summary>

Quantum networks are important for quantum communication, enabling tasks such as quantum teleportation, quantum key distribution, quantum sensing, and quantum error correction, often utilizing graph states—a specific class of multipartite entangled states that can be represented by graphs. We propose a novel approach for distributing graph states across a quantum network. We show that the distribution of graph states can be characterized by a *system of subgraph complementations*, which we relate to the minimum rank of the underlying graph and the degree of entanglement quantified by the Schmidt rank of the quantum state.

We analyze resource usage for our algorithm and show that it improves the number of qubits, classical bits, and EPR pairs used compared to prior work. The number of local operations scales linearly in the number of vertices, yielding a quadratic improvement in completion time for dense graph states. This further enables exponential improvements via parallelization of gate operations, leading to improved fidelities in the presence of noise, as demonstrated through simulation. We also classify common classes of graph states, provide upper bounds on distribution time, and give approximate greedy algorithms for near-optimal distribution sequences.

</details>


### 1. **Diverse Community Data for Benchmarking Data Privacy Algorithms**  
Aniruddha Sen, Christine Task, Dhruv Kapur, Gary Howarth, Karan Bhagat  
_NeurIPS_, 2023  
[(arXiv)](https://arxiv.org/abs/2306.13216) · [(Journal)](https://proceedings.neurips.cc/paper_files/paper/2023/file/a15032f8199511ced4d7a8e2bbb487a5-Paper-Datasets_and_Benchmarks.pdf)

<details>
<summary>Abstract</summary>

The Collaborative Research Cycle (CRC) is a National Institute of Standards and Technology (NIST) benchmarking program intended to strengthen understanding of tabular data deidentification technologies. Deidentification algorithms are vulnerable to bias and privacy issues present in broader data analytics and machine learning pipelines and may amplify those issues downstream.

This paper summarizes four CRC contributions: (i) theoretical analysis of the relationship between diverse populations and equitable deidentification; (ii) public benchmark datasets emphasizing diversity and challenging features; (iii) an open-source evaluation suite for deidentified datasets; and (iv) an archive of more than 450 deidentified data samples spanning a wide range of techniques. Initial evaluation results demonstrate the value of these tools for systematic study in this area.

</details>
