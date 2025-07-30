Machine Learning for Drug Discovery

This project uses a machine learning model to predict the biological activity ('Active' or 'Inactive') of chemical compounds based on their molecular properties. This is a classic binary classification task in the field of virtual screening for drug discovery.

Dataset
The dataset used for this project is the Drug Discovery - Virtual Screening Dataset from Kaggle. It contains 11 molecular descriptor columns and one 'Activity' column, which is the target variable.

Project Overview
The project follows these key steps:

1.Data Loading: The dataset is loaded from the provided CSV file.

2.Data Preprocessing: The categorical target variable ('Activity') is encoded into numerical format (0 and 1).

3.Train-Test Split: The data is split into a training set (75%) and a testing set (25%).

4.Model Training: A Decision Tree Classifier is trained on the training data.

5.Prediction & Evaluation: The trained model makes predictions on the unseen test data. The model's performance is evaluated using accuracy, a classification report, and a confusion matrix.
