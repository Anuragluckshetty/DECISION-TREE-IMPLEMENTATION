# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIIONS

*NAME*: ANURAG LUCKSHETTY

*INTERN ID*: CTIS1612

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

##In this task, a Decision Tree classifier was implemented using the well-known Iris dataset to demonstrate a supervised machine learning classification technique. The Iris dataset is a standard dataset in machine learning and contains 150 instances of iris flowers belonging to three different species: Setosa, Versicolor, and Virginica. Each instance is described using four numerical features: sepal length, sepal width, petal length, and petal width. The objective of this task is to classify iris flowers into their respective species based on these feature values.

The dataset was first loaded using the scikit-learn library, which provides direct access to the Iris dataset. After loading the data, it was divided into two subsets: training data and testing data. Eighty percent (80%) of the dataset was used for training the model, while the remaining twenty percent (20%) was reserved for testing. This train-test split ensures that the model is evaluated on unseen data, which helps measure its generalization performance and prevents overfitting.

A Decision Tree classifier was then created and trained using the training dataset. Decision Trees work by recursively splitting the dataset based on feature values that best separate the target classes. At each node of the tree, a condition is applied to one of the features, such as petal length or sepal width, to divide the data into smaller subsets. The splitting process continues until a stopping condition is reached, such as achieving pure nodes or reaching the maximum depth of the tree. The model uses the Gini impurity measure to decide the best feature and threshold for splitting the data.

Once the model was trained, predictions were made on the test dataset. The accuracy of the model was calculated by comparing the predicted labels with the actual labels. The achieved accuracy indicates that the Decision Tree classifier performs well in classifying iris flower species. This demonstrates that the dataset is well-structured and that the chosen model is effective for this classification task.

An important part of this task is the visualization of the Decision Tree. The trained tree was visualized using the plot_tree function from scikit-learn along with Matplotlib. The visualization clearly shows how decisions are made at each node, including the feature used for splitting, the threshold value, the Gini impurity, the number of samples at each node, and the predicted class. Color coding was applied to the nodes to represent different classes and the confidence of predictions. This visual representation helps in understanding the internal working of the Decision Tree and makes the model more interpretable compared to many other machine learning algorithms.

In conclusion, this task successfully demonstrates the implementation of a Decision Tree classifier using the Iris dataset. The model achieves good accuracy, provides interpretable decision rules, and visually explains how classification decisions are made. This task highlights the simplicity, effectiveness, and explainability of Decision Trees in solving classification problems.
