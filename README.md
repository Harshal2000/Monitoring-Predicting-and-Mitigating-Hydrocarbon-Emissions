# Monitoring-Predicting-and-Mitigating-Hydrocarbon-Emissions
Project Overview
This project focuses on predicting total hydrocarbon (HC) emissions from maritime vessels using advanced machine learning models. The goal is to identify key factors influencing HC pollution and provide actionable insights for mitigating environmental impact in maritime ports. The project employs various regression models, including Decision Tree, Random Forest, and XGBoost, to analyze a dataset of vessel characteristics and operational parameters.

Key Features
Data Analysis: Utilizes a dataset capturing vessel characteristics such as dead weight, gross tonnage, and engine speed.
Machine Learning Models: Implements and compares the performance of Decision Tree, Random Forest, and XGBoost models.
Performance Metrics: Evaluates models based on Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) metrics.
Feature Importance: Identifies the most significant predictors of HC emissions, with dead weight and gross tonnage emerging as key factors.
Managerial Insights: Provides strategic recommendations for reducing HC pollution, including load optimization, fleet composition adjustments, and speed regulations.
Technologies Used
Python: Primary programming language for data analysis and model implementation.
Pandas & NumPy: For data manipulation and preprocessing.
Scikit-learn: For building and evaluating machine learning models.
Matplotlib & Seaborn: For visualizing data and model performance.

Results
The XGBoost model outperformed other models, demonstrating superior predictive accuracy with the lowest MSE and RMSE values and the highest R² score. The analysis suggests that optimizing vessel load and speed management can significantly reduce HC emissions in maritime ports.

Conclusion
This project provides a comprehensive analysis of HC emissions in maritime environments, offering valuable insights for environmental management and policy-making in the maritime industry. The findings emphasize the importance of data-driven strategies in mitigating pollution and enhancing sustainability in port operations.

How to Run
Clone the repository.
Install the required Python packages using pip install -r requirements.txt.
Run the Jupyter Notebook file to explore the data analysis and model results.

Future Work
Explore additional machine learning models and feature engineering techniques.
Expand the dataset to include more variables and a larger sample size.
Implement real-time data processing for dynamic emissions monitoring.
