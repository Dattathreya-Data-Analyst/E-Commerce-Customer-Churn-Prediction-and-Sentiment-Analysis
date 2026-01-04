# E-Commerce Intelligence Hub: Sentiment & Churn Analytics

### 🚀 Strategic Customer Insight Dashboard | MSc Data Analytics Project

**A Dual-Track Machine Learning Solution for Customer Experience (CX) Optimization**

---

## 📌 Project Overview
This project bridges the gap between **unstructured text data** and **structured behavioral analytics**. By strictly following the **CRISP-DM** methodology, we developed an end-to-end system that not only predicts *who* will leave the platform but understands *why* they are dissatisfied.

This repository contains the code and resources for:
1.  **Sentiment Intelligence (NLP):** Automated classification of product reviews to monitor brand health.
2.  **Churn Risk Scoring:** Predictive modeling to identify high-risk banking/e-commerce customers.

---

## 📊 Key Performance Metrics (Updated)

| Track | Champion Model | Accuracy | Key Metric |
| :--- | :--- | :--- | :--- |
| **Sentiment Analysis** | **Support Vector Machine (SVM)** | **84.56%** | **0.51 Kappa** (Moderate-Strong Agreement) |
| **Churn Prediction** | **XGBoost Classifier** | **77.74%** | **0.836 ROC-AUC** (High Predictive Power) |

> *Note: While Random Forest offered competitive accuracy, XGBoost was selected as the champion for Churn Prediction due to its superior stability in distinguishing between positive and negative classes (ROC-AUC).*

---

## 🛠️ Tech Stack & Methodology

* **Languages:** Python (Pandas, NumPy, Scikit-Learn), DAX (Power BI).
* **Text Processing:** TF-IDF Vectorization (5,000 features), Bigram analysis.
* **Data Handling:** **SMOTE** (Synthetic Minority Over-sampling) for class balancing.
* **Explainable AI (XAI):**
    * **LIME:** Used to visualize feature importance in text (e.g., "disappointed" = Negative).
    * **SHAP:** Used to interpret behavioral drivers (e.g., Age & Balance impact).

---

## 💡 Strategic Business Insights
* **Targeted Retention:** Analysis identified **inactive members aged 45-60** (specifically in Germany) as the highest churn risk segment.
* **Voice of Customer:** The SVM model automates the processing of **568,000+ reviews**, reducing manual analysis time by ~90% while maintaining 84% accuracy.
* **Risk Calibration:** The XGBoost model provides a "Churn Probability Score," enabling the marketing team to prioritize retention budgets for high-value customers.

---

## 📂 Repository Structure
* `Code.ipynb` - The complete Jupyter Notebook pipeline.
* `member1_results.csv` - NLP model benchmarking (SVM vs. Naive Bayes).
* `member2_results.csv` - Churn model benchmarking (XGBoost vs. Random Forest).
* `E-Commerce_Dashboard.pbix` - Interactive Power BI Executive Dashboard.

---

## 👥 Authors
* **Saatvik Reddy Gutha** (x24257460) - *Feature Engineering & Model Optimization*
* **Dattathreya Chintalapudi** (x24212881) - *Data Pipeline & Visualization Strategy*

---

## ⚙️ How to Run
1.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
2.  **Launch the Analysis:**
    ```bash
    jupyter notebook Code.ipynb
    ```
