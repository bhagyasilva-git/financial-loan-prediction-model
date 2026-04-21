📌 Loan Approval Prediction & Maximum Loan Amount Estimation using Machine Learning


📖 Project Description

Implemented in Jupyter Notebooks, the project is fully built using Python and standard machine learning libraries.This project applies machine learning techniques to analyze client financial data and solve two key problems in banking risk analysis:


Loan Approval Prediction (Classification)

Predict whether a client’s loan application should be Approved or Rejected

Helps reduce financial risk by identifying high-risk applicants

Maximum Loan Amount Prediction (Regression)

Estimate the maximum loan amount a bank can safely offer to approved clients

Supports optimized lending decisions and risk control


The project combines data preprocessing, classification models (LR, KNN, NB), regression models (Decision Trees), and ensemble learning to improve prediction reliability.


🧠 Machine Learning Models Used

Classification Models

Logistic Regression (LR)
K-Nearest Neighbors (KNN)
Naïve Bayes (NB)
Voting Ensemble (LR + KNN)

Regression Models

Decision Tree Regressor (Fully grown)
Decision Tree Regressor (Pruned)

📊 Key Features

Data cleaning and preprocessing (missing values, encoding, outliers)

Feature selection based on financial relevance

Train-test split with stratification

Model evaluation using:

Accuracy
Recall
F1-score
AUC-ROC
MSE, MAE, R²

Hyperparameter tuning using GridSearchCV

Ensemble learning using probability-based voting



🚀 How to Run the Project

Option 1: Run in Google Colab (Recommended)

Open Google Colab: https://colab.research.google.com/

Upload the three notebooks:

Notebook 1 (Data Preprocessing)

Notebook 2 (Classification Models)

Notebook 3 (Regression Models)

Upload the dataset file (loan_approval_data.csv)

Run notebooks step-by-step in order

Option 2: Run Locally

Install Python (3.8+ recommended)

Install required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn
Open Jupyter Notebook:
jupyter notebook
Run notebooks in sequence

📌 Important Notes

Always run Notebook 1 first (data cleaning & preprocessing)

Ensure dataset is uploaded before running models

Use same train-test split for fair model comparison

GridSearchCV is used to improve model performance

🧪 Key Results Summary

Best Classification Model

KNN (k=5)

High recall for rejected loans

Best balance between precision and risk reduction

Best Regression Model

Pruned Decision Tree (max depth = 4–5)

Lower MSE compared to fully grown tree

Better generalization for loan amount prediction

⚠️ Limitations

KNN is computationally expensive for large datasets

Decision Trees may still overfit without careful pruning

Some features may introduce bias if not carefully evaluated

⚖️ Ethical Considerations

Risk of bias from sensitive financial attributes

Lack of explainability in some models (especially KNN)

Automated decisions should always include human review

👤 Author Contribution

Machine learning pipeline development

Data preprocessing & feature engineering

Model training, evaluation, and optimization

Hyperparameter tuning and ensemble modeling

Documentation, reporting, and analysis write-up


📌 License


This project is developed for academic and educational purposes.
