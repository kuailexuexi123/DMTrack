<div align="center">
<h1>
  <!--   <img src="images/logo.png" alt="Logo" width="47" height="30" style="margin-right: 10px;"> -->
    <a href="https://arxiv.org/abs/2510.17860">DMTrack: Deformable State-Space Modeling for UAV Multi-Object Tracking with Kalman Fusion and Uncertainty-Aware Association</a>
</h1>

<!-- Authors -->
Zenghuang Fu · Xiaofeng Han · Mingda Jia · Qi Zeng · Muyanng Zhang · Changwei Wang ·
Weiliang Meng · Xiaopeng Zhang 

<!-- Badges -->
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![](https://img.shields.io/badge/PRs-Welcome-%23FF4500)](https://github.com/kuailexuexi123/DMTrack)
![](https://img.shields.io/github/stars/kuailexuexi123/DMTrack?color=yellow)


</div>
<!-- # MF-RV
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/kuailexuexi123/DMTrack?color=green) 
[![](https://img.shields.io/badge/PRs-Welcome-%23FF4500)](https://github.com/kuailexuexi123/DMTrack)
![](https://img.shields.io/github/stars/kuailexuexi123/DMTrack?color=yellow)
![](https://img.shields.io/github/forks/kuailexuexi123/DMTrack?color=lightblue)  -->

### 1. Abstract
 Multi-object tracking (MOT) from unmanned aerial vehicles
 (UAVs) presents unique challenges due to unpredictable ob
ject motion, frequent occlusions, and limited appearance cues
 inherent to aerial viewpoints. These issues are further exacer
bated by abrupt UAVmovements,leadingtounreliable trajec
tory estimation and identity switches. Conventional motion
 models, such as Kalman filters or static sequence encoders,
 often fall short in capturing both linear and non-linear dy
namics under such conditions. To tackle these limitations, we
 propose DMTrack, a deformable motion tracking framework
 tailored for UAV-based MOT. Our DMTrack introduces three
 key components: DeformMamba, a deformable state-space
 predictor that dynamically aggregates historical motion states
 for adaptive trajectory modeling; MotionGate, a lightweight
 gating module that fuses Kalman and Mamba predictions
 based on motion context and uncertainty; and an uncertainty
aware association strategy that enhances identity preservation
 by aligning motion trends with prediction confidence. Exten
sive experiments on the VisDrone-MOT and UAVDT bench
marks demonstrate that our DMTrack achieves state-of-the
art performance in identity consistency and tracking accuracy,
 particularly under high-speed and non-linear motion. Impor
tantly, our method operates without appearance models and
 maintains competitive efficiency, highlighting its practicality
 for robust UAV-based tracking.

### 2. Overview
<p align="center">
   <img width="1587" height="627" alt="image" src="123.png" />

 <br />
</p>

### :star: Share us a :star:
Share us a :star: if you're interested in this repo. We will continue to track relevant progress and update this repository.


## 📖 Citation

If you find our survey and repository useful for your research, please consider citing our paper:

```bibtex
@article{fu2025dmtrack,
  title={DMTrack: Deformable State-Space Modeling for UAV Multi-Object Tracking with Kalman Fusion and Uncertainty-Aware Association},
  author={Fu, Zenghuang and Han, Xiaofeng and Jia, Mingda and Zeng, Qi and Zahng, Muyang and Wang, Changwei and Meng, Weiliang and Zhang, Xiaopeng and others},
  journal={arXiv preprint arXiv:2510.17860},
  year={2025}
}
