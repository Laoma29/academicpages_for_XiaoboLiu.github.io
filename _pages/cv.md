---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Neuroscience**, McGill University, 2020–2025
  * Thesis: *Spatiotemporal structure of human spontaneous traveling waves*
  * Supervisor: Prof. Sylvain Baillet
  * Committee: Boris Bernhardt, Christopher Pack
* **M.Eng. in Biomedical Engineering**, University of Electronic Science and Technology of China (UESTC), 2017–2020
  * Thesis: *Research on EEG Rhythm of Population of Action Video Game*
  * Supervisor: Prof. Dezhong Yao | Co-Supervisor: Prof. Li Dong
* **B.Eng. in Automation**, HuaQiao University, 2013–2017
  * Thesis: *Adaptive Control of Brushless DC Motors Based on Embedded Microcontroller*
  * Supervisor: Prof. Zhuoyun Nie

Research Experience
======
* **Feb. 2025–Present**: Neuroimaging Data Scientist, Chongqing University Affiliated Hospital
  * Analyzing multimodal neuroimaging data (fMRI, MRI) for subjective cognitive decline
* **Dec. 2025–Present**: MEG Data Scientist, The Sixth Hospital of Peking University
  * Analyzing MEG data during sleep and memory-consolidation processes
* **Feb. 2023–Apr. 2023**: Neuroimaging Data Scientist, Dept. of Psychiatry, Wuhan Wuchang Hospital, Wuhan University of Science and Technology
  * Analyzing multimodal neuroimaging data for psychiatric disorders
* **Sept. 2017–Sept. 2020**: Software Engineer, Key Laboratory of Nerve Information, UESTC
  * Developed EEG/fMRI analysis pipeline and website for [Webrain Project](http://webrain.uestc.edu.cn)
* **Jan. 2015–Sept. 2017**: Research Assistant, Institution of Advanced Technology, Xiamen
  * Developed hardware/software platforms for motor control ([Sukung](https://docs.sukung.cn/zh/latest/))
  * Developed Matlab/Arduino teaching platform for algorithm control
  * Developed multi-DOF mechanical arm with visual feedback control

Technical Skills
======
* **Programming**: Python, C, MATLAB, R
* **Operating Systems**: Unix, Linux, Windows
* **Languages**: Chinese (native), English, Hokkien
* **Neuroimaging**: fMRI, MRI, DTI, EEG, MEG, iEEG, PSG
* **Modeling**: Statistical modeling, Machine/Deep learning (Transformer, LSTM, CNN), Reinforcement learning, Computer vision, Computational neuroscience modeling (Mean Field, Wilson-Cowan)
* **BCI**: Single-chip microcomputer

Editorial Service
======
* **Editor**: Current Alzheimer Research (2025–present), Magnetic Resonance Imaging (2024–present)
* **Reviewer**: Frontiers in Neuroscience, Frontiers in Human Neuroscience, Neuroimage, Advanced Science, Physiological Measurement, Brain Research Bulletin, IEEE TCE, Journal of Neural Engineering, Brain Behavior and Immunity, BMC Medicine, EAAI, IEEE IoT Journal

Honors & Awards
======
* Grad Excellence Award & CSC Scholarship, McGill University ($27,000/year, 2020–2024)
* Grad Excellence Award, McGill University ($16,000/year, 2020–2024)
* QBIN Recruitment Scholarships Competition ($8,000, 2023–2024)
* QBIN Training Scholarships ($3,000, 2023–2024)
* McGill Mobility Scholarships ($1,500, 2023–2024)
* QBIN Traveling Award ($1,500, 2022–2024)
* HBHL Traveling Award ($500, 2022)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
