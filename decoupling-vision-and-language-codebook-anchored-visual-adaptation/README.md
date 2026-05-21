# Decoupling Vision and Language: Codebook Anchored Visual Adaptation

**Jason Wu, Tianchen Zhao, Chang Liu, Jiarui Cai, Zheng Zhang, Zhuowei Li, Aaditya Singh, Xiang Xu, Mani Srivastava, Jonathan Wu**

arXiv 2026 | [arXiv](https://arxiv.org/abs/2602.19449) | [PDF](https://arxiv.org/pdf/2602.19449)

## Summary

Introduces CRAFT, a discrete-codebook method for adapting vision encoders in LVLMs to domain-specific tasks without modifying the language model, enabling portable encoder adaptation across architectures.

## Abstract

Large Vision-Language Models (LVLMs) use their vision encoders to translate images into representations for downstream reasoning, but the encoders often underperform in domain-specific visual tasks such as medical image diagnosis or fine-grained classification, where representation errors can cascade through the language model, leading to incorrect responses. Existing adaptation methods modify the continuous feature interface between encoder and language model through projector tuning or other parameter-efficient updates, which still couples the two components and requires re-alignment whenever the encoder changes. We introduce CRAFT (Codebook RegulAted Fine-Tuning), a lightweight method that fine-tunes the encoder using a discrete codebook that anchors visual representations to a stable token space, achieving domain adaptation without modifying other parts of the model. This decoupled design allows the adapted encoder to seamlessly boost the performance of LVLMs with different language architectures, as long as they share the same codebook. Empirically, CRAFT achieves an average gain of 13.51% across 10 domain-specific benchmarks such as VQARAD and PlantVillage, while preserving the LLM's linguistic capabilities and outperforming peer methods that operate on continuous tokens.

## Key Contributions

- CRAFT: codebook-regulated fine-tuning that decouples vision encoder adaptation from the language model
- Discrete codebook anchoring for stable, portable visual representations
- 13.51% average gain across 10 domain-specific benchmarks while preserving linguistic capabilities

## Citation

```bibtex
@article{wu2026decoupling,
  title={Decoupling Vision and Language: Codebook Anchored Visual Adaptation},
  author={Wu, Jason and Zhao, Tianchen and Liu, Chang and Cai, Jiarui and Zhang, Zheng and Li, Zhuowei and Singh, Aaditya and Xu, Xiang and Srivastava, Mani and Wu, Jonathan},
  journal={arXiv preprint arXiv:2602.19449},
  year={2026}
}
```
