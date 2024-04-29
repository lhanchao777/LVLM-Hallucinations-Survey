# A Survey on Hallucination in Large Vision-Language Models
*updated 2024/04/29*

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
| ![Star](https://img.shields.io/github/stars/haoyiq114/VALOR.svg?style=social&label=Star) <br> [**VALOR-EVAL: Holistic Coverage and Faithfulness Evaluation of Large Vision-Language Models**](https://arxiv.org/pdf/2404.13874.pdf) <br> | **VALOR-Eval** | arXiv | 2024-04-22 | [Github](https://github.com/haoyiq114/VALOR) |
| [**ALOHa: A New Measure for Hallucination in Captioning Models**](https://arxiv.org/pdf/2404.02904.pdf) <br> | **ALOHa** | arXiv | 2024-04-03 | |
| [**Cartoon Hallucinations Detection: Pose-aware In Context Visual Learning**](https://arxiv.org/pdf/2403.15048.pdf) <br> | **PA-ICVL (for hallucinations in generated images)** | arXiv | 2024-03-22 | |
| [**Hal-Eval: A Universal and Fine-grained Hallucination Evaluation Framework for Large Vision Language Models**](https://arxiv.org/pdf/2403.11116.pdf) | **AFHA** | arXiv | 2024-02-24 | |
| ![Star](https://img.shields.io/github/stars/Anonymousanoy/FOHE.svg?style=social&label=Star) <br> [**Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites**](https://arxiv.org/pdf/2312.01701.pdf) <br> | **FGHE** | arXiv | 2023-12-04 | [Github](https://github.com/Anonymousanoy/FOHE) |
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
| ![Star](https://img.shields.io/github/stars/haoyiq114/VALOR.svg?style=social&label=Star) <br> [**VALOR-EVAL: Holistic Coverage and Faithfulness Evaluation of Large Vision-Language Models**](https://arxiv.org/pdf/2404.13874.pdf) <br> | **VALOR** | arXiv | 2024-04-22 | [Github](https://github.com/haoyiq114/VALOR) |
| ![Star](https://img.shields.io/github/stars/jiazhen-code/IntrinsicHallu.svg?style=social&label=Star) <br> [**PhD: A Prompted Visual Hallucination Evaluation Dataset**](https://arxiv.org/pdf/2403.11116.pdf) <br> | **Phd** | arXiv | 2024-03-17 | [Github](https://github.com/jiazhen-code/IntrinsicHallu) |
| [**Hal-Eval: A Universal and Fine-grained Hallucination Evaluation Framework for Large Vision Language Models**](https://arxiv.org/pdf/2403.11116.pdf) | **Hal-Eval** | arXiv | 2024-02-24 | |
| ![Star](https://img.shields.io/github/stars/wenhuang2000/VHTest.svg?style=social&label=Star) <br> [**Visual Hallucinations of Multi-modal Large Language Models**](https://arxiv.org/pdf/2402.14683.pdf) <br> | **VHTest** | arXiv | 2024-02-22 | [Github](https://github.com/wenhuang2000/VHTest) |
| [**Visually Dehallucinative Instruction Generation: Know What You Don't Know**](https://arxiv.org/pdf/2402.09717.pdf) | **VQAv2-IDK** | arXiv | 2024-02-15 | |
| ![Star](https://img.shields.io/github/stars/MasaiahHan/CorrelationQA.svg?style=social&label=Star) <br> [**The Instinctive Bias: Spurious Images lead to Hallucination in MLLMs**](https://arxiv.org/pdf/2402.03757.pdf) <br> | **CorrelationQA** | arXiv | 2024-02-06 | [Github](https://github.com/MasaiahHan/CorrelationQA) |
| ![Star](https://img.shields.io/github/stars/knowlab/halt-medvqa.svg?style=social&label=Star) <br> [**Hallucination Benchmark in Medical Visual Question Answering**](https://arxiv.org/pdf/2401.05827.pdf) <br> | | ICLR 2024 | 2024-01-11 | [Github](https://github.com/knowlab/halt-medvqa) |
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
| [**Detecting and Mitigating Hallucination in Large Vision Language Models via Fine-Grained AI Feedback**](https://arxiv.org/pdf/2404.14233.pdf) | **HSA-DPO** | arXiv | 2024-04-22 | |
| [**Fact :Teaching MLLMs with Faithful, Concise and Transferable Rationales**](https://arxiv.org/pdf/2404.11129.pdf) | **Fact** | arXiv | 2023-04-17 | |
| [**Prescribing the Right Remedy: Mitigating Hallucinations in Large Vision-Language Models via Targeted Instruction Tuning**](https://arxiv.org/pdf/2404.10332.pdf) | **DFTG** | arXiv | 2024-04-16 | |
| [**Learning to Localize Objects Improves Spatial Reasoning in Visual-LLMs**](https://arxiv.org/pdf/2404.07449.pdf) | | arXiv | 2024-04-11 | |
| [**BRAVE: Broadening the visual encoding of vision-language models**](https://arxiv.org/pdf/2404.07204.pdf) | **BRAVE** | arXiv | 2024-04-10 | |
| [**FGAIF: Aligning Large Vision-Language Models with Fine-grained AI Feedback**](https://arxiv.org/pdf/2404.05046.pdf) | **FGAIF** | arXiv | 2024-04-07 | |
| ![Star](https://img.shields.io/github/stars/opendatalab/H2RSVLM.svg?style=social&label=Star) <br> [**H2RSVLM: Towards Helpful and Honest Remote Sensing Large Vision Language Model**](https://arxiv.org/pdf/2403.20213.pdf) <br> | **RSSA** | arXiv | 2024-03-29 | [Github](https://github.com/opendatalab/H2RSVLM) |
| [**Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding**](https://arxiv.org/pdf/2403.18715.pdf) | **ICD** | arXiv | 2024-03-27 | |
| [**Visual Hallucination: Definition, Quantification, and Prescriptive Remediations**](https://arxiv.org/pdf/2403.17306.pdf) | VHILT | arXiv | 2024-03-26 | |
| [**Exploiting Semantic Reconstruction to Mitigate Hallucinations in Vision-Language Models**](https://arxiv.org/pdf/2403.16167.pdf) | **ESREAL** | arXiv | 2024-03-24 | |
| ![Star](https://img.shields.io/github/stars/DingchenYang99/Pensieve.svg?style=social&label=Star) <br> [**Pensieve: Retrospect-then-Compare Mitigates Visual Hallucination**](https://arxiv.org/pdf/2403.14401.pdf) <br> | **Pensieve** | arXiv | 2024-03-21 | [Github](https://github.com/DingchenYang99/Pensieve) |
| [**Multi-Modal Hallucination Control by Visual Information Grounding**](https://arxiv.org/pdf/2403.14003.pdf) | **M3ID** | arXiv | 2024-03-20 | |
| ![Star](https://img.shields.io/github/stars/IVY-LVLM/Counterfactual-Inception.svg?style=social&label=Star) <br> [**What if...?: Counterfactual Inception to Mitigate Hallucination Effects in Large Multimodal Models**](https://arxiv.org/pdf/2403.13513.pdf) <br> | **Counterfactual Inception** | arXiv | 2024-03-20 | [Github](https://github.com/IVY-LVLM/Counterfactual-Inception) |
| ![Star](https://img.shields.io/github/stars/yfzhang114/LLaVA-Align.svg?style=social&label=Star) <br> [**Debiasing Multimodal Large Language Models**](https://arxiv.org/pdf/2403.05262.pdf) <br> | **LLaVA-Align** | arXiv | 2024-03-08 | [Github](https://github.com/yfzhang114/LLaVA-Align) |
| [**Quantity Matters: Towards Assessing and Mitigating Number Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2403.01373.pdf) | | arXiv | 2024-03-03 | | 
| ![Star](https://img.shields.io/github/stars/BillChan226/HALC.svg?style=social&label=Star) <br> [**HALC: Object Hallucination Reduction via Adaptive Focal-Contrast Decoding**](https://arxiv.org/pdf/2403.00425.pdf) <br> | **HALC** | arXiv | 2024-03-01 | [Github](https://github.com/BillChan226/HALC) |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/all-seeing.svg?style=social&label=Star) <br> [**The All-Seeing Project V2: Towards General Relation Comprehension of the Open World**](https://arxiv.org/pdf/2402.19474.pdf) <br> | **ASMv2** | arXiv | 2024-02-29 | [Github](https://github.com/OpenGVLab/all-seeing) |
| [**IBD: Alleviating Hallucinations in Large Vision-Language Models via Image-Biased Decoding**](https://arxiv.org/pdf/2402.18476.pdf) | **IBD** | arXiv | 2024-02-28 | |
| [**GROUNDHOG: Grounding Large Language Models to Holistic Segmentation**](https://arxiv.org/pdf/2402.16846.pdf) | **GROUNDHOG** | arXiv | 2024-02-26 | [Coming Soon](https://groundhog-mllm.github.io/) |
| ![Star](https://img.shields.io/github/stars/d-ailin/CLIP-Guided-Decoding.svg?style=social&label=Star) <br> [**Seeing is Believing: Mitigating Hallucination in Large Vision-Language Models via CLIP-Guided Decoding**](https://arxiv.org/pdf/2402.15300.pdf) <br> | **CGD** | arXiv | 2024-02-23 | [Github](https://github.com/d-ailin/CLIP-Guided-Decoding) |
| [**DualFocus: Integrating Macro and Micro Perspectives in Multi-modal Large Language Models**](https://arxiv.org/pdf/2402.14767.pdf) | **CGD** | arXiv | 2024-02-22 | [Github](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/DualFocus) |
| ![Star](https://img.shields.io/github/stars/yuezih/less-is-more.svg?style=social&label=Star) <br> [**Less is More: Mitigating Multimodal Hallucination from an EOS Decision Perspective**](https://arxiv.org/pdf/2402.14545.pdf) <br> | | arXiv | 2024-02-22 | [Github](https://github.com/yuezih/less-is-more) |
| ![Star](https://img.shields.io/github/stars/Hyperwjf/LogicCheckGPT.svg?style=social&label=Star) <br> [**Logical Closed Loop: Uncovering Object Hallucinations in Large Vision-Language Models**](https://arxiv.org/pdf/2402.11622.pdf) <br> | **LogicCheckGPT** | arXiv | 2024-02-18 | [Github](https://github.com/Hyperwjf/LogicCheckGPT) |
| ![Star](https://img.shields.io/github/stars/YiyangZhou/POVID.svg?style=social&label=Star) <br> [**Aligning Modalities in Vision Large Language Models via Preference Fine-tuning**](https://arxiv.org/pdf/2402.11411.pdf) <br> | **POVID** | arXiv | 2024-02-18 | [Github](https://github.com/YiyangZhou/POVID) |
| [**EFUF: Efficient Fine-grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models**](https://arxiv.org/pdf/2402.09801.pdf) | **EFUF** | arXiv | 2024-02-15 | |
| [**Mitigating Object Hallucination in Large Vision-Language Models via Classifier-Free Guidance**](https://arxiv.org/pdf/2402.08680.pdf) | **MARINE** | arXiv | 2024-02-13 | |
| [**Visually Dehallucinative Instruction Generation**](https://arxiv.org/pdf/2402.08348.pdf) | **CAP2QA**| ICASSP 2024 | 2024-02-13 | |
| [**ViGoR: Improving Visual Grounding of Large Vision Language Models with Fine-Grained Reward Modeling**](https://arxiv.org/pdf/2402.06118.pdf) | | arXiv | 2024-02-09 | |
| ![Star](https://img.shields.io/github/stars/hanmenghan/Skip-n.svg?style=social&label=Star) <br> [**Skip \n: A Simple Method to Reduce Hallucination in Large Vision-Language Models**](https://arxiv.org/pdf/2402.01345.pdf) <br> | **Skip \n** | arXiv | 2024-02-02 | [Github](https://github.com/hanmenghan/Skip-n) |
| [**Temporal Insight Enhancement: Mitigating Temporal Hallucination in Multimodal Large Language Models**](https://arxiv.org/pdf/2401.09861.pdf) | | arXiv | 2024-01-18 | |
| ![Star](https://img.shields.io/github/stars/tsb0601/MMVP.svg?style=social&label=Star) <br> [**Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs**](https://arxiv.org/pdf/2401.06209.pdf) <br> | **MoF** | arXiv | 2024-01-11 | [Github](https://github.com/tsb0601/MMVP) |
| ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) <br> [**InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks**](https://arxiv.org/pdf/2312.14238.pdf) <br> | **InternVL** | arXiv | 2023-12-21 | [Github](https://github.com/OpenGVLab/InternVL) |
| ![Star](https://img.shields.io/github/stars/SHI-Labs/VCoder.svg?style=social&label=Star) <br> [**VCoder: Versatile Vision Encoders for Multimodal Large Language Models**](https://arxiv.org/pdf/2312.14233.pdf) <br> | **VCoder** | arXiv | 2023-12-21 | [Github](https://github.com/SHI-Labs/VCoder) |
| ![Star](https://img.shields.io/github/stars/vlf-silkie/VLFeedback.svg?style=social&label=Star) <br> [**Silkie: Preference Distillation for Large Visual Language Models**](https://arxiv.org/pdf/2312.10665.pdf) <br> | **Silkie** | arXiv | 2023-12-17 | [Github](https://github.com/vlf-silkie/VLFeedback) |
| [**Hallucination augmented contrastive learning for multimodal large language model**](https://arxiv.org/pdf/2312.06968.pdf)| **HACL** | arXiv | 2023-12-12 | [Github](https://github.com/X-PLUG/mPLUG-HalOwl/tree/main/hacl) |
| ![Star](https://img.shields.io/github/stars/Anonymousanoy/FOHE.svg?style=social&label=Star) <br> [**Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites**](https://arxiv.org/pdf/2312.01701.pdf) <br> | **ReCaption** | arXiv | 2023-12-04 | [Github](https://github.com/Anonymousanoy/FOHE) |
| ![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V.svg?style=social&label=Star) <br> [**RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback**](https://arxiv.org/pdf/2312.00849.pdf) <br> | **RLHF-V** | arXiv | 2023-12-01 | [Github](https://github.com/RLHF-V/RLHF-V) |
| ![Star](https://img.shields.io/github/stars/shikiw/OPERA.svg?style=social&label=Star) <br> [**OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation**](https://arxiv.org/pdf/2311.17911.pdf) <br> | **OPERA** | arXiv | 2023-11-29 | [Github](https://github.com/shikiw/OPERA) |
| ![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/VCD.svg?style=social&label=Star) <br> [**Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding**](https://arxiv.org/pdf/2311.16922.pdf) <br> | **VCD** | arXiv | 2023-11-28 | [Github](https://github.com/DAMO-NLP-SG/VCD) |
| ![Star](https://img.shields.io/github/stars/opendatalab/HA-DPO.svg?style=social&label=Star) <br> [**Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization**](https://arxiv.org/pdf/2311.16839.pdf) <br> | **HA-DPO** | arXiv | 2023-11-28 | [Github](https://github.com/opendatalab/HA-DPO) |
| [**Mitigating Hallucination in Visual Language Models with Visual Supervision**](https://arxiv.org/pdf/2311.16479.pdf) | | arXiv | 2023-11-27 | |
| ![Star](https://img.shields.io/github/stars/Yuqifan1117/HalluciDoctor.svg?style=social&label=Star) <br> [**HalluciDoctor: Mitigating Hallucinatory Toxicity in Visual Instruction Data**](https://arxiv.org/pdf/2311.13614.pdf) <br> | **HalluciDoctor** | arXiv | 2023-11-22 | [Github](https://github.com/Yuqifan1117/HalluciDoctor) |
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


