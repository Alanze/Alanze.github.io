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

Research experience
======
* **Research intern**, IWIN-FINS Lab (FINS), Shanghai Jiao Tong University  
  * Mar 2023 – Jun 2025  
  * Supervisor: Prof. Jianping He  

* **DRPP with ambiguity sets for visual tracking**  
  * PyTorch implementation; evaluation on OTB and TC128 benchmarks  
  * Robust / distributionally robust formulation with ambiguity-set modeling  

* **Real-time detection for PRCV-oriented scenarios** (Sep 2025 – Nov 2025)  
  * YOLOv5, YOLOv8, and YOLO-Nano; TensorRT and ONNX deployment  
  * ROI-focused pipeline; 150+ FPS inference; strong mAP gains on target benchmarks  

* **Multi-object tracking** (Nov 2023 – Feb 2024)  
  * YOLOv5 detector with DeepSORT and ByteTrack  
  * IOU association, ReID features, GPU-accelerated pipeline  

* **CUT++ unsupervised image translation** (Sep 2024 – Dec 2024)  
  * CUT / GAN baselines with Transformer and PatchNCE  
  * Diffusion-based variants; evaluation with INST, FID, and PSNR  

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
