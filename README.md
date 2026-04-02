Marketing Predictive Modeling – School Inquiry Prediction
Project Overview

This project uses marketing and web analytics data to predict the number of school inquiries.
The goal is to help marketing teams forecast demand and allocate budget more efficiently across paid, owned, and organic channels.

Business Problem

Schools and universities invest heavily in marketing (Google Ads, SEO, social media, portals, etc.), but it is difficult to know:

Which channels drive inquiries
How search trends affect inquiries
How many inquiries to expect in the future

This project builds a predictive model to forecast school inquiries using marketing data and search behavior data.

Data Used

The model uses the following variables:

Total Search Volume
Google Impressions
Clicks
Page Views
Sessions
New Users
User Engagement
Google Trends Data
Lag Features (previous weeks/months data)

Target variable:

School Inquiries
Feature Engineering

Key feature engineering steps:

Created lag features (e.g., last 1 week, last 2 weeks search volume)
Created moving averages
Handled missing values
Standardized numerical variables
Removed multicollinearity
Modeling Methods

Models tested:

Linear Regression
Random Forest
XGBoost
Time Series Models (optional)

Model evaluation metrics:

RMSE (Root Mean Square Error)
MAE (Mean Absolute Error)
R² Score
Project Workflow
Data Collection
Data Cleaning
Feature Engineering (Lag Features, Moving Average)
Exploratory Data Analysis (EDA)
Model Training
Model Evaluation
Prediction / Forecast
Marketing Insights & Recommendations
Tools & Technologies
Python
Pandas
Scikit-learn
XGBoost
Google Trends
Tableau (for dashboard)
SEMrush (SEO data)
Google Analytics
Results / Insights

Example insights:

Search volume is a leading indicator of school inquiries
Paid search drives short-term inquiries
SEO drives long-term inquiries
Lag features significantly improve prediction accuracy
How to Run This Project
Clone this repository

Install required packages:

pip install -r requirements.txt

Run the model:

python train_model.py
Future Improvements
Add more marketing channels
Use Prophet or advanced time series models
Automate Google Trends data pipeline
Deploy model as dashboard
Author

Jacob Chen – Marketing Data Analyst / Data Scientist

License

This project is licensed under the MIT License.
