---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download the full CV (PDF)](/files/Cong_Wang_CV.pdf){: .btn .btn--primary }

Research Interests
==================

**Electronic Design Automation (EDA)**, **Machine-Learning Accelerators**, **Domain-Specific Architecture**

Education
=========

* **Ph.D. Candidate**, The Hong Kong University of Science and Technology (Guangzhou), Sept. 2023 - Present
  * Microelectronic Thrust
  * Advisors: [Prof. Shanshi Huang](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/HUANG-Shanshi/shanshihuang) and [Prof. Wei Zhang](https://ece.hkust.edu.hk/eeweiz) (IEEE Fellow)
* **M.Eng.**, Southern University of Science and Technology, Sept. 2021 - Jul. 2023
  * School of Microelectronics; Advisor: [Prof. Quan Chen](https://sustech.edu.cn/en/faculties/chenquan.html)
* **B.Eng.**, Zhengzhou University, Sept. 2017 - Jul. 2021
  * School of Information Engineering

Research and Project Experience
===============================

### MICSim: Open-Source CIM Accelerator Simulator

*First contributor, Sept. 2023 - Jul. 2024*

Developed a modular simulator for mixed-signal CIM accelerators in CNNs and Transformers. Unified model-accuracy and hardware-performance evaluation in the open-source [MICSim V1.0](https://github.com/MICSim-official/MICSim_V1.0) project.

### Tiny TPU: MICS6000U Course Project

*Teaching assistant and lead contributor, Fall 2024*

Implemented a compact TPU in SystemVerilog and authored course tutorials and cocotb testbenches.

### Transient Circuit Simulation Acceleration

*Core contributor, Jan. 2022 - Jul. 2023*

Developed exponential-integrator methods in an NSFC project to accelerate large-scale transient circuit simulation.

### Model Order Reduction for Circuit Simulation

*Primary contributor, Jul. 2021 - Aug. 2022*

Developed industrial-grade C++ programs for model order reduction methods in a Huawei HiSilicon collaboration.

Publications
============

<ol>
{% assign publications = site.publications | sort: "date" | reverse %}
{% for post in publications %}
  <li>{{ post.citation }}</li>
{% endfor %}
</ol>

Honors and Awards
=================

* Best Paper Award, International Symposium on Quality Electronic Design (ISQED), 2026
* HKUST(GZ) Research Postgraduate Scholarship, 2023-present
* SUSTech Outstanding Graduate, 2023
* Best Paper Nomination, National Graduate Forum on Microelectronics, 2023
* Third Place, Integrated Circuit EDA Elite Challenge, 2023
* SUSTech Postgraduate Scholarship, 2021-2023
* Zhengzhou University Third Prize Scholarship, 2021
* National Encouragement Scholarship, 2019 and 2020
* Merit Student of Zhengzhou University, 2019 and 2020
* First Prize, Zhengzhou University National Mathematics Competition, 2020
* Second Prize, Henan Province National Mathematics Competition, 2020
* First Place, Zhengzhou University "Qiushi Cup" Mathematics Competition, 2020
* First Prize, "Challenge Cup" National College Student Business Plan Competition, 2019
* Excellent Student Cadre, 2019
* Advanced Individual of Social Work, 2018
* Excellent Student Volunteer, 2018

Teaching
========

* **MICS6000U ML Accelerator**, Teaching Assistant, Fall 2024
* **UCMP6010 Cross-disciplinary Research Methods**, Teaching Assistant, Spring 2025

Skills
======

* **Programming:** Python (NumPy, SciPy), C/C++, MATLAB
* **Hardware and Verification:** Verilog/SystemVerilog, cocotb
* **AI Framework:** PyTorch
* **Software and Tools:** LaTeX, Markdown, Microsoft Office
* **Languages:** Mandarin (native), English (IELTS 7.0, CET-6)
