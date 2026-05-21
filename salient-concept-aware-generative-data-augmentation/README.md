# Salient Concept-Aware Generative Data Augmentation

**Authors:** Tianchen Zhao, Xuanbai Chen, Zhihua Li, Jun Fang, Dongsheng An, Xiang Xu, Zhuowen Tu, Yifan Xing

**Venue:** arXiv, 2025 | **Citations:** 1

**Links:** [arXiv](https://arxiv.org/abs/2510.15194) | [PDF](https://arxiv.org/pdf/2510.15194)

---

## Summary

Proposes a salient concept-aware generative augmentation framework that disentangles class-discriminative features from irrelevant context, improving fine-grained recognition under both conventional and long-tail settings.

## Abstract

Recent generative data augmentation methods conditioned on both image and text prompts struggle to balance between fidelity and diversity, as it is challenging to preserve essential image details while aligning with varied text prompts. This challenge arises because representations in the synthesis process often become entangled with non-essential input image attributes such as environmental contexts, creating conflicts with text prompts intended to modify these elements. To address this, we propose a personalized image generation framework that uses a salient concept-aware image embedding model to reduce the influence of irrelevant visual details during the synthesis process, thereby maintaining intuitive alignment between image and text inputs. By generating images that better preserve class-discriminative features with additional controlled variations, our framework effectively enhances the diversity of training datasets and thereby improves the robustness of downstream models. Our approach demonstrates superior performance across eight fine-grained vision datasets, outperforming state-of-the-art augmentation methods with averaged classification accuracy improvements by 0.73% and 6.5% under conventional and long-tail settings, respectively.

## Key Contributions

- Salient concept-aware image embedding that reduces irrelevant visual detail influence
- Personalized generation preserving class-discriminative features with controlled variation
- Superior performance on 8 fine-grained datasets, especially under long-tail settings (+6.5%)

## Cite This Paper If

Your work involves generative data augmentation, concept-aware augmentation, salient concept modeling, or synthetic data generation for visual recognition.

## BibTeX

```bibtex
@article{zhao2025salient,
  title={Salient Concept-Aware Generative Data Augmentation},
  author={Zhao, Tianchen and Chen, Xuanbai and Li, Zhihua and Fang, Jun and An, Dongsheng and Xu, Xiang and Tu, Zhuowen and Xing, Yifan},
  journal={arXiv preprint arXiv:2510.15194},
  year={2025}
}
```

## Related Papers

- [Diversity-Sensitive Conditional Generative Adversarial Networks](../diversity-sensitive-conditional-generative-adversarial-networks/) (ICLR 2019)
- [Adversarial Defense via Learning to Generate Diverse Attacks](../adversarial-defense-via-learning-to-generate-diverse-attacks/) (ICCV 2019)
- [Model Diagnosis and Correction via Linguistic and Implicit Attribute Editing](../model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing/) (CVPR 2025)
- [Decoupling Vision and Language: Codebook Anchored Visual Adaptation](../decoupling-vision-and-language-codebook-anchored-visual-adaptation/) (arXiv 2026)
