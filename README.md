<div align="center">
### Machine Learning Engineering · End-to-End ML Systems
 
Data → features → model → served API. I build ML pipelines that go past the notebook.
 
[![GitHub](https://img.shields.io/badge/GitHub-Ahmed77923-181717?style=flat-square&logo=github)](https://github.com/Ahmed77923)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/ahmed-alsafi-444a983ab/)
 
</div>
---
 
### About
 
Data science background, currently focused on machine learning engineering — the part of ML that happens after the model works in a notebook: pipelines, tracking, serving, and testing. My projects run from raw data through a served prediction API, not just to a validation score.
 
I'm also building toward deep learning and computer vision, and I'd rather show that honestly as "in progress" than list frameworks I haven't shipped anything with yet.
 
### Currently
 
- Deepening machine learning engineering: pipeline design, experiment tracking, model serving
- Working through the fundamentals of neural networks (see `NumPyNet` below) before moving to PyTorch
- Next up: a real computer vision project — image classification with a proper CNN, not just a script
---
 
### Tech Stack
 
Only what's demonstrated in the projects below.
 
**Languages & Data**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
 
**Machine Learning**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square)
 
**Serving & MLOps**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
 
**Testing & Tools**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
 
---
 
### Featured Projects
 
**[Flight Delay Prediction](https://github.com/Ahmed77923/flight_delay_prediction)**
End-to-end regression system predicting arrival delay in minutes from pre-departure flight data. LightGBM model trained on a chronological 80/20 split (no leakage), tracked with MLflow, served through a FastAPI endpoint with Pydantic-validated requests, with a Streamlit client on top. Containerized with Docker Compose (separate API + UI services, health-checked). Backed by a pytest suite covering the API, feature engineering, and a custom target encoder.
`Python` `LightGBM` `scikit-learn` `MLflow` `FastAPI` `Streamlit` `Docker` `pytest`
 
**[Auto-ML System](https://github.com/Ahmed77923/Auto-ML-System)**
A modular AutoML pipeline: automatic classification/regression detection, a pipeline-based preprocessing stage (no leakage), a model registry for swapping algorithms, MLflow experiment tracking, and a Streamlit UI for upload → train → download. Built with a clear separation of concerns across config, data, training, and evaluation modules.
`Python` `scikit-learn` `MLflow` `Streamlit`
 
**[NumPyNet](https://github.com/Ahmed77923/NumPyNet)**
A feed-forward neural network library built from scratch in NumPy — dense layers, forward/backward propagation, four optimizers (SGD, Momentum, RMSProp, Adam), He/Xavier initialization, L1/L2 regularization, and classification metrics, wrapped in a Streamlit training demo. Built to understand what deep learning frameworks abstract away before relying on them.
`Python` `NumPy` `Streamlit`
 
**[Fraud Detection ML System](https://github.com/Ahmed77923/Fraud-Detection-ML-System)**
Early-stage pipeline for fraud detection: preprocessing, feature engineering, class-imbalance handling, and a FastAPI inference layer with a test file in place. Structure is solid; still needs a finished training run and reported metrics.
`Python` `scikit-learn` `FastAPI`
 
---
 
### GitHub Activity
 
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ahmed77923&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ahmed77923&layout=compact&theme=default&hide_border=true" />
</p>
---
 
<div align="center">
<sub>Building toward AI engineering, one shipped project at a time.</sub>
</div>
 
