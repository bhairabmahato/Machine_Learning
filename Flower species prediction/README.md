# Machine Learning Project: Iris Flower Classification

This repository contains a machine learning project for classifying Iris flowers using the RandomForestClassifier algorithm.

## Overview

The project utilizes the Iris dataset from scikit-learn, which includes features like sepal length, sepal width, petal length, and petal width. These features are used to predict the species of Iris flowers, which are categorized into three classes: Setosa, Versicolor, and Virginica.

## Data Preprocessing

- The dataset is loaded using scikit-learn's `load_iris()` function.
- Features and target names are extracted from the dataset.
- The data is structured into a pandas DataFrame for analysis.

## Model Training

- The dataset is split into training and testing sets using `train_test_split()` from scikit-learn.
- A RandomForestClassifier model is trained with 10 estimators initially and then with 50 estimators for improved accuracy.
- The model's performance is evaluated using the accuracy score.

## Technologies Used

- Python
- Pandas
- Scikit-learn

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to train and test the model.

## Results

The RandomForestClassifier model achieved an accuracy score of X% on the test set, demonstrating its effectiveness in classifying Iris flowers.

## Contributions

Contributions are welcome! Fork this repository, make your enhancements, and submit a pull request.

Happy coding!
