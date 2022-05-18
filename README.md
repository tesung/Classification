# Classification

### Abstract

The goal of this project is to use classification models to predict fraudulent bank transactions in order to improve the security of ABC bank and protect its customers' financial assets. I obtained a dataset form [kaggle](https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction) and focused on feature engineering and used logistic regression, oversampling, and class weight balance as my main model training tools. 

### Design

The main issue this project aims to solve is to strengthen the bank security system and optimize flagging fraudulent transactions. However, it is important to realize >90% of the transactions are legitimate; as such, it is a difficult feat to train a machine to lock onto those subtle trends. Utilizing classification ML model training methods will help the bank achieve its goal.

### Data

The data is downloaded from Kaggle and contains 6,362,620 rows with 11 columns. Most of the columns are integer or float data and the nature of the data focuses around transaction amount, transcation type, sender account balance, reciever account balance, and whether or not the transaction is fraudulent. In depth EDA and feature engineering such as dummy creation is necessary.

### Algorithm & Tools

I built a classification model in python using logistic regression with feature engineering, up-sampling, and class imbalance techniques. Since the goal is to flag fraudulent charges, I chose to focus on improving the recall score in exchange for precision. The theory is customers would rather have the bank flag a transaction and seek clarification over letting a transaction through at the cost of having their money stolen. 

The main packages used are sklearn, pandas, numpy, imblearn, matplotlib, and seaborn. 




