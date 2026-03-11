---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hieu Phan is a research scientist at Google Research (Sydney) with a track record of from fundamental research on multimodal intelligence into production-ready systems. He specializes in **multimodal LLMs**, **vision-language grounding**, **knowledge distillation**, and **continual learning**. Hieu holds a PhD from the University of Wollongong. He completed his postdoctoral research fellow at the Australian Institute for Machine Learning (AIML) at Adelaide University, advised by A/Prof Johan Verjans and Prof. Anton van de Hengel.

<p class="cta"><a href="/files/atlas-hieu-phan-cv.pdf" target="_blank" rel="noopener">Download CV</a></p>

## Research Statement

Humans perceive the visual world as symbols, reasoning and imagining. My work focuses on linking visual perceptions to concepts so that machines can understand, and reason the visual world.

## 🔥 News
- **2026.03:** CVPR 2026 accepted two papers on LVLM hallucination detection and confounder tracing.
- **2025.10:** CVPR 2025 accepted two papers (Interactive Medical Image Analysis with Concept-based Similarity Reasoning; Looking in the Mirror).
- **2025.09:** <img src="images/g-logo.jpg" alt="Google logo" class="inline-logo"> Joined Google Research Sydney as a Vision-Language Modeling Research Scientist.
- **2025.08:** ICCV 2025 accepted two papers, including an ICCV Highlight for weakly supervised medical grounding and OVG-HQ for hybrid-modal video grounding.
- **2024.11:** CVPR 2024 accepted the multi-aspect pathology description framework.
- **2023.08:** IJCV published SegViTv2 for efficient continual segmentation.
- **2022.06:** CVPR 2022 accepted the class similarity weighted knowledge distillation method.
- **2020.12:** ACL 2020 accepted the LCFS-BERT framework for aspect-based sentiment analysis.

## 📝 Selected Publications
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src="images/cvpr'26_overview.pdf" alt='Beyond the Global Scores overview' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Beyond the Global Scores: Fine-Grained Token Grounding as a Robust Detector of LVLM Hallucinations**

Token-level grounding metrics detect hallucinations with high sensitivity and flag spurious generations before they leave the model stack.

<p class="impact">Impact: Sets a benchmark for LVLM hallucination detection and keeps grounded tokens distinguishable from noise.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2026 Findings</div><img src="images/cvpr'26_hallu_method.pdf" alt='Overthinking Causes Hallucination' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Overthinking Causes Hallucination: Tracing Confounder Propagation in Vision Language Models**

Analyzes confounder paths inside LVLM decoders and surfaces the layers where grounding diverges from actual context.

<p class="impact">Impact: Provides a debugging lens on LVLM hallucinations, enabling teams to intervene at the right layers.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge badge--highlight">ICCV 2025 Highlight</div><img src="images/iccv'25_prompt_feature_huy.pdf" alt='Seeing the Trees for the Forest' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Seeing the Trees for the Forest: Rethinking Weakly-Supervised Medical Visual Grounding**

Highlights prompt-feature pairings to reconcile coarse annotations with fine-grained localization in medical imaging.

<p class="impact">Impact: Chosen as an ICCV 2025 Highlight for pushing interpretability in weak supervision.</p>
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Huy_Seeing_the_Trees_for_the_Forest_Rethinking_Weakly-Supervised_Medical_Visual_ICCV_2025_paper.pdf" target="_blank" rel="noopener">Paper</a> · <span class="publication-links__na">Code: pending</span></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src="images/iccv'25-ovg-hq.png" alt='OVG-HQ' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**OVG-HQ: Online Video Grounding with Hybrid-modal Queries**

OVG-HQ-Unify leverages a Parametric Memory Block and cross-modal distillation to keep previous knowledge while strengthening weaker modalities in limited-context online settings.

<p class="impact">Impact: Empowers a single model to handle hybrid-modal queries despite modality imbalance.</p>
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Zeng_OVG-HQ_Online_Video_Grounding_with_Hybrid-modal_Queries_ICCV_2025_paper.pdf" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/maojiaqi2324/OVG-HQ" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src="images/ijcai'25_main_fig_loba.pdf" alt='Localizing Before Answering' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Localizing Before Answering: A Benchmark for Grounded Medical Visual Question Answering**

The Localize-before-Answer (LobA) framework trains LMMs to spot regions of interest and self-prompt on segmented pathological areas before producing answers.

<p class="impact">Impact: Boosts visual reasoning by forcing grounding first, then generating reliable answers.</p>
<p class="publication-links"><a href="https://www.ijcai.org/proceedings/2025/853" target="_blank" rel="noopener">Paper</a> · <span class="publication-links__na">Code: pending</span></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src="images/cvpr'24-method.pdf" alt='Decomposing disease descriptions' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Decomposing Disease Descriptions for Enhanced Pathology Detection: A Multi-Aspect Vision-Language Pre-training Framework**

