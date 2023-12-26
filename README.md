Heart Disease Prediction Project


Overview: 

This repository contains the code and analysis for a machine learning project focused on predicting heart disease. The project explores various classification algorithms, including Linear SVM, SVM with RBF kernel, Naive Bayes, Decision Tree, Random Forest, AdaBoost, and XGBoost. The primary goal is to assess the effectiveness of these models in predicting heart disease based on a comprehensive dataset.


Dataset: 

The dataset used in this project is a combination of five heart-related datasets, resulting in a comprehensive collection of features for heart disease prediction. The attributes include age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, electrocardiogram results, maximum heart rate achieved, exercise-induced angina, oldpeak (ST depression), slope of the peak exercise ST segment, and the output class indicating the presence or absence of heart disease.


Data Preparation: 

The dataset undergoes extensive data preparation, including handling missing values, data encoding, visualization, and handling outliers. These steps ensure a clean and standardized dataset for training and evaluating machine learning models.


Classification Models: 

The project evaluates the performance of various classification models on different sizes of training data (20%, 30%, and 50%). Notably, Random Forest consistently emerges as the top-performing model in terms of accuracy.


Ensemble Learning: 

To enhance predictive performance, ensemble learning is implemented. The ensemble approach combines multiple classifiers to achieve improved accuracy, precision, recall, and F1 score. The results showcase the effectiveness of ensemble learning in enhancing the robustness of predictive models.


Results: 

The project results indicate that Random Forest, both as an individual model and within an ensemble, offers superior predictive accuracy for heart disease. The ensemble approach further demonstrates consistent improvement across different training data sizes.
