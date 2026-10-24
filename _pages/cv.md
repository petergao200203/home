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
* M.S.E. in Electrical and Computer Engineering, Johns Hopkins University, 2025 – Present
* Graduate Success Through Academics and Research (G-STAR), Data Science, University of California, Irvine, 2024 – 2025 (GPA: 3.95/4.00)
* B.E. in Network Engineering, Shandong University of Science and Technology, 2021 – 2024 (GPA: 3.50/4.00)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Experience
======
* **Cost-Aware Advice Renewal in Non-Stationary Bandits** (Sep 2026 – Present)
  * Developing a framework balancing dynamic regret and advice-query costs, deriving near-matching minimax bounds for two-arm bandits with at most one unknown change.
  * Designed a confidence-gated advice-renewal strategy with finite-sample bounds; benchmarked across 500 synthetic settings.
* **LLM-Enhanced Parallel Snake Optimizer for KELM Hyperparameter Optimization** (Jun 2025 – Dec 2025) — Published in IEEE Transactions on Industry Applications (2026)
  * Proposed an LLM-enhanced parallel snake optimizer with adaptive cross-population communication; designed an asymmetric fitness function explicitly penalizing over-prediction.
  * Achieved the best MAE, RMSE, NRMSE, MAPE and R² on the GEFCom2012 short-term load forecasting benchmark.
* **Prosody-Controllable Multilingual Speech Synthesis for Expressive Speech Translation** (Oct 2025 – Jul 2026, Johns Hopkins University)
  * Built multilingual TTS pipelines; implemented word-level prosody modeling for controllable transfer of pitch, energy, duration, emotion and speaking style.
* **"HyperA2M" Multimodal Speech-to-Text and Meeting Summarization** (Oct 2025 – Dec 2025)
  * Built a pipeline of speech activity detection, speaker clustering (Chinese Restaurant Process) and Whisper transcription; fine-tuned Qwen-1.5B with LoRA for meeting summarization.
* **UAV Path Planning with a Reinforcement Evolutionary Algorithm** (Oct 2025 – Nov 2025) — Accepted at ICGEC 2025
  * Developed a Double DQN–DE framework for multi-UAV path planning; validated on LiDAR-based real-world island terrain with up to 27.7% improvement over DE and pure Double DQN baselines.
* **Color Image Encryption with Hierarchical Surrogate-Assisted Optimization** (Oct 2025 – Nov 2025) — Published in Electronics (2025)
  * Hybrid differential evolution + surrogate-model optimization with EMA-based dynamic population control; Chen hyperchaotic system and DNA-encoding fusion workflow.
* **Android Malware Classification with MSMOPSO-FlashCodeBERT** (Jul 2025 – Nov 2025)
  * Integrated FlashAttention into CodeBERT for Android malware detection; multi-objective hyperparameter optimization with an improved MOPSO algorithm.
* **Information-Theoretic Foundations of Federated Unlearning** (Mar 2025 – May 2026)
  * Led a systematic review of federated unlearning; built an information-theoretic framework (mutual information, Shannon entropy, KL divergence) comparing exact and approximate unlearning.
* **LLM-Driven Emergency Rescue Command-and-Control** (Jan 2025 – Present)
  * Proposed a GPT-enhanced parallel PREA framework for typhoon-induced urban flood emergency response; built LLM-driven information extraction and planning modules.
* **Wind Power Forecasting with Parallel SO-KELM** (Nov 2023 – Sep 2024) — Published at IEEE SPIES 2024
  * Integrated parallel snake-optimizer-tuned KELM into wind power forecasting for automated hyperparameter tuning; ran parameter-sensitivity and stability analyses.
* **Motor Health Monitoring and Efficiency Optimization** (Jun 2023 – Jun 2024)
  * Coordinated project workflow; processed real industrial motor data for efficiency evaluation and fault pattern detection.
* **Smart Grid Security with Federated Intelligence** (Jun 2022 – Jun 2023)
  * Integrated federated-learning-based ML into smart grid security for collaborative training without sharing sensitive data.
* **Wind–Solar Complementary Power Generation System** (Sep 2022 – Nov 2022)
  * Optimized system models and core algorithms for wind–solar complementary generation under varying conditions.
* **WOA-GSK-ELMAN Atmospheric Temperature Prediction** (May 2022 – Jul 2022)
  * Debugged and optimized the WOA-GSK-ELMAN model for stability, convergence and generalization.
