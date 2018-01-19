# Training Machine Learning Algorithms for Classification

## Artificial neurons - a brief glimpse into the early history of machine learning

Rosenblatt's initial perceptron rule can be summarized in the following steps
* 1. Initialize the weights to 0 or small random numbers.
* 2. For each training sample x^(i) perform the following steps:
** 1. Compute the output value y
** 2. Update the weights

The convergence of the perceptron is only guaranteed if the two classes are linearly separable and the learning rate is sufficiently small.

### Implementing a perceptron learning algorithm in Python
See snippets

### Training a perceptron model on the Iris dataset
See snippets

### Adaptive linear neurons and the convergence of learning
The Adaline algorithm is interesting because it illustrates the key concept of defining and minimizing cost functions, which will lay the groundwork for understanding more advanced machine learning algorithms for classification, such as logistic regression and support vector machines, as well as regression models that we will discuss in future chapters.

The key difference between the Adaline rule and the perceptron is that the weights are updated based on a linear activation function rather than a unit step function.

### Minimizing cost functions with gradient descent
One of the key ingredients of supervised machine learning algorithms is to define an *objective function* that is to be optimized during the learning process.  This objective function is often a *cost function* that we want to minimize.  In the case of Adaline, we define the cost function as the sum of squared errors between the calculated outcome and the true class label.

The main advantage of the continuous linear activation function (instead of the unit step function) is that the cost function becomes differentiable.  Another nice property is that it is convex, and so we can use an optimization algorithm called *gradient descent* to find the weights that minimize our cost function.

### Implementing an Adaptive Linear Neuron in Python
See snippets