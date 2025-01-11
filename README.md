# Supervised-Salary-Prediction

Here’s the description translated into English:

Project "Supervised-Salary-Prediction" aims to develop a supervised regression model to predict salaries based on historical data.

Project Goals:
To build a machine learning regression model that predicts an individual's salary based on features like experience level, job title, and company location.

Dataset:
The project uses a dataset containing information such as:

work_year: The year of the job data.
experience_level: Job experience level (e.g., Junior, Senior).
job_title: Job title.
salary_in_usd: Annual salary in USD (target variable).
remote_ratio: The percentage of remote work (0–100).
company_location: Company location.
company_size: Company size (Small, Medium, Large).
Models Used:
Several machine learning algorithms were implemented and evaluated, including:

Linear Regression
Random Forest
Decision Tree
Support Vector Regressor (SVR)
XGBoost
Results:
The XGBoost model achieved the best performance with:

R² on training data: 31.81%
R² on testing data: 26.52%
RMSE: $59,374
Technologies Used:

Programming Language: Python
Libraries:
Data Analysis: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: scikit-learn, XGBoost
Environment: Jupyter Notebook / Google Colab
Key Features:

Outlier Handling: Ensures the model can handle extreme salary values without affecting predictions.
Model Comparison: Evaluates basic models (Linear Regression) and advanced models (XGBoost).
Interpretability: Provides insights into the impact of various features on salary predictions.
Next Steps:

Feature Engineering: Add other relevant features, such as industry, education level, or skills.
Hyperparameter Tuning: Further optimize the model to improve performance.
Deployment: Deploy the model as a web application (e.g., using Flask or Streamlit) for real-world use.
For more details and the complete code, visit the project's GitHub repository: Supervised-Salary-Prediction by JamesKun21.






