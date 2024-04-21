Assignment 5- Parameter Optimization in SVM

UCS654: Predictive Analytics using Statistics

Submitted By: Akshit SIngh,102103767, 3CO27

Support Vector Machine

In machine learning, support vector machines or SVMs are supervised learning models with associated learning algorithms that analyze data for classification and regression analysis. It is used to find a hyperplane that best separates the two classes, or the plane that has the maximum distance from both the classes. SVM works best with smaller datasets.

Parameter Optimization

Optimization of parameter values means finding the best combination of the parameters that governs the model, to enable it to perform the given task with relative accuracy. The hyperparameters tuned in the SVM model were:-

Parameters	Description

kernel	the type of kernel used for the SVM
c (epsilon)	penalty parameter of the error term
degree (nu)	the degree of the polynomial kernel

About Dataset used

The dataset used for the project is Room Occupancy Estimation that has been downloaded from the UCI Machine Learning Repository.

Number of Instances: 10129

Number of Attributes: 16

Data Analytics and Parameter Optimization steps

1. Data Cleaning
2. Data Preprocessing
3. Normalization
4. Creating 10 samples with 70-30 ratio of Training and Testing Set
5. Optimizing the SVM model for each sample, by using grid search and cross-validation with 1000 iterations.

Final Result Table

![image](https://github.com/akshit2605/Parameter-Optimization-of-SVM/assets/100219639/7b9152e7-9f58-4686-a810-adb5518de882)
