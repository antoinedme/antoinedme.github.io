---
layout: default
---

Recently, I've started to study **Machine Learning** using Sci-kit Learn.

On of my latest fun work is applying Logistic Regression and Decision Tree on the RMS Titanic Dataset.

![Opening Image](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/img/opening-image.png)

[Link to the Titanic Machine Learning Notebook](https://github.com/antoinedme/titanic-dataset-ml).

## ML models and Python packages

Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist.

```python
from sklearn import linear_model
from sklearn.linear_model import LogisticRegression
```

In contrast to linear regression, logistic regression does not produce an 𝑅2 score by which we can assess the accuracy of our model. In order to evaluate that, we will use a classification report, a confusion matrix, and the accuracy score. We import the related tools from sklearn.metrics.

```python
from sklearn.metrics import classification_report, confusion_matrix, accuracy_score
```
Illustration of my Logistics Regression model:

![Logistics Regression](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/img/regression-illus.png)

Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.

```python
from sklearn import tree
```

Illustration of my output Decision Tree:

![Decision Tree](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/img/decision-tree-illustration.png)


## Results

Let's create the data for our lovely couple (we will follow the structure: class, age, parents on board, fare, sex): Jack is on third class, around 27 years old, alone on board, only paid 8$ and is a male `jack = [3, 27, 0, 8, 1]`, and rose is on first class, around 22 years old, with family and paid 60$ `rose = [1, 22, 1, 60, 0]`.

![Results](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/img/results.png)




Visit the Project for more fun:


[My Notebook:](https://github.com/antoinedme/titanic-dataset-ml) https://github.com/antoinedme/titanic-dataset-ml

Thank you!
Antoine

