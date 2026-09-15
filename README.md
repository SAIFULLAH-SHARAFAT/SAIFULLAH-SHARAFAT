<div align="center">

<img width="150%" src="./assets/MD_Saifullah_Sharafat.svg" alt="Perception becomes geometry" />
<p><i>Perception becomes geometry.</i></p>
<h1>MD Shaifullah Sharafat</h1>
<p><b>Machine Learning Researcher · Computer Vision · Intelligent Sensing</b></p>
<p><i>Learning useful representations. Building reliable systems.</i></p>
<img width="700" src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=18&amp;duration=3300&amp;pause=1400&amp;color=E53935&amp;center=true&amp;vCenter=true&amp;width=700&amp;lines=Self-supervised+vision+and+robust+perception;3D+medical+imaging+and+multimodal+learning;From+sensor+signals+to+real-world+decisions" alt="Self-supervised vision · Medical imaging · Intelligent sensing" />

[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Research-0D1117?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=Y1GviSYAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--7757--6950-0D1117?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0005-7757-6950)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0D1117?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shaifullah-sharafat/)
[![Email](https://img.shields.io/badge/Email-Contact-0D1117?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shaifullah.sharafat@northsouth.edu)

<p><a href="#research-profile">About</a> &nbsp; / &nbsp; <a href="#selected-publications">Papers</a> &nbsp; / &nbsp; <a href="#featured-research-systems">Projects</a> &nbsp; / &nbsp; <a href="#research-toolkit">Toolkit</a></p>

</div>

## Research profile

I am a **Computer Science and Engineering graduate from North South University** and a machine learning researcher based in Bangladesh. I build **data-efficient, interpretable, and deployable AI systems** that connect learning algorithms with images, sensors, and real-world decision making.

My published work spans **self-supervised visual representation learning** and an **edge-deployed IoT–AI system for precision agriculture**. My recent systems work also includes leakage-controlled **3D DaT SPECT classification** for Parkinsonian syndrome screening. I am extending this foundation toward robust computer vision, multimodal scientific sensing, physics- and knowledge-guided learning, robotics perception, and responsible language technologies.

> **Research objective:** turn strong representations into reliable systems that remain useful under limited labels, distribution shift, noisy sensing, and deployment constraints.

## At a glance

<p align="center"><img src="https://img.shields.io/badge/02-PEER_REVIEWED_PAPERS-22D3EE?style=for-the-badge&labelColor=0D1117" alt="2 peer-reviewed papers" /> <img src="https://img.shields.io/badge/01-UNDER_REVIEW-A78BFA?style=for-the-badge&labelColor=0D1117" alt="1 manuscript under review" /></p>

| | |
|---|---|
| **Core** | Computer vision · self-supervised learning · robust and efficient deep learning |
| **Systems** | Intelligent sensing · edge AI · IoT–ML integration · decision support |
| **Emerging directions** | Multimodal learning · robotics perception · scientific ML · responsible Bangla NLP |
| **Application domains** | Agriculture · medical imaging · environmental sensing · autonomous systems |
| **Research output** | 2 peer-reviewed journal articles · 1 first-author manuscript under review · open research code and data |

## Selected publications

<table>
<tr>
<td width="50%" valign="top">
<h3>🌿 Self-supervised vision for plant health</h3>
<p><strong>Towards practical AI for agriculture: A self-supervised attention framework for Spinach leaf disease detection</strong></p>
<p><em>PLOS ONE, 21(1), e0340989, 2026</em><br /><strong>Co-author</strong></p>
<ul><li>SimSiam pretraining with attention-enhanced CNNs</li><li>CNN and vision-transformer benchmarking under limited data</li><li>Calibration, corruption robustness, and gradient-based explainability</li><li>Best domain-optimized model: <strong>97.31% accuracy</strong> and <strong>0.9983 macro ROC–AUC</strong></li></ul>
<a href="https://doi.org/10.1371/journal.pone.0340989"><strong>Paper</strong></a> · <a href="https://github.com/SAIFULLAH-SHARAFAT/A-Self-Supervised-Deep-Learning-Framework-for-Malabar-Spinach-Leaf-Disease-Classification"><strong>Code</strong></a> · <a href="https://huggingface.co/datasets/saifullah03/malabar_spinach_leaf_disease_dataset"><strong>Dataset</strong></a>
</td>
<td width="50%" valign="top">
<h3>🌾 Edge intelligence for precision agriculture</h3>
<p><strong>An IoT-enabled AI system for real-time crop prediction using soil and weather data in precision agriculture</strong></p>
<p><em>Smart Agricultural Technology, 12, 101263, 2025</em><br /><strong>First author</strong></p>
<ul><li>End-to-end acquisition, inference, and visualization pipeline</li><li>Soil N–P–K, pH, moisture, and live weather integration</li><li>Classical ensembles and deep tabular architectures</li><li>Raspberry Pi deployment with an interactive IoT dashboard</li></ul>
<a href="https://doi.org/10.1016/j.atech.2025.101263"><strong>Paper</strong></a> · <a href="https://github.com/SAIFULLAH-SHARAFAT/An-IoT-Enabled-AI-System-for-Real-Time-Crop-Prediction-Using-Soil-and-Weather-Data"><strong>Code</strong></a>
</td>
</tr>
</table>

<details>
<summary><b>◷ Manuscript under review — transformer-based vision</b></summary>


**Color-Aware and Token-Attentive Swin Transformers for Tea Leaf Disease and Pest Classification**  
*First-author manuscript · under review*

- Studies color-aware feature fusion and token-level attention for fine-grained disease and pest recognition.
- Evaluates transformer-based visual modeling for difficult agricultural image classes.

*This manuscript has not yet been accepted; it is separate from the peer-reviewed publications above.*

</details>

## Featured research systems

<table>
<tr>
<td width="55%" valign="top">
<h3>🧠 Multicenter 3D DaT SPECT classification</h3>
<p><strong>DrivenData DaT Parkinson’s Challenge · 2026</strong></p>
<p>A reproducible screening pipeline designed around the realities of multicenter neuroimaging rather than random image-level validation.</p>
<ul><li>Leakage-controlled 3D/2.5D modeling and acquisition-group-held-out validation</li><li>Frozen DINOv3 representations, radiomics/PCA features, and multimodal fusion</li><li>21-model volumetric ensemble with probability calibration and domain-shift testing</li><li>Previously recorded internal OOF log loss improved from <strong>0.3076 to 0.2930</strong>; AUROC from <strong>0.9389 to 0.9456</strong></li><li>Deterministic, network-free inference for containerized evaluation</li></ul>
<p><em>Internal validation results, not official leaderboard scores or evidence of clinical readiness.</em></p>
<a href="https://github.com/SAIFULLAH-SHARAFAT/DaT-Parkinson-Challenger"><strong>Explore the repository →</strong></a>
</td>
<td width="45%" valign="top">
<h3>🌱 Counterfactual weed vision</h3>
<p><strong>Background-robust recognition · ongoing</strong></p>
<p>An ongoing research pipeline that tests whether weed detectors learn the plant or exploit contextual shortcuts.</p>
<ul><li>Segmentation-assisted foreground/background interventions</li><li>Matched counterfactual evaluation arms</li><li>Cluster-held-out split design and annotation audits</li><li>Executable CIP-DETR experimental scaffold</li></ul>
Completed audits and frozen artifacts are distinguished from experiments still in progress.
<p><a href="https://github.com/SAIFULLAH-SHARAFAT/Weed_detection"><strong>Explore the repository →</strong></a></p>
</td>
</tr>
</table>

<details>
<summary><b>＋ Research and engineering experience</b></summary>


| Period | Role | Focus |
|---|---|---|
| **2025–Present** | **Deep Learning Researcher**, North South University | Self-supervised vision, transformers, robustness, calibration, and explainability |
| **2024–2025** | **Undergraduate Researcher / Capstone Research Lead**, North South University with Habiganj Agricultural University | Plant-health vision and an end-to-end IoT–AI crop decision system |
| **Apr–Jun 2025** | **IoT Engineer**, Neways International Company Limited | Embedded sensing, device integration, and applied IoT development |

</details>

## Current research directions

- **Representation learning:** self-supervision, contrastive objectives, attention, and foundation-model adaptation for label-scarce domains.
- **Reliable perception:** corruption robustness, calibration, explainability, uncertainty, and evaluation under distribution shift.
- **Scientific and sensor-aware ML:** multimodal fusion, physics- or knowledge-guided learning, and spatiotemporal decision support.
- **Embodied intelligence:** visual sensing and learning for UAV/UGV and robotic perception pipelines.
- **Responsible language technology:** evaluation of social-bias drift across Bangla, Romanized Bangla, and Banglish.

## Research toolkit

<div align="center">

[![Core toolkit](https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,sklearn&theme=dark)](https://skillicons.dev)

[![Systems toolkit](https://skillicons.dev/icons?i=c,cpp,raspberrypi,arduino,linux,bash,git,github,latex&theme=dark)](https://skillicons.dev)

</div>

| Area | Experience |
|---|---|
| **Vision and ML** | PyTorch, TensorFlow, OpenCV, scikit-learn, CNNs, vision transformers, SimSiam, supervised contrastive learning |
| **Evaluation** | Ablation studies, calibration, corruption testing, Grad-CAM family, classification and regression metrics |
| **Data and modeling** | NumPy, pandas, SQL, tree ensembles, tabular deep learning, multimodal fusion, experiment design |
| **Embedded and IoT** | Raspberry Pi, ESP32, Arduino, FreeRTOS, sensors/actuators, UART/I²C/SPI, edge inference |
| **Research workflow** | Git/GitHub, Linux, Bash, Jupyter, FastAPI, MATLAB, LaTeX, reproducible pipelines and scientific writing |

## Education and continuous learning

**BSc in Computer Science and Engineering**  
North South University, Dhaka, Bangladesh · 2025

Recent focused study includes deep learning, mathematical foundations for ML, computer vision, Python/SQL, and IoT/embedded systems. Credentials are selected below for relevance; credential IDs are omitted from this public profile.

<details>
<summary><b>Selected credentials</b></summary>

<br>

**Deep learning and machine learning**

- Neural Networks and Deep Learning — DeepLearning.AI, 2026
- Improving Deep Neural Networks: Hyperparameter Tuning, Regularization and Optimization — DeepLearning.AI, 2026
- Structuring Machine Learning Projects — DeepLearning.AI, 2026
- Convolutional Neural Networks — DeepLearning.AI, 2026
- Mathematics for Machine Learning and Data Science — DeepLearning.AI, 2025
- Supervised Machine Learning: Regression and Classification — Stanford Online, 2024

**Programming and data**

- Python for Everybody — University of Michigan, 2026
- SQL for Data Science — University of California, Davis, 2026
- Python for Data Science, AI & Development — IBM, 2024
- HackerRank Python Certificate — HackerRank, 2025

**IoT and embedded systems**

- The Raspberry Pi Platform and Python Programming for the Raspberry Pi — University of California, Irvine, 2025
- The Arduino Platform and C Programming — University of California, Irvine, 2025
- Interfacing with the Arduino — University of California, Irvine, 2025
- Introduction to the Internet of Things and Embedded Systems — University of California, Irvine, 2025
- Getting Started with Azure IoT Hub — Coursera Project Network, 2024

**Research and communication**

- IEEE Authorship and Open Access Symposium — IEEE, 2025
- Academic English: Writing — University of California, Irvine, 2025
- Speak English Professionally — Georgia Institute of Technology, 2025

</details>

## GitHub activity

<p align="center">
  <img width="57%" src="https://streak-stats.demolab.com?user=SAIFULLAH-SHARAFAT&amp;hide_border=true&amp;background=0D1117&amp;ring=22D3EE&amp;fire=A78BFA&amp;currStreakLabel=22D3EE&amp;sideLabels=94A3B8&amp;dates=64748B&amp;currStreakNum=E2E8F0&amp;sideNums=E2E8F0" alt="Shaifullah's public GitHub contribution streak" />
</p>

<p align="center"><sub><i>Contribution history is shown through the currently working streak service; unreliable public stats endpoints have been removed.</i></sub></p>

## Let’s connect

I welcome conversations around **computer vision, reliable and efficient AI, intelligent sensing, robotics perception, and interdisciplinary research collaborations**.

<div align="center">

[**Google Scholar**](https://scholar.google.com/citations?user=Y1GviSYAAAAJ) · [**ORCID**](https://orcid.org/0009-0005-7757-6950) · [**LinkedIn**](https://www.linkedin.com/in/shaifullah-sharafat/) · [**Email**](mailto:shaifullah.sharafat@northsouth.edu) · [**GitHub**](https://github.com/SAIFULLAH-SHARAFAT)

![Footer](https://capsule-render.vercel.app/api?type=waving&height=105&section=footer&color=0:0D1117,50:164E63,100:7C3AED)

</div>
