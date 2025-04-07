🚗 Vehicle Price Recommender System
This project is a machine learning-powered Vehicle Price Recommender System built using Python and deployed via a Flask web application. It predicts the price of used cars based on various user inputs like manufacturer, fuel type, condition, and more.

🔍 Project Overview
In the used car market, pricing can be highly inconsistent due to various factors such as brand, condition, fuel type, and mileage. This project aims to build a robust regression model to predict vehicle prices accurately. A user-friendly web interface was created where users can input their vehicle specifications and get an estimated price.


📁 Files in This Repo
PRML_ProjCode-GPNo47.ipynb – Full project code including EDA, preprocessing, modeling, and evaluation.

app.py – Flask web application for deployment.

final_random_forest_model.pkl – Final trained model (not included in repo, to be added by user).

preprocessor.pkl – Pipeline object with all preprocessing steps (scaling, encoding).

Cleaned_Car_data.csv – Dataset used to populate dropdowns in the web interface.

🧠 Skills & Tools Used
Programming: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

Machine Learning: Random Forest Regressor, K-Nearest Neighbors, XGBoost, Linear Regression

Data Preprocessing: Label Encoding, One-Hot Encoding, Feature Scaling, Missing Value Imputation

Model Evaluation: RMSE, MAE, R² Score, Cross-validation

Deployment: Flask Web Framework

Version Control: Git & GitHub

📊 Machine Learning Workflow
Data Cleaning & Preprocessing

Handled missing values and irrelevant columns

Created new features (e.g., car_age)

Encoded categorical variables and scaled numerical ones

Model Training & Tuning

Trained multiple models (Random Forest, KNN, XGBoost)

Hyperparameter tuning for model optimization

Final model selection based on performance

Model Deployment

Built a Flask app to make predictions via a user interface

Preprocessed user input using saved pipeline

Deployed the trained model for real-time predictions

🖥️ How to Run This Project Locally
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/vehicle-price-recommender.git
cd vehicle-price-recommender
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Ensure the following files are in the directory:

final_random_forest_model.pkl

preprocessor.pkl

Cleaned_Car_data.csv

Run the Flask app:

bash
Copy
Edit
python app.py
Open your browser and go to http://127.0.0.1:5000/.

✨ Future Enhancements
Add support for additional vehicle features

Implement a dashboard to visualize feature importance

Add model explainability using SHAP

Deploy to cloud platforms like AWS/GCP/Heroku

🙋‍♂️ Author
Rohit Baral
Master’s Student in Data Science
GitHub: https://github.com/baralrohit
LinkedIn:(https://www.linkedin.com/in/rohit-baral-20248b328?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BRaWBDAdvSdaLiwnPAbiVuA%3D%3D)
