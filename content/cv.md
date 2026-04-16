---
title: CV
showDate: false
showAuthor: false
layout: "profile"
showTableOfContents: true
showReadingTime: false
baseURL: "https://jorgesintes.dev/cv/"
runtimeDownloads:
  - path: /files/jorge-sintes-cv.pdf
    label: Open CV as PDF
---

## Experience

{{< company_title companyName="Grazper Technologies" url="https://www.grazper.com" logoLight="/company_logos/grazper_logo_light.svg" logoDark="/company_logos/grazper_logo_dark.svg" >}}

{{< position title="Machine Learning Software developer" duration="04/2023 - Present" >}}

- Led the redesign of a legacy multi-camera annotation tool into a modern **FastAPI + Vue** web application
  tailored to Grazper's large-scale **3D computer vision datasets**, enabling **~10 internal annotators** to
  work efficiently through a novel **3D-first interaction model** for pose correction and review.

- Collaborated on fine-tuning **Ultralytics YOLO 2D pose-estimation models** on Grazper's in-house
  multi-camera datasets, including dataset preparation, experiment iteration, augmentation improvements, and
  evaluation of subsequent training directions.

- Co-designed and built an **auto-annotation pipeline** that converted **2D pose-estimation outputs** into
  track-consistent **3D annotations** using triangulation and **Kalman-filter smoothing**, reducing manual
  work and improving throughput in production annotation workflows.

- Led the company's **migration from Gitea to GitHub**, establishing reproducible CI/CD workflows on
  containerized **self-hosted GitHub runners** for privacy-sensitive dataset and model pipelines. Check out
  [this post](/posts/self_hosted_github_runners) for more details.

- Deployed and maintained core internal platform infrastructure, including a **self-hosted package registry**,
  **Prometheus + Grafana** for observability, and **MLflow** for experiment tracking and model deployment
  workflows.

- Built a speech-driven internal prototype during a company hackathon, using voice segmentation,
  speech-to-text, and an internal **MCP** server to expose Grazper product commands to a local language-model
  agent.

{{< position title="Master Thesis Student" duration="07/2022 - 02/2023" >}}

- Researched methods to **improve 3D human pose estimation** using IoT sole-pressure sensors.

- Designed a supervised model predicting pressure signals to **attempt monocular 3D pose estimation without
  physical sensors**.

