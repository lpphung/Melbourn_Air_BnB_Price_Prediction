# Melbourne Airbnb Price Prediction

## Overview

This project builds a **machine learning model to predict Airbnb listing prices in Melbourne** using listing and host characteristics.

The project was completed as part of a **data analytics forecasting assignment**, where teams developed predictive models and submitted price forecasts for evaluation.

The problem is framed as a **supervised regression task**, with performance measured using **Mean Absolute Error (MAE)**.

## Dataset

The dataset contains information about Airbnb listings in Melbourne, including:

- **Property details** (room type, bedrooms, bathrooms)
- **Location information** (neighbourhood)
- **Host characteristics**
- **Listing activity and availability metrics**

Two datasets were provided:

- **Train dataset** – listings with known prices used to train the model  
- **Test dataset** – listings without prices used for prediction  

## Methodology

The project follows a standard machine learning workflow:

- **Exploratory Data Analysis (EDA)** to understand the data and identify patterns  
- **Data preprocessing** including handling missing values and encoding variables  
- **Feature engineering** to improve model performance  
- **Model training and evaluation** using regression models  

Model performance is evaluated using **Mean Absolute Error (MAE)**.

## Results

Multiple regression models were tested and compared. Tree-based ensemble models performed best due to their ability to capture non-linear relationships in the data.

The **XGBoost Model** achieved the best overall performance and was selected as the final model for generating predictions on the test dataset.
