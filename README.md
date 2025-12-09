Insurance Premium Prediction :

This project predicts the Annual Health Insurance Premium Amount for customers using demographic, lifestyle, income, and medical information. It includes a complete machine learning workflow and a Streamlit web application for real-time premium prediction.

1. Project Objectives
- Analyze customer data to understand factors influencing premium amounts
- Perform data cleaning, preprocessing, and feature engineering
- Build and evaluate machine learning models for premium prediction
- Deploy the best-performing model through a Streamlit web app
- Provide a simple and interactive UI for real-time premium estimation

2. Dataset Information
The dataset contains the following features:
Age
Gender
Region
Marital_status
Number_Of_Dependants
BMI_Category
Smoking_Status
Employment_Status
Income_Level
Income_Lakhs
Medical_History
Insurance_Plan
Genetical_Risk
Annual_Premium_Amount (Target Variable)

The dataset was sourced from a publicly available online resource.

3. Technologies Used
Python
Pandas and NumPy
Matplotlib and Seaborn
Scikit-Learn
XGBoost (optional)
Joblib
Streamlit
Git and GitHub

4. Steps Followed in the Project

4.1 Data Cleaning and Preprocessing
- Handled missing values
- Encoded categorical variables using Label Encoding or One-Hot Encoding
- Treated outliers using IQR or Z-score techniques
- Converted and standardized income-related fields

4.2 Exploratory Data Analysis (EDA)
- Analyzed feature distributions and premium patterns
- Visualized relationships for age, BMI category, income level, smoking status, and genetic risk
- Identified important factors affecting premium values

4.3 Feature Engineering
- Extracted relevant features
- Applied scaling where required
- Created a correlation matrix to understand feature importance

4.4 Model Building
Models used in the project:
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor (optional)

4.5 Model Evaluation
Evaluation metrics used:
R2 Score
Mean Absolute Error (MAE)
Root Mean Square Error (RMSE)

Ensemble models such as Random Forest and Gradient Boosting performed better than linear models.

5. Streamlit App

The project includes an interactive Streamlit web app for premium prediction.

App Features:
- Dropdown and numeric input fields for customer attributes
- Predict button to calculate the estimated annual premium
- Loads trained model and scaler from joblib artifacts

Deployment Tools:
Streamlit
Joblib
Git and GitHub

7. How to Run the Project
Step 1: Clone the repository
git clone <your-repo-link>
cd <project-folder>

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Run the Streamlit app
cd app
streamlit run main.py

8. Results and Insights
- Premium amount is strongly influenced by age, BMI category, smoking status, income levels, and genetic risk
- Customers with higher BMI, smoking habits, or high genetic risk tend to pay higher premiums
- Ensemble models delivered the highest prediction accuracy

9. Conclusion
This project demonstrates a complete ML pipeline, from data preprocessing and EDA to model development and deployment using Streamlit. It helps insurance companies predict premium amounts, identify high-risk customer segments, and understand premium pricing trends.
