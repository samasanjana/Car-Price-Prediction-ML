# Car Price Prediction Using Machine Learning

## 1. Project Overview

Car Price Prediction is a Machine Learning project that predicts the selling price of used cars based on different car features. This project uses historical car data to understand the factors that influence the resale value of a vehicle.

The main aim is to build a Machine Learning model that helps buyers and sellers estimate the selling price of a used car.

## 2. Problem Statement

In the used car market, buyers and sellers often find it difficult to determine the correct resale price of a vehicle. Car prices depend on several factors, such as manufacturing year, present price, kilometers driven, fuel type, and transmission.

This project uses Machine Learning techniques to predict the estimated selling price based on these features.

## 3. Project Objectives

- Analyze used car data and understand pricing patterns.
- Perform data cleaning and preprocessing.
- Explore relationships between car features and selling prices.
- Build and evaluate different Machine Learning models.
- Select the best-performing model.
- Develop a user-friendly web application using Gradio.

## 4. Dataset Description

The dataset is collected from the Vehicle Dataset from CarDekho available on Kaggle.

**Dataset Link:** 
https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

### Dataset Columns

| Column | Description |
|---|---|
| Car_Name | Name of the car |
| Year | Manufacturing year |
| Selling_Price | Selling price of the car |
| Present_Price | Current showroom price |
| Kms_Driven | Kilometers driven |
| Fuel_Type | Type of fuel |
| Seller_Type | Dealer or Individual |
| Transmission | Manual or Automatic |
| Owner | Number of previous owners |

## 5. Technologies and Libraries Used

- Python – Programming language
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine Learning model building and evaluation
- Joblib – Model saving and loading
- Gradio – Web application deployment
- Google Colab – Development environment

## 6. Machine Learning Workflow

The project follows these steps:

1. Business Understanding and Problem Statement
2. Data Loading and Understanding
3. Data Preprocessing and Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Model Building and Training
8. Model Evaluation and Selection
9. Model Saving
10. Gradio Application Development
11. Testing the Deployed Application

## 7. Machine Learning Problem Type

This project is a **Supervised Machine Learning - Regression Problem** because the target variable, Selling_Price, is a continuous numerical value.

**Input:** Car details such as year, present price, fuel type, and kilometers driven.

**Output:** Predicted selling price of the car.

## 8. Model Evaluation Metrics

The models will be evaluated using the following metrics:

- **MAE (Mean Absolute Error):** Measures the average absolute prediction error.
- **MSE (Mean Squared Error):** Measures the average squared prediction error.
- **RMSE (Root Mean Squared Error):** Measures the square root of the average squared error.
- **R2 Score:** Measures how well the model explains variations in selling prices.

## 9. Expected Output

The final application will allow users to enter car details such as manufacturing year, present price, kilometers driven, fuel type, seller type, transmission, and previous owners.

Based on these details, the trained Machine Learning model will predict the estimated selling price of the car.

## 10. Conclusion

This project demonstrates how Machine Learning can be applied to a real-world problem in the automobile industry. It helps estimate used car prices by analyzing important vehicle features.

Through this project, I aim to gain practical knowledge of the complete Machine Learning workflow, from data preprocessing and model building to model deployment using Gradio.

---

**Project Domain:** Machine Learning / Data Science

**Project Title:** Car Price Prediction Using Machine Learning
