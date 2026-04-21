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

## 🚀 Features

* 🔍 **Fraud Detection Engine**
  Identifies suspicious claims based on unusual patterns in the dataset

* 📊 **Interactive Dashboard**
  Displays claim insights in a simple and understandable format

* 📁 **Dataset Upload**
  Users can upload claim data (CSV) for analysis

* ⚡ **Real-time Processing (Prototype Level)**
  Provides quick results based on uploaded data

* 🧠 **Rule-based + ML Approach**
  Combines basic logic and ML concepts for detection

* 🖥️ **User-friendly Interface**
  Clean and simple UI built for easy interaction

## 🛠️ Tech Stack

**Frontend:**
* HTML
* CSS (Tailwind CSS)
* JavaScript

**Backend (Concept/Prototype Level):**
* Python (Flask – if used)

**Data Handling & AI:**
* Pandas
* Basic Machine Learning concepts

**Tools & Platforms:**
* GitHub (Version Control)
* VS Code

## ⚙️ How It Works

1. User uploads a claims dataset (`claims_data.csv`)
2. The system processes the data
3. Fraud detection logic is applied:
    * Detects abnormal claim amounts
    * Identifies duplicate or suspicious entries
4. Results are displayed on the dashboard
5. Insights help in identifying potential fraud cases

## ✨ Key Highlights

* 💡 Solves a **real-world problem** in healthcare fraud detection
* ⚡ Built as a **lightweight, software-based solution** (no expensive sensors needed)
* 🔍 Focus on **early-stage fraud identification**
* 📈 Scalable idea that can be expanded with advanced AI models
* 🏆 Designed for hackathon/prototype-level innovation

## 🔮 Future Scope

* 🤖 Integration of advanced ML models (Random Forest, Neural Networks)
* ☁️ Deployment using cloud platforms (AWS / Google Cloud)
* 🔐 Secure login system for officials
* 📊 Advanced analytics dashboard with visualizations
* 🔗 Integration with real government healthcare databases
* 📱 Mobile-friendly version or app

## 📂 Project Structure

GovShield_Fraud_Detection_System/
│── index.html
│── README.md
│── claims_data.csv
│── Project_Report.pdf
│── Output_Screenshots/
   └── (all screenshots)

