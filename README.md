# Sales Forecast

This project explores forecasting retail sales using Kaggle’s “Sales Forecasting” dataset by Rohit Sahoo. The goal is to demonstrate practical skills in data cleaning, exploratory analysis, baseline modeling, and communicating results visually.

Dataset link: [https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

---

## Preview of Results

**Historical Monthly Sales Performance (EDA)**
![EDA](assets/Historical%20Monthly%20Sales%20Performance%20-%20EDA.png)

**Model Comparison – Central Region**
![Model Comparison](assets/Model%20Comparison-%20Central%20Region.png)

**Forecast vs Actuals by Region**
![Forecast Regions](assets/forecast_regions.png)

---
## Key Insights

* Sales show clear seasonality with recurring peaks and troughs across months.
* Performance varies by region, some regions show steady growth while others are more volatile.
* A simple naïve lag-1 forecast provides a baseline that already captures much of the sales pattern.
* Error metrics (MAE, sMAPE) help compare models and highlight where more advanced methods (e.g., XGBoost, Prophet) could add value.

---

## Project Objectives

* Performe Eplanatory Data Analysis on retail sales.
* Clean and explore raw sales data.
* Develop baseline and machine learning forecasting models.
* Compare forecast accurary.
* Communicate results to non-technical stakeholders.

---

---

## Explore the Notebook

For those interested in the code and step-by-step analysis, see
notebooks/EDA and notebooks/SF_Modeling.ipynb

---

## Repository Layout

```
Sales-Forecast/
├─ .ipynb_checkpoints/
├─ .venv/
├─ assets/ # holds images shown above
├─ data/
├─ models/
├─ notebooks/
├─ src/
├─ setup/ # detailed environment + reproducibility steps
├─ .gitignore
├─ README.md
├─ requirements.lock.txt # use for exact reproducibility
└─ requirements.txt # contains a minimal, clean list of top-level libraries with version ranges.
```
---

## Setup
For detailed environment and reproducibility steps, see [setup/SETUP.md](setup/SETUP.md).

---

