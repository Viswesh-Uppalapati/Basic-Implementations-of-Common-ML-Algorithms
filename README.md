# Implementation of Common ML Algorithms From Scratch

This Repository contains basis implementations of commonly used ML algorithms from scratch. The files include:

1. **kNN.ipynb:** This Notebook contains a simple implementation of the **k-nearest neighbors** algorithm coded mainly using numpy and pandas for optimization. It includes time analysis on projected data for dimensionality reduction to see which value of k results in the best performance on the dimensionally reduced data and the original data.

2. **ID3_DecisionTreeClassifier.ipynb:** contains the implementation of a **Decision Tree Classifier using the ID3 algorithm**. All the functions for entropy and information gain used in the ID3 algorithm are written from scratch using numpy for optimization. There is a comparison of test errors before and after pruning of the ID3 algorithm. Pruning the tree results in a better test accuracy.

3. **Linear_Classification.ipyb:** contains the comparison between two different linear classification algorithms: **Perceptron** and **Logistic Regression using Gradient Descent**. Both algorithms are written from scratch and seem to perform similary on the train and test data after a certain number of iterations. The perception algorithm converges in about 3 to 4 passes while the Gradient Descent alternative takes around 100 iterations. The project also includes a **one vs. all** classifier for **multi-class classification** as well as a **confusion matrix** built on this classifier to see the classification accuracies and misclassifications in relation to each class.

The Data folder contains the data for each of the above algorithms and is sourced from CSE 151A: Intro to Machine Learning at The Univeristy of California at San Diego.
