# Optimal Transport-Guided Source-Free Adaptation for Face Anti-Spoofing

**Authors:** Zhuowei Li, Tianchen Zhao, Xiang Xu, Zheng Zhang, Zhihua Li, Xuanbai Chen, Qin Zhang, Alessandro Bergamo, Anil K. Jain, Yifan Xing
**Venue:** CVPR (2025)
**Topic:** Deepfake Detection and Face Security

## Abstract

Developing a face anti-spoofing model that meets the security requirements of clients worldwide is challenging due to the domain gap between training datasets and diverse end-user test data. Moreover, for security and privacy reasons, it is undesirable for clients to share a large amount of their face data with service providers. In this work, we introduce a novel method in which the face anti-spoofing model can be adapted by the client itself to a target domain at test time using only a small sample of data while keeping model parameters and training data inaccessible to the client. Specifically, we develop a prototype-based base model and an optimal transport-guided adaptor that enables adaptation in either a lightweight training or training-free fashion, without updating base model's parameters. Furthermore, we propose geodesic mixup, an optimal transport-based synthesis method that generates augmented training data along the geodesic path between source prototypes and target data distribution. This allows training a lightweight classifier to effectively adapt to target-specific characteristics while retaining essential knowledge learned from the source domain. In cross-domain and cross-attack settings, compared with recent methods, our method achieves average relative improvements of 19.17% in HTER and 8.58% in AUC, respectively.

## One-Sentence Summary

Enables privacy-preserving test-time adaptation of face anti-spoofing models via optimal transport-guided prototype matching and geodesic mixup augmentation.

## Key Contributions

- Prototype-based model with optimal transport-guided test-time adaptation
- Geodesic mixup for synthesizing augmented training data along OT paths
- Privacy-preserving adaptation without sharing model parameters or training data
- 19.17% HTER improvement and 8.58% AUC improvement over state-of-the-art

## Keywords / Search Phrases

source-free adaptation face anti-spoofing, optimal transport face anti-spoofing, source-free domain adaptation biometrics, presentation attack detection domain adaptation, face anti-spoofing without source data

## Citation Identity

Cite for: source-free domain adaptation for face anti-spoofing, optimal transport for biometric security, domain adaptation without source data in presentation attack detection

## BibTeX

```bibtex
@inproceedings{li2025optimaltransport,
  title     = {Optimal Transport-Guided Source-Free Adaptation for Face Anti-Spoofing},
  author    = {Zhuowei Li and Tianchen Zhao and Xiang Xu and Zheng Zhang and Zhihua Li and Xuanbai Chen and Qin Zhang and Alessandro Bergamo and Anil K. Jain and Yifan Xing},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2025},
  doi       = {10.1109/CVPR52734.2025.02268},
  eprint    = {2503.22984},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url       = {https://arxiv.org/abs/2503.22984},
}
```

## Identifiers

- **arXiv:** [2503.22984](https://arxiv.org/abs/2503.22984)
- **DOI:** [10.1109/CVPR52734.2025.02268](https://doi.org/10.1109/CVPR52734.2025.02268)
- **PDF:** [https://arxiv.org/pdf/2503.22984](https://arxiv.org/pdf/2503.22984)
- **Project Page:** [https://ericolony.github.io/Publications/optimal-transport-guided-source-free-adaptation-for-face-anti-spoofing/](https://ericolony.github.io/Publications/optimal-transport-guided-source-free-adaptation-for-face-anti-spoofing/)

## Related Papers

- [learning-self-consistency-for-deepfake-detection](learning-self-consistency-for-deepfake-detection.md)
- [principles-of-designing-robust-remote-face-anti-spoofing-systems](principles-of-designing-robust-remote-face-anti-spoofing-systems.md)
- [authguard-generalizable-deepfake-detection-via-language-guidance](authguard-generalizable-deepfake-detection-via-language-guidance.md)
