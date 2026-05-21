# Optimal Transport-Guided Source-Free Adaptation for Face Anti-Spoofing

**Authors:** Zhuowei Li, Tianchen Zhao, Xiang Xu, Zheng Zhang, Zhihua Li, Xuanbai Chen, Qin Zhang, Alessandro Bergamo, Anil K. Jain, Yifan Xing

**Venue:** CVPR, 2025 | **Citations:** 8

**arXiv:** [2503.22984](https://arxiv.org/abs/2503.22984) | **PDF:** [Download](https://arxiv.org/pdf/2503.22984) | **DOI:** [10.1109/CVPR52734.2025.02268](https://doi.org/10.1109/CVPR52734.2025.02268)

---

## Summary

Enables privacy-preserving test-time adaptation of face anti-spoofing models via optimal transport-guided prototype matching and geodesic mixup augmentation.

## Abstract

Developing a face anti-spoofing model that meets the security requirements of clients worldwide is challenging due to the domain gap between training datasets and diverse end-user test data. Moreover, for security and privacy reasons, it is undesirable for clients to share a large amount of their face data with service providers. In this work, we introduce a novel method in which the face anti-spoofing model can be adapted by the client itself to a target domain at test time using only a small sample of data while keeping model parameters and training data inaccessible to the client. Specifically, we develop a prototype-based base model and an optimal transport-guided adaptor that enables adaptation in either a lightweight training or training-free fashion, without updating base model's parameters. Furthermore, we propose geodesic mixup, an optimal transport-based synthesis method that generates augmented training data along the geodesic path between source prototypes and target data distribution. This allows training a lightweight classifier to effectively adapt to target-specific characteristics while retaining essential knowledge learned from the source domain. In cross-domain and cross-attack settings, compared with recent methods, our method achieves average relative improvements of 19.17% in HTER and 8.58% in AUC, respectively.

## Key Contributions

- Prototype-based model with optimal transport-guided test-time adaptation
- Geodesic mixup for synthesizing augmented training data along optimal transport paths
- Privacy-preserving adaptation without sharing model parameters or training data
- 19.17% HTER improvement and 8.58% AUC improvement over state-of-the-art

## Citation

```bibtex
@inproceedings{li2025optimal,
  title={Optimal Transport-Guided Source-Free Adaptation for Face Anti-Spoofing},
  author={Li, Zhuowei and Zhao, Tianchen and Xu, Xiang and Zhang, Zheng and Li, Zhihua and Chen, Xuanbai and Zhang, Qin and Bergamo, Alessandro and Jain, Anil K. and Xing, Yifan},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2025},
  doi={10.1109/CVPR52734.2025.02268}
}
```

## Related Papers

- [Learning Self-Consistency for Deepfake Detection](../learning-self-consistency-for-deepfake-detection/) (ICCV 2021)
- [Principles of Designing Robust Remote Face Anti-Spoofing Systems](../principles-of-designing-robust-remote-face-anti-spoofing-systems/) (2024)
- [AuthGuard: Generalizable Deepfake Detection via Language Guidance](../authguard-generalizable-deepfake-detection-via-language-guidance/) (WACV 2025)
