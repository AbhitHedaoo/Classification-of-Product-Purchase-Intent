# **K-Nearest Neighbors (K-NN) Classification**

**Overview** - This repository contains a Python script that demonstrates the implementation of the K-Nearest Neighbors (K-NN) algorithm for classification. K-NN is a simple and effective supervised learning algorithm used for both classification and regression tasks.

**Dataset** - The dataset used in this script is obtained from the file Social_Network_Ads.csv. It contains information about users' age, estimated salary, and whether they purchased a product (Purchased).

**Implementation** : 

**Loading Dataset:** The dataset is loaded from the CSV file using the Pandas library.

**Data Preprocessing**:
- The features (Age and Estimated Salary) and target variable (Purchased) are extracted from the dataset.
- The dataset is split into training and test sets using the train_test_split function from the scikit-learn library.
- Feature scaling is performed to standardize the features using the StandardScaler from scikit-learn.

**Fitting K-NN Model**: The K-Nearest Neighbors classifier is initialized with parameters such as the number of neighbors, distance metric, and power parameter for the Minkowski metric. The classifier is trained on the training set using the fit method.

**Making Predictions:** Predictions are made on the test set using the predict method of the trained classifier.

**Confusion Matrix:** The confusion matrix is computed to evaluate the performance of the classifier.

**Visualizing Results:** - The decision boundary for the K-NN classifier on both the training and test sets is visualized using contour plots. This visualization helps in understanding how the model separates the classes based on the features "Age" and "Estimated Salary".
