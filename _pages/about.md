---
permalink: /
title: About Me
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year PhD student in the Computer Science department at the [University of Texas at Austin](https://www.cs.utexas.edu), where I am advised by [Scott Aaronson](https://www.scottaaronson.com) and [Nick Hunter-Jones](https://nickrhj.github.io). I am broadly interested in quantum computing and theoretical computer science. I'm affiliated with UT's [Theory Group](https://www.cs.utexas.edu/act) and [Quantum Information Center](https://www.cs.utexas.edu/~qic/), and supported by a [TQI Graduate Fellowship](https://quantum.utexas.edu).

I previously graduated from the [University of Massachusetts Amherst](https://www.cics.umass.edu) with a B.S. degree double majoring in computer science and mathematics. During my undergraduate, I worked under [Don Towsley](https://www.cics.umass.edu/about/directory/donald-towsley) as part of the [ACQuIRe Lab](https://acquire.cs.umass.edu) at UMass. I recently spent a summer interning at [Visa Research](https://usa.visa.com/about-visa/visa-research.html) in their quantum computing team, and prior to that I was a research fellow at Los Alamos National Laboratory, as part of their [Quantum Computing Summer School Fellowship](https://www.lanl.gov/engage/collaboration/internships/summer-schools/quantumschool).

## Selected Papers
<ol class="publications">
  
<li>
<strong>Nearly Time-Optimal Pure State Tomography with Pauli Measurements</strong><br>
Sabee Grewal, Meghal Gupta, William He, Aniruddha Sen, Mihir Singhal<br>
FOCS 2026<br>
<a href="https://arxiv.org/abs/2601.04444">(arXiv)</a>

<details>
<summary>Abstract</summary>
We give an algorithm for pure state tomography with near-optimal copy and time complexity using only single-qubit measurements. Specifically, given $\widetilde{O}(2^n / \epsilon)$ copies of an unknown $n$-qubit pure state $\ket{\psi}$, the algorithm performs only nonadaptive Pauli measurements, runs in time $\widetilde{O}(2^n / \epsilon)$, and outputs $\ket{\hat{\psi}}$ with fidelity at least $1 - \epsilon$ with $\ket{\psi}$ with high probability. This is the first algorithm for pure state tomography that achieves near-optimal running time.
</details>
</li>

<li>
<strong>Local random quantum circuits converge to the Porter-Thomas distribution in polynomial depth</strong><br>
Aniruddha Sen, Nick Hunter-Jones <br>
Preprint (2026) <br>
<a href="https://arxiv.org/abs/2610.02125">(arXiv)</a>

<details>
<summary>Abstract</summary>
Porter-Thomas statistics are a characteristic feature of the output distribution of random quantum states and, more broadly, chaotic quantum many-body systems. Convergence to Porter-Thomas plays a central role in random circuit sampling and experimental demonstrations of quantum advantage, where the output statistics of low-depth random quantum circuits are expected to be approximately Porter-Thomas, despite the absence of a rigorous proof of con- vergence. We show that the output distribution of polynomial-depth brickwork random circuits converges inverse-polynomially in total variation distance to the Porter-Thomas distribution. Specifically, consider the output probability distribution over a fixed bitstring of a local ran- dom quantum circuit, constructed from nearest-neighbor Haar random gates. Then, for any \(m \ge 0\), the distribution corresponding to circuits of depth \(O(n^{2m+1} \log(n))\) is at most \(O(1/n^m)\) far in total variation distance from the Porter-Thomas distribution. Our proof uses moment bounds from approximate designs, analytic estimates for characteristic functions, and a local anticoncentration property for inverse moments.
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
<strong>Classical Shadows with Arbitrary Group Representations</strong><br>
Maxwell West, Frederic Sauvage, Aniruddha Sen, Roy Forestano, David Wierichs, Nathan Killoran, Dmitry Grinko, M. Cerezo, Martin Larocca<br>
QTML 2025<br>
<a href="https://arxiv.org/abs/2604.01429">(arXiv)</a>

<details>
<summary>Abstract</summary>
Classical shadows (CS) has recently emerged as an important framework to efficiently predict properties of an unknown quantum state. A common strategy in CS protocols is to parametrize the basis in which one measures the state by a random group action; many examples of this have been proposed and studied on a case-by-case basis. In this work, we present a unified theory that allows us to simultaneously understand CS protocols based on sampling from general group representations, extending previous approaches that worked in simplified (multiplicity-free) settings. We identify a class of measurement bases which we call "centralizing bases" that allows us to analytically characterize and invert the measurement channel, minimizing classical post-processing costs. We complement this analysis by deriving general bounds on the sample-complexity necessary to obtain estimates of a given precision. Beyond its unification of previous CS protocols, our method allows us to readily generate new protocols based on other groups, or different representations of previously considered ones. For example, we characterize novel shadow protocols based on sampling from the spin and tensor representations of \(\mathrm{𝖲𝖴}(2)\), symmetric and orthogonal groups, and the exceptional Lie group \(G2\).
</details>
</li>
