

[![MasterHead](https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif)](https://github.com/dpnsu)

<h1 align="center">Hi there 👋, I'm Deepanshu</h1>
<h3 align="center">Machine Learning Engineer @ Rechk | Responsible AI & Governance | Building Production-Grade ML Systems</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=dpnsu&label=Profile%20views&color=0e75b6&style=flat" alt="dpnsu" />
</p>

<div align="center">
  
[![Email](https://img.shields.io/badge/Email-deepanshusnpt%40gmail.com-red?style=for-the-badge&logo=gmail)](mailto:deepanshusnpt@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/deepanshu-shimar-704633256)
[![Medium](https://img.shields.io/badge/Medium-Follow-black?style=for-the-badge&logo=medium)](https://medium.com/@deepanshusnpt)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-orange?style=for-the-badge&logo=leetcode)](https://leetcode.com/deepanshusnpt)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--7709--7095-green?style=for-the-badge&logo=orcid)](https://orcid.org/0009-0005-7709-7095)

</div>

<br>

## 🚀 About Me

<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif"/>

I'm a **Machine Learning Engineer at Rechk** and a **B.Tech graduate in Computer Science (AI & ML)** from UIET, MDU, working at the intersection of **AI systems and AI governance**. I build production-grade ML systems (NLP, LLMs, multimodal) with hands-on experience in **Responsible AI** — fairness testing, explainability, model cards, and policy-aligned auditing.

- 🔭 Currently building a **research-paper intelligence platform** at Rechk (BERT + LLM agents, FastAPI, Docker)
- ⚖️ Built a **Responsible AI audit framework** for credit-scoring models aligned with **RBI FREE-AI, NITI Aayog RAI & DPDP**
- 🔬 Prior experience: **Research Intern @ NIT Warangal** | **ML Intern @ DRDO**
- 🏆 **Microsoft Learn Student Ambassador** | **Top-60 Healthcare AI Hackathon Finalist**
- 📝 Published researcher with **2 ML research papers** on degradation prediction
- 💬 Ask me about **PyTorch, LangChain, RAG Systems, Fairlearn, SHAP, MLOps, LLMs**
- 📫 Reach me at **deepanshusnpt@gmail.com**
- ⚡ Fun fact: **I build production ML systems that solve real-world problems!**

<br clear="right"/>

---

## 💼 Professional Experience

### 🤖 Machine Learning Engineer | Rechk
**Jan 2026 - Present | Remote**
- 📄 Built and fine-tuned the core **BERT model** of a research-paper intelligence platform classifying papers into **5 journal-quality tiers (Q1–Q4 + Non-Publishable)** across **1,350+ papers**: **82.4% accuracy, macro F1 0.827, ROC-AUC 0.946**
- 🏗️ Architected the full pipeline — ingestion → BERT classification → **Gemini 3.5 Flash grammar agent** in parallel with plagiarism detection → merged dashboard with PDF reports
- 🚀 Deployed as a **FastAPI REST API**, Dockerized for one-command deployment

### 🔬 Research Intern | NIT Warangal
**Aug 2025 - Dec 2025 | Remote**
- 🌾 Forecasted crop yields for **572 Indian districts** using NASA POWER, MODIS & SoilGrids (**35 features**)
- 📊 Best model: **LightGBM (R² = 0.906, MAE = 17.65 kg/ha)** — **40× faster** than Deep NN
- 🎯 Identified historical crop yield as dominant predictive feature via **SHAP-based feature importance** for model transparency and accountability

### 🛡️ ML Intern | Defence Research and Development Organisation (DRDO)
**June 2025 - Aug 2025 | Delhi, India**
- 🧪 Trained **6 ML classifiers** for **toxic gas classification** on multi-sensor chemical readings
- 🏆 Best model: **XGBoost (95.02% accuracy, ROC-AUC = 0.9965)**
- 🚀 Exported models in **.pkl & .onnx** formats for real-time deployment on **drones and embedded field systems**

---

## 🏗️ Featured Projects

### ⚖️ Responsible AI Audit Framework for Credit Scoring — [Live Demo (HF Space)](https://huggingface.co/spaces/JARVIS-JI/responsible-ai-audit)
**Tech Stack:** Python, Fairlearn, SHAP, XGBoost, Streamlit

- 🏛️ Built an end-to-end **AI governance pipeline** auditing credit-scoring models for **fairness** (disparate impact, equal opportunity, intersectional sex×age), **explainability** (SHAP), robustness, and proxy bias
- 📋 Converts findings into a **mechanical risk rating** from config-defined policy thresholds, **auto-generated model cards**, and regulator-readable reports mapped to **RBI FREE-AI** and **NITI Aayog** principles
- 📊 Benchmarked **20 public model families on 30,000 real credit records** (UCI Taiwan) under one governance standard; found model choice alone changes approval outcomes for **22% of applicants**, and a standard bias-mitigation method **widened** the fairness gap on held-out data — evidence that mitigation must be audited, not assumed
- 🔒 Interactive HF Space: live threshold-to-risk-rating re-derivation, 20-model applicant scoring with **SHAP-based adverse-action notices**; protected attributes excluded from model inputs (**DPDP-aligned**)

### ⚖️ [IPC & BNS Predictor](https://huggingface.co/spaces/JARVIS-JI/IPCBNSPredictorRAG-basedLegalAISystem) - RAG-based Legal AI System
**Tech Stack:** LangChain, FAISS, RAG, Gemini 3.5 Flash, HuggingFace

- 🎯 Built a legal/regulatory AI system (**LangChain + FAISS RAG**) mapping FIRs to **500+ IPC & 350+ BNS** sections at **92% accuracy**, powered by **Gemini 3.5 Flash** for inference
- ⚡ Reduced manual review time by **60%** and response times by **40%** for law enforcement
- 🚀 Deployed on **HuggingFace Spaces**; automated legal classification from official government PDFs

### 🥔 [Potato Disease Detection]() - Transformer Benchmarking
**Tech Stack:** Python, Transformers, Swin, MobileViT, FastAPI, Streamlit

- 🔬 Benchmarked **7 transformer models** on 717 leaf images (5-fold CV): **97% accuracy (Swin)**, **94.86% with lightweight MobileViT (5.6M params)**
- 🔍 Applied **Grad-CAM** for interpretability; deployed **FastAPI backend + Streamlit UI**

### 🛒 [Amazon ML Challenge 2025](https://github.com/dpnsu/AML2025) - Multimodal Price Prediction
**Tech Stack:** PyTorch, Qwen3, DINOv2

- 🧠 Designed **cross-attention fusion** between **Qwen3 (text)** and **DINOv2 (vision)** encoders
- 🏅 **SMAPE 50–52%, Top 1200 national rank** via 5-fold CV and ensemble stacking

### 🏥 [Insight Onco](https://synapse-gules.vercel.app/) - AI Healthcare System
**Jan 2025 - Feb 2025 | Tech Stack:** CNN, PyTorch, Computer Vision, GDPR/HIPAA

- 🎯 Built **computer vision system** for cancer detection achieving **92% classification accuracy**
- 🔒 Implemented **secure model serving** infrastructure with **GDPR & HIPAA-compliant** deployment
- 🏆 Secured **Top-60 position (Semi-Finalist)** in Predictive AI in Healthcare with FHIR® International Hackathon
- 📉 Reduced data breach risk by **30%** through enhanced security measures

⚠️ **Note:** Some advanced ML projects are in private repositories, undergoing research validation and production optimization! 🚀

---

## 📚 Research Publications

<img align="right" alt="Research" width="300" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif"/>

1. **📄 Solar Panel Degradation Prediction using Machine Learning: A Comprehensive Approach** 
   - Status: Preprint | [Read Paper](https://www.researchsquare.com/article/rs-6297947/v1) | [GitHub Repo](https://github.com/dpnsu/Solar-Panel-Degradation-Predictor)
   - Machine learning models for predictive maintenance of solar energy systems

2. **⚡ Fuel Cell Degradation Prediction Using Machine Learning Models** 
   - Focus: Proton Exchange Membrane (PEM) Fuel Cell Dataset
   - Status: Preprint | [Read Paper](https://www.researchgate.net/publication/392034748_Fuel_Cell_Degradation_Prediction_Using_Machine_Learning_Models_A_Study_on_Proton_Exchange_Membrane_PEM_Fuel_Cell_Dataset) | [GitHub Repo](https://github.com/dpnsu/Fuel-cell-degradation-predictor)
   - Advanced ML techniques for fuel cell lifecycle prediction

<br clear="right"/>

---

## 🛠️ Technical Arsenal

<h3 align="left">Programming Languages:</h3>
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cpp" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="45" height="45"/>
</p>

<h3 align="left">AI/ML & Deep Learning:</h3>
<p align="left">
  <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="45" height="45"/>
  <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="45" height="45"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit-learn" width="45" height="45"/>
  <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" alt="numpy" width="45" height="45"/>
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="45" height="45"/>
</p>

<h3 align="left">NLP & LLMs:</h3>
<p align="left">
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="45" height="45"/>
  <img src="https://www.vectorlogo.zone/logos/langchain/langchain-icon.svg" alt="langchain" width="45" height="45"/>
</p>

<h3 align="left">Databases & Cloud:</h3>
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="45" height="45"/>
  <img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-icon.svg" alt="aws" width="45" height="45"/>
  <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="45" height="45"/>
  <img src="https://www.vectorlogo.zone/logos/docker/docker-icon.svg" alt="docker" width="45" height="45"/>
</p>

<h3 align="left">Tools & Version Control:</h3>
<p align="left">
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="45" height="45"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="45" height="45"/>
</p>

### 🎯 Core Competencies

<table>
<tr>
<td width="50%">

**Deep Learning & Computer Vision**
- CNNs, Transformers, Vision Transformers (ViT)
- RoBERTa, BERT, Sentence-BERT
- Image Classification & Feature Extraction
- Object Detection & Segmentation

</td>
<td width="50%">

**NLP & Large Language Models**
- LangChain, LangSmith, FAISS
- RAG Systems & Vector Databases
- Transformers, Sentence-BERT, LLaMA, Gemini 3.5 Flash
- Prompt Engineering & Model Optimization

</td>
</tr>
<tr>
<td width="50%">

**Responsible AI & Governance**
- Fairlearn, SHAP, Model Cards
- Fairness Metrics (Disparate Impact, Equalized Odds)
- Bias Mitigation & Proxy Bias Auditing
- AI Policy: RBI FREE-AI, NITI Aayog RAI, DPDP Act, EU AI Act

</td>
<td width="50%">

**Multimodal & Computer Vision**
- Vision Transformers (Swin, MobileViT, DINOv2)
- Cross-Attention Multimodal Fusion
- Grad-CAM Interpretability
- Image Classification & Feature Extraction

</td>
</tr>
<tr>
<td width="50%">

**MLOps & Deployment**
- Model Serving & REST APIs
- Docker & Cloud Deployment (AWS, GCP)
- Hugging Face Inference Endpoints
- Low-latency Inference Optimization

</td>
<td width="50%">

**Data Science & ML Engineering**
- XGBoost, LightGBM, Ensemble Methods
- Feature Engineering & Selection
- Hyperparameter Tuning
- Production ML Pipeline Development

</td>
</tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">
  
![](https://github-readme-stats.vercel.app/api?username=dpnsu&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=dpnsu&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=dpnsu&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

</div>

---

## 🏆 Achievements & Recognition

- 🎖️ **Microsoft Learn Student Ambassador** - Recognized for technical leadership and community impact
- 🥈 **Top-60 Finalist** - Predictive AI in Healthcare with FHIR® International Hackathon (2025)
- 🛒 **Top 1200 National Rank** - Amazon ML Challenge 2025 (Multimodal Price Prediction)
- 📖 **Published Researcher** - 2 ML research papers (Solar Panel & Fuel Cell Degradation Prediction)
- 🔬 **Research Experience** - NIT Warangal & DRDO

---

## 🌱 Currently Working On

- 📄 **Research-Paper Intelligence Platform @ Rechk** - BERT classification, LLM agents, plagiarism detection, FastAPI + Docker
- ⚖️ **Responsible AI & Governance** - Fairness auditing, explainability, and policy-aligned model evaluation (RBI FREE-AI, NITI Aayog, DPDP, EU AI Act)
- 🚀 **Production ML Systems** - Scalable model deployment and MLOps best practices

---

## 💡 Random Dev Quote

![Dev Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

---

## 📫 Let's Connect!

I'm always interested in collaborating on ML/AI projects, research opportunities, and innovative tech solutions. Feel free to reach out!

<div align="center">

[![Email](https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail)](mailto:deepanshusnpt@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/deepanshu-shimar-704633256)
[![Medium](https://img.shields.io/badge/Medium-Read_My_Articles-black?style=for-the-badge&logo=medium)](https://medium.com/@deepanshusnpt)

![Profile Views](https://visitcount.itsvg.in/api?id=dpnsu&icon=5&color=12)

</div>
