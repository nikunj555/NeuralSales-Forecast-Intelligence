# ⚡ NeuralSales — AI-Powered Sales Forecast Intelligence Platform

NeuralSales is an advanced end-to-end Machine Learning powered sales forecasting and analytics platform built using modern ML engineering and data visualization technologies.

The platform combines:

- Supervised Machine Learning
- Time Series Forecasting
- Explainable AI
- Interactive Dashboards
- Model Comparison
- Forecast Intelligence
- Backend API Engineering

into a production-style AI analytics ecosystem.

---

# 🚀 Core Features

## 📈 Advanced Sales Analytics Dashboard
- Real-time KPI monitoring
- Revenue analytics
- Customer intelligence
- Sales trend visualization
- Monthly heatmaps
- Correlation analysis
- Moving averages
- Bollinger Bands

---

## 🔮 AI-Powered 30-Day Forecasting
- Future sales prediction
- Confidence intervals
- Growth rate analysis
- Trend forecasting
- Peak demand prediction
- Dynamic prediction bands

---

## 🤖 Multi-Model ML Training Engine

The system trains and evaluates multiple supervised ML algorithms:

| Model | Category |
|---|---|
| Linear Regression | Linear Model |
| Lasso Regression | Regularized Linear |
| Ridge Regression | Regularized Linear |
| Decision Tree | Tree-Based |
| Random Forest | Ensemble Learning |
| Gradient Boosting | Boosting |
| AdaBoost | Ensemble Boosting |
| Extra Trees | Randomized Ensemble |
| SVR | Kernel-Based Learning |
| XGBoost | Advanced Boosting |

---

## 📊 Dynamic Model Comparison
- R² comparison
- MAE comparison
- RMSE analysis
- Cross-validation scores
- Best model detection
- Real backend-integrated comparison engine

---

## 🧠 Explainable AI (XAI)
Integrated SHAP explainability:
- Feature importance
- Prediction explainability
- Model transparency
- Interpretable AI outputs

---

## ⚙️ Enterprise Backend APIs
- FastAPI REST architecture
- Dynamic ML inference
- Forecast APIs
- Model metadata APIs
- Explainable AI APIs
- Health monitoring APIs

---

# 🧠 Machine Learning Architecture

## 🔹 Data Processing Pipeline

```text
Raw Sales Data
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Lag Feature Generation
        ↓
Rolling Window Features
        ↓
Train/Test Split
        ↓
Cross Validation
        ↓
Multi-Model Training
        ↓
Model Evaluation
        ↓
Best Model Selection
        ↓
Forecast Generation
        ↓
Backend API Serving
        ↓
Interactive Dashboard Visualization
```

---

# 🧩 Feature Engineering Architecture

The forecasting engine uses advanced engineered features:

## 📅 Temporal Features
- day_of_week
- month
- year
- is_weekend
- is_holiday_season

---

## 📈 Lag Features
- sales_lag_1
- sales_lag_7
- sales_lag_30

---

## 📊 Rolling Statistics
- sales_rolling_7
- sales_rolling_30

---

## 🛒 Business Features
- customers
- quantity
- discount

---

# 🧪 Model Training Architecture

## Training Strategy
- Chronological split
- TimeSeriesSplit cross validation
- Multi-model evaluation
- Ensemble comparison
- Automatic best model selection

---

## Evaluation Metrics
- MAE
- RMSE
- R² Score
- Accuracy %
- Cross Validation Mean

---

# ⚡ Tech Stack

# 🎨 Frontend Stack

| Technology | Usage |
|---|---|
| Streamlit | Interactive dashboard |
| Plotly | Data visualization |
| Plotly Graph Objects | Advanced charts |
| HTML/CSS | Custom enterprise UI |
| Pandas | Data manipulation |

---

# ⚙️ Backend Stack

| Technology | Usage |
|---|---|
| FastAPI | REST APIs |
| Uvicorn | ASGI server |
| JSON | Data exchange |
| Joblib | Model serialization |

---

# 🧠 Machine Learning Stack

| Technology | Usage |
|---|---|
| Scikit-learn | ML models |
| XGBoost | Advanced boosting |
| SHAP | Explainable AI |
| NumPy | Numerical computation |
| Pandas | Feature engineering |

---

# 📊 Visualization Stack

| Technology | Usage |
|---|---|
| Plotly | Interactive analytics |
| Matplotlib | Static visualization |
| Seaborn | Statistical plots |

---

# 📂 Project Structure

```bash
sales_analyzer_project/
│
├── backend/
│   └── api.py
│
├── frontend/
│   └── app.py
│
├── data/
│   └── sales_data.csv
│
├── models/
│   ├── sales_model.pkl
│   ├── feature_cols.json
│   └── model_results.pkl
│
├── outputs/
│   ├── feature_importance.png
│   ├── actual_vs_predicted.png
│   └── residual_distribution.png
│
├── train_model.py
│
└── README.md
```

---

# 📡 API Endpoints

| Endpoint | Description |
|---|---|
| `/health` | Backend health check |
| `/forecast/30day` | AI sales forecasting |
| `/model/info` | Model metadata |
| `/model-comparison` | Dynamic model comparison |
| `/model/shap` | Explainable AI insights |

---

# ⚡ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/neuralsales.git

cd neuralsales
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate:

### Windows
```bash
venv\Scripts\activate
```

### Linux/Mac
```bash
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

## 1️⃣ Train Models

```bash
python train_model.py
```

---

## 2️⃣ Start Backend

```bash
cd backend

uvicorn api:app --reload
```

---

## 3️⃣ Start Frontend

```bash
cd frontend

streamlit run app.py
```

---

# 📈 Dashboard Modules

## 📊 Dashboard
Business analytics and KPI tracking.

## 🔮 Forecast
30-day ML forecasting engine.

## 🤖 Model Insights
Feature importance and ML diagnostics.

## 📊 Model Comparison
Multi-model evaluation engine.

## 🧠 Explainable AI
SHAP-powered AI explainability.

## ⚙️ Settings
Backend configuration and controls.

---

# 🔥 Advanced Highlights

✅ Enterprise-grade Dashboard  
✅ Dynamic ML Forecasting  
✅ Ensemble Learning Models  
✅ Explainable AI Integration  
✅ Forecast Confidence Bands  
✅ Production Backend APIs  
✅ Time-Series Validation  
✅ Multi-Model Benchmarking  
✅ Feature Engineering Pipeline  
✅ Professional Dark UI  

---

# 🚀 Future Enhancements

- LightGBM Integration
- CatBoost Integration
- Hyperparameter Optimization
- Docker Deployment
- CI/CD Pipeline
- Drift Detection
- Real-Time Forecast Streaming
- Cloud Deployment
- Auto Retraining System

---

# 👨‍💻 Author

Nikunj Katta

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
