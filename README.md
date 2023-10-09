# Project-ATM-Fraud-Detection-Model
This is an End to End project on how to build a Machine Learning model that helps to predict fraudulent ATM transactions by using certain input data

Fraud Detection

ATM fraud detection is of paramount importance in the banking sector for the following reasons:

1. Financial Loss Prevention: ATM fraud can result in significant financial losses for both banks and customers. Detecting and preventing fraudulent activities helps minimize these losses, ensuring the financial stability of the banking institution and the trust of its customers.

2. Customer Trust and Confidence: Effective ATM fraud detection mechanisms reassure customers that their funds and personal information are secure. Maintaining trust is essential for retaining existing customers and attracting new ones.

3. Reputation Management: A bank's reputation is a critical asset. Incidents of ATM fraud can damage a bank's reputation and lead to a loss of customers. Robust fraud detection and prevention measures demonstrate a commitment to security and can help safeguard a bank's reputation.

4. Operational Efficiency: ATM fraud can lead to operational disruptions, including customer service inquiries, investigations, and card replacements. Efficient fraud detection reduces the workload associated with managing fraudulent transactions.

5. Technological Advancements: As technology evolves, so do the tactics used by fraudsters. Continuous investment in fraud detection systems is essential to stay ahead of emerging threats.

Hence, Fraud detection is a critical component of the banking sector's security framework. It safeguards financial institutions, their customers, and their reputations, while also ensuring regulatory compliance and operational efficiency.

About Dataset
Building a Fraudelent prediction model, dataset used is provided by an Australian bank, whose profitability and reputation are being hit by fraudulent ATM transactions. They want help in reducing and if possible completely eliminating such fraudulent transactions. This can be done by building a predictive model to catch such fraudulent transactions in real time and decline them. The challenging part of the problem is that the data contains very few fraud instances in comparison to the overall population. To give more edge to the solution they have also collected data regarding location geo_scores of the transactions, their own proprietary index Lambda_wts, on network turn around times Qset_tats and vulnerability qualification score instance_scores. Training data contains masked variables pertaining to each transaction id . The prediction target here is 'Target'.

1: Fraudulent transactions

0: Clean transactions

Features
The dataset contains masked variable for both train and test data, to protect the confidentiality.

The dataset can also be found within this repository.

Data Preprocessing is done by using missing value imputation, imbalance data treatment by using Over Sampling technique.

Exploratory Data Analysis (EDA) has been performed by using dataprep package to understand the distribution and behaviour of all the input features.

Model Building Logistic Regression for binary classification, Random Forest, XGB Classifier models are used and to build the final implementable machine learning model Radom Forest is used. The model is having train and test accuracy of 100% and 99% repectively and 99% on test and train mean accuracy on 10 fold Cross Validation.

Model Evaluation: Model's performance has been evaluated using Classification Report, Confusion Matrix, Accuracy score, Recall Score and Cross Validation tests for both test and train datasets.

You can follow the jupyter notebook available in this repository to get more insights about the procedure and methodologies.
