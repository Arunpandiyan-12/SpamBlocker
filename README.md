# SpamBlocker

This project implements an email spam detection model using Python. The model combines multiple classification algorithms, including Support Vector Machine (SVM), Random Forest, K-Nearest Neighbors (KNN), Naive Bayes, and Logistic Regression, to provide accurate predictions for email spam detection.

## Dataset

The model is trained on the "email.csv" dataset. The dataset contains labeled email data, where each email is classified as either spam or not spam.

## Algorithms

The following classification algorithms are used in the model:

1. Support Vector Machine (SVM)

   - SVM is a powerful algorithm that separates data points into different classes using a hyperplane. It works well for both linearly separable and non-linearly separable data.

2. Random Forest

   - Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions. It is known for its high accuracy and ability to handle large datasets.

3. K-Nearest Neighbors (KNN)

   - KNN is a non-parametric algorithm that classifies new data points based on the majority class of its neighboring points. It is simple yet effective for classification tasks.

4. Naive Bayes

   - Naive Bayes is a probabilistic algorithm that calculates the probability of a data point belonging to a certain class based on the Bayes' theorem. It assumes independence between features.

5. Logistic Regression

   - Logistic Regression is a linear classifier that models the probability of a data point belonging to a certain class using a logistic function. It is widely used for binary classification tasks.


# Steps
To use the email spam detection model, follow these steps:

1. Install the required dependencies by running the following command:
     pip install -r requirements.txt

2. Open the "spam_detection.ipynb" Jupyter Notebook in your preferred environment.

3. Run the notebook cells to execute the code and train the model on the "email.csv" dataset.

[Provide any additional instructions or information required to run the notebook, such as data preprocessing steps or parameter tuning.]

4. Once the model is trained, you can use it to make predictions on new email data or evaluate its performance using evaluation metrics such as accuracy, precision, recall, or F1-score.

