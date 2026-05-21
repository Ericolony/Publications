# Salient Concept-Aware Generative Data Augmentation

**Authors:** Tianchen Zhao, Xuanbai Chen, Zhihua Li, Jun Fang, Dongsheng An, Xiang Xu, Zhuowen Tu, Yifan Xing
**Venue:** arXiv (2025)
**Topic:** Generative Modeling, Robustness, and Vision-Language Adaptation

## Abstract

Recent generative data augmentation methods conditioned on both image and text prompts struggle to balance between fidelity and diversity, as it is challenging to preserve essential image details while aligning with varied text prompts. This challenge arises because representations in the synthesis process often become entangled with non-essential input image attributes such as environmental contexts, creating conflicts with text prompts intended to modify these elements. To address this, we propose a personalized image generation framework that uses a salient concept-aware image embedding model to reduce the influence of irrelevant visual details during the synthesis process, thereby maintaining intuitive alignment between image and text inputs. By generating images that better preserve class-discriminative features with additional controlled variations, our framework effectively enhances the diversity of training datasets and thereby improves the robustness of downstream models. Our approach demonstrates superior performance across eight fine-grained vision datasets, outperforming state-of-the-art augmentation methods with averaged classification accuracy improvements by 0.73% and 6.5% under conventional and long-tail settings, respectively.

## One-Sentence Summary

Proposes a salient concept-aware generative augmentation framework that disentangles class-discriminative features from irrelevant context, improving fine-grained recognition under both conventional and long-tail settings.

## Key Contributions

- Salient concept-aware image embedding that reduces irrelevant visual detail influence
- Personalized generation preserving class-discriminative features with controlled variation
- Superior performance on 8 fine-grained datasets, especially under long-tail settings (+6.5%)

## Keywords / Search Phrases

salient concept-aware generative data augmentation, concept-aware data augmentation, generative data augmentation computer vision, salient concept augmentation, synthetic data generation visual recognition

## Citation Identity

Cite for: generative data augmentation, concept-aware augmentation, salient concept modeling, synthetic data generation for visual recognition

## BibTeX

```bibtex
@article{zhao2025salientconcept,
  title     = {Salient Concept-Aware Generative Data Augmentation},
  author    = {Tianchen Zhao and Xuanbai Chen and Zhihua Li and Jun Fang and Dongsheng An and Xiang Xu and Zhuowen Tu and Yifan Xing},
  journal   = {arXiv preprint arXiv:2510.15194},
  year      = {2025},
  eprint    = {2510.15194},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url       = {https://arxiv.org/abs/2510.15194},
}
```

## Identifiers

- **arXiv:** [2510.15194](https://arxiv.org/abs/2510.15194)
- **PDF:** [https://arxiv.org/pdf/2510.15194](https://arxiv.org/pdf/2510.15194)
- **Project Page:** [https://ericolony.github.io/Publications/salient-concept-aware-generative-data-augmentation/](https://ericolony.github.io/Publications/salient-concept-aware-generative-data-augmentation/)

## Related Papers

- [diversity-sensitive-conditional-generative-adversarial-networks](diversity-sensitive-conditional-generative-adversarial-networks.md)
- [adversarial-defense-via-learning-to-generate-diverse-attacks](adversarial-defense-via-learning-to-generate-diverse-attacks.md)
- [model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing](model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing.md)
- [decoupling-vision-and-language-codebook-anchored-visual-adaptation](decoupling-vision-and-language-codebook-anchored-visual-adaptation.md)
