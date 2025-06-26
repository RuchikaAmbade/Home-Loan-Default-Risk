# Home Loan Default Risk Prediction
This project focuses on building a predictive machine learning model to identify individuals at high risk of defaulting on home loans, using demographic, financial, and previous loan data. Accurate early detection enables financial institutions to manage lending risks, minimize financial loss, and comply with regulatory standards.

# Project Objectives
Develop a robust ML model for predicting home loan default risk.

Analyze and preprocess data from multiple sources including previous applications and credit history.

Handle data imbalance and missing values effectively.

Evaluate a range of classification models for optimal performance.

Communicate actionable insights for risk mitigation strategies.

# Dataset Summary
This project utilizes data from three primary sources:

Application Data: Personal, demographic, and financial information about loan applicants.

Bureau Data: External credit history from other financial institutions.

Previous Applications: Applicant’s past loan applications and outcomes.

Records analyzed: 307,511+  Final merged dataset: 35 features

# Exploratory Data Analysis (EDA)
Univariate, bivariate, and multivariate analysis

Visualization of continuous, categorical, and discrete variables

Identification of skewed distributions and outliers

Correlation heatmaps for feature insights

# Data Preprocessing Techniques
Missing Value Imputation: Median (numerical), Mode (categorical)

Outlier Treatment: IQR-based clipping

Encoding: Label encoding and frequency encoding

Scaling: StandardScaler

Dimensionality Reduction: PCA (95% variance retained with 24 components)

Balancing Classes: SMOTE oversampling

# Models Trained & Evaluated
Model	F1 Score	CV Score	ROC AUC
Logistic Regression	0.64	0.64	0.68
Decision Tree	0.90	0.89	0.89
Random Forest	0.96	0.95	0.99
Bagging Classifier	0.94	0.93	0.97
Gradient Boosting	0.91	0.91	0.96
XGBoost	0.95	0.95	0.97
Neural Network (MLP)	0.82	0.81	0.90
Naive Bayes	0.62	0.63	0.67
K-Nearest Neighbors	0.86	0.84	0.96
 Random Forest and XGBoost demonstrated superior performance across all metrics.

# Key Challenges Addressed
Handling complex, non-linear relationships in high-dimensional data.

Resolving feature redundancy and multicollinearity.

Ensuring model generalizability with cross-validation and ROC analysis.

Building an interpretable pipeline that balances performance and explainability.

# Conclusion
This project demonstrates the effectiveness of ensemble models, especially Random Forest and XGBoost, in detecting high-risk home loan applicants. Through meticulous feature engineering, balancing, and dimensionality reduction, the pipeline delivers strong classification performance with business-ready insights.
