 **Loan Approval Prediction & Maximum Loan Amount Estimation using Machine Learning**

---

##  Project Description

This project is implemented using **Python in Jupyter Notebooks** and standard machine learning libraries. It applies supervised learning techniques to analyze client financial data and address two critical problems in **banking risk analysis**:

### Loan Approval Prediction (Classification)

* Predicts whether a client’s loan application should be **Approved** or **Rejected**
* Helps financial institutions reduce lending risk by identifying high-risk applicants

### Maximum Loan Amount Prediction (Regression)

* Estimates the **maximum loan amount** that can be safely offered to approved clients
* Supports optimized lending decisions and effective risk control

The project integrates **data preprocessing**, multiple **classification and regression models**, and **ensemble learning** techniques to improve prediction accuracy and reliability.

---

##  Machine Learning Models Used

### Classification Models

* Logistic Regression (LR)
* K-Nearest Neighbors (KNN)
* Naïve Bayes (NB)
* Voting Ensemble (LR + KNN)

### Regression Models

* Decision Tree Regressor (Fully Grown)
* Decision Tree Regressor (Pruned)

---

##  Key Features

* Data cleaning and preprocessing (handling missing values, encoding, and outliers)
* Feature selection based on financial relevance
* Train-test split with stratification
* Model evaluation using:

  * Accuracy
  * Recall
  * F1-score
  * AUC-ROC
  * Mean Squared Error (MSE)
  * Mean Absolute Error (MAE)
  * R² Score
* Hyperparameter tuning using **GridSearchCV**
* Ensemble learning using probability-based voting

---

##  How to Run the Project

### Option 1: Run in Google Colab (Recommended)

1. Open Google Colab: [https://colab.research.google.com/](https://colab.research.google.com/)
2. Upload the following notebooks:

   * Notebook 1: Data Preprocessing
   * Notebook 2: Classification Models
   * Notebook 3: Regression Models
3. Upload the dataset file: `loan_approval_data.csv`
4. Run the notebooks step-by-step in order

### Option 2: Run Locally

1. Install Python (version 3.8 or higher recommended)
2. Install required all libraries include:

   ```
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open Jupyter Notebook:

   ```
   jupyter notebook
   ```
4. Run the notebooks sequentially

---

##  Important Notes

* Always run **Notebook 1** first for data cleaning and preprocessing
* Ensure the dataset is uploaded before running any models
* Use the same train-test split across models for fair comparison
* GridSearchCV is used to improve and optimize model performance

---

##  Key Results Summary

### Best Classification Model

* **KNN (k = 5)**
* Achieved high recall for rejected loans
* Provided a strong balance between precision and risk reduction

### Best Regression Model

* **Pruned Decision Tree (max depth ≈ 4–5)**
* Lower MSE compared to the fully grown tree
* Better generalization for loan amount prediction

---

##  Limitations

* KNN is computationally expensive for large datasets
* Decision Trees may still overfit without careful pruning
* Some financial features may introduce bias if not critically evaluated

---

##  Ethical Considerations

* Potential bias arising from sensitive financial attributes
* Limited explainability in certain models (especially KNN)
* Automated decisions should always be complemented by human review

---

## 👤 Author Contribution

* End-to-end machine learning pipeline development
* Data preprocessing and feature engineering
* Model training, evaluation, and optimization
* Hyperparameter tuning and ensemble modeling
* Documentation, analysis, and reporting

---

