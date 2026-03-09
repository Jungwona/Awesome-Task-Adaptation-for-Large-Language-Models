# Awesome-Task-Adaptation-for-Large-Language-Models

This is the GitHub repository for Task Adaptation for Large Language Models, where we aggregate and organize papers included in our taxonomy. The taxonomy is still being updated, and we welcome recommendations, corrections, or missing references. Please feel free to contact our team at **quoded97@snu.ac.kr**. 

Survey Paper: Under Review

Thank you!

<center>
<img src="./images/survey_overview.png" width="800"/>
</center>

---

# Awesome Papers

## Weight-Based Adaptation

### Single-Task Adaptation

#### LoRA Variants
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**HIRA: Parameter-Efficient Hadamard High-Rank Adaptation**](https://openreview.net/pdf?id=TwJrTz9cRS) | ICLR (Oral) | 2025-01-23 | [GitHub](https://github.com/hqsiswiliam/hira) |
| [**LoRA-GA: Low-Rank Adaptation with Gradient Approximation**](https://arxiv.org/pdf/2407.05000) | NeurIPS | 2024-07-06 | [GitHub](https://github.com/Outsider565/LoRA-GA) |
| [**Mixture-of-Subspaces in Low-Rank Adaptation**](https://arxiv.org/pdf/2406.11909) | EMNLP (Oral) | 2024-06-16 | [GitHub](https://github.com/wutaiqiang/MoSLoRA) |
| [**LoRA-XS: Low-Rank Adaptation with Extremely Small Number of Parameters**](https://arxiv.org/pdf/2405.17604) | arXiv | 2024-05-27 | [GitHub](https://github.com/mohammadrezabanaei/lora-xs) |
| [**VB-LoRA: Extreme Parameter Efficient Fine-Tuning with Vector Banks**](https://arxiv.org/pdf/2405.15179) | NeurIPS | 2024-05-24 | [GitHub](https://github.com/leo-yangli/vb-lora) |
| [**MoRA: High-Rank Updating for Parameter-Efficient Fine-Tuning**](https://arxiv.org/pdf/2405.12130) | arXiv | 2024-05-20 | [GitHub](https://github.com/kongds/MoRA) |
| [**PiSSA: Principal Singular Values and Singular Vectors Adaptation of Large Language Models**](https://arxiv.org/pdf/2404.02948) | NeurIPS | 2024-04-03 | [GitHub](https://github.com/GraphPKU/PiSSA) |
| [**ALoRA: Allocating Low-Rank Adaptation for Fine-tuning Large Language Models**](https://arxiv.org/pdf/2403.16187) | NAACL | 2024-03-24 |  |
| [**DoRA: Weight-Decomposed Low-Rank Adaptation**](https://arxiv.org/pdf/2402.09353) | ICML (Oral) | 2024-02-14 | [GitHub](https://github.com/NVlabs/DoRA) |
| [**LQ-LoRA: Low-rank Plus Quantized Matrix Decomposition for Efficient Language Model Finetuning**](https://arxiv.org/pdf/2311.12023) | ICLR | 2023-11-20 | [GitHub](https://github.com/hanguo97/lq-lora) |
| [**Sparse Low-rank Adaptation of Pre-trained Language Models**](https://arxiv.org/pdf/2311.11696) | EMNLP | 2023-11-20 | [GitHub](https://github.com/tsinghuac3i/sora) |
| [**Tied-Lora: Enhancing parameter efficiency of LoRA with weight tying**](https://arxiv.org/pdf/2311.09578) | NAACL | 2023-11-16 |  |
| [**VeRA: Vector-based Random Matrix Adaptation**](https://arxiv.org/pdf/2310.11454) | ICLR | 2023-10-17 | [GitHub](https://github.com/vera-framework/VERA) |
| [**Navigating Text-To-Image Customization: From LyCORIS Fine-Tuning to Model Evaluation**](https://arxiv.org/pdf/2309.14859) | ICLR | 2023-09-26 | [GitHub](https://github.com/KohakuBlueleaf/LyCORIS) |
| [**QA-LoRA: Quantization-Aware Low-Rank Adaptation of Large Language Models**](https://arxiv.org/pdf/2309.14717) | ICLR | 2023-09-26 | [GitHub](https://github.com/yuhuixu1993/qa-lora) |
| [**QLoRA: Efficient Finetuning of Quantized LLMs**](https://arxiv.org/pdf/2305.14314) | NeurIPS (Oral) | 2023-05-23 | [GitHub](https://github.com/artidoro/qlora) |
| [**AdaLoRA: Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning**](https://arxiv.org/pdf/2303.10512) | ICLR | 2023-03-18 | [GitHub](https://github.com/QingruZhang/AdaLoRA) |
| [**KronA: Parameter Efficient Tuning with Kronecker Adapter**](https://arxiv.org/pdf/2212.10650) | arXiv | 2022-12-20 |  |
| [**DyLoRA: Parameter Efficient Tuning of Pre-trained Models using Dynamic Search-Free Low-Rank Adaptation**](https://arxiv.org/pdf/2210.07558) | EACL | 2022-10-14 | [GitHub](https://github.com/huawei-noah/Efficient-NLP/tree/main/DyLoRA) |
| [**FedPara: Low-Rank Hadamard Product for Communication-Efficient Federated Learning + (Paper 'LyCORIS')**](https://arxiv.org/pdf/2108.06098) | ICLR | 2021-08-13 | [GitHub](https://github.com/South-hw/FedPara_ICLR22) |
| [**LoRA: Low-Rank Adaptation of Large Language Models**](https://arxiv.org/pdf/2106.09685) | ICLR | 2021-06-17 | [GitHub](https://github.com/microsoft/LoRA) |

#### Other PEFT
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**ADePT: Adaptive Decomposed Prompt Tuning for Parameter-Efficient Fine-tuning**](https://arxiv.org/pdf/2501.03291) | ICLR | 2025-01-06 | [GitHub](https://github.com/HungerPWAY/ADePT) |
| [**PARA: Parameter-Efficient Fine-tuning with Prompt Aware Representation Adjustment**](https://arxiv.org/pdf/2502.01033) | EMNLP | 2024-11-12 |  |
| [**3-in-1: 2D Rotary Adaptation for Efficient Finetuning, Efficient Batching and Composability**](https://arxiv.org/pdf/2409.00119) | NeurIPS | 2024-08-28 |  |
| [**Parameter-Efficient Fine-Tuning with Discrete Fourier Transform**](https://arxiv.org/pdf/2405.03003) | ICML | 2024-05-05 |  |
| [**Advancing Parameter Efficiency in Fine-tuning via Representation Editing**](https://arxiv.org/pdf/2402.15179) | ACL | 2024-02-23 | [GitHub](https://github.com/mlwu22/RED) |
| [**ComPEFT: Compression for Communicating Parameter Efficient Updates via Sparsification and Quantization**](https://arxiv.org/pdf/2311.13171) | TMLR | 2023-11-22 |  |
| [**DePT: Decomposed Prompt Tuning for Parameter-Efficient Fine-tuning**](https://arxiv.org/pdf/2309.05173) | ICLR | 2023-09-11 | [GitHub](https://github.com/ShiZhengyan/DePT) |
| [**LST: Ladder Side-Tuning for Parameter and Memory Efficient Transfer Learning**](https://arxiv.org/pdf/2206.06522) | NeurIPS | 2022-06-13 | [GitHub](https://github.com/ylsung/Ladder-Side-Tuning) |
| [**Few-Shot Parameter-Efficient Fine-Tuning is Better and Cheaper than In-Context Learning**](https://arxiv.org/pdf/2205.05638) | NeurIPS | 2022-05-11 | [GitHub](https://github.com/r-three/t-few) |
| [**Training Neural Networks with Fixed Sparse Masks**](https://arxiv.org/pdf/2111.09839) | NeurIPS | 2021-11-18 |  |
| [**BitFit: Simple Parameter-efficient Fine-tuning for Transformer-based Masked Language-models**](https://arxiv.org/pdf/2106.10199) | ACL | 2021-06-18 | [GitHub](https://github.com/benzakenelad/BitFit) |
| [**Compacter: Efficient Low-Rank Hypercomplex Adapter Layers**](https://arxiv.org/pdf/2106.04647) | NeurIPS | 2021-06-08 | [GitHub](https://github.com/rabeehk/compacter) |
| [**Intrinsic Dimensionality Explains the Effectiveness of Language Model Fine-Tuning**](https://arxiv.org/pdf/2012.13255) | ACL | 2020-12-22 | [GitHub](https://github.com/rojagtap/intrinsic-dimension-lm-fine-tuning) |
| [**Parameter-Efficient Transfer Learning for NLP**](https://arxiv.org/pdf/1902.00751) | ICML | 2019-02-02 |  |

### Multi-Task Adaptation

#### Multi-Task PEFT
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**R-LoRA: Randomized Multi-Head LoRA for Efficient Multi-Task Learning**](https://arxiv.org/pdf/2502.15455) | EMNLP Findings | 2025-02-21 |  |
| [**Efficient Multi-task LLM Quantization and Serving for Multiple LoRA Adapters**](https://openreview.net/pdf?id=HfpV6u0kbX) | NeurIPS | 2024-09-26 |  |
| [**Sparse High Rank Adapters**](https://arxiv.org/pdf/2406.13175) | NeurIPS | 2024-06-19 | [GitHub](https://huggingface.co/docs/peft/en/package_reference/shira) |
| [**MeteoRA: Multiple-tasks Embedded LoRA for Large Language Models**](https://arxiv.org/pdf/2405.13053) | ICLR | 2024-05-19 |  |
| [**HydraLoRA: An Asymmetric LoRA Architecture for Efficient Fine-Tuning**](https://arxiv.org/abs/2404.19245) | NeurIPS (Oral) | 2024-04-30 | [GitHub](https://github.com/Clin0212/HydraLoRA) |
| [**MTLoRA: A Low-Rank Adaptation Approach for Efficient Multi-Task Learning**](https://arxiv.org/pdf/2403.20320) | CVPR | 2024-03-29 | [GitHub](https://github.com/scale-lab/MTLoRA) |
| [**Mixture-of-LoRAs: An Efficient Multitask Tuning for Large Language Models**](https://arxiv.org/pdf/2403.03432) | COLING | 2024-03-06 |  |
| [**Batched Low-Rank Adaptation of Foundation Models**](https://arxiv.org/pdf/2312.05677) | ICLR (Oral) | 2023-12-09 |  |
| [**Customizable Combination of Parameter-Efficient Modules for Multi-Task Learning**](https://arxiv.org/pdf/2312.03248) | ICLR | 2023-12-06 |  |
| [**MultiLoRA: Democratizing LoRA for Better Multi-Task Learning**](https://arxiv.org/pdf/2311.11501) | arXiv | 2023-11-20 |  |
| [**Orthogonal Subspace Learning for Language Model Continual Learning**](https://arxiv.org/pdf/2310.14152) | EMNLP Findings | 2023-10-22 | [GitHub](https://github.com/cmnfriend/O-LoRA) |
| [**LoraHub: Efficient Cross-Task Generalization via Dynamic LoRA Composition**](https://arxiv.org/pdf/2307.13269) | COLM | 2023-07-25 |  |
| [**AdapterFusion: Non-Destructive Task Composition for Transfer Learning**](https://arxiv.org/pdf/2005.00247) | EACL | 2020-05-01 |  |

#### Model Merging
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Activation-Guided Consensus Merging for Large Language Models**](https://arxiv.org/pdf/2505.14009) | NeurIPS | 2025-05-20 | [GitHub](https://github.com/hahahawu/Long-to-Short-via-Model-Merging/blob/main/README.md) |
| [**Dynamic Fisher-weighted Model Merging via Bayesian Optimization**](https://arxiv.org/pdf/2504.18992) | NAACL | 2025-04-26 | [GitHub](https://github.com/sanwooo/df-merge) |
| [**Efficient Model Editing with Task-Localized Sparse Fine-tuning**](https://arxiv.org/abs/2504.02620) | ICLR | 2025-04-03 | [GitHub](https://github.com/iurada/talos-task-arithmetic) |
| [**Scalable Model Merging with Progressive Layer-wise Distillation**](https://arxiv.org/pdf/2502.12706) | ICML | 2025-02-18 | [GitHub](https://github.com/JingXuTHU/Scalable_Model_Merging_with_Progressive_Layerwise_Distillation) |
| [**Activation-Informed Merging of Large Language Models**](https://arxiv.org/pdf/2502.02421) | NeurIPS | 2025-02-04 | [GitHub](https://github.com/ahnobari/ActivationInformedMerging) |
| [**Task Singular Vectors: Reducing Task Interference in Model Merging**](https://arxiv.org/pdf/2412.00081) | CVPR | 2024-11-26 |  |
| [**Merging LoRAs like Playing LEGO: Pushing the Modularity of LoRA to Extremes Through Rank-Wise Clustering**](https://arxiv.org/pdf/2409.16167) | ICLR | 2024-09-24 |  |
| [**MetaGPT: Merging Large Language Models Using Model Exclusive Task Arithmetic**](https://arxiv.org/pdf/2406.11385) | EMNLP | 2024-06-17 |  |
| [**Language Models are Super Mario: Absorbing Abilities from Homologous Models as a Free Lunch**](https://arxiv.org/pdf/2311.03099) | ICML | 2023-11-06 | [GitHub](https://github.com/yule-BUAA/MergeLM) |
| [**Parameter Efficient Multi-task Model Fusion with Partial Linearization**](https://arxiv.org/pdf/2310.04742) | ICLR | 2023-10-07 |  |
| [**AdaMerging: Adaptive Model Merging for Multi-Task Learning**](https://arxiv.org/pdf/2310.02575) | ICLR | 2023-10-04 | [GitHub](https://github.com/EnnengYang/AdaMerging) |
| [**Composing Parameter-Efficient Modules with Arithmetic Operations**](https://arxiv.org/pdf/2306.14870) | NeurIPS | 2023-06-26 |  |
| [**TIES-Merging: Resolving Interference When Merging Models**](https://arxiv.org/pdf/2306.01708) | NeurIPS | 2023-06-02 | [GitHub](https://github.com/prateeky2806/ties-merging) |
| [**Task Arithmetic in the Tangent Space: Improved Editing of Pre-Trained Models**](https://arxiv.org/pdf/2305.12827) | NeurIPS | 2023-05-22 |  |
| [**Editing Models with Task Arithmetic**](https://arxiv.org/abs/2212.04089) | ICLR | 2022-12-08 | [GitHub](https://github.com/mlfoundations/task_vectors) |
| [**Model Soups: Averaging Weights of Multiple Fine-Tuned Models Improves Accuracy Without Increasing Inference Time**](https://arxiv.org/pdf/2203.05482) | ICML | 2022-03-10 | [GitHub](https://github.com/mlfoundations/model-soups) |
| [**Merging Models with Fisher-Weighted Averaging**](https://arxiv.org/pdf/2111.09832) | NeurIPS | 2021-11-18 | [GitHub](https://github.com/mmatena/model_merging) |


## Prompt-Based Adaptation

### Instruction Optimization

#### Direct Optimization
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Local Prompt Optimization**](https://arxiv.org/abs/2504.20355) | NAACL (Oral) | 2025-04-29 |  |
| [**GReaTer: Gradients over Reasoning Makes Smaller Language Models Strong Prompt Optimizers**](https://arxiv.org/pdf/2412.09722) | ICLR | 2024-12-12 |  |
| [**Efficient and Accurate Prompt Optimization: the Benefit of Memory in Exemplar-Guided Reflection**](https://arxiv.org/pdf/2411.07446) | ACL | 2024-11-12 |  |
| [**Task Facet Learning: A Structured Approach To Prompt Optimization**](https://arxiv.org/pdf/2406.10504) | ACL Findings | 2024-06-15 |  |
| [**PromptWizard: Task-Aware Prompt Optimization Framework**](https://arxiv.org/pdf/2405.18369) | ACL Findings | 2024-05-28 | [GitHub](https://github.com/microsoft/PromptWizard) |
| [**Localized Zeroth-Order Prompt Optimization**](https://arxiv.org/abs/2403.02993) | NeurIPS | 2024-03-05 | [GitHub](https://github.com/allen4747/ZOPO) |
| [**Unleashing the Potential of Large Language Models as Prompt Optimizers: Analogical Analysis with Gradient-based Model Optimizers**](https://arxiv.org/pdf/2402.17564) | AAAI | 2024-02-27 | [GitHub](https://github.com/RUCAIBox/GPO) |
| [**In-Context Principle Learning from Mistakes**](https://arxiv.org/pdf/2402.05403) | arXiv | 2024-02-08 |  |
| [**Self-Discover: Large Language Models Self-Compose Reasoning Structures**](https://arxiv.org/pdf/2402.03620) | NeurIPS | 2024-02-06 | [GitHub](https://github.com/catid/self-discover) |
| [**Prompt Optimization via Adversarial In-Context Learning**](https://arxiv.org/pdf/2312.02614) | ACL | 2023-12-05 | [GitHub](https://github.com/zhaoyiran924/Adv-In-Context-Learning) |
| [**Prompt Engineering a Prompt Engineer**](https://arxiv.org/pdf/2311.05661) | ACL Findings | 2023-11-09 | [GitHub](https://github.com/INK-USC/PE2) |
| [**PromptAgent: Strategic Planning with Language Models Enables Expert-level Prompt Optimization**](https://arxiv.org/pdf/2310.16427) | ICLR | 2023-10-25 | [GitHub](https://github.com/XinyuanWangCS/PromptAgent) |
| [**Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution**](https://arxiv.org/pdf/2309.16797) | ICML | 2023-09-28 | [GitHub](https://github.com/vaughanlove/PromptBreeder) |
| [**EvoPrompt: Connecting LLMs with Evolutionary Algorithms Yields Powerful Prompt Optimizers**](https://arxiv.org/pdf/2309.08532) | ICLR | 2023-09-15 | [GitHub](https://github.com/beeevita/EvoPrompt) |
| [**Large Language Models as Optimizers**](https://arxiv.org/pdf/2309.03409) | ICLR | 2023-09-07 | [GitHub](https://github.com/google-deepmind/opro) |
| [**Automatic Prompt Optimization with "Gradient Descent" and Beam Search**](https://arxiv.org/pdf/2305.03495) | EMNLP | 2023-05-04 | [GitHub](https://github.com/microsoft/LMOps) |
| [**Large Language Models Are Human-Level Prompt Engineers**](https://arxiv.org/pdf/2211.01910) | ICLR | 2022-11-03 | [GitHub](https://github.com/keirp/automatic_prompt_engineer) |

#### Indirect Optimization
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**How to Auto-optimize Prompts for Domain Tasks? Adaptive Prompting and Reasoning through Evolutionary Domain Knowledge Adaptation**](https://arxiv.org/pdf/2510.21148) | NeurIPS | 2025-10-24 | [GitHub](https://github.com/miemieyanga/EGO-Prompt) |
| [**StablePrompt: Automatic Prompt Tuning using Reinforcement Learning for Large Language Models**](https://aclanthology.org/2024.emnlp-main.551.pdf) | EMNLP | 2024-10-10 | [GitHub](https://github.com/kmc0207/Stableprompt) |
| [**Use Your INSTINCT: INSTruction optimization for LLMs usIng Neural bandits Coupled with Transformers**](https://arxiv.org/pdf/2310.02905) | ICML | 2023-10-02 | [GitHub](https://github.com/xqlin98/INSTINCT) |
| [**InstructZero: Efficient Instruction Optimization for Black-Box Large Language Models**](https://arxiv.org/pdf/2306.03082) | ICML | 2023-06-05 | [GitHub](https://github.com/Lichang-Chen/InstructZero) |

### Demonstration Optimization

#### Unordered Demonstration Selection
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Linear-Time Demonstration Selection for In-Context Learning via Gradient Estimation**](https://arxiv.org/pdf/2508.19999) | EMNLP | 2025-08-27 | [GitHub](https://github.com/VirtuosoResearch/ICL-GradSel) |
| [**Sample Efficient Demonstration Selection for In-Context Learning**](https://arxiv.org/abs/2506.08607) | ICML | 2025-06-10 | [GitHub](https://github.com/kiranpurohit/CASE) |
| [**Selecting Demonstrations for Many-Shot In-Context Learning via Gradient Matching**](https://www.arxiv.org/pdf/2506.04579) | ACL Findings | 2025-06-05 |  |
| [**Learning to Select In-Context Demonstration Preferred by Large Language Model**](https://arxiv.org/pdf/2505.19966) | ACL Findings | 2025-05-26 | [GitHub](https://github.com/zheng-z18/GenICL_preferred) |
| [**Revisiting Demonstration Selection Strategies in In-Context Learning**](https://arxiv.org/pdf/2401.12087) | ACL | 2024-01-22 | [GitHub](https://github.com/Romainpkq/revisit_demon_selection_in_ICL) |
| [**Representative Demonstration Selection for In-Context Learning with Two-Stage Determinantal Point Process**](https://aclanthology.org/2023.emnlp-main.331.pdf) | EMNLP | 2023-12-06 |  |
| [**In-Context Learning with Iterative Demonstration Selection**](https://arxiv.org/pdf/2310.09881) | EMNLP Findings | 2023-10-15 |  |
| [**Unified Demonstration Retriever for In-Context Learning**](https://arxiv.org/pdf/2305.04320) | ACL | 2023-05-07 | [GitHub](https://github.com/KaiLv69/UDR) |
| [**UPRISE: Universal Prompt Retrieval for Improving Zero-Shot Evaluation**](https://arxiv.org/pdf/2303.08518) | EMNLP | 2023-03-15 | [GitHub](https://github.com/microsoft/LMOps) |
| [**In-context Example Selection with Influences**](https://arxiv.org/pdf/2302.11042) | arXiv | 2023-02-21 | [GitHub](https://github.com/BrachioLab/incontext_influences) |
| [**Compositional Exemplars for In-context Learning**](https://arxiv.org/pdf/2302.05698) | ICML | 2023-02-11 | [GitHub](https://github.com/HKUNLP/icl-ceil) |
| [**Large Language Models Are Latent Variable Models: Explaining and Finding Good Demonstrations for In-Context Learning**](https://arxiv.org/pdf/2301.11916) | NeurIPS | 2023-01-27 | [GitHub](https://github.com/WANGXinyiLinda/concept-based-demonstration-selection) |
| [**Complexity-Based Prompting for Multi-Step Reasoning**](https://arxiv.org/pdf/2210.00720) | ICLR | 2022-10-03 | [GitHub](https://github.com/FranxYao/chain-of-thought-hub) |
| [**Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning**](https://arxiv.org/pdf/2209.14610) | ICLR | 2022-09-29 | [GitHub](https://github.com/lupantech/PromptPG) |
| [**Learning To Retrieve Prompts for In-Context Learning**](https://arxiv.org/pdf/2112.08633) | NAACL | 2021-12-16 | [GitHub](https://github.com/OhadRubin/EPR) |
| [**What Makes Good In-Context Examples for GPT-3?**](https://arxiv.org/pdf/2101.06804) | arXiv | 2021-01-17 |  |


#### Ordered Demonstration Selection
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Demonstration Selection for In-Context Learning via Reinforcement Learning**](https://arxiv.org/pdf/2412.03966) | ICML | 2024-12-05 |  |
| [**What Makes a Good Order of Examples in In-Context Learning**](https://aclanthology.org/2024.findings-acl.884.pdf) | ACL Findings | 2024-08-11 |  |
| [**Prompt Optimization with EASE? Efficient Ordering-aware Automated Selection of Exemplars**](https://arxiv.org/pdf/2405.16122) | NeurIPS | 2024-05-25 | [GitHub](https://github.com/ZhaoxuanWu/EASE-Prompt-Optimization) |
| [**Se²: Sequential Example Selection for In-Context Learning**](https://arxiv.org/pdf/2402.13874) | ACL Findings | 2024-02-21 |  |
| [**Let's Learn Step by Step: Enhancing In-Context Learning Ability with Curriculum Learning**](https://arxiv.org/pdf/2402.10738) | arXiv | 2024-02-16 |  |
| [**RetICL: Sequential Retrieval of In-Context Examples with Reinforcement Learning**](https://arxiv.org/pdf/2305.14502) | arXiv | 2023-05-23 | [GitHub](https://github.com/umass-ml4ed/RetICL) |
| [**Self-Adaptive In-Context Learning: An Information Compression Perspective for In-Context Example Selection and Ordering**](https://arxiv.org/pdf/2212.10375) | ACL | 2022-12-20 | [GitHub](https://github.com/Shark-NLP/self-adaptive-ICL) |
| [**Active Example Selection for In-Context Learning**](https://arxiv.org/pdf/2211.04486) | EMNLP | 2022-11-08 | [GitHub](https://github.com/ChicagoHAI/active-example-selection) |
| [**Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot Prompt Order Sensitivity**](https://arxiv.org/pdf/2104.08786) | ACL | 2021-04-18 | [GitHub](https://github.com/yaolu/ordered-prompt) |


#### Selective Demonstration Annotation
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Which Examples to Annotate for In-Context Learning? Towards Effective and Efficient Selection**](https://arxiv.org/pdf/2310.20046) | arXiv | 2023-10-30 |  |
| [**IDEAL: Influence-Driven Selective Annotations Empower In-Context Learners in Large Language Models**](https://arxiv.org/pdf/2310.10873) | ICLR | 2023-10-16 | [GitHub](https://github.com/skzhang1/IDEAL) |
| [**Selective Annotation Makes Language Models Better Few-Shot Learners**](https://arxiv.org/pdf/2209.01975) | ICLR | 2022-09-05 | [GitHub](https://github.com/xlang-ai/icl-selective-annotation) |


#### Demonstration Generation
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Exploring Explanations Improves the Robustness of In-Context Learning**](https://arxiv.org/pdf/2506.02378) | ACL | 2025-06-03 | [GitHub](https://github.com/CyberAgentAILab/x2-icl) |
| [**From Few to Many: Self-Improving Many-Shot Reasoners Through Iterative Optimization and Generation**](https://arxiv.org/pdf/2502.00330) | ICLR | 2025-02-01 |  |
| [**Demonstration Augmentation for Zero-shot In-context Learning**](https://arxiv.org/pdf/2406.01224) | ACL Findings | 2024-06-03 |  |
| [**Using Natural Language Explanations to Improve Robustness of In-context Learning**](https://arxiv.org/pdf/2311.07556) | ACL | 2023-11-13 | [GitHub](https://github.com/xlhex/acl2024_xicl) |
| [**Self-ICL: Zero-Shot In-Context Learning with Self-Generated Demonstrations**](https://arxiv.org/pdf/2305.15035) | EMNLP | 2023-05-24 | [GitHub](https://github.com/ntunlplab/Self-ICL) |
| [**Synthetic Prompting: Generating Chain-of-Thought Demonstrations for Large Language Models**](https://arxiv.org/pdf/2302.00618) | ICML | 2023-02-01 |  |

#### Many-Shot ICL
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Focused Large Language Models are Stable Many-Shot Learners**](https://arxiv.org/pdf/2408.13987) | EMNLP | 2024-08-26 |  |
| [**In-Context Learning with Long-Context Models: An In-Depth Exploration**](https://arxiv.org/pdf/2405.00200) | NAACL | 2024-04-30 | [GitHub](https://github.com/abertsch72/long-context-icl) |
| [**Many-Shot In-Context Learning**](https://arxiv.org/abs/2404.11018) | NeurIPS | 2024-04-17 |  |
| [**Structured Prompting: Scaling In-Context Learning to 1,000 Examples**](https://arxiv.org/pdf/2212.06713) | arXiv | 2022-12-13 |  |


## Embedding-Based Adaptation

### ICL-Derived Task Embeddings

#### Non-Contrastively Derived
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Soft Injection of Task Embeddings Outperforms Prompt-Based In-Context Learning**](https://arxiv.org/pdf/2507.20906) | arXiv | 2025-07-28 | [GitHub](https://github.com/SNU-DRL/Soft_Injection) |
| [**Beyond Demonstrations: Dynamic Vector Construction from Latent Representations**](https://arxiv.org/pdf/2505.20318) | EMNLP | 2025-05-23 |  |
| [**ELICIT: LLM Augmentation via External In-Context Capability**](https://arxiv.org/pdf/2410.09343) | ICLR | 2024-10-12 | [GitHub](https://github.com/LINs-lab/ELICIT) |
| [**Multimodal Task Vectors Enable Many-Shot Multimodal In-Context Learning**](https://arxiv.org/pdf/2406.15334) | NeurIPS | 2024-06-21 | [GitHub](https://github.com/Brandon3964/MultiModal-Task-Vector) |
| [**Implicit In-Context Learning**](https://arxiv.org/pdf/2405.14660) | ICLR | 2024-05-23 | [GitHub](https://github.com/LzVv123456/I2CL) |
| [**Batch-ICL: Effective, Efficient, and Order-Agnostic In-Context Learning**](https://arxiv.org/pdf/2401.06469) | ACL Findings | 2024-01-12 | [GitHub](https://github.com/Cardinalere/Batch-ICL) |
| [**In-Context Learning Creates Task Vectors**](https://arxiv.org/pdf/2310.15916) | EMNLP Findings | 2023-10-24 | [GitHub](https://github.com/mlfoundations/task_vectors) |
| [**Function Vectors in Large Language Models**](https://arxiv.org/pdf/2310.15213) | ICLR | 2023-10-23 | [GitHub](https://github.com/ericwtodd/function_vectors) |


#### Contrastively Derived
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Prototype-Based Dynamic Steering for Large Language Models**](https://arxiv.org/pdf/2510.05498) | arXiv | 2025-10-07 |  |
| [**Iterative Vectors: In-Context Gradient Steering without Backpropagation**](https://openreview.net/pdf?id=1v3XEcRMyP) | ICML | 2025-07-13 | [GitHub](https://github.com/ArkciaTheDragon/iterative-vectors) |
| [**REAL: Reading Out Transformer Activations for Precise Localization in Language Model Steering**](https://arxiv.org/pdf/2506.08359) | ICLR | 2025-06-10 |  |
| [**Semantics-Adaptive Activation Intervention for LLMs via Dynamic Steering Vectors**](https://arxiv.org/pdf/2410.12299) | ICLR | 2024-10-16 | [GitHub](https://github.com/weixuan-wang123/SADI) |
| [**Adaptive Activation Steering: A Tuning-Free LLM Truthfulness Improvement Method for Diverse Hallucinations Categories**](https://arxiv.org/pdf/2406.00034) | WWW | 2024-05-26 | [GitHub](https://github.com/tianlwang/ACT) |
| [**Spectral Editing of Activations for Large Language Model Alignment**](https://arxiv.org/pdf/2405.09719) | NeurIPS | 2024-05-15 | [GitHub](https://github.com/yfqiu-nlp/sea-llm) |
| [**Steering Llama 2 via Contrastive Activation Addition**](https://arxiv.org/pdf/2312.06681) | ACL | 2023-12-09 | [GitHub](https://github.com/nrimsky/CAA) |
| [**In-context Vectors: Making In Context Learning More Effective and Controllable Through Latent Space Steering**](https://arxiv.org/pdf/2311.06668) | ICML | 2023-11-11 | [GitHub](https://github.com/shengliu66/ICV) |
| [**Inference-time Intervention: Eliciting truthful answers from a language model**](https://arxiv.org/abs/2306.03341) | NeurIPS | 2023-06-06 | [GitHub](https://github.com/likenneth/honest_llama) |


### Learned Task Embeddings

#### Soft Prompting
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Dynamic Task Vector Grouping for Efficient Multi-Task Prompt Tuning**](https://arxiv.org/pdf/2503.18063) | ACL Findings | 2025-03-23 |  |
| [**Task Prompt Vectors: Effective Initialization through Multi-Task Soft-Prompt Transfer**](https://arxiv.org/pdf/2408.01119) | ECML PKDD | 2024-08-02 |  |
| [**Prompt Tuning Strikes Back: Customizing Foundation Models with Low-Rank Prompt Adaptation**](https://arxiv.org/pdf/2405.15282) | NeurIPS | 2024-05-24 | [GitHub](https://github.com/jabhinav/Prompt-Tuning-Strikes-Back-with-LOPA) |
| [**Multitask Prompt Tuning Enables Parameter-Efficient Transfer Learning**](https://arxiv.org/pdf/2303.02861) | ICLR | 2023-03-06 |  |
| [**Progressive Prompts: Continual Learning for Language Models**](https://arxiv.org/pdf/2301.12314) | ICLR | 2023-01-29 |  |
| [**ATTEMPT: Parameter-Efficient Multi-task Tuning via Attentional Mixtures of Soft Prompts**](https://arxiv.org/pdf/2205.11961) | EMNLP | 2022-05-24 |  |
| [**SPoT: Better Frozen Model Adaptation through Soft Prompt Transfer**](https://arxiv.org/pdf/2110.07904) | ACL | 2021-10-15 | [GitHub](https://github.com/google-research/prompt-tuning/tree/main/prompt_tuning/spot) |
| [**P-Tuning v2: Prompt Tuning Can Be Comparable to Fine-tuning Universally Across Scales and Tasks**](https://arxiv.org/pdf/2110.07602) | ACL | 2021-10-14 | [GitHub](https://github.com/THUDM/P-tuning-v2) |
| [**The Power of Scale for Parameter-Efficient Prompt Tuning**](https://arxiv.org/pdf/2104.08691) | EMNLP | 2021-04-18 | [GitHub](https://github.com/mkshing/Prompt-Tuning) |
| [**GPT Understands, Too**](https://arxiv.org/pdf/2103.10385) | AI Open | 2021-03-18 | [GitHub](https://github.com/THUDM/P-tuning) |
| [**Prefix-Tuning: Optimizing Continuous Prompts for Generation**](https://arxiv.org/pdf/2101.00190) | ACL | 2021-01-01 | [GitHub](https://github.com/XiangLi1999/PrefixTuning) |


#### Other Learned Embeddings
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Task Vectors, Learned Not Extracted: Performance Gains and Mechanistic Insight**](https://arxiv.org/pdf/2509.24169) | ICLR | 2025-09-29 |  |
| [**Towards Generalizable Implicit In-Context Learning with Attention Routing**](https://arxiv.org/pdf/2509.22854) | arXiv | 2025-09-26 |  |
| [**Adaptive Task Vectors for Large Language Models**](https://arxiv.org/pdf/2506.03426) | arXiv | 2025-06-03 | [GitHub](https://github.com/MLAI-Yonsei/ATV) |
| [**M²IV: Towards Efficient and Fine-grained Multimodal In-Context Learning via Representation Engineering**](https://arxiv.org/pdf/2504.04633) | COLM | 2025-04-06 |  |
| [**Learning Task Representations from In-Context Learning**](https://arxiv.org/pdf/2502.05390) | ACL Findings | 2025-02-08 | [GitHub](https://github.com/Brandon3964/MultiModal-Task-Vector) |
| [**LIVE: Learnable In-Context Vector for Visual Question Answering**](https://arxiv.org/pdf/2406.13185) | NeurIPS | 2024-06-19 | [GitHub](https://github.com/ma-xu/LIVE) |

---

# Awesome Datasets

## Datasets for Natural Language Understanding
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **GLUE** | [GLUE: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding](https://arxiv.org/pdf/1804.07461) | [Link](https://huggingface.co/datasets/nyu-mll/glue) | Classification | ~1.05M |
| **SuperGLUE** | [SuperGLUE: A Stickier Benchmark for General-Purpose Language Understanding Systems](https://arxiv.org/abs/1905.00537) | [Link](https://super.gluebenchmark.com/) | Classification / Multiple Choice Question | ~184K |
| **SNLI** | [A large annotated corpus for learning natural language inference](https://arxiv.org/abs/1508.05320) | [Link](https://huggingface.co/datasets/stanfordnlp/snli) | Classification | ~570K |
| **ANLI** | [Adversarial NLI: A New Benchmark for Natural Language Inference](https://arxiv.org/abs/1910.14599) | [Link](https://huggingface.co/datasets/facebook/anli) | Classification | ~168K |
| **CoNLL-2003** | [Introduction to the CoNLL-2003 Shared Task: Named Entity Recognition](https://aclanthology.org/W03-0419/) | [Link](https://huggingface.co/datasets/eriktks/conll2003) | Classification | ~22K |
| **SST-5** | [Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank](https://aclanthology.org/D13-1170/) | [Link](https://github.com/stanfordnlp/sentiment-treebank) | Classification | ~12K |
| **WikiQA** | [WikiQA: A Challenge Dataset for Open-Domain Question Answering](https://aclanthology.org/D15-1237/) | [Link](https://huggingface.co/datasets/microsoft/wiki_qa) | Classification | ~3K |
| **TREC** | [Learning Question Classifiers](https://aclanthology.org/C02-1150/) | [Link](https://cogcomp.seas.upenn.edu/Data/QA/QC/) | Classification | ~6K |
| **DBPedia** | [Character-level Convolutional Networks for Text Classification](https://arxiv.org/abs/1509.01626) | [Link](https://www.kaggle.com/datasets/danofer/dbpedia-classes) | Classification | ~630K |
| **Subj** | [Seeing Stars: Exploiting Class Relationships for Sentiment Forecasting](https://arxiv.org/abs/cs/0409058) | [Link](https://huggingface.co/datasets/SetFit/subj) | Classification | ~10K |

## Datasets for Reasoning
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **MMLU** | [Measuring Massive Multitask Language Understanding](https://arxiv.org/abs/2009.03300) | [Link](https://github.com/hendrycks/test) | Multiple Choice Question | ~16K |
| **BBH** | [Challenging BIG-bench Tasks and Whether Chain-of-Thought Can Solve Them](https://arxiv.org/abs/2210.09261) | [Link](https://github.com/suzgunmirac/BIG-Bench-Hard) | Multiple Choice Question / Open-ended generation | ~6.5K |
| **GPQA** | [GPQA: A Graduate-Level Google-Proof Q&A Benchmark](https://arxiv.org/abs/2311.12022) | [Link](https://huggingface.co/datasets/Idavidrein/gpqa) | Multiple Choice Question | ~0.4K |
| **CommonsenseQA** | [CommonsenseQA: A Question Answering Challenge Targeting Commonsense Knowledge](https://arxiv.org/abs/1811.00937) | [Link](https://huggingface.co/datasets/tau/commonsense_qa) | Multiple Choice Question | ~12.1K |
| **ARC** | [Think you have Solved Question Answering? Try ARC, the AI2 Reasoning Challenge](https://arxiv.org/abs/1803.05457) | [Link](https://huggingface.co/datasets/allenai/ai2_arc) | Multiple Choice Question | ~7.8K |
| **HellaSwag** | [HellaSwag: Can a Machine Really Finish Your Sentence?](https://arxiv.org/abs/1905.07830) | [Link](https://huggingface.co/datasets/Rowan/hellaswag) | Multiple Choice Question | ~60K |
| **WinoGrande** | [WinoGrande: An Adversarial Winograd Schema Challenge at Scale](https://arxiv.org/abs/1907.10641) | [Link](https://github.com/allenai/winogrande) | Multiple Choice Question | ~44K |

## Datasets for Mathematics
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **GSM8K** | [Training Verifiers to Solve Math Word Problems](https://arxiv.org/abs/2110.14168) | [Link](https://huggingface.co/datasets/openai/gsm8k) | Open-ended generation | ~8.8K |
| **MATH** | [Measuring Mathematical Problem Solving With the MATH Dataset](https://arxiv.org/abs/2103.03874) | [Link](https://github.com/hendrycks/math) | Open-ended generation | ~12.5K |
| **MATH500** | [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050) | [Link](https://huggingface.co/datasets/HuggingFaceH4/MATH-500) | Open-ended generation | ~0.5K |
| **MetaMathQA** | [MetaMath: Bootstrap Your Own Mathematical Questions for LLMs](https://arxiv.org/abs/2309.12284) | [Link](https://huggingface.co/datasets/meta-math/MetaMathQA) | Open-ended generation | ~395K |
| **AQuA-RAT** | [Program Induction by Rationale Generation: Learning to Solve and Explain Algebraic Word Problems](https://arxiv.org/abs/1705.04148) | [Link](https://github.com/google-deepmind/AQuA) | Multiple Choice Question / Open-ended generation | ~100K |
| **SVAMP** | [Are NLP Models really able to Solve Simple Math Word Problems?](https://arxiv.org/abs/2103.07191) | [Link](https://huggingface.co/datasets/ChilleD/SVAMP) | Open-ended generation | ~1K |
| **TabMWP** | [Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning](https://arxiv.org/abs/2211.14418) | [Link](https://github.com/lupantech/PromptPG?tab=readme-ov-file) | Multiple Choice Question / Open-ended generation | ~38K |


## Datasets for Coding
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **HumanEval** | [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374) | [Link](https://github.com/openai/human-eval) | Open-ended generation | ~0.16K |
| **MBPP** | [Program Synthesis with Large Language Models](https://arxiv.org/abs/2108.07732) | [Link](https://github.com/google-research/google-research/tree/master/mbpp) | Open-ended generation | ~1K |
| **MultiPL-E** | [Multipl-e: A scalable and polyglot approach to benchmarking neural code generation](https://arxiv.org/abs/2208.08227) | [Link](https://github.com/nuprl/MultiPL-E) | Open-ended generation | ~25K |
| **CruxEval** | [CruxEval: A Benchmark for Code Reasoning, Understanding and Execution](https://arxiv.org/abs/2401.03065) | [Link](https://crux-eval.github.io/) | Open-ended generation | ~0.8K |
| **SWE-bench** | [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770) | [Link](https://www.swebench.com/original.html) | Open-ended generation | ~2.3K |


## Datasets for Question Answering
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **SQuAD v1.1** | [SQuAD: 100,000+ Questions for Machine Comprehension of Text](https://arxiv.org/abs/1606.05250) | [Link](https://huggingface.co/datasets/rajpurkar/squad) | Open-ended generation | ~98K |
| **Natural Questions** | [Natural Questions: A Benchmark for Question Answering Research](https://aclanthology.org/Q19-1026/) | [Link](https://github.com/google-research-datasets/natural-questions) | Open-ended generation | ~323K |
| **TriviaQA** | [TriviaQA: A Large Scale Distantly Supervised Challenge Dataset](https://arxiv.org/abs/1705.03551) | [Link](https://huggingface.co/datasets/mandarjoshi/trivia_qa) | Open-ended generation | ~96K |
| **HotpotQA** | [HotpotQA: A Dataset for Diverse, Explainable Multi-hop Question Answering](https://arxiv.org/abs/1809.09600) | [Link](https://huggingface.co/datasets/hotpotqa/hotpot_qa) | Open-ended generation | ~112.8K |

## Datasets for Summarization
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **CNN/DailyMail** | [Teaching Machines to Read and Comprehend](https://arxiv.org/abs/1506.03340) | [Link](https://huggingface.co/datasets/abisee/cnn_dailymail) | Open-ended generation | ~312K |
| **XSum** | [Don’t Give Me the Details, Just the Summary! Topic-Aware Convolutional Neural Networks for Extreme Summarization](https://arxiv.org/abs/1808.08702) | [Link](https://huggingface.co/datasets/EdinburghNLP/xsum) | Open-ended generation | ~227K |
| **SAMSum** | [SAMSum Corpus: A Human-annotated Dialogue Dataset for Summarization](https://arxiv.org/abs/1911.12237) | [Link](https://huggingface.co/datasets/knkarthick/samsum) | Open-ended generation | ~16K |
| **DialogSum** | [DialogSum: A Real-Life Scenario Dialogue Summarization Dataset](https://arxiv.org/abs/2105.06762) | [Link](https://huggingface.co/datasets/knkarthick/dialogsum) | Open-ended generation | ~13.5K |
| **XL-Sum** | [XL-Sum: Large-Scale Multilingual Abstractive Summarization](https://arxiv.org/abs/2106.13822) | [Link](https://github.com/csebuetnlp/xl-sum) | Open-ended generation | ~1.35M |

## Datasets for Structured Data-to-Text
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **E2E NLG** | [The E2E Dataset: Fresh Challenges for End-to-End Generation Systems](https://arxiv.org/abs/1706.09255) | [Link](https://github.com/tuetschek/e2e-dataset) | Open-ended generation | ~51K |
| **WebNLG** | [The WebNLG Challenge: Generating Text from RDF Data](https://aclanthology.org/W17-3518/) | [Link](https://synalp.gitlabpages.inria.fr/webnlg-challenge/) | Open-ended generation | ~25.3K |
| **ToTTo** | [ToTTo: A Controlled Table-to-Text Generation Dataset](https://arxiv.org/abs/2004.14373) | [Link](https://github.com/google-research-datasets/ToTTo) | Open-ended generation | ~136K |

## Datasets for Safety and Trustworthiness
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **TruthfulQA** | [TruthfulQA: Measuring How Models Mimic Human Falsehoods](https://arxiv.org/abs/2109.07958) | [Link](https://github.com/sylinrl/TruthfulQA) | Multiple Choice Question / Open-ended generation | ~0.8K |
| **ToxiGen** | [ToxiGen: A Large-Scale Machine-Generated Dataset for Implicit Hate Speech](https://arxiv.org/abs/2203.09509) | [Link](https://huggingface.co/datasets/toxigen/toxigen-data) | Classification | ~274K |
| **HaluEval** | [HaluEval: A Large-Scale Hallucination Evaluation Benchmark](https://arxiv.org/abs/2305.11747) | [Link](https://github.com/RUCAIBox/HaluEval) | Classification | ~35K |
| **RealToxicityPrompts** | [RealToxicityPrompts: Evaluating Neural Language Models for Toxicity](https://arxiv.org/abs/2009.11462) | [Link](https://huggingface.co/datasets/allenai/real-toxicity-prompts) | Open-ended generation | ~100K |
| **ParaDetox** | [ParaDetox: Detoxification with Parallel Data](https://arxiv.org/abs/2205.13605) | [Link](https://github.com/s-nlp/paradetox?tab=readme-ov-file) | Open-ended generation | ~19.8K |
| **CrowS-Pairs** | [CrowS-Pairs: A Challenge Dataset for Measuring Social Biases](https://arxiv.org/abs/2010.00133) | [Link](https://github.com/nyu-mll/crows-pairs) | Multiple Choice Question | ~1.5K |
| **ETHOS** | [ETHOS: an Online Hate Speech Detection Dataset](https://arxiv.org/abs/2006.08328) | [Link](https://huggingface.co/datasets/iamollas/ethos) | Classification | ~1K |
| **HateSpeech18** | [Hate Speech Dataset from a White Supremacist Forum](https://aclanthology.org/W18-5102/) | [Link](https://github.com/Vicomtech/hate-speech-dataset) | Classification | ~11K |
| **Do-Not-Answer** | [Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs](https://arxiv.org/abs/2311.04017) | [Link](https://huggingface.co/datasets/LibrAI/do-not-answer) | Open-ended generation | ~0.9K |

## Datasets for General ICL Capabilities
|   Name  |   Paper   |   Link   |   Output Type   |   Size   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **ICL-50** | [More is not always better? Enhancing Many-Shot In-Context Learning with Differentiated and Reweighting Objectives](https://arxiv.org/abs/2501.04070) | [Link](https://github.com/xiaoqzhwhu/DrICL) | Multiple Choice Question / Open-ended generation | ~3M+ |
| **FV-Benchmark** | [Function Vectors in Large Language Models](https://arxiv.org/abs/2310.15213) | [Link](https://github.com/ericwtodd/function_vectors) | Multiple Choice Question / Open-ended generation | ~9.3K |