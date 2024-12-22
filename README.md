**Rock vs Mine Prediction**  
This repository contains a project that uses supervised machine learning to predict whether sonar signals reflect off rocks or mines. The project is implemented in Python and employs a Logistic Regression, Random Forest and SVM models for comparison.

**Overview**  
The Rock vs Mine Prediction project is a binary classification problem. Using the sonar dataset, this project identifies whether the given sonar readings correspond to rocks (R) or mines (M).

**Dataset**  
The dataset used in this project is the Sonar Dataset, which contains:  
208 samples of sonar data  
60 numerical features representing sonar frequencies  
1 label column: "R" for Rock and "M" for Mine  

**Technologies Used**  
Python: Programming language  
Pandas: Data manipulation  
NumPy: Numerical computations  
scikit-learn: Machine learning library  

**Project Workflow**  
Load the dataset  
Explore data distribution and statistics  
Split data into features (X) and labels (y)  
Data Splitting  
Train-test split (90% training, 10% testing)  
Stratified sampling ensures class balance  
Model Training  
Model Evaluation  


**Results**  

Logistic Regression:  
Training Accuracy: 83%  
Test Accuracy: 76%  

Random Forest:  
Training Accuracy: 100%  
Test Accuracy: 76%  

Support Vector Machine:    
Training Accuracy: 99%  
Test Accuracy: 95%  

