#Amazon Review Star Rating Prediction

This project aims to predict star ratings (1-5) for Amazon movie reviews based on review text and metadata, using various machine learning techniques. The dataset consists of over 1.6 million reviews with metadata like helpfulness scores, review summary, and full text. The final model achieved an accuracy of approximately 63%.

##Project Structure
Data: The dataset contains train.csv (with star ratings) and test.csv (without star ratings).
Feature Engineering: Key features include TF-IDF vectors from the review text, helpfulness ratios, and text length metrics.
Models Tried: Initial experiments with KNN, Random Forest, and Logistic Regression resulted in 53-55% accuracy.
Final Model: A tuned Logistic Regression model with TF-IDF features and hyperparameter optimization using GridSearchCV achieved the best accuracy.
Evaluation: Performance was evaluated using accuracy, confusion matrix, and other classification metrics.
