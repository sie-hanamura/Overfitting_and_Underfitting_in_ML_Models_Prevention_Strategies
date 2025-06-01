# Overfitting and Underfitting in ML Models: Prevention Strategies

**Student Name:** Hallig, Siera Q.

**Section:** BSCS 3B - IS

**Subject Code:** CSST 104 

**Course Title:** Advanced Machine Learning

# Introduction to Overfitting and Underfitting (Overview & Importance)

Overfitting and underfitting are critical challenges in machine learning that directly affect a model’s ability to generalize. Underfitting occurs when a model is too simple to capture the underlying patterns in the data, resulting in poor performance on both training and test sets. Overfitting happens when the model becomes too complex, memorizing the training data instead of learning from it, which leads to high accuracy on the training set but poor results on unseen data. Addressing these issues is essential to developing robust models that perform well in real-world scenarios.

For this practical implementation, I used the California Housing dataset from `sklearn.datasets`. I applied three regression models—Linear Regression (prone to underfitting), Decision Tree (prone to overfitting), and XGBoost (with regularization to balance both). The dataset was preprocessed by scaling features and splitting into training and testing sets. Each model's performance was evaluated using Mean Squared Error (MSE) and R² Score. XGBoost achieved the best results, demonstrating effective bias-variance tradeoff handling. Visualizations and metrics further confirmed each model's strengths and weaknesses regarding generalization.

## Table of Contents
* [Code Implementation](Code_Implementation/Overfitting_and_Underfitting_in_ML_Models.ipynb)
* [Dataset Used](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
* [Presentation Slides](Presentation/Overfitting_and_Underfitting_in_ML_Models.pptx)
* [Video Presentation](Presentation/Overfitting_and_Underfitting_Presentation.mp4)
