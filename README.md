# Time Series Forecasting on Pulse Price Indices  

## 📌 Project Overview  
This project analyzes **UPDES (Uttar Pradesh Directorate of Economics and Statistics)** data on **Pulse Price Indices** to explore patterns, interdependencies, and forecasting models for price prediction.  

The study involves examining **stationarity, seasonality, causal relationships, and forecasting accuracy** using advanced time series techniques.  

---

## 🔑 Key Steps & Methodology  

- **Data Analysis**:  
  - Analyzed **Pulse Price Indices** from UPDES dataset.  
  - Checked **stationarity** using **ADF (Augmented Dickey–Fuller) Test**.  
  - Examined **seasonality** using **Fast Fourier Transform (FFT)**.  

- **Causality & Interdependencies**:  
  - Performed **Granger-Causality Tests** across each pair of pulses.  
  - Identified and modeled interdependencies among different pulses.  

- **Forecasting Models**:  
  - **VAR (Vector AutoRegression)** model  
    - Achieved **MAPE: 4.2%**  
  - **ARIMAX (AutoRegressive Integrated Moving Average with Exogenous Variables)** model  
    - Achieved **MAPE: 2.8% – 5.1%**  
  - Validated model assumptions using **Ljung–Box Test**.  

---

## 📊 Results & Insights  
- Captured strong **interdependencies** between different pulse indices.  
- **ARIMAX** provided better performance compared to **VAR**, especially when incorporating external regressors.  
- Forecast accuracy achieved with **low MAPE**, indicating robust predictive capability.  

---

## 🛠️ Tech Stack  
- **Python** (pandas, numpy, statsmodels, matplotlib, seaborn, scipy)  
- **Time Series Analysis** (ADF Test, FFT, Granger Causality, VAR, ARIMAX, Ljung–Box)  
- **Jupyter Notebook** for exploration and visualization  

---


---

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Sarvesh1Yadav/Multivariate-Time-Series-Analysis.git
   cd Multivariate-Time-Series-Analysis

## Installation

Install the required dependencies using:

```bash
pip install -r requirements.txt


