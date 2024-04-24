# A Survey on Hallucination in Large Vision-Language Models
*updated 2024/02/01*

**This is the first released survey paper in the field of hallucinations in large vision-language models (LVLMs). Our paper focuses on the benchmark, evaluation methods, causes and mitigation methods of hallucinations in LVLMs.**
**Paper link:** [A Survey on Hallucination in Large Vision-Language Models]((https://arxiv.org/abs/2402.00253)

<img src="[图像链接](https://github.com/lhanchao777/Papers-for-Hallucinations-in-Large-Vision-Language-Models/assets/22700712/6947adfd-570d-4c9e-ac74-c506168be658)" width="60" height="90" />

Recent development of Large Vision-Language Models (LVLMs) has attracted growing attention within the AI landscape for its practical implementation potential. However, ''hallucination'', or more specifically, the misalignment between factual visual content and corresponding textual generation, poses a significant challenge of utilizing LVLMs. In this comprehensive survey, we dissect LVLM-related hallucinations in an attempt to establish an overview and facilitate future mitigation. Our scrutiny starts with a clarification of the concept of hallucinations in LVLMs, presenting a variety of hallucination symptoms and highlighting the unique challenges inherent in LVLM hallucinations. Subsequently, we outline the benchmarks and methodologies tailored specifically for evaluating hallucinations unique to LVLMs. Additionally, we delve into an investigation of the root causes of these hallucinations, encompassing insights from the training data and model components. We also critically review existing methods for mitigating hallucinations. The open questions and future directions pertaining to hallucinations within LVLMs are discussed to conclude this survey.

## Definitions of Hallucinations in Vision-Language Models
1. Rohrbach A, Hendricks L A, Burns K, et al. [Object hallucination in image captioning](https://arxiv.org/abs/1809.02156)[J]. arXiv preprint arXiv:1809.02156, 2018.


## Evaluation of Hallucinations in Large Vision-Language Models
1. Rohrbach A, Hendricks L A, Burns K, et al. [Object hallucination in image captioning](https://arxiv.org/abs/1809.02156)[J]. arXiv preprint arXiv:1809.02156, 2018.
2. Li Y, Du Y, Zhou K, et al. [Evaluating object hallucination in large vision-language models](https://arxiv.org/abs/2305.10355)[J]. arXiv preprint arXiv:2305.10355, 2023.
3. Hu H, Zhang J, Zhao M, et al. [CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning](https://arxiv.org/abs/2309.02301)[J]. arXiv preprint arXiv:2309.02301, 2023.
4. Gunjal A, Yin J, Bas E. [Detecting and preventing hallucinations in large vision language models](https://arxiv.org/abs/2308.06394)[J]. arXiv preprint arXiv:2308.06394, 2023.
5. Wang J, Zhou Y, Xu G, et al. [Evaluation and Analysis of Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2308.15126)[J]. arXiv preprint arXiv:2308.15126, 2023.
6. Liu H, Wan X. [Models See Hallucinations: Evaluating the Factuality in Video Captioning](https://arxiv.org/abs/2303.02961)[J]. arXiv preprint arXiv:2303.02961, 2023.
7. Liu F, Lin K, Li L, et al. [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565)[J]. arXiv preprint arXiv:2306.14565, 2023.
8. Lovenia H, Dai W, Cahyawijaya S, et al. [Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models](https://arxiv.org/abs/2310.05338)[J]. arXiv preprint arXiv:2310.05338, 2023.
9. liu F, Guan T, Li Z, et al. [HallusionBench: You See What You Think? Or You Think What You See? An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Models](https://arxiv.org/abs/2310.14566)[J]. arXiv preprint arXiv:2310.14566, 2023.
10. Jing L, Li R, Chen Y, et al. [FAITHSCORE: Evaluating Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2311.01477)[J]. arXiv preprint arXiv:2311.01477, 2023.
11. Wang J, Wang Y, Xu G, et al. [An LLM-free Multi-dimensional Benchmark for MLLMs Hallucination Evaluation](https://arxiv.org/abs/2311.07397)[J]. arXiv preprint arXiv:2311.07397, 2023.

<br></br>

## Mitigation of Hallucinations in Large Vision-Language Models
1. Biten A F, Gómez L, Karatzas D. [Let there be a clock on the beach: Reducing object hallucination in image captioning](http://openaccess.thecvf.com/content/WACV2022/html/Biten_Let_There_Be_a_Clock_on_the_Beach_Reducing_Object_WACV_2022_paper.html)[C]//Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision. 2022: 1381-1390. (Not for Large Vision-Language Models, only for image caption models)
2. Dai W, Liu Z, Ji Z, et al. [Plausible May Not Be Faithful: Probing Object Hallucination in Vision-Language Pre-training](https://arxiv.org/abs/2210.07688)[C]//Proceedings of the 17th Conference of the European Chapter of the Association for Computational Linguistics. 2023: 2128-2140. (Not for large vision-language models, only for vision-language pretraining models)
3. Hu H, Zhang J, Zhao M, et al. [CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning](https://arxiv.org/abs/2309.02301)[J]. arXiv preprint arXiv:2309.02301, 2023.
4. Gunjal A, Yin J, Bas E. [Detecting and preventing hallucinations in large vision language models](https://arxiv.org/abs/2308.06394)[J]. arXiv preprint arXiv:2308.06394, 2023.
5. Wang B, Wu F, Han X, et al. [VIGC: Visual Instruction Generation and Correction](https://arxiv.org/abs/2308.12714)[J]. arXiv preprint arXiv:2308.12714, 2023.
6. Liu F, Lin K, Li L, et al. [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565)[J]. arXiv preprint arXiv:2306.14565, 2023.
7. Sun Z, Shen S, Cao S, et al. [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2309.14525)[J]. arXiv preprint arXiv:2309.14525, 2023.
8. You H, Zhang H, Gan Z, et al. [Ferret: Refer and Ground Anything Anywhere at Any Granularity](https://arxiv.org/abs/2310.07704)[J]. arXiv preprint arXiv:2310.07704, 2023. 
9. Zhou Y, Cui C, Yoon J, et al. [Analyzing and Mitigating Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2310.00754)[J]. arXiv preprint arXiv:2310.00754, 2023. (Mitigating hallucination is not the main purpose of this paper)
10. Zhai B, Yang S, Zhao X, et al. [HallE-Switch: Rethinking and Controlling Object Existence Hallucinations in Large Vision Language Models for Detailed Caption](https://arxiv.org/abs/2310.01779)[J]. arxiv preprint arXiv:2310.01779, 2023.
11. Yin S, Fu C, Zhao S, et al. [Woodpecker: Hallucination Correction for Multimodal Large Language Models](https://arxiv.org/abs/2310.16045)[J]. arXiv preprint arXiv:2310.16045, 2023.
12. Lu J, Rao J, Chen K, et al. [Evaluation and Mitigation of Agnosia in Multimodal Large Language Models](https://arxiv.org/abs/2309.04041)[J]. arXiv preprint arXiv:2309.04041, 2023.
13. Lee S, Park S H, Jo Y, et al. [Volcano: Mitigating Multimodal Hallucination through Self-Feedback Guided Revision](https://arxiv.org/abs/2311.07362)[J]. arXiv preprint arXiv:2311.07362, 2023.
14. Zhao Z, Wang B, Ouyang L, et al. [Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization](https://arxiv.org/abs/2311.16839)[J]. arXiv preprint arXiv:2311.16839, 2023.
15. Leng S, Zhang H, Chen G, et al. [Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding](https://arxiv.org/abs/2311.16922)[J]. arXiv preprint arXiv:2311.16922, 2023.
16. Huang Q, Dong X, Zhang P, et al. [OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation](https://arxiv.org/abs/2311.17911)[J]. arXiv preprint arXiv:2311.17911, 2023.
17. Chen Z, Zhu Y, Zhan Y, et al. [Mitigating Hallucination in Visual Language Models with Visual Supervision](https://arxiv.org/abs/2311.16479)[J]. arXiv preprint arXiv:2311.16479, 2023.
18. Yu Q, Li J, Wei L, et al. [HalluciDoctor: Mitigating Hallucinatory Toxicity in Visual Instruction Data](https://arxiv.org/abs/2311.13614)[J]. arXiv preprint arXiv:2311.12614, 2023.
19. Yu T, Yao Y, Zhang H, et al. [RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback](https://arxiv.org/abs/2312.00849)[J]. arXiv preprint arXiv:2312.00849, 2023.
20. Wang L, He J, Li S, et al. [Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites](https://arxiv.org/abs/2312.01701)[C]. International Conference on Multimedia Modeling, 2023.

