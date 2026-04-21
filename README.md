📊 K-Nearest Neighbors (KNN) Classification

📌 Overview
This project aims to classify data points into target classes using the K-Nearest Neighbors (KNN) algorithm. The model predicts the class of a data point based on the similarity (distance) to its nearest neighbors. The project includes data preprocessing, model training, evaluation, and optimization of the K value.

📂 Dataset
The dataset used in this project is:

KNN_Project_Data.csv

It contains multiple numerical features along with:

TARGET CLASS – Target variable (1 or 0)

🔍 Exploratory Data Analysis (EDA)
Data visualization was performed to understand patterns and relationships:

Pair plots to visualize relationships between features
Analysis of feature distribution
Observing class separation based on TARGET CLASS

⚙️ Data Preparation
Performed feature scaling using StandardScaler because KNN is distance-based

Selected all numerical features for training

Split dataset into:
Training set (70%)
Testing set (30%)

🤖 Model
Algorithm: K-Nearest Neighbors (KNN)
Library: Scikit-Learn

Initial parameter:
K = 1

Then optimized K value by testing values from 1 to 40

📈 Performance
Model performance improved after tuning:

K = 1 → Accuracy ≈ 72%
K = 30 → Accuracy ≈ 83%

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn

✅ Conclusion
The KNN model showed better performance after selecting the optimal K value. Feature scaling played a critical role in improving accuracy. Choosing the right K helps balance between overfitting and generalization.
