KNN Project
Overview

This project applies the K-Nearest Neighbors (KNN) algorithm for classification using Python and Scikit-learn.

Dataset

KNN_Project_Data.csv
The dataset contains numerical features and a target column called TARGET CLASS.

Steps
Load the dataset using pandas
Perform basic data exploration (EDA)
Standardize the features using StandardScaler
Split the data into training and testing sets
Train the KNN model
Evaluate the model using confusion matrix and classification report
Test different K values to find the best one
Results

K = 1 → Accuracy ≈ 72%
K = 30 → Accuracy ≈ 83%

Technologies

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Conclusion

The model performance improved after choosing the optimal K value. Feature scaling and selecting the right K are important for KNN.
