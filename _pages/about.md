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

# About Me

I am **Yuanyuan Zhang (张源远)**, a Postdoctoral Associate at the [SensorWeb Lab](http://sensorweb.engr.uga.edu/), University of Georgia, working with Prof. Wenzhan Song. I received my Ph.D. degree in Electrical and Electronic Engineering from the [University of Liverpool](https://www.liverpool.ac.uk/) (XJTLU joint program, Suzhou) in November 2025, advised by Prof. Rui Yang. Before that, I obtained my M.Sc. in Control and Optimization from [Imperial College London](https://www.imperial.ac.uk/) under the supervision of Prof. Eric C. Kerrigan, and my B.Eng. (First-Class Honours) in Electrical and Electronic Engineering, also from the University of Liverpool.

My research lies at the intersection of **device-free sensing, robust deep learning, and time-series modelling**. I am particularly interested in millimeter-wave radar-based contactless vital sign monitoring, where signal sparsity, motion artifacts, and limited annotated data continue to pose fundamental challenges. To address them, I develop solutions across the full stack — sparse signal processing, multi-task optimization, transfer learning, and ODE-embedded deep models — with the long-term goal of bringing reliable, unobtrusive cardiac sensing into real clinical and home environments.

I have authored several first-author papers in *IEEE Transactions on Mobile Computing*, *IEEE Transactions on Instrumentation and Measurement*, and *EMBC* (Oral, Top 7%). I also serve as a reviewer for *IEEE TIM*, *Neurocomputing*, and *IEEE WF-IoT*.

You can reach me via [email](mailto:y_zhang16@163.com), or find more information from my [Google Scholar](https://scholar.google.com/citations?user=hcCYfu4AAAAJ&hl=en), [GitHub](https://github.com/ZYY0844), [LinkedIn](https://www.linkedin.com/in/yuanyuan-16/), and [ORCID](https://orcid.org/0000-0003-0789-2294). A full [CV](/files/Yuanyuan_Zhang_CV.pdf) is available.

**Research Interests**

- Contactless vital sign monitoring with millimeter-wave radar
- Robust and transfer learning under limited / noisy data
- Multi-task optimization and gradient alignment
- Time-series forecasting (Mamba / state-space models)
- Sparse signal processing for biomedical applications

<span class='anchor' id='-news'></span>

# 🔥 News

- *2026.02*: &nbsp;🏆 Awarded the **[Marie Skłodowska-Curie Actions (MSCA) Postdoctoral Fellowship](https://marie-sklodowska-curie-actions.ec.europa.eu/actions/postdoctoral-fellowships)**, with the fellowship to commence in Summer 2027.
- *2026.01*: &nbsp; Started as a Postdoctoral Associate at the SensorWeb Lab, University of Georgia.
- *2025.11*: &nbsp;🎓 Successfully defended my Ph.D. thesis *"[Robust Cardiac Feature Monitoring based on Millimeter-Wave Radar](https://livrepository.liverpool.ac.uk/3194297/)"*.
- *2025.10*: &nbsp;🎉 Paper *"From High-SNR Radar Signal to ECG: A Transfer Learning Model with Cardio-Focusing Algorithm for Scenarios with Limited Data"* accepted by **IEEE Transactions on Mobile Computing**.
- *2025.07*: &nbsp;🎙️ *Recover from Horcrux* selected for **Oral Presentation (Top 7%)** at **EMBC 2025**.
- *2025.04*: &nbsp;🎉 *radarODE* accepted by **IEEE Transactions on Mobile Computing**, and *radarODE-MTL* accepted by **IEEE Transactions on Instrumentation and Measurement**.

<span class='anchor' id='-publications'></span>

# 📝 Publications

Co-author papers are listed at the end of each subsection. Full list on [Google Scholar](https://scholar.google.com/citations?user=hcCYfu4AAAAJ&hl=en).

**Journal**

1. **Yuanyuan Zhang**, Haocheng Zhao, Sijie Xiong, Rui Yang, Eng Gee Lim, Yutao Yue, "From High-SNR Radar Signal to ECG: A Transfer Learning Model with Cardio-Focusing Algorithm for Scenarios with Limited Data", **IEEE Transactions on Mobile Computing**, Oct. 2025.

2. **Yuanyuan Zhang**, Runwei Guan, Lingxiao Li, Rui Yang, Yutao Yue, Eng Gee Lim, "radarODE: An ODE-Embedded Deep Learning Model for Contactless ECG Reconstruction from Millimeter-Wave Radar", **IEEE Transactions on Mobile Computing**, Apr. 2025.

3. **Yuanyuan Zhang**, Rui Yang, Yutao Yue, Eng Gee Lim, "radarODE-MTL: A Multi-Task Learning Framework with Eccentric Gradient Alignment for Robust Radar-Based ECG Reconstruction", **IEEE Transactions on Instrumentation and Measurement**, Apr. 2025.

4. **Yuanyuan Zhang**, Rui Yang, Yutao Yue, Eng Gee Lim, Zidong Wang, "An Overview of Algorithms for Contactless Cardiac Feature Extraction From Radar Signals: Advances and Challenges", **IEEE Transactions on Instrumentation and Measurement**, Jul. 2023.

5. Sijie Xiong, Cheng Tang, **Yuanyuan Zhang**, Haoling Xiong, Youhao Xu, Atsushi Shimada, "CME-Mamba with Enhancing Nonlinear Dependencies for Time Series Forecasting", **Applied Soft Computing**, Aug. 2025.

6. Sijie Xiong, **Yuanyuan Zhang**, Cheng Tang, Haoling Xiong, Yiding Li, Atsushi Shimada, "U-MA: A Unified Framework with Differential Mamba under Parallel U-Net Scheme for Time Series Forecasting", **Engineering Applications of Artificial Intelligence**. *(Under Review)*

**Conference**

1. **Yuanyuan Zhang**, Sijie Xiong, Rui Yang, Eng Gee Lim, Yutao Yue, "Recover from Horcrux: A Spectrogram Augmentation Method for Cardiac Feature Monitoring from Radar Signal Components", *47th Annual International Conference of the IEEE Engineering in Medicine & Biology Society* (**EMBC 2025**), Jul. 2025. **(Oral, Top 7%)**

<span class='anchor' id='-projects'></span>

# 💻 Projects

Open-source code and data accompanying my research. See [GitHub](https://github.com/ZYY0844) for the full list.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMC 2025</div><img src='images/projects/cft_rfcardi.png' alt="CFT-RFcardi" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[CFT-RFcardi](https://github.com/ZYY0844/CFT-RFcardi)** &nbsp; <a href="https://github.com/ZYY0844/CFT-RFcardi"><img src="https://img.shields.io/github/stars/ZYY0844/CFT-RFcardi?style=social" alt="stars"></a>

A **cardio-focusing + transfer-learning** pipeline that learns ECG recovery from a small set of high-SNR radar signals and transfers to limited-data regimes. Released with a ready-to-run pre-processed dataset for quick validation.

[**Paper**](https://ieeexplore.ieee.org/document/11216086) &nbsp; · &nbsp; [**Code**](https://github.com/ZYY0844/CFT-RFcardi) &nbsp; · &nbsp; [**Dataset**](https://drive.google.com/file/d/1i0lZghlh_cT6JN0vsXCl66FX0eeETEfs/view?usp=sharing)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMC / TIM 2025</div><img src='images/projects/radarODE_MTL.jpg' alt="radarODE-MTL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[radarODE-MTL](https://github.com/ZYY0844/radarODE-MTL)** &nbsp; <a href="https://github.com/ZYY0844/radarODE-MTL"><img src="https://img.shields.io/github/stars/ZYY0844/radarODE-MTL?style=social" alt="stars"></a>

A multi-task learning framework with **eccentric gradient alignment** for robust radar-based ECG reconstruction. The repository implements both *radarODE* (IEEE TMC 2025) and *radarODE-MTL* (IEEE TIM 2025), decomposing long-term cardiac activity into individual cycles and leveraging an ODE decoder for noise robustness under body motion.

[**Paper (radarODE)**](https://arxiv.org/abs/2408.01672) &nbsp; · &nbsp; [**Paper (radarODE-MTL)**](https://arxiv.org/abs/2410.08656) &nbsp; · &nbsp; [**Code**](https://github.com/ZYY0844/radarODE-MTL)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMBC 2025 · Oral</div><img src='images/projects/horcrux.jpg' alt="Horcrux" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Horcrux](https://github.com/ZYY0844/Horcrux)** &nbsp; <a href="https://github.com/ZYY0844/Horcrux"><img src="https://img.shields.io/github/stars/ZYY0844/Horcrux?style=social" alt="stars"></a>

A **spectrogram-component augmentation** method for cardiac feature monitoring from radar signals. Horcrux splits a spectrogram into time-consistent components and re-combines them to enlarge effective training data, plug-and-play for any radar-spectrogram pipeline.

[**Paper**](https://embc.embs.org/2025/) &nbsp; · &nbsp; [**Code**](https://github.com/ZYY0844/Horcrux)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Toolkit</div><img src='images/projects/gpr_bscan.png' alt="GPR B-scan generator" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[GPR-B-scan-dataset-generator](https://github.com/ZYY0844/GPR-B-scan-dataset-generator)** &nbsp; <a href="https://github.com/ZYY0844/GPR-B-scan-dataset-generator"><img src="https://img.shields.io/github/stars/ZYY0844/GPR-B-scan-dataset-generator?style=social" alt="stars"></a>

A synthetic **B-scan dataset generation toolkit** for training neural networks on ground-penetrating radar imagery, built on top of [gprMax](https://github.com/gprMax/gprMax). Used in my undergraduate thesis on buried-object detection with CNNs.

[**Code**](https://github.com/ZYY0844/GPR-B-scan-dataset-generator)
</div>
</div>

<span class='anchor' id='-experience'></span>

# 💼 Experience

- *2026.01 - Present*, **Postdoctoral Associate**, SensorWeb Lab, University of Georgia, USA. *Advisor:* Prof. Wenzhan Song.
- *2024.07 - 2025.03*, **Research Assistant**, HKUST (Guangzhou), China. *Advisor:* Prof. Yutao Yue.
  - Time-series forecasting for predicting daily hospital outpatient visits (consulting for Distinct HealthCare, Shenzhen).
- *2021.12 - 2024.11*, **Research Assistant**, Deep Interdisciplinary Intelligence Lab, Institute of Deep Perception Technology (JITRI), Wuxi, China. *Advisor:* Prof. Yutao Yue.
  - Patent: Safety distance reminder system based on radar–camera fusion.
  - NSFC application: Pedestrian intention prediction for autonomous driving using multi-modality fusion.
  - Project: Next-generation radar–camera fusion for transportation with metamaterial and epistemic uncertainty.
- *2019.06 - 2019.08*, **Research Intern**, NARI Group Corporation, Nanjing, China.
  - Communications system engineer; validated the PCS-9882 multi-port Ethernet switch (BERT, RFC 2544, multi-stream UDP).

<span class='anchor' id='-education'></span>

# 📖 Education

- *2021.12 - 2025.11*, **Ph.D. in Electrical and Electronic Engineering**, University of Liverpool (XJTLU joint program), Suzhou, China.
  - *Thesis:* [Robust Cardiac Feature Monitoring based on Millimeter-Wave Radar](https://livrepository.liverpool.ac.uk/3194297/).
  - *Advisor:* Prof. Rui Yang.
- *2020.10 - 2021.10*, **M.Sc. in Control and Optimization (EEE)**, Imperial College London, UK. *GPA: 3.73/4.00.*
  - *Thesis:* Derivative-free Multi-objective Optimization.
  - *Advisor:* Prof. Eric C. Kerrigan.
- *2018.09 - 2020.05*, **B.Eng. in Electrical and Electronic Engineering (Year 2 & 3)**, University of Liverpool, UK. *GPA: 4.00/4.00.*
  - *Thesis:* Detection and Classification of Buried Objects from GPR Image Using CNN.

<span class='anchor' id='-service-and-skills'></span>

# 🛠️ Service & Skills

**Professional Service** &nbsp;&middot;&nbsp; Reviewer for *IEEE Transactions on Instrumentation and Measurement*, *Neurocomputing*, *IEEE WF-IoT 2025*.

**Programming** &nbsp;&middot;&nbsp; C / C++, Python, PyTorch, MATLAB, Julia, GPRmax, LaTeX.

**Languages** &nbsp;&middot;&nbsp; Chinese (Native), English (Fluent).

**Volunteer** &nbsp;&middot;&nbsp; Primary School Teacher, AIESEC Overseas Volunteer Program, Colombo, Sri Lanka (Jul. 2017).

**Off the clock** &nbsp;&middot;&nbsp; Swimming, fingerstyle guitar, classical music.
