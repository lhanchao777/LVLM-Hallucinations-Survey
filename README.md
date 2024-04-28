# A Survey on Hallucination in Large Vision-Language Models
*updated 2024/02/01*

**This is the first released survey paper in the field of hallucinations in large vision-language models (LVLMs). Our paper focuses on the benchmark, evaluation methods, causes and mitigation methods of hallucinations in LVLMs.**

**Paper link:** [A Survey on Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2402.00253)


![Hallucinations examples in LVLMs](https://github.com/lhanchao777/Papers-for-Hallucinations-in-Large-Vision-Language-Models/assets/22700712/9782ef66-9f08-4d78-a1ab-5cd5515dfbc9)



Recent development of Large Vision-Language Models (LVLMs) has attracted growing attention within the AI landscape for its practical implementation potential. However, ''hallucination'', or more specifically, the misalignment between factual visual content and corresponding textual generation, poses a significant challenge of utilizing LVLMs. In this comprehensive survey, we dissect LVLM-related hallucinations in an attempt to establish an overview and facilitate future mitigation. Our scrutiny starts with a clarification of the concept of hallucinations in LVLMs, presenting a variety of hallucination symptoms and highlighting the unique challenges inherent in LVLM hallucinations. Subsequently, we outline the benchmarks and methodologies tailored specifically for evaluating hallucinations unique to LVLMs. Additionally, we delve into an investigation of the root causes of these hallucinations, encompassing insights from the training data and model components. We also critically review existing methods for mitigating hallucinations. The open questions and future directions pertaining to hallucinations within LVLMs are discussed to conclude this survey.

---

<br> **📑 If you find our projects helpful to your research, please consider citing:** <br>
```
@article{liu2024survey,
  title={A survey on hallucination in large vision-language models},
  author={Liu, Hanchao and Xue, Wenyuan and Chen, Yifei and Chen, Dapeng and Zhao, Xiutian and Wang, Ke and Hou, Liping and Li, Rongjun and Peng, Wei},
  journal={arXiv preprint arXiv:2402.00253},
  year={2024}
}
```

---

## Evaluation Methods

|  Title  |   Name  |   Venue   |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/bcdnlp/FAITHSCORE.svg?style=social&label=Star) <br> [**FAITHSCORE: Evaluating Hallucinations in Large Vision-Language Models**](https://arxiv.org/pdf/2311.01477.pdf) <br> | **FAITHSCORE** | arXiv | 2023-11-02 | [Github](https://github.com/bcdnlp/FAITHSCORE) |
| [**Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models**](https://arxiv.org/pdf/2310.05338.pdf) | **NOPE** | arXiv | 2023-10-09 | |
| ![Star](https://img.shields.io/github/stars/bronyayang/HallE_Control.svg?style=social&label=Star) <br> [**HallE-Control: Controlling Object Hallucination in Large Multimodal Models**](https://arxiv.org/pdf/2310.01779.pdf) <br> | **CCEval** | arXiv | 2023-10-03 | [Github](https://github.com/bronyayang/HallE_Control) |
| ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star) <br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/pdf/2309.14525.pdf) <br> | **MMHal-Bench** | arXiv | 2023-09-25 | [Github](https://github.com/llava-rlhf/LLaVA-RLHF) |
| [**CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning**](https://arxiv.org/pdf/2309.02301.pdf) | **CIEM** | NeurIPS 2023 | 2023-09-05 | |
| ![Star](https://img.shields.io/github/stars/junyangwang0410/HaELM.svg?style=social&label=Star) <br> [**Evaluation and analysis of hallucination in large vision-language models**](https://arxiv.org/pdf/2308.15126.pdf) <br> | **HaELM** | arXiv | 2023-08-29 | [Github](https://github.com/junyangwang0410/HaELM) |
| ![Star](https://img.shields.io/github/stars/hendryx-scale/mhal-detect.svg?style=social&label=Star) <br> [**Detecting and preventing hallucinations in large vision language models**](https://arxiv.org/pdf/2308.06394.pdf) <br> | **M-HalDetect** | AAAI 2024 | 2023-08-11 | [Github](https://github.com/hendryx-scale/mhal-detect) |
| ![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star) <br> [**Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning**](https://openreview.net/pdf?id=J44HfH4JCg) <br> | **GAVIE** | ICLR 2024 | 2023-06-26 | [Github](https://github.com/FuxiaoLiu/LRV-Instruction) |
| ![Star](https://img.shields.io/github/stars/RUCAIBox/POPE.svg?style=social&label=Star) <br> [**Evaluating object hallucination in large vision-language models**](https://arxiv.org/pdf/2305.10355.pdf) <br> | **POPE** | EMNLP 2023 | 2023-05-17 | [Github](https://github.com/RUCAIBox/POPE) |
|[**Object hallucination in image captioning**](https://arxiv.org/pdf/1809.02156.pdf)| **CHAIR** | EMNLP 2019 | 2019-03-19 | |

---

## Benchmarks

|  Title  |   Name  |   Venue   |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/junyangwang0410/AMBER.svg?style=social&label=Star) <br> [**An llm-free multi-dimensional benchmark for mllms hallucination evaluation**](https://arxiv.org/pdf/2311.07397.pdf) <br> | **AMBER** | arXiv | 2023-11-13 | [Github](https://github.com/junyangwang0410/AMBER) |
| ![Star](https://img.shields.io/github/stars/bcdnlp/FAITHSCORE.svg?style=social&label=Star) <br> [**FAITHSCORE: Evaluating Hallucinations in Large Vision-Language Models**](https://arxiv.org/pdf/2311.01477.pdf) <br> | **FAITHSCORE** | arXiv | 2023-11-02 | [Github](https://github.com/bcdnlp/FAITHSCORE) |
| [**Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models**](https://arxiv.org/pdf/2310.05338.pdf) | **NOPE** | arXiv | 2023-10-09 | |
| ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star) <br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/pdf/2309.14525.pdf) <br> | **MMHal-Bench** | arXiv | 2023-09-25 | [Github](https://github.com/llava-rlhf/LLaVA-RLHF) |
| [**CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning**](https://arxiv.org/pdf/2309.02301.pdf) | **CIEM** | NeurIPS 2023 | 2023-09-05 | |
| ![Star](https://img.shields.io/github/stars/junyangwang0410/HaELM.svg?style=social&label=Star) <br> [**Evaluation and analysis of hallucination in large vision-language models**](https://arxiv.org/pdf/2308.15126.pdf) <br> | **HaELM** | arXiv | 2023-08-29 | [Github](https://github.com/junyangwang0410/HaELM) |
| ![Star](https://img.shields.io/github/stars/hendryx-scale/mhal-detect.svg?style=social&label=Star) <br> [**Detecting and preventing hallucinations in large vision language models**](https://arxiv.org/pdf/2308.06394.pdf) <br> | **M-HalDetect** | AAAI 2024 | 2023-08-11 | [Github](https://github.com/hendryx-scale/mhal-detect) |
| ![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star) <br> [**Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning**](https://openreview.net/pdf?id=J44HfH4JCg) <br> | **GAVIE** | ICLR 2024 | 2023-06-26 | [Github](https://github.com/FuxiaoLiu/LRV-Instruction) |
| ![Star](https://img.shields.io/github/stars/RUCAIBox/POPE.svg?style=social&label=Star) <br> [**Evaluating object hallucination in large vision-language models**](https://arxiv.org/pdf/2305.10355.pdf) <br> | **POPE** | EMNLP 2023 | 2023-05-17 | [Github](https://github.com/RUCAIBox/POPE) |

---

## Mitigation Methods

|  Title  |   Name  |   Venue   |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) <br> [**InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks**](https://arxiv.org/pdf/2312.14238.pdf) <br> | **InternVL** | arXiv | 2023-12-21 | [Github](https://github.com/OpenGVLab/InternVL) |
| ![Star](https://img.shields.io/github/stars/SHI-Labs/VCoder.svg?style=social&label=Star) <br> [**VCoder: Versatile Vision Encoders for Multimodal Large Language Models**](https://arxiv.org/pdf/2312.14233.pdf) <br> | **VCoder** | arXiv | 2023-12-21 | [Github](https://github.com/SHI-Labs/VCoder) |
| [**Hallucination augmented contrastive learning for multimodal large language model**](https://arxiv.org/pdf/2312.06968.pdf)| **HACL** | arXiv | 2023-12-12 | [Github](https://github.com/X-PLUG/mPLUG-HalOwl/tree/main/hacl) |
| ![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V.svg?style=social&label=Star) <br> [**RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback**](https://arxiv.org/pdf/2312.00849.pdf) <br> | **RLHF-V** | arXiv | 2023-12-01 | [Github](https://github.com/RLHF-V/RLHF-V) |
| ![Star](https://img.shields.io/github/stars/shikiw/OPERA.svg?style=social&label=Star) <br> [**OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation**](https://arxiv.org/pdf/2311.17911.pdf) <br> | **OPERA** | arXiv | 2023-11-29 | [Github](https://github.com/shikiw/OPERA) |
| ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/VCD.svg?style=social&label=Star) <br> [**Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding**](https://arxiv.org/pdf/2311.16922.pdf) <br> | **VCD** | arXiv | 2023-11-28 | [Github](https://github.com/DAMO-NLP-SG/VCD) |
| ![Star](https://img.shields.io/github/stars/opendatalab/HA-DPO.svg?style=social&label=Star) <br> [**Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization**](https://arxiv.org/pdf/2311.16839.pdf) <br> | **HA-DPO** | arXiv | 2023-11-28 | [Github](https://github.com/opendatalab/HA-DPO) |
| ![Star](https://img.shields.io/github/stars/Yuliang-Liu/Monkey.svg?style=social&label=Star) <br> [**Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models**](https://arxiv.org/pdf/2311.06607.pdf) <br> | **Ferret** | arXiv | 2023-11-11 | [Github](https://github.com/Yuliang-Liu/Monkey) |
| [**Enhancing the Spatial Awareness Capability of Multi-Modal Large Language Model**](https://arxiv.org/pdf/2310.20357.pdf) | **Spatial Awareness Enhancing** | arXiv | 2023-10-31 | |
| ![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star) <br> [**Woodpecker: Hallucination Correction for Multimodal Large Language Models**](https://arxiv.org/pdf/2310.16045.pdf) <br> | **Woodpecker** | arXiv | 2023-10-24 | [Github](https://github.com/BradyFU/Woodpecker) |
| ![Star](https://img.shields.io/github/stars/apple/ml-ferret.svg?style=social&label=Star) <br> [**Ferret: Refer and Ground Anything Anywhere at Any Granularity**](https://arxiv.org/pdf/2310.07704.pdf) <br> | **Ferret** | ICLR 2024 | 2023-10-11 | [Github](https://github.com/apple/ml-ferret) |
| ![Star](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star) <br> [**Improved Baselines with Visual Instruction Tuning**](https://arxiv.org/pdf/2310.03744.pdf) <br> | **LLaVA-1.5** | NeurIPS 2023 | 2023-10-05 | [Github](https://github.com/haotian-liu/LLaVA) |
| ![Star](https://img.shields.io/github/stars/bronyayang/HallE_Control.svg?style=social&label=Star) <br> [**HallE-Switch: Rethinking and Controlling Object Existence Hallucinations in Large Vision Language Models for Detailed Caption**](https://arxiv.org/pdf/2310.01779.pdf) <br> | **HallE-Switch** | arXiv | 2023-10-03 | [Github](https://github.com/bronyayang/HallE_Control) |
| ![Star](https://img.shields.io/github/stars/YiyangZhou/LURE.svg?style=social&label=Star) <br> [**Analyzing and Mitigating Object Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2310.00754.pdf) <br> | **LURE** | arXiv | 2023-10-01 | [Github](https://github.com/YiyangZhou/LURE) |
| ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star) <br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/pdf/2309.14525.pdf) <br> | **MMHal-Bench** | arXiv | 2023-09-25 | [Github](https://github.com/llava-rlhf/LLaVA-RLHF) |
| [**Evaluation and Mitigation of Agnosia in Multimodal Large Language Models**](https://arxiv.org/pdf/2309.04041.pdf) | **EMMA** | ICLR 2024 | 2023-09-07 | |
| [**CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning**](https://arxiv.org/pdf/2309.02301.pdf) | **CIEM** | NeurIPS 2023 | 2023-09-05 | |
| ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star) <br> [**Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond**](https://arxiv.org/pdf/2308.12966.pdf) <br> | **Qwen-VL** | arXiv | 2023-08-24 | [Github](https://github.com/QwenLM/Qwen-VL) |
| ![Star](https://img.shields.io/github/stars/hendryx-scale/mhal-detect.svg?style=social&label=Star) <br> [**Detecting and preventing hallucinations in large vision language models**](https://arxiv.org/pdf/2308.06394.pdf) <br> | **FDPO** | AAAI 2024 | 2023-08-11 | [Github](https://github.com/hendryx-scale/mhal-detect) |
| ![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star) <br> [**Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning**](https://openreview.net/pdf?id=J44HfH4JCg) <br> | **LRV-Instruction** | ICLR 2024 | 2023-06-26 | [Github](https://github.com/FuxiaoLiu/LRV-Instruction) |

---


