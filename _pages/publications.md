---
title: "Publications"
permalink: /publications/
author_profile: true
---
<ol class="publications">

<li>
<strong>Classical Shadows with Arbitrary Group Representations</strong><br>
Maxwell West, Frederic Sauvage, Aniruddha Sen, Roy Forestano, David Wierichs, Nathan Killoran, Dmitry Grinko, M. Cerezo, Martin Larocca<br>
<em>Preprint, 2026</em><br>
<a href="https://arxiv.org/abs/2604.01429">(arXiv)</a>

<details>
<summary>Abstract</summary>
Classical shadows (CS) has recently emerged as an important framework to efficiently predict properties of an unknown quantum state. A common strategy in CS protocols is to parametrize the basis in which one measures the state by a random group action; many examples of this have been proposed and studied on a case-by-case basis. In this work, we present a unified theory that allows us to simultaneously understand CS protocols based on sampling from general group representations, extending previous approaches that worked in simplified (multiplicity-free) settings. We identify a class of measurement bases which we call "centralizing bases" that allows us to analytically characterize and invert the measurement channel, minimizing classical post-processing costs. We complement this analysis by deriving general bounds on the sample-complexity necessary to obtain estimates of a given precision. Beyond its unification of previous CS protocols, our method allows us to readily generate new protocols based on other groups, or different representations of previously considered ones. For example, we characterize novel shadow protocols based on sampling from the spin and tensor representations of \(\mathrm{𝖲𝖴}(2)\), symmetric and orthogonal groups, and the exceptional Lie group \(G2\).
</details>
</li>

<li>
<strong>Nearly Time-Optimal Pure State Tomography with Pauli Measurements</strong>*<br>
Sabee Grewal, Meghal Gupta, William He, Aniruddha Sen, Mihir Singhal<br>
<em>FOCS 2026</em><br>
<a href="https://arxiv.org/abs/2601.04444">(arXiv)</a>

<details>
<summary>Abstract</summary>
We give an algorithm for pure state tomography with near-optimal copy and time complexity using only single-qubit measurements. Specifically, given $\widetilde{O}(2^n / \epsilon)$ copies of an unknown $n$-qubit pure state $\ket{\psi}$, the algorithm performs only nonadaptive Pauli measurements, runs in time $\widetilde{O}(2^n / \epsilon)$, and outputs $\ket{\hat{\psi}}$ with fidelity at least $1 - \epsilon$ with $\ket{\psi}$ with high probability. This is the first algorithm for pure state tomography that achieves near-optimal running time.
</details>
</li>

<li>
<strong>Multipartite Entanglement Distribution in Quantum Networks using Subgraph Complementations</strong><br>
Aniruddha Sen, Kenneth Goodenough, Don Towsley<br>
<em>Quantum</em> 9, 1911 (2025)<br>
<a href="https://arxiv.org/abs/2308.13700">(arXiv)</a> ·
<a href="https://quantum-journal.org/papers/q-2025-11-17-1911/">(Journal)</a>

<details>
<summary>Abstract</summary>
Quantum networks are important for quantum communication, enabling tasks such as quantum teleportation, quantum key distribution, quantum sensing, and quantum error correction, often utilizing graph states, a specific class of multipartite entangled states that can be represented by graphs. We propose a novel approach for distributing graph states across a quantum network. We show that the distribution of graph states can be characterized by a <em>system of subgraph complementations</em>, which we relate to the minimum rank of the underlying graph and the degree of entanglement quantified by the Schmidt rank of the quantum state. We analyze resource usage for our algorithm and show that it improves on the number of qubits, bits for classical communication, and EPR pairs utilized, as compared to prior work. In fact, the number of local operations and resource consumption for our approach scales linearly in the number of vertices. This produces a quadratic improvement in completion time for several classes of graph states represented by dense graphs, which translates into an exponential improvement by allowing parallelization of gate operations. This leads to improved fidelities in the presence of noisy operations, as we show through simulation in the presence of noisy operations. We classify common classes of graph states, along with their optimal distribution time using subgraph complementations. We find a sequence of subgraph complementation operations to distribute an arbitrary graph state which we conjecture is close to the optimal sequence, and establish upper bounds on distribution time along with providing approximate greedy algorithms.
</details>
</li>

<li>
<strong>Diverse Community Data for Benchmarking Data Privacy Algorithms</strong><br>
Aniruddha Sen, Christine Task, Dhruv Kapur, Gary Howarth, Karan Bhagat<br>
<em>NeurIPS</em> 2023<br>
<a href="https://arxiv.org/abs/2306.13216">(arXiv)</a> ·
<a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/a15032f8199511ced4d7a8e2bbb487a5-Paper-Datasets_and_Benchmarks.pdf">(Journal)</a>

<details>
<summary>Abstract</summary>
The Collaborative Research Cycle (CRC) is a National Institute of Standards and Technology (NIST) benchmarking program intended to strengthen understanding of tabular data deidentification technologies. Deidentification algorithms are vulnerable to the same bias and privacy issues that impact other data analytics and machine learning applications, and can even amplify those issues by contaminating downstream applications. This paper summarizes four CRC contributions: theoretical work on the relationship between diverse populations and challenges for equitable deidentification; public benchmark data focused on diverse populations and challenging features; a comprehensive open source suite of evaluation metrology for deidentified datasets; and an archive of more than 450 deidentified data samples from a broad range of techniques. The initial set of evaluation results demonstrate the value of these tools for investigations in this field.
</details>
</li>

</ol>

<details class="pub-note">
<summary><span style="font-weight: 400; color: #666;">*Credit</span></summary>
<small style="color: #777; font-weight: 300;">
Authors are listed in alphabetical order by last name for papers marked with an asterisk (*), as is standard in mathematics and theoretical computer science.
</small>
</details>
