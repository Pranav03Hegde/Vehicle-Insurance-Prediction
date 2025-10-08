# 🚗 Vehicle Insurance Data & MLOps Cloud Pipeline

An end-to-end **machine learning pipeline** designed to automate the lifecycle of vehicle insurance risk prediction — from data ingestion to real-time deployment.  
This project demonstrates complete **MLOps workflow** integration using AWS, Docker, and CI/CD pipelines.

---

## ⚙️ Tech Stack

**Languages:** Python, SQL  
**Frameworks:** FastAPI, Scikit-learn  
**Cloud & DevOps:** AWS (EC2, S3, IAM), Docker, GitHub Actions  
**Database:** MongoDB Atlas  
**Tools:** Pandas, NumPy, joblib  

---

## 🧠 Project Overview

1. **Data Engineering**
   - Collected and preprocessed vehicle insurance datasets.
   - Stored data securely in **MongoDB Atlas** with schema validation.

2. **Model Development**
   - Built regression/classification model for risk prediction.
   - Tracked experiments and stored model versions using **AWS S3**.

3. **MLOps Automation**
   - Integrated **Docker** containers for environment consistency.
   - Used **GitHub Actions** for automated CI/CD and model deployment.

4. **Cloud Deployment**
   - Deployed the FastAPI-based prediction API on **AWS EC2**.
   - Supports scalable, real-time inference for multiple clients.

---

## 🧩 Pipeline Architecture

Data Ingestion → Preprocessing → Model Training → Model Registry (S3)
↓ ↓ ↓
MongoDB Feature Store Docker Image Build
↓ ↓
API Deployment (FastAPI) ← CI/CD (GitHub Actions + AWS EC2)

---

## 🧾 Results

- Achieved **87% accuracy** in insurance claim risk prediction.  
- Automated training → testing → deployment pipeline with zero manual steps.  
- Endpoints serve real-time predictions within **<200ms latency**.

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/Pranav03Hegde/Vehicle-Insurance-MLPipeline.git
cd Vehicle-Insurance-MLPipeline
pip install -r requirements.txt
python app.py
