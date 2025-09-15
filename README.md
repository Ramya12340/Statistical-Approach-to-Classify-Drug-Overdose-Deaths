# Statistical-Approach-to-Classify-Drug-Overdose-Deaths
Drug overdose deaths are a major public health crisis, causing high mortality and economic burden. Accurate data analysis is essential for effective policies, prevention strategies, and targeted interventions.


### Abstract
This project addresses the escalating crisis of drug overdose deaths by developing a classification model to predict the type of drug most likely responsible for overdose deaths in various demographic groups in the U.S. Using a comprehensive dataset from Data.gov, the model aims to identify high-risk demographics for targeted prevention and intervention efforts. Several machine learning algorithms, including Logistic Regression, Naive Bayes, Random Forest, SVM, and GBM, are compared to select the most effective model.


### Methodology

![image](https://github.com/user-attachments/assets/005bfd87-c949-4729-8e1a-23f477392e9a)

#### Data Collection
- Data sourced from national public health databases on Data.gov.

![image](https://github.com/user-attachments/assets/29a11b73-ed51-4bc2-9a62-c8a7d20aafa2)


- Key attributes include drug type, demographic information (age, sex, race), year of the incident, and estimated number of deaths per 100,000 residents.

![image](https://github.com/user-attachments/assets/e6364920-bcc3-4fd8-917a-dda2c1fefe18)


#### Data Processing
- Imputation of missing values with the mean.
- Standardization of data.
- Factorization of categorical variables for machine learning algorithms.

#### Feature Selection
- Selection of numerically encoded variables for analysis.

#### Data Splitting
- Dataset split into 80% training and 20% testing subsets.

#### Models
- **Logistic Regression:** Effective for handling multiple class problems.
- **Naive Bayes:** Proficient in probability-based classification.
- **SVM:** Finds optimal hyperplane for class separation.
- **Random Forest:** Ensemble of decision trees for improved accuracy.
- **GBM:** Sequentially builds an ensemble of weak models for high accuracy.

### Results and Discussions
- Evaluation metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC.

![image](https://github.com/user-attachments/assets/f1e9465c-adc4-49e4-b97b-64b6c482766f)


- **Random Forest** emerged as the best model due to its high performance across precision, recall, and F1-scores.
- Variable importance was analyzed using Random Forest.

![image](https://github.com/user-attachments/assets/73698e0e-64ed-4b4e-bd21-579f30168e48)
![image](https://github.com/user-attachments/assets/dddc0ade-112d-4802-85c1-65d5e10fb68a)


### Conclusions
- **Random Forest** demonstrated the best performance for this classification task, making it the most reliable model for predicting drug overdose deaths based on the dataset.
![image](https://github.com/user-attachments/assets/93525b00-b4c5-4f7b-9ead-72d80ac9b97f)
![image](https://github.com/user-attachments/assets/0d313195-22f7-4c4e-a439-0aa26335e554)
![image](https://github.com/user-attachments/assets/dab02d8d-b8c6-44e3-a5fe-85b06b316418)

### R Code
- The project includes detailed R code for data processing, model training, and evaluation.
