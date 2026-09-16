---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}

{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an undergraduate student at Shantou University, majoring in Data Science and Big Data Technology.

My research interests include multimodal representation and reasoning, embodied AI, and physical AI.

# Research Interests

<span class='anchor' id='research-interests'></span>

Multimodal Representation and Reasoning, Embodied and Physical AI

# Education

<span class='anchor' id='education'></span>

**Shantou University**, Shantou, China | Sep 2023 - Present

- Bachelor of Science in Data Science and Big Data Technology
- Cumulative GPA: 89.50/100
- Selected Courses: Machine Learning; Statistical Learning Method; Multi-source Information Fusion; Linear Algebra; Probability and Statistics; Advanced Calculus; Python Programming Practice, etc.

**University of Cambridge**, Cambridge, UK | 21 Jul 2024 - 3 Aug 2024

- Deep Learning Summer Programme
- Cumulative GPA: 3.9/4.00

# Research Experience

<span class='anchor' id='research-experience'></span>

**ProcessVLM: Long-Horizon Robot Process Understanding for VLA Data Curation** | SLAI & HKUST

*Research Intern, Advisor: Prof. Ziqi Wang* | 10 Jul 2026 - Present

- Built a long-video preprocessing pipeline for VLA data curation, using a VLM to perform temporal subtask segmentation and semantic labeling on raw multi-view robot episodes. Integrated task-schema constraints, entity grounding, and persistent SAM 3.1 tracking to produce structured data with persistent entity associations, subtask boundaries, and process-state labels.
- Developed ProcessVLM based on Qwen3-VL-8B to jointly predict events, temporal boundaries, task phases, outcomes, entity states, task progress, and executable subtasks. Introduced a history branch and gated memory module to model long-term process states across temporal windows.
- Designed a closed-loop ProcessVLM-π0.5 integration framework that conditions the action policy on entity states, task progress, failure signals, and replanning cues. Proposed staged joint training to reduce invalid actions and improve long-horizon task success under dynamic subtask ordering and failure recovery.

**Multi-level Context-aware Reasoning and Multimodality for Visual Emotion Analysis** | Shantou University, China

*First Author, Mentor: Rui Li* | Apr 2025 - Jan 2026

- For problems in VEA tasks such as dispersed emotional cues and insufficient cross-modal semantic alignment, studied multi-level context-aware reasoning and multimodal fusion methods.
- Compared the performance of multiple text-image fusion strategies on VEA tasks and proposed improvement schemes based on experimental results.
- Collected and organized commonly used VEA datasets, and completed analyses of data distribution, data volume bias, and dataset characteristics to support model design and experimental settings.
- Investigated representative baseline models and constructed a unified comparison benchmark to ensure comparability and reproducibility of subsequent validation.
- Studied the role of the text modality in VEA, constructed a textualized expression framework for image emotion by integrating knowledge from affective science/psychology, and improved emotion representation capability through multimodal modeling, achieving SOTA on multiple datasets.
- Responsible for paper writing, experimental result visualization, and figure plotting.

**Development of a Multi-stage Physical-Constraint Framework for Constitutive Modeling** | Shantou University, China

*Third Author, Mentor: Zhen Wang* | Jul 2024 - Sep 2025

- To address the problem of insufficient physical consistency in data-driven constitutive models, a multi-stage physical-constraint learning framework was constructed to study the embedding strategies of physical priors and their effects.
- Baseline models (e.g., MLP, RNN, and PINN) and a unified experimental environment were built and implemented for method comparison and ablation analysis.
- An evaluation dataset and experimental protocol were constructed based on material mechanics-related properties, and evaluation was conducted from the perspectives of performance, stability, and physical consistency.
- The first and second laws of thermodynamics were incorporated into training in the forms of data constraints and network structural constraints, respectively; a stage-wise physical-constraint mechanism was designed and its effects were verified.
- Responsible for writing the Method and Experiments sections of the paper, and completed key experimental design, result analysis, figure preparation, and reference organization.
- Responsible for periodic academic presentations, presenting the method design and experimental conclusions.

# 📝 Works

<span class='anchor' id='works'></span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJMS</div><img src='images/physical_c.png' alt="Constitutive Modeling" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[An Artificial Neural Networks Framework for Constitutive Modeling Enhanced by Multi-stage Thermodynamic Constraints](files/Manuscript_MTCNN.pdf)

**Zhen Wang**, Chen Zhang, **Zonghui Mai**, Meng Wang, Xiaoqiang Chen, Yaqi Yi, Huifang Chen

*International Journal of Mechanical Sciences* - Under Review (Manuscript: SUBMIT2IJMS-D-25-09869)

- To address the problem of insufficient physical consistency in data-driven constitutive models, we constructed a multi-stage physical-constraint learning framework.
- The first and second laws of thermodynamics were incorporated into training as data constraints and network structural constraints.
- Comprehensive evaluation on material mechanics tasks demonstrates improved performance, stability, and physical consistency.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI-ECAI</div><img src='images/stimuli_r.jpg' alt="Visual Sentiment Analysis" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Multi-level Context-aware Reasoning for Enhancing Visual Sentiment Analysis: Decoding Image-Inherent Sentiment-Stimuli](files/MCRStimuli.pdf)

