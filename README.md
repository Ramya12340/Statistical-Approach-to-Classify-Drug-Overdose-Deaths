Drug overdose deaths are a major public health crisis, causing high mortality and economic burden. Accurate data analysis is essential for effective policies, prevention strategies, and targeted interventions.

# Abstract
This project addresses the escalating crisis of drug overdose deaths by developing a classification model to predict the type of drug most likely responsible for overdose deaths in various demographic groups in the U.S. Using a comprehensive dataset from Data.gov, the model aims to identify high-risk demographics for targeted prevention and intervention efforts. Several machine learning algorithms, including Logistic Regression, Naive Bayes, Random Forest, SVM, and GBM, are compared to select the most effective model.

# Methodology
# Data Collection
Data sourced from national public health databases on Data.gov.

Key attributes include drug type, demographic information (age, sex, race), year of the incident, and estimated number of deaths per 100,000 residents.

# Data Processing
Imputation of missing values with the mean.
Standardization of data.
Factorization of categorical variables for machine learning algorithms.
Feature Selection
Selection of numerically encoded variables for analysis.
# Data Splitting
Dataset split into 80% training and 20% testing subsets.
Models
Logistic Regression: Effective for handling multiple class problems.
Naive Bayes: Proficient in probability-based classification.
SVM: Finds optimal hyperplane for class separation.
Random Forest: Ensemble of decision trees for improved accuracy.
GBM: Sequentially builds an ensemble of weak models for high accuracy.
# Results and Discussions
Evaluation metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC.

# R Code
The project includes detailed R code for data processing, model training, and evaluation.

Conclusions
Random Forest demonstrated the best performance for this classification task, making it the most reliable model for predicting drug overdose deaths based on the dataset.

R Code
The project includes detailed R code for data processing, model training, and evaluation.
