# Airbnb-Price-Prediction-and-Value-Identification-Model
Overview
This project focuses on developing predictive models for Airbnb listings, with two primary objectives:

Predict the price of new Airbnb listings.
Identify listings considered as great value.
This involves a comprehensive approach, including data cleaning, feature selection, and machine learning modeling, to aid both Airbnb hosts in maximizing earnings and travelers in finding budget-friendly accommodations with desired amenities.

Business Objectives
Understand the factors that contribute to higher pricing in Airbnb listings.
Develop a predictive model for Airbnb listing prices using significant features.
Create a model to identify Airbnb listings considered as great value based on price, amenities, and guest reviews.
Technical Objectives
Data Understanding: Import the datasets and familiarize with the features.
Data Preparation:
Handle null values and outliers.
Drop non-essential features for price prediction.
Create dummy variables for categorical features.
Remove duplicates and check for multicollinearity.
Visualize data for a comprehensive overview.
Modeling:
Split data into training (80%) and testing (20%) sets.
Standardize features.
Lasso Regression:
Configure parameters, fit the model, predict test data, and assess accuracy.
Fine-tune using grid search and select important features.
Ridge Regression:
Use features from Lasso regression, repeat fitting, and assessment steps.
Value Classification:
Employ Logistic Regression, Decision Tree, and Random Forest to classify listings as great value and select the best model.
Conclusions
The project effectively used Lasso and Ridge regressions for price prediction and a Random Forest Classifier for identifying great value listings. Key insights included:

Bedrooms, bathrooms, and accommodation capacity are crucial price determinants.
Random Forest Classifier provided the best performance in identifying great value listings with an accuracy of 87%.
Future Work
Explore additional features and refine model parameters.
Implement other machine learning algorithms to enhance model accuracy.
