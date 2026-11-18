---
permalink: /
title: "About"
redirect_from:
  - /about/
  - /about.html
---

# Yuanyuan Zhang {#profile}

I am **Yuanyuan Zhang (张源远)**, a Postdoctoral Associate at the [SensorWeb Lab](http://sensorweb.engr.uga.edu/), University of Georgia, working with Prof. Wenzhan Song. I received my Ph.D. degree in Electrical and Electronic Engineering from the [University of Liverpool](https://www.liverpool.ac.uk/) in November 2025, advised by Prof. Rui Yang. Before that, I obtained my M.Sc. in Control and Optimization from [Imperial College London](https://www.imperial.ac.uk/) under the supervision of Prof. Eric C. Kerrigan, and my B.Eng. (First-Class Honours) in Electrical and Electronic Engineering, also from the University of Liverpool.

My primary research focus is **Physical AI for Health**. I combine deep learning with physical models of how the body generates signals and how sensors measure them. I study how these models can recover cardiovascular information from radar reflections and bed vibrations, even when motion distorts the measurements or paired training data are scarce. <span id="interests">Outside research, I enjoy swimming, playing fingerstyle guitar, and listening to classical music.</span>

[Curriculum Vitae]({{ '/files/Yuanyuan_Zhang_CV.pdf' | relative_url }}) · [Google Scholar](https://scholar.google.com/citations?user=hcCYfu4AAAAJ&hl=en) · [Publications]({{ '/publications/' | relative_url }}) · [Interests](#interests)

## Research Overview

<div class="research-themes" markdown="1">

### Physical AI for Health

I embed models of cardiac dynamics in neural networks and use models of vibration transmission to constrain what networks learn from bed-mounted sensors.

[Bodyseismography](https://arxiv.org/abs/2610.35844) · [Blood Pressure Estimation](https://arxiv.org/abs/2608.23562) · [radarODE](https://doi.org/10.1109/TMC.2025.3563945)

### Unobtrusive Cardiovascular Sensing

I develop radar methods for recovering electrocardiograms during body motion and for adapting those methods to settings with few paired radar and ECG recordings.

[radarODE-MTL](https://doi.org/10.1109/TIM.2025.3562975) · [CFT-RFcardi](https://doi.org/10.1109/TMC.2025.3625051)

### Time-Series Modeling for Health

My collaborators and I study how state-space models capture temporal dependencies and how feedback controllers can improve forecasts from continuous glucose measurements.

[CME-Mamba](https://doi.org/10.1016/j.asoc.2025.113758) · [Glucose Forecasting](https://doi.org/10.1016/j.neunet.2026.109893)

</div>

<h2 id="-education">Education</h2>

- *2021.12 - 2025.11*, **Ph.D. in Electrical and Electronic Engineering**, University of Liverpool (XJTLU), Suzhou, China.
  - *Thesis:* [Robust Cardiac Feature Monitoring based on Millimeter-Wave Radar](https://livrepository.liverpool.ac.uk/3194297/).
  - *Advisor:* Prof. Rui Yang.
- *2020.10 - 2021.10*, **M.Sc. in Control and Optimization (EEE)**, Imperial College London, UK.
  - *Thesis:* Derivative-free Multi-objective Optimization.
  - *Advisor:* Prof. Eric C. Kerrigan.
- *2018.09 - 2020.05*, **B.Eng. in Electrical and Electronic Engineering (Year 2 & 3)**, University of Liverpool, UK.
  - *Thesis:* Detection and Classification of Buried Objects from GPR Image Using CNN.

<h2 id="-news">News</h2>

<div class="news-scroll" role="region" aria-labelledby="-news" tabindex="0" markdown="1">

| | |
|:---|:---|
| Nov 2026 | Our [study on glucose forecasting](https://doi.org/10.1016/j.neunet.2026.109893) appeared in *Neural Networks*. We combined Holt–Winters forecasting with feedback control to predict glucose levels from continuous monitor readings. |
| Oct 2026 | We released a [white paper on bodyseismography (BSG)](https://arxiv.org/abs/2610.35844). It uses physical models to explain how cardiovascular activity produces body vibrations along three axes. |
| Oct 2026 | Our [workshop paper on reconstructing arterial blood pressure waveforms from body vibrations](https://doi.org/10.1145/3842436.3843808) appeared in the proceedings of the 4th International Workshop on Human-Centered Sensing, Modeling, and Intelligent Systems. |
| Oct 2026 | Our paper on [differential state-space models for time-series forecasting](https://doi.org/10.1016/j.engappai.2026.115625) appeared in *Engineering Applications of Artificial Intelligence*. |
| Sep 2026 | *Heart Rhythm O2* published three of our conference abstracts on bed-based sensing for [blood pressure monitoring](https://doi.org/10.1016/j.hroo.2026.08.074), [atrial fibrillation detection](https://doi.org/10.1016/j.hroo.2026.08.105), and [sleep staging and apnea monitoring](https://doi.org/10.1016/j.hroo.2026.08.104). |
| Feb 2026 | Awarded a Marie Skłodowska-Curie Actions Postdoctoral Fellowship for [HealRo](https://cordis.europa.eu/project/id/101263991) at the University of Glasgow. |
| Jan 2026 | Joined the SensorWeb Lab at the University of Georgia as a Postdoctoral Associate. |
| Nov 2025 | Completed my Ph.D. at the University of Liverpool. [Doctoral thesis](https://livrepository.liverpool.ac.uk/3194297/) |
| Oct 2025 | Our paper on [radar-based ECG reconstruction with limited training data](https://doi.org/10.1109/TMC.2025.3625051) was accepted by *IEEE Transactions on Mobile Computing*. |
| Jul 2025 | [Recover from Horcrux](https://doi.org/10.1109/EMBC58623.2025.11254289) was selected for an oral presentation at EMBC (top 7% of submissions). |
| Apr 2025 | radarODE and radarODE-MTL were accepted by *IEEE Transactions on Mobile Computing* and *IEEE Transactions on Instrumentation and Measurement*, respectively. |
{: .news-list}

</div>

<h2 id="-experience">Experience</h2>

- *2026.01 - Present*, **Postdoctoral Associate**, SensorWeb Lab, University of Georgia, USA. *Advisor:* Prof. Wenzhan Song.
- *2024.07 - 2025.03*, **Research Assistant**, HKUST (Guangzhou), China. *Advisor:* Prof. Yutao Yue.
  - Time-series forecasting for predicting daily hospital outpatient visits (consulting for Distinct HealthCare, Shenzhen).
- *2021.12 - 2024.11*, **Research Assistant**, Deep Interdisciplinary Intelligence Lab, Institute of Deep Perception Technology (JITRI), Wuxi, China. *Advisor:* Prof. Yutao Yue.
  - Patent: Safety distance reminder system based on radar–camera fusion.
  - NSFC application: Pedestrian intention prediction for autonomous driving using multi-modality fusion.
  - Project: Next-generation radar–camera fusion for transportation with metamaterial and epistemic uncertainty.
- *2019.06 - 2019.08*, **Research Intern**, NARI Group Corporation, Nanjing, China.
  - Communications system engineer; validated the PCS-9882 multi-port Ethernet switch (BERT, RFC 2544, multi-stream UDP).

## Collaborators

- Brunel University of London
- East China University of Science and Technology
- Emory University
- Kyushu University
- Nagoya Institute of Technology
- Stanford University
- The Chinese University of Hong Kong
- The Hong Kong University of Science and Technology (Guangzhou)
- University of Georgia
- University of Liverpool
- University of Washington
- Xi’an Jiaotong-Liverpool University
{: .collaborator-schools}

<script>
  const formerSections = {
    '#-publications': "{{ '/publications/' | relative_url }}",
    '#-projects': "{{ '/research/' | relative_url }}",
    '#-service-and-skills': "{{ '/service/' | relative_url }}"
  };
  if (formerSections[location.hash]) location.replace(formerSections[location.hash]);
</script>
