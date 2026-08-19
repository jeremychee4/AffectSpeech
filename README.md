# AffectSpeech: A Large-Scale Emotional Speech Dataset with Fine-Grained Textual Descriptions for Speech Emotion Captioning and Synthesis

<!-- [![Paper](https://img.shields.io/badge/Paper-arXiv-red)]([Your_Paper_Link]) -->
[![License](https://img.shields.io/badge/License-EULA-blue)](EULA.pdf)

This repository provides the official distribution of the **AffetSpeech** dataset. AffetSpeech is a large-scale emotional speech dataset with fine-grained, multi-level textual descriptions, enabling advanced research in speech emotion captioning (SEC) and emotional speech synthesis (ESS), containing 253,799 high-quality emotional speech data and 1,522,794 natural language descriptions.

The demo can be accessed at: <a href="https://jeremychee4.github.io/AffectSpeech_Demo/" target="_blank">  https://jeremychee4.github.io/AffectSpeech_Demo/</a>.

The paper is available at: <a href="https://ieeexplore.ieee.org/document/11656683" target="_blank"> https://ieeexplore.ieee.org/document/11656683</a>

<!-- ## 📢 News -->
<!-- * **[2026/02/01]** AffetSpeech v1.0 is officially released! -->

---

## 📊 Dataset Overview
<!-- - **Speakers:** [Number] (e.g., 10 professional actors) -->
- **Emotions:** angry, disgust, fear, happy, neutral, sad, surprise, contempt, calm
- **Language:** English
- **Format:** 16kHz, 16-bit, PCM wav.
- **Annotations (ShareGPT format​):** Includes *sentiment polarity*, *open-vocabulary emotion captions*, *prosody (pitch, tempo, energy)*, *emotional intensity*, *prominent segments*, and *semantic analysis*.

---

## 📥 Access Request (EULA)

AffetSpeech is released under a **Restricted End User License Agreement (EULA)** for **non-commercial academic research** purposes only.

### Steps to Apply:
1.  **Download** the [EULA.pdf](EULA.pdf) from this repository.
2.  **Read and Sign**: Please read the terms carefully. The form must be signed by a **Permanent Staff/Faculty Member** (e.g., Professor or Senior Researcher) of your institution.
3.  **Submit**: Send the scanned PDF copy to **qitianhua@seu.edu.cn**.
    * **Email Subject**: `[AffetSpeech Request] Name - Institution`
    * **Email Body**: Please use your **institutional email address** (.edu, .ac, etc.) and briefly describe your intended use of the dataset.
4.  **Verification**: Once approved, we will send you a private link to download the full version.

---

## 📑 Citation

If you use **AffectSpeech** in your research, please cite:

### BibTeX
```bibtex
@ARTICLE{11656683,
  author={Qi, Tianhua and Zheng, Wenming and Schuller, Björn W. and Luo, Zhaojie and Li, Haizhou},
  journal={IEEE Transactions on Audio, Speech and Language Processing}, 
  title={AffectSpeech: A Large-Scale Emotional Speech Dataset with Fine-Grained Textual Descriptions for Speech Emotion Captioning and Synthesis}, 
  year={2026},
  volume={},
  number={},
  pages={1-16},
  doi={10.1109/TASLPRO.2026.3724419}
}

```
### Plain Text
T. Qi, W. Zheng, B. W. Schuller, Z. Luo and H. Li, "AffectSpeech: A Large-Scale Emotional Speech Dataset with Fine-Grained Textual Descriptions for Speech Emotion Captioning and Synthesis," in IEEE Transactions on Audio, Speech and Language Processing, doi: 10.1109/TASLPRO.2026.3724419.

---

## 📁 Repository Structure
```text
.
├── EULA.pdf               # License agreement to be signed
├── README.md              # Project description
├── metadata_sample/       # Small samples of annotations for preview
│   └── sample_sec.json
│   └── sample_ess.json
└── scripts/               # Helper scripts for data loading/evaluation
    └── data_loader.py
```
