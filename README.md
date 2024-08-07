# Singapore Resale Flat Prices Prediction

## Project Overview

This project aims to develop a machine learning model to predict the resale prices of flats in Singapore. The model is deployed as a user-friendly web application, allowing users to estimate the resale value of a flat based on various factors. This tool assists both potential buyers and sellers in the competitive Singapore real estate market.

## Skills and Technologies

- **Data Wrangling**
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Model Building** (Decision Tree and Random Forest Regressors)
- **Model Deployment**
- **Streamlit** (for web application development)
- **Python** (including libraries like Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- **Decision Tree Regressor**
- **Random Forest Regressor**

## Domain

- **Real Estate**

## Problem Statement

Develop a predictive model to estimate the resale prices of flats in Singapore using historical transaction data. The model helps users make informed decisions regarding buying or selling flats.

## Motivation

Estimating resale values in Singapore's competitive market can be challenging. This project provides a solution by offering accurate predictions based on historical data and various influencing factors.

## Scope

1. **Data Collection and Preprocessing**
   - Collected dataset from the Singapore Housing and Development Board (HDB) for the years 1990 to present.
   - Preprocessed the data by splitting columns, handling null values, and converting categorical features to numeric.

2. **Feature Engineering**
   - Extracted and created features such as `price_per_sqm`, `years_holding`, and `current_remaining_lease`.
   - Applied log transformation and outlier handling to improve model performance.

3. **Model Selection and Training**
   - **Models Used:** Decision Tree Regressor and Random Forest Regressor
   - Trained both models on the preprocessed dataset.
   - Evaluated models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.

4. **Streamlit Web Application**
   - Developed a web application using Streamlit for user-friendly interaction and predictions.

5. **Testing and Validation**
   - Thoroughly tested the application to ensure accuracy and functionality.

## Deliverables

- A well-trained Decision Tree and Random Forest model for predicting resale prices.
- A user-friendly web application built with Streamlit.
- Documentation and instructions for using the application.
- A comprehensive project report detailing data analysis, model development, and deployment processes.

## Data Source

The dataset for this project is available at [Singapore Housing and Development Board (HDB) Data](https://beta.data.gov.sg/collections/189/view).

## Results

The project benefits buyers and sellers by providing a tool for accurate resale price estimation. The models demonstrate practical applications of machine learning in real estate and web development.

### Evaluation Metrics for All Algorithms:

| Model                     | Mean Absolute Error | Mean Squared Error | Root Mean Squared Error | R² Score  |
|---------------------------|----------------------|---------------------|--------------------------|-----------|
| Linear Regression        | 0.008018             | 0.000930            | 0.030495                 | 0.997224  |
| Decision Tree Regressor   | 0.001338             | 0.000164            | 0.012824                 | 0.999509  |
| Random Forest Regressor   | 0.001022             | 0.000085            | 0.009213                 | 0.999747  |

**Best Algorithm:** Random Forest Regressor


