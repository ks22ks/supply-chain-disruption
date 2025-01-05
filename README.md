# Supplier Risk Prediction Using Classification Models
## Description
This project leverages machine learning and statistical techniques to predict supply chain disruptions based on supplier risk data. By evaluating multiple classification models, the analysis identifies the most effective methods for predicting disruptions and determining optimal decision thresholds.
## Key Features
1. Exploratory Data Analysis
Created side-by-side box plots for continuous variables against supply chain disruption classes (0 and 1).
Evaluated the discriminative ability of continuous variables and selected the top eight for further analysis.
2. Data Preparation
Split the dataset into training (80%) and testing (20%) sets using a random seed for reproducibility.
Retained only the most discriminative variables for modeling.
3. Model Training and Prediction
#### Classification Models:
##### Logistic Regression
##### Random Forest (500 trees)
##### Support Vector Machine (RBF kernel)
##### Neural Network (2 hidden layers, matching input size)
Trained all models on the training data and predicted probabilities of supply chain disruption for the test data.
4. Model Evaluation
#### Discriminative Analysis:
Compared predicted probabilities for each model using box plots against test classes.
#### Performance Metrics:
##### Calculated sensitivity, specificity, and accuracy for each model using a median decision threshold.
##### Plotted ROC curves and compared AUC-ROC values to assess model performance.
5. Optimal Decision Threshold
##### Determined optimal decision thresholds for logistic regression and random forest models using cost-based optimization for false positives and false negatives.
##### Analyzed the trade-offs and insights from this optimization exercise.
## Results and Insights
1. Explored the ability of different models to discriminate between supply chain disruption classes.
2. Evaluated and compared model performance using key metrics and ROC-AUC curves.
3. Highlighted the trade-offs between model complexity and prediction accuracy, and identified optimal decision thresholds for risk mitigation.
##### This project demonstrates a structured approach to predictive modeling in the context of supply chain risk management, providing actionable insights for businesses to minimize disruptions.
