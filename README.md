# Machine-Learning-Hyper-parameter-Tuning-GridSearchCV

This repository contains a practice exercise on Machine Learning Hyperparameter Tuning using GridSearchCV. The exercise utilizes the digit dataset from the sklearn library to train various models. The models used for training include SVM, Linear Regression, Random Forest, Decision Tree, Logistic Regression, GaussianNB, and MultinomialNB from Naive Bayes. The goal is to determine which algorithm yields the highest accuracy and identify the best hyperparameters.

## Hyper-parameter-Tuning-GridSearchCV

Hyperparameter tuning is an essential step in machine learning model development. It involves selecting the optimal values for the hyperparameters of a machine learning algorithm. GridSearchCV is a method used to systematically search through a specified parameter grid and find the best combination of hyperparameters for a given model. By exhaustively evaluating each combination, GridSearchCV helps to identify the hyperparameters that yield the highest performance metrics, such as accuracy, precision, or recall.

## Dataset

The digit dataset from the sklearn library is used for this exercise. It is a commonly used dataset in the field of machine learning and consists of 8x8 images of handwritten digits from 0 to 9. Each image is represented as an array of pixel values, and the corresponding target variable is the digit represented in the image.

## Models and Algorithms

The following models and algorithms are implemented in this practice exercise:

- Support Vector Machine (SVM)
- Linear Regression
- Random Forest
- Decision Tree
- Logistic Regression
- Gaussian Naive Bayes (GaussianNB)
- Multinomial Naive Bayes (MultinomialNB)

The goal is to compare the performance of these algorithms on the digit dataset and identify the algorithm that achieves the highest accuracy. Hyperparameter tuning using GridSearchCV is employed to find the best combination of hyperparameters for each model.

## Results

After evaluating the models using hyperparameter tuning and GridSearchCV, the algorithm that achieves the highest accuracy on the digit dataset will be identified. Additionally, the best hyperparameter values for each model will be determined and reported.

Feel free to explore the code and experiment with different hyperparameter settings to gain a better understanding of the impact of hyperparameter tuning on model performance.



