🌍 Air Quality (PM2.5) Prediction Using Machine Learning
📌 Project Overview

Air pollution is a major environmental concern affecting public health worldwide. This project focuses on predicting PM2.5 air pollution levels using meteorological and geographical parameters. It demonstrates a complete end-to-end machine learning workflow, from data preprocessing to model evaluation.

🎯 Objective

To develop a regression-based machine learning model that accurately estimates PM2.5 concentrations based on environmental and location-based features.

📊 Dataset Description

The dataset consists of the following features:

🔹 Input Variables

Temperature

Humidity

Wind Speed

Atmospheric Pressure

Cloud Cover

Latitude

Longitude

🔹 Target Variable

PM2.5 – Continuous values representing fine particulate matter concentration in the air.

🛠️ Tools & Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

🔍 Project Workflow

Data Loading and Understanding

Data Preprocessing and Cleaning

Exploratory Data Analysis (EDA)

Feature Selection

Train-Test Split

Model Training using Linear Regression

Model Evaluation using MAE and RMSE

Interpretation of Results and Conclusions

📈 Model Selection

Linear Regression was chosen due to its simplicity and interpretability. It helps in understanding the relationship between environmental factors and PM2.5 levels, making it suitable for baseline air quality prediction.

📏 Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

These metrics were used to evaluate the accuracy and reliability of the model.

🧠 Key Insights

Higher humidity and cloud cover tend to increase PM2.5 concentration.

Wind speed shows a negative correlation with PM2.5, indicating dispersion of pollutants.

Geographical coordinates (latitude and longitude) play a significant role in pollution variation.

Effective preprocessing and EDA significantly improve model performance and insights.

✅ Conclusion

This project successfully demonstrates how machine learning can be applied to predict air quality levels. The developed model provides meaningful insights into the environmental factors influencing PM2.5 and serves as a strong foundation for more advanced air pollution forecasting systems.

📁 Repository Structure

Air_Quality_PM2_5_Prediction.ipynb – Complete Jupyter Notebook implementation

air_quality.csv – Sample dataset

README.md – Project documentation

👤 Author

Akshaya M

