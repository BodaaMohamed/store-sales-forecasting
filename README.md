# 📈 Store Sales Forecasting with SARIMA, ARIMA & Prophet

Welcome to the **Store Sales Forecasting** project! This notebook guides you through building and comparing multiple time series forecasting models to predict weekly store sales. From cleaning raw data to visualizing forecast performance, everything is covered in one place.

---

## 🧠 Project Highlights

- ⚙️ **End-to-End Pipeline**: From raw CSV files to meaningful forecasts.
- 📊 **Model Comparison**: SARIMA vs. ARIMA vs. Prophet.
- 🧼 **Data Engineering**: Merging datasets, handling missing values, and preparing weekly time series.
- 📉 **Performance Evaluation**: MAE, RMSE, and visual diagnostics.

---

## 📂 Table of Contents

1. [Overview](#-project-highlights)
2. [Project Structure](#-project-structure)
3. [Datasets](#-datasets)
4. [Requirements](#-requirements)
5. [How to Run](#-how-to-run)
6. [Results & Visualizations](#-results--visualizations)
7. [License](#-license)

---

## 🏗️ Project Structure

```
📁 store_sales_forecasting/
│
├── 📄 store_sales_forecasting.ipynb   # Main notebook
├── 📄 train.csv                        # Historical sales data
├── 📄 test.csv                         # Test data for prediction
├── 📄 stores.csv                       # Store metadata
├── 📄 features.csv                     # Extra features (e.g. holidays, markdowns)
└── 📄 README.md                        # Project documentation
```

---

## 📊 Datasets

This project uses Walmart’s weekly sales data across multiple stores and departments.

**Files Required:**
- `train.csv`: Weekly sales data for training
- `test.csv`: Data for forecast evaluation
- `stores.csv`: Info about store type and size
- `features.csv`: Additional features like holidays, markdowns, and temperature

---

## 📦 Requirements

Install all required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn statsmodels prophet plotly scikit-learn
```

---

## ▶️ How to Run

1. Clone this repository or download the files.
2. Place all CSV files in the same folder as the notebook.
3. Launch Jupyter Notebook or VS Code.
4. Run `store_sales_forecasting.ipynb` step-by-step.

---

## 📈 Results & Visualizations

- Seasonal decomposition (trend, seasonality, residuals)
- ACF & PACF plots for SARIMA tuning
- Forecast plots with confidence intervals
- MAE & RMSE for each model comparison

---

## 📎 License

This notebook is provided for educational and research purposes. Attribution is appreciated if reused or modified.

---

Made with ❤️ by a Data Science Enthusiast.