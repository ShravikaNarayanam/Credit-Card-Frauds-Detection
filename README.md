# Credit-Card-Frauds-Detection

The aim of this project is to develop Machine Learning and Deep Learning models to detect anomalies in credit card transactions. 
The machine learning models implemented are Logistic Regression, K-Nearest Neighbors, Random Forest, AdaBoost, XGBoost, Gaussian 
Naive Bayes and Decision Tree. The purpose of choosing these models is to compare the performance of the ensemble models with the 
rest. Deep Learning based Autoencoders are implemented which outperform ensemble models. The datasets contain transactions made by 
credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 
492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all 
transactions. To balance the dataset, SMOTE sampling is implemented. To measure the performance of the model along with accuracy, 
precision and recall, ROC-AUC is also used.

## Steps to run the code in Google Colab:

- Get Kaggle API Token
- Upload kaggle.json into Google Drive
- Create a new Colab notebook
- Mount the drive to colab notebook
- Provide the config path to kaggle.json
- Download the kaggle dataset 

link to dataset: https://www.kaggle.com/mlg-ulb/creditcardfraud
