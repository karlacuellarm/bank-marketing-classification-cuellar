# Bank Marketing Classification Project

This project develops a binary classification process using the Bank Marketing dataset. The main objective is to predict whether a client subscribes to a term deposit based on demographic, financial, and campaign-related variables.

## Project objective

The objective of this notebook is to apply and compare different classification models using PySpark MLlib. The process includes exploratory data analysis, data preprocessing, feature transformation, model training, evaluation, and comparison.

## Dataset

The dataset contains information from a bank marketing campaign. The target variable is `y`, which indicates whether the client subscribed to a term deposit:

- `yes`: the client subscribed.
- `no`: the client did not subscribe.

Some of the main variables analyzed are:

- `age`: client age.
- `job`: type of job.
- `balance`: average yearly balance.
- `duration`: last contact duration in seconds.
- `campaign`: number of contacts during the campaign.
- `pdays`: days since the client was last contacted in a previous campaign.
- `previous`: number of contacts before this campaign.
- `poutcome`: outcome of the previous campaign.

## Models evaluated

The following classification models were implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosted Tree
- Support Vector Machine
- Multilayer Perceptron

## Evaluation metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Curve

## Main findings

The exploratory analysis showed the importance of understanding variable distributions, outliers, class imbalance, and relationships between predictors and the target variable before training the models.

The Gradient Boosted Tree model achieved the best overall performance, with the highest accuracy, F1-score, and ROC-AUC values. The feature importance analysis showed that variables related to previous campaign outcomes and contact month contributed significantly to the prediction.

## Tools used

- Python
- PySpark
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Author

Karla Cuellar
