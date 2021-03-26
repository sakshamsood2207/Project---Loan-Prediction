# Project---Loan-Prediction
**Introduction**
Predicting the outcome of a loan is a recurrent, crucial and difficult issue in insurance and banking. The objective of our project is to predict whether a loan will default or not based on objective financial data only.
This is a Python-based Project. This project was created via Spyder 3.3.5. IDE (Integrated Development Environment) using Python 3.7.3 and Ipython Console 7.4.0. The final outcome of this project is saved in a Jupyter Notebook v7.8.0. The libraries of python used in this project are:
1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn
5. Stats models
6. Sci-kit Learn

This project is based on a data set provided by the teachers via GITHUB.
Since the objective is to predict the outcome from the information gathered at the signature of the loan, we cannot use the data concerning the history of payments or the current situation of a loan.

Excluding features for which the information is incomplete, or uninformative, we get a total of 19 features, that cover personal information (credit grade, income, housing status, ...) and credit information (amount, interest rates, ...).
Accuracy is not well-suited for our problem. The unbalance of the classes would lead an algorithm to never predict a default. F1-score allows us to quantify a good prediction on both precision and recall.
Loan Prediction

**Problem**
A Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a data set.

**Data**
1. Variable Description
2. Loan ID - Unique Loan ID
3. Gender - Male/ Female
4. Married - Applicant married (Y/N)
5. Dependents - Number of dependents
6. Education - Applicant Education (Graduate/ Undergraduate)
7. Self Employed - Self-employed (Y/N)
8. Applicant Income - Applicant income
9. Co-applicant Income – Co-applicant income
10. Loan Amount - Loan amount in thousands
11. Loan Amount Term - Term of loan in months
12. Credit History - credit history meets guidelines
13. Property Area - Urban/ Semi Urban/ Rural
14. Loan Status - Loan approved (Y/N)


**Accuracy:** - 79.46%
**Cross-Validation Score:** - 84.02%
