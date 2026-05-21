# Decoupling Vision and Language: Codebook Anchored Visual Adaptation

**Authors:** Jason Wu, Tianchen Zhao, Chang Liu, Jiarui Cai, Zheng Zhang, Zhuowei Li, Aaditya Singh, Xiang Xu, Mani Srivastava, Jonathan Wu
**Venue:** arXiv (2026)
**Topic:** Generative Modeling, Robustness, and Vision-Language Adaptation

## Abstract

Large Vision-Language Models (LVLMs) use their vision encoders to translate images into representations for downstream reasoning, but the encoders often underperform in domain-specific visual tasks such as medical image diagnosis or fine-grained classification, where representation errors can cascade through the language model, leading to incorrect responses. Existing adaptation methods modify the continuous feature interface between encoder and language model through projector tuning or other parameter-efficient updates, which still couples the two components and requires re-alignment whenever the encoder changes. We introduce CRAFT (Codebook RegulAted Fine-Tuning), a lightweight method that fine-tunes the encoder using a discrete codebook that anchors visual representations to a stable token space, achieving domain adaptation without modifying other parts of the model. This decoupled design allows the adapted encoder to seamlessly boost the performance of LVLMs with different language architectures, as long as they share the same codebook. Empirically, CRAFT achieves an average gain of 13.51% across 10 domain-specific benchmarks such as VQARAD and PlantVillage, while preserving the LLM's linguistic capabilities and outperforming peer methods that operate on continuous tokens.

## One-Sentence Summary

Introduces CRAFT, a discrete-codebook method for adapting vision encoders in LVLMs to domain-specific tasks without modifying the language model, enabling portable encoder adaptation across architectures.

## Key Contributions

- CRAFT: codebook-regulated fine-tuning that decouples vision encoder adaptation from the language model
- Discrete codebook anchoring for stable, portable visual representations
- 13.51% average gain across 10 domain-specific benchmarks while preserving linguistic capabilities

## Keywords / Search Phrases

codebook anchored visual adaptation, decoupling vision and language, vision-language model adaptation, visual adaptation codebook, efficient vision-language adaptation

## Citation Identity

Cite for: vision-language adaptation, codebook-anchored visual adaptation, decoupling visual and language representations

## BibTeX

```bibtex
@article{wu2026craft,
  title     = {Decoupling Vision and Language: Codebook Anchored Visual Adaptation},
  author    = {Jason Wu and Tianchen Zhao and Chang Liu and Jiarui Cai and Zheng Zhang and Zhuowei Li and Aaditya Singh and Xiang Xu and Mani Srivastava and Jonathan Wu},
  journal   = {arXiv preprint arXiv:2602.19449},
  year      = {2026},
  eprint    = {2602.19449},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url       = {https://arxiv.org/abs/2602.19449},
}
```

## Identifiers

- **arXiv:** [2602.19449](https://arxiv.org/abs/2602.19449)
- **PDF:** [https://arxiv.org/pdf/2602.19449](https://arxiv.org/pdf/2602.19449)
- **Project Page:** [https://ericolony.github.io/Publications/decoupling-vision-and-language-codebook-anchored-visual-adaptation/](https://ericolony.github.io/Publications/decoupling-vision-and-language-codebook-anchored-visual-adaptation/)

## Related Papers

- [salient-concept-aware-generative-data-augmentation](salient-concept-aware-generative-data-augmentation.md)
- [model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing](model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing.md)
