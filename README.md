## PySpark Classification Project Using Iris Dataset
### Objective:
The goal of this project was to apply machine learning classification models (Decision Tree and Random Forest) using the Iris dataset, which contains features of Iris flowers and aims to predict their species.
### 1. Data Preprocessing:
a. StringIndexer: Converted the categorical target variable Species (Setosa, Versicolor, Virginica) into numerical labels (0, 1, 2).
b. VectorAssembler: Combined individual feature columns (sepal length, sepal width, petal length, petal width) into a single Features vector for model input.
### 2. Dimensionality Reduction (PCA):
Applied PCA to reduce the feature space from four dimensions to two principal components, helping to retain the most significant variance in the data.
### 3. Data Splitting:
Split the data into 80% training and 20% testing to evaluate model performance.
### 4. Model Training and Classification:
Decision Tree Classifier: Trained on the training data and evaluated for accuracy on the test data.
Random Forest Classifier: Also trained on the training data and tested similarly.
### 5. Results:
Both models (Decision Tree and Random Forest) achieved an accuracy of 0.97297 on the test data, indicating strong performance in predicting the Iris species.

