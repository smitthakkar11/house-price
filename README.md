# house-price
🏠 GeoNest – Real Estate Price Prediction & Recommendation System

Data-driven property valuation and intelligent house recommendation platform built using machine learning.

📌 Project Overview

PropVista is an end-to-end data science project that predicts real estate prices in Gurgaon and recommends similar properties based on user preferences.

The system integrates:

Web scraping

Exploratory Data Analysis (EDA)

Feature engineering

Regression modeling

Content-based recommendation system

🎯 Problem Statement

Real estate pricing is influenced by multiple dynamic factors such as location, size, amenities, and property type.
The objective of this project is to:

Accurately predict property prices using machine learning.

Identify key factors driving real estate valuation.

Recommend similar properties based on user-selected criteria.

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

BeautifulSoup (Web Scraping)

📊 Dataset

Gurgaon real estate listings (flats & houses)

Features include:

Location

Built-up area

Bedrooms

Bathrooms

Furnishing status

Amenities

Price

Data preprocessing included:

Missing value imputation

Outlier treatment

Categorical encoding

Feature scaling

🔎 Exploratory Data Analysis (EDA)

Univariate and multivariate analysis

Price distribution study

Location-wise pricing trends

Correlation analysis

Identification of high-impact features

⚙️ Feature Engineering

Price per square foot

Locality-based aggregations

Encoded categorical variables

Selected relevant predictors using feature selection techniques

🤖 Model Training & Evaluation

Trained and compared multiple regression models:

Linear Regression

Decision Tree

Random Forest

Gradient Boosting

XGBoost

📈 Evaluation Metrics

RMSE (Root Mean Squared Error)

R² Score

The best-performing model was selected based on lowest RMSE and highest R².

🏘️ Recommender System

A content-based recommender system was developed to:

Suggest properties with similar features

Match based on price range, location, area, and amenities

Provide personalized recommendations

Technique used:

Feature similarity comparison

Distance-based similarity scoring

🚀 Project Workflow

Web Scraping

Data Cleaning

EDA

Feature Engineering

Model Training

Model Selection

Recommendation Engine

📌 Key Insights

Location significantly impacts property pricing.

Price per square foot is a strong predictor.

Tree-based models outperformed linear models.

Feature engineering improved prediction accuracy substantially.

🔮 Future Improvements

Deploy as a web application (Streamlit/Flask)

Integrate live scraping pipeline

Add collaborative filtering to recommender system

Incorporate geospatial visualizations

👨‍💻 Author

Smit Thakkar
