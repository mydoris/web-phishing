# Detecting Phishing Websites based on SVM and Decision Tree
Support Vector Machine, Decision Tree and other machine learning techniques to detect phishing websites base on the dataset from UCI.

## How to run
Scikit-learn is used as the machine learning tool. Jupyter notebook needs be installed to run the code interactively. Graphviz is also needed to generate graph for plotting the decision tree. You can use Pip or other tools to install these packages.

## Tune the parameters
The interactive notebook is pretty much self-explanatory. For the SVM model, linear kernel is used and C is set to 1.0. For the decision tree model, C4.5 algorithm is used and gini is the criteria as default.

## Evaluation
To avoid overfitting, 10-fold validation is performed to evaluate the estimator performance. The average accuracy for both model is calculated.

## Reference
Related paper, the dataset and a corresponding dataset feature specification are listed as well.
