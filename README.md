# An Exploratory Servey
This repository provides an overview on audio-visual deepfake generation and detection.

## Summary of Contents
---
- [Summary of Contents](#Summary-of-Contents)
- [Audio Visual Generation](#Audio-Visual-Generation)
  - [Methods](#Methods)
  - [Datasets](#Datasets)
- [Audio Visual Detection](#Audio-Visual-Detection)
  - [Modal Fusion Detectors](#Modal-Fusion-Detectors)
  - [Modal Inconsistency Detectors](#Modal-Inconsistency-Detectors)
- [Generalization Experiments](#Generalization-Experiments)

## Audio Visual Generation

### Methods

### Datasets



## Audio Visual Detection

### Modal Fusion Detectors
|Year|Source|CCF Rank|Category|Paper Title|Code|
|:-:|:-:|:-:|:-:|-|:-:|
|2024|ICASSP|CCF-B|Supervised Methods|[Cross-Modality and Within-Modality Regularization for Audio-Visual DeepFake Detection](https://arxiv.org/abs/2401.05746)|[Code](https://github.com/Vincent-ZHQ/MRDF)|
|2024|ACM MM|CCF-A|Supervised Methods|[FRADE: Forgery-aware Audio-distilled Multimodal Learning for Deepfake Detection](https://dl.acm.org/doi/10.1145/3664647.3681672)|[Code](https://github.com/niefengxxx/FRADE)|
|2024|ACM TOMM|CCF-A|Supervised Methods|[Joint Audio-Visual Attention with Contrastive Learning for More General Deepfake Detection](https://dl.acm.org/doi/10.1145/3625100)|-|
|2024|IJCV|CCF-A|Supervised Methods|[Fine-grained Multimodal DeepFake Classification via Heterogeneous Graphs](https://link.springer.com/article/10.1007/s11263-024-02128-1)|[Code](https://github.com/yinql1995/Fine-grained-Multimodal-DeepFake-Classification/)
|2023|IEEE TIFS|CCF-A|Supervised Methods|[AVoiD-DF: Audio-Visual Joint Learning for Detecting Deepfake](https://ieeexplore.ieee.org/document/10081373)|[Code](https://github.com/SYSU-DISG/AVoiD-DF)|
|2024|ICME|CCF-B|Supervised Methods|[Explicit Correlation Learning for Generalizable Cross-Modal Deepfake Detection](https://ieeexplore.ieee.org/document/10687814)|[Code](https://github.com/ljj898/CMDFD-Dataset-and-Deepfake-Detection)|
|2025|AAAI|CCF-A|Supervised Methods|[Multi-modal Deepfake Detection via Multi-task Audio-Visual Prompt Learning](https://ojs.aaai.org/index.php/AAAI/article/view/32042)|-|
|2023|IEEE TCSVT|CCF-A|Supervised Methods|[MCL: Multimodal Contrastive Learning for Deepfake Detection](https://ieeexplore.ieee.org/document/10243082)|-|   
|2025|AAAI|CCF-A|Supervised Methods|[GLCF: A Global-Local Multimodal Coherence Analysis Framework for Talking Face Generation Detection](https://arxiv.org/abs/2412.13656)|-|

|Year|Source|CCF Rank|Category|Paper Title|Code|
|:-:|:-:|:-:|:-:|-|:-:|
|2024|CVPR|CCF-A|Hybrid Self-Supervised and Supervised Methods|[Avff: Audio-visual feature fusion for video deepfake detection](https://openaccess.thecvf.com/content/CVPR2024W/WIFS/html/Oorloff_AVFF_Audio-Visual_Feature_Fusion_for_Video_Deepfake_Detection_CVPRW_2024_paper.html)|-|
|2024|CVIU|CCF-B|Hybrid Self-Supervised and Supervised Methods|[Audio–visual deepfake detection using articulatory representation learning](https://www.sciencedirect.com/science/article/abs/pii/S107731422400115X)|-|
|2024|ACM MM|CCF-A|Hybrid Self-Supervised and Supervised Methods|[Mfms: Learning modality-fused and modality-specific features for deepfake detection and localization tasks](https://dl.acm.org/doi/abs/10.1145/3652876.3681678)|-|

### Modal Inconsistency Detectors


## Generalization Experiments

### Benchmark Results

|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Detector&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Testing Set&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AUC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ACC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Precision&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recall&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|:-:|:-:|:-:|:-:|:-:|:-:|
|                     | FakeAVCeleb | 0.9912 | 0.939 | 0.8998 | 0.988 |
|                     | LAV-DF      | 0.6513 | 0.561 | 0.5340 | 0.958 |
| **Yu et al.**       | IDForge     | 0.8346 | 0.617 | 0.5711 | 0.940 |
|                     | AVLips      | 0.8807 | 0.746 | 0.6864 | 0.906 |
|                     | CMDFD       | 0.7955 | 0.711 | 0.6924 | 0.757 |
|                     | FakeAVCeleb | 0.7127 | 0.625 | 0.6371 | 0.492 |
|                     | LAV-DF      | 0.5055 | 0.548 | 0.4494 | 0.211 |
| **LIPINC**          | IDForge     | 0.7882 | 0.654 | 0.8791 | 0.216 |
|                     | AVLips      | 0.7054 | 0.669 | 0.6045 | 0.353 |
|                     | CMDFD       | 0.6677 | 0.619 | 0.6503 | 0.416 |
|                     | FakeAVCeleb | 0.7242 | 0.675 | 0.8159 | 0.415 |
|                     | LAV-DF      | 0.4195 | 0.450 | 0.5112 | 0.500 |
| **LipFD**           | IDForge     | 0.6997 | 0.706 | 0.6129 | 0.055 |
|                     | AVLips      | 0.8498 | 0.802 | 0.9620 | 0.631 |
|                     | CMDFD       | 0.7472 | 0.626 | 0.6949 | 0.323 |
|                     | FakeAVCeleb | 0.7643 | 0.649 | 0.8266 | 0.454 |
|                     | LAV-DF      | 0.5594 | 0.565 | 0.5144 | 0.135 |
| **VFD**             | IDForge     | 0.4334 | 0.480 | 0.6895 | 0.504 |
|                     | AVLips      | 0.6510 | 0.567 | 0.6433 | 0.287 |
|                     | CMDFD       | 0.6892 | 0.606 | 0.7947 | 0.370 |
|                     | FakeAVCeleb | 0.9929 | 0.962 | 0.9408 | 0.986 |
|                     | LAV-DF      | 0.8537 | 0.780 | 0.7778 | 0.784 |
| **SpeechForensics** | IDForge     | 0.9567 | 0.927 | 0.9514 | 0.900 |
|                     | AVLips      | 0.9946 | 0.984 | 0.9899 | 0.978 |
|                     | CMDFD       | 0.9958 | 0.979 | 0.9878 | 0.970 |
|                     | FakeAVCeleb | 0.8086 | 0.729 | 0.6803 | 0.864 |
|                     | LAV-DF      | 0.5753 | 0.575 | 0.5632 | 0.668 |
| **Feng et al.**     | IDForge     | 0.7549 | 0.708 | 0.7023 | 0.722 |
|                     | AVLips      | 0.7439 | 0.713 | 0.7530 | 0.634 |
|                     | CMDFD       | 0.4627 | 0.500 | 0.5000 | 1.000 |
|                     | FakeAVCeleb | 0.9529 | 0.900 | 0.8556 | 0.962 |
|                     | LAV-DF      | 0.8870 | 0.814 | 0.7549 | 0.930 |
| **AVH-Align**       | IDForge     | 0.1472 | 0.501 | 0.5005 | 1.000 |
|                     | AVLips      | 0.8661 | 0.864 | 0.8085 | 0.954 |
|                     | CMDFD       | 0.8286 | 0.758 | 0.7287 | 0.822 |
