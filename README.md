# diabetes-data-analysis
This project focuses on analyzing and predicting hospital readmissions in diabetic patients within 30 days, leveraging data analytics and visualisations. 
It provides insights into the factors affecting readmissions among diabetics, including demographic, medical, and treatment-related variables.
It also includes a trained logistic regression model but the focus of the project is on analytics and visualisations.

Project Files
1. 725 dataset table (description of dataset).xlsx is a comprehensive description of the dataset used in the project.
It contains metadata about the variables in the dataset, including column names, data types, and brief explanations of their meanings.
Helps users understand the context and structure of the data.

2. data_analytics_visualisation.ipynb is a Jupyter Notebook for performing exploratory data analysis (EDA).
It includes data cleaning, visualizations, and statistical summaries to explore trends and correlations in the dataset.
Outputs: Visualizations and insights into the readmission patterns.

3. Demographic Analysis of Readmission Within 30 Days_v2023.3.twb is a Tableau workbook focused on analyzing demographic trends related to 30-day readmissions.
Includes dashboards and charts highlighting readmission rates by age, gender, ethnicity, and other demographic variables.
Outputs: Interactive visualizations for deeper demographic insights.

4. diabetic_data.csv is the primary dataset used in the project.
It contains records of diabetic patients, including medical history, demographics, lab results, medications, and 30-day readmission outcomes.
Basis for all analyses, visualizations, and predictive models.

5. Impact of HbA1c Levels on Patient Readmission Rates.twb is a Tableau workbook analyzing the impact of HbA1c levels (a key diabetes biomarker) on readmission rates.
Provides interactive dashboards to explore how controlled and uncontrolled HbA1c levels influence patient outcomes.
Outputs: Data-driven insights on HbA1c levels and their implications.

6. model.pkl is a logistic regression model trained on the dataset. It can be loaded and used to predict 30-day readmissions based on patient features.
Represents the culmination of machine learning efforts in the project.

7. Medical Specialties Dashboard.twb is a Tableau workbook analyzing readmission trends across different medical specialties.
Highlights specialties with higher or lower readmission rates, helping identify focus areas for improvement.
Outputs: Specialty-based insights for healthcare optimization.

8. machine_learning_prediction.ipynb is a Jupyter Notebook implementing machine learning models to predict 30-day readmissions.
Includes steps like feature engineering, model training, hyperparameter tuning, and performance evaluation.
Outputs: Model metrics (accuracy, precision, recall) and predictions.

9. Impact of Hospital Stay Duration and Medication on Readmission Rates.twb is a Tableau workbook exploring the relationship between hospital stay duration, medication usage, and readmission rates.
Provides interactive charts to understand how length of stay and specific medications influence outcomes.
Outputs: Actionable insights into hospital operations and treatment protocols.

How to Use the Repository
1. Data Exploration:
- Start with data_analytics_visualisation.ipynb to clean and explore the dataset.
- Use Tableau workbooks (.twb files) for in-depth analysis and visualization.

2. Model Prediction:
- Load and test the model.pkl file using machine_learning_prediction.ipynb for predictions on new data.

3. Dataset Reference:
- Refer to 725 dataset table (description of dataset).xlsx for understanding dataset columns and their meanings.
