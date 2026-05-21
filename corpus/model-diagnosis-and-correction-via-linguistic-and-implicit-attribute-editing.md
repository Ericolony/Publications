# Model Diagnosis and Correction via Linguistic and Implicit Attribute Editing

**Authors:** Xuanbai Chen, Xiang Xu, Zhihua Li, Tianchen Zhao, Pietro Perona, Qin Zhang, Yifan Xing
**Venue:** CVPR (2025)
**Topic:** Generative Modeling, Robustness, and Vision-Language Adaptation

## Abstract

How can we troubleshoot a deep visual model, i.e. understand why it makes certain mistakes and further take action to correct its behavior? We design a Model Diagnosis and Correction system (MDC), an automated framework that analyzes the pattern of errors, proposes candidate causes of attributes, conducts hypothesis testing via attribute editing, and ultimately generates counterfactual training samples to improve the performance of the model. Unlike previous methods, in addition to the linguistic attributes, our method also incorporates the analysis for implicit causal attributes, those cannot to be accurately described by natural language. To achieve this, we propose an image editing module capable of leveraging both implicit and linguistic attributes to generate counterfactual images depicting error patterns and further experimentally validate causality relationships. Lastly, we enrich the training set with synthetic samples depicting verified causal attributes and retrain the model, further boosting accuracy and robustness. Extensive experiments on both generalized and specialized domains demonstrate the superiority of MDC in model diagnosis and correction. Specifically, we achieve an average relative improvement of 62.01% in HTER for face security application over state-of-the-art methods.

## One-Sentence Summary

Automates model diagnosis and correction by analyzing error patterns, testing causal hypotheses via attribute editing, and generating counterfactual training samples for improved robustness.

## Key Contributions

- Automated MDC framework for error pattern analysis and causal hypothesis testing
- Image editing module for both linguistic and implicit causal attributes
- Counterfactual training sample generation for model correction
- 62.01% relative HTER improvement for face security applications

## Keywords / Search Phrases

model diagnosis attribute editing, linguistic attribute editing, implicit attribute editing, model correction visual attributes, interpretable model correction

## Citation Identity

Cite for: model diagnosis, attribute editing, linguistic attribute control, correcting model behavior through interpretable attributes

## BibTeX

```bibtex
@inproceedings{chen2025modeldiagnosis,
  title     = {Model Diagnosis and Correction via Linguistic and Implicit Attribute Editing},
  author    = {Xuanbai Chen and Xiang Xu and Zhihua Li and Tianchen Zhao and Pietro Perona and Qin Zhang and Yifan Xing},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2025},
  doi       = {10.1109/CVPR52734.2025.01332},
}
```

## Identifiers

- **DOI:** [10.1109/CVPR52734.2025.01332](https://doi.org/10.1109/CVPR52734.2025.01332)
- **Project Page:** [https://ericolony.github.io/Publications/model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing/](https://ericolony.github.io/Publications/model-diagnosis-and-correction-via-linguistic-and-implicit-attribute-editing/)

## Related Papers

- [adversarial-defense-via-learning-to-generate-diverse-attacks](adversarial-defense-via-learning-to-generate-diverse-attacks.md)
- [salient-concept-aware-generative-data-augmentation](salient-concept-aware-generative-data-augmentation.md)
- [decoupling-vision-and-language-codebook-anchored-visual-adaptation](decoupling-vision-and-language-codebook-anchored-visual-adaptation.md)