- Master's thesis:
  [Guiding 3D Human Pose Estimation using Feet Pressure Sensors](https://jorgesintes.dev/files/jorge-sintes-master-thesis.pdf).

{{< company_title companyName="Novo Nordisk" url="https://www.novonordisk.com" logoLight="/company_logos/novo_nordisk_logo.svg" logoDark="/company_logos/novo_nordisk_logo.svg" >}}

{{< position title="Data Science Student" duration="06/2021 - 07/2022" >}}

- Performed **data processing, statistical analysis, and visualization** for the HR department of Novo
  Nordisk's largest production site.
- Built automated workflows for **data collection, cleaning, and reporting**, improving the reliability and
  usability of HR data for recurring operational follow-up.
- Developed dashboards and forecasting tools that helped **non-technical stakeholders** monitor workforce
  trends and planning needs.

{{< company_title companyName="DTU" url="https://www.dtu.dk" logoLight="/company_logos/dtu_logo_light.png" logoDark="/company_logos/dtu_logo_light.png" >}}
{{< position title="Teaching Assistant" duration="02/2021 - 06/2021" >}}

- Assisted teaching the course **02450 -- Introduction to Machine Learning and Data Mining**.
- Supervised weekly labs for **40+ students** and evaluated course projects.

## Technical Skills

{{< icontitle iconClass="fa-solid fa-terminal" title="Languages" >}}

{{< multicolumnlist >}}

- **Python**
- **TypeScript/JavaScript**
- Bash
- C/C++
- HTML/CSS
- LaTeX
- Matlab {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-server" title="Backend / APIs" >}}

{{< multicolumnlist >}}

- **FastAPI**
- **Pydantic**
- SQLAlchemy
- Alembic
- Flask
- WebSockets {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-database" title="Databases" >}}

{{< multicolumnlist >}}

- **PostgreSQL**
- SQL
- Data modeling
- DB migrations {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-circle-nodes" title="Machine learning" >}}

{{< multicolumnlist >}}

- **PyTorch**
- **PyTorch Lightning**
- Ultralytics
- YOLO
- MLOps
- MLflow
- OpenCV
- Scikit-learn
- FiftyOne
- Ollama {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-microchip" title="Numerical" >}}

{{< multicolumnlist >}}

- **NumPy**
- Autograd
- SciPy {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-cubes" title="Infrastructure / DevOps" >}}

{{< multicolumnlist >}}

- **Docker**
- **Git**
- **GitHub Actions**
- self-hosted runners
- Linux
- Gitea (packages)
- Vim {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-shield-halved" title="Observability / Auth" >}}

{{< multicolumnlist >}}

- **Prometheus**
- **Grafana**
- Microsoft Entra ID
- OpenID Connect
- OAuth 2.0 {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-chart-line" title="Data viz" >}}

{{< multicolumnlist >}}

- **Pandas**
- Matplotlib
- Plotly/Dash {{< /multicolumnlist >}}

{{< icontitle iconClass="fa-solid fa-palette" title="Frontend" >}}

{{< multicolumnlist >}}

- **Vue**
- **Hugo**
- Pinia
- Three.js {{< /multicolumnlist >}}

---

## Projects

Here are some of the projects I've done in the past or I'm currently doing now:

- [PureGym MCP](https://puregym-mcp.jorgesintes.dev/) \
  Built a Python client and MCP server for PureGym by reverse-engineering the app's internal API and turning
  it into a reusable automation layer. It provides an MCP interface for class search, booking management, live
  center status, and opening hours for LLM clients and other agent tools.

- [PureGym Telegram Bot](https://github.com/JorgeSintes/puregym-bot) \
  Built on top of the PureGym client above to automate bookings, send reminders, and manage classes from
  Telegram.

- [ScaleGuru](https://scaleguru.jorgesintes.dev/) \
  A web tool for practicing musical scales and keys, designed for daily use in my own music practice. Built
  with **TypeScript**, with ear-training and visualization features for structured instrument practice.
- [Bayesian Methods for Electroencephalogram (EEG) Decoding](https://github.com/JorgeSintes/CNN_EEG_signals) \
  Implementing and comparing the performance of different Bayesian Neural Networks
  (Ensembles/SWA/SWAG/MultiSWAG) with state-of-the-art deep learning techniques in the task of classifying EEG
  readings while the test subjects imagines performing a task.
- [Time Series Anomaly Detection with Variational AutoEncoder and GRU](https://github.com/JorgeSintes/Advanced_Machine_Learning)
  \
  Research project for DTU's Advanced Machine Learning course exploring ways of combining VAEs with RNNs to
  detect anomalies in real-world time-series data from vehicle telemetry, including the design and training of
  novel hybrid architectures. Read the paper [here](/files/time-series-anomaly-detection-vae-gru.pdf).

---

## Education

- [MSc in Mathematical Modelling and Computation](https://www.dtu.dk/english/education/graduate/msc-programmes/mathematical-modelling-and-computation)
  at [Technical University of Denmark (DTU)](https://www.dtu.dk/): _09/2020 - 02/2023_\
  Graduate studies focused on machine learning, mathematical modelling, and scientific computing, with
  relevant work in deep learning, Bayesian machine learning, algorithms and data structures, high-performance
  computing, optimization, and stochastic processes.

- [BSc + MSc in General Engineering](https://www.upv.es/titulaciones/MUII/index-en.html) at
  [UPV](https://www.upv.es/): _09/2015 - 07/2020_\
  Broad engineering education spanning mathematics, physics, electronics, mechanics, control systems, and
  computation, providing a strong foundation for interdisciplinary software and machine learning work.

---

## About Me

{{< icontitle iconClass="fa-solid fa-music" title="Music" >}}

I play trombone in orchestras, jazz ensembles, and modern music bands. For me, music is about sharing
something I love with other people, and staying creative through improvisation.

{{< icontitle iconClass="fa-solid fa-person-running" title="Sports" >}}

I stay active through running, cycling, strength training, and occasional bouldering, mainly to stay healthy,
challenge myself and enjoy the social side of training.

{{< icontitle iconClass="fa-solid fa-language" title="Languages" >}}

Spanish and Catalan (native), English (professional).

{{< icontitle iconClass="fa-solid fa-address-card" title="References" >}}

Available upon request.
