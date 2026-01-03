\# Comparative Analysis of ML Methods for E-Commerce Analytics

\*\*Sentiment Classification and Customer Churn Prediction\*\*



\## Project Overview

This project investigates the application of machine learning to two critical e-commerce data types: text-based product reviews and structured behavioral data. We followed the \*\*CRISP-DM\*\* (Cross-Industry Standard Process for Data Mining) methodology to structure our research.





\## Datasets

\* \*\*Sentiment Analysis\*\*: 568,000+ Amazon Fine Food Reviews.

\* \*\*Churn Prediction\*\*: 10,000 Bank Customer Records used to identify at-risk users.



\## Methodology

\* \*\*Text Processing\*\*: Used TF-IDF vectorization with bigrams (5,000 features).

\* \*\*Data Balancing\*\*: Applied \*\*SMOTE\*\* (Synthetic Minority Over-sampling Technique) to handle class imbalances.

\* \*\*Interpretability\*\*: Leveraged \*\*SHAP\*\* and \*\*LIME\*\* to explain model predictions for better business decision-making.



\## Key Results

\* \*\*Sentiment Analysis\*\*: Support Vector Machines (SVM) outperformed Naive Bayes with \*\*78.9% accuracy\*\*.

\* \*\*Churn Prediction\*\*: XGBoost was the top performer with \*\*86.7% accuracy\*\* and a \*\*0.869 ROC-AUC\*\*.



\## Authors

\* \*\*Saatvik Reddy Gutha\*\* (x24257460)

\* \*\*Dattathreya Chintalapudi\*\* (x24212881)



\## How to Run

1\. Install dependencies: `pip install -r requirements.txt`

2\. Run the Jupyter Notebook: `Code.ipynb`

