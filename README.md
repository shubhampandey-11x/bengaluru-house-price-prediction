🏠 Bengaluru House Price Prediction using Machine Learning

This project predicts house prices in Bengaluru based on property features such as location, size (BHK), total square feet, and number of bathrooms. It demonstrates an end-to-end machine learning workflow including data preprocessing, feature engineering, model training, and deployment through a simple web interface.

🚀 Features

Data cleaning and handling missing values

Feature engineering and categorical encoding

Outlier detection and removal

Model training using Linear Regression

Model evaluation using train-test split and cross-validation

Web app for real-time price prediction

🛠 Tech Stack

Python

Pandas, NumPy

Scikit-learn

Flask / Streamlit (for web app)

HTML, CSS (if Flask used)

📊 Dataset

The dataset contains Bengaluru real estate data with the following key attributes:

Location

Total Square Feet

BHK (Bedrooms)

Bathrooms

Price

Data preprocessing includes removing invalid entries, handling missing values, and converting categorical features using one-hot encoding.

🧠 Machine Learning Workflow

Load and explore dataset

Clean data and handle missing values

Perform feature engineering

Remove outliers using statistical methods

Split data into training and testing sets

Train model using Linear Regression

Evaluate using R² score and cross-validation

Save trained model for deployment

🌐 Web Application

The trained model is integrated into a simple web interface where users can:

Enter location

Select BHK and bathrooms

Provide total square feet

Get instant price prediction

This demonstrates how ML models can be used in real-world applications.

📈 Results

The model provides reasonably accurate price predictions for common residential areas and demonstrates how structured real estate data can be used for predictive analytics.

📌 Future Improvements

Try advanced models like Random Forest and XGBoost

Add map-based location selection

Integrate real-time property listing APIs

Improve UI and mobile responsiveness

Add price trend visualization