* **Image Encryption with Improved Marine Predator Algorithm** (Jan 2022 – Apr 2022)
  * Improved the Marine Predator Algorithm to strengthen image encryption security and efficiency.
* **Differential Evolution Image Encryption with Logistic-Map DNA Encoding** (Dec 2021 – Apr 2022)
  * Implemented DE-optimized key generation with Logistic-map and DNA-based encryption techniques.

Research Positions & Activities
======
* **Team Leader, Key Laboratory, Shandong University of Science and Technology** (Sep 2021 – Jun 2025)
  * Coordinated team participation in competitions and guided the team in conducting research.
  * Organized recruitment of new team members, fostering a collaborative environment for learning technical skills.
  * Research areas: optimization algorithms, deep learning, evolutionary computation, federated learning, secure image encryption, and energy and industry applications.

Work Experience
======
* **ML & Data Engineering Intern, Shandong Sun Digital Technology Co., Ltd.** (May 2026 – Aug 2026, Shandong, China)
  * Built a Python data pipeline integrating heterogeneous structured and unstructured enterprise records.
  * Prototyped semantic retrieval and RAG for domain-specific information access (vector + keyword hybrid search).
  * Implemented API-based model and data services with automated evaluation and logging workflows.
* **Data Analyst Intern, Xendat Data Analytics** (Mar 2025 – Jun 2025, Orange County, CA, USA)
  * Analyzed complex datasets into business insights; designed and maintained ontology models; contributed to Django backend development.
* **Laser Display Factory Intern, Hisense Laser Display Co., Ltd.** (Jun 2024 – Aug 2024, Shandong, China)
  * Assisted product quality inspection with automated testing equipment and secondary screening; analyzed quality data for continuous improvement.
* **Optoelectronics Technology Intern, Primanex Corporation** (Jan 2024 – Feb 2024, Shandong, China)
  * Assisted inspection and functional testing of laser anemometers; conducted automated testing on transmission modules.
* **Network Technology Intern, Shandong Sun Digital Technology Co., Ltd.** (Dec 2022 – Jan 2023, Shandong, China)
  * Managed network switches and system configurations in a hospital environment; maintained a big data center and server room operations.

Professional Trainings & Projects
======
* Graduate Studies Projects, Johns Hopkins University (Aug 2025 – Present)
  * Machine Learning for Signal Processing: Accent ID — Interpretable Accent Recognition with Phonetic Attribution
  * Wavelets & Filter Banks: Wavelet Top-K Front-End for CNN and ViT on CIFAR-10
  * Random Signal Analysis: Adaptive Filtering–based time series prediction on financial stock data
  * Dynamics & Control of Modern Power Systems: PLL Bandwidth Tuning for Grid-Following Inverters in Weak Microgrids
  * Information Extraction: HMM language modeling, HMM-based speech recognition, CTC/HuBERT end-to-end ASR
  * Topics in Machine Learning-Augmented Algorithm Design: Cost-Aware Advice Renewal in Non-Stationary Bandits
  * Ultrasound and Photoacoustic Beamforming: Physics-Informed AI for Microbubble Localization
* Exchange Studies Projects, University of California, Irvine (Sep 2024 – Jun 2025)
  * Data Analytics: Music Recommendation System with K-Means clustering on audio features
  * Descriptive Analytics & Visualization: Data-driven Analysis of California Housing Prices
  * Prescriptive Analytics: Soccer team optimization model using FIFA 18 player statistics
  * Predictive Analytics: Student Performance Prediction Model using supervised machine learning
  * Business Analytics: Electric Vehicle Adoption Trends Analysis in the United States
* Undergraduate Projects, Shandong University of Science and Technology (Sep 2021 – Jun 2025)
  * Internet of Things: "Cloud Farm" — Smart Agricultural Management System
  * Java Web Online Shopping Platform: front- and back-end development with Docker containerization
  * Software Engineering: Smart Agriculture E-Commerce Trading Platform
  * Database System Development: Easy-Go Travel Service Platform
  * Software Defined Network: Virtual Network Topology and Traffic Monitor in Ubuntu

Skills & Interests
======
* Technological Skills: C, Java, MATLAB, Python, Adobe, SQL, Microsoft Office, HTML, PyTorch, Tableau, KNIME, LaTeX
* Interests: Natural Language Processing, Expressive Speech Generation, Signal Processing, Multimodal Learning, Optimization Algorithms, Image Encryption, Artificial Intelligence, Machine Learning, Deep Learning, Emotional Analysis, Industry Application
