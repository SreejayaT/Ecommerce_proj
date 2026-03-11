ONLINE SHOPPER PURCHASE PREDICTION

Project Overview:
This project predicts whether a visitor will make a purchase during an online shopping session using machine learning.

The goal is to identify high-intent customers based on their browsing behavior so that businesses can target them with marketing actions.

------------------------------------------------------------

Dataset:
The dataset contains session-level data from an e-commerce website. Each row represents a user session.

Key features include:
- Page visit counts
- Session duration
- Bounce rates and exit rates
- Visitor type
- Month of visit

Target Variable:
Revenue
1 → purchase occurred
0 → no purchase

------------------------------------------------------------

Workflow:

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and encoding
3. Model training and evaluation
4. Hyperparameter tuning
5. Model explainability using SHAP
6. Threshold optimization
7. Customer intent segmentation

------------------------------------------------------------

Models Used:

The following machine learning models were tested:

- Logistic Regression
- Random Forest
- XGBoost

The XGBoost model achieved the best performance with a ROC-AUC of approximately 0.92.

------------------------------------------------------------

Key Insights:

- User engagement features strongly influence purchases.
- Higher PageValues and longer ProductRelated_Duration increase purchase likelihood.
- High BounceRates and ExitRates reduce the chance of conversion.

------------------------------------------------------------

Customer Segmentation:

Based on predicted purchase probabilities, users were segmented into three groups:

Low Intent      → low probability of purchase
Medium Intent   → moderate probability
High Intent     → high probability of purchase

This segmentation can help businesses prioritize marketing strategies.

------------------------------------------------------------

Tools and Libraries:

- Python
- Pandas
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn

------------------------------------------------------------

Future Work:

Possible improvements include:
- Deploying the model using FastAPI
- Monitoring model performance over time
- Adding additional behavioral features
