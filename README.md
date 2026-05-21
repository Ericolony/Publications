# Tianchen Zhao — Publications

This repository contains publication pages for 17 research papers spanning deepfake detection, face anti-spoofing, generative modeling, neural quantum states, and scientific machine learning. Each paper has a dedicated page with abstract, key contributions, citation information, and related links.

---

## Papers by Topic

### Deepfake Detection and Face Security

| Paper | Venue | Year | Citations |
|-------|-------|------|-----------|
| [Learning Self-Consistency for Deepfake Detection](./learning-self-consistency-for-deepfake-detection/) | ICCV | 2021 | 538 |
| [Principles of Designing Robust Remote Face Anti-Spoofing Systems](./principles-of-designing-robust-remote-face-anti-spoofing-systems/) | arXiv | 2024 | 10 |
| [Optimal Transport-Guided Source-Free Adaptation for Face Anti-Spoofing](./optimal-transport-guided-source-free-adaptation-for-face-anti-spoofing/) | CVPR | 2025 | 8 |
| [AuthGuard: Generalizable Deepfake Detection via Language Guidance](./authguard-generalizable-deepfake-detection-via-language-guidance/) | WACV | 2025 | 2 |

- **Learning Self-Consistency for Deepfake Detection** — Detects deepfakes by learning to extract and compare source-feature inconsistencies within forged images, achieving state-of-the-art cross-dataset generalization.
- **Principles of Designing Robust Remote Face Anti-Spoofing Systems** — Presents a comprehensive taxonomy of face anti-spoofing threats and proposes design principles for building robust systems resilient to digital injection, deepfake, and replay attacks.
- **Optimal Transport-Guided Source-Free Adaptation for Face Anti-Spoofing** — Enables privacy-preserving test-time adaptation of face anti-spoofing models via optimal transport-guided prototype matching and geodesic mixup augmentation.
- **AuthGuard: Generalizable Deepfake Detection via Language Guidance** — Integrates language guidance and commonsense reasoning into deepfake detection via vision-language contrastive learning, achieving state-of-the-art generalization across unseen forgery methods.

### Generative Modeling, Robustness, and Vision-Language Adaptation

| Paper | Venue | Year | Citations |
|-------|-------|------|-----------|
| [Diversity-Sensitive Conditional Generative Adversarial Networks](./diversity-sensitive-conditional-generative-adversarial-networks/) | ICLR | 2019 | 268 |
| [Adversarial Defense via Learning to Generate Diverse Attacks](./adversarial-defense-via-learning-to-generate-diverse-attacks/) | ICCV | 2019 | 108 |
| [Salient Concept-Aware Generative Data Augmentation](./salient-concept-aware-generative-data-augmentation/) | arXiv | 2025 | 1 |
| [Model Diagnosis and Correction via Linguistic and Implicit Attribute Editing](./model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing/) | CVPR | 2025 | 1 |
| [Decoupling Vision and Language: Codebook Anchored Visual Adaptation](./decoupling-vision-and-language-codebook-anchored-visual-adaptation/) | arXiv | 2026 | 0 |

- **Diversity-Sensitive Conditional Generative Adversarial Networks** — Proposes a simple diversity-sensitive regularization for conditional GANs that explicitly encourages diverse outputs, solving mode collapse across image translation, inpainting, and video prediction.
- **Adversarial Defense via Learning to Generate Diverse Attacks** — Trains a stochastic generator to produce diverse adversarial attacks, yielding more robust defenses than single-attack adversarial training.
- **Salient Concept-Aware Generative Data Augmentation** — Proposes a salient concept-aware generative augmentation framework that disentangles class-discriminative features from irrelevant context, improving fine-grained recognition under both conventional and long-tail settings.
- **Model Diagnosis and Correction via Linguistic and Implicit Attribute Editing** — Automates model diagnosis and correction by analyzing error patterns, testing causal hypotheses via attribute editing, and generating counterfactual training samples for improved robustness.
- **Decoupling Vision and Language: Codebook Anchored Visual Adaptation** — Introduces CRAFT, a discrete-codebook method for adapting vision encoders in LVLMs to domain-specific tasks without modifying the language model, enabling portable encoder adaptation across architectures.

