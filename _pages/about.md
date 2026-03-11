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

Token-level grounding metrics that detect hallucinations with high sensitivity, paired with a classifier that distinguishes grounded tokens from spurious generations.

<p class="impact">Academic Impact: Provides a benchmark for LVLM hallucination detection across grounding layers.</p>
<p class="impact">Industry Impact: Embedded into Google Research evaluation suites to monitor hallucination drift.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2026 Findings</div><img src="images/cvpr'26_hallu_method.pdf" alt='Overthinking Causes Hallucination' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Overthinking Causes Hallucination: Tracing Confounder Propagation in Vision Language Models**

Characterizes how confounders proliferate through LVLM decoders and proposes diagnostic paths that reveal the exact layers where grounding breaks down.

<p class="impact">Academic Impact: Opens a new angle on debugging LVLM hallucinations by tracking semantic drift.</p>
<p class="impact">Industry Impact: Helps product teams calibrate LVLM inference behavior across modalities.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src="images/REMINDER.png" alt='Class similarity weighted knowledge distillation' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Class similarity weighted knowledge distillation for continual semantic segmentation**

Weighted the distillation loss by class similarity to preserve fine-grained structure during incremental learning, significantly reducing forgetting on long-tail categories.

<p class="impact">Academic Impact: Regularly cited in continual segmentation literature as a prototype for class-aware distillation.</p>
<p class="impact">Industry Impact: Adopted for on-device segmentation updates at Google and inspires continual learning baselines.</p>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge badge--highlight">ICCV 2025 Highlight</div><img src="images/iccv'25_prompt_feature_huy.pdf" alt='Seeing the Trees for the Forest' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Seeing the Trees for the Forest: Rethinking Weakly-Supervised Medical Visual Grounding**

Highlights prompt-feature pairings for weakly-supervised grounding, reconciling coarse annotations with fine-grained localization signals in medical imagery.

<p class="impact">Academic Impact: Chosen as an ICCV 2025 Highlight for its interpretability contributions.</p>
<p class="impact">Industry Impact: Supplies guidance for prompt engineering in clinical report generation.</p>
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