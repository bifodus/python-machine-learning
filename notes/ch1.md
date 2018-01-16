# Giving Computers the Ability to Learn from Data

## Building intelligent machines to transform data into knowledge
Machine learning evolved as a subfield of artificial intelligence that involved the development of self-learning algorithms to gain knowledge from that data in order to make predictions.

## The three different types of machine learning

### Making predictions about the future with supervised learning
The main goal in supervised learning is to learn a model from labeled training data that allows us to make predictions about unseen or future data.  *Supervised* refers to a set of samples where the desired output signals (labels) are already known.

A supervised learning task with discrete *class labels* is also called a *classification* task.

Another subcategory of supervised learning is *regression*, where the outcome signal is a continuous value.

### Classification for predicting class labels
Classification is a subcategory of supervised learning where the goal is to predict the categorical class labels of new instances based on past observations.

The predictive model learned by a supervised learning algorithm can assign any class label that was presented in the training dataset to a new, unlabeled instance

### Regression for predicting continuous outcomes
In *regression analysis*, we are given a number of *predictor* (explanatory) variables and a continuous response variable (outcome), and we try to find a relationship between those variables that allows us to predict an outcome.

With *linear regression*, when we are given a predictor variable *x* and a response variable *y*, we fit a straight line to the data that minimizes the distance between the sample points and the fitted line.  We can then use the intercept and slope to predict the outcome variable of new data.

### Solving interactive problems with reinforcement learning
In reinforcement learning, the goal is to develop a system (agent) that improves its performance based on interactions with the *environment*.

### Discovering hidden structures with unsupervised learning
In unsupervised learning, we are dealing with unlabeled data or data of *unknown structure*.  Using unsupervised learning techniques, we are able to explore the structure of our data to extract meaningful information without the guidance of a known outcome variable or reward function.

### Finding subgroups with clustering
*Clustering* is an exploratory data analysis technique that allows us to organize a pile of information into meaningful subgroups (*clusters*) without having any prior knowledge of their group memberships.  This is sometimes called "unsupervised classification."

### Dimensionality reduction for data compression
Unsupervised dimensionality reduction is a commonly used approach in feature preprocessing to remove noise from data, which can also degrade the predictive performance of certain algorithms, and compress the data onto a smaller dimensional subspace while retaining most of the relevant information.

### Preprocessing - getting data into shape
To determine whether our machine learning algorithm not only performs well on the training set but also generalizes well to new data, we want to randomly divide the dataset into a separate training and test set.  We use the training set to train and optimize our machine learning model, while we keep the test set until the very end to evaluate the final model.

### Training and selecting a predictive model
Each classification algorithm has its inherent biases, and no single classification model enjoys superiority if we don't make any assumptions about the task.  One commonly used metric to compare models is classification accuracy.

### Using Python for machine learning
For machine learning programming tasks, we will mostly refer to the *scikit-learn* library, which is one of the most popular and accessible open source machine learning libraries as of today.

### Installing Python packages
install package: `pip install SomePackage`
upgrade package: `pip install SomePackage --upgrade`

Anaconda is a free enterprise-ready Python distribution that bundles all the essential Python packages for data science, math, and engineering in one user-friendly cross-platform distribution.

After installing Anaconda:
install package: `conda install SomePackage`
upgrade package: `conda update SomePackage`

We will mainly use NumPy's multi-dimensional arrays to store and manipulate data.  Occasionally we will use *pandas* which provides additional higher level data manipulation tools.  To visualize data, we will use the *matploglib* library.