### Neural Quantum States and Scientific Machine Learning

| Paper | Venue | Year | Citations |
|-------|-------|------|-----------|
| [Scalable Neural Quantum States Architecture for Quantum Chemistry](./scalable-neural-quantum-states-architecture-for-quantum-chemistry/) | ML: Science and Technology | 2023 | 65 |
| [Natural Evolution Strategies and Variational Monte Carlo](./natural-evolution-strategies-and-variational-monte-carlo/) | ML: Science and Technology | 2021 | 32 |
| [Overcoming Barriers to Scalability in Variational Quantum Monte Carlo](./overcoming-barriers-to-scalability-in-variational-quantum-monte-carlo/) | SC | 2021 | 27 |
| [Natural Evolution Strategies and Quantum Approximate Optimization](./natural-evolution-strategies-and-quantum-approximate-optimization/) | arXiv | 2020 | 8 |
| [Meta Variational Monte Carlo](./meta-variational-monte-carlo-arxiv/) | arXiv | 2020 | 4 |
| [Meta-Variational Quantum Monte Carlo](./meta-variational-quantum-monte-carlo/) | Quantum Machine Intelligence | 2023 | 0 |
| [Neural Quantum States for Scientific Computing](./neural-quantum-states-for-scientific-computing/) | PhD Thesis, U. of Michigan | 2022 | 0 |

- **Scalable Neural Quantum States Architecture for Quantum Chemistry** — Introduces GPU-scalable parallelization strategies for neural-network variational Monte Carlo applied to ab-initio quantum chemistry, achieving systematic speedups over existing neural-network methods.
- **Natural Evolution Strategies and Variational Monte Carlo** — Introduces quantum natural evolution strategies as a geometric unification of quantum/classical black-box optimization algorithms, achieving competitive Max-Cut approximation ratios.
- **Overcoming Barriers to Scalability in Variational Quantum Monte Carlo** — Replaces MCMC with autoregressive exact sampling in variational quantum Monte Carlo, enabling GPU-scalable parallelism for up to ten-thousand dimensional problems.
- **Natural Evolution Strategies and Quantum Approximate Optimization** — Applies natural evolution strategies to quantum approximate optimization, achieving competitive Max-Cut approximation ratios via neural quantum states.
- **Meta Variational Monte Carlo** — Connects meta-learning to quantum ground-state problems, proposing Meta Variational Monte Carlo that accelerates training and improves convergence on random Max-Cut instances.
- **Meta-Variational Quantum Monte Carlo** — Journal version presenting Meta Variational Monte Carlo, which applies meta-learning to accelerate neural quantum state optimization across random Hamiltonian ensembles.
- **Neural Quantum States for Scientific Computing** — PhD thesis synthesizing neural quantum states for scientific computing, covering variational Monte Carlo for quantum chemistry, combinatorial optimization, and financial derivative pricing.

### Quantum-Inspired Scientific Computing and Finance

| Paper | Venue | Year | Citations |
|-------|-------|------|-----------|
| [Quantum-Inspired Variational Algorithms for Partial Differential Equations](./quantum-inspired-variational-algorithms-for-partial-differential-equations/) | Quantitative Finance | 2024 | 16 |

- **Quantum-Inspired Variational Algorithms for Partial Differential Equations** — Generalizes variational quantum Monte Carlo with neural-network quantum states to solve arbitrary time-dependent PDEs, demonstrated on multi-asset Black-Scholes option pricing.

---

## How to Cite

Each paper page includes a recommended BibTeX entry. For all entries in one file, see [`citation.bib`](./citation.bib).

## Machine-Readable Resources

- [`papers.json`](./papers.json) — Structured metadata for all publications
- [`citation.bib`](./citation.bib) — BibTeX entries for all papers
- [`llms.txt`](./llms.txt) — LLM-friendly plain-text summary of all publications
- [`sitemap.xml`](./sitemap.xml) — Sitemap for search engine indexing

## External Profiles

- [Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=-uCJznsAAAAJ)
- [Semantic Scholar](https://www.semanticscholar.org/author/2305116981)
- [DBLP](https://dblp.org/pid/217/2471)
