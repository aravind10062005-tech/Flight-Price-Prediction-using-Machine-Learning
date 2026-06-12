# Flight Price Prediction using Machine Learning

## Project Overview

Flight ticket prices vary based on multiple factors such as airline, source, destination, duration, number of stops, and travel dates. Predicting flight prices helps travelers and businesses make informed decisions and optimize travel planning.

This project uses Machine Learning techniques to predict flight ticket prices based on historical flight data.

---

## Problem Statement

Airfare prices fluctuate frequently due to demand, seasonality, airline policies, and route characteristics.

The objective of this project is to build a predictive model that accurately estimates flight ticket prices using various flight-related features.

---

## Business Objective

The project helps:

- Travelers estimate future flight costs
- Travel agencies optimize pricing strategies
- Businesses manage travel budgets
- Airlines understand pricing patterns

---

## Dataset Description

The dataset contains flight-related information including:

### Features

- Airline
- Date of Journey
- Source
- Destination
- Route
- Duration
- Total Stops
- Additional Information
- Departure Time
- Arrival Time

### Target Variable

- Price (Flight Ticket Cost)

---

## Project Workflow

### 1. Data Collection

- Load flight dataset
- Understand feature distributions
- Analyze target variable

### 2. Data Preprocessing

- Handle missing values
- Extract date and time features
- Convert categorical variables
- Feature encoding
- Feature scaling

### 3. Exploratory Data Analysis (EDA)

- Airline-wise price analysis
- Route analysis
- Duration impact analysis
- Stop-wise fare comparison
- Correlation analysis

### 4. Feature Engineering

- Journey Day & Month extraction
- Departure Hour extraction
- Arrival Hour extraction
- Duration transformation
- Route processing

### 5. Model Building

Regression Algorithms Used:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- Gradient Boosting Regressor

### 6. Model Evaluation

Evaluation Metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### 7. Price Prediction

The final model predicts the estimated flight ticket price based on user inputs.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Jupyter Notebook

## Machine Learning Pipeline
- Data Collection
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Feature Selection
- Model Training
- Model Evaluation
- Flight Price Prediction

##Results
The model successfully predicts flight ticket prices with high accuracy, helping users estimate airfare costs and understand factors affecting ticket pricing.

## Key Insights
- Airline type significantly affects ticket prices.
- Flights with multiple stops are generally cheaper.
- Travel duration impacts fare pricing.
-  Seasonal demand influences ticket costs.

##Future Improvements
- Hyperparameter Tuning
- Real-Time Flight Data Integration
- Streamlit Web Application
- API Deployment using Flask/FastAPI
- Cloud Deployment (AWS/Azure)

## Skills Demonstrated
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Regression Modeling
- Model Evaluation
- Predictive Analytics
- Machine Learning

## Author
Aravind
