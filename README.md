# analytics-projects
These are my projects

Bike Rental Prediction Project
Overview
This project aims to develop a machine learning model to predict the number of bike rentals based on various environmental and seasonal factors. The goal is to provide insights into bike rental demand, which can be valuable for bike-sharing companies to optimize their operations and resources.

Dataset
The dataset used for this project contains the following columns:

Date
Rented Bike Count
Hour
Temperature (°C)
Humidity (%)
Wind speed (m/s)
Visibility (10m)
Dew point temperature (°C)
Solar Radiation (MJ/m2)
Rainfall (mm)
Snowfall (cm)
Seasons
Holiday
Functioning Day
Methodology
Data Exploration and Preprocessing:
Explore the dataset to understand its structure, features, and distributions.
Handle missing values, outliers, and data inconsistencies.
Encode categorical variables and perform feature scaling as necessary.
Model Development:
Train machine learning models to predict the number of bike rentals.
Experiment with different algorithms such as Random Forest Regression and Gradient Boosting Regression.
Perform hyperparameter tuning using techniques like Grid Search to optimize model performance.
Model Evaluation:
Evaluate model performance using metrics such as Mean Squared Error (MSE) and 
𝑅
2
R 
2
  Score.
Compare the performance of different models and select the best-performing one.
Deployment:
Deploy the trained model for real-time predictions or integrate it into existing systems.
Results
After training and evaluating several machine learning models, the Gradient Boosting Regression model with the following hyperparameters achieved the best performance:

Learning Rate: 0.1
Max Depth: 5
Min Samples Split: 3
Number of Estimators: 150
The model achieved a Mean Squared Error (MSE) of approximately 73937.22 and an 
𝑅
2
R 
2
  Score of approximately 0.795 on the test data.

Future Work
Explore additional feature engineering techniques to capture more information from the dataset.
Experiment with ensemble methods and advanced machine learning techniques to further improve model performance.
Continuously monitor and update the model as new data becomes available to ensure its accuracy and relevance.
Dependencies
Python 3.x
scikit-learn
pandas
numpy
