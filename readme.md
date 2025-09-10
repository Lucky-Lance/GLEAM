# GLEAM: Learning to Match and Explain in Cross-View Geo-Localization

Xudong Lu\*, Zhi Zheng\*, Yi Wan, Yongxiang Yao, Annan Wang, Renrui Zhang, Panwang Xia, Qiong Wu, Qingyun Li, Weifeng Lin, Xiangyu Zhao, Xue Yang, Hongsheng Li

![GLEAM Overview](asserts/overview.png)

This repository contains the official implementation of **GLEAM**, a foundational pipeline for Cross-View Geo-Localization (CVGL) that unifies multi-modal and multi-view alignment with explainable reasoning. GLEAM consists of two core components:

- **GLEAM-C (A)**: A foundational CVGL model that aligns multiple views and modalities (UAV, street maps, panoramas, ground photos) with satellite imagery through efficient two-phase training.
- **GLEAM-X (B)**: A novel task that extends cross-view matching with explainable reasoning using multimodal large language models (MLLMs), supported by a bilingual benchmark.

## 🧠 Overview

Traditional CVGL methods are often limited to single views or modalities and lack interpretability. GLEAM addresses these limitations by:

- Unifying multiple geographic views and modalities into a single alignment framework.
- Introducing explainable reasoning into cross-view geo-localization via MLLM-powered analysis.
- Providing a bilingual (English/Chinese) benchmark for training and evaluating explainable CVGL systems.

## 🏗️ Framework

### GLEAM-C
GLEAM-C aligns diverse geographic views with satellite imagery through:
- Optimized implementation for efficient training.
- A two-phase training strategy achieving accuracy comparable to prior modality-specific models.

### GLEAM-X
GLEAM-X introduces a new task combining cross-view correspondence prediction with natural language explanations. It includes:
- A bilingual dataset generated using GPT-4o and Doubao-1.5-Thinking-Vision-Pro.
- A human-refined test set for systematic evaluation of explainable reasoning.

## 📜 Citation 

If you find our paper useful in your research, please cite

```
@misc{lu2025gleamlearningmatchexplain,
      title={GLEAM: Learning to Match and Explain in Cross-View Geo-Localization}, 
      author={Xudong Lu and Zhi Zheng and Yi Wan and Yongxiang Yao and Annan Wang and Renrui Zhang and Panwang Xia and Qiong Wu and Qingyun Li and Weifeng Lin and Xiangyu Zhao and Xue Yang and Hongsheng Li},
      year={2025},
      eprint={2509.07450},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2509.07450}, 
}
```

---
> 🔔 **Note**: This repository is under active development. Code and data will be fully released upon paper acceptance.

