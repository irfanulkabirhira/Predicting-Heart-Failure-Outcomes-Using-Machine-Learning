# Predicting-Heart-Failure-Outcomes-Using-Machine-Learning
This project analyzes heart failure clinical data and builds ML models to predict death events. Tasks include EDA, visualizations, preprocessing, and applying models like Logistic Regression, KNN, and Decision Tree. Models are evaluated using metrics and tuned for performance, offering insights for healthcare decision-making.
## Objective
The goal of this assignment is to analyze the **heart failure clinical records** dataset and build a machine learning model to predict the occurrence of a **death event** in patients with heart failure. You will perform exploratory data analysis (EDA), visualize trends, and apply classification models to predict the target variable.

## Dataset Overview

The dataset consists of 13 variables, each representing clinical features and demographic information of heart failure patients:

1. **age**: Age of the patient (years)
2. **anaemia**: Whether the patient has anaemia (0: no, 1: yes)
3. **creatinine_phosphokinase**: Level of the CPK enzyme in the blood (mcg/L)
4. **diabetes**: Whether the patient has diabetes (0: no, 1: yes)
5. **ejection_fraction**: Percentage of blood leaving the heart with each contraction (%)
6. **high_blood_pressure**: Whether the patient has high blood pressure (0: no, 1: yes)
7. **platelets**: Platelets in the blood (kiloplatelets/mL)
8. **serum_creatinine**: Level of serum creatinine in the blood (mg/dL)
9. **serum_sodium**: Level of serum sodium in the blood (mEq/L)
10. **sex**: Gender of the patient (1: male, 0: female)
11. **smoking**: Whether the patient smokes (0: no, 1: yes)
12. **time**: Follow-up period (days)
13. **DEATH_EVENT**: Whether the patient died during the follow-up period (0: no, 1: yes) [Target Variable]

## Instructions

### 1. Data Exploration (EDA)
- **Task 1**: Load the dataset using pandas and display the first few rows.
- **Task 2**: Check for missing values and clean the data if necessary.
- **Task 3**: Generate summary statistics for the numerical columns.
- **Task 4**: Visualize the distribution of the target variable (`DEATH_EVENT`).
- **Task 5**: Plot histograms or box plots for continuous variables like `age`, `creatinine_phosphokinase`, `ejection_fraction`, `serum_creatinine`, etc.

![image alt]( )

### 2. Data Visualization
- **Task 6**: Create a correlation matrix heatmap to understand the relationships between the features.
- **Task 7**: Create count plots or bar charts for categorical variables like `anaemia`, `diabetes`, `high_blood_pressure`, `sex`, and `smoking`.
- **Task 8**: Create scatter plots or pair plots for continuous variables like `age` vs `ejection_fraction`, `serum_creatinine`, etc., colored by `DEATH_EVENT`.

![image alt]( )

### 3. Model Building
- **Task 9**: Split the dataset into features (`X`) and the target variable (`y = DEATH_EVENT`).
- **Task 10**: Perform train-test splitting (70% training, 30% testing) using `train_test_split` from sklearn.
- **Task 11**: Standardize the continuous features using `StandardScaler`.

![image alt]( )

### 4. Model Training and Evaluation
- **Task 12**: Train a Logistic Regression model and evaluate it using accuracy, precision, recall, and F1-score.
- **Task 13**: Train a K-Nearest Neighbors (KNN) model and evaluate its performance.
- **Task 14**: Train a Decision Tree Classifier and compare its performance with other models.

 ![image alt]( https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/a35a3cb8779056deefd2b5b71e2286cec7d0151a/Task%204.png)


### 5. Cross Validation
- **Task 15**: Perform K-Fold Cross-Validation (with 5 folds) on the Logistic Regression model to evaluate its performance.
- **Task 16**: Perform Stratified K-Fold Cross-Validation to ensure class balance during cross-validation.

![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/17098af86dce43d0d7aa3ab76117070cfdc4bbf3/Task%205%20-1.png)
![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/9e7041623092ac67faf7c8537af4bf642d8d51c9/Task%205-2.png)

### 6. Model Improvement
- **Task 17**: Use Grid Search or Randomized Search to tune the hyperparameters of the KNN and Decision Tree models.
- **Task 18**: Plot the ROC curves and calculate the AUC for all models to compare their performance visually.

![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/bb8067dc46af87e6fa30312ef11843c118e7120a/Task%206.png)

### 7. Conclusion
- **Task 19**: Summarize your findings and explain which model performed best and why. Consider which features were most important for predicting the death event.
- **Task 20**: Suggest potential improvements or next steps for the analysis.

![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/918b0df270045fed17503cb49b70c90fec96db42/Task%207-1.png )
![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/c098c80728c3a03f8970dd8c3c8aafa03002f543/Task%207-2.png)
![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/2470a6403a5b037fd9786539ba9241db3d522d1c/Task%207-3.png)

![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/f1a1a0c16f521374cb51ff439bd2f7bbbeb53c21/Task%208.png)
![image alt](https://github.com/irfanulkabirhira/Predicting-Heart-Failure-Outcomes-Using-Machine-Learning/blob/7000b3101ae479c01ff7074cf7171fc74866bcbf/task%2018.png)
