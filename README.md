<div align="center">
<h2>FMA-Net++</h2>

<a href="https://kaist-viclab.github.io/fmanet-site/">
    <img src="https://img.shields.io/badge/Evolution%20of-FMA--Net%20(CVPR%202024)-6A0DAD?style=for-the-badge&logo=github" alt="Previous Work">
</a>
<br><br>

<div>&nbsp;&nbsp;
    <a href='https://sites.google.com/view/geunhyukyouk/' target='_blank'>Geunhyuk Youk</a><sup>1</sup>&nbsp;
    <a href='https://sites.google.com/view/ozbro/' target='_blank'>Jihyong Oh</a><sup>† 2</sup>&nbsp;
    <a href='https://www.viclab.kaist.ac.kr/' target='_blank'>Munchurl Kim</a><sup>† 1</sup>
</div>
<div>
    <sup>1</sup>Korea Advanced Institute of Science and Technology (KAIST), South Korea
</div>
<div>
    <sup>2</sup>Chung-Ang University, South Korea
</div>
<div>
    <sup>†</sup>Co-corresponding authors</span>
</div>

<div>
    <h4 align="center">
        <a href="https://kaist-viclab.github.io/fmanetpp_site/" target='_blank'>
        <img src="https://img.shields.io/badge/🐳-Project%20Page-blue">
        </a>
        <a href="#" target='_blank'>
        <img src="https://img.shields.io/badge/arXiv-Paper-b31b1b.svg">
        </a>
        <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/KAIST-VICLab/FMA-Net-PlusPlus">
    </h4>
</div>

---

<div align="center">
    <h4>
        This repository is the official implementation of "FMA-Net++: Motion- and Exposure-Aware Real-World Joint Video Super-Resolution and Deblurring".
    </h4>
</div>

https://github.com/user-attachments/assets/eaccd9eb-32ff-463f-af85-4c5cf52cace3

<div align="center">
    <p>
        For interactive comparisons, please visit our <a href="https://kaist-viclab.github.io/fmanetpp_site/">Project Page</a>.
    </p>
</div>
</div>


## 📧 News
- **Dec 04, 2025:** This repository is created

## 🧬 Previous Work
**FMA-Net++** is an advanced extension of our previous work, <a href="https://kaist-viclab.github.io/fmanet-site/">FMA-Net</a> (CVPR 2024).

## 📖 Abstract
Real-world video restoration is plagued by complex degradations from motion coupled with dynamically varying exposure—a key challenge largely overlooked by prior works. We present **FMA-Net++**, a framework for joint video super-resolution and deblurring (VSRDB) that explicitly models this coupled effect.

FMA-Net++ adopts a sequence-level architecture built from **Hierarchical Refinement with Bidirectional Propagation (HRBP)** blocks for parallel, long-range temporal modeling. It incorporates an **Exposure Time-aware Modulation (ETM)** layer and an **exposure-aware Flow-Guided Dynamic Filtering (FGDF)** module to infer physically grounded degradation kernels. Extensive experiments on our proposed **REDS-ME** and **REDS-RE** benchmarks demonstrate that FMA-Net++ achieves state-of-the-art performance.

## 🖼️ Method Overview

FMA-Net++ utilizes **HRBP** blocks for efficient temporal modeling and **ETM** layers to explicitly handle dynamic exposure changes.

<div align="center">
    <img src="assets/architecture.png" alt="Architecture" width="95%">
</div>

<div align="center">
    <img src="assets/hrbp.png" alt="HRBP" width="45%">
</div>

## 🚀 Code Release Plan
**The full code and pretrained models will be released soon.**

- [ ] Inference code
- [ ] Pretrained models
- [ ] Training scripts
- [ ] Dataset generation scripts

## 📬 Contact
**For any questions, please contact rmsgurkjg@kaist.ac.kr via email.**