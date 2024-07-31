---
title: "Machine Learning with Pytorch and Scikit-Learn"
draft: false
ShowToc: true
date: 2024-03-01
tags: ["books", "ml"]
author: Carlos L.
---

# 1. Giving Computers the Ability to Learn from Data

Machine Learning is a sub-field of AI, consisting of algorithms capable of learning from data. This allows us humans not to have to explicitly tell the computer/machine what to do.

## Types of ML

### Supervised
- Labeled data
- Direct feedback
- Predict future

### Unsupervised
- No Labels/targets
- No feedback
- Find hidden structure

### Reinforcement
- Decision process
- Reward system
- Learn series of actions

## Supervised

We use data with labels, for example, a dataset with a column containing records made by humans to indicate whether a message is spam or not.

**Classification** is a type of Supervised learning and consists of obtaining an output that can be binary (yes/no or spam/not-spam) or multi-class (winter, summer, autumn).

**Regression** consists of obtaining a numerical result at the output: temperature, age, or property value.

## Reinforcement

In reinforcement learning, a model is trained to improve its performance through interaction with the environment.

An example is the game of Chess.

## Unsupervised Learning

In supervised learning, we know the correct answer; in unsupervised learning, we do not.

**Clustering** is a technique that allows finding patterns in data (sub-groups).

**Dimensionality reduction** condenses information from the dataset and eliminates what is not relevant.

## Cross-Validation

Cross-Validation helps in verifying the effectiveness of a model without having to use the test set.

## Hyperparameter Optimization

Hyperparameter optimization exists because, by default, the model parameters may not be ideal for our specific problem.

# 2. Training Simple Machine Learning Algorithms for Classification

The **Perceptron** is a binary classifier with two characteristics:
- The weights are initialized randomly.
- For each example, the weights and bias are updated.

[Adaline](https://medium.com/ensina-ai/rede-neural-perceptron-adaline-8f69dc419d4e) teaches about continuous minimization of the cost function.

In Adaline, it is proposed to include an error signal block to modify the weight values before submitting to the activation function (g).

Adaline compares the correct value for the input with the linear function and updates the weights and corrects the error; the perceptron compares the original value with the predicted value to update the weights.

Adaline emerged as a solution to the fact that the Perceptron did not handle the (XOR) problem well, i.e., non-linearly separable data.

The Adaline neuron inaugurates the use of an algorithm to reduce the cost function (L) called Gradient Descent.

### Gradient Descent

Imagine you are on top of a mountain; Gradient Descent would be like trying to reach the lowest possible point (descending the mountain).

### Scaling

Scaling allows for better results when using Gradient Descent.

Scaling is useful because it keeps the weights within the same range of values. Imagine, on the other hand, features that are out of scale, where one weight is 10 times larger than another (for example), which disrupts the Gradient Descent process.

### Large-scale Machine Learning and Stochastic Gradient Descent

Gradient Descent updates weights based on the sum of errors in relation to all training examples, \(x_i\).

The downside is that if our dataset is extensive, this can take a considerable amount of time. Therefore, an alternative is Stochastic Gradient Descent (SGD).

SGD updates weights for each example, resulting in faster convergence compared to GD.

# 3. A Tour of Machine Learning Classifiers Using Scikit-Learn

A summary for training a supervised machine learning model could be:

1. **Select features**
2. **Choose a metric**
3. **Select the algorithm and train the model**
4. **Evaluate the algorithm's performance**
5. **Adjust the model's parameters and fine-tune it**

Finding an efficient learning rate involves testing because if the eta is too large, the model may "jump" over the global minimum. On the other hand, if it's too small, it may take longer to converge, which implies more processing.

The major disadvantage of the Perceptron (besides the limitation of not being able to be used for data with multiple targets/outputs) is that there is no convergence if the data is not linearly separable.

## Tackling Overfitting via Regularization

Overfitting is an inherent problem in machine learning models that occurs when they fail to make accurate predictions on data other than the training data. When this happens, the model is said to have high variance, often due to the large number of parameters.

Underfitting, on the other hand, occurs when the model fails to capture the patterns in the data, resulting in poor performance on unseen data (test data).

### The Bias-Variance Tradeoff

In the machine learning literature, the terms "high variance" and "high bias" refer to overfitting and underfitting, respectively. The model's variance refers to the consistency with which it classifies a class correctly each time the dataset is retrained, while bias refers to the error (how far the model's prediction is from the true value) in each of these instances.

Regularization is a method capable of preventing high variance by eliminating noise (irrelevant information) from the data. It involves adding information to the data to penalize extreme values.

### Regularization and Feature Normalization

For regularization to be effective, the data must be on the same scale. The parameter λ represents the strength of the regularization; the larger the value, the stronger the regularization. It is common for bias not to be regularized; instead, the weight is adjusted.

In the context of the Support Vector Machine (SVM) model, the term C is inversely proportional to regularization; decreasing C increases regularization. However, caution is needed when using regularization, as it can lead to underfitting.

## Maximum Margin Classification with Support Vector Machines

Support Vector Machine (SVM) is another machine learning algorithm, inspired by the Perceptron. Unlike the Perceptron, which minimizes misclassifications, SVM maximizes the margin. The margin is defined as the distance between the decision boundary and the closest data points (support vectors).

## Maximum Margin Intuition

The larger the margin, the lower the generalization error (the likelihood of the model becoming too complex or too simple and not performing well on unseen data). Smaller margins are associated with a higher likelihood of generalization error.

**Generalization Error**: This refers to the possibility of the model not learning the data patterns properly or learning them too well, which can lead to overfitting (learning too well) or underfitting (not learning well enough).

The mathematics behind the concept of maximum margin is not trivial and requires parallel studies alongside books for a deeper understanding of the topic.

Models with smaller margins are more vulnerable to overfitting, meaning they are more likely to perform poorly on test data.

## Dealing with a Nonlinearly Separable Case Using Slack Variables**

In 1995, W. Vapnik proposed the concept of slack variables, which led to the idea of soft-margin classification.

The motivation for slack variables arose from the need for greater flexibility in the SVM model in situations where data were not linearly separable, allowing for convergence even in cases where there are classification errors, with a penalty for these errors.

Slack variables are represented by the parameter \( C \). A higher value of \( C \) means we are less tolerant of error (more punishment), while a lower value means more tolerance (less punishment).

We can use the value of \( C \) to control the bias-variance tradeoff, which regulates how well the model learns the data patterns.

This idea is related to the concept of regularization, meaning that higher values of \( C \) increase bias (underfitting) and reduce variance (overfitting).
