# Lending_Club_Loan_Data_Analysis
Deep learning for Lending_Club_Loan_Data_Analysis utilizing Tensorflow and Keras



Description
This project aims to create a model that predicts whether or not a loan will default using historical data. Predicting loan defaults accurately is crucial for companies like Lending Club. The dataset spans from 2007 to 2015 and includes various features related to borrowers' financial attributes.

Problem Statement
The goal is to build a deep learning model that predicts the likelihood of loan default for future loans based on historical data. The dataset is highly imbalanced and contains multiple features, presenting a challenging problem for analysis.

Domain
Finance

Analysis to be Done
Perform data preprocessing and construct a deep learning prediction model.

Dataset Columns and Definitions
credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
purpose: The purpose of the loan (e.g., "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
int.rate: The interest rate of the loan, as a proportion.
installment: The monthly installments owed by the borrower if the loan is funded.
log.annual.inc: The natural log of the self-reported annual income of the borrower.
dti: The debt-to-income ratio of the borrower.
fico: The FICO credit score of the borrower.
days.with.cr.line: The number of days the borrower has had a credit line.
revol.bal: The borrower's revolving balance.
revol.util: The borrower's revolving line utilization rate.
inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
pub.rec: The borrower's number of derogatory public records.
Tasks
Feature Transformation: Convert categorical values into numerical values.
Exploratory Data Analysis: Analyze different factors of the dataset.
Additional Feature Engineering: Check feature correlations and drop strongly correlated features.
Modeling: Build a deep learning model using Keras with TensorFlow backend.
Steps to Perform
Perform data preprocessing.
Conduct exploratory data analysis.
Perform feature engineering.
Build and train the deep learning model.
Evaluate model performance.
Files Included
loan_data.csv: Dataset containing historical loan data.
lending_club_loan_analysis.ipynb: Jupyter Notebook containing the code for data analysis and model building.
Instructions to Run the Code
Clone the repository.
Ensure you have Python installed along with the required libraries (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, and TensorFlow).
Open and run the lending_club_loan_analysis.ipynb file in Jupyter Notebook or any compatible environment.
Follow the instructions within the notebook to execute each cell and analyze the results.
Conclusion
The project aims to provide insights into loan default prediction using deep learning techniques. By leveraging historical data and building predictive models, lenders can make informed decisions and mitigate risks associated with loan defaults.
