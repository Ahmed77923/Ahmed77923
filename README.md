<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=2800&pause=1200&color=4FA8FF&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Ahmed+Alsafi;Machine+Learning+Engineer;I+build+end-to-end+ML+systems" alt="Typing SVG" />
<br/>
<sub><b>DATA SCIENCE • MACHINE LEARNING • MLOPS</b></sub>
 
<h3>Building practical machine learning systems<br/>from data to deployment.</h3>
 
<a href="https://github.com/Ahmed77923?tab=repositories">
  <img src="https://img.shields.io/badge/View_My_Work-4FA8FF?style=for-the-badge&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/ahmed-alsafi-444a983ab/">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
</div>
<br/>
<table width="100%">
<tr>
<td width="50%" valign="top">
### 🧠 About Me
 
Data science background, now focused on **machine learning engineering** — the part of ML that starts after the model works in a notebook.
 
I build pipelines that go from raw data through feature engineering, tracked training runs, and a served prediction API — with tests around the parts that matter. My strongest project (`flight_delay_prediction`) runs the full loop: LightGBM → MLflow → FastAPI → Docker.
 
I'm working through deep learning fundamentals from first principles (see `NumPyNet`) before relying on frameworks, and computer vision is next on the list — not yet a finished project, so it isn't listed as a skill here.
 
</td>
<td width="50%" valign="top">
### 🎯 Current Focus
 
```text
⚙️  ML Pipeline Engineering
🧪  Experiment Tracking (MLflow)
🚀  Model Serving (FastAPI + Docker)
🧮  Neural Nets from Scratch (NumPy)
📚  Next: Computer Vision (CNNs, PyTorch)
```
 
<sub>Each line above is backed by a shipped repository below — nothing here is aspirational except the last one, which is labeled as such.</sub>
 
</td>
</tr>
</table>
---
 
### 🛠️ Tech Stack
 
<table width="100%">
<tr>
<td valign="top">
**Languages & Data**
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
 
</td>
<td valign="top">
**Machine Learning**
<br/>
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square)
 
</td>
<td valign="top">
**MLOps & Serving**
<br/>
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
 
</td>
<td valign="top">
**Testing & Tools**
<br/>
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
 
</td>
</tr>
</table>
<sub>Not listed: PyTorch, OpenCV, CUDA, PostgreSQL, Prometheus/Grafana — none are backed by a finished project yet, so they're left off rather than implied.</sub>
 
---
 
### 🚀 Featured Projects
 
<table width="100%">
<tr>
<td width="50%" valign="top">
#### ✈️ Flight Delay Prediction
 
End-to-end regression system predicting arrival delay in minutes. LightGBM on a chronological 80/20 split, MLflow experiment tracking, FastAPI inference service with validated request schemas, Streamlit client, Dockerized with health-checked services, pytest coverage on the API and feature pipeline.
 
`Python` `LightGBM` `MLflow` `FastAPI` `Docker` `pytest`
 
**[View Repository →](https://github.com/Ahmed77923/flight_delay_prediction)**
 
</td>
<td width="50%" valign="top">
#### 🤖 AutoML System
 
Modular pipeline that auto-detects classification vs. regression, trains through a model registry, tracks runs with MLflow, and ships a Streamlit UI for upload → train → download. Pipeline-first design avoids data leakage.
 
`Python` `scikit-learn` `MLflow` `Streamlit`
 
**[View Repository →](https://github.com/Ahmed77923/Auto-ML-System)**
 
</td>
</tr>
<tr>
<td width="50%" valign="top">
#### 🧮 NumPyNet
 
A feed-forward neural network library built from scratch in NumPy — dense layers, manual backprop, four optimizers (SGD, Momentum, RMSProp, Adam), He/Xavier init, L1/L2 regularization — with a Streamlit training demo on top.
 
`Python` `NumPy` `Streamlit`
 
**[View Repository →](https://github.com/Ahmed77923/NumPyNet)**
 
</td>
<td width="50%" valign="top">
#### 🔍 Fraud Detection ML System
 
Preprocessing, feature engineering, class-imbalance handling, and a FastAPI inference layer with a test file in place. Early-stage — structure is solid, a finished training run and reported metrics are next.
 
`Python` `scikit-learn` `FastAPI`
 
**[View Repository →](https://github.com/Ahmed77923/Fraud-Detection-ML-System)**
 
</td>
</tr>
</table>
---
 
### 🔄 End-to-End ML Pipeline
 
The shape this actually takes in `flight_delay_prediction`, my most complete project:
 
```text
  Data              Feature Eng.         Model Training        Tracking
┌─────────┐        ┌─────────────┐      ┌───────────────┐    ┌─────────┐
│ Pandas  │  ───▶  │ scikit-learn│ ───▶ │   LightGBM    │───▶│ MLflow  │
└─────────┘        └─────────────┘      └───────────────┘    └────┬────┘
                                                                    │
                                                                    ▼
                                ┌──────────┐         ┌──────────────┐
                                │  Docker  │  ◀────  │   FastAPI    │
                                └──────────┘         └──────────────┘
```
 
<sub>Monitoring (Prometheus/Grafana) exists as a folder in that repo but isn't wired up per its own documentation — it's on the improvement list below, not shown here as done.</sub>
 
---
 
### 📊 GitHub Statistics
 
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ahmed77923&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ahmed77923&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Ahmed77923&theme=tokyonight&hide_border=true&background=0d1117" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg" />
</p>
---
 
<div align="center">
**[GitHub](https://github.com/Ahmed77923)** · **[LinkedIn](https://www.linkedin.com/in/ahmed-alsafi-444a983ab/)**
 
<sub>Always building, always shipping the next stage of the pipeline.</sub>
 
</div>
 
