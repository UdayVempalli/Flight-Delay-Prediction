# Syracuse Flight Arrival Delay Prediction

## Overview
This project focuses on predicting flight arrival delays at Syracuse Hancock International Airport (SYR) using advanced machine learning techniques. By integrating historical flight data with detailed weather information, we've developed a robust prediction model that can forecast flight statuses (Early, On-time, or Late) for both incoming and subsequent flights.

## Key Features
- Prediction of flight arrival statuses using machine learning models
- Integration of historical flight data with real-time weather information
- Analysis of cascading effects of delays on subsequent flights
- Comparison of multiple machine learning algorithms (Random Forest, Gradient Boosting, XGBoost)
- Feature importance analysis for understanding key factors affecting flight delays

## Data Sources
- Flight data: Bureau of Transportation Statistics (BTS)
- Weather data: Open Meteo's historical weather API and forecast weather API

## Methodology
1. Data Collection and Merging
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Model Training and Testing
   - Random Forest Classifier
   - Gradient Boosting Classifier
   - XGBoost Classifier
5. Hyperparameter Tuning
6. Feature Importance Analysis
7. Prediction for First and Subsequent Flights

## Results
- XGBoost Classifier demonstrated the best performance with an accuracy of approximately 55% on the test set
- Inclusion of previous flight status improved the accuracy to 59% for predicting subsequent flight statuses
- Weather conditions (snowfall, rain) and scheduled departure time were identified as crucial factors in predicting delays

## Future Work
- Incorporate real-time data feeds for more accurate predictions
- Explore additional features that may impact flight delays
- Investigate the possibility of integrating the model into airport operations systems

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn

## Acknowledgments
- Syracuse University
- Bureau of Transportation Statistics
- Open Meteo for providing weather data APIs
