## 👩‍💻 Authors  
- Marcus Peerboccus  
- Gareth Bacchus
- Jason Peerboccus

# 🚗 Car Sales Forecasting  

This project explores time series forecasting and machine learning methods to predict car sales trends. The analysis combines historical sales data, economic indicators, and lagged covariates to build robust forecasting models.  

The primary analysis is in **[Sales Forecasting.ipynb](Sales%20Forecasting.ipynb)**.  

## 🛠️ Project Features  
- **Data Extraction and Aggregation**:  
  - Extracted 10 years of monthly car sales data for a popular sedan.  
  - Combined sales data with relevant economic indicators from multiple sources.  

- **Model Implementation**:  
  - Built time series forecasting models using **Facebook's Prophet**.  
  - Developed machine learning models with **LASSO**, **Random Forest**, and **XGBoost** using lagged covariates.  

- **Hyperparameter Tuning**:  
  - Conducted iterative tuning for Prophet and LASSO models, improving Prophet's MAPE from **87% to 16%**.  

- **Model Evaluation**:  
  - Achieved MAPE ranging from **22% (LASSO)** to **11% (Random Forest)**, demonstrating model accuracy and effectiveness.  
  - LASSO model provided insights into the most significant covariates impacting car sales trends.  

## 📂 Files in This Repository  
- **[Sales Forecasting.ipynb](Sales%20Forecasting.ipynb)**: The main Jupyter Notebook containing the data analysis, model implementation, and results.  
- **data/**: Folder containing the cleaned and aggregated datasets used in the analysis.  
- **images/**: Sample car images and visualizations generated during the project.  

## ✨ Highlights  
This project combines traditional forecasting approaches like Prophet with modern machine learning techniques to evaluate and predict car sales trends. The results showcase the potential for hybrid methodologies in business forecasting.  

Feel free to explore the code and reach out with any feedback or questions!  
