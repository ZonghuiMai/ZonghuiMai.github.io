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

My research interests include Physical enhancement, Constitutive model, Multimodality, and Affective Computing.

# Research Interests

<span class='anchor' id='research-interests'></span>

Physical enhancement, Constitutive model, Multimodality, Affective Computing

# Education

<span class='anchor' id='education'></span>

**Shantou University**, Shantou, China | Sep 2023 - Present
- Bachelor in Data Science and Big Data Technology
- Cumulative GPA: 3.89/5.00
- Selected Courses: Data Structure and Algorithm; Operating System; Database Theory; Object-Oriented Programming; C Language Programming; Python Programming Practice; Programming Design Foundation; Basic Software Design; System Design and Integration I; Machine Learning; Statistical Learning Method; Data Visualization; Data Collecting Techniques; Multi-source Information Fusion; Calculus B-I; Calculus B-II; Advance Calculus; Linear Algebra (Engineering); Probability and Statistics; Discrete Mathematics.

**University of Cambridge**, Cambridge, UK | Jul 21, 2024 - Aug 3, 2024
- Deep Learning Summer Program
- Cumulative GPA: 3.9/4.00

# Research Experience

<span class='anchor' id='research-experience'></span>

**Develop Muliti-stage Physical Constraint Framework Applied in Constitutive Models** | Shantou University, China
*Third Author, Mentor: Zhen Wang* | Jul 2024 - Sep 2025

- To address the problem of insufficient physical consistency in data-driven constitutive models, a multi-stage physical-constraint learning framework was constructed to study the embedding strategies of physical priors and their effects.
- Baseline models (e.g., MLP, RNN, and PINN) and a unified experimental environment were built and implemented for method comparison and ablation analysis.
- An evaluation dataset and experimental protocol were constructed based on material mechanics-related properties, and evaluation was conducted from the perspectives of performance, stability, and physical consistency.
- The first and second laws of thermodynamics were incorporated into training in the forms of data constraints and network structural constraints, respectively; a stage-wise physical-constraint mechanism was designed and its effects were verified.
- Responsible for writing the Method and Experiments sections of the paper, and completed key experimental design, result analysis, figure preparation, and reference organization.
- Responsible for periodic academic presentations, presenting the method design and experimental conclusions.

**Models Communication** | Shantou University, China
*Leader, Mentor: Zhen Wang* | Nov 2025 - Present

- For multi-model collaborative learning, designed an inter-model communication protocol to explore information interaction mechanisms during training/inference.
- Implemented and validated the communication protocol in constitutive thermodynamics tasks; results showed that, under specific settings, smaller-parameter models can obtain performance/efficiency gains superior to complex models through communication-based collaboration.
- Leading the extension of the communication mechanism to medical ultrasound image segmentation tasks and verifying its cross-domain applicability.
- Guiding group members in conducting application experiments of the communication protocol on different tasks.
- Participating in paper writing and result organization.

**Multi-level Context-aware Reasoning and Multimodality for Visual Emotion Analysis** | Shantou University, China
*First Author, Mentor: Rui Li* | Apr 2025 - Jan 2026

- For problems in VEA tasks such as dispersed emotional cues and insufficient cross-modal semantic alignment, studied multi-level context-aware reasoning and multimodal fusion methods.
- Compared the performance of multiple text-image fusion strategies on VEA tasks and proposed improvement schemes based on experimental results.
- Collected and organized commonly used VEA datasets, and completed analyses of data distribution, data volume bias, and dataset characteristics to support model design and experimental settings.
- Investigated representative baseline models and constructed a unified comparison benchmark to ensure comparability and reproducibility of subsequent validation.
- Studied the role of the text modality in VEA, constructed a textualized expression framework for image emotion by integrating knowledge from affective science/psychology, and improved emotion representation capability through multimodal modeling, achieving SOTA on multiple datasets.
- Responsible for paper writing, experimental result visualization, and figure plotting.

**Medical Ultrasound Segmentation Model and AI Agent** | Shantou University, China
*Group Leader, Course Project, Basic Software Design Course* | Sep 2025 - Dec 2025

- Participated in building an integrated medical ultrasound segmentation model + AI Agent system for segmentation and result analysis.
- Investigated AI Agent frameworks and medical image segmentation models, completed technical selection, and set up the training environment and experimental pipeline.
- Collected and preprocessed ultrasound datasets, adapted segmentation models to task requirements, and completed model service encapsulation and front-end integration for AI Agent invocation.

**Deep Learning Summer Programme** | Cambridge, UK
*Mentor: Pietro Lio* | Jul 21, 2025 - Aug 3, 2025

- Studied the full architecture of Deep Reinforcement Learning (DRL) and delved into Multi-Agent Reinforcement Learning (MARL) algorithms, including DDPG (Deep Deterministic Policy Gradient) and MADDPG (Multi-Agent DDPG).
- Collaborated with a team of 11 members to develop a "Simple World Communicate Game" as the main project.
- Took responsibility for explaining the key algorithms (DDPG and MADDPG) used in the game, presenting their application and implementation to the team. And finally got 70% grade of this program [(Grade Certificate)](files/cambridge_grade.pdf)

# 📝 Works

<span class='anchor' id='works'></span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJMS</div><img src='images/physical_c.png' alt="Constitutive Modeling" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Artificial Neural Networks Framework for Constitutive Modeling Enhanced by Multi-stage Thermodynamic Constraints](https://www.sciencedirect.com/journal/international-journal-of-mechanical-sciences)

**Zhen Wang**, Chen Zhang, **Zonghui Mai**, Meng Wang, Xiaoqiang Chen, Yaqi Yi, Huifang Chen

*International Journal of Mechanical Sciences* - Under Review (Manuscript: SUBMIT2IJMS-D-25-09869)

- To address the problem of insufficient physical consistency in data-driven constitutive models, we constructed a multi-stage physical-constraint learning framework.
- The first and second laws of thermodynamics were incorporated into training as data constraints and network structural constraints.
- Comprehensive evaluation on material mechanics tasks demonstrates improved performance, stability, and physical consistency.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI-ECAI</div><img src='images/stimuli_r.jpg' alt="Visual Sentiment Analysis" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-level Context-aware Reasoning for Enhancing Visual Sentiment Analysis: Decoding Image-Inherent Sentiment-Stimuli](https://www.ijcai.org/)

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
- Organizes the field from a practitioner’s perspective, with emphasis on why language helps, how prompts and multimodal fusion affect performance, and where current methods still fail.
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
- Implemented a **classification–segmentation–agent–report** framework: a classifier predicts organ/category cues, a segmentation model extracts lesion regions and quantitative features, and the agent layer generates standardized diagnostic reports.
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

**DaZhi Jiang**
*Professor, Department of Computer Science and Technology, Shantou University, Shantou, China*
- E-mail: dzjiang@stu.edu.cn
- [Shantou University - Personal Page](https://www.stu.edu.cn/cmac/info/1451/15891.htm)
