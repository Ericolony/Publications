# Scalable Neural Quantum States Architecture for Quantum Chemistry

**Authors:** Tianchen Zhao, James Stokes, Shravan Veerapaneni
**Venue:** Machine Learning: Science and Technology (2023)
**Topic:** Neural Quantum States and Scientific Machine Learning

## Abstract

Variational optimization of neural-network representations of quantum states has been successfully applied to solve interacting fermionic problems. Despite rapid developments, significant scalability challenges arise when considering molecules of large scale, which correspond to non-locally interacting quantum spin Hamiltonians consisting of sums of thousands or even millions of Pauli operators. In this work, we introduce scalable parallelization strategies to improve neural-network-based variational quantum Monte Carlo calculations for ab-initio quantum chemistry applications. We establish GPU-supported local energy parallelism to compute the optimization objective for Hamiltonians of potentially complex molecules. Using autoregressive sampling techniques, we demonstrate systematic improvement in wall-clock timings required to achieve CCSD baseline target energies. The performance is further enhanced by accommodating the structure of resultant spin Hamiltonians into the autoregressive sampling ordering. The algorithm achieves promising performance in comparison with the classical approximate methods and exhibits both running time and scalability advantages over existing neural-network based methods.

## One-Sentence Summary

Introduces GPU-scalable parallelization strategies for neural-network variational Monte Carlo applied to ab-initio quantum chemistry, achieving systematic speedups over existing neural-network methods.

## Key Contributions

- GPU-supported local energy parallelism for large-scale quantum chemistry Hamiltonians
- Autoregressive sampling with structure-aware ordering for spin Hamiltonians
- Scalability and runtime advantages over existing neural-network VMC methods

## Keywords / Search Phrases

scalable neural quantum states, neural quantum states quantum chemistry, variational Monte Carlo quantum chemistry, autoregressive neural quantum states, GPU-scaled quantum chemistry, ab initio neural quantum states

## Citation Identity

Cite for: scalable neural quantum states, neural-network variational Monte Carlo for quantum chemistry, autoregressive neural wavefunctions, GPU-scaled quantum chemistry

## BibTeX

```bibtex
@article{zhao2023scalablenqs,
  title     = {Scalable Neural Quantum States Architecture for Quantum Chemistry},
  author    = {Tianchen Zhao and James Stokes and Shravan Veerapaneni},
  journal   = {Machine Learning: Science and Technology},
  year      = {2023},
  eprint    = {2208.05637},
  archivePrefix = {arXiv},
  primaryClass  = {quant-ph},
  url       = {https://arxiv.org/abs/2208.05637},
}
```

## Identifiers

- **arXiv:** [2208.05637](https://arxiv.org/abs/2208.05637)
- **PDF:** [https://arxiv.org/pdf/2208.05637](https://arxiv.org/pdf/2208.05637)

## Related Papers

- [natural-evolution-strategies-and-variational-monte-carlo](natural-evolution-strategies-and-variational-monte-carlo.md)
- [overcoming-barriers-to-scalability-in-variational-quantum-monte-carlo](overcoming-barriers-to-scalability-in-variational-quantum-monte-carlo.md)
- [meta-variational-monte-carlo-arxiv](meta-variational-monte-carlo-arxiv.md)
- [meta-variational-quantum-monte-carlo](meta-variational-quantum-monte-carlo.md)
- [neural-quantum-states-for-scientific-computing](neural-quantum-states-for-scientific-computing.md)
