# GovShield: AI-Powered Fraud Intelligence System

## 🚀 Overview
GovShield is an interactive fraud detection platform built to protect the Ayushman Bharat scheme. It uses a custom-weighted Machine Learning heuristic engine to identify, explain, and simulate healthcare fraud in real-time.

## 🛠️ System Architecture
- **Engine:** JavaScript-based Weighted Random Forest emulation.
- **Frontend:** Tailwind CSS with Glassmorphism (Government Intelligence UI).
- **Analytics:** Chart.js for anomaly detection and hospital benchmarking.
- **Data Handling:** PapaParse for dynamic CSV ingestion and processing.

## 🧠 Key Logic Components
1. **Heuristic Model:** Processes 8 key features (Inflation Ratio, Submission Count, etc.) to generate a 0-100 Risk Score.
2. **Explainable AI (XAI):** Decomposes every score into specific "Impact Factors" so investigators understand the "Why" behind the "Flag."
3. **What-If Simulator:** Allows real-time "Feature Perturbation"—changing claim variables to see how the model's risk assessment shifts.

## 📥 Setup Instructions
1. Extract the folder.
2. Open `index.html` in any modern web browser (Chrome/Edge preferred).
3. Use the pre-loaded data or upload the provided `claims_data.csv` to see the system in action.