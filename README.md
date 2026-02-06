# 🚀 SurgeStream-ML: Intelligent Dynamic Pricing Engine

**SurgeStream-ML** is a high-performance pricing engine designed to solve the supply-demand imbalance in urban mobility. Built using the Boston Uber/Lyft dataset, this project implements a **Multi-Model Inference Pipeline** to predict fares, surge multipliers, and demand in real-time.

![Status](https://img.shields.io)
![Tech](https://img.shields.io)

---

## 🎯 Project Overview
The goal is to build an Uber-like engine that doesn't just predict price, but optimizes it. The system answers:
- "How much should the price increase during heavy rain at North Station?"
- "What is the probability of a user accepting a 2.0x surge?"

## 🏗️ System Architecture (The Multi-Model Approach)
This project is not just one model, but a pipeline of **4 specialized AI models**:
1. **Demand Forecaster (XGBoost):** Predicts trip volume for a given hour/location.
2. **Surge Estimator (LightGBM):** Calculates the optimal surge multiplier.
3. **ETA Predictor (Random Forest):** Estimates arrival time considering weather.
4. **Acceptance Model (Logistic Regression):** Predicts price sensitivity of the user.

---

## 🛠️ Tech Stack
- **Languages:** Python (3.10+)
- **Libraries:** Pandas, Scikit-Learn, XGBoost, LightGBM
- **Deployment:** FastAPI, Docker (Planned)
- **Monitoring:** MLflow (Planned)
- **Frontend:** Streamlit Dashboard

## 📂 Project Roadmap
- [x] **Day 1:** Repository Setup & Initial Data Analysis.
- [ ] **Day 2-3:** Feature Engineering (Cyclical Encoding & Discomfort Index).
- [ ] **Day 4-6:** Multi-Model Training & Optimization.
- [ ] **Day 7-9:** API Integration with FastAPI.
- [ ] **Day 10:** Final Deployment & Killer Portfolio Documentation.

---

## 🚀 How to Run
*Instructions will be updated as the project progresses.*

1. Clone the repo: `git clone https://github.com`
2. Install requirements: `pip install -r requirements.txt`
