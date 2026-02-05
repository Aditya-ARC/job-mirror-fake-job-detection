🚀 Job Mirror — Fake Job Posting Detection (ML + Cloud)

Job Mirror is a production-ready machine learning web application that detects fake job postings in real time using NLP, XGBoost, and cloud-based logging.

It combines machine learning, explainability, and full cloud deployment to help job seekers identify suspicious job listings and understand why they may be fraudulent.

🔗 Live Demo:
https://job-mirror-fake-job-detection-5bqj5wb3hefcfe6vdoeeyg.streamlit.app/ 
<img width="1920" height="997" alt="image" src="https://github.com/user-attachments/assets/e5fcb65e-6c85-401a-96ed-8aed6bf5322f" />


💡 What This Project Demonstrates

End-to-end ML system design

Real-time model inference in production

Secure cloud deployment

Database-backed logging & analytics

Clean, user-friendly web interface

This project mirrors how ML systems are built and deployed in real-world industry settings.

🧠 Key Capabilities

🔍 Fake vs Real job classification

📊 Probability scores (Fake / Real)

🧩 Explainability engine highlighting red flags

🧠 NLP preprocessing using TF-IDF

☁️ Cloud logging with Supabase (PostgreSQL)

🔐 Secure secrets & access control

🛠️ Tech Stack

Machine Learning

Python

XGBoost

Scikit-learn

TF-IDF Vectorization

Feature Engineering (text + categorical + boolean)

Web & Cloud

Streamlit (UI + backend runtime)

Streamlit Cloud (deployment)

Supabase (PostgreSQL)

REST APIs

Row Level Security (RLS)

Engineering Practices

Modular architecture

Model artifact versioning

Secure secret management

GitHub version control 

🏗️ Architecture Overview 
User Input (Streamlit UI)
        ↓
Preprocessing Pipeline (TF-IDF + Encoders)
        ↓
XGBoost Model Inference
        ↓
Explainability Rules Engine
        ↓
Prediction + Reasons
        ↓
Supabase (PostgreSQL Logging)

🗄️ Data & Logging

Every prediction is logged to a PostgreSQL database with:

Job input fields

Prediction label (FAKE / REAL)

Fraud probabilities

Explanation reasons

Auto-generated UUID

Auto-generated timestamp

This enables:

Auditing

Model monitoring

Future retraining pipelines

📸 Application Preview

Job Input Interface
(Streamlit UI for entering job details)

Prediction Result
(Fraud label, probabilities, and red-flag explanations)

Cloud Database Logs
(Predictions stored in Supabase PostgreSQL)

📌 Screenshots available in the repository for full walkthrough.

🚀 Deployment

Hosted on Streamlit Cloud

Supabase credentials stored securely using Streamlit Secrets

Fully serverless deployment

No local setup required for users


