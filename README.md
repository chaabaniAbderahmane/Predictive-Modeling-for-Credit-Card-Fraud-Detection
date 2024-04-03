
# Predictive Modeling for Credit Card Fraud Detection

This project focuses on building a machine learning model to detect fraudulent credit card transactions. The dataset used is highly imbalanced, with a significantly higher number of legitimate transactions compared to fraudulent ones.

## Data Preprocessing

The code starts by loading the dataset and performing exploratory data analysis (EDA) to understand the data distribution, missing values, and class imbalance. To address the imbalance, the legitimate transactions are undersampled to match the number of fraudulent transactions, creating a balanced dataset.

## Feature Engineering

The code then applies feature scaling using <code class="highlighted">StandardScaler</code> to ensure that all features are on a similar scale. Additionally, feature selection is performed using <code class="highlighted">SelectKBest</code> and <code class="highlighted">f_classif</code> to identify the top 10 most relevant features for the classification task.

## Model Training and Evaluation

The data is split into training and testing sets, and a Logistic Regression model is trained. To find the optimal hyperparameters, a <code class="highlighted">GridSearchCV</code> is employed with a range of regularization strengths (<code class="highlighted">C</code> values) for the Logistic Regression model.

The trained model is then evaluated on both the training and testing sets using various metrics, including accuracy, classification report, and confusion matrix. The classification report provides valuable insights into the model's performance for each class, including precision, recall, and F1-score. The confusion matrix helps identify the number of true positives, true negatives, false positives, and false negatives.

## Conclusion

The provided code demonstrates a complete pipeline for credit card fraud detection, from data exploration and preprocessing to model training, hyperparameter tuning, and evaluation. By addressing the class imbalance, performing feature engineering, and leveraging appropriate evaluation metrics, this approach aims to build a robust and reliable model for identifying fraudulent transactions.



<div style="background-color: #f0f0f0; padding: 20px; border-radius: 5px; box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1); text-align: center; margin: auto;">
  <h2 style="color: #333;">Thank you for visiting!</h2>
  <p style="color: #666;">Your feedback and contributions are highly appreciated.</p>
</div>
