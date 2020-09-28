---
layout: default
---

## Hello there, I'm Antoine!

I like **technology and collaborative projects**, I worked within two Horizon 2020 projects, EU Framework Programme for Research and Innovation. The overall objective is to create an innovative framework on ICT tools and services that can be deployed in cities to improve the health of the population in the urban context. 


**Embedded Systems Engineer**, I received a master's degree from ECE Paris and had the opportunity to share my time between Europe and Asia. I specialized in Internet-of-Things, playing around with electronics components and controllers.

Find some of my repositories:

- About my work in Singapore: https://github.com/antoinedme/experience-iot
- About Machine Learning workshop: https://github.com/antoinedme/titanic-dataset-ml

## How to deploy ICT projects in Singapore

Direct link to the poster: https://github.com/antoinedme/experience-iot/blob/master/README.md#poster-singapore-use-case

![Opening Antoine de Marasse](https://raw.githubusercontent.com/antoinedme/experience-iot/master/img/01-title.png) 

Workshop's contents:

1. [How do we keep our elders safe and well within the community?](https://github.com/antoinedme/experience-iot/blob/master/README.md#how-do-we-keep-our-elders-safe-and-well-within-the-community)
2. [Smart Living Framework](https://github.com/antoinedme/experience-iot/blob/master/README.md#smart-living-framework)
    1. [Ubiquitous Service MAnagement and Reasoning archiTecture](https://github.com/antoinedme/experience-iot/blob/master/README.md#ubiquitous-service-management-and-reasoning-architecture)
    2. [Ontology and Semantic Web](https://github.com/antoinedme/experience-iot/blob/master/README.md#ontology-and-semantic-web)
3. [Platform, services and Internet-of-Things](https://github.com/antoinedme/experience-iot/blob/master/README.md#platform-services-and-internet-of-things)
    1. [Creating pilot dashboard for health](https://github.com/antoinedme/experience-iot/blob/master/README.md#creating-pilot-dashboard-for-health)
    2. [Integrating Risk models](https://github.com/antoinedme/experience-iot/blob/master/README.md#integrating-risk-models)    
    3. [Data Plot and visualisations](https://github.com/antoinedme/experience-iot/blob/master/README.md#data-plot-and-visualisations)    
4. [Poster: Singapore use-case](https://github.com/antoinedme/experience-iot/blob/master/README.md#poster-singapore-use-case)

## How to learn Machine Learning in a fun way

Recently, I've started to study **Machine Learning** using Sci-kit Learn.
On of my latest fun work is applying Logistic Regression and Decision Tree on the RMS Titanic Dataset.

![Opening Antoine de Marasse](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/ressources/img/opening-image.png) 

Contents:
1. [History of the RMS Titanic passenger liner](https://github.com/antoinedme/titanic-dataset-ml#history-of-the-rms-titanic-passenger-liner)
2. [Exploring the Passengers dataset entries](https://github.com/antoinedme/titanic-dataset-ml#exploring-the-passengers-dataset-entries)
    1. [Analysing the data](https://github.com/antoinedme/titanic-dataset-ml#analysing-the-data) (more having a look and trying to analyse correlation of parameters and to plot simple stuffs)
    2. [Cleaning the data](https://github.com/antoinedme/titanic-dataset-ml#cleaning-the-data) (basic cleaning, no real process here)
    3. [Splitting the dataset for training and testing](https://github.com/antoinedme/titanic-dataset-ml#splitting-the-dataset-for-training-and-testing)
3. [Applying Logistic Regression](https://github.com/antoinedme/titanic-dataset-ml#applying-logistic-regression)
    1. [Evaluating the model](https://github.com/antoinedme/titanic-dataset-ml#evaluating-the-model)
    2. [What about Jack and Rose?](https://github.com/antoinedme/titanic-dataset-ml#what-about-jack-and-rose)
4. [Applying Decision Tree](https://github.com/antoinedme/titanic-dataset-ml#applying-decision-tree)
5. [Final remarks](https://github.com/antoinedme/titanic-dataset-ml#final-remarks) (wait, there's a surprise here!)

Directly access all the code on the Jupyter Notebook (Python): 

https://github.com/antoinedme/titanic-dataset-ml/blob/master/Titanic-MachineLearning.ipynb


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

![Logistics Regression](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/ressources/img/regression-illus.png)

Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.

```python
from sklearn import tree
```

Illustration of my output Decision Tree:

![Decision Tree](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/ressources/img/decision-tree-illustration.png)


## And the results are...

Let's create the data for our lovely couple (we will follow the structure: class, age, parents on board, fare, sex): Jack is on third class, around 27 years old, alone on board, only paid 8$ and is a male `jack = [3, 27, 0, 8, 1]`, and rose is on first class, around 22 years old, with family and paid 60$ `rose = [1, 22, 1, 60, 0]`.

![Results](https://raw.githubusercontent.com/antoinedme/titanic-dataset-ml/master/ressources/img/results.png)

Visit the Project for more fun:


[My Notebook:](https://github.com/antoinedme/titanic-dataset-ml) https://github.com/antoinedme/titanic-dataset-ml

Thank you!
Antoine

