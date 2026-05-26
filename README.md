# 🚀 Predictive Analytics & Insights API

A production-grade Machine Learning API built with **FastAPI**, **Scikit-learn**, and **MongoDB** that provides real-time predictive analytics through classification, regression, and anomaly detection endpoints. Designed for enterprise-scale workloads with secure multi-tenant access, model versioning, and optimized database performance.

---

## 📌 Overview

This project exposes ML-powered REST APIs that enable organizations to integrate predictive analytics directly into their applications. The system supports multiple machine learning workflows, automated feature engineering, and scalable model serving while maintaining low-latency responses.

### Key Highlights

- Classification, Regression, and Anomaly Detection APIs
- FastAPI-based high-performance REST architecture
- Automated feature engineering pipelines
- MongoDB aggregation optimization with compound indexing
- Sub-50ms query response times
- Role-Based Access Control (RBAC)
- Multi-tenant architecture
- Model versioning and lifecycle management
- GitHub Actions CI/CD integration

---

## 🏗️ Tech Stack

| Category | Technology |
|-----------|------------|
| Backend | FastAPI, Python |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Database | MongoDB |
| Authentication | JWT, RBAC |
| DevOps | GitHub Actions |
| API Docs | OpenAPI, Swagger UI |

---

## 📂 Project Structure

```text
Predictive-Analytics-Insights-API/
│
├── app/
│   ├── api/
│   ├── services/
│   ├── models/
│   ├── schemas/
│   └── utils/
│
├── ml/
│   ├── training/
│   ├── inference/
│   └── feature_engineering/
│
├── database/
├── tests/
├── .github/workflows/
├── requirements.txt
└── README.md
```

---

## ✨ Features

### 📊 Machine Learning Inference

- Classification Predictions
- Regression Forecasting
- Anomaly Detection & Scoring
- Batch and Real-Time Predictions

### ⚡ Performance Optimization

- MongoDB compound indexing
- Optimized aggregation pipelines
- Low-latency inference workflows
- Efficient data preprocessing

### 🔒 Security

- JWT Authentication
- Role-Based Access Control (RBAC)
- Multi-Tenant Data Isolation
- Secure API Access

### 🚀 DevOps & MLOps

- Model Versioning
- Automated CI/CD Pipelines
- GitHub Actions Integration
- Automated Testing Workflows

---

## 🎯 API Endpoints

### Classification

```http
POST /predict/classification
```

Predict categorical outcomes using trained classification models.

### Regression

```http
POST /predict/regression
```

Generate numerical predictions and forecasts.

### Anomaly Detection

```http
POST /predict/anomaly
```

Identify unusual patterns and outliers in incoming data.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/payalsinghz/Predictive-Analytics-Insights-API.git
cd Predictive-Analytics-Insights-API
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
uvicorn app.main:app --reload
```

---

## 📖 API Documentation

After starting the server:

### Swagger UI

```text
http://localhost:8000/docs
```

### ReDoc

```text
http://localhost:8000/redoc
```

---

## 📈 Example Use Cases

- Customer Churn Prediction
- Fraud Detection
- Demand Forecasting
- Predictive Maintenance
- Risk Assessment
- Business Intelligence Platforms
- Enterprise Analytics Solutions

---

## 🧪 Testing

Run all tests:

```bash
pytest
```

---

## 📊 Performance Metrics

- Sub-50ms optimized query response times
- FastAPI asynchronous request handling
- Scalable ML inference architecture
- Efficient MongoDB aggregation pipelines

---

## 🔮 Future Enhancements

- Docker & Kubernetes Deployment
- Real-Time Streaming Analytics
- Explainable AI (XAI)
- Automated Model Retraining
- Monitoring & Observability Dashboard

---

## 👩‍💻 Author

**Payal Singh**

GitHub: https://github.com/payalsinghz

---

## ⭐ Support

If you find this project useful, consider giving it a **Star ⭐** on GitHub.