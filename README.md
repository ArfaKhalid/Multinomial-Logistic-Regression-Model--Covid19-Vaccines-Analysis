# Project: Analyzing the Effectiveness of Covid-19 Vaccines - Prediction Model

## Overview
This project involves the development of a multinomial logistic regression model to analyze the effectiveness of Covid-19 vaccines across different age groups. The model aims to predict the vaccination status (Fully Vaccinated, Partially Vaccinated, Unvaccinated) based on features such as age groups and the number of Covid-19 cases.

## Background
Multinomial Logistic Regression is utilized as a classification algorithm for scenarios with more than two possible discrete outcomes. It extends binary logistic regression to handle multiple classes, predicting the probability of an instance belonging to each class. The model output is transformed using the softmax function, ensuring that probabilities sum to 1 across all classes.

## Target
The primary goal is to analyze Covid-19 cases for vaccine effectiveness among different age groups.

## Libraries Used
- Pandas and NumPy for data handling and numerical operations.
- Scikit-learn for building and evaluating machine learning models.
- Seaborn and Matplotlib for creating visually appealing plots to communicate insights.

## Dataset
The dataset captures information about Covid-19 cases based on age groups and vaccination status on specific dates. Key variables include the date of observation, age group categorization, and the number of cases for unvaccinated, partially vaccinated, and fully vaccinated individuals within each age group.

## Analysis Steps
1. **Data Review:** Load and review the dataset, including variables such as date, age groups, and vaccination status cases.
2. **Data Visualization:** Visualize Covid-19 cases by age group and vaccination status using bar plots and time series plots.
3. **Data Reshaping:** Transform the data into long format using the melt function for better analysis and visualization.
4. **Exploratory Data Analysis:** Utilize violin plots, line plots, and scatter plots to explore relationships between age groups, vaccination status, and cases.
5. **Reference Category:** Designate a reference category in multinomial logistic regression and discuss its impact on coefficient interpretation.
6. **Data Preparation:** Convert categorical variables, set reference category, and split data into training and testing sets.
7. **Model Development:** Create a machine learning pipeline with imputation and logistic regression. Optimize the model using a grid search with cross-validation.
8. **Model Evaluation:** Evaluate the model's performance on the test set using classification reports and confusion matrices.
9. **Visualization of Results:** Create visualizations, including confusion matrix heatmap and model prediction plots.
10. **ROC and AUC Curve:** Explore the Receiver Operating Characteristic (ROC) curve and Area Under the Curve (AUC) to assess model performance.
11. **Monte Carlo Simulation:** Conduct a simulation to generate random samples and predict vaccination status, visualizing the results.

## Conclusion
The project provides a comprehensive analysis of Covid-19 vaccine effectiveness across age groups, leveraging a multinomial logistic regression model. It includes data exploration, model development, evaluation, and visualizations to communicate insights effectively. The use of machine learning techniques contributes to understanding the complex relationships between age, vaccination status, and Covid-19 cases.
