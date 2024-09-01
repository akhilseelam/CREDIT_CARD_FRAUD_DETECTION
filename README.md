# CREDIT_CARD_FRAUD_DETECTION

**DATASET LINK** :- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


**Credit Card Fraud Detection**
This project focuses on building a predictive model for credit card fraud detection using machine learning techniques. The dataset used in this project is a credit card transaction dataset, which includes features derived from real transactions made by European cardholders.

**Project Overview**
The goal of this project is to accurately classify whether a transaction is fraudulent or not. The steps involved include data analysis, feature selection, model training, and evaluation. The Random Forest Classifier is used as the primary model due to its effectiveness in handling imbalanced datasets and providing feature importance insights.

**Workflow**
1)Data Importation:
.The dataset is loaded using Pandas for manipulation and analysis.

2)Data Analysis:
.Basic data exploration is performed to understand the structure and distribution of the data.
.A correlation matrix is plotted using Seaborn to visualize relationships between features.

3)Feature Selection:
.The ExtraTreesClassifier is utilized to determine the most important features influencing the target variable.
.The top 18 features are selected and visualized using a bar plot.

4)Model Training:
.The dataset is split into training and testing sets using an 80-20 split.
.The RandomForestClassifier is trained on the selected features from the training set.

5)Model Evaluation:
.The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score.
.Predictions on the test set are compared with actual values to assess the model's effectiveness.

Dependencies
->Python 3.x
->Pandas
->NumPy
->Matplotlib
->Seaborn
->Scikit-learn
