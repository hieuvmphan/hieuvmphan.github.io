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

Hieu Phan is a research scientist at Google Research (Sydney) with a track record of from fundamental research on multimodal intelligence into production-ready systems. He specializes in **multimodal LLMs**, **vision-language grounding**, **knowledge distillation**, and **continual learning**. Hieu holds a PhD from the University of Wollongong. He completed his postdoctoral research fellow at the Australian Institute for Machine Learning (AIML), Adelaide University, advised by [Prof. Anton van de Hengel](https://www.google.com/search?client=safari&rls=en&q=Anton+van+de+Hengel&ie=UTF-8&oe=UTF-8) and [A/Prof Johan Verjans](https://scholar.google.com/citations?user=57JVdyIAAAAJ&hl=en).

<p class="cta"><a href="/files/atlas-hieu-phan-cv.pdf" target="_blank" rel="noopener">Download CV</a></p>

## Research Statement

Current vision-language models remain data-hungry and often rely on spurious correlations, unlike humans who reason through symbols and concepts. My research builds concept-grounded visual reasoning systems that link perception to semantic evidence so models become more data-efficient, reliable, and interpretable.

## Research Agenda

My work advances grounded visual reasoning in VLMs through two connected directions:
- **Hallucination Diagnosis:** Dissect and identify when visual hallucination arises within internal layers of VLMs.
- **Human-centric Intervention:** Design human priors that enforce visual grounding, and correct hallucinatory behaviors.

The goal is to shift VLMs from pattern matching to evidence-based reasoning systems that generalize efficiently in real settings.

## 🔥 News
- **2026.03:** Two CVPR 2026 papers accepted on LVLM hallucination diagnosis and detection!
- **2025.09:** Joined Google <img src="images/g-logo.jpg" alt="Google logo" class="inline-logo"> as a Vision-Language Modeling Research Scientist.
- **2025.10:** Awarded ICCV 2025 Outstanding Reviewer.
- **2025.08:** Three ICCV 2025 papers accepted, including an **ICCV Highlight** on weakly supervised  visual grounding!
- **2024.02:** One CVPR 2024 paper accepted on multi-aspect vision-language pre-training.
- **2023.08:** IJCV published SegViTv2 on efficient and continual segmentation with Vision Transformers.
- **2022.02:** CVPR 2022 accepted, proposing class-aware distillation for continual segmentation.
- **2020.12:** ACL 2020 paper introduced LCFS-BERT for syntax-aware aspect-based sentiment analysis.

<span class='anchor' id='publications'></span>

## 📝 Selected Publications
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src="images/cvpr'26_overview.pdf" alt='Beyond the Global Scores overview' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Beyond the Global Scores: Fine-Grained Token Grounding as a Robust Detector of LVLM Hallucinations**

A breakthrough framework reveals insufficient token-grounding ability within VLM's internal layers when hallucination arises. This insight helps establish a strong benchmark for LVLM hallucination detection.
<p class="publication-links"><a href="https://arxiv.org/html/2604.04863v1" target="_blank" rel="noopener">Paper</a> · <a href="https://token-grounding-detection-cvpr26.github.io" target="_blank" rel="noopener">Project</a> · <span class="publication-links__na">Code: pending</span></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2026 Findings</div><img src="images/cvpr'26_hallu_method.pdf" alt='Overthinking Causes Hallucination' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Overthinking Causes Hallucination: Tracing Confounder Propagation in Vision Language Models**

A novel study pinpoints where confounders propagate in LVLM decoders, providing a practical debugging signal for targeted intervention before hallucinations escalate.
<p class="publication-links"><a href="https://arxiv.org/pdf/2603.07619" target="_blank" rel="noopener">Paper</a> · <a href="https://overthinking-cvpr26.github.io/Overthinking-VLMs-CVPR26.github.io/" target="_blank" rel="noopener">Project</a> · <span class="publication-links__na">Code: pending</span></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ACL 2026 Oral</div><img src="images/mmclip_figure1.png" alt='MMCLIP Figure 1' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**MMCLIP: Cross-Modal Attention Masked Modelling for Medical Language-Image Pre-Training**

We developed MMCLIP to help VLMs learn rare pathological features under scarce data by combining paired and unpaired data with attention-masked image modeling and entity-driven language modeling.
<p class="publication-links"><a href="https://arxiv.org/abs/2407.19546" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/AIGeeksGroup/MMCLIP" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge badge--highlight">ICCV 2025 Highlight</div><img src="images/iccv'25_prompt_feature_huy.pdf" alt='Seeing the Trees for the Forest' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Seeing the Trees for the Forest: Rethinking Weakly-Supervised Medical Visual Grounding**

This ICCV 2025 Highlight advances weakly supervised medical visual grounding by aligning prompt cues with fine-grained evidence.
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Huy_Seeing_the_Trees_for_the_Forest_Rethinking_Weakly-Supervised_Medical_Visual_ICCV_2025_paper.pdf" target="_blank" rel="noopener">Paper</a> · <span class="publication-links__na">Code: pending</span></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src="images/iccv'25-ovg-hq.png" alt='OVG-HQ' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**OVG-HQ: Online Video Grounding with Hybrid-modal Queries**

OVG-HQ enables robust online video grounding with hybrid-modal queries, maintaining strong performance even under severe modality imbalance and limited context.
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Zeng_OVG-HQ_Online_Video_Grounding_with_Hybrid-modal_Queries_ICCV_2025_paper.pdf" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/maojiaqi2324/OVG-HQ" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src="images/ijcai'25_main_fig_loba.pdf" alt='Localizing Before Answering' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Localizing Before Answering: A Benchmark for Grounded Medical Visual Question Answering**

LobA, a novel MLLM model, reduces hallucinations by enforcing localization before answer generation.
<p class="publication-links"><a href="https://www.ijcai.org/proceedings/2025/853" target="_blank" rel="noopener">Paper</a> · <span class="publication-links__na">Code: pending</span></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src="images/cvpr'24-method.pdf" alt='Decomposing disease descriptions' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Decomposing Disease Descriptions for Enhanced Pathology Detection: A Multi-Aspect Vision-Language Pre-training Framework**

MAVL (pronounced as 'Marvel') improves generalizability of medical vision-language model by aligning multi-aspect disease concepts with image evidence.
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Phan_Decomposing_Disease_Descriptions_for_Enhanced_Pathology_Detection_A_Multi-Aspect_Vision-Language_CVPR_2024_paper.pdf" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/hieuvmphan/CVPR2024_MAVL" target="_blank" rel="noopener">Code</a></p>
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">IJCV 2024</div><img src="images/ijcv'25.png" alt='SegViTv2' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**SegViTv2: Exploring Efficient and Continual Semantic Segmentation with Plain Vision Transformers**

SegViTv2 delivers efficient continual segmentation by converting ViT attention into high-quality masks while preserving prior knowledge with minimal forgetting.
<p class="publication-links"><a href="https://link.springer.com/article/10.1007/s11263-023-01894-8" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/zbwxp/SegVit" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src="images/REMINDER.png" alt='Class similarity weighted knowledge distillation' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Class similarity weighted knowledge distillation for continual semantic segmentation**

This paper established a class-aware distillation strategy that became a practical reference for reducing forgetting in continual semantic segmentation.
<p class="publication-links"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Phan_Class_Similarity_Weighted_Knowledge_Distillation_for_Continual_Semantic_Segmentation_CVPR_2022_paper.pdf" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/hieuvmphan/REMINDER" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ACL 2020</div><img src="images/acl'20.png" alt='LCFS-BERT' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Modelling context and syntactical features for aspect-based sentiment analysis**

LCFS-BERT addressed a key syntactic weakness in Transformer-based sentiment models and delivered state-of-the-art results for aspect-based sentiment analysis.

<p class="publication-links"><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=gSEw8EsAAAAJ&cstart=20&pagesize=80&sortby=pubdate&citation_for_view=gSEw8EsAAAAJ:u-x6o8ySG0sC" target="_blank" rel="noopener">Paper</a> · <a href="https://github.com/hieuvmphan/LCFS-BERT" target="_blank" rel="noopener">Code</a></p>
</div>
</div>

<!-- Visit the Google Scholar crawler action (see README) to refresh the citation data living under `google-scholar-stats/gs_data_shieldsio.json`. Use `<span class='show_paper_citations' data='[google-paper-id]'></span>` whenever you want to highlight an individual paper’s citation count. -->

## 🌱 Research Projects
- **Vision-Language Hallucination Detection:** Architected token-level grounding diagnostics that detect hallucinations in LVLM outputs.
- **Perception-grounded Vision-Language Model:** Created multimodal LLMs and VLMs that ground on visual evidence before predicting. Created proof-of-concept model on medical imaging domain.
- **Continual & Distillation Systems:** Designed knowledge distillation framework for model compression and continual learning via knowledge anchor.

<span class='anchor' id='honors-awards'></span>

## 🎖 Achievements
- **2023:** Chief Investigator on a $40k grant from the Channel 7 Children’s Research Foundation for AI-assisted pediatric tumor segmentation (see [media link](https://crf.org.au/ai-assisted-contouring-of-sarcomas-to-improve-safety-of-proton-therapy-in-children/)).
- **2022:** Co-Investigator on a $50k Queensland Department of Transport and Main Roads grant for scene segmentation in road-condition assessment.
- **2021–2023:** University Postgraduate Award (PhD scholarship), University of Wollongong.
- **2025:** ICCV 2025 Highlight paper on weakly supervised medical visual grounding.
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
