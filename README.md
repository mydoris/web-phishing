# Detecting Phishing Websites based on SVM and Decision Tree
Support Vector Machine, Decision Tree and other machine learning techniques are applied to detect phishing websites using the dataset from UCI machine learning repository.

## How to run
**scikit-learn** is used as the machine learning tool. Jupyter notebook needs be installed to run the code interactively. Graphviz, a visualization software is also needed for plotting the decision tree. You can use Pip, homebrew or other tools to install these packages and softwares.

## Parameters tuning
The interactive notebook is pretty much self-explanatory. For the SVM model, linear kernel is used and C is set to 1.0. For the decision tree model, C4.5 algorithm is used and gini is the criteria by default.

## Evaluation
To avoid overfitting, 10-fold Cross Validation is performed to evaluate the estimator performance. The average accuracy for both model is calculated.

## Reference
Related paper, the dataset and a corresponding dataset feature specification are listed as well.
