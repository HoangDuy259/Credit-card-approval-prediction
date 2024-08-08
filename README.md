# Credit-card-approval-prediction
Predicting creditworthiness involves using statistical or machine learning models to estimate a borrower’s loan repayment ability. This tool is essential for credit institutions (CIs) to minimize lending risks and improve operational efficiency.
Factors affecting creditworthiness include:
* Personal Information: Age, gender, education level, occupation, marital status, etc.
* Financial Information: Income, assets, credit history, etc.
* Loan Information: Purpose of the loan, loan amount, loan term, etc.

This report uses machine learning algorithms such as Random Forest, Decision Tree, Naïve Bayes, and Logistic Regression to analyze and predict creditworthiness. The data used was collected from Kaggle and downloaded in CSV format. The analysis process includes the following steps:
1. Creating a target variable for the data.
2. Merging two separate datasets into a single dataset.
3. The data was split into two parts: 80% for training and 20% for testing.
4. Applying Logistic Regression, ID3, Naïve Bayes, and Random Forest algorithms for classification on the training set.
6. Making predictions and evaluating the model using the test set.

The results show that the Random Forest algorithm achieves the highest accuracy, with an accuracy of 89%.

# Run
```plaintext
Streamlit run cc_approval_pred_1.py


