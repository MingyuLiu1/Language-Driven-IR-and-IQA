# Language-Driven Image Restoration and Semantic-Aware Quality Assessment: A Survey

<div align="center">
<a href="https://www.preprints.org/manuscript/202603.2366"><img src="https://img.shields.io/badge/preprint-202603.2366-orange.svg" alt="Preprint Badge"/></a>
<a href="https://github.com/MingyuLiu1/Language-Driven-IR-and-IQA/stargazers"><img src="https://img.shields.io/github/stars/MingyuLiu1/Language-Driven-IR-and-IQA" alt="Stars Badge"/></a>
<a href="https://github.com/MingyuLiu1/Language-Driven-IR-and-IQA/network/members"><img src="https://img.shields.io/github/forks/MingyuLiu1/Language-Driven-IR-and-IQA" alt="Forks Badge"/></a>
<a href="https://github.com/MingyuLiu1/Language-Driven-IR-and-IQA/issues"><img src="https://img.shields.io/github/issues/MingyuLiu1/Language-Driven-IR-and-IQA" alt="Issues Badge"/></a>
<a href="https://github.com/MingyuLiu1/Language-Driven-IR-and-IQA/blob/main/LICENSE"><img src="https://img.shields.io/github/license/MingyuLiu1/Language-Driven-IR-and-IQA" alt="License Badge"/></a>
</div>

