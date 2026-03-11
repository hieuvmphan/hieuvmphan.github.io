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
- **2026.03:** CVPR 2026 accepted 2 papers on detection pipelines for LVLM hallucinations and confounder propagation.
- **2025.10:** CVPR 2025 accepted 2 papers (Interactive Medical Image Analysis with Concept-based Similarity Reasoning and Looking in the Mirror: Faithful Counterfactual Explanations).
- **2025.09:** ICCV 2025 Highlight (medical visual grounding) and recognition as an ICCV 2025 Outstanding Reviewer.
- **2024.11:** CVPR 2024 accepted 1 paper on multi-aspect pathology descriptions.

## 📝 Selected Publications (high-impact venues)
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
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src="images/iccv'25-ovg-hq.png" alt='OVG-HQ' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**OVG-HQ: Online Video Grounding with Hybrid-modal Queries**

OVG-HQ-Unify leverages a Parametric Memory Block and cross-modal distillation to keep previous knowledge while strengthening weaker modalities in limited-context online settings.

<p class="impact">Impact: Empowers a single model to handle hybrid-modal queries despite modality imbalance.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src="images/ijcai'25_main_fig_loba.pdf" alt='Localizing Before Answering' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Localizing Before Answering: A Benchmark for Grounded Medical Visual Question Answering**

The Localize-before-Answer (LobA) framework trains LMMs to spot regions of interest and self-prompt on segmented pathological areas before producing answers.

<p class="impact">Impact: Boosts visual reasoning by forcing grounding first, then generating reliable answers.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src="images/cvpr'24-method.pdf" alt='Decomposing disease descriptions' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Decomposing Disease Descriptions for Enhanced Pathology Detection: A Multi-Aspect Vision-Language Pre-training Framework**

Dissects biomedical texts into aspect-centric representations via LLMs and medical experts, then aligns each aspect with image cues through a dual-head Transformer.

<p class="impact">Impact: Aligns images with disease representations by matching diverse aspects, yielding stronger compatibility scores for known and unknown pathologies.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src="images/REMINDER.png" alt='Class similarity weighted knowledge distillation' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Class similarity weighted knowledge distillation for continual semantic segmentation**

Weights the distillation loss by class similarity to preserve fine-grained structure during incremental learning, reducing forgetting on long-tail categories.

<p class="impact">Impact: Serves as a reference for class-aware distillation in continual segmentation and on-device updates.</p>
</div>
</div>

Visit the Google Scholar crawler action (see README) to refresh the citation data living under `google-scholar-stats/gs_data_shieldsio.json`. Use `<span class='show_paper_citations' data='[google-paper-id]'></span>` whenever you want to highlight an individual paper’s citation count.

## 🌱 Research Projects
- **Vision-Language Hallucination Detection:** Architected token-level grounding diagnostics that detect hallucinations in LVLM outputs and plugged them into Google Research evaluation suites.
- **Medical Visual Grounding + Explainability:** Led concept-based similarity reasoning systems for medical image analysis, pairing counterfactual explanations with expert feedback loops.
- **Continual & Distillation Systems:** Designed class-independent transformations and multi-head distillation to maintain segmentation accuracy as new domains arrive.

## 🎖 Achievements
- **2023:** Chief Investigator on a $40k research grant from the Channel 7 Children’s Research Foundation for tumor segmentation (see [media link](https://crf.org.au/ai-assisted-contouring-of-sarcomas-to-improve-safety-of-proton-therapy-in-children/)).
- **2022:** Co-Investigator on a $50k research grant from the Queensland Department of Transport and Main Roads covering scene segmentation for road conditioning assessment.
- **2021–2023:** University Postgraduate Award (PhD scholarship), University of Wollongong.
- **2020:** Best Research Paper Award, IEEE SmartIoT Conference.
- **2017–2019:** Dean’s Merit Award (top 5% in faculty), University of Wollongong.

## 📖 Education
- **2020–2023:** Doctor of Philosophy, “Knowledge Distillation and Continual Learning for Optimized Deep Neural Networks,” University of Wollongong.
- **2017–2019:** Bachelor of Computer Science (GPA 9/10), University of Wollongong.

## 💬 Invited Talks & Workshops
- CVPR 2025 Workshop on Vision-Language Alignment (Sydney) – *“Grounded hallucination diagnostics for industrial LVLMs.”*
- MICCAI 2025 Industrial Spotlight – *“Concept-based similarity reasoning in medical imaging.”*

## 💻 Internships & Collaboration
- Google Research Sydney – Research Scientist (current).
- Collaborative projects with AIML, University of Adelaide and CSIRO to translate medical grounding research into clinical pilots.

For collaboration or recruitment inquiries, email **hieu.phan@google.com** or connect via [LinkedIn](https://www.linkedin.com).