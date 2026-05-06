# My-project
# Upper Awash River Project
 📌 Project Overview

This project investigates the impacts of climate change on streamflow in the Upper Awash River Basin, Ethiopia. It integrates deep learning techniques and statistical downscaling methods to improve the accuracy of hydrological predictions and support sustainable water resource management.

 Objectives

The main objectives of this study are:

* To analyze historical climate trends in the Upper Awash Basin
* To develop predictive models for streamflow using deep learning
* To apply statistical downscaling techniques for climate projections
* To assess the impact of future climate scenarios on water availability

🧪 Methodology

1. Data Collection

* Historical hydro-meteorological data (rainfall, temperature, streamflow)
* GCM (Global Climate Model) outputs for future projections

2. Data Preprocessing

* Handling missing values
* Outlier detection using IQR method
* Data normalization and scaling

3. Trend Analysis

* Mann-Kendall test for detecting trends
* Sen’s slope estimator for quantifying trend magnitude

 4. Statistical Downscaling

* Quantile Delta Mapping (QDM) used to correct bias in GCM outputs
* Preserves climate change signals while adjusting distributions

5. Deep Learning Modeling

* Long Short-Term Memory (LSTM) network applied for streamflow prediction
* Model training, validation, and testing performed using time-series data


6. Model Evaluation

Performance assessed using:

* Root Mean Square Error (RMSE)
* Mean Absolute Error (MAE)
* Coefficient of Determination (R²)

 📊 Results and Findings

* Trend analysis revealed variability in rainfall and temperature across stations
* Bias correction using QDM significantly improved GCM data reliability
* LSTM model demonstrated strong performance in capturing temporal patterns of streamflow
* Future projections indicate potential changes in water availability under climate change scenario

 🛠️ Tools and Technologies

* Python
* Pandas, NumPy
* TensorFlow / Keras
* Matplotlib

👤 Author

Mandefro Mengistu
📚 Acknowledgment

This project is part of a hydroinformatics study focused on improving water resource management in the Upper Awash River Basin.
