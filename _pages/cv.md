---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

🎓 Education
======
  - **Ph.D.** in Computer Vision and Autonomous Driving — **Bosch Research for AI**, in cooperation with University of Lübeck *(Dec 2023 – Present)*
  - **M.S.** in Robotics, Systems and Control — **ETH Zurich** *(2021-2023)*, GPA: 5.67/6.0                      
  - **B.Sc.** in Mechanical Engineering — **RWTH Aachen University** *(2016-2020)*, Dean's List (Top 5%)

💼 Industry Experience
======

* Since December 2023: **Industrial Ph.D. Research Scientist** at Bosch Research
  * Developing 3D scene understanding methods for autonomous driving, with **first-author** or **core contributor** publications at **CVPR (2024, 2026)**, **ICML 2026**, **AAAI 2026**, **WACV 2026**; one additional paper under review.
  * Benchmarked radar perception methods, including object detection, occupancy prediction, and self-supervised learning, on proprietary Bosch datasets.
  * Co-organized and contributed to workshops on 3D foundation models for autonomous driving perception.

* Winter 2021: **Research Engineer Intern** at Volkswagen AG
  * Developed an AR-based data augmentation pipeline for semantic segmentation, automating obstacle catalogue extraction and camera-projection-based insertion into driving scenes across diverse ground textures; 
  * Boosted semantic segmentation performance by **+5% mIoU** through photorealistic synthetic data augmentation, reducing manual annotation overhead.

* Summer 2021: **Software Engineering Intern** at BMW AG
  * Analyzed large-scale driving data via AWS and PySpark to characterize traffic scenario distributions across China and Germany
  * Developed Monte Carlo-based risk models for autonomous driving safety-in-use analysis. 

* 2019-2020: **Research Intern and Bachelor Thesis Student** at Schaeffler AG
  * Researched optimization methods for heat pump systems in electric mobility applications. Personal Patent: *(Patent No. DE102022100491A1)* Geometry-variable ejector.

🔬 Research Experience at University
======
* Summer 2023: Master Thesis Student at **ETH Zurich, Autonomous Systems Lab**
  * Proposed a Swin-Transformer-based method for high-resolution LiDAR point cloud reconstruction from sparse low-resolution input, published at CVPR 2024, GPA: 6.0/6.0
  * Mentored one undergraduate researcher, supervising continuation of ongoing LiDAR perception research

* Winter 2022: Research Project Assistant at **ETH Zurich, AIT Lab for Intelligent Interactive Systems**
  * Designed a camera localization method to enhance 3D gaze estimation, improving spatial accuracy of gaze-to-scene mapping through refined camera pose optimization.

🛠️ Skills
======
* **Programming**: Python, C++, CUDA, Bash
* **Deep Learning**: PyTorch, PyTorch Lightning, TensorFlow, Hugging Face, Weights & Biases
* **3D/CV Libraries**: Open3D, PCL, MinkowskiEngine, MMDetection3D, OpenCV
* **Infrastructure**: Linux, Docker, ROS, GPU clusters, Azure, AWS, OpenShift
* **LLM**: OpenAI, Claude automations, Antropic API

🏅 Honors & Awards
======
* Outstanding Reviewer Award — **CVPR 2025, 2026**
* Silver Reviewer Award — **ICML 2026**
* Schaeffler Top Student Award — **Schaeffler AG** *(2020)*
* Dean's List Award every semester — **RWTH Aachen University** *(2016–2020, top 5%)*
* **Scholarship** recipient — Bildungsfonds, Carl-Arthur Pastor Stiftung, Hans Hermann Voss-Stiftung *(2016–2018)*

📄 Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

🤝 Service and Leadership
======
* **Teaching Assistant** — Perception for Autonomous Vehicles, University of Lübeck *(since 2024)*
* **Reviewer** — CVPR, NeurIPS, ICML, ICLR, ICCV, ECCV *(2024–2026)*
