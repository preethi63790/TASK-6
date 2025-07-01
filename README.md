 *Objective
To classify data using the K-Nearest Neighbors algorithm, experiment with different values of K, evaluate the model’s performance, and visualize decision boundarie
*Dataset
Iris dataset from sklearn.datasets.
Only 2 features (sepal length and sepal width) used for easier 2D visualization.
*3 classes:
Setosa, Versicolor, Virginica.
*Steps Performed:
Data Preprocessing:
Selected two features for 2D plotting.
Scaled features using StandardScaler.
Model Training:
Trained KNeighborsClassifier for multiple values of K (1, 3, 5, 7, 9).
Model Evaluation:
Evaluated each model using accuracy and confusion matrix.
Identified the best K based on highest test accuracy.
Visualization:
Plotted Accuracy vs. K to show performance trend.
Visualized decision boundaries using a mesh grid for the best K.

