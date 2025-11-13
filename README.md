# ByteMasters-SIH
# 🌦️ GeoSat Weather Prediction System

A data-driven system that analyzes and processes imagery from **geostationary satellites** such as **INSAT-3D/3DR** to forecast heavy precipitation events.  
This project combines **AI, remote sensing, and web technologies** to deliver interpretable and real-time weather predictions.

##  Features

- **Satellite Data Analysis:**  
  Process multispectral imagery including cloud cover, temperature profiles, humidity levels, wind patterns, and historical rainfall data.

- **AI-Based Forecasting:**  
  Implement **CNN** and **LSTM** models for predictive modeling and data fusion, integrating real-time satellite inputs for accurate forecasts.

- **Model Interpretability:**  
  Apply **SHAP** and **LIME** techniques to explain model predictions and highlight influential features.

- **Monitoring & Reliability:**  
  Track and identify potential model failures due to data quality issues, sudden weather changes, or calibration anomalies.

- **Interactive Web Application:**  
  Web-based interface where users can input parameters (date, time, location) and receive predictions for heavy rainfall events — visualized in an intuitive, user-friendly format.

## Tech Stack

- **Languages:** Python, JavaScript  
- **Libraries/Frameworks:** TensorFlow, Keras, Flask, SHAP, LIME  
- **Data Sources:** INSAT-3D/3DR, IMD datasets  
- **Frontend:** HTML, CSS, JavaScript (for interactive visualization)

## Objective

To create an interpretable, real-time system that bridges **satellite meteorology** and **AI modeling**, helping researchers and users make informed decisions on severe weather events.

## Future Work

- Integration with live satellite feeds  
- Model optimization for regional forecasts  
- Addition of ensemble learning for improved accuracy
