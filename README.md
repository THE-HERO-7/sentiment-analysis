# Credit Card Fraud Detection using Ensemble models

A machine learning project to detect credit card fraud using the popular imbalanced dataset from Kaggle.

## Dataset
[Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Overview
- Preprocessed highly imbalanced data
- Applied class weighting via `scale_pos_weight`
- Trained ensemble models- RandomForest, XGBoost,LightBoost
- Evaluated via ROC AUC and confusion matrix
- Achieved 0.86 recall and 0.94 precision on fraud class

## Final Results
- **XGBoost gives the best scores of evaluation metrices**
- **Recall (fraud): 0.86**
- **Precision (fraud): 0.94**
- **ROC AUC: 0.93**

## How to Run
1. Clone this repo
3. Run the notebook inside `/notebooks/`

## Notes
- Dataset is not included due to size. Download it from Kaggle.
- Full project also hosted on [Kaggle Notebook](https://www.kaggle.com/code/errorcoder/creditcardfrauddetection-using-xgboost)

## Author
AJ
