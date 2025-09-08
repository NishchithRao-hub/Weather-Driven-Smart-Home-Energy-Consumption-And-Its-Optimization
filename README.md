# Overview

 The main objective of this project is to develop a comprehensive framework for analyzing, predicting, and
 optimizing energy consumption in a smart home environment using weather-driven data. By the use of
 advanced time-series analysis techniques and ML models, this project aims to recognize patterns in
 energy usage, detect anomalies, and provide usable insights for efficient usage of energy. The end goal is
 to create a system capable of predicting energy consumption and offering optimized device configurations
 that reduce costs and environmental impact without affecting household comfort.
 
 This project highlight key findings into the dynamics of energy consumption and the efficacy of
 predictive and optimization models. We have used the VAR, Prophet and LightGBM Regressor model in 
 predicting energy as these models acheived a lower mean absolute error (MAE) score and showed better
 predictive performance compared to other models like VARMAX, LSTM and Support Vector Machine. 

 ## Snapshots

<img src="https://github.com/user-attachments/assets/89b5fbbc-2450-4901-9ea4-b266610de3b9" width="400" height="400">
<p align="center">Dependency between home appliances and weather conditions</p>

---

<img src="https://github.com/user-attachments/assets/904ee490-68ce-4d55-8396-1ad12ac29c53" width="400" height="400">
<p align="center">Total energy consumption of various household appliances by day</p>

---

<img src="https://github.com/user-attachments/assets/33ec4e9a-eb8d-45c6-ba3c-f974eee5f91f" width="400" height="400">
<p align="center">Total Energy consumption (actual vs predicted by the VAR model)</p>

---

<img src="https://github.com/user-attachments/assets/cf76433f-62c7-4642-9a37-ffe8467a906f" width="400" height="400">
<p align="center">Total Energy consumption (actual vs predicted by the Prophet model)</p>

---

<img src="https://github.com/user-attachments/assets/05a755ef-9c1f-4ad0-93af-dfaeef480849" width="400" height="400">
<p align="center">Total Energy consumption (actual vs predicted by the LightGBM Regressor model)</p>

---

<img src="https://github.com/user-attachments/assets/6f766132-436c-4ec8-9e49-15c13fd37343" width="400" height="400">
<p align="center">SHAP model showing the impact of features on the prediction model</p>


 ### Dataset Link

 This is the Dataset Link: [Smart Home Energy Consumption and Weather Data](https://www.kaggle.com/datasets/jamshaid1202/smart-home-energy-consumption-and-weather-data)