Dissects biomedical texts into aspect-centric representations via LLMs and medical experts, then aligns each aspect with image cues through a dual-head Transformer.

<p class="impact">Impact: Aligns images with disease representations by matching diverse aspects, yielding stronger compatibility scores for known and unknown pathologies.</p>
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Phan_Decomposing_Disease_Descriptions_for_Enhanced_Pathology_Detection_A_Multi-Aspect_Vision-Language_CVPR_2024_paper.pdf" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/hieuvmphan/CVPR2024_MAVL" target="_blank" rel="noopener">Code</a></p>
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">IJCV 2023</div><img src="images/ijcv'25.png" alt='SegViTv2' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**SegViTv2: Exploring Efficient and Continual Semantic Segmentation with Plain Vision Transformers**

SegViTv2 couples an Attention-to-Mask decoder with a Shrunk++ encoder so ViT attention maps become lightweight semantic masks, enabling efficient segmentation with near-zero forgetting.

<p class="impact">Impact: Converts ViT attentions into high-quality masks while trimming encoder cost, and maintains prior knowledge when adapted to continual segmentation.</p>
<p class="publication-links"><a href="https://link.springer.com/article/10.1007/s11263-023-01894-8" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/zbwxp/SegVit" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src="images/REMINDER.png" alt='Class similarity weighted knowledge distillation' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Class similarity weighted knowledge distillation for continual semantic segmentation**

Weights the distillation loss by class similarity to preserve fine-grained structure during incremental learning, reducing forgetting on long-tail categories.

<p class="impact">Impact: Serves as a reference for class-aware distillation in continual segmentation.</p>
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Phan_Class_Similarity_Weighted_Knowledge_Distillation_for_Continual_Semantic_Segmentation_CVPR_2022_paper.pdf" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/hieuvmphan/REMINDER" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ACL 2020</div><img src="images/acl'20.png" alt='LCFS-BERT' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Modelling context and syntactical features for aspect-based sentiment analysis**

Introduced LCFS-BERT, the first framework to bridge the syntactical gap in Transformer models for aspect extraction and sentiment classification, delivering new state-of-the-art results in 2020.

<p class="impact">Impact: Resolves the syntactical blind spot of Transformers and sets SoTA on aspect extraction and sentiment benchmarks.</p>

<p class="publication-links"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=gSEw8EsAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=gSEw8EsAAAAJ:u-x6o8ySG0sC" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/hieuvmphan/LCFS-BERT" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<!-- Visit the Google Scholar crawler action (see README) to refresh the citation data living under `google-scholar-stats/gs_data_shieldsio.json`. Use `<span class='show_paper_citations' data='[google-paper-id]'></span>` whenever you want to highlight an individual paper’s citation count. -->

## 🌱 Research Projects
- **Vision-Language Hallucination Detection:** Architected token-level grounding diagnostics that detect hallucinations in LVLM outputs.
- **Perception-grounded Vision-Language Model:** Created multimodal LLMs and VLMs that ground on visual evidence before predicting. Created proof-of-concept model on medical imaging domain.
- **Continual & Distillation Systems:** Designed knowledge distillation framework for model compression and continual learning via knowledge anchor.

## 🎖 Achievements
- **2023:** Chief Investigator on a $40k research grant from the Channel 7 Children’s Research Foundation for tumor segmentation (see [media link](https://crf.org.au/ai-assisted-contouring-of-sarcomas-to-improve-safety-of-proton-therapy-in-children/)).
- **2022:** Co-Investigator on a $50k research grant from the Queensland Department of Transport and Main Roads covering scene segmentation for road conditioning assessment.
- **2021–2023:** University Postgraduate Award (PhD scholarship), University of Wollongong.
<!-- - **2020:** Best Research Paper Award, IEEE SmartIoT Conference. -->
- **2017–2019:** Dean’s Merit Award (top 5% in faculty), University of Wollongong.

## 📖 Education
- **2020–2023:** Doctor of Philosophy, “Knowledge Distillation and Continual Learning for Optimized Deep Neural Networks,” University of Wollongong.
- **2017–2019:** Bachelor of Computer Science (GPA 9/10), University of Wollongong.

<!-- ## 💬 Invited Talks & Workshops
- CVPR 2025 Workshop on Vision-Language Alignment (Sydney) – *“Grounded hallucination diagnostics for industrial LVLMs.”*
- MICCAI 2025 Industrial Spotlight – *“Concept-based similarity reasoning in medical imaging.”* -->

## 💻 Collaboration
- Google Research Sydney – Research Scientist (current).
- Collaborative projects with AIML, University of Adelaide and CSIRO to translate medical grounding research into clinical pilots.

For collaboration or recruitment inquiries, email **hieuvmphan@google.com** or connect via [LinkedIn](https://www.linkedin.com/in/hieu-p/).