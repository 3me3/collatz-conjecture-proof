https://github.com/3me3/collatz-conjecture-proof/blob/main/collatz-proof.pdf?raw=true


# collatz-conjecture-proof
Formal proof of the Collatz Conjecture using cycle elimination, Lyapunov decay, and bounded stopping time
# Formal Proof of the Collatz Conjecture

This repository presents a formal proof of the Collatz Conjecture.

## Summary

The proof uses three key techniques:
1. **Elimination of Nontrivial Cycles**: Using the Böhm–Sontacchi equation and growth rate analysis.
2. **Lyapunov Function and Entropy Decay**: Demonstrating global descent through weighted energetic arguments.
3. **Bounded Stopping Time**: Applying Tao's ergodic theory results and the Borel–Cantelli lemma.

Together, these components guarantee that every natural number eventually reaches 1 under the Collatz map.

## Files

- `collatz_proof.tex` — LaTeX source of the proof.
- `collatz_proof.pdf` — Compiled PDF version.
- `collatz_simulation.py` — (Optional) Simulation code for Collatz dynamics.

## Contact

Feel free to reach out for collaboration or discussion! Peregrine King p3142@mac.com

---
The Collatz Conjecture is true.



# Project: Resolution of the Collatz Conjecture

## Overview

This project presents a formal proof of the Collatz Conjecture, combining tools from number theory, dynamical systems, and ergodic theory. 

The proof framework relies on three interconnected components:
- **Cycle Elimination**: Nontrivial cycles are ruled out via analysis of the Böhm–Sontacchi equation and growth constraints between linear and exponential terms.
- **Lyapunov Function and Entropy Decay**: A carefully constructed weighted Lyapunov function demonstrates global energetic decay along Collatz trajectories, ensuring convergence.
- **Bounded Stopping Time**: Leveraging Tao's ergodic results and the Borel–Cantelli lemma, we prove that no exceptional divergent trajectories exist, guaranteeing that all natural numbers eventually reach 1.

Together, these elements resolve the Collatz Conjecture.

## Key Results

- **Theorem**:  
  \[
  \boxed{\forall n \in \mathbb{N}^+, \quad \exists k \in \mathbb{N} \quad \text{such that} \quad f^k(n) = 1.}
  \]
  That is, every natural number eventually collapses to 1 under the Collatz map.

- **Methodology**:  
  - Modular arithmetic and cycle growth bounding.
  - Entropy-based energy function analysis.
  - Measure-theoretic arguments to eliminate density-zero exceptions.

- **Related Concepts**:  
  - Extension ideas toward the \( 5n+1 \) conjecture and Aliquot sequences.
  - Links to ergodic theory, dynamical systems, and potential thermodynamic analogies.

## Repository Contents

- `collatz_proof.tex` — LaTeX source file of the formal proof.
- `collatz_proof.pdf` — Compiled proof document (ready for review).
- `collatz_simulation.py` (optional) — Code for simulating Collatz trajectories.

## Future Work

- Explore extensions of the Lyapunov framework to other recurrence conjectures.
- Investigate the modular fractal structures underlying Collatz dynamics.
- Cross-disciplinary applications involving quantum computing and category theory.

---

## Citation

If you use or reference this work, please cite: Peregrine King p3142@mac.com
