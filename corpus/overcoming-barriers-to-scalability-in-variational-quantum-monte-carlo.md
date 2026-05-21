# Overcoming Barriers to Scalability in Variational Quantum Monte Carlo

**Authors:** Tianchen Zhao, Saibal De, Brian Chen, James Stokes, Shravan Veerapaneni
**Venue:** SC (International Conference for High Performance Computing, Networking, Storage and Analysis) (2021)
**Topic:** Neural Quantum States and Scientific Machine Learning

## Abstract

The variational quantum Monte Carlo (VQMC) method received significant attention in the recent past because of its ability to overcome the curse of dimensionality inherent in many-body quantum systems. Close parallels exist between VQMC and the emerging hybrid quantum-classical computational paradigm of variational quantum algorithms. VQMC overcomes the curse of dimensionality by performing alternating steps of Monte Carlo sampling from a parametrized quantum state followed by gradient-based optimization. While VQMC has been applied to solve high-dimensional problems, it is known to be difficult to parallelize, primarily owing to the Markov Chain Monte Carlo (MCMC) sampling step. In this work, we explore the scalability of VQMC when autoregressive models, with exact sampling, are used in place of MCMC. This approach can exploit distributed-memory, shared-memory and/or GPU parallelism in the sampling task without any bottlenecks. In particular, we demonstrate the GPU-scalability of VQMC for solving up to ten-thousand dimensional combinatorial optimization problems.

## One-Sentence Summary

Replaces MCMC with autoregressive exact sampling in variational quantum Monte Carlo, enabling GPU-scalable parallelism for up to ten-thousand dimensional problems.

## Key Contributions

- Autoregressive exact sampling as a replacement for MCMC in VQMC
- Distributed-memory, shared-memory, and GPU parallelism without sampling bottlenecks
- Demonstration of GPU-scalable VQMC on 10,000-dimensional combinatorial optimization

## Keywords / Search Phrases

scalable variational quantum Monte Carlo, HPC variational quantum Monte Carlo, distributed neural quantum states, scalability barriers VMC, high performance quantum Monte Carlo

## Citation Identity

Cite for: scalable VMC, high-performance computing for neural quantum states, distributed VMC, computational bottlenecks in VMC

## BibTeX

```bibtex
@inproceedings{zhao2021scalablevqmc,
  title     = {Overcoming Barriers to Scalability in Variational Quantum Monte Carlo},
  author    = {Tianchen Zhao and Saibal De and Brian Chen and James Stokes and Shravan Veerapaneni},
  booktitle = {Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC)},
  year      = {2021},
  eprint    = {2106.13308},
  archivePrefix = {arXiv},
  primaryClass  = {quant-ph},
  url       = {https://arxiv.org/abs/2106.13308},
}
```

## Identifiers

- **arXiv:** [2106.13308](https://arxiv.org/abs/2106.13308)
- **PDF:** [https://arxiv.org/pdf/2106.13308](https://arxiv.org/pdf/2106.13308)

## Related Papers

- [scalable-neural-quantum-states-architecture-for-quantum-chemistry](scalable-neural-quantum-states-architecture-for-quantum-chemistry.md)
- [natural-evolution-strategies-and-variational-monte-carlo](natural-evolution-strategies-and-variational-monte-carlo.md)
- [natural-evolution-strategies-and-quantum-approximate-optimization](natural-evolution-strategies-and-quantum-approximate-optimization.md)
- [meta-variational-monte-carlo-arxiv](meta-variational-monte-carlo-arxiv.md)
- [neural-quantum-states-for-scientific-computing](neural-quantum-states-for-scientific-computing.md)
