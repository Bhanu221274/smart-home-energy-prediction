# Smart Home Energy Consumption Prediction (Linear Regression)

This project predicts household energy consumption using a real 100,000-record smart home dataset. The entire project is built only using Linear Regression and includes complete preprocessing, feature engineering, model training, evaluation, and visualization.

---

## Project Overview

The goal of this project is to predict how much energy a home will consume based on:

- Appliance Type  
- Outdoor Temperature  
- Time of Day  
- Date and Season  
- Household Size  

This dataset contains 100,000 rows and is ideal for building and understanding regression models.

---

## Key Features

- Full data cleaning and preprocessing  
- Datetime feature engineering (hour, day, month, weekday, weekend)  
- One-Hot Encoding for appliance type and season  
- Linear Regression as the baseline model  
- Model evaluation using MAE and R² score  
- Visualizations: Actual vs Predicted, Residual Distribution  
- Saved model file: `smart-home-energy-prediction_LR_model.pkl`

---

## Dataset

Dataset used in this project:  
https://www.kaggle.com/datasets/mexwell/smart-home-energy-consumption

Raw data is not included in this repo due to size. Instead, the dataset link is stored in `data/`.

---

## Results

Replace the values below with your actual results:

- Mean Absolute Error (MAE): 0.47599430202431947  
- R² Score: 0.7575214050257248

## Contributions

Feel free to open issues or submit pull requests!


