# 🧠 Multidomain Adaptive Semantic Communications (MA-DeepSC)

This repository provides the official implementation of our **IEEE JSAC 2025** paper titled:

> **"Multidomain Adaptive Semantic Communications"**  
> *IEEE Journal on Selected Areas in Communications (JSAC), Vol. 43, No. 7, pp. 2506–2517, 2025*  
> [DOI: 10.1109/JSAC.2025.3559127](https://doi.org/10.1109/JSAC.2025.3559127)

## 🔧 Overview

We propose two multidomain-adaptive modules for semantic image communication over wireless channels:

- **MASCN (Multidomain Adaptive Semantic Coding Network)**  
  A StarGAN-based end-to-end encoder-decoder architecture that inherently supports multi-domain semantic encoding and decoding, making it robust against both domain shifts and channel noise (e.g., AWGN, Fading).

- **MDAN (Multidomain Data Adaptation Network)**  
  A generalized, StarGAN-based adaptation module derived from the CycleGAN-like framework in [4], enabling multi domain data adaptation to desired target domains, prior to semantic endcoding.

Both components support **multi-domain settings in a unified and scalable manner**, and can be combined or used independently.

4-digit Datasets
https://drive.google.com/drive/folders/1joqfCtRxitmrTZao49smzVnLT_6FSNRQ?usp=sharing


---

## 📁 Reference Implementations

Our work is inspired by and partially built upon the following public repositories:

- [1] DeepJSCC-f (JSCC with feedback): DeepJSCC-f: Deep Joint Source-Channel Coding of Images with Feedback
  Kurka & Gunduz, *IEEE JSAIT 2020*  
  👉 https://github.com/kurka/deepJSCC-feedback

- [2] ADJSCC (with attention modules): Wireless Image Transmission Using Deep Source Channel Coding With Attention Modules
  Xu et al., *IEEE TCSVT 2022*  
  👉 https://github.com/alexxu1988/ADJSCC

- [3] Predictive and Adaptive Deep Coding for Wireless Image Transmission in Semantic Communication 
  Zhang et al., *IEEE TWC 2023*  
  👉 https://github.com/wyzhang-ustb/Predictive-and-Adaptive-Deep-Coding-for-Wireless-Image-Transmission-in-Semantic-Communication

- [4] Deep Learning-Enabled Semantic Communication Systems with Task-Unaware Transmitter and Dynamic Data 
  Zhang et al., *IEEE JSAC 2022*  
  👉 https://github.com/SJTU-mxtao/Semantic-Communication-Systems

---

## 📝 Citation

If you use this code or find the project helpful, please cite:

```bibtex
@ARTICLE{10960416,
  author={Won, Dongwook and Do, Quang Tuan and Win, Thwe Thwe and Lee, Donghyun and Oh, Junsuk and Cho, Sungrae},
  journal={IEEE Journal on Selected Areas in Communications}, 
  title={Multidomain Adaptive Semantic Communications}, 
  year={2025},
  volume={43},
  number={7},
  pages={2506-2517},
  keywords={Encoding;Semantic communication;Decoding;Signal to noise ratio;Adaptive systems;Transmitters;Generators;Receivers;Scalability;Adaptation models;Semantic communications;semantic coding;domain adaptation},
  doi={10.1109/JSAC.2025.3559127}
}
