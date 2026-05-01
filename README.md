📊 Customer Churn Analysis & Prediction
Project Overview:-
This project focuses on identifying key factors that lead to customer attrition (churn) in a telecommunications company. Using Python and Machine Learning, I performed an end-to-end analysis to predict which customers are likely to leave, providing actionable insights for retention strategies.

The Business Problem:-
Customer acquisition is often more expensive than retention. By predicting churn, the company can proactively offer incentives to high-risk customers, directly impacting the bottom line.

🛠️ Tech Stack & Tools
Language: Python  

Data Manipulation: Pandas, NumPy  

Visualization: Matplotlib, Seaborn  

Machine Learning: Scikit-Learn  

Environment: Jupyter Notebook

📈 Key Insights from EDA
Based on the exploratory data analysis, the following trends were observed:

High Churn Segments: Customers on month-to-month contracts show a significantly higher churn rate compared to those on one- or two-year contracts.  

Price Sensitivity: There is a clear correlation between high monthly charges and the likelihood of churn.  

Service Impact: Customers without tech support or online security services tend to leave at higher rates.

Machine Learning ImplementationI utilized a Random Forest Classifier to build the predictive model.  Preprocessing: Handled missing values, encoded categorical variables (like Gender and Contract), and scaled numerical features.  Ensemble Method: Leveraged Bagging logic to reduce variance and improve model robustness.  Evaluation: The model was evaluated based on accuracy, precision, and recall to ensure it captures as many potential "churners" as possible.

