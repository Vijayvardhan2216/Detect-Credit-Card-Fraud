# Detect-Credit-Card-Fraud
**Credit Card Fraud Detection using Machine Learning :-**
<<<<<<< HEAD
    This project implements and compares various machine learning algorithms to detect fraudulent credit card transactions. Using a dataset of customer transactions, the project explores data preprocessing, exploratory data analysis (EDA) and the implementation of classification models including Logistic Regression, Decision Trees and Gradient Boosting Machines (GBM).


**Project Overview :-**
    Credit card fraud is a significant issue for financial institutions. This project aims to build a robust classification system that can distinguish between legitimate and fraudulent transactions based on features such as customer age, gender, annual income and spending score.
=======
This project implements and compares various machine learning algorithms to detect fraudulent credit card transactions. Using a dataset of customer transactions, the project explores data preprocessing, exploratory data analysis (EDA) and the implementation of classification models including Logistic Regression, Decision Trees and Gradient Boosting Machines (GBM).


**Project Overview :-**
Credit card fraud is a significant issue for financial institutions. This project aims to build a robust classification system that can distinguish between legitimate and fraudulent transactions based on features such as customer age, gender, annual income and spending score.
>>>>>>> fc0cc5e911a52d09036a2bb9c47dd62b57a78cc1


**Dataset:**
    The project utilizes a dataset (referenced as Mall_Customers.csv in the notebook, though treated as transaction data for fraud detection) containing the following features:

- **CustomerID:** Unique identifier for each customer.
- **Gender:** Customer gender (Male/Female).
- **Age:** Customer age.
- **Annual Income (k$):** Annual income of the customer.
- **Spending Score (1-100):** A score assigned based on customer behavior and spending nature.


**Key Features:**

- **Data Preprocessing:** Handling categorical variables (Gender) and stratified splitting of data.
- **Exploratory Data Analysis:** Statistical summaries and variance analysis of features.

- **Model Implementation:**
- **Logistic Regression:** A baseline probabilistic classifier.
- **Decision Trees:** A non-linear model for capturing complex decision boundaries.
- **Gradient Boosting Machine (GBM):** An ensemble technique to improve prediction accuracy.

- **Performance Evaluation:**
- Confusion Matrices
- ROC Curves and AUC (Area Under the Curve) calculation.
- Relative Influence analysis for feature importance.


**Technologies Used:**

- **Language:** R

- **Libraries:**
- **ranger:** For fast random forest implementation.
- **caret:** For data splitting and model training.
- **data.table:** For efficient data manipulation.
- **caTools:** For moving window statistics and data splitting.
- **gbm:** For Gradient Boosting Machines.
- **pROC:** For analyzing and visualizing ROC curves.


**Results:**
    The models were evaluated based on their ability to correctly classify transactions. The GBM model showed significant performance, with the relative influence of features being analyzed to understand the drivers of fraud detection. ROC curves were plotted to visualize the trade-off between sensitivity and specificity.

**Conclusion :-**
    This project demonstrates the effectiveness of ensemble methods like GBM in detecting patterns within transaction data. Future improvements could include handling class imbalance more aggressively and exploring deep learning architectures.
