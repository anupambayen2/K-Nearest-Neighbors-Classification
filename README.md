Project Summary: Customer Purchase Prediction Using K-Nearest Neighbors (KNN)

This project applies the K-Nearest Neighbors (KNN) algorithm to predict whether a user will purchase a product based on social network advertisement data. This is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To classify whether a customer will buy a product using a distance-based algorithm that compares the new user to its nearest neighbors in the feature space.

📊 Dataset

Dataset used: Social_Network_Ads.csv

Features:

Age

Estimated Salary

Target:

Purchased (0 or 1)

This dataset works well for testing classification algorithms that rely on distance metrics.

🛠️ Steps Performed

Loaded and preprocessed the dataset

Selected features and target variable

Split dataset into training and test sets

Applied feature scaling (very important for KNN)

Trained the KNN classifier with chosen k value

Predicted purchase behavior for test data

Evaluated model performance using:

Confusion matrix

Accuracy score

Visualized decision boundaries

📈 Key Insight

KNN makes predictions based on the majority vote of the k nearest points.

Works well on this dataset when scaling is applied.

Decision boundary is non-linear, showing that KNN can capture complex patterns.

Performance depends heavily on the choice of k.

🧪 Outputs

Confusion matrix

Accuracy score

Decision boundary visualization

Predictions for test set

🚀 Conclusion

K-Nearest Neighbors is a simple yet powerful algorithm for classification when the dataset is small and scaling is applied.
It handles complex decision boundaries better than Logistic Regression but can be slower for large datasets.
