# Loan-Approval-Prediction-with-ML

## Introduction
Loan approval is a critical decision-making process for financial institutions, requiring thorough assessment of an applicant's creditworthiness. This project uses machine learning to automate the prediction of loan approval based on various applicant features, such as income, credit history, and employment status. By analyzing historical data, the model learns to identify patterns that indicate a successful loan application, helping lenders streamline their decision-making process and reduce manual effort.
## Dataset
The dataset includes the following features:

ApplicantIncome: Income of the loan applicant.
CoapplicantIncome: Income of the co-applicant (if any).
LoanAmount: The loan amount requested.
Loan_Amount_Term: Term of the loan (in months).
Credit_History: Whether the applicant has a credit history (1: Yes, 0: No).
Gender: Gender of the applicant.
Married: Marital status of the applicant.
Dependents: Number of dependents.
Education: Education level of the applicant (Graduate/Not Graduate).
Self_Employed: Whether the applicant is self-employed (Yes/No).
Property_Area: The area of the property (Urban, Semiurban, Rural).
Loan_Status: The target variable, indicating if the loan was approved (Y/N).

## Technologies Used
Programming Language: Python
Libraries:
pandas for data manipulation
numpy for numerical computations
scikit-learn for machine learning models
matplotlib and seaborn for data visualization
Gradio for creating the app interface.
## Results
he final model achieved an accuracy of 91%, effectively predicting loan approvals based on the input features. The following models were trained and evaluated:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
Best Model: Random Forest Classifier with an accuracy of 91%.
## Future Work
Enhance feature engineering by adding more features such as applicant's employment history.
Explore more advanced models like Gradient Boosting Machines (GBM) or Neural Networks.
Improve the Gradio app to include more visualizations and explanations for users.
## Contact
HARSHINI - harshiniudayagiri123@gmail.com
