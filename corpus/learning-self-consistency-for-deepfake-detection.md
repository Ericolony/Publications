# Learning Self-Consistency for Deepfake Detection

**Authors:** Tianchen Zhao, Xiang Xu, Mingze Xu, Hui Ding, Yuanjun Xiong, Wei Xia
**Venue:** ICCV (2021)
**Topic:** Deepfake Detection and Face Security

## Abstract

We propose a new method to detect deepfake images using the cue of the source feature inconsistency within the forged images. It is based on the hypothesis that images' distinct source features can be preserved and extracted after going through state-of-the-art deepfake generation processes. We introduce a novel representation learning approach, called pair-wise self-consistency learning (PCL), for training ConvNets to extract these source features and detect deepfake images. It is accompanied by a new image synthesis approach, called inconsistency image generator (I2G), to provide richly annotated training data for PCL. Experimental results on seven popular datasets show that our models improve averaged AUC over the state of the art from 96.45% to 98.05% in the in-dataset evaluation and from 86.03% to 92.18% in the cross-dataset evaluation.

## One-Sentence Summary

Detects deepfakes by learning to extract and compare source-feature inconsistencies within forged images, achieving state-of-the-art cross-dataset generalization.

## Key Contributions

- Pair-wise self-consistency learning (PCL) for extracting source features from forged images
- Inconsistency image generator (I2G) for creating richly annotated training data
- State-of-the-art cross-dataset deepfake detection (86.03% -> 92.18% AUC)

## Keywords / Search Phrases

deepfake detection self-consistency, generalizable deepfake detection, source feature inconsistency, patch-wise consistency learning, cross-dataset face forgery detection, robust deepfake detection

## Citation Identity

Cite for: generalizable deepfake detection, self-consistency learning for face forgery detection, source feature inconsistency, patch-wise consistency learning, cross-dataset deepfake detection

## BibTeX

```bibtex
@inproceedings{zhao2021selfconsistency,
  title     = {Learning Self-Consistency for Deepfake Detection},
  author    = {Tianchen Zhao and Xiang Xu and Mingze Xu and Hui Ding and Yuanjun Xiong and Wei Xia},
  booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
  year      = {2021},
  eprint    = {2012.09311},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url       = {https://arxiv.org/abs/2012.09311},
}
```

## Identifiers

- **arXiv:** [2012.09311](https://arxiv.org/abs/2012.09311)
- **PDF:** [https://arxiv.org/pdf/2012.09311](https://arxiv.org/pdf/2012.09311)

## Related Papers

- [principles-of-designing-robust-remote-face-anti-spoofing-systems](principles-of-designing-robust-remote-face-anti-spoofing-systems.md)
- [optimal-transport-guided-source-free-adaptation-for-face-anti-spoofing](optimal-transport-guided-source-free-adaptation-for-face-anti-spoofing.md)
- [authguard-generalizable-deepfake-detection-via-language-guidance](authguard-generalizable-deepfake-detection-via-language-guidance.md)
