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

Hieu Phan is a research scientist at Google Research (Sydney) with a track record of translating multimodal intelligence research into production-ready systems. He specializes in **multimodal LLMs**, **vision-language grounding**, **knowledge distillation**, and **continual learning**. Hieu holds a PhD from the University of Wollongong and completed his postdoctoral work at the Australian Institute for Machine Learning (AIML) at the University of Adelaide.

## Research Statement

Humans perceive the visual world as symbols, reasoning and imagining. My work focuses on linking visual perceptions to concepts so that machines can understand, reason, and predict across language, vision, and audio modalities. I develop robust evaluation pipelines, grounding metrics, and representation models that keep pace with large-scale industrial deployments.

## 🔥 News
- **2026.03:** CVPR ’26 papers on LVLM hallucination detection and confounder tracing were accepted, both led from the Google Research Sydney lab.
- **2025.10:** Awarded internal Google Research funding to build multi-modal grounding toolkits with clinical collaborators.

## 📝 Selected Publications (high-impact venues)
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/500x300.png' alt='Class similarity weighted knowledge distillation' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Class similarity weighted knowledge distillation for continual semantic segmentation**<br>
MH Phan, SL Phung, L Tran-Thanh, A Bouzerdoum, et al.

<p class="publication-meta">Project | Citations: 95</p>

Introduced class similarity weighting to distill knowledge for continual semantic segmentation, significantly reducing catastrophic forgetting while keeping the teacher’s high-resolution predictions.

<p class="impact">Academic Impact: Adopted by follow-up works in class-incremental segmentation and continual learning benchmarks.</p>
<p class="impact">Industry Impact: Provided the distillation backbone for a Google Research pipeline that updates segmentation models without retraining from scratch.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">IJCV 2023</div><img src='images/500x300.png' alt='SegViT v2' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**SegViT v2: Exploring Efficient and Continual Semantic Segmentation with Plain Vision Transformers**<br>
B Zhang, L Liu, MH Phan, Z Tian, C Shen, Y Liu

<p class="publication-meta">Project | Volume 71</p>

Re-envisioned plain Vision Transformers for continual semantic segmentation by pairing efficient patch encoders with experience replay. Demonstrated strong generalization across urban and medical domains.

<p class="impact">Academic Impact: Reference architecture for ViT-based continual segmentation evaluations.</p>
<p class="impact">Industry Impact: Shared as an internal Google blueprint for balancing efficiency and accuracy on on-device GPUs.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/500x300.png' alt='Decomposing disease descriptions' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Decomposing Disease Descriptions for Enhanced Pathology Detection**<br>
VMH Phan, Y Xie, Y Qi, L Liu, L Liu, B Zhang, Z Liao, Q Wu, MS To, et al.

<p class="publication-meta">Project | Citations: 46</p>

Multi-aspect vision-language pre-training framework that decomposes textual disease descriptions into structured factors, improving both classification and grounding accuracy in clinical imaging.

<p class="impact">Academic Impact: Influenced subsequent work in structured VLP for medicine.</p>
<p class="impact">Industry Impact: Powered prototype diagnostics that provide concept-level explanations to radiologists.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">WACV 2024</div><img src='images/500x300.png' alt='Boundary privileged knowledge distillation' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**BPKD: Boundary Privileged Knowledge Distillation for Semantic Segmentation**<br>
L Liu, Z Wang, MH Phan, B Zhang, J Ge, Y Liu

<p class="publication-meta">Project | Citations: 55</p>

Introduced boundary-aware privileged distillation that focuses the student on hard pixel transitions, improving performance on both segmentation benchmarks and clinical datasets.

<p class="impact">Academic Impact: Spawned follow-ups in boundary-sensitive distillation and unsupervised training.</p>
<p class="impact">Industry Impact: Adopted for high-resolution partitioning in medical image pipelines.</p>
</div>
</div>

Visit the Google Scholar crawler action (see README) to refresh the citation data living under `google-scholar-stats/gs_data_shieldsio.json`. Use `<span class='show_paper_citations' data='[google-paper-id]'></span>` whenever you want to highlight an individual paper’s citation count.

## 🌱 Research Projects
- **Vision-Language Hallucination Detection:** Architected token-level grounding diagnostics that detect hallucinations in LVLM outputs and plugged them into Google Research evaluation suites.
- **Medical Visual Grounding + Explainability:** Led concept-based similarity reasoning systems for medical image analysis, pairing counterfactual explanations with expert feedback loops.
- **Continual & Distillation Systems:** Designed class-independent transformations and multi-head distillation to maintain segmentation accuracy as new domains arrive.

## 🎖 Honors & Funding
- Competitive Google Research internal funding for grounded medical multimodal systems (2025–2026).
- Postdoctoral fellowship, Australian Institute for Machine Learning, University of Adelaide.
- Google PhD fellowship shortlist (finalist).

## 📖 Education
- **Postdoctoral Researcher** – Australian Institute for Machine Learning, University of Adelaide.
- **PhD, Computer Vision & Machine Learning** – University of Wollongong.
- **BEng (Hons)** – [Add university if preferred].

## 💬 Invited Talks & Workshops
- CVPR 2025 Workshop on Vision-Language Alignment (Sydney) – *“Grounded hallucination diagnostics for industrial LVLMs.”*
- MICCAI 2025 Industrial Spotlight – *“Concept-based similarity reasoning in medical imaging.”*

## 💻 Internships & Collaboration
- Google Research Sydney – Research Scientist (current).
- Collaborative projects with AIML, University of Adelaide and CSIRO to translate medical grounding research into clinical pilots.

For collaboration or recruitment inquiries, email **hieu.phan@google.com** or connect via [LinkedIn](https://www.linkedin.com).