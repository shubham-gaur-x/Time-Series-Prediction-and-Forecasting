# Time Series Analysis and Forecasting

This repository contains solutions for a project focused on **Time Series Analysis and Forecasting**.

---

## Objectives

The project focuses on analyzing and forecasting mobility trends using time series data. The dataset includes mobility trends for **Residential**, **Workplaces**, and **Grocery and Pharmacy** categories in King County, USA, from 2020 to 2022.

---

## Steps Involved

### **Task: Mobility Data Forecasting**
1. **Dataset**: Google Mobility Data (King County, 2020-2022).
   - Isolated time series for:
     - Residential
     - Workplaces
     - Grocery and Pharmacy.
2. **Steps**:
   - Merge all time series into a single DataFrame.
   - Remove months before April 2020 (to focus on pandemic conditions).
   - Perform **Additive Time Series Decomposition**:
     - Plot trend, seasonality, and remainder for each time series.
   - Build forecasting models:
     - **Exponential Smoothing (ES)**:
       - Test at least 2 ES models and evaluate using MAE and RMSE.
     - **ARIMA**:
       - Justify the ARIMA model selection.
   - Compare the best ES and ARIMA models for each time series using forecast evaluation metrics.
   - Forecast the remainder of 2022 using the best model for each time series.
     - Plot past data points in one color and forecasted points in another.

---

## Repository Contents

- **Time-Series-Prediction-and-Forecasting.ipynb**: Jupyter Notebook containing:
  - Code implementation.
  - Results and plots for Time Series Prediction and Forecasting.
- **data/**: Folder containing all necessary datasets:
  - Google Mobility Data (King County, 2020-2022).
- **README.md**: Project documentation (this file).

---

## Dataset Location

The dataset used in this project is available at the following location:

[Google Drive - Mobility Data](https://drive.google.com/drive/folders/1REVSP3Z6NbRkco8-RCLPNTirUWkV5Rsz?usp=sharing)
