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

## Benchmark Results

|Detector|Testing Set|AUC|ACC|Precision|Recall|
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
<table style="width:100%; table-layout:fixed; text-align:center; border-collapse:collapse;" border="1">
  <thead>
    <tr>
      <th style="width:15%;">Detector</th>
      <th style="width:15%;">Testing Set</th>
      <th style="width:14%;">AUC</th>
      <th style="width:14%;">ACC</th>
      <th style="width:14%;">Precision</th>
      <th style="width:14%;">Recall</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color:#f9f9f9;">
      <td rowspan="2"></td>
      <td>FakeAVCeleb</td><td>0.9912</td><td>0.939</td><td>0.8998</td><td>0.988</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>LAV-DF</td><td>0.6513</td><td>0.561</td><td>0.5340</td><td>0.958</td>
    </tr>

    <tr style="background-color:#f2f2f2;">
      <td rowspan="5"><b>Yu et al.</b></td>
      <td>IDForge</td><td>0.8346</td><td>0.617</td><td>0.5711</td><td>0.940</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>AVLips</td><td>0.8807</td><td>0.746</td><td>0.6864</td><td>0.906</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>CMDFD</td><td>0.7955</td><td>0.711</td><td>0.6924</td><td>0.757</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>FakeAVCeleb</td><td>0.7127</td><td>0.625</td><td>0.6371</td><td>0.492</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>LAV-DF</td><td>0.5055</td><td>0.548</td><td>0.4494</td><td>0.211</td>
    </tr>

    <tr style="background-color:#f9f9f9;">
      <td rowspan="5"><b>LIPINC</b></td>
      <td>IDForge</td><td>0.7882</td><td>0.654</td><td>0.8791</td><td>0.216</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>AVLips</td><td>0.7054</td><td>0.669</td><td>0.6045</td><td>0.353</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>CMDFD</td><td>0.6677</td><td>0.619</td><td>0.6503</td><td>0.416</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>FakeAVCeleb</td><td>0.7242</td><td>0.675</td><td>0.8159</td><td>0.415</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>LAV-DF</td><td>0.4195</td><td>0.450</td><td>0.5112</td><td>0.500</td>
    </tr>

    <tr style="background-color:#f2f2f2;">
      <td rowspan="5"><b>LipFD</b></td>
      <td>IDForge</td><td>0.6997</td><td>0.706</td><td>0.6129</td><td style="color:red;"><b>0.055</b></td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>AVLips</td><td>0.8498</td><td>0.802</td><td>0.9620</td><td>0.631</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>CMDFD</td><td>0.7472</td><td>0.626</td><td>0.6949</td><td>0.323</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>FakeAVCeleb</td><td>0.7643</td><td>0.649</td><td>0.8266</td><td>0.454</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>LAV-DF</td><td>0.5594</td><td>0.565</td><td>0.5144</td><td>0.135</td>
    </tr>

    <tr style="background-color:#f9f9f9;">
      <td rowspan="5"><b>VFD</b></td>
      <td>IDForge</td><td>0.4334</td><td>0.480</td><td>0.6895</td><td>0.504</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>AVLips</td><td>0.6510</td><td>0.567</td><td>0.6433</td><td>0.287</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>CMDFD</td><td>0.6892</td><td>0.606</td><td>0.7947</td><td>0.370</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>FakeAVCeleb</td><td style="color:green;"><b>0.9929</b></td><td style="color:green;"><b>0.962</b></td><td>0.9408</td><td style="color:green;"><b>0.986</b></td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>LAV-DF</td><td>0.8537</td><td>0.780</td><td>0.7778</td><td>0.784</td>
    </tr>

    <tr style="background-color:#f2f2f2;">
      <td rowspan="5"><b>SpeechForensics</b></td>
      <td>IDForge</td><td>0.9567</td><td>0.927</td><td>0.9514</td><td>0.900</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>AVLips</td><td style="color:green;"><b>0.9946</b></td><td style="color:green;"><b>0.984</b></td><td style="color:green;"><b>0.9899</b></td><td style="color:green;"><b>0.978</b></td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>CMDFD</td><td style="color:green;"><b>0.9958</b></td><td style="color:green;"><b>0.979</b></td><td style="color:green;"><b>0.9878</b></td><td style="color:green;"><b>0.970</b></td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>FakeAVCeleb</td><td>0.8086</td><td>0.729</td><td>0.6803</td><td>0.864</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>LAV-DF</td><td>0.5753</td><td>0.575</td><td>0.5632</td><td>0.668</td>
    </tr>

    <tr style="background-color:#f9f9f9;">
      <td rowspan="5"><b>Feng et al.</b></td>
      <td>IDForge</td><td>0.7549</td><td>0.708</td><td>0.7023</td><td>0.722</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>AVLips</td><td>0.7439</td><td>0.713</td><td>0.7530</td><td>0.634</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>CMDFD</td><td>0.4627</td><td>0.500</td><td>0.5000</td><td>1.000</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>FakeAVCeleb</td><td>0.9529</td><td>0.900</td><td>0.8556</td><td>0.962</td>
    </tr>
    <tr style="background-color:#f9f9f9;">
      <td>LAV-DF</td><td>0.8870</td><td>0.814</td><td>0.7549</td><td>0.930</td>
    </tr>

    <tr style="background-color:#f2f2f2;">
      <td rowspan="3"><b>AVH-Align</b></td>
      <td>IDForge</td><td style="color:red;"><b>0.1472</b></td><td>0.501</td><td>0.5005</td><td>1.000</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>AVLips</td><td>0.8661</td><td>0.864</td><td>0.8085</td><td>0.954</td>
    </tr>
    <tr style="background-color:#f2f2f2;">
      <td>CMDFD</td><td>0.8286</td><td>0.758</td><td>0.7287</td><td>0.822</td>
    </tr>
  </tbody>
</table>

