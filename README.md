# Classifier-task-

## Installation

Use the package manager pip to install Required Packages.
```python
pip install pandas
pip install numpy
pip install seaborn
```
Machine Learning Library for Classifiers and classification_report.
```python
pip install scikit-learn
```
## Explanation 
the data was non-linear so that used non-linear classifiers, 
in this i used KNN and GradientBossting classifiers to implement the code.

i have created error rate function which can estimate and find out best n_neighbors value for good accuracy, 
using graph of Error Rate vs neighbors find out best neighbors for the KNN classifier.

used
```python 
pip install matplotlib
```
to create the graph, used __import matplotlib.pyplot as plt__.

__from sklearn.metrics import confusion_matrix,classification_report__ created confusion matrix which 
gaves me Accuracy, Precision, Recall and F1-score.

[Reference](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning)



