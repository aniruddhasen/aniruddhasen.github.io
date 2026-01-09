---
title: "Publications"
permalink: /publications/
author_profile: true
---
<details class="pub-note">
<summary>Credit*</summary>
Authors are listed in alphabetical order by last name for papers marked with an asterisk (*), as is standard in mathematics and theoretical computer science.
</details>

<ol class="publications" reversed>

<li>
<strong>Pauli Measurements Are Near-Optimal for Pure State Tomography</strong>*<br>
Sabee Grewal, Meghal Gupta, William He, Aniruddha Sen, Mihir Singhal<br>
<em>Preprint</em><br>
<a href="https://arxiv.org/abs/2601.04444">(arXiv)</a>

<details>
<summary>Abstract</summary>
We give an algorithm for pure state tomography with near-optimal copy complexity using single-qubit measurements. Specifically, given \(\tilde{O}(2^n/\epsilon)\) copies of an unknown pure \(n\)-qubit state \(|\psi\rangle\), the algorithm performs only <em>nonadaptive Pauli measurements</em>, runs in time \(\mathrm{poly}(2^n,1/\epsilon)\), and outputs \(|\hat{\psi}\rangle\) that has fidelity \(1-\epsilon\) with \(|\psi\rangle\) with high probability. This improves upon the previous best copy complexity bound of \(\tilde{O}(3^n/\epsilon)\).
</details>
</li>

<li>
<strong>Multipartite Entanglement in Quantum Networks using Subgraph Complementations</strong><br>
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
<em>NeurIPS</em>, 2023<br>
<a href="https://arxiv.org/abs/2306.13216">(arXiv)</a> ·
<a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/a15032f8199511ced4d7a8e2bbb487a5-Paper-Datasets_and_Benchmarks.pdf">(Journal)</a>

<details>
<summary>Abstract</summary>
The Collaborative Research Cycle (CRC) is a National Institute of Standards and Technology (NIST) benchmarking program intended to strengthen understanding of tabular data deidentification technologies. Deidentification algorithms are vulnerable to the same bias and privacy issues that impact other data analytics and machine learning applications, and can even amplify those issues by contaminating downstream applications. This paper summarizes four CRC contributions: theoretical work on the relationship between diverse populations and challenges for equitable deidentification; public benchmark data focused on diverse populations and challenging features; a comprehensive open source suite of evaluation metrology for deidentified datasets; and an archive of more than 450 deidentified data samples from a broad range of techniques. The initial set of evaluation results demonstrate the value of these tools for investigations in this field.
</details>
</li>

</ol>
