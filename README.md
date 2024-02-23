Sorting Project

This project aims to sort fruits based on their features such as mass, width, height, and color score. The project uses Python and several libraries such as pandas, matplotlib, seaborn, and sklearn.

Data

The data used for this project is the fruit.txt file, which contains 59 samples of fruits with 7 features each. The features include the fruit name, fruit subtype, mass, width, height, color score, and fruit label. The fruit label is a numerical value that corresponds to the fruit name.

The data is loaded and explored using pandas and matplotlib. The number of samples for each fruit name is printed. A scatter matrix is plotted to show the pairwise relationship between the features.

Preprocessing

The data is split into features (X) and target (y) variables. The features are the mass, width, height, and color score columns. The target is the fruit label column.

The features are normalized by using a MinMaxScaler, which scales the data to the range [0, 1]. The data is then split into training and testing sets, with 75% of the data for training and 25% for testing. The random_state parameter is set to 0 to ensure reproducibility of the results.

Model

The models used for this project are four different classifiers: Logistic Regression, Decision Tree, K-Nearest Neighbors, and Support Vector Machine. These models are imported from the sklearn module and instantiated with the default parameters.

The models are fitted on the training data and used to make predictions on the testing data. The accuracy of the models is evaluated by comparing the predicted labels with the true labels. The accuracy scores for the training and testing sets are printed for each model.

Results

The results of the models are as follows:

- Logistic Regression: The accuracy on the training set is 0.70 and on the test set is 0.47.
- Decision Tree: The accuracy on the training set is 1.00 and on the test set is 0.87.
- K-Nearest Neighbors: The accuracy on the training set is 0.95 and on the test set is 1.00.
- Support Vector Machine: The accuracy on the training set is 0.92 and on the test set is 0.80.

The best model for this project is the K-Nearest Neighbors, which achieved a perfect accuracy on the test set. The worst model is the Logistic Regression, which had a low accuracy on both the training and test sets. The Decision Tree and the Support Vector Machine had good accuracy scores, but they were slightly overfitting the training data.