A structured repository for papers, taxonomy, benchmarks, and resources on language-driven image restoration (IR) and language-driven image quality assessment (IQA). The repo maintained by [TUM-AIR](https://www.ce.cit.tum.de/air/home/) will be continuously updated to track the latest work in the community. 


## 📄 Abstract

Image restoration aims to recover a high-quality image from its degraded counterpart by mitigating distortions introduced during acquisition, transmission, or environmental interaction. Despite the remarkable progress of deep learning–based restoration models, most conventional approaches remain tightly coupled to predefined degradation assumptions and pixel-level supervision, limiting their capability to handle complex and diverse scenarios or user-dependent restoration targets. Recent advances in multimodal large language models (MLLMs) and vision–language models (VLMs) have introduced a new paradigm in which restoration systems incorporate semantic reasoning, language-driven interaction, and cross-modal knowledge. By integrating language models, restoration is extended beyond low-level reconstruction toward degradation interpretation, perceptual alignment, and high-level controllability. In this survey, we provide a systematic review of language-driven image restoration, organized through an interaction-centric taxonomy that characterizes how language models are coupled with restoration pipelines. We analyze representative frameworks from the perspectives of semantic conditioning, perceptual supervision, and execution-level interaction, and discuss how these mechanisms influence restoration objectives and system design. In addition, we review emerging language-driven image quality assessment (IQA) approaches, highlighting their complementary role to conventional fidelity-based metrics. Finally, we identify unresolved challenges and outline potential research directions toward more robust, efficient, and trustworthy restoration techniques.

**Keywords: Image Restoration, Image Quality Assessment, Vision Language Model, Multimodal Large Language Model**

<p align="center">
<img src="assets/taxonomy.png" widt="88%">
</p>

<details>
<summary><b>Prototype</b></summary>
<p align="center">
<img src="assets/prototype.png" widt="80%">
</p>
</details>

<details>
<summary><b>Timeline</b></summary>
<p align="center">
  <img src="assets/timeline.png" alt="timeline" width="100%">
</p>
</details>


## :fire: Update
- [April 08 2026] Preprints version has been released: [Link](https://www.preprints.org/manuscript/202603.2366)


## 📌 TODO

- [ ] Complete the paper table
- [ ] Add language-driven IQA subsection
- [ ] Complete dataset table


## 📚 Papers by Task

<details>
<summary><b>Denoising</b></summary>
<br>

| Method | Venue | Task | Domain | Coupling Level | Code |
|---|---|---|---|---|---|
| [Paper 1](https://arxiv.org/) | CVPR 2024 | Denoising | Natural | Feature-level | [Code](https://github.com/) |
| [Paper 2](https://arxiv.org/) | ECCV 2024 | Denoising | Natural | Optimization-level | N/A |
| [Paper 3](https://arxiv.org/) | AAAI 2025 | Denoising | UHD | Execution-level | [Code](https://github.com/) |
</details>

<details>
<summary><b>Deraining</b></summary>
</details>

<details>
<summary><b>Dehazing</b></summary>
</details>

<details>
<summary><b>Desnowing</b></summary>
</details>

<details>
<summary><b>Deblurring</b></summary>
</details>

<details>
<summary><b>Low-Light Image Enhancement</b></summary>
</details>

<details>
<summary><b>Super-Resolution</b></summary>
</details>

<details>
<summary><b>Underwater Image Enhacenmebt</b></summary>
</details>

<details>
<summary><b>All-in-One</b></summary>
</details>

## ⚖️ Evaluation Metrics

<details>
<summary><b>Conventional IQA Methods</b></summary>
<br>

| Method | Paper | Sub-category | GT Required |
|---|---|---|---|
| PSNR | N/A | Non-Learning-Based | ✓ |
| SSIM | [Image quality assessment: from error visibility to structural similarity](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf) | Non-Learning-Based | ✓ |
| FSIM | [FSIM: A feature similarity index for image quality assessment](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=FSIM%3A+A+feature+similarity+index+for+image+quality+assessment&btnG=) | Non-Learning-Based | ✓ |
| MAE | N/A | Non-Learning-Based | ✓ |
| MSE | N/A | Non-Learning-Based | ✓ |
| RMSE | N/A | Non-Learning-Based | ✓ |
| ERGAS | [On the performance evaluation of pan-sharpening techniques](https://www.researchgate.net/profile/Roger-King-4/publication/3449922_On_the_Performance_Evaluation_of_Pan-Sharpening_Techniques/links/0fcfd509845bd01bc9000000/On-the-Performance-Evaluation-of-Pan-Sharpening-Techniques.pdf) | Non-Learning-Based | ✓ |
| LPIPS | [The unreasonable effectiveness of deep features as a perceptual metric](https://arxiv.org/abs/1801.03924) | Learning-Based | ✓ |
| DISTS | [Image quality assessment: Unifying structure and texture similarity](https://arxiv.org/abs/2004.07728) | Learning-Based | ✓ |
| CKDN | [Learning conditional knowledge distillation for degraded-reference image quality assessment](https://arxiv.org/abs/2108.07948) | Learning-Based | ✓ |
| AHIQ | [Attentions help cnns see better: Attention-based hybrid image quality assessment network](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Lao_Attentions_Help_CNNs_See_Better_Attention-Based_Hybrid_Image_Quality_Assessment_CVPRW_2022_paper.html) | Learning-Based | ✓ |
| TOPIQ-FR | [Topiq: A top-down approach from semantics to distortions for image quality assessment](https://arxiv.org/abs/2308.03060) | Learning-Based | ✓ |
| FID | [Gans trained by a two time-scale update rule converge to a local nash equilibrium](https://arxiv.org/abs/1706.08500) | Distribution-based | ✓ |
| BRISQUE | [No-reference image quality assessment in the spatial domain](https://www.live.ece.utexas.edu/publications/2012/TIP%20BRISQUE.pdf) | Hand-Crafted | × |
| NIQE | [Making a “completely blind” image quality analyzer](https://www.live.ece.utexas.edu/publications/2013/mittal2013.pdf) | Hand-Crafted | × |
| PIQE | [Blind image quality evaluation using perception based features](https://ieeexplore.ieee.org/document/7084843) | Hand-Crafted | × |
| LOE | [Naturalness preserved enhancement algorithm for non-uniform illumination images](https://ieeexplore.ieee.org/document/6512558) | Hand-Crafted | × |
| PI | [The 2018 PIRM challenge on perceptual image super-resolution](https://arxiv.org/pdf/1809.07517) | Hand-Crafted | × |
| MUSIQ | [Musiq: Multi-scale image quality transformer](https://arxiv.org/abs/2108.05997) | Learning-Based | × |
| MANIQA | [Maniqa: Multi-dimension attention network for no-reference image quality assessment](https://arxiv.org/abs/2204.08958) | Learning-Based | × |
| NIMA | [NIMA: Neural image assessment](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8352823) | Learning-Based | × |
| HyperIQA | [Blindly assess image quality in the wild guided by a self-adaptive hyper network](https://openaccess.thecvf.com/content_CVPR_2020/html/Su_Blindly_Assess_Image_Quality_in_the_Wild_Guided_by_a_CVPR_2020_paper.html) | Learning-Based | × |
| PAQ2-PIQ | [From patches to pictures (PaQ-2-PiQ): Mapping the perceptual space of picture quality](https://openaccess.thecvf.com/content_CVPR_2020/html/Ying_From_Patches_to_Pictures_PaQ-2-PiQ_Mapping_the_Perceptual_Space_of_CVPR_2020_paper.html) | Learning-Based | × |
| DBCNN | [Blind image quality assessment using a deep bilinear convolutional neural network](https://arxiv.org/pdf/1907.02665) | Learning-Based | × |
| TOPIQNR | [Topiq: A top-down approach from semantics to distortions for image quality assessment](https://arxiv.org/abs/2308.03060) | Learning-Based | × |
| CNNIQA | [Convolutional neural networks for no-reference image quality assessment](https://www.cv-foundation.org/openaccess/content_cvpr_2014/html/Kang_Convolutional_Neural_Networks_2014_CVPR_paper.html) | Learning-Based | × |

</details>

<details>
<summary><b>Language-Driven IQA Methods</b></summary>
<br>

| Method | Paper | Sub-category | GT Required |
|---|---|---|---|
| CLIP-IQA | [Exploring clip for assessing the look and feel of images](https://arxiv.org/abs/2207.12396) | Alignment-Based | × |
| QualiCLIP | [Quality-aware image-text alignment for opinion-unaware image quality assessment](https://arxiv.org/abs/2403.11176) | Alignment-Based | × |
| LIQE | [Blind image quality assessment via vision-language correspondence: A multitask learning perspective](https://arxiv.org/abs/2303.14968) | Alignment-Based | × |
| SCUIA | [Semantic Contrast for Domain-Robust Underwater Image Quality Assessment](https://ieeexplore.ieee.org/abstract/document/11353920) | Alignment-Based | × |
| PromptIQA | [Promptiqa: Boosting the performance and generalization for no-reference image quality assessment via prompts](https://arxiv.org/abs/2403.04993) | Alignment-Based | × |
| GRMP-IQA | [Few-Shot Image Quality Assessment via Adaptation of Vision-Language Models](https://arxiv.org/abs/2409.05381) | Alignment-Based | × |
| ATTIQA | [ATTIQA: Generalizable image quality feature extractor using attribute-aware pretraining](https://arxiv.org/abs/2406.01020) | Alignment-Based | × |
| CAP-IQA | [CAP-IQA: Context-Aware Prompt-Guided CT Image Quality Assessment](https://arxiv.org/abs/2601.01613) | Alignment-Based | × |
| SFD | [Exploring semantic feature discrimination for perceptual image super-resolution and opinion-unaware no-reference image quality assessment](https://openaccess.thecvf.com/content/CVPR2025/html/Dong_Exploring_Semantic_Feature_Discrimination_for_Perceptual_Image_Super-Resolution_and_Opinion-Unaware_CVPR_2025_paper.html) | Alignment-Based | × |
| UniQA | [UniQA: Unified vision-language pre-training for image quality and aesthetic assessment](https://arxiv.org/abs/2406.01069) | Alignment-Based | × |
| RALI | [Reasoning as Representation: Rethinking Visual Reinforcement Learning in Image Quality Assessment](https://arxiv.org/abs/2510.11369) | Alignment-Based | × |
| DepictQA | [Depicting beyond scores: Advancing image quality assessment through multi-modal language models](https://arxiv.org/abs/2312.08962) | Reasoning-Based | × |
| DepictQA-Wild | [Descriptive image quality assessment in the wild](https://arxiv.org/abs/2405.18842) | Reasoning-Based | × |
| IQAGPT | [IQAGPT: computed tomography image quality assessment with vision-language and ChatGPT models](https://vciba.springeropen.com/articles/10.1186/s42492-024-00171-w) | Reasoning-Based | × |
| Co-Instruct | [Towards open-ended visual quality comparison](https://arxiv.org/abs/2402.16641) | Reasoning-Based | × |
| Q-Ground | [Q-Ground: Image quality grounding with large multi-modality models](https://arxiv.org/abs/2407.17035) | Reasoning-Based | × |
| SEAGULL | [Seagull: No-reference image quality assessment for regions of interest via vision-language instruction tuning](https://arxiv.org/abs/2411.10161) | Reasoning-Based | × |
| AgenticIQA | [Agenticiqa: An agentic framework for adaptive and interpretable image quality assessment](https://arxiv.org/abs/2509.26006) | Reasoning-Based | × |
| Q-Align | [Q-align: Teaching lmms for visual scoring via discrete text-defined levels](https://arxiv.org/abs/2312.17090) | Scoring-Based | × |
| DeQA-Score | [Teaching large language models to regress accurate image quality scores using score distribution](https://arxiv.org/abs/2501.11561) | Scoring-Based | × |
| Dog-IQA | [Dog-IQA: Standard-guided Zero-shot MLLM for Mix-grained Image Quality Assessment](https://arxiv.org/abs/2410.02505) | Scoring-Based | × |
| QScorer | [Revisiting MLLM Based Image Quality Assessment: Errors and Remedy](https://arxiv.org/abs/2511.07812) | Scoring-Based | × |
| Compare2Score | [Adaptive image quality assessment via teaching large multimodal model to compare](https://arxiv.org/abs/2405.19298) | Scoring-Based | × |
| Q-Insight | [Q-insight: Understanding image quality via visual reinforcement learning](https://arxiv.org/abs/2503.22679) | Scoring-Based | × |
| QPonder | [Q-ponder: A unified training pipeline for reasoning-based visual quality assessment](https://arxiv.org/abs/2506.05384) | Scoring-Based | × |
| Q-Hawkeye | [Q-Hawkeye: Reliable Visual Policy Optimization for Image Quality Assessment](https://arxiv.org/abs/2601.22920) | Scoring-Based | × |
| LEAF | [Decoupling Perception and Calibration: Label-Efficient Image Quality Assessment Framework](https://arxiv.org/abs/2601.20689) | Scoring-Based | × |
| Q-Bench | [Q-bench: A benchmark for general-purpose foundation models on low-level vision](https://arxiv.org/abs/2309.14181) | Benchmark / Instruction Resource | × |
| Q-Bench+ | [Q-Bench + : A Benchmark for Multi-Modal Foundation Models on Low-Level Vision From Single Images to Pairs](https://arxiv.org/pdf/2402.07116) | Benchmark / Instruction Resource | × |
| Q-Instruct | [Q-instruct: Improving low-level visual abilities for multi-modality foundation models](https://arxiv.org/abs/2311.06783) | Benchmark / Instruction Resource | × |


</details>

<details>
<summary><b>Evaluation Protocols</b></summary>
<br>

| Protocol | Paper | Sub-category | GT Required |
|---|---|---|---|
| PLCC | N/A | Human-Aligned | × |
| SRCC | N/A | Human-Aligned | × |
| KRCC | A new measure of rank correlation | Human-Aligned | × |
| Weighted Kappa | Interrater reliability and agreement of subjective judgments | Human-Aligned | × |
| Percent Agreement | N/A | Human-Aligned | × |
| Precision | N/A | Task-Oriented | ✓ |
| Recall | N/A | Task-Oriented | ✓ |
| F1 | N/A | Task-Oriented | ✓ |
| mIoU | N/A | Task-Oriented | ✓ |
| Accuracy | [Depicting beyond scores: Advancing image quality assessment through multi-modal language models](https://arxiv.org/abs/2312.08962) | Task-Oriented | ✓ |
| BLEU-N | [Bleu: a method for automatic evaluation of machine translation](https://research.ibm.com/publications/bleu-a-method-for-automatic-evaluation-of-machine-translation) | Text-Based | ✓ |
| ROUGE-L | [Rouge: A package for automatic evaluation of summaries](https://www.microsoft.com/en-us/research/publication/rouge-a-package-for-automatic-evaluation-of-summaries/) | Text-Based | ✓ |
| METEOR | [METEOR: An automatic metric for MT evaluation with improved correlation with human judgments](https://aclanthology.org/W05-0909.pdf) | Text-Based | ✓ |
| CIDEr | [Cider: Consensus-based image description evaluation](https://arxiv.org/abs/1411.5726) | Text-Based | ✓ |


</details>


## 📊 Dataset

<details>
<summary><b>Denoising</b></summary>
<br>

| Method | Venue | Task | Domain |
|---|---|---|---|
| [Paper 1](https://arxiv.org/) | CVPR 2024 | Dehazing | Natural |
| [Paper 2](https://arxiv.org/) | ECCV 2024 | Dehazing | Natural |
| [Paper 3](https://arxiv.org/) | AAAI 2025 | Dehazing | Medical |
</details>

<details>
<summary><b>Deraining</b></summary>
</details>

<details>
<summary><b>Dehazing</b></summary>
</details>

<details>
<summary><b>Desnowing</b></summary>
</details>

<details>
<summary><b>Deblurring</b></summary>
</details>

<details>
<summary><b>Low-Light Image Enhancement</b></summary>
</details>

<details>
<summary><b>Super-Resolution</b></summary>
</details>

<details>
<summary><b>Underwater Image Enhacenmebt</b></summary>
</details>

<details>
<summary><b>All-in-One</b></summary>
</details>


## 🤝 &nbsp; Citation

Please visit [Language-Driven Image Restoration and Semantic-Aware Quality Assessment: A Survey](https://www.preprints.org/manuscript/202603.2366) for more details and comprehensive information. If you find our paper and repo helpful, please consider citing it as follows:

```BibTex
@article{liu2026language,
  title={Language-Driven Image Restoration and Semantic-Aware Quality Assessment: A Survey},
  author={Liu, Mingyu and Shu, Haozhan and Cui, Yuning and Zhou, Xingcheng and Cao, Hu and Ren, Wenqi and Shi, Boxin and Knoll, Alois C},
  year={2026},
  publisher={Preprints}
}
```


## 🙏 Acknowledgement

This repository is built as part of our survey project on language-driven image restoration and image quality assessment.

We sincerely thank the research community for its valuable contributions to the following areas:

- image restoration and related datasets
- multimodal learning
- foundation models
- image quality assessment


## License

This repository is released under the [Apache 2.0 license](https://github.com/MingyuLiu1/Language-Driven-IR-and-IQA/blob/main/LICENSE).

