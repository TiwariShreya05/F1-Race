<div align="center">

# 🏎️ F1 Race Outcome & Strategy Analyzer

**An end-to-end Machine Learning project that analyzes historical Formula 1 race data to predict race finishing positions using a Random Forest Regressor.**

</div>

---

## 📌 Overview

This project uses historical F1 race data to build a complete ML pipeline — from raw data preprocessing to a deployed web application. Users can input race parameters and receive predicted finishing positions through a simple browser interface.

The project covers the **full ML lifecycle**:

- 🧹 Data cleaning & preprocessing
- 📊 Exploratory data analysis (EDA)
- ⚙️ Feature engineering
- 🌲 Model training (Random Forest Regressor)
- 📈 Model evaluation & error analysis
- 🚀 Deployment via Flask

---

## 🧠 ML Workflow

```
Raw Data → Preprocessing → EDA → Feature Engineering → Model Training → Evaluation → Flask API → Frontend
```

| Step | Description |
|------|-------------|
| 1. Data Cleaning | Handle missing values, outliers, and format inconsistencies |
| 2. EDA | Visualize distributions, correlations, and race trends |
| 3. Feature Engineering | Construct meaningful predictors from raw race attributes |
| 4. Model Selection | Random Forest Regressor (handles nonlinear relationships well) |
| 5. Training | Fit model on historical race data |
| 6. Evaluation | RMSE, MAE, and residual/error analysis |
| 7. Deployment | Serve predictions via Flask REST endpoint |

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| Language | Python 3.8+ |
| Data | Pandas, NumPy |
| ML | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Backend | Flask |
| Frontend | HTML, CSS, JavaScript |

---

## 📂 Project Structure

```
F1_RACE_STRATEGY_ML/
│
├── data/                   # Raw CSV datasets
├── notebooks/              # Jupyter notebooks (EDA & model training)
├── models/                 # Trained model artifacts (excluded from Git)
├── static/                 # CSS & JavaScript files
├── templates/              # HTML frontend templates
├── app.py                  # Flask application entry point
├── requirements.txt        # Python dependencies
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/F1_RACE_STRATEGY_ML.git
cd F1_RACE_STRATEGY_ML
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Flask App

```bash
python app.py
```

### 4. Open in Browser

```
http://127.0.0.1:5000/
```

Enter race parameters to receive a predicted finishing position.

---

## 📊 Key Insights

- **Grid position** is the strongest predictor of final race outcome
- **Historical driver performance** provides meaningful signal for predictions
- **Random Forest** captures nonlinear feature interactions that linear models miss
- Higher prediction variance observed in races with unusual conditions (safety cars, retirements, weather)

---

## 🔮 Future Improvements

- [ ] Benchmark against Gradient Boosting / XGBoost
- [ ] Add prediction confidence intervals
- [ ] Integrate live F1 data via the Ergast or OpenF1 API
- [ ] Improve UI with interactive lap-by-lap visualizations
- [ ] Deploy publicly on Render or Railway

---

## 🎯 Project Goals

This project was built to:

- Practice building end-to-end ML pipelines
- Apply regression modeling to sports analytics
- Gain hands-on experience deploying ML models with Flask
- Develop a production-style ML workflow from scratch

---

<div align="center">
Made with ❤️ and too much coffee ☕ — inspired by the relentless pursuit of the fastest lap.
</div>
