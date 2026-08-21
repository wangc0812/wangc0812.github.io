---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. candidate in the Microelectronic Thrust at [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), advised by [Prof. Shanshi Huang](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/HUANG-Shanshi/shanshihuang) and [Prof. Wei Zhang](https://ece.hkust.edu.hk/eeweiz) (IEEE Fellow).

My research lies at the intersection of **electronic design automation (EDA)**, **machine-learning accelerators**, and **domain-specific architecture**. I develop simulation methods, design-space exploration tools, and heterogeneous compute-in-memory (CIM) architectures for efficient AI systems.

[Download my CV (PDF)](/files/Cong_Wang_CV.pdf){: .btn .btn--primary } &nbsp; [View all publications](/publications/){: .btn }

Research Highlights
===================

* **CIM simulation and design-space exploration:** First contributor to [MICSim](https://github.com/MICSim-official/MICSim_V1.0), an open-source modular simulator that connects model-accuracy evaluation with hardware-performance estimation for mixed-signal CIM accelerators.
* **Heterogeneous AI hardware:** Research on scalable CIM chiplet architectures, hybrid CIM accelerators, and hardware-mapping co-exploration for Vision Transformers.
* **Circuit simulation:** Research on exponential integration and model order reduction for large-scale transient circuit simulation, with publications at IEEE TCAD and ICCAD.

Education
=========

* **Ph.D. Candidate**, The Hong Kong University of Science and Technology (Guangzhou), Sept. 2023 - Present
  * Microelectronic Thrust
  * Advisors: [Prof. Shanshi Huang](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/HUANG-Shanshi/shanshihuang) and [Prof. Wei Zhang](https://ece.hkust.edu.hk/eeweiz)
* **M.Eng.**, Southern University of Science and Technology, Sept. 2021 - Jul. 2023
  * School of Microelectronics; Advisor: [Prof. Quan Chen](https://sustech.edu.cn/en/faculties/chenquan.html)
* **B.Eng.**, Zhengzhou University, Sept. 2017 - Jul. 2021
  * School of Information Engineering

Selected Publications
=====================

{% assign selected_publications = site.publications | where_exp: "post", "post.priority != 1" %}
{% assign priority_publications = selected_publications | where_exp: "post", "post.priority" | sort: "priority" %}
{% assign other_publications = selected_publications | where_exp: "post", "post.priority == nil" | sort: "date" | reverse %}
{% for post in priority_publications %}
{{ forloop.index }}. {{ post.citation }}
{% endfor %}
{% for post in other_publications %}
{{ forloop.index | plus: priority_publications.size }}. {{ post.citation }}
{% endfor %}

Honors and Awards
=================

* Best Paper Award, International Symposium on Quality Electronic Design (ISQED), 2026
* HKUST(GZ) Research Postgraduate Scholarship, 2023-present
* SUSTech Outstanding Graduate, 2023
* Best Paper Nomination, National Graduate Forum on Microelectronics, 2023
* Third Place, Integrated Circuit EDA Elite Challenge, 2023
* SUSTech Postgraduate Scholarship, 2021-2023

Teaching
========

* **MICS6000U ML Accelerator**, Teaching Assistant, Fall 2024
* **UCMP6010 Cross-disciplinary Research Methods**, Teaching Assistant, Spring 2025
