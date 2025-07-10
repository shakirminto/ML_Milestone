# ML_Milestone
This project focuses on predicting loan approval status using machine learning techniques. The model helps automate and improve the loan approval process. 

Project Overview:
This project aims to predict loan approval status for applicants based on demographic, financial, and asset information. Using a real-world dataset, we apply machine learning techniques to automate and improve the accuracy of the loan approval process.

Workflow

1. Data Loading and Inspection:
Loaded the loan approval dataset into a pandas DataFrame.
Inspected the structure, columns, and data types.
Checked for and handled missing values.

2. Data Cleaning and Preparation:
Stripped unnecessary spaces from column names and categorical data.
Filtered out records with unclear loan status.
Encoded the loan status into binary values (Approved = 1, Rejected = 0).

3. Feature Engineering:
Label encoded categorical variables such as education and self-employed status.
Created a new feature (log_income) by applying a logarithmic transformation to the applicant’s income to reduce skewness.

4. Data Splitting:
Split the dataset into input features and the target variable.
Divided the data into training and testing sets to ensure fair evaluation of model performance.

5. Model Training:
Trained a Random Forest Classifier on the training dataset to learn patterns for loan approval prediction.

6. Model Evaluation:
Made predictions on the test dataset.
Evaluated model performance using accuracy, confusion matrix, and classification report (precision, recall, F1-score).

7. Visualization:
Visualized feature importance to interpret which variables most influence loan approval decisions.
Plotted confusion matrix and compared actual vs. predicted outcomes to assess model effectiveness.

Key Insights:
The machine learning model can successfully predict loan approval status with good accuracy.
Features such as applicant income, CIBIL score, and asset values are highly influential in determining loan approvals.


