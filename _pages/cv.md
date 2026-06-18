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
* **Nanyang Technological University** — Graduate student, 2025 – present  
* **Shanghai Jiao Tong University** — B.S. in Automation, IEEE Pilot Class, Aug 2021 – Jun 2025  
  * Outstanding student recognition, 2022  

Internships
======
* **KNQ** — Intern, May 2026 – present  
  * AI applications with large multimodal models for visual understanding (VLMs, visual reasoning, product-facing pipelines)  
* **Pulse Vision** — Intern, Sep 2025 – Nov 2025  
  * Real-time detection for PRCV-oriented scenarios; YOLOv5 / YOLOv8 / YOLO-Nano  
  * ONNX export and TensorRT deployment; ROI-focused pipeline; 150+ FPS inference  

Research experience
======
* **Research intern**, IWIN-FINS Lab (FINS), Shanghai Jiao Tong University  
  * Mar 2023 – Jun 2025  
  * Supervisor: Prof. Jianping He  

* **DRPP with ambiguity sets for visual tracking**  
  * PyTorch implementation; evaluation on OTB and TC128 benchmarks  
  * Robust / distributionally robust formulation with ambiguity-set modeling  

* **CUT++ unsupervised image translation** (Sep 2024 – Dec 2024)  
  * AI3603 group project; CUT / GAN baselines with Transformer and PatchNCE  
  * Evaluation with FID, LPIPS, and PSNR — [code on GitHub](https://github.com/Alanze/AI3603-Final-Project)  

Skills
======
* **Languages:** Python, C++, MATLAB  
* **Frameworks & tools:** PyTorch, Transformers, YOLO, CLIP, SAM  
* **Other:** LaTeX, Markdown  

Portfolio
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
