# MachineL

# ⚡ Lithium & Battery Production Forecasting using Machine Learning

---

## 📖 Overview

This project applies **Machine Learning techniques** to analyze and forecast **global battery production** based on key variables from the lithium supply chain and energy transition.

The study explores the relationship between:

- 🌍 Global lithium production  
- 🇧🇷 Lithium production in Brazil  
- ⚡ Renewable energy generation  
- 🚗 Electric vehicle (EV) sales  

The goal is to understand how these factors influence future battery demand and support the global energy transition.

---

## 🎯 Objective

To build a predictive model capable of estimating **global battery production (2016–2030)** using regression-based Machine Learning and energy transition indicators.

---

## 📊 Dataset

The dataset integrates multiple sources:

| Variable | Description | Period |
|----------|------------|--------|
| Lithium Production (World) | Global lithium output | 2010–2024 |
| Lithium Production (Brazil) | Brazilian lithium production | 2010–2024 |
| Renewable Energy | Global renewable generation | 2010–2024 |
| EV Sales | Electric vehicle sales | 2010–2024 |
| Battery Production | Global battery production (target) | 2016–2023 |

---

## ⚙️ Methodology

The workflow includes:

1. 📥 Data collection and cleaning  
2. 🔗 Data integration by year  
3. 📊 Exploratory Data Analysis (EDA)  
4. 🤖 Machine Learning model (Linear Regression)  
5. 📈 Model evaluation:
   - R² (Explained variance)
   - RMSE (Root Mean Squared Error)
   - RMSRE (Relative error)
6. 🔮 Forecasting (2024–2030 scenarios)

---

## 🧠 Machine Learning Model

- Algorithm: **Multiple Linear Regression**
- Library: Scikit-learn
- Features:
  - Lithium Production (World)
  - Lithium Production (Brazil)
  - Renewable Energy
  - EV Sales

---

## 📈 Results

The model demonstrates strong predictive capability for battery production trends, indicating that lithium supply and EV adoption are major drivers of demand.

---

## 📊 Model Evaluation

| Metric | Description |
|--------|------------|
| R² | Proportion of variance explained by the model |
| RMSE | Average prediction error in original units |
| RMSRE | Relative prediction error |

---

## 🚀 Tech Stack

- Python 🐍
- Pandas 📊
- NumPy 🔢
- Matplotlib 📉
- Scikit-learn 🤖

---

## 📌 Future Work

- Replace linear regression with:
  - Random Forest 🌲
  - XGBoost 🚀
  - LSTM (time series) ⏳
- Add logistic growth models for saturation effects
- Improve scenario-based forecasting

---

## 👩‍🔬 Author

Research project focused on:
- Energy transition 🌍  
- Critical minerals supply chain ⛏️  
- Machine Learning applications 🤖  

---

## 📜 License

This project is for academic and research purposes.

---

⭐ If you like this project, consider giving it a star!
