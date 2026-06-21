# 🚀 AI-Based Customer Churn + Lifetime Value Prediction

An AI-powered customer analytics platform that predicts churn probability, performs customer segmentation, forecasts lifetime value (LTV), and simulates ROI impact.

## ✨ Features

- 🔮 **Churn Prediction** - Predict customer churn probability using XGBoost
- 🎯 **Customer Segmentation** - K-means clustering for customer grouping
- 📈 **LTV Forecasting** - Lifetime value prediction using survival analysis
- 💰 **ROI Simulation** - What-if analysis for retention strategies
- 📊 **Interactive Dashboard** - Beautiful React + Tailwind CSS UI

## 🛠️ Tech Stack

### Frontend
- React 18
- Tailwind CSS
- Recharts
- Axios

### Backend
- Python 3.9+
- FastAPI
- XGBoost
- Scikit-learn
- PostgreSQL

## 📁 Project Structure

## 🚀 Quick Start

### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload

cd frontend
npm install
npm run dev