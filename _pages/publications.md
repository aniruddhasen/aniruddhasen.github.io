---
title: "Papers"
permalink: /publications/
author_profile: true
---
<ol class="publications">

<li>
<strong>Local random quantum circuits converge to the Porter-Thomas distribution in polynomial depth</strong><br>
Aniruddha Sen, Nick Hunter-Jones <br>
Preprint (2026) <br>
<a href="https://arxiv.org/abs/2610.02125">(arXiv)</a>

<details>
<summary>Abstract</summary>
Porter-Thomas statistics are a characteristic feature of the output distribution of random quantum states and, more broadly, chaotic quantum many-body systems. Convergence to Porter-Thomas plays a central role in random circuit sampling and experimental demonstrations of quantum advantage, where the output statistics of low-depth random quantum circuits are expected to be approximately Porter-Thomas, despite the absence of a rigorous proof of convergence. We show that the output distribution of polynomial-depth brickwork random circuits converges inverse-polynomially in total variation distance to the Porter-Thomas distribution. Specifically, consider the output probability distribution over a fixed bitstring of a local ran- dom quantum circuit, constructed from nearest-neighbor Haar random gates. Then, for any \(m \ge 0\), the distribution corresponding to circuits of depth \(O(n^{2m+1} \log(n))\) is at most \(O(1/n^m)\) far in total variation distance from the Porter-Thomas distribution. Our proof uses moment bounds from approximate designs, analytic estimates for characteristic functions, and a local anticoncentration property for inverse moments.
</details>
</li>

<li>
<strong>Device-Independent Conference Keys from Parity-Extended Games</strong><br>
Suvradip Chakraborty, Ronak Ramachandran, Aniruddha Sen* <br>
Preprint (2026) <br>
<a href="https://arxiv.org/abs/2610.01025">(arXiv)</a>

<details>
<summary>Abstract</summary>
Device-independent conference key agreement (DI-CKA) lets a group of parties establish a shared secret key from untrusted quantum devices, with security certified by non-locality. Existing DI-CKA protocols are each built around a single Bell inequality, typically a multiparty variant of the CHSH game. DI-QKD protocols, in contrast, have been built from a much richer landscape of non-local games, and it has remained unclear how to carry this landscape over to the conference setting. We introduce Parity-\(G\) games, which extend any two-player game \(G\) to \(N\) players, for every \(N\), provided \(G\) has an optimal strategy in which one player measures Pauli observables. The extension preserves the quantum and classical values of \(G\), and the security of the resulting \(N\)-party protocol follows from an analysis of the two-player game alone. Our framework recovers the Parity-CHSH game of Ribeiro, Murta and Wehner (Phys. Rev. A, 2018) as a special case. Applied to the Mermin-Peres Magic Square Game, it yields a new \(N\)-player pseudo-telepathy game, the Parity Magic Square Game, which ideal devices win in every round. We use it to construct the first DI-CKA protocol based on a pseudo-telepathy game. We prove the protocol secure against coherent attacks. It produces up to two key bits per round, and at low noise its key rate exceeds that of the DI-CKA protocol based on the Parity-CHSH game.
</details>
</li>

<li>
<strong>Learning Sparse Quantum States</strong><br>
Aniruddha Sen <br>
Preprint (2026) <br>
<a href="https://arxiv.org/abs/2609.12219">(arXiv)</a>

<details>
<summary>Abstract</summary>
We study the problem of tomography for \(k\)-sparse quantum states. In contrast to classical distribution learning, where tight sample and time complexity bounds in terms of support size are well understood, no non-trivial bounds were previously shown for this problem. We give the first near optimal algorithm for learning \(n\)-qubit \(k\)-sparse pure quantum states, obtaining fidelity at least \(1−\varepsilon\) with high probability using \(\tilde{O}(k/\varepsilon)\) copies of the state and \(\tilde{O}(kn/\varepsilon)\) time. Both bounds are optimal up to polylogarithmic factors. As an implication, we also obtain an algorithm with near optimal \(\tilde{O}(kr/\varepsilon)\) sample complexity for learning \(k\)-sparse rank-\(r\) mixed states, via the random purification channel technique. Obtaining time complexity nearly matching the sample complexity, for \(r>1\), remains an important open question.
</details>
</li>

<li>
<strong>Nearly Time-Optimal Pure State Tomography with Pauli Measurements</strong><br>
Sabee Grewal, Meghal Gupta, William He, Aniruddha Sen*, Mihir Singhal<br>
FOCS 2026<br>
<a href="https://arxiv.org/abs/2601.04444">(arXiv)</a>

<details>
<summary>Abstract</summary>
We give an algorithm for pure state tomography with near-optimal copy and time complexity using only single-qubit measurements. Specifically, given \(\widetilde{O}\left(\frac{2^n}{\epsilon}\right)\) copies of an unknown \(n\)-qubit pure state \(\lvert \psi \rangle\), the algorithm performs only nonadaptive Pauli measurements, runs in time \(\widetilde{O}\left(\frac{2^n}{\epsilon}\right)\), and outputs \(\lvert \hat{\psi} \rangle\) with fidelity at least \(1 - \epsilon\) with \(\lvert \psi \rangle\) with high probability. This is the first algorithm for pure state tomography that achieves near-optimal running time.
</details>
</li>

<li>
<strong>Classical Shadows with Arbitrary Group Representations</strong><br>
Maxwell West, Frederic Sauvage, Aniruddha Sen, Roy Forestano, David Wierichs, Nathan Killoran, Dmitry Grinko, M. Cerezo, Martin Larocca<br>
QTML 2025<br>
<a href="https://arxiv.org/abs/2604.01429">(arXiv)</a>

<details>
<summary>Abstract</summary>
Classical shadows (CS) has recently emerged as an important framework to efficiently predict properties of an unknown quantum state. A common strategy in CS protocols is to parametrize the basis in which one measures the state by a random group action; many examples of this have been proposed and studied on a case-by-case basis. In this work, we present a unified theory that allows us to simultaneously understand CS protocols based on sampling from general group representations, extending previous approaches that worked in simplified (multiplicity-free) settings. We identify a class of measurement bases which we call "centralizing bases" that allows us to analytically characterize and invert the measurement channel, minimizing classical post-processing costs. We complement this analysis by deriving general bounds on the sample-complexity necessary to obtain estimates of a given precision. Beyond its unification of previous CS protocols, our method allows us to readily generate new protocols based on other groups, or different representations of previously considered ones. For example, we characterize novel shadow protocols based on sampling from the spin and tensor representations of \(\mathrm{𝖲𝖴}(2)\), symmetric and orthogonal groups, and the exceptional Lie group \(G2\).
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
NeurIPS 2023<br>
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
