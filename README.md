## Insurance-Cost-Prediction
Health Insurance Cost Prediction and Regression

# Healthcare Insurance Personal Prediction
This is a machine learning project to predict healthcare insurance charges for individuals based on various features such as age, gender, BMI, smoking habit, and region. The goal is to build a regression model that can accurately predict the insurance charges for new individuals based on their features.

# Preparation
Import Libraries
We start by importing the necessary libraries for data manipulation, visualization, and machine learning.

# Data Loading
We load the insurance dataset and explore its features and target variable. We also check for missing values and outliers.

# Feature Engineering
We transform the categorical features into numerical ones using one-hot encoding. We also normalize the numerical features to have zero mean and unit variance.

# Prediction
Model Training and Inference
We train and evaluate several regression models such as Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regression, Random Forest Regression, Gradient Boosting Regression, and Support Vector Regression. We use k-fold cross-validation to select the best model based on its R2 score.

# Hyperparameter Tuning
We perform hyperparameter tuning for the best models to further improve their performance.

![image](https://user-images.githubusercontent.com/88907921/220463997-e4598df9-c35d-489d-ba3a-99e805666303.png)

# Best Models
We select the best models based on their R2 score and evaluate their performance on the test set.

# Visualizations
We create several visualizations to better understand the models and their predictions.

# Comparison Models with R2 Score
We compare the R2 score of the best models and visualize their performance using a bar chart.
![image](https://user-images.githubusercontent.com/88907921/220679744-29484891-5885-457b-b88c-b57b4ae9a00a.png)

# Feature Importance
We visualize the feature importance of the best models to understand which features are most important in predicting the insurance charges.

# Linearity (Actual vs Predicted Values)
We create scatter plots to compare the actual and predicted insurance charges for the best models and check for linearity.
![image](https://user-images.githubusercontent.com/88907921/220680254-db1407ef-7f9a-40f2-9265-d1fe246dc3a1.png)

# Residual Plot
We create residual plots to check for homoscedasticity and normality of the errors.
![image](https://user-images.githubusercontent.com/88907921/220680559-9a9d764a-b74f-439b-b004-889f7c9eb79a.png)

Instructions:
to run the model you need to download the data and the ipynb
you need to install-
-plotly
-Numpy
-pandas
-matplotlib
-scikit-learn

# Conclusion
We conclude the project by summarizing the results and discussing the limitations of the models. We also suggest possible future work to improve the models.