**Zonghui Mai**, **Rui Li**, Shuhao Wu

*IJCAI-ECAI 2026 Main Track* - Under Review (Submission ID: 5266)

- Addressed problems in Visual Emotion Analysis tasks such as dispersed emotional cues and insufficient cross-modal semantic alignment.
- Proposed a multi-level context-aware reasoning and multimodal fusion method for enhanced emotion representation.
- Achieved SOTA performance on multiple datasets through text modality integration and multimodal modeling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Survey / Notes</div><img src='images/3methods.jpg' alt="Visual Emotion Analysis Survey" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Visual Emotion Analysis: Notes, Bottlenecks, and Future Directions](files/VEA_survey.pdf)

**Zonghui Mai**

*Personal Survey / Research Notes* - Unpublished (2026)

- A self-driven survey and research note that summarizes how Visual Emotion Analysis (VEA) has evolved from visual-only methods to language-assisted and VLM-assisted paradigms.
- Organizes the field from a practitioner's perspective, with emphasis on why language helps, how prompts and multimodal fusion affect performance, and where current methods still fail.
- Distills key open challenges (e.g., label ambiguity, limited supervision semantics, reasoning quality) and motivates future directions toward richer context-aware sentiment-stimuli reasoning.

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Course Project</div>
      <img src='images/ai_agent.png' alt="Multi-Agent Ultrasound Diagnostic Assistant Pipeline" width="100%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

[Multi-Agent Ultrasound AI Assistant](files/demo_video.mp4)

**Team Project** | *Software Design Course, Shantou University*

*Course Project / Full-Stack AI System Prototype* - 2025

- Built an end-to-end ultrasound case interpretation system covering **case creation → image upload → AI analysis → result saving → report generation → PDF export**.
- Designed a **5-agent collaborative pipeline** (**Result Parser / Feature Extractor / Diagnosis Analyzer / Report Generator / Report Refiner**) to transform model outputs into structured clinical-style reports.
- Implemented a **classification-segmentation-agent-report** framework: a classifier predicts organ/category cues, a segmentation model extracts lesion regions and quantitative features, and the agent layer generates standardized diagnostic reports.
- Integrated the AI pipeline with a full-stack application (frontend + backend + API service) for interactive analysis, result visualization, and report management.

<div style="margin-top: 10px; display: flex; gap: 10px; flex-wrap: wrap;">
  <a href="files/demo_video.mp4" target="_blank" rel="noopener"
     style="display:inline-block; padding:8px 14px; border-radius:8px; background:#2563eb; color:#fff; text-decoration:none; font-weight:600;">
    ▶ Watch Demo Video
  </a>
</div>

  </div>
</div>

# English Test & Additional Skills

<span class='anchor' id='english-test--additional-skills'></span>

- **[Duolingo English Test (DET)](files/DuolingoEnglishTest.pdf):** 110 (Overall); Literacy 110, Comprehension 115, Conversation 110, Production 85
- **Languages:** Mandarin (Native), Cantonese (Native), English (Fluent)
- **Saxophone:** Awarded First Prize in Instrumental Group A at the 7th Guangdong University Students' Art Exhibition
- **English Debate:** Won Second Prize at the 2024 Guangdong International Speech and Debate Championship and Shantou Intercollegiate English Debate Competition; Won Second Prize in the 5th FLTRP English Debate Novice Championship

# References

<span class='anchor' id='references'></span>

**Zhen Wang**

*Lecturer, Department of Civil Engineering and Smart Cities, Shantou University, Shantou, China*

- E-mail: wzhen@stu.edu.cn
- [Shantou University - Personal Page](https://eng.stu.edu.cn/info/1085/2064.htm)

**Rui Li**

*Lecturer, Department of Computer Science and Technology, Shantou University, Shantou, China*

- E-mail: ruili@stu.edu.cn
- [Shantou University - Personal Page](https://www.stu.edu.cn/cmac/info/1451/5301.htm) | [Google Scholar](https://scholar.google.com/citations?user=V9oO4oMAAAAJ&hl=en)
