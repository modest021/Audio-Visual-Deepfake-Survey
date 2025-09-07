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

### Modal Inconsistency Detectors


## Generalization Experiments

| **Detector**       | **Testing Set** | **AUC** | **ACC** | **Precision** | **Recall** |
|--------------------|-----------------|---------|---------|---------------|------------|
| **SpeechForensics** | FakeAVCeleb | 0.9929 | 0.962 | 0.9408 | 0.986 |
|                    | LAV-DF      | 0.8537 | 0.780 | 0.7778 | 0.784 |
|                    | IDForge     | 0.9567 | 0.927 | 0.9514 | 0.900 |
|                    | AVLips      | 0.9946 | 0.984 | 0.9899 | 0.978 |
|                    | CMDFD       | 0.9958 | 0.979 | 0.9878 | 0.970 |
| **Feng et al.**    | FakeAVCeleb | 0.8086 | 0.729 | 0.6803 | 0.864 |
|                    | LAV-DF      | 0.5753 | 0.575 | 0.5632 | 0.668 |
|                    | IDForge     | 0.7549 | 0.708 | 0.7023 | 0.722 |
|                    | AVLips      | 0.7439 | 0.713 | 0.7530 | 0.634 |
|                    | CMDFD       | 0.4627 | 0.500 | 0.5000 | 1.000 |
| **LipFD**          | FakeAVCeleb | 0.7242 | 0.675 | 0.8159 | 0.415 |
|                    | LAV-DF      | 0.4195 | 0.450 | 0.5112 | 0.500 |
|                    | IDForge     | 0.6997 | 0.706 | 0.6129 | 0.055 |
|                    | AVLips      | 0.8498 | 0.802 | 0.9620 | 0.631 |
|                    | CMDFD       | 0.7472 | 0.626 | 0.6949 | 0.323 |
| **VFD**            | FakeAVCeleb | 0.7643 | 0.649 | 0.8266 | 0.454 |
|                    | LAV-DF      | 0.5594 | 0.565 | 0.5144 | 0.135 |
|                    | IDForge     | 0.4334 | 0.480 | 0.6895 | 0.504 |
|                    | AVLips      | 0.6510 | 0.567 | 0.6433 | 0.287 |
|                    | CMDFD       | 0.6892 | 0.606 | 0.7947 | 0.370 |
| **LIPINC**         | FakeAVCeleb | 0.7127 | 0.625 | 0.6371 | 0.492 |
|                    | LAV-DF      | 0.5055 | 0.548 | 0.4494 | 0.211 |
|                    | IDForge     | 0.7882 | 0.654 | 0.8791 | 0.216 |
|                    | AVLips      | 0.7054 | 0.669 | 0.6045 | 0.353 |
|                    | CMDFD       | 0.6677 | 0.619 | 0.6503 | 0.416 |
| **Yu et al.**      | FakeAVCeleb | 0.9912 | 0.939 | 0.8998 | 0.988 |
|                    | LAV-DF      | 0.6513 | 0.561 | 0.5340 | 0.958 |
|                    | IDForge     | 0.8346 | 0.617 | 0.5711 | 0.940 |
|                    | AVLips      | 0.8807 | 0.746 | 0.6864 | 0.906 |
|                    | CMDFD       | 0.7955 | 0.711 | 0.6924 | 0.757 |
| **AVH-Align**      | FakeAVCeleb | 0.9529 | 0.900 | 0.8556 | 0.962 |
|                    | LAV-DF      | 0.8870 | 0.814 | 0.7549 | 0.930 |
|                    | IDForge     | 0.1472 | 0.501 | 0.5005 | 1.000 |
|                    | AVLips      | 0.8661 | 0.864 | 0.8085 | 0.954 |
|                    | CMDFD       | 0.8286 | 0.758 | 0.7287 | 0.822 |



