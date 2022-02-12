# Machine Learning 🧠

> Some Machine Learning algorithms and notes that I'm making while studying the field.

<p align="center">
  <img align="center" width="600" src="docs/imgs/machine_learning.jpeg" alt="Main Pic"/>
</p>

---

## Introduction 📈

Machine learning is a method of data analysis that automates analytical model building. It is a branch of artificial
intelligence based on the idea that systems can learn from data, identify patterns and make decisions with minimal human
intervention.

In machine learning, we create a model and try to predict the test data. There are two types of data:

- **Training data** - used to fit the model
- **Testing data** - used to test the model

Some machine learning algorithms:

- Linear Regression
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Support Vector Machine
- Naive Bayes Algorithm
- K-Means
- Random Forest Algorithm

---

### Linear Regression

Linear Regression is a machine learning algorithm based on supervised learning. Performs the task to predict a dependent
variable value (y) based on a given independent variable (x). So, this regression technique finds out a linear
relationship between x (input) and y(output).

Linear regression line equation: **y = a + bx**:

- x: explanatory variable (training data)
- y: dependent variable
- a: slope of the line (how much the y value increases for each x value)
- b: intercept (the value of y when x = 0)

<p align="center">
  <img align="center" width="600" src="docs/imgs/linear_regression.png" alt="Linear Regression"/>
</p>

---

### K-Nearest Neighbors (KNN)

KNN algorithm is used for classification and regression. Works by looking at the **K-closest points** to the given data
point
(the one we want to classify) and picking the class that occurs the most to be the predicted value.

However, the algorithm is computationally heavy, because requires the entire data set to make a prediction, and has a
high memory usage, because requires that the entire data set be loaded into memory.

<p align="center">
  <img align="center" width="600" src="docs/imgs/knn.png" alt="KNN"/>
</p>

---

### Support Vector Machine (SVM)

Support vector machines (SVMs) are a set of supervised learning methods used for classification, regression and outliers
detection. It's effective in high dimensional spaces (complicated data).

Divides data into multiple classes using a **hyper-plane**. A hyper plane is a fancy word for something that is
straight (e.g., line, plane) that can divide data points. To create a hyper-plane we need to pick two points known as
the **support vectors**; their distance to the plane must be identical, and they need to be the closest points to the
hyper-plane.

We choose the hyper-plane with the greatest possible **margin** (distance between points and plane). There are two types
of data:

- Hard margin: no points may exist inside the margin
- Soft margin: outliers may exist inside the margin
    - **hyper-parameter** is the amount of points allowed to exist inside the margin

**Kernels** provide a way for us to create a hyper-plane for "unorganized" data, bring it up to a higher dimension (in
this case from 2D→3D). There are several kernel options:

- Linear
- Polynomial
- Circular
- Hyperbolic Tangent (Sigmoid)

More info about SVMs [here](https://scikit-learn.org/stable/modules/svm.html#).

<p align="center">
  <img align="center" width="600" src="docs/imgs/svm.png" alt="SVMs"/>
</p>

---

## Author Info

- LinkedIn - [André Jesus](https://www.linkedin.com/in/andre-jesus-engineering)
- Twitter - [@andre_j3sus](https://twitter.com/andre_j3sus)
- Website - [André Jesus](https://sites.google.com/view/andre-jesus/p%C3%A1gina-inicial)