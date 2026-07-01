# 💰 Employee Salary Prediction — Streamlit App

A full-featured, interactive, 3D salary prediction dashboard built with Streamlit, XGBoost, and Plotly.

---

## 🚀 Setup & Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Place your dataset
Make sure `Salary_Data.csv` is in the **same folder** as `app.py`.

### 3. Run the app
```bash
streamlit run app.py
```

---

## 📦 File Structure
```
📁 your-folder/
├── app.py              ← Main Streamlit app
├── Salary_Data.csv     ← Your dataset
├── requirements.txt    ← Python dependencies
└── README.md
```

---

## 🌟 Features

| Page | Features |
|------|----------|
| 🏠 Dashboard | KPI cards, salary by education/gender, top-paying jobs, experience distribution |
| 🔮 Salary Predictor | Live prediction gauge, confidence range, what-if slider, AI-generated tips |
| 📊 Data Explorer | 3D salary surface, 3D scatter, violin/box plots, correlation heatmap |
| 🧠 Model Insights | Feature importance, actual vs predicted, 3D LR vs XGBoost comparison |
| 📦 Batch Predictor | CSV upload → bulk predictions → download results |
| ⚖️ Profile Compare | Compare 2–3 profiles with grouped bar + radar chart |
| 📈 Career Growth | Salary trajectory + 3D growth landscape |

---

## 🤖 Models
- **Linear Regression** — R² ≈ 93.5%
- **XGBoost Regressor** — R² ≈ 94.6%

---

## 💻 Tech Stack
- [Streamlit](https://streamlit.io) — UI framework
- [Plotly](https://plotly.com) — Interactive & 3D charts
- [XGBoost](https://xgboost.readthedocs.io) — Gradient boosting model
- [scikit-learn](https://scikit-learn.org) — ML utilities
