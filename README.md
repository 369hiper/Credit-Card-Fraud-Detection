# Credit-Card-Fraud-Detection
In this Project, We are Operating an Online Book store, Not as big as Amazon/Kindle. However, This E-Commerce also had a Transaction Traffic of 1,000s of Books. We’ll use an available dataset for these, that have Real Credit Card Transactions that have been anonymized for curtesy of Privacy of the Customers. The Problem with Credit Card fraud Detection is that anyone can steal their 15/16 Digit numeric digits with a Security Code and an Expiration date to make Online Purchases in the CardHolder’s Name.

I am using Python 3.6.1 for this project. You need to install the following Python libraries.
 1. NumPy (for documentation:http://www.numpy.org/)
 2. Pandas (for documentation:http://pandas.pydata.org/)
 3. Scikit-Learn (for documentation:http://scikit-learn.org/stable/)
 4. Seaborn (for documentation:https://seaborn.pydata.org/)
I have been using Jupyter Notebook for this project.

# Code:
The code contains in the 'credit_card_fraud_detection.ipynb' file.
# Data
The data contains in the 'creditcard.csv' file.
As the file is too big to upload in the repository, to download the file please follow the link below:
creditcard.csv.zip (https://www.kaggle.com/dalpozz/creditcardfraud/downloads/creditcardfraud.zip)
The above file is in .zip format. Please extract the file to get the .csv file out of it.

# Data Description
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
1. Outlier Fraction - 0.0017304750013189597
2. Fraud Cases: 492
3. Valid Cases: 284315


 The Criteria for Detection of Fraudulent Transactions are simple as Follows -:

  1. Is This the first purchase ever from the Consumer and it’s over 500$.
  2. The IP-Address (Internet Protocol) is from Country (A) [China], The Billing Address is from Country (B) [Germany] and The Shipping      Address is from Country (C) India.

We’re trying to Protect the CardHolder’s Who own the Credit Card from those who have stolen the Credit Card and are trying to make fraudulent transaction in their Name.

# Challenges Faced
One of the Biggest Challenge with This Problem is that the Vast Majority of the Transaction are Non-Fraudulent, This will make it Harder for us, to detect the Underlying Patterns in the Information Available.
# Steps for Overcoming for Challenge
To Overcome This Problem, We will apply different Sampling Techniques and Different Metrics Available with 99.94% Accuracy that information is any Good.

# Data Description
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
1. Outlier Fraction - 0.0017304750013189597
2. Fraud Cases: 492
3. Valid Cases: 284315
