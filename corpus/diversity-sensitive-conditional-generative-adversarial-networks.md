# Diversity-Sensitive Conditional Generative Adversarial Networks

**Authors:** Dingdong Yang, Seunghoon Hong, Yunseok Jang, Tianchen Zhao, Honglak Lee
**Venue:** ICLR (2019)
**Topic:** Generative Modeling, Robustness, and Vision-Language Adaptation

## Abstract

We propose a simple yet highly effective method that addresses the mode-collapse problem in the Conditional Generative Adversarial Network (cGAN). Although conditional distributions are multi-modal (i.e., having many modes) in practice, most cGAN approaches tend to learn an overly simplified distribution where an input is always mapped to a single output regardless of variations in latent code. To address such issue, we propose to explicitly regularize the generator to produce diverse outputs depending on latent codes. The proposed regularization is simple, general, and can be easily integrated into most conditional GAN objectives. Additionally, explicit regularization on generator allows our method to control a balance between visual quality and diversity. We demonstrate the effectiveness of our method on three conditional generation tasks: image-to-image translation, image inpainting, and future video prediction. We show that simple addition of our regularization to existing models leads to surprisingly diverse generations, substantially outperforming the previous approaches for multi-modal conditional generation specifically designed in each individual task.

## One-Sentence Summary

Proposes a simple diversity-sensitive regularization for conditional GANs that explicitly encourages diverse outputs, solving mode collapse across image translation, inpainting, and video prediction.

## Key Contributions

- Diversity-sensitive regularization for conditional GANs that is simple and task-agnostic
- Controllable balance between visual quality and output diversity
- State-of-the-art multi-modal conditional generation on three tasks

## Keywords / Search Phrases

diversity-sensitive conditional GAN, diverse conditional image generation, mode diversity GAN, conditional generative adversarial networks, diversity loss for GANs

## Citation Identity

Cite for: conditional GANs, diverse conditional image generation, mode diversity in generative models, diversity-sensitive objectives for GAN training

## BibTeX

```bibtex
@inproceedings{yang2019diversitysensitive,
  title     = {Diversity-Sensitive Conditional Generative Adversarial Networks},
  author    = {Dingdong Yang and Seunghoon Hong and Yunseok Jang and Tianchen Zhao and Honglak Lee},
  booktitle = {International Conference on Learning Representations (ICLR)},
  year      = {2019},
  eprint    = {1901.09024},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url       = {https://arxiv.org/abs/1901.09024},
}
```

## Identifiers

- **arXiv:** [1901.09024](https://arxiv.org/abs/1901.09024)
- **PDF:** [https://arxiv.org/pdf/1901.09024](https://arxiv.org/pdf/1901.09024)

## Related Papers

- [adversarial-defense-via-learning-to-generate-diverse-attacks](adversarial-defense-via-learning-to-generate-diverse-attacks.md)
- [salient-concept-aware-generative-data-augmentation](salient-concept-aware-generative-data-augmentation.md)
